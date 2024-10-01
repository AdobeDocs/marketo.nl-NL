---
description: Salesforce Sync Observability Metrics Dashboard - Marketo Docs - Productdocumentatie
title: Salesforce Sync Observability Metrics Dashboard
hide: true
hidefromtoc: true
feature: Reporting
source-git-commit: 2457f0f51c6365c29a040e908678e81517327de5
workflow-type: tm+mt
source-wordcount: '503'
ht-degree: 0%

---

# Salesforce Sync Backlog Metrics  {#salesforce-sync-backlog-metrics}

Bekijk de doorvoer van uw synchronisatieprestaties en synchroniseer de logbestanden met dit dashboard.

## Doorvoer en back-up synchroniseren {#sync-throughput-and-backlog}

1. Ga in Marketo Engage naar het gebied Beheer.

   SCREENSHOT

1. Selecteer Salesforce.

   SCREENSHOT

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
    <td>Schatting van de tijd die nodig is om de achterstand per objecttype te synchroniseren. Berekend als synchronisatiegegevens op basis van back-up/gemiddelde en gesynchroniseerd per uur.</td>
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

## Trend van back-up {#backlog-trend}

De trend van de achterstand weerspiegelt veranderingen in de achterstand die in de afgelopen vijf dagen is geregistreerd. De achterstand wordt getoond in een 4-uurs tijdinterval spreidt zich over 5 dagen uit. Daarom zal de grafiek 6 intervallen per dag tijden 5 dagen tonen, die 30 intervallen evenaart.

Backlog wordt waargenomen bij een bepaald 4-uurs tijdinterval op de x-as. Deze waarde is voor alle objecten die gesynchroniseerd zijn. Dit is het totaal van de achterstand in Salesforce en Marketo Engage die wachten op synchronisatie.

SCREENSHOT
