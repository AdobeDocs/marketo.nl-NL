---
unique-page-id: 1147322
description: Anonieme activiteiten en mensen begrijpen - Marketo-documenten - productdocumentatie
title: Anonieme activiteiten en mensen begrijpen
exl-id: 1676e8f3-9138-42ed-8bb4-40e195391fc4
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '208'
ht-degree: 0%

---

# Anonieme activiteit en personen {#understanding-anonymous-activity-and-people}

De eerste keer dat iemand een Marketo landingspagina bezoekt (of een pagina op uw website met de [Munchkin Tracking Code](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md), maakt Marketo een _anonieme activiteit_ en gebruikt een browsercookie om deze bij te houden. Zodra het wordt geïdentificeerd, wordt het een persoon en de geschiedenis verbonden aan hun browser koekje wordt samengevoegd in.

**Een** Anonymousactivity wordt gemaakt wanneer iemand:

* Bezoekt de eerste keer je Marketo-landingspagina.
* Bezoekt een pagina op uw site met [Munchkin-tracking](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md).
* Klik op de koppeling [Weergeven als webpagina](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md) in een Marketo-e-mail.

>[!NOTE]
>
>In tegenstelling tot andere koppelingen in Marketo-e-mails wordt [View as Web Page](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md) niet als een e-mailklik bijgehouden.

Een anonieme activiteit wordt samengevoegd in een nieuwe of bestaande persoon wanneer iemand:

* Klik op een [koppeling in een Marketo-e-mail](/help/marketo/product-docs/email-marketing/general/using-tokens/add-a-system-token-as-a-link-in-an-email.md).
* Hiermee vult u een Marketo [Form](/help/marketo/product-docs/demand-generation/forms/form-actions/embed-a-form-on-your-website.md) in.
* Gebruikt Marketo [SOAP](/help/marketo/product-docs/administration/additional-integrations/configuring-your-soap-api-settings.md) of [Munchkin](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md) API (voor ontwikkelaars) om een anonieme persoon met een bekend verslag te associëren.

Eén naam in de database kan aan veel cookies zijn gekoppeld, omdat mensen vaak verschillende apparaten en browsers gebruiken om uw site te bezoeken.

>[!NOTE]
>
>Wanneer anonieme records worden samengevoegd in een nieuw of bestaand persoonrecord, worden aangepaste veldwaarden **niet** overgedragen.
