---
unique-page-id: 1900573
description: Een systeemtoken toevoegen als een koppeling in een e-mail - Marketo Docs - Productdocumentatie
title: Een systeemtoken toevoegen als een koppeling in een e-mailbericht
exl-id: 9156be24-18ae-44ea-96e5-a6257ff29b46
feature: Tokens
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '212'
ht-degree: 0%

---

# Een systeemtoken toevoegen als een koppeling in een e-mailbericht {#add-a-system-token-as-a-link-in-an-email}

U kunt deze systeemtokens gebruiken om de positie van speciale koppelingen in uw e-mails aan te passen.

De volgende tokens kunnen als koppelingen in een e-mailsjabloon of e-mailsjabloon worden gebruikt:

* `{{system.forwardToFriendLink}}`
* `{{system.unsubscribeLink}}`
* `{{system.viewAsWebpageLink}}`

>[!NOTE]
>
>Deze tokens **niet** kan worden geklikt, tenzij binnen een ankerkoppeling. Ze kunnen ook **niet** worden ingebed in Mijn Token.

Hieronder wordt beschreven hoe u ze aan een e-mail kunt toevoegen:

1. Zoek en selecteer uw e-mail en klik vervolgens op **Concept bewerken**.

   ![](assets/one-1.png)

1. Dubbelklik in een bewerkbaar gebied.

   ![](assets/two-1.png)

1. Markeer de tekst die u wilt omzetten in een koppeling die het token bevat en klik op de knop **Koppeling invoegen/bewerken** knop.

   ![](assets/three-1.png)

1. Voer het token in de URL van de koppeling in en klik op **Invoegen**.

   ![](assets/four-1.png)

   >[!TIP]
   >
   >Kopieer/plak de gewenste token: **`{{system.forwardToFriendLink}}`** of **`{{system.unsubscribeLink}}`** of **`{{system.viewAsWebpageLink}}`**

1. Klikken **Opslaan**.

   ![](assets/image2014-9-17-22-3a12-3a17.png)

>[!IMPORTANT]
>
>Als u deze benadering gebruikt om het &quot;viewAsWebpageLink&quot;systeemteken toe te voegen, kunt u **niet** Gebruik tokens om deze te negeren. Gebruik in plaats daarvan [Een koppeling Weergeven als webpagina toevoegen aan een e-mailbericht](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md) aanpak waarmee u &quot;viewAsWebPageLink&quot; kunt negeren met behulp van tokens.

>[!NOTE]
>
>Vergeet niet om [uw e-mail goedkeuren](/help/marketo/product-docs/email-marketing/general/creating-an-email/approve-an-email.md) wanneer gereed.

Echt waar! Nu weet u hoe u een systeemtoken als een koppeling in een e-mail kunt toevoegen.
