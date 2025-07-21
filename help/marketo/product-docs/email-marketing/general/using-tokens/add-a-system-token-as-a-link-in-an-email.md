---
unique-page-id: 1900573
description: Een systeemtoken toevoegen als een koppeling in een e-mail - Marketo Docs - Productdocumentatie
title: Een systeemtoken toevoegen als een koppeling in een e-mailbericht
exl-id: 9156be24-18ae-44ea-96e5-a6257ff29b46
feature: Tokens
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '205'
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
>Deze tokens zullen **niet** klikbaar zijn tenzij binnen een ankerverbinding. Ook, kunnen zij **niet** in Mijn Token worden ingebed.

Hieronder wordt beschreven hoe u ze aan een e-mail kunt toevoegen:

1. Zoek en selecteer uw e-mail en klik vervolgens op **[!UICONTROL Edit Draft]** .

   ![](assets/one-1.png)

1. Dubbelklik in een bewerkbaar gebied.

   ![](assets/two-1.png)

1. Markeer de tekst die u naar een koppeling wilt converteren die de token zal hebben en klik op de knop **[!UICONTROL Insert/Edit Link]** .

   ![](assets/three-1.png)

1. Voer het token in de URL van de koppeling in en klik op **[!UICONTROL Insert]** .

   ![](assets/four-1.png)

   >[!TIP]
   >
   >Kopieer/plak de gewenste token: **`{{system.forwardToFriendLink}}`** of **`{{system.unsubscribeLink}}`** of **`{{system.viewAsWebpageLink}}`**

1. Klik op **[!UICONTROL Save]**.

   ![](assets/image2014-9-17-22-3a12-3a17.png)

>[!IMPORTANT]
>
>Als u deze benadering gebruikt om het &quot;viewAsWebpageLink&quot;systeemteken toe te voegen, kunt u **niet** het met behulp van tokens met voeten treden. In plaats daarvan, gebruik [ een Mening als Verbinding van de Pagina van het Web aan een e-mail ](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md) benadering toevoegen die u toestaat om &quot;viewAsWebPageLink&quot;met behulp van tokens met voeten te treden.

>[!NOTE]
>
>Vergeet niet [ uw e-mail ](/help/marketo/product-docs/email-marketing/general/creating-an-email/approve-an-email.md) goed te keuren wanneer gedaan.

Echt waar! Nu weet u hoe u een systeemtoken als een koppeling in een e-mail kunt toevoegen.
