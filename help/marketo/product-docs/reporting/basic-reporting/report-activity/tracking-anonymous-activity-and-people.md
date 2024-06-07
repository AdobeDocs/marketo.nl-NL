---
unique-page-id: 2360181
description: Anonieme activiteiten en personen bijhouden - Marketo-documenten - Productdocumentatie
title: Anonieme activiteiten en personen volgen
exl-id: 95a39e57-4636-4bae-8ca8-00cb43cb566c
feature: Reporting
source-git-commit: 2b610cc3486b745212b0b1f36018a83214d7ecd7
workflow-type: tm+mt
source-wordcount: '221'
ht-degree: 0%

---

# Anonieme activiteiten en personen volgen {#tracking-anonymous-activity-and-people}

De eerste keer dat iemand een Marketo bezoekt [landingspagina](/help/marketo/product-docs/demand-generation/landing-pages/free-form-landing-pages/create-a-free-form-landing-page.md) (of een pagina op uw website die de [Munchkin-trackingcode](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md)), maakt Marketo een _anonieme activiteit_ en gebruikt een browsercookie om het bij te houden. Zodra de bezoeker is geïdentificeerd, wordt het een persoon en wordt de geschiedenis verbonden aan het browser koekje binnen samengevoegd.

1. Er wordt een anonieme activiteit gemaakt wanneer iemand:

   * Bezoek je Marketo [landingspagina](/help/marketo/product-docs/demand-generation/landing-pages/free-form-landing-pages/create-a-free-form-landing-page.md) de eerste keer.
   * Bezoek een pagina op uw site die [Munchkin-tracking](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md).
   * Klik op de knop [Weergeven als webpagina](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md) in een Marketo-e-mailbericht.

   >[!NOTE]
   >
   >In tegenstelling tot andere koppelingen in e-mailberichten van Marketo, wordt de optie Weergeven als webpagina niet als een e-mailklik bijgehouden.

   Een anonieme activiteit wordt samengevoegd in een nieuwe of bestaande persoon wanneer iemand:

   * Klik op een [koppeling in een Marketo-e-mailbericht](/help/marketo/product-docs/email-marketing/general/using-tokens/add-tokens-to-an-email-link.md).
   * Hiermee vult u een Marketo in [formulier](/help/marketo/product-docs/demand-generation/forms/creating-a-form/create-a-form.md).
   * Gebruikt Marketo [REST API](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/leads) of [Munchkin](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/javascriptapi/lead-tracking) API (voor ontwikkelaars) om een anonieme activiteit te associëren met een bekende record.

   Eén naam in de database kan aan veel cookies zijn gekoppeld, omdat mensen vaak verschillende apparaten en browsers gebruiken om uw site te bezoeken.

   >[!NOTE]
   >
   >Wanneer anonieme records worden samengevoegd in een nieuw of bestaand persoonrecord, worden aangepaste veldwaarden gebruikt **niet** overdracht over.

   >[!MORELIKETHIS]
   >
   >[Personen of anonieme bezoekers weergeven in webrapporten](/help/marketo/product-docs/reporting/basic-reporting/report-activity/display-people-or-anonymous-visitors-in-web-reports.md)
