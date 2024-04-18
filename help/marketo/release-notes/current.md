---
description: Actuele aanvullende informatie - Marketo Docs - Productdocumentatie
title: Opmerkingen bij de huidige release
exl-id: a2eccad5-73ad-48f9-8091-51cee23824e1
feature: Release Information
source-git-commit: 9f442b64f2e6d012207f79d06298583655db86b7
workflow-type: tm+mt
source-wordcount: '356'
ht-degree: 2%

---

# Opmerkingen bij de release: april 2024 {#release-notes-apr-24}

Hieronder vindt u alle functies die zijn inbegrepen in de release van 24 april. Raadpleeg de Adobe Marketo Engage-editie voor informatie over de beschikbaarheid van functies.

>[!AVAILABILITY]
>
>Kenmerken die door een ster worden aangeduid (![ster](assets/yellow-star.png)) worden betaald als extra&#39;s. Neem contact op met uw Marketo Engage voor meer informatie.

## Standaardfuncties van releasecyclus {#standard-release-cycle-features}

De volgende functies vallen onder de standaardreleasecyclus en worden vrijgegeven op **26 april 2024**, met een gefaseerde uitrol van de resterende functies in de daaropvolgende weken. De functies en datums van de release kunnen worden gewijzigd. Controleer de status naast elke functie.

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:65%">Functie</th> 
   <th style="width:10%">Status</th>
   <th style="width:25%">Documentatie</th>
  </tr>
     <tr> 
   <td><strong>Verbeteringen voor interactieve webinars</strong>: U kunt gastheren en presentatoren nu de mogelijkheid bieden een webinar-titel toe te voegen, de naam van een ruimte te wijzigen en de betrokkenheidsgegevens handmatig te synchroniseren na de levering van de gebeurtenis.</td> 
   <td><i>Binnenkort beschikbaar</i></td>
   <td><i>Binnenkort beschikbaar</i></td>
  </tr>
  <tr> 
   <td> </td> 
   <td> </td>
   <td> </td>
  </tr>
    <tr> 
   <td><strong>Verbeteringen audittrail</strong>: Nieuwe typen acties kunnen nu worden vastgelegd in Audittrail voor wijzigingen die zijn aangebracht in Veldbeheer, wijzigingen die zijn aangebracht in Gebruikers en rollen en het aantal personen dat is geëxporteerd uit lijsten en slimme lijsten.</td> 
   <td><i>Binnenkort beschikbaar</i></td>
   <td><i>Binnenkort beschikbaar</i></td>
  </tr>
  <tr> 
   <td> </td> 
   <td> </td>
   <td> </td>
  </tr>
    <tr> 
   <td><strong>Nieuwe gebruikers- en rolmachtigingen</strong>: Er zijn nieuwe machtigingen beschikbaar, waardoor gebruikers meer toegang krijgen tot Marketo Engage in korreligheid. Besturingsonderdelen van Admin die niet eerder zijn opgenomen, zoals New Experience en Predictive Audiences, splitsmachtigingen om toegang tot Asset Audit Trail en Admin Audit Trail afzonderlijk te verlenen en nieuwe aanmaak- en verplaatsingsmachtigingen voor elementen en mappen te gebruiken om te voorkomen dat alleen-lezen gebruikers wijzigingen aanbrengen.</td> 
   <td><i>Binnenkort beschikbaar</i></td>
   <td><i>Binnenkort beschikbaar</i></td>
  </tr>
 </tbody> 
</table>
<br/>

## Aankondigingen {#announcements}

* **Update voor activiteitenAPI**: Op 26 april, voegen wij verscheidene nieuwe attributen aan web-based en e-mailgebaseerde activiteiten toe die zijn teruggekeerd wanneer u activiteiten terugwint gebruikend [MARKETO REST API](https://developers.marketo.com/rest-api/lead-database/activities/){target="_blank"}. The activities listed below will now include Browser, Platform, Device, and User Agent attributes. Call the [Get Activity Types](https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Activities/getAllActivityTypesUsingGET){target="_blank"} eindpunt om kenmerkdetails voor elke activiteit te herzien.

**Webactiviteiten**

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:30%">Activiteit</th> 
   <th style="width:70%">Nieuw toegevoegde kenmerken</th>
   </tr>
  <tr> 
   <td>Webpagina bezoeken</td> 
   <td>Browser, platform, apparaat</td>
  </tr>
   <tr> 
   <td>Formulier invullen</td> 
   <td>Browser, platform, apparaat</td>
  </tr>
  <tr> 
   <td>Klik op Koppeling</td> 
   <td>Browser, platform, apparaat</td>
  </tr>
 </tbody> 
</table>

**E-mailactiviteiten**

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:30%">Activiteit</th> 
   <th style="width:70%">Nieuw toegevoegde kenmerken</th>
  </tr>
   <tr> 
   <td>E-mail verzenden</td> 
   <td>Browser, platform, apparaat, gebruikersagent</td>
  </tr>
   </tr>
  <tr> 
   <td>E-mail bezorgd</td> 
   <td>Browser, platform, apparaat, gebruikersagent</td>
  </tr>
   <tr> 
   <td>E-mail verzonden</td> 
   <td>Browser, platform, apparaat, gebruikersagent</td>
  </tr>
  <tr> 
   <td>E-mailadres opzeggen</td> 
   <td>Browser, platform, apparaat</td>
  </tr>
  <tr> 
   <td>E-mail openen</td> 
   <td>Browser</td>
  </tr>
   <tr> 
   <td>Klik op E-mail</td> 
   <td>Browser</td>
  </tr>
  <tr> 
   <td>Door e-mail teruggekaatst</td> 
   <td>Browser, platform, apparaat, gebruikersagent</td>
  </tr>
 </tbody> 
</table>
