---
unique-page-id: 2360181
description: Anonieme activiteiten en personen volgen - Marketo Docs - Productdocumentatie
title: Anonieme activiteiten en personen volgen
translation-type: tm+mt
source-git-commit: 03ee7b69f691efce12825aa708c81dffa23cecd9
workflow-type: tm+mt
source-wordcount: '229'
ht-degree: 0%

---


# Anonieme activiteit en personen {#tracking-anonymous-activity-and-people} volgen

De eerste keer dat iemand een Marketo [landingspagina](/help/marketo/product-docs/demand-generation/landing-pages/free-form-landing-pages/create-a-free-form-landing-page.md) (of een pagina op uw website met de [Munchkin-trackingcode](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md)) bezoekt, maakt Marketo een _anonieme activiteit_ en gebruikt een browsercookie om deze bij te houden. Zodra de bezoeker is geïdentificeerd, wordt het een persoon en wordt de geschiedenis verbonden aan het browser koekje binnen samengevoegd.

1. Er wordt een anonieme activiteit gemaakt wanneer iemand:

   * Bezoekt de eerste keer uw Marketo [landingspagina](/help/marketo/product-docs/demand-generation/landing-pages/free-form-landing-pages/create-a-free-form-landing-page.md).
   * Bezoekt een pagina op uw site met [Munchkin-tracking](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md).
   * Klik op de koppeling [Weergeven als webpagina](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md) in een e-mailbericht van Marketo.

   >[!NOTE]
   >
   >In tegenstelling tot andere koppelingen in e-mailberichten voor markeren wordt de optie Weergeven als webpagina niet als een e-mailklik bijgehouden.

   Een anonieme activiteit wordt samengevoegd in een nieuwe of bestaande persoon wanneer iemand:

   * Klik op een [koppeling in een Marketo-e-mail](/help/marketo/product-docs/email-marketing/general/using-tokens/add-tokens-to-an-email-link.md).
   * Vult een Marketo [form](/help/marketo/product-docs/demand-generation/forms/creating-a-form/create-a-form.md) uit.
   * Gebruikt de [REST API](https://developers.marketo.com/rest-api/lead-database/leads/) of [Munchkin](https://developers.marketo.com/documentation/websites/lead-tracking-munchkin-js/) API (voor ontwikkelaars) van Marketo om een anonieme activiteit met een bekende verslag te associëren.

   Eén naam in de database kan aan veel cookies zijn gekoppeld, omdat mensen vaak verschillende apparaten en browsers gebruiken om uw site te bezoeken.

   >[!NOTE]
   >
   >Wanneer anonieme records worden samengevoegd in een nieuw of bestaand persoonrecord, worden aangepaste veldwaarden **niet** overgedragen.

   >[!MORELIKETHIS]
   >
   >[Personen of anonieme bezoekers weergeven in webrapporten](/help/marketo/product-docs/reporting/basic-reporting/report-activity/display-people-or-anonymous-visitors-in-web-reports.md)
