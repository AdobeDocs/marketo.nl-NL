---
unique-page-id: 2360181
description: Anonieme activiteiten en personen bijhouden - Marketo-documenten - Productdocumentatie
title: Anonieme activiteiten en personen volgen
exl-id: 95a39e57-4636-4bae-8ca8-00cb43cb566c
feature: Reporting
source-git-commit: e3f61755dccd9bea1378a429fc428b440fc3ecb4
workflow-type: tm+mt
source-wordcount: '221'
ht-degree: 0%

---

# Anonieme activiteiten en personen volgen {#tracking-anonymous-activity-and-people}

De eerste keer bezoekt iemand een Marketo [ landende pagina ](/help/marketo/product-docs/demand-generation/landing-pages/free-form-landing-pages/create-a-free-form-landing-page.md) (of een pagina op uw website die [ Munchkin volgcode ](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md) heeft), leidt Marketo tot een _anonieme activiteit_ en gebruikt een browser koekje om het te volgen. Zodra de bezoeker is geïdentificeerd, wordt het een persoon en wordt de geschiedenis verbonden aan het browser koekje binnen samengevoegd.

1. Er wordt een anonieme activiteit gemaakt wanneer iemand:

   * Bezoekt uw Marketo [ landende pagina ](/help/marketo/product-docs/demand-generation/landing-pages/free-form-landing-pages/create-a-free-form-landing-page.md) de eerste keer.
   * Bezoekt een pagina op uw plaats die [ het volgen van Munchkin ](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md) heeft.
   * Klik de [ Mening als Web-pagina ](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md) verbinding in een e-mail van Marketo.

   >[!NOTE]
   >
   >In tegenstelling tot andere koppelingen in e-mailberichten van Marketo, wordt de optie Weergeven als webpagina niet als een e-mailklik bijgehouden.

   Een anonieme activiteit wordt samengevoegd in een nieuwe of bestaande persoon wanneer iemand:

   * Klik a [ verbinding in een e-mail van Marketo ](/help/marketo/product-docs/email-marketing/general/using-tokens/add-tokens-to-an-email-link.md).
   * Vult een vorm van Marketo [&#128279;](/help/marketo/product-docs/demand-generation/forms/creating-a-form/create-a-form.md) uit.
   * Gebruikt Marketo [ REST API ](https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/rest/lead-database/leads) of [ Munchkin ](https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/javascriptapi/leadtracking/lead-tracking) API (voor ontwikkelaars) om een anonieme activiteit met een bekend verslag te associëren.

   Eén naam in de database kan aan veel cookies zijn gekoppeld, omdat mensen vaak verschillende apparaten en browsers gebruiken om uw site te bezoeken.

   >[!NOTE]
   >
   >Wanneer de anonieme verslagen in een nieuw of bestaand persoonverslag worden samengevoegd, zullen de waarden van het douanegebied **niet** overdracht over.

   >[!MORELIKETHIS]
   >
   >[ Mensen van de vertoning of Anonieme Bezoekers in de Rapporten van het Web ](/help/marketo/product-docs/reporting/basic-reporting/report-activity/display-people-or-anonymous-visitors-in-web-reports.md)
