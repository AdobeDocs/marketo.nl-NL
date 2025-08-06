---
description: Aanvullende informatie voor Dynamic Chat - Documentatie voor Marketo - Productdocumentatie
title: Aanvullende informatie over Dynamic Chat
feature: Release Information, Dynamic Chat
hide: true
hidefromtoc: true
exl-id: 0a7e5cc9-f2a6-4721-bbdc-661249a2e2b6
source-git-commit: 21bcdc10fe1f3517612efe0f8e2adaf2f4411a70
workflow-type: tm+mt
source-wordcount: '900'
ht-degree: 2%

---

# Aanvullende informatie over Dynamic Chat {#dynamic-chat-release}

De versies van Adobe Dynamic Chat werken op een ononderbroken leveringsmodel dat voor een scalable benadering van eigenschapplaatsing toestaat. Soms zijn er meerdere releases per maand, dus raadpleeg je regelmatig voor de meest actuele informatie.

De standaardpagina van de Nota&#39;s van de Versie voor Marketo Engage [ kan hier ](/help/marketo/release-notes/current.md){target="_blank"} worden gevonden.

## Release van juni 2025 {#june-2025-release}

### Logica Revamp routeren {#routing-logic-revamp}

Wij hebben de levende praatje verpletterend logica in Dynamic Chat vernieuwd om intelligenter en voorspelbaarder betrokkenheidsgedrag over alle verpletterende types (Rekening, Douane, Team, en Round Robin) te verzekeren. De nieuwe logica vereenvoudigt het verpletteren van stromen en verbetert reservebehandeling wanneer de agenten niet beschikbaar zijn.

#### Zeer belangrijke Verbeteringen in het Verpletteren van Gedrag

* **tot twee verbindingspogingen per zitting**

   * Het systeem zal proberen om met maximaal twee agenten (hoogstens) te verbinden, maar strikt binnen de primaire verpletterende regel.

   * Als een agent beschikbaar is maar niet antwoordt (b.v., leidt of mist de praatje), zal het systeem proberen om met een verschillende agent van de zelfde pool te verbinden.

   * De fallback-logica (zoals Round Robin) wordt alleen geactiveerd als er geen in aanmerking komende agents zijn gevonden tijdens de eerste resolutie, niet om het opnieuw te proberen na een mislukte betrokkenheid.

* **Verpletterend regel-Specifiek Gedrag**

_&#x200B;**Verpletterende Rekening**&#x200B;_

Als het e-maildomein van een bezoeker wordt toegewezen aan een bekende account, krijgt de toegewezen agent altijd de prioriteit.

Als de agent beschikbaar is, wordt het praatje verpletterd aan hen direct.

Als de agent niet beschikbaar is, het systeem:

* Probeert geen andere agent, zelfs als Round Robin is ingeschakeld als fallback.

* In plaats daarvan:

   * Toont de vergaderingskalender van de in kaart gebrachte agent (als toegelaten),
-of-
   * Hiermee keert u terug naar een standaardbericht (worst case).

De kaart-vlakke verpletterende regel (b.v. Team, Douane) wordt slechts overwogen als het Verpletteren van de Rekening niet in aanmerking komt (geen passend domein of agent).

_&#x200B;**Douane/Team die**&#x200B;_ verplettert

Deze regels kunnen meerdere in aanmerking komende agenten teruggeven.

Als de eerste beschikbare agent niet in dienst neemt, zal het systeem één meer agent van de zelfde lijst proberen.

Round Robin fallback wordt niet geactiveerd alleen omdat één agent niet reageert.

Als geen van beide agenten aangaat:

* Het systeem toont de agenda van de eerste beproefde agent (indien toegelaten),
-of-
* Hiermee geeft u het standaardfallback-bericht weer.

_&#x200B;**Rond Robin die**&#x200B;_ verplettert

Wanneer gebruikt als primaire verpletterende regel, het systeem:

* Probeert de eerste beschikbare agent van de ronde robin pool in dienst te nemen.

* Als de eerste agent niet antwoordt, probeert het met de volgende beste geschikte agent opnieuw.

Als Round Robin wordt gebruikt als fallback, wordt deze alleen geactiveerd als er geen agents zijn gevonden op basis van de primaire regel.

_&#x200B;**de Stroom van de Ervaring van de Bezoeker**&#x200B;_

Het systeem controleert of het Verpletteren van de Rekening toepasselijk is.

* Als ja en de agent beschikbaar is, verbindt het onmiddellijk.

* Als de agent niet in aanmerking komt of niet beschikbaar is, gaat het aan kaart-niveau dat regel verplettert.

De kaart-vlakke verpletterende regel (Douane, Team, Ronde Robin) wordt geëvalueerd.

* De in aanmerking komende agenten worden gecontroleerd op beschikbaarheid (toestemmingen, status).

* Het systeem treedt één agent in dienst, en probeert indien nodig, een tweede agent van de zelfde regel.

* Als geen betrokkenheid slaagt, wordt fallback-logica toegepast:

   * terugvaldatum kalender (indien ingeschakeld),
-of-
   * Standaardbericht.

De ronde reserve van Robin wordt slechts overwogen wanneer geen in aanmerking komende agenten van de primaire verpletterende regel worden gevonden, niet wanneer de individuele agenten er niet in slagen te antwoorden.

##### Gebruiksscenario’s {#use-cases}

_&#x200B;**Verpletterende Rekening**&#x200B;_

<table><thead>
  <tr>
    <th>Type</th>
    <th>Voorbeeld</th>
    <th>Resultaat</th>
  </tr></thead>
<tbody>
  <tr>
    <td>Ideaal</td>
    <td>De domeinkaarten van de bezoeker aan een rekening; de in kaart gebrachte agent heeft toegelaten levende praatje en is beschikbaar</td>
    <td>Chat maakt rechtstreeks verbinding met de toegewezen agent</td>
  </tr>
  <tr>
    <td>Fallback (Round Robin)</td>
    <td>Toegewezen agent is niet beschikbaar, Round Robin fallback is ingeschakeld</td>
    <td>Het systeem selecteert één beschikbare agent via Round Robin en verbindt hen </td>
  </tr>
  <tr>
    <td>Geen valagent</td>
    <td>De toegewezen agent is niet beschikbaar, geen Round Robin fallback; het boeken van de vergadering wordt toegelaten</td>
    <td>Het systeem toont in kaart gebrachte agentenkalender of toont een standaardreservebericht</td>
  </tr>
</tbody></table>

_&#x200B;**Douane Verpletterend**&#x200B;_

<table><thead>
  <tr>
    <th>Type</th>
    <th>Voorbeeld</th>
    <th>Resultaat</th>
  </tr></thead>
<tbody>
  <tr>
    <td>Ideaal</td>
    <td>De logica van de douane lost een lijst van agenten op; de eerste agent is beschikbaar en keurt praatje goed.</td>
    <td>Chat verbindt met de eerste agent.</td>
  </tr>
  <tr>
    <td>Fallback (Round Robin)</td>
    <td>De regel van de douane lost geen agenten op, wordt de Round Robin fallback toegelaten.</td>
    <td>Het systeem selecteert één beschikbare agent via Round Robin en verbindt hen.</td>
  </tr>
  <tr>
    <td>Geen valagent</td>
    <td>Twee agenten opgelost; noch keurt praatje goed, reserve die aan vergaderingskalender wordt geplaatst.</td>
    <td>De agenda van de eerste beproefde agent wordt getoond of het standaardreservebericht wordt getoond.</td>
  </tr>
</tbody></table>

_&#x200B;**Team dat**&#x200B;_ verplettert

<table><thead>
  <tr>
    <th>Type</th>
    <th>Voorbeeld</th>
    <th>Resultaat</th>
  </tr></thead>
<tbody>
  <tr>
    <td>Ideaal</td>
    <td>Het team omvat agenten met levende praatje; de eerste beschikbare agent keurt de chat goed.</td>
    <td>Chat verbindt met die agent.</td>
  </tr>
  <tr>
    <td>Fallback (Round Robin)</td>
    <td>Er is geen teamagent beschikbaar en Round Robin fallback is ingeschakeld.</td>
    <td>Het systeem selecteert en verbindt met één agent van Round Robin pool.</td>
  </tr>
  <tr>
    <td>Geen valagent</td>
    <td>Twee beschikbare agenten, maar geen van beiden verbindt; de terugval van de kalender toegelaten.</td>
    <td>Het eerste beproefde kalender van de agent wordt getoond of het reservebericht wordt teweeggebracht.</td>
  </tr>
</tbody></table>

_&#x200B;**Rond Robin die**&#x200B;_ verplettert

<table><thead>
  <tr>
    <th>Type</th>
    <th>Voorbeeld</th>
    <th>Resultaat</th>
  </tr></thead>
<tbody>
  <tr>
    <td>Ideaal</td>
    <td>Round Robin-pool heeft meerdere agents; de tweede agent accepteert chat nadat dit niet het geval is.</td>
    <td>Chat verbindt met tweede agent.</td>
  </tr>
  <tr>
    <td>Fallback (Round Robin)</td>
    <td>Geen agenten beschikbaar in de Ronde Groep van Robin; vergaderingskalender wordt toegelaten.</td>
    <td>De kalender wordt getoond voor eerste agent in de lijst (indien gevormd), of het terugvalbericht getoond.</td>
  </tr>
  <tr>
    <td>Geen valagent</td>
    <td>Geen beschikbare agenten; fallback wordt onbruikbaar gemaakt.</td>
    <td>Het statische terugvalbericht wordt getoond aan de bezoeker.</td>
  </tr>
</tbody></table>

### Pulsmelding {#pulse-notification}

Wanneer een bezoeker om met een agent verzoekt te verbinden, verstrekken wij in-app, browser bericht aan de agent. Maar soms missen agenten deze chats.

Met deze release krijgt de live agent een e-mail, Slack, in-app en browsermelding wanneer een nieuwe bezoeker geïnteresseerd is in chatten.

1. Voor uw homepage van Adobe Experience Cloud, klik het pictogram van de Rekening en selecteer **Voorkeur**.

   ![](assets/dynamic-chat-june-2025-release-1.png)

1. De rol neer aan _Berichten_ en maakt uw gewenste selecties van Dynamic Chat.

   ![](assets/dynamic-chat-june-2025-release-2.png)

>[!NOTE]
>
>Inhoud voor een Pulse-melding kan hetzelfde zijn als de inhoud voor browsermeldingen in de app.
