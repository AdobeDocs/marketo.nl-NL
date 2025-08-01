---
description: OP-Acquisition-API - Marketo Docs - Productdocumentatie
title: OP-Acquisition-API
feature: Programs
exl-id: abf7c4a0-c363-4e92-9a1f-197c3953c515
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '171'
ht-degree: 0%

---

# OP-Acquisition-API {#op-acquisition-api}

Dit voorbeeldprogramma is bedoeld voor operationele processen om de aanschaf van records van API-bronnen te volgen aan de hand van een Marketo Engage Default Program.

## Kanaaloverzicht {#channel-summary}

<table style="table-layout:auto">
 <tbody>
  <tr>
   <th>Kanaal</th>
   <th>Lidmaatschapsstatus</th>
   <th>Analysegedrag</th>
   <th>Programmatype</th>
  </tr>
  <tr>
   <td>Operationeel</td>
   <td>01-Lid</td>
   <td>Operationeel</td>
   <td>Standaard</td>
  </tr>
 </tbody>
</table>

## Het programma bevat de volgende Assets {#program-contains-the-following-assets}

<table style="table-layout:auto">
 <tbody>
  <tr>
   <th>Type</th>
   <th>Sjabloonnaam</th>
   <th>Elementnaam</th>
  </tr>
  <tr>
   <td>Slimme campagne</td>
   <td> </td>
   <td>Verwerving instellen - Batch</td>
  </tr>
  <tr>
   <td>Slimme campagne</td>
   <td> </td>
   <td>Verwerving instellen - trigger</td>
  </tr>
  <tr>
   <td>Map</td>
   <td> </td>
   <td>Campagnes (bevat alle slimme campagnes)</td>
  </tr>
 </tbody>
</table>

![](assets/op-acquisition-api-1.png)

## Conflictregels {#conflict-rules}

* **de Markeringen van het Programma**
   * Creeer markeringen in dit abonnement - _Geadviseerde_
   * Negeren

* **het Bestaan malplaatje van de Pagina met de zelfde naam**
   * Origineel malplaatje van het exemplaar - _geadviseerde_
   * Doelsjabloon gebruiken

* **Beelden met de zelfde naam**
   * Houd beide dossiers - _geadviseerde_
   * Item in dit abonnement vervangen

* **E-mailmalplaatjes met de zelfde naam**
   * Houd beide malplaatjes - _geadviseerde_
   * Bestaande sjabloon vervangen

## Aanbevolen procedures {#best-practices}

* Voer eerst de batchcampagne uit als u uw gegevensbeheer wilt inhalen.

* Overweeg gelijkaardige programma&#39;s te gebruiken om zich aan beste praktijken over alle inputbronnen te verzekeren om uw CRM of Integratie van Gegevens te omvatten.

* Zorg ervoor dat binnen kanaalspecifieke marketinginitiatieven de acquisitie wordt vastgelegd wanneer dat nodig is.
