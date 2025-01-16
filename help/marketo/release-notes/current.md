---
description: Huidige aanvullende informatie - Documentatie voor Marketo - Productdocumentatie
title: Opmerkingen bij de huidige release
exl-id: a2eccad5-73ad-48f9-8091-51cee23824e1
feature: Release Information
source-git-commit: 7837499e74558e6e48bf7b1e681f936f63d2843f
workflow-type: tm+mt
source-wordcount: '523'
ht-degree: 3%

---

# Opmerkingen bij de release: januari 2025 {#release-notes-jan-25}

Hieronder vindt u alle functies die zijn inbegrepen in de release van 25 januari. Raadpleeg de Adobe Marketo Engage-editie voor informatie over de beschikbaarheid van functies.

De Nota&#39;s van de Versie specifiek voor Adobe Dynamic Chat [ kunnen hier ](/help/marketo/release-notes/dynamic-chat.md){target="_blank"} worden gevonden.

>[!AVAILABILITY]
>
>De eigenschappen die door een ster (![ worden aangegeven ster ](assets/yellow-star.png)) worden betaald toe:voegen-ons. Neem contact op met uw Marketo Engage voor meer informatie.

## Standaardfuncties van releasecyclus {#standard-release-cycle-features}

De volgende eigenschappen vallen onder de standaardversiecyclus en zullen beginnen om op **17 Januari, 2025**, met een gefaseerde uitrol van resterende eigenschappen in de verdere weken worden vrijgegeven. De functies en datums van de release kunnen worden gewijzigd. Controleer de status naast elke functie.

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:65%">Functie</th> 
   <th style="width:10%">Status</th>
   <th style="width:25%">Documentatie</th>
  </tr>
    <tr> 
   <td><strong> Nieuwe E-mail Designer </strong>: Creeer moderne en efficiënte e-mails gebruikend nieuwe inheemse E-mail Designer in Marketo Engage. Open een van de vooraf ontworpen out-of-the-box e-mailsjablonen of maak eenvoudig uw eigen sjablonen. Gebruik dynamische inhoud en open afbeeldingen van Adobe Experience Manager-cloudservices.
   <p><img src="assets/note-icon.png" alt="notitiepictogram"> NOTA: Om tot de nieuwe e-mailontwerper toegang te hebben, moet uw abonnement van het Marketo Engage aan het <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview"> Systeem van Identity Management van de Adobe (IMS) </a> worden gemigreerd. Als u nog niet bent geweest en u zou willen verzoeken om het wordt bespoedigd, gelieve het Team van de Rekening van de Adobe (uw rekeningsmanager), of <a href="https://nation.marketo.com/t5/support/ct-p/Support"> Steun van Marketo </a> te contacteren.</td> 
   <td><i>Binnenkort beschikbaar</i></td>
   <td><i>Binnenkort beschikbaar</i></td>
  </tr>
  <tr> 
   <td> </td> 
   <td> </td>
   <td> </td>
  </tr>
  <tr> 
   <td><strong> Unregister Registrants van een Gebeurtenis in Interactieve Webinars </strong>: Nu als u geen registrant in uw webinar om het even welke reden wilt, kunt u hen unregister. De workflow verwijdert de registrant uit zowel het Marketo-gebeurtenisprogramma als Adobe Connect.</td> 
   <td><i>Binnenkort beschikbaar</i></td>
   <td><i>Binnenkort beschikbaar</i></td>
  </tr>
  <tr> 
   <td> </td> 
   <td> </td>
   <td> </td>
  </tr>
  <tr> 
   <td><strong> maak Campagnes op Archief </strong> onbruikbaar: maak actieve trekkercampagnes onbruikbaar en annuleer om het even welke geplande partijlooppas van campagnes in een omslag wanneer het wordt gearchiveerd. Aangezien er een extra toestemmingencontrole voor het archiveren omslagen is die actieve campagnes (activeer de Campagne van de Campagne van de Tejaar en de Campagne van de Partij van het Programma) bevatten, wordt deze eigenschap gehandicapt door gebrek met deze versie en kan worden toegelaten door aan <b> Admin </b> &gt; <b> de Chest van de Schat </b> in uw Marketo Engage te navigeren.</td> 
   <td><i>Binnenkort beschikbaar</i></td>
   <td><i>Binnenkort beschikbaar</i></td>
  </tr>
 </tbody> 
</table>
<br/>

## Aankondigingen {#announcements}

* **Sociale Veroudering van Eigenschappen**: Op Woensdag, 31 Juli, 2024, begon Marketo Engage de veroudering van de volgende Sociale eigenschappen binnen het product:

   * Opiniepeiling
   * Sociale knop
   * Aanbieding via verwijzing
   * Video delen
   * Sweepstake

Vanaf dat moment konden gebruikers geen van deze sociale functies in Marketo Engage maken, klonen of insluiten. Bestaande sociale voorzieningen blijven werken tot 31 januari 2025. Op 1 februari 2025 zullen de sociale activa niet meer functioneren. Sociale functies die zijn ingesloten in bestemmingspagina&#39;s, moeten worden verwijderd. [ leer meer ](https://nation.marketo.com/t5/employee-blogs/marketo-engage-social-features-deprecation/ba-p/351977) {target="_blank"}

* **krijgt de Update van de Update van de Leden van het Programma**: Wij hebben [ verbeterd krijgen de Leden van het Programma ](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/program-members#query) {target="_blank"} API om de capaciteit te steunen om het herkenningsteken van programmaleden terug te winnen. Hiervoor voegt u id toe aan de lijst met velden die is opgegeven in de parameter fields van de API-aanvraag.

* **Rest API &quot;access_token&quot;de Verdringing van de Parameter**: De `access_token` vraagparameter die wordt gebruikt om de vraag van Marketo REST API voor authentiek te verklaren wordt afgekeurd en zal niet beschikbaar na 30 Juni, 2025 zijn. Alle nieuwe en bestaande integratie zouden vraag REST API gebruikend de kopbal van de &quot;Vergunning&quot;voor authentiek moeten verklaren, [ zoals hier beschreven ](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/authentication) {target="_blank"}.

* **SOAP API Deprecation**: Steun voor de SOAP API van Marketo zal op 31 okt, 2025 eindigen. De diensten die SOAP API mogelijkheden gebruiken zouden aan [ REST API ](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/rest-api) {target="_blank"} moeten worden gemigreerd.
