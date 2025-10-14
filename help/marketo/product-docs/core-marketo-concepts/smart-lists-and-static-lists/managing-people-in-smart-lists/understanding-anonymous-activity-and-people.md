---
unique-page-id: 1147322
description: Anonieme activiteiten en mensen begrijpen - Marketo-documenten - productdocumentatie
title: Anonieme activiteiten en mensen begrijpen
exl-id: 1676e8f3-9138-42ed-8bb4-40e195391fc4
feature: Smart Lists
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '263'
ht-degree: 0%

---

# Anonieme activiteiten en mensen begrijpen {#understanding-anonymous-activity-and-people}

De eerste keer bezoekt iemand een Marketo landende pagina (of een pagina op uw website die de [&#x200B; het Volgen Code van Munchkin &#x200B;](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md){target="_blank"} heeft), leidt Marketo tot een *anonieme activiteit* en gebruikt een browser koekje om het te volgen. Zodra het wordt geïdentificeerd, wordt het een persoon en de geschiedenis verbonden aan hun browser koekje wordt samengevoegd in.

>[!IMPORTANT]
>
>Als u de Beta-functie **[!DNL Munchkin]V2 Anoniem opnieuw afspelen activeert op Bekende** , zorgt u ervoor dat campagnes die worden geactiveerd door anonieme lead-promotie altijd worden afgespeeld nadat de anonieme lead is samengevoegd in de bekende record. Als gevolg hiervan blijven aangepaste velden die zijn gewijzigd door de stappen Gegevenswaarde wijzigen in opnieuw afgespeelde campagnes behouden in de bekende record.

**Anonieme** activiteit wordt gecreeerd wanneer iemand:

* Bezoekt de eerste keer je Marketo-landingspagina.
* Bezoekt een pagina op uw plaats die [&#x200B; het volgen van Munchkin &#x200B;](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md){target="_blank"} heeft.
* Klik de [&#x200B; Mening als Web-pagina &#x200B;](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md){target="_blank"} verbinding in een e-mail van Marketo.

>[!NOTE]
>
>In tegenstelling tot andere verbindingen in de e-mail van Marketo, [&#x200B; Mening als Web-pagina &#x200B;](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md){target="_blank"} wordt niet gevolgd als e-mailklik.

Een anonieme activiteit wordt samengevoegd in een nieuwe of bestaande persoon wanneer iemand:

* Klik a [&#x200B; verbinding in een e-mail van Marketo &#x200B;](/help/marketo/product-docs/email-marketing/general/using-tokens/add-a-system-token-as-a-link-in-an-email.md){target="_blank"}.
* Vult een Vorm van Marketo [&#128279;](/help/marketo/product-docs/demand-generation/forms/form-actions/embed-a-form-on-your-website.md){target="_blank"} uit.
* Gebruikt Marketo [&#x200B; SOAP &#x200B;](/help/marketo/product-docs/administration/additional-integrations/configuring-your-soap-api-settings.md){target="_blank"} of [&#x200B; Munchkin &#x200B;](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md){target="_blank"} API (voor ontwikkelaars) om een anonieme persoon met een bekend verslag te associëren.

Eén naam in de database kan aan veel cookies zijn gekoppeld, omdat mensen vaak verschillende apparaten en browsers gebruiken om uw site te bezoeken.

>[!NOTE]
>
>Wanneer de anonieme verslagen in een nieuw of bestaand persoonverslag worden samengevoegd, zullen de waarden van het douanegebied *niet* overdracht over.
