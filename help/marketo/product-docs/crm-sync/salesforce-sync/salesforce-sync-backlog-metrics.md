---
description: Salesforce Sync Backlog Metrics - Marketo Docs - Productdocumentatie
title: Salesforce Sync Backlog Metrics
hide: true
hidefromtoc: true
feature: Reporting
source-git-commit: a9ed4a7e2247a26b376bde64bb1cfd6db2833822
workflow-type: tm+mt
source-wordcount: '840'
ht-degree: 0%

---

# Salesforce Sync Backlog Metrics  {#salesforce-sync-backlog-metrics}

De synchronisatieachterstand vertegenwoordigt de records die gesynchroniseerd moeten worden van Salesforce naar Marketo Engage en andersom. Als u ervoor zorgt dat de back-up onder controle blijft, wordt de synchronisatie vlot en tijdig uitgevoerd.

>[!NOTE]
>
>De achterstand behandelt de aantallen in afwachting van synchronisatie post-updates op één van beide kant, en niet die die door de stappen van de synchronisatiestroom zoals de [ Persoon van de Synchronisatie aan SFDC ](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md){target="_blank"} of [ de stappen van de de stroomstroom van de Synchronisatie aan Microsoft ](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/microsoft-dynamics-flow-actions/sync-person-to-microsoft.md){target="_blank"} worden ondernomen.

## Toegang krijgen {#how-to-access}

1. In Marketo Engage, ga naar het **Admin** gebied.

   SCREENSHOT

1. Selecteer **Salesforce**.

   SCREENSHOT

## Trend bij synchroniseren van back-up {#sync-backlog-trend}

De trend van de achterstand weerspiegelt veranderingen in de achterstand die in de afgelopen vijf dagen is geregistreerd. De achterstand wordt getoond in een 4-uurs tijdinterval spreidt zich over 5 dagen uit. Daarom zal de grafiek 6 intervallen per dag tijden 5 dagen tonen, die 30 intervallen evenaart.

Backlog wordt waargenomen bij een bepaald 4-uurs tijdinterval op de x-as. Deze waarde is voor alle objecten die gesynchroniseerd zijn. Dit is het totaal van de achterstand in Salesforce en Marketo Engage die wachten op synchronisatie.

SCREENSHOT

## Doorvoer en back-up synchroniseren {#sync-throughput-and-backlog}

De statistieken geven de doorvoer en de status van de achterstand weer voor elk objecttype dat gedurende de laatste 24 uur gesynchroniseerd is. De objecttypen omvatten alle objecten die gesynchroniseerd zijn, zoals Lead, Contact, Account, Opportunity, Campagne, User en Custom Objects. De productiestatistieken worden automatisch vernieuwd om de 15 minuten, maar u kunt manueel verfrissen gebruikend het verfrissen pictogram. De achterstand wordt elk uur opgehaald.

>[!NOTE]
>
>Statistieken worden doorlopend bijgewerkt, niet per kalenderdag.

SCREENSHOT

<table><thead>
  <tr>
    <th>Veld</th>
    <th>Beschrijving</th>
  </tr></thead>
<tbody>
  <tr>
    <td>Max records gesynchroniseerd / uur</td>
    <td>Het maximumaantal records dat per uur (maximale doorvoer) is gesynchroniseerd in de laatste 24 uur voor het objecttype. De periode van 24 uur rolt met tijd, niet de kalenderdag.</td>
  </tr>
  <tr>
    <td>Min. records gesynchroniseerd / uur</td>
    <td>Het minimumaantal records dat per uur (minimale doorvoer) is gesynchroniseerd in de laatste 24 uur voor het objecttype. De periode van 24 uur rolt met tijd, niet de kalenderdag.</td>
  </tr>
  <tr>
    <td>Gemiddelde records gesynchroniseerd / uur</td>
    <td>Het gemiddelde aantal records dat per uur (minimale doorvoer) is gesynchroniseerd in de laatste 24 uur voor het objecttype. De periode van 24 uur rolt met tijd, niet de kalenderdag. Dit wordt berekend als het totale aantal records dat in de laatste 24 uur is gesynchroniseerd.</td>
  </tr>
  <tr>
    <td>Back-up synchroniseren</td>
    <td>The backlog of records pending sync for the object type. Dit is het totaal van de achterstand bij synchronisatie in beide richtingen (van Salesforce naar Marketo Engage en omgekeerd). De achterstand van Salesforce wordt verkregen gebruikend een API vraag aan Salesforce, en de achterstand van Marketo Engage wordt berekend gebruikend de statistieken die uit het logboek van veranderingsgegevens worden verkregen. Dit wordt elk uur berekend. De volgende twee gebieden in deze lijst informeren wanneer de achterstand en het volgende programma voor berekening het laatst werd berekend, respectievelijk.</td>
  </tr>
  <tr>
    <td>Geschatte achterstand (tijd)</td>
    <td>Schatting van de tijd die nodig is om de achterstand per objecttype te synchroniseren. Berekend als 'Back-up/Gemiddeld synchroniseren records gesynchroniseerd per uur'.</td>
  </tr>
  <tr>
    <td>Backlog laatst opgehaald</td>
    <td>De tijd van de laatste backlogberekening.</td>
  </tr>
  <tr>
    <td>Backlog volgende fetch</td>
    <td>De tijd van de volgende backlogberekening.</td>
  </tr>
  <tr>
    <td>Backlogstatus</td>
    <td>Dit toont aan of de achterstand in de afgelopen 6 uur is gegroeid. Het wordt als "Groei"beschouwd als de huidige achterstand groter is dan de achterstand die zes uur geleden is geregistreerd. Anders wordt het weergegeven als 'Normaal'. Dit is gericht op het tonen van als de synchronisatieproductie met de achterstand inhaalt.</td>
  </tr>
</tbody></table>

## Wat veroorzaakt synchronisatiebacklogs {#what-causes-sync-backlogs}

Of de update aan de zijde van het Marketo Engage of aan de zijde van CRM wordt gemaakt, het zal het verslag teweegbrengen om opnieuw te worden gesynchroniseerd om de informatie aan de andere kant door het regelmatige Marketo Engage aan de synchronisatiecyclus van CRM bij te werken. Wanneer een update aan een verslag op Salesforce wordt gemaakt, produceert het een Stempel van de Tijd van de Wijziging van het Systeem, die als &quot;SysModStamp wordt bedoeld.&quot; Hiermee wordt een synchronisatie-wijziging in de wachtrij geplaatst.

Wanneer een grote hoeveelheid updates wordt gemaakt (zoals van een veranderend gebied), worden vele verslagen veranderd, veroorzakend nieuwe SysModStamps. Een groot aantal updates van het persoonrecord moet dan opnieuw worden gesynchroniseerd tussen Marketo Engage en uw CRM, waardoor soms een kortstondige achterstand ontstaat.

## Aanbevolen procedures voor het beheren van synchronisatiebacklogs {#best-practices-for-managing-sync-backlogs}

**Gebieden onder synchronisatie**: Zorg ervoor de gebieden onder synchronisatie slechts die zijn die moeten worden gesynchroniseerd. Door wijzigingen in velden neemt de synchronisatieachterstand toe en velden met lagere prioriteit worden mogelijk minder belangrijke velden gesynchroniseerd of vertraagd. Bereik uit aan [ de Steun van het Marketo Engage ](https://nation.marketo.com/t5/support/ct-p/Support) {target="_blank"} om gebieden onder synchronisatie te verwijderen.

**Gevoelige gebieden**: Sommige gebieden zijn aan frequente updates (b.v., muntgebieden vatbaar voor muntveranderingen). Controleer of deze moeten worden gesynchroniseerd of dat de velden anders moeten worden ontworpen.

**de voorwerpen van de Douane**: Herzie periodiek douanevoorwerpen onder synchronisatie en verwijder om het even welke die niet meer moeten worden gesynchroniseerd.

**Activiteiten**: Controle als er om het even welke activiteiten onder synchronisatie zijn die uit de synchronisatie kunnen worden verwijderd.

**bulkupdates van het Programma tijdens niet-kritieke uren**: Herzie uw patronen van de gegevenssynchronisatie om niet-kritieke periodes te identificeren. Controleer of bulkupdates tijdens deze niet-kritieke perioden kunnen worden gepland.

Als u alle beste praktijken hierboven volgt en u nog significante backlogs ervaart, contacteer [ de Steun van het Marketo Engage ](https://nation.marketo.com/t5/support/ct-p/Support) {target="_blank"}.
