---
description: Huidige aanvullende informatie - Documentatie voor Marketo - Productdocumentatie
title: Opmerkingen bij de huidige release
exl-id: a2eccad5-73ad-48f9-8091-51cee23824e1
feature: Release Information
source-git-commit: 97806e0df45327fb695f02c02af0dde42a602737
workflow-type: tm+mt
source-wordcount: '546'
ht-degree: 1%

---

# Opmerkingen bij de release: oktober 2024 {#release-notes-oct-24}

Hieronder vindt u alle functies die zijn inbegrepen in de release van 24 oktober. Raadpleeg de Adobe Marketo Engage-editie voor informatie over de beschikbaarheid van functies.

De Nota&#39;s van de Versie specifiek voor Adobe Dynamic Chat [ kunnen hier ](/help/marketo/release-notes/dynamic-chat.md){target="_blank"} worden gevonden.

>[!AVAILABILITY]
>
>De eigenschappen die door een ster (![ worden aangegeven ster ](assets/yellow-star.png)) worden betaald toe:voegen-ons. Neem contact op met uw Marketo Engage voor meer informatie.

## Standaardfuncties van releasecyclus {#standard-release-cycle-features}

De volgende eigenschappen vallen onder de standaardversiecyclus en zullen beginnen om op **worden vrijgegeven 4 Oktober, 2024**, met een gefaseerde implementatie van resterende eigenschappen in de verdere weken. De functies en datums van de release kunnen worden gewijzigd. Controleer de status naast elke functie.

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:65%">Functie</th> 
   <th style="width:10%">Status</th>
   <th style="width:25%">Documentatie</th>
  </tr>
    <tr> 
   <td><strong> Tokenization voor Interactive Webinars </strong>: U kunt nu tokens gebruiken om Interactieve Webinars in e-mails en Openende Pagina's te bevorderen zonder het moeten de webinar details manueel toevoegen.</td> 
   <td>Verzonden</td>
   <td><a href="/help/marketo/product-docs/demand-generation/events/interactive-webinars/promoting-an-interactive-webinar.md#interactive-webinars-tokens" target="_blank">Een interactief webinar promoten</a></td>
  </tr>
  <tr> 
   <td> </td> 
   <td> </td>
   <td> </td>
  </tr>
  </tr>
   <tr> 
   <td><strong> Slimme Lijst "Reeks om"Telling </strong> te beïnvloeden: Zie hoeveel mensen wanneer het uitgeven van de kwalificatieregels van een Slimme Campagne zullen worden beïnvloed.</td> 
   <td>Verzonden</td>
   <td>nvt</td>
  </tr>
  <tr> 
   <td> </td> 
   <td> </td>
   <td> </td>
  </tr>
  </tr>
   <tr> 
   <td><strong> Mijn knoop van de Rekening in navigatiespoor </strong>: Voor degenen die naar het Systeem van Identity Management van de Adobe zijn gemigreerd, staat een nieuwe "Mijn knoop van de Rekening"in de linkernavigatiespoor het vormen van uw tijdzone en de toegang tot abonnementsdetails toe.</td> 
   <td>Verzonden</td>
   <td>nvt</td>
  </tr>
  <tr> 
   <td> </td> 
   <td> </td>
   <td> </td>
  </tr>
   <tr> 
   <td><strong> de Verbeteringen van het Rapport van Prestaties van de E-mail </strong>: De veelvoudige verbeteringen zijn aangebracht aan e-mail rapporterend metriek en activiteit die, extra inzichten aanbieden en nauwkeurigheid verbeteren.
   <ul>
   <li>Verwijderde en samengevoegde personen filteren van e-mailprestatiegegevens</li>
   <li>E-mail nu geclassificeerd als <i> geaborteerd </i> na het wachten drie dagen voor reactieactiviteit</li>
   <li>E-mail wordt beschouwd als een unieke opening voor elke slimme campagne</li>
   </td> 
   <td>Verzonden</td>
   <td><a href="/help/marketo/product-docs/email-marketing/email-programs/email-program-data/email-performance-report.md" target="_blank">E-mailprestatierapport</a></td>
  </tr>
  <tr> 
   <td> </td> 
   <td> </td>
   <td> </td>
  </tr>
   <tr> 
   <td><strong> de Metriek van de Achtergrond van de Synchronisatie van Salesforce </strong>: De synchrone productie en de tendensen van de backlog van de monitor om de updates van CRM voor een optimale synchronisatieervaring te plannen en te plannen.
   </td> 
   <td>Verzonden</td>
   <td><a href="/help/marketo/product-docs/crm-sync/salesforce-sync/salesforce-sync-backlog-metrics.md" target="_blank">Salesforce Sync Backlog Metrics</a></td>
  </tr>
 </tbody> 
</table>
<br/>

## Aankondigingen {#announcements}

* **Bulk extraheerde API Update**: Wij bevestigden een kwestie in het Bulk Uittreksel API die de columnHeaderNames optie impliceert, die u de namen van de douanekolomkopbal in het uitgevoerde dossier laat specificeren. Eerder konden kolomkopnamen die niet-ASCII-tekens bevatten, beschadigd raken.

* **Rest API access_token de Afschrijving van de Parameter**: De &quot;access_token&quot;vraagparameter wordt gebruikt om de vraag van Marketo REST API voor authentiek te verklaren wordt afgekeurd en zal niet beschikbaar na 30 Juni, 2025 zijn. Alle nieuwe en bestaande integraties zouden vraag REST API voor authentiek moeten verklaren gebruikend de kopbal van de &quot;Vergunning&quot;[ zoals die hier ](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/authentication#using-an-access-token) wordt beschreven.


* **QR de Afschrijving van de Code**: Op 4 Oktober, 2024, zal de QR codeeigenschap die in dupberichten en in-app overseinenactiva wordt gebruikt worden afgekeurd. Dit omvat het gebruik van QR-codes voor een nieuw testapparaat en het maken van nieuwe elementen met QR-codes. Door functies met een lager gebruik te deactiveren, kunnen we hun middelen opnieuw toewijzen aan het algemene onderhoud van het Marketo Engage.

* **de Veranderingen van Munchkin**

   * **Nieuwe Versie**: Op 17 September, 2024, [ Munchkin ](/help/marketo/product-docs/administration/setup-administration/munchkin.md){target="_blank"} v.164 zal beginnen uitrollen aan de instanties van het Marketo Engage die &quot;Munchkin Beta&quot;plaatsen hebben die in **wordt toegelaten Admin** > **de Chest van de Schat**. Het is gepland om op 29 oktober met de uitrol naar alle andere instanties te beginnen. Deze versie werkt het maken van Munchkin cookies bij. Er zijn geen wijzigingen in de functionaliteit.

   * **Karakters van Verwijderde URL**: &quot;Bezoekt Web-pagina&quot;en de &quot;Klik Verbinding&quot;activiteiten die door Munchkin JS worden gecreeerd zullen niet-URL gecodeerde controlekarakters van alle gebieden URL nu verwijderen. Deze verandering wordt ontworpen om fouten met betrekking tot propagatie van die types van karakters in systemen te verhinderen die hen niet steunen, en geen geldig gebruik binnen Marketo Engage hebben.
