---
unique-page-id: 11376159
description: Voordat u pushmeldingen en in-app berichten maakt - Marketo Docs - Productdocumentatie
title: Voordat u pushberichten en in-app-berichten maakt
exl-id: c7e24338-387b-4c6f-bb29-7f7e6a1a7de5
feature: Mobile Marketing
source-git-commit: 2b610cc3486b745212b0b1f36018a83214d7ecd7
workflow-type: tm+mt
source-wordcount: '336'
ht-degree: 0%

---

# Voordat u pushberichten en in-app-berichten maakt {#before-you-create-push-notifications-and-in-app-messages}

Het is niet moeilijk om pushmeldingen en in-app-berichten te maken, maar u moet alles klaar hebben voordat u kunt starten. De ontwikkelaar van Marketo Admin en mobiele apps moet de onderstaande stappen volgen om de noodzakelijke integratie voor te bereiden.

1. Ten eerste, de Marketo Admin [voegt een mobiele app toe](/help/marketo/product-docs/mobile-marketing/admin/add-a-mobile-app.md).

1. De Marketo Admin [verzendt een codefragment naar de ontwikkelaar](/help/marketo/product-docs/mobile-marketing/admin/send-sdk-code-to-a-developer.md).

1. De ontwikkelaar downloadt de SDK, inclusief fragmenten en andere methoden, voor [Android](https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/mobile/installation#how-to-install-marketo-sdk-on-android) of [iOS](https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/mobile/installation#how-to-install-marketo-sdk-on-ios).

1. Standaard worden in-app berichten geactiveerd wanneer uw app wordt geopend. Als u berichten voor andere gebeurtenissen wilt teweegbrengen, zoals wanneer een bepaalde pagina wordt bekeken of een specifieke knoop wordt geduwd, moet de ontwikkelaar douanegebeurtenissen aan de code toevoegen (zie [Aangepaste gebeurtenissen voor In-App-berichten](#CustomEvents) hieronder).

1. De ontwikkelaar [Hiermee worden de API-sleutel en het projectnummer van de server voor Android gegenereerd](https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/mobile/installation#how-to-install-marketo-sdk-on-android) of [de certificering en het wachtwoord voor iOS](https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/mobile/installation#install-marketo-sdk-on-ios) en stuurt het naar de Marketo Admin.

1. Marketo Admin configureert de toegang tot pushberichten [met de Server API-sleutel (Android)](/help/marketo/product-docs/mobile-marketing/admin/configure-mobile-app-android-push-access.md) of [met het certificaat (iOS)](/help/marketo/product-docs/mobile-marketing/admin/configure-mobile-app-ios-push-access.md).

>[!TIP]
>
>Een Marketo Admin kan eenvoudig controleren of uw pushconfiguratie is geverifieerd. Ga gewoon door [hier](/help/marketo/product-docs/mobile-marketing/admin/verify-push-configuration.md).

## Aangepaste gebeurtenissen voor In-App-berichten {#custom-events-for-in-app-messages}

Voor in-app berichten wordt de weergavemarkering ingesteld op **App openen** standaard. Als u aangepaste gebeurtenissen wilt gebruiken om de weergave van berichten in de app te activeren (bijvoorbeeld **Klik op Toevoegen aan winkelwagentje**, **Pagina met weergaveinstellingen**), maakt u een lijst met gewenste gebeurtenissen en geeft u deze door aan uw ontwikkelaar van mobiele apps. De ontwikkelaar voegt de aangepaste gebeurtenissen vervolgens toe aan de code. Nadat ze zijn goedgekeurd, worden ze weergegeven als weergave-triggers bij het instellen van het publiek. **Waarschuwing**: Het kan enige tijd duren voordat het goedkeuringsproces voor de aangepaste gebeurteniscodering is voltooid.

Nadat u al uw voorbereidingen voor in-app berichten en dupmeldingen hebt gedaan, is het tijd om aan de slag te gaan!

>[!MORELIKETHIS]
>
>* [Een bericht in de app maken](/help/marketo/product-docs/mobile-marketing/in-app-messages/creating-in-app-messages/create-an-in-app-message.md)
>
>* [Een pushmelding maken](/help/marketo/product-docs/mobile-marketing/push-notifications/create-a-push-notification.md)
