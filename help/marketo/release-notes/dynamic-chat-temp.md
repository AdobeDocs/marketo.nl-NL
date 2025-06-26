---
description: Aanvullende informatie voor Dynamic Chat - Documentatie voor Marketo - Productdocumentatie
title: Aanvullende informatie over Dynamic Chat
feature: Release Information, Dynamic Chat
hide: true
hidefromtoc: true
source-git-commit: ce7142e471271dfb33b265e226b67bcc3b35594b
workflow-type: tm+mt
source-wordcount: '710'
ht-degree: 3%

---

# Aanvullende informatie over Dynamic Chat {#dynamic-chat-release}

De versies van Adobe Dynamic Chat werken op een ononderbroken leveringsmodel dat voor een scalable benadering van eigenschapplaatsing toestaat. Soms zijn er meerdere releases per maand, dus raadpleeg je regelmatig voor de meest actuele informatie.

De standaardpagina van de Nota&#39;s van de Versie voor Marketo Engage [ kan hier ](/help/marketo/release-notes/current.md){target="_blank"} worden gevonden.

## Release van juni 2025 {#june-25-release}

### Logica Revamp routeren {#routing-logic-revamp}

Wij hebben de levende praatje verpletterend logica in Dynamic Chat vernieuwd om intelligenter en voorspelbaarder betrokkenheidsgedrag over alle verpletterende types (Rekening, Douane, Team, en Round Robin) te verzekeren. De nieuwe logica vereenvoudigt het verpletteren van stromen en verbetert reservebehandeling wanneer de agenten niet beschikbaar zijn.

#### Zeer belangrijke Verbeteringen in het Verpletteren van Gedrag

* **tot twee verbindingspogingen per zitting**

   * Het systeem zal proberen om met hoogstens twee agenten, maar strikt binnen de primaire verpletterende regel te verbinden.

   * Als een agent beschikbaar is maar niet antwoordt (b.v., vermindert of mist), zal het systeem een tweede agent van de zelfde pool proberen.

   * De fallback-logica (zoals Round Robin) wordt alleen geactiveerd als er geen in aanmerking komende agents zijn gevonden tijdens de eerste resolutie — niet om het opnieuw te proberen na een mislukte betrokkenheid.

* **Verpletterend regel-Specifiek Gedrag**

_&#x200B;**Verpletterende Rekening**&#x200B;_

Als het e-maildomein van een bezoeker wordt toegewezen aan een bekende account, krijgt de toegewezen agent altijd de prioriteit.

Als de agent beschikbaar is, wordt het praatje verpletterd aan hen direct.

Als de agent niet beschikbaar is, het systeem:

Probeert geen andere agent, zelfs als Round Robin is ingeschakeld als fallback.

In plaats daarvan:

toont de vergaderingkalender van de in kaart gebrachte agent (indien toegelaten), of

Hiermee keert u terug naar een standaardbericht (worst case).

De kaart-vlakke verpletterende regel (b.v. Team, Douane) wordt slechts overwogen als het Verpletteren van de Rekening niet in aanmerking komt (geen passend domein of agent).

_&#x200B;**Douane/Team die**&#x200B;_ verplettert

Deze regels kunnen meerdere in aanmerking komende agenten teruggeven.

Als de eerste beschikbare agent niet in dienst neemt, zal het systeem één meer agent van de zelfde lijst proberen.

Round Robin fallback wordt niet geactiveerd alleen omdat één agent niet heeft gereageerd.

Als geen van beide agenten aangaat:

Het systeem toont de agenda van de eerste beproefde agent (als toegelaten), of

Hiermee geeft u het standaardfallback-bericht weer.

_&#x200B;**Rond Robin die**&#x200B;_ verplettert

Wanneer gebruikt als primaire verpletterende regel, het systeem:

Probeert de eerste beschikbare agent van de ronde robin pool in dienst te nemen.

Als eerste niet antwoordt, probeert het met de volgende beste geschikte agent opnieuw.

Als Round Robin wordt gebruikt als fallback, wordt deze alleen geactiveerd als er geen agents zijn gevonden op basis van de primaire regel.

**de Stroom van de Ervaring van de Bezoeker**

Het systeem controleert als de Verplettering van de Rekening toepasselijk is.

Indien ja en agent beschikbaar is → maakt onmiddellijk verbinding.

Als niet in aanmerking komend of agent niet beschikbaar → opbrengst aan kaart-niveau het verpletteren regel.

De kaart-vlakke verpletterende regel (Douane, Team, Ronde Robin) wordt geëvalueerd.

De in aanmerking komende agenten worden gecontroleerd op beschikbaarheid (toestemmingen, status).

Het systeem treedt één agent in dienst, en probeert indien nodig, een tweede agent van de zelfde regel.

Als geen overeenkomst slaagt → wordt de fallback logica toegepast:

terugvaldatum kalender (indien ingeschakeld), of

Standaardbericht.

De ronde Robin fallback wordt slechts overwogen wanneer geen in aanmerking komende agenten van de primaire verpletterende regel worden gevonden — niet wanneer de individuele agenten er niet in slagen om te antwoorden.

**Gevallen van het Gebruik**

Account routeren

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

Aangepaste routering

<table><thead>
  <tr>
    <th>Type</th>
    <th>Voorbeeld</th>
    <th>Resultaat</th>
  </tr></thead>
<tbody>
  <tr>
    <td>Ideaal</td>
    <td>TEXT</td>
    <td>TEXT</td>
  </tr>
  <tr>
    <td>Fallback (Round Robin)</td>
    <td>TEXT</td>
    <td>TEXT</td>
  </tr>
  <tr>
    <td>Geen valagent</td>
    <td>TEXT</td>
    <td>TEXT</td>
  </tr>
</tbody></table>

Team dat verplettert

<table><thead>
  <tr>
    <th>Type</th>
    <th>Voorbeeld</th>
    <th>Resultaat</th>
  </tr></thead>
<tbody>
  <tr>
    <td>Ideaal</td>
    <td>TEXT</td>
    <td>TEXT</td>
  </tr>
  <tr>
    <td>Fallback (Round Robin)</td>
    <td>TEXT</td>
    <td>TEXT</td>
  </tr>
  <tr>
    <td>Geen valagent</td>
    <td>TEXT</td>
    <td>TEXT</td>
  </tr>
</tbody></table>

Round Robin-routering

<table><thead>
  <tr>
    <th>Type</th>
    <th>Voorbeeld</th>
    <th>Resultaat</th>
  </tr></thead>
<tbody>
  <tr>
    <td>Ideaal</td>
    <td>TEXT</td>
    <td>TEXT</td>
  </tr>
  <tr>
    <td>Fallback (Round Robin)</td>
    <td>TEXT</td>
    <td>TEXT</td>
  </tr>
  <tr>
    <td>Geen valagent</td>
    <td>TEXT</td>
    <td>TEXT</td>
  </tr>
</tbody></table>

### Pulsmelding {#pulse-notification}

Wanneer een bezoeker om met een agent verzoekt te verbinden, vandaag verstrekken wij in-app, browser bericht aan de agent, maar de agenten ontbreken vaak deze hoofdstukken.

* Live agent ontvangt nu een e-mail, Slack, Inapp, browsermelding wanneer een nieuwe bezoeker geïnteresseerd is in chatten

* Inhoud voor pulsmeldingen kan hetzelfde zijn als wat we vandaag gebruiken voor meldingen in apps, browsers

Het gedrag zou het zelfde als huidig voor agent moeten zijn om goed te keuren wanneer de veelvoudige agenten goedkeurt.
