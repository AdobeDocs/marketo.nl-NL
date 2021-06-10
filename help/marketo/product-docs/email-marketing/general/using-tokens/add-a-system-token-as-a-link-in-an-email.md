---
unique-page-id: 1900573
description: Een systeemtoken toevoegen als een koppeling in een e-mail - Marketo Docs - Productdocumentatie
title: Een systeemtoken toevoegen als een koppeling in een e-mailbericht
exl-id: 9156be24-18ae-44ea-96e5-a6257ff29b46
source-git-commit: 65caed388ac33fc9f3142102343fe43ebc186e6e
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# Een systeemtoken toevoegen als een koppeling in een e-mail {#add-a-system-token-as-a-link-in-an-email}

U kunt deze systeemtokens gebruiken om de positie van speciale koppelingen in uw e-mails aan te passen.

De volgende tokens kunnen als koppelingen in een e-mailsjabloon of e-mailsjabloon worden gebruikt:

* `{{system.forwardToFriendLink}}`
* `{{system.unsubscribeLink}}`
* `{{system.viewAsWebpageLink}}`

>[!NOTE]
>
>Deze tokens zijn **niet** aanklikbaar tenzij binnen een ankerverbinding. Ook, kunnen zij **niet** in Mijn Token worden ingebed.

Hieronder wordt beschreven hoe u ze aan een e-mail kunt toevoegen:

1. Zoek en selecteer uw e-mail en klik vervolgens op **Concept bewerken**.

   ![](assets/one-1.png)

1. Dubbelklik in een bewerkbaar gebied.

   ![](assets/two-1.png)

1. Markeer de tekst die u wilt omzetten in een koppeling die de token zal hebben en klik op de knop **Koppeling invoegen/bewerken**.

   ![](assets/three-1.png)

1. Typ het token in de URL van de koppeling en klik op **Invoegen**.

   ![](assets/four-1.png)

   >[!TIP]
   >
   >Kopieer/plak de gewenste token: **`{{system.forwardToFriendLink}}`** of **`{{system.unsubscribeLink}}`** of **`{{system.viewAsWebpageLink}}`**

1. Klik **Opslaan**.

   ![](assets/image2014-9-17-22-3a12-3a17.png)

>[!IMPORTANT]
>
>Als u deze benadering gebruikt om het &quot;viewAsWebpageLink&quot;systeemteken toe te voegen, kunt u **not** het met behulp van tokens met voeten treden. Gebruik in plaats daarvan [Een weergave als webpaginakoppeling toevoegen aan een e-mailbenadering](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md) waarmee u &quot;viewAsWebPageLink&quot; kunt overschrijven met behulp van tokens.

>[!NOTE]
>
>Vergeet niet [uw e-mail](/help/marketo/product-docs/email-marketing/general/creating-an-email/approve-an-email.md) goed te keuren wanneer u klaar bent.

Echt waar! Nu weet u hoe u een systeemtoken als een koppeling in een e-mail kunt toevoegen.
