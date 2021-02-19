---
unique-page-id: 11376159
description: Voordat u pushmeldingen en in-app berichten maakt - Marketo Docs - Productdocumentatie
title: Voordat u pushberichten en in-app-berichten maakt
translation-type: tm+mt
source-git-commit: 972cf9769ac751d9abfd5665975703dcd07930f0
workflow-type: tm+mt
source-wordcount: '352'
ht-degree: 0%

---


# Voordat u pushmeldingen en in-app berichten maakt {#before-you-create-push-notifications-and-in-app-messages}

Het is niet moeilijk om pushmeldingen en in-app-berichten te maken, maar u moet alles klaar hebben voordat u kunt starten. De ontwikkelaar van de app Marketo Admin en mobile moet de onderstaande stappen volgen om de noodzakelijke integratie voor te bereiden.

1. Eerst voegt de Marketo-beheerder [een mobiele app](/help/marketo/product-docs/mobile-marketing/admin/add-a-mobile-app.md) toe.

1. Marketo Admin verzendt dan [een codefragment naar de ontwikkelaar](/help/marketo/product-docs/mobile-marketing/admin/send-sdk-code-to-a-developer.md).

1. De ontwikkelaar downloadt de SDK en bevat fragmenten en andere methoden voor [Android](https://developers.marketo.com/documentation/mobile/installation-instructions-on-android/) of [iOS](https://developers.marketo.com/documentation/mobile/installation-instructions-on-ios/).

1. Standaard worden in-app berichten geactiveerd wanneer uw app wordt geopend. Als u berichten voor andere gebeurtenissen wilt teweegbrengen, zoals wanneer een bepaalde pagina wordt bekeken of een specifieke knoop wordt geduwd, moet de ontwikkelaar douanegebeurtenissen aan de code toevoegen (zie [Aangepaste Gebeurtenissen voor Berichten In-App ](#CustomEvents) hieronder).

1. De ontwikkelaar [genereert de server-API-sleutel en het projectnummer voor Android](https://developers.marketo.com/documentation/mobile/enabling-push-notifications-on-android/) of [de certificering en het wachtwoord voor iOS](https://developers.marketo.com/documentation/mobile/enabling-push-notifications-on-ios/) en verzendt deze naar de Marketo-beheerder.

1. De beheerder van de Marketo vormt de toegang van de dupmelding [met de sleutel van de Server API (Android)](/help/marketo/product-docs/mobile-marketing/admin/configure-mobile-app-android-push-access.md) of [met het certificaat (iOS)](/help/marketo/product-docs/mobile-marketing/admin/configure-mobile-app-ios-push-access.md).

>[!TIP]
>
>Een Marketo-beheerder kan eenvoudig controleren of uw pushconfiguratie is geverifieerd. Ga [hier](/help/marketo/product-docs/mobile-marketing/admin/verify-push-configuration.md).

## Aangepaste gebeurtenissen voor in-app berichten {#custom-events-for-in-app-messages}

Voor in-app overseinen, wordt de vertoningstrekker geplaatst aan **App Open** door gebrek. Als u aangepaste gebeurtenissen wilt gebruiken om de weergave van berichten in de app te activeren (klik bijvoorbeeld op **Toevoegen aan winkelwagentje**, **Weergave-instellingen Pagina**), maakt u een lijst met gewenste gebeurtenissen en geeft u deze door aan de ontwikkelaar van mobiele apps. De ontwikkelaar voegt de aangepaste gebeurtenissen vervolgens toe aan de code. Nadat ze zijn goedgekeurd, worden ze weergegeven als weergave-triggers bij het instellen van het publiek. **Waarschuwing**: Het goedkeuringsproces voor aangepaste gebeurteniscodes kan enige tijd duren.

Nadat u al uw voorbereidingen voor in-app berichten en dupmeldingen hebt gedaan, is het tijd om aan de slag te gaan!

>[!MORELIKETHIS]
>
>* [Een bericht in de app maken](/help/marketo/product-docs/mobile-marketing/in-app-messages/creating-in-app-messages/create-an-in-app-message.md)
   >
   >
* [Een pushmelding maken](/help/marketo/product-docs/mobile-marketing/push-notifications/create-a-push-notification.md)

