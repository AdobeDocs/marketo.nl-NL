---
unique-page-id: 2360181
description: Anonieme activiteiten en personen volgen - Marketo Docs - Productdocumentatie
title: Anonieme activiteiten en personen volgen
translation-type: tm+mt
source-git-commit: 1a29614ec938074902af201b2ffc11cfaa625f7a
workflow-type: tm+mt
source-wordcount: '249'
ht-degree: 0%

---


# Anonieme activiteiten en personen volgen {#tracking-anonymous-activity-and-people}

De eerste keer dat iemand een Marketo- [landingspagina](../../../../product-docs/demand-generation/landing-pages/free-form-landing-pages/create-a-free-form-landing-page.md) bezoekt (of een pagina op uw website met de [Munchkin-trackingcode](../../../../product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md)), maakt Marketo een *anonieme* *activiteit* en gebruikt het een browsercookie om deze te volgen. Zodra de bezoeker is geïdentificeerd, wordt het een persoon en wordt de geschiedenis verbonden aan het browser koekje binnen samengevoegd.

1. Er wordt een anonieme activiteit gemaakt wanneer iemand:

   * Bezoekt de [landingspagina](../../../../product-docs/demand-generation/landing-pages/free-form-landing-pages/create-a-free-form-landing-page.md) van uw Marketo.
   * Bezoek een pagina op uw site met [Munchkin-tracking](../../../../product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md).
   * Klik op de koppeling [Weergeven als webpagina](../../../../product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md) in een e-mailbericht voor Marketo.

   >[!NOTE]
   >
   >In tegenstelling tot andere koppelingen in e-mailberichten voor markeren wordt de optie Weergeven als webpagina niet als een e-mailklik bijgehouden.

   Een anonieme activiteit wordt samengevoegd in een nieuwe of bestaande persoon wanneer iemand:

   * Klik op een [koppeling in een e-mailbericht](../../../../product-docs/email-marketing/general/using-tokens/add-tokens-to-an-email-link.md)Marketo.
   * Vult een Marketo- [formulier](http://docs.marketo.com/display/docs/forms)uit.
   * Gebruikt de [REST-API](http://developers.marketo.com/rest-api/lead-database/leads/) of [Munchkin](http://developers.marketo.com/documentation/websites/lead-tracking-munchkin-js/) -API (voor ontwikkelaars) van Marketo om een anonieme activiteit te koppelen aan een bekende record.

   Eén naam in de database kan aan veel cookies zijn gekoppeld, omdat mensen vaak verschillende apparaten en browsers gebruiken om uw site te bezoeken.

   >[!NOTE]
   >
   >Wanneer anonieme records worden samengevoegd in een nieuw of bestaand persoonrecord, worden aangepaste veldwaarden **niet** overgedragen.

   >[!NOTE]
   >
   >**Verwante artikelen**
   >
   >    
   >    
   >    * [Personen of anonieme bezoekers weergeven in webrapporten](display-people-or-anonymous-visitors-in-web-reports.md)


   >[!NOTE]
   >
   >**Diep duiken**
   >
   >
   >Meer weten over [Basisrapportage](http://docs.marketo.com/display/docs/basic+reporting)?

