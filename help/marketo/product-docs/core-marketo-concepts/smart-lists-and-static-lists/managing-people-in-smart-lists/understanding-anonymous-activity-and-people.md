---
unique-page-id: 1147322
description: Anonieme activiteiten en mensen begrijpen - Marketo Docs - Productdocumentatie
title: Anonieme activiteiten en mensen begrijpen
translation-type: tm+mt
source-git-commit: d7d6aee63144c472e02fe0221c4a164183d04dd4
workflow-type: tm+mt
source-wordcount: '219'
ht-degree: 0%

---


# Anonieme activiteiten en mensen begrijpen {#understanding-anonymous-activity-and-people}

De eerste keer dat iemand een Marketo [l bezoekt `anding page`](http://docs.marketo.com/display/DOCS/Personalizing+Landing+Pages) (of een pagina op uw website met de [Munchkin Tracking Code](../../../../product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md)), maakt Marketo een *anonieme **activiteit* en gebruikt het een browsercookie om deze te volgen. Zodra het wordt geïdentificeerd, wordt het een persoon en de geschiedenis verbonden aan hun browser koekje wordt samengevoegd in.

**Een anonieme** activiteit wordt gecreeerd wanneer iemand:

* Bezoekt de eerste keer uw Marketo-landingspagina.

* Bezoek een pagina op uw site met [Munchkin-tracking](../../../../product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md).

* Klik op de koppeling [Weergeven als webpagina](../../../../product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md) in een e-mailbericht voor Marketo.

>[!NOTE]
>
>In tegenstelling tot andere koppelingen in e-mails met Markering wordt [Weergeven als webpagina](../../../../product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md) niet als een e-mailklik bijgehouden.

Een anonieme activiteit wordt samengevoegd in een nieuwe of bestaande persoon wanneer iemand:

* Klik op een [koppeling in een e-mailbericht](../../../../product-docs/email-marketing/general/using-tokens/add-a-system-token-as-a-link-in-an-email.md)Marketo.
* Vult een Marketo- [formulier](../../../../product-docs/demand-generation/forms/form-actions/embed-a-form-on-your-website.md)uit.
* Gebruikt [SOAP](http://docs.marketo.com/pages/viewpage.action?pageid=7509846) of [Munchkin](../../../../product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md) API van Marketo (voor ontwikkelaars) om een anonieme persoon met een bekend verslag te associëren.

Eén naam in de database kan aan veel cookies zijn gekoppeld, omdat mensen vaak verschillende apparaten en browsers gebruiken om uw site te bezoeken.

>[!NOTE]
>
>Wanneer anonieme records worden samengevoegd in een nieuw of bestaand persoonrecord, worden aangepaste veldwaarden **niet** overgedragen.

