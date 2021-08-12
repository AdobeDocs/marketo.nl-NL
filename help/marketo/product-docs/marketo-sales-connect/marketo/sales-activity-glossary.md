---
description: Verklarende woordenlijst Verkoopactiviteiten - Marketo-documenten - Productdocumentatie
title: Verklarende woordenlijst Verkoopactiviteiten
hide: true
hidefromtoc: true
source-git-commit: 70f17106efe52ee742c8e31013e533fc36ce9835
workflow-type: tm+mt
source-wordcount: '275'
ht-degree: 3%

---

# Verklarende woordenlijst Verkoopactiviteiten {#sales-activity-glossary}

In Sales Connect, wanneer een verkoper: voegt een lead toe aan een verkoopkadentie, stuurt ze een e-mail of maakt een oproep tot een activiteit, dan wordt deze geregistreerd onder de Marketo-activiteitengeschiedenis. Bovendien, wanneer de lood met e-mail in dienst neemt, opent, klikt, en de antwoorden worden ook geregistreerd.

De onderstaande activiteiten worden vanuit Sales Connect aangemeld bij Marketo.

>[!NOTE]
>
>Deze activiteiten en kenmerken kunnen worden gebruikt via de REST- en Bulk-API.

## Activiteiten {#activities}

<table>
 <tr>
  <th>Verkoopactiviteit</th>
  <th>Kenmerk</th>
 </tr>
 <tr>
  <th rowspan="3">Verkoop-e-mail verzenden</th>
  <td>Verzonden door</td>
 </tr>
 <tr>
  <td>Bron</td>
 </tr>
 <tr>
  <td>Sjabloon-id</td>
 </tr>
 <tr>
  <th rowspan="3">Verkoopbericht openen</th>
  <td>Verzonden door</td>
 </tr>
 <tr>
  <td>Bron</td>
 </tr>
 <tr>
  <td>Sjabloon-id</td>
 </tr>
 <tr>
  <th rowspan="4">E-mail met geklikte verkoop</th>
  <td>Koppeling</td>
 </tr>
 <tr>
  <td>Verzonden door</td>
 </tr>
 <tr>
  <td>Bron</td>
 </tr>
 <tr>
  <td>Sjabloon-id</td>
 </tr>
 <tr>
  <th rowspan="2">E-mail over ontvangen verkoop</th>
  <td>Ontvangen door</td>
 </tr>
 <tr>
  <td>Bron</td>
 </tr>
 <tr>
  <th rowspan="4">Verkoop-e-mail teruggestuurd</th>
  <td>Details</td>
 </tr>
 <tr>
  <td>Sjabloon-id</td>
 </tr>
 <tr>
  <td>E-mail</td>
 </tr>
 <tr>
  <td>Verzonden door</td>
 </tr>
 <tr>
  <th rowspan="7">Ontvangen verkoopoproep</th>
  <td>Verkoopoproep gemaakt door</td>
 </tr>
 <tr>
  <td>Status van verkoopoproep</td>
 </tr>
 <tr>
  <td>Onderwerp verkoopoproep</td>
 </tr>
 <tr>
  <td>Naam verkoopcampagne</td>
 </tr>
 <tr>
  <td>Verkoopcampagne-URL</td>
 </tr>
 <tr>
  <td>Telefoonnummer van verkoper opgevraagd</td>
 </tr>
 <tr>
  <td>Bron</td>
 </tr>
 <tr>
  <th rowspan="6">Toevoegen aan verkoopcampagne</th>
  <td>Naam verkoopcampagne</td>
 </tr>
 <tr>
  <td>Status van verkoopoproep</td>
 </tr>
 <tr>
  <td>Verkoopcampagne-URL</td>
 </tr>
 <tr>
  <td>Verzonden door</td>
 </tr>
 <tr>
  <td>Bron</td>
 </tr>
 <tr>
  <td>Verkoopcampagne-id</td>
 </tr>
 <tr>
  <th rowspan="6">Verwijderen uit verkoopcampagne</th>
  <td>Naam verkoopcampagne</td>
 </tr>
 <tr>
  <td>Status van verkoopoproep</td>
 </tr>
 <tr>
  <td>Verkoopcampagne-URL</td>
 </tr>
 <tr>
  <td>Verzonden door</td>
 </tr>
 <tr>
  <td>Bron</td>
 </tr>
 <tr>
  <td>Verkoopcampagne-id</td>
 </tr>
</table>

## Beschrijvingen {#descriptions}

<table> 
 <tr>
  <th>Kenmerk</th>
  <th>Beschrijving</th>
 </tr>
 <tbody> 
  <tr> 
   <td><strong>Verzonden door</strong></td>
   <td>E-mailadres van de persoon die het e-mailbericht heeft verzonden.</td> 
  </tr> 
  <tr> 
   <td><strong>Bron</strong></td> 
   <td>Bron van de activiteit. Wordt ingesteld als "Tout" voor Connect-activiteiten van Sales.</td> 
  </tr> 
  <tr> 
   <td><strong>Sjabloon-id</strong></td> 
   <td>Als de bron Tout is, is de sjabloon-id de Marketo Sales Connect-sjabloon-id. Gebruik deze optie om een specifieke sjabloon te kiezen in plaats van een onderwerpregel, die in meerdere sjablonen kan bestaan.
</td> 
  </tr> 
  <tr> 
   <td><strong>Ontvangen door</strong></td> 
   <td>E-mailadres van de persoon die het e-mailbericht heeft verzonden.</td> 
  </tr> 
  <tr> 
   <td><strong>Details</strong></td> 
   <td>Bounce error message detail.</td> 
  </tr> 
  <tr> 
   <td><strong>E-mail</strong></td> 
   <td>E-mailadres dat is teruggestuurd.</td> 
  </tr> 
 </tbody> 
</table>