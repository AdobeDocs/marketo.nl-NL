---
description: Opmerkingen bij de release - april 2024 - Marketo Docs - Productdocumentatie
title: Opmerkingen bij de release - april 2024
feature: Release Information
exl-id: d87474f8-fc47-407b-bc97-e343b56c1f8f
source-git-commit: 8e72b24e18ae108ec74e6d4fa6b04f10130439a4
workflow-type: tm+mt
source-wordcount: '447'
ht-degree: 1%

---

# Opmerkingen bij de release: april 2024 {#release-notes-apr-24}

Hieronder vindt u alle functies die zijn inbegrepen in de release van 24 april. Raadpleeg de Adobe Marketo Engage-editie voor informatie over de beschikbaarheid van functies.

De Nota&#39;s van de Versie specifiek voor Adobe Dynamic Chat [&#x200B; kunnen hier &#x200B;](/help/marketo/release-notes/dynamic-chat.md){target="_blank"} worden gevonden.

>[!AVAILABILITY]
>
>De eigenschappen die door een ster (![&#x200B; worden aangegeven ster &#x200B;](assets/yellow-star.png)) worden betaald toe:voegen-ons. Neem contact op met je Marketo Engage-vertegenwoordiger voor meer informatie.

## Standaardfuncties van releasecyclus {#standard-release-cycle-features}

De volgende eigenschappen vallen onder de standaardversiecyclus en zullen beginnen om op **worden vrijgegeven 26 april, 2024**, met een gefaseerde uitrol van resterende eigenschappen in de verdere weken. De functies en datums van de release kunnen worden gewijzigd. Controleer de status naast elke functie.

<table style="table-layout:auto">
 <tbody>
  <tr>
   <th style="width:65%">Functie</th>
   <th style="width:10%">Status</th>
   <th style="width:25%">Documentatie</th>
  </tr>
     <tr>
   <td><strong> Interactieve de Verbeteringen van Webinars </strong>: U kunt gastheren en presentatoren van de capaciteit nu voorzien om een webinar titel toe te voegen, een ruimte anders te noemen, en manueel betrokkenheidsgegevens na de gebeurtenislevering te synchroniseren.</td>
   <td>Vrijgegeven</td>
   <td><li><a href="/help/marketo/product-docs/demand-generation/events/interactive-webinars/create-an-interactive-webinar.md">Een interactief webinar maken</a></li>
   <li><a href="/help/marketo/product-docs/demand-generation/events/interactive-webinars/event-workflows.md#manual-sync">Handmatige synchronisatie</a></li></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
    <tr>
   <td><strong> Verbeteringen van het Spoor van de Controle </strong>:
   Nieuwe typen acties kunnen nu worden vastgelegd in Audittrail voor wijzigingen die zijn aangebracht in Veldbeheer, wijzigingen die zijn aangebracht in Gebruikers en rollen en het aantal personen dat is geëxporteerd uit lijsten en slimme lijsten.</td>
   <td><i>Binnenkort beschikbaar</i></td>
   <td><i>Binnenkort beschikbaar</i></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
    <tr>
   <td><strong> Nieuwe Gebruikers &amp; de Toestemmingen van Rollen </strong>: De nieuwe toestemmingen zijn beschikbaar, die gebruikers voorzien van meer korrelige toegang tot Marketo Engage. Besturingsonderdelen van Admin die niet eerder zijn opgenomen, zoals New Experience en Predictive Audiences, splitsmachtigingen om toegang tot Asset Audit Trail en Admin Audit Trail afzonderlijk te verlenen en nieuwe aanmaak- en verplaatsingsmachtigingen voor elementen en mappen te gebruiken om te voorkomen dat alleen-lezen gebruikers wijzigingen aanbrengen.
   <p>Terwijl de nieuwe toestemmingen in uw instantie van Marketo Engage vanaf 26 April zullen verschijnen, zijn zij passief voor nu en zullen later dit kwart toegankelijk worden.
   <li>Toegang tot Adobe Experience Manager</li>
   <li>Toewijzing Adobe-organisatie openen</li>
   <li>Access Admin Audit Trail</li>
   <li>Actief assetaudittrail</li>
   <li>Toegang tot nieuwe ervaring</li>
   <li>Voorspelend publiek toegang</li>
   <li>Rapport maken</li>
   <li>Lijst maken</li>
   <li>Campagne exporteren</li>
   </td>
   <td>Vrijgegeven</td>
   <td><a href="/help/marketo/product-docs/administration/users-and-roles/descriptions-of-role-permissions.md">Beschrijvingen van rolmachtigingen</a></td>
  </tr>
 </tbody>
</table>
<br/>

## Aankondigingen {#announcements}

* **Activiteiten API Update**: Op 26 april, voegen wij verscheidene nieuwe attributen aan web-based en op e-mail-Gebaseerde activiteiten toe die zijn teruggekeerd wanneer u activiteiten terugwint gebruikend [&#x200B; Marketo REST API &#x200B;](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Activities){target="_blank"}. De hieronder vermelde activiteiten omvatten nu de kenmerken Browser, Platform, Apparaat en Gebruikersagent. Roep [&#x200B; krijgt het 1&rbrace; eindpunt van de Types van Activiteit &lbrace;om kenmerkdetails voor elke activiteit te herzien.](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Activities/operation/getAllActivityTypesUsingGET){target="_blank"}

**Web-based Activiteiten**

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

**op e-mail-Gebaseerde Activiteiten**

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
