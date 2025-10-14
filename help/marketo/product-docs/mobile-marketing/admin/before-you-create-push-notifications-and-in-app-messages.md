---
unique-page-id: 11376159
description: Voordat u pushmeldingen en in-app berichten maakt - Marketo Docs - Productdocumentatie
title: Voordat u pushberichten en in-app-berichten maakt
exl-id: c7e24338-387b-4c6f-bb29-7f7e6a1a7de5
feature: Mobile Marketing
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '334'
ht-degree: 0%

---

# Voordat u pushberichten en in-app-berichten maakt {#before-you-create-push-notifications-and-in-app-messages}

Het is niet moeilijk om pushmeldingen en in-app-berichten te maken, maar u moet alles klaar hebben voordat u kunt starten. De ontwikkelaar van Marketo Admin en mobiele apps moet de onderstaande stappen volgen om de noodzakelijke integratie voor te bereiden.

1. Eerst, voegt Marketo Admin [&#x200B; een mobiele app &#x200B;](/help/marketo/product-docs/mobile-marketing/admin/add-a-mobile-app.md) toe.

1. Marketo Admin verzendt dan [&#x200B; een codefragment naar de ontwikkelaar &#x200B;](/help/marketo/product-docs/mobile-marketing/admin/send-sdk-code-to-a-developer.md).

1. De ontwikkelaar downloadt SDK, en omvat fragment en andere methodes, voor [&#x200B; Android &#x200B;](https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/mobile/installation#how-to-install-marketo-sdk-on-android) of [&#x200B; iOS &#x200B;](https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/mobile/installation#how-to-install-marketo-sdk-on-ios).

1. Standaard worden in-app berichten geactiveerd wanneer uw app wordt geopend. Als u berichten voor andere gebeurtenissen wilt teweegbrengen, zoals wanneer een bepaalde pagina wordt bekeken of een specifieke knoop wordt geduwd, moet de ontwikkelaar douanegebeurtenissen aan de code toevoegen (zie [&#x200B; Gebeurtenissen van de Douane voor Berichten In-App &#x200B;](#CustomEvents) hieronder).

1. De ontwikkelaar [&#x200B; produceert de sleutel en het projectaantal van de Server API voor Android &#x200B;](https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/mobile/installation#how-to-install-marketo-sdk-on-android) of [&#x200B; de certificatie en het wachtwoord voor iOS &#x200B;](https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/mobile/installation#install-marketo-sdk-on-ios) en verzendt het naar Marketo Admin.

1. Marketo Admin vormt de toegang van het duw- bericht [&#x200B; met de Server API sleutel (Android) &#x200B;](/help/marketo/product-docs/mobile-marketing/admin/configure-mobile-app-android-push-access.md) of [&#x200B; met het certificaat (iOS) &#x200B;](/help/marketo/product-docs/mobile-marketing/admin/configure-mobile-app-ios-push-access.md).

>[!TIP]
>
>Een Marketo Admin kan eenvoudig controleren of uw pushconfiguratie is geverifieerd. Ga enkel [&#x200B; hier &#x200B;](/help/marketo/product-docs/mobile-marketing/admin/verify-push-configuration.md).

## Aangepaste gebeurtenissen voor In-App-berichten {#custom-events-for-in-app-messages}

Voor in-app berichten wordt de weergavemarkering standaard ingesteld op **[!UICONTROL App Open]** . Als u om het even welke douanegebeurtenissen wilt gebruiken om de vertoning van in-app berichten (bijvoorbeeld, **klikken toevoegen aan Kaart**, **Pagina van de Montages van Weergaven**) teweeg te brengen, creeer een lijst van gewenste gebeurtenissen en geef het aan uw mobiele apps ontwikkelaar. De ontwikkelaar voegt de aangepaste gebeurtenissen vervolgens toe aan de code. Nadat ze zijn goedgekeurd, worden ze weergegeven als weergave-triggers bij het instellen van het publiek. **Voorzichtigheid**: Het proces van de de codeergoedkeuring van de douanegebeurtenis kan wat tijd vergen om te voltooien.

Nadat u al uw voorbereidingen voor in-app berichten en dupmeldingen hebt gedaan, is het tijd om aan de slag te gaan!

>[!MORELIKETHIS]
>
>* [&#x200B; creeer een Bericht In-App &#x200B;](/help/marketo/product-docs/mobile-marketing/in-app-messages/creating-in-app-messages/create-an-in-app-message.md)
>
>* [&#x200B; creeer een Duw Bericht &#x200B;](/help/marketo/product-docs/mobile-marketing/push-notifications/create-a-push-notification.md)
