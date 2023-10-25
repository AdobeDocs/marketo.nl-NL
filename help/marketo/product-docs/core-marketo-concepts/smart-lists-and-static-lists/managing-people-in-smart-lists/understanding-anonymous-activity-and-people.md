---
unique-page-id: 1147322
description: Anonieme activiteiten en mensen begrijpen - Marketo-documenten - productdocumentatie
title: Anonieme activiteiten en mensen begrijpen
exl-id: 1676e8f3-9138-42ed-8bb4-40e195391fc4
feature: Smart Lists
source-git-commit: 208ba59e3a5cb8e613e887b4c89e51cec4b3f897
workflow-type: tm+mt
source-wordcount: '262'
ht-degree: 0%

---

# Anonieme activiteiten en mensen begrijpen {#understanding-anonymous-activity-and-people}

De eerste keer dat iemand een Marketo landingspagina bezoekt (of een pagina op uw website die de [Munchkin-trackingcode](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md){target="_blank"}), maakt Marketo een *anonieme activiteit* en gebruikt een browsercookie om het bij te houden. Zodra het wordt geïdentificeerd, wordt het een persoon en de geschiedenis verbonden aan hun browser koekje wordt samengevoegd in.

>[!IMPORTANT]
>
>De bètafunctie inschakelen **Munchkin V2 Anonieme replay-activiteit op bekende** zorgt ervoor dat campagnes die worden geactiveerd door anonieme leads altijd worden afgespeeld nadat de anonieme lead is samengevoegd in de bekende record. Als gevolg hiervan blijven aangepaste velden die zijn gewijzigd door de stappen Gegevenswaarde wijzigen in opnieuw afgespeelde campagnes behouden in de bekende record.

**Anoniem** activiteit wordt gecreeerd wanneer iemand:

* Bezoekt de eerste keer je Marketo-landingspagina.
* Bezoek een pagina op uw site die [Munchkin-tracking](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md){target="_blank"}.
* Klik op de knop [Weergeven als webpagina](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md){target="_blank"} in een Marketo-e-mailbericht.

>[!NOTE]
>
>In tegenstelling tot andere links in e-mailberichten van Marketo, [Weergeven als webpagina](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md){target="_blank"} wordt niet bijgehouden als een e-mailklik.

Een anonieme activiteit wordt samengevoegd in een nieuwe of bestaande persoon wanneer iemand:

* Klik op een [koppeling in een Marketo-e-mailbericht](/help/marketo/product-docs/email-marketing/general/using-tokens/add-a-system-token-as-a-link-in-an-email.md){target="_blank"}.
* Hiermee vult u een Marketo in [Formulier](/help/marketo/product-docs/demand-generation/forms/form-actions/embed-a-form-on-your-website.md){target="_blank"}.
* Gebruikt Marketo [SOAP](/help/marketo/product-docs/administration/additional-integrations/configuring-your-soap-api-settings.md){target="_blank"} or [Munchkin](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md){target="_blank"} API (voor ontwikkelaars) om een anonieme persoon te associëren met een bekende record.

Eén naam in de database kan aan veel cookies zijn gekoppeld, omdat mensen vaak verschillende apparaten en browsers gebruiken om uw site te bezoeken.

>[!NOTE]
>
>Wanneer anonieme records worden samengevoegd in een nieuw of bestaand persoonrecord, worden aangepaste veldwaarden gebruikt *niet* overdracht over.
