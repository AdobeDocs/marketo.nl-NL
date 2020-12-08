---
unique-page-id: 11376159
description: Voordat u pushmeldingen en in-app berichten maakt - Marketo Docs - Productdocumentatie
title: Voordat u pushberichten en in-app-berichten maakt
translation-type: tm+mt
source-git-commit: d88fb92a00e4c20509617e6ef8b2e51b66cc085b
workflow-type: tm+mt
source-wordcount: '362'
ht-degree: 0%

---


# Voordat u pushberichten en in-app-berichten maakt {#before-you-create-push-notifications-and-in-app-messages}

Het is niet moeilijk om pushmeldingen en in-app-berichten te maken, maar u moet alles klaar hebben voordat u kunt starten. De ontwikkelaar van de app Marketo Admin en mobile moet de onderstaande stappen volgen om de noodzakelijke integratie voor te bereiden.

1. Eerst [voegt de Marketo Admin een mobiele app toe](add-a-mobile-app.md)
1. De beheerder van de Marketo [verzendt dan een codefragment naar de ontwikkelaar](send-sdk-code-to-a-developer.md)
1. De ontwikkelaar downloadt de SDK, inclusief fragmenten en andere methoden, voor [Android](http://developers.marketo.com/documentation/mobile/installation-instructions-on-android/) of [iOS](http://developers.marketo.com/documentation/mobile/installation-instructions-on-ios/)
1. Standaard worden in-app berichten geactiveerd wanneer uw app wordt geopend. Als u berichten voor andere gebeurtenissen wilt teweegbrengen, zoals wanneer een bepaalde pagina wordt bekeken of een specifieke knoop wordt geduwd, moet de ontwikkelaar douanegebeurtenissen aan de code toevoegen (zie de Gebeurtenissen van de [Douane voor Berichten](#CustomEvents) in-App hieronder)
1. De ontwikkelaar [genereert de Server API-sleutel en het projectnummer voor Android](http://developers.marketo.com/documentation/mobile/enabling-push-notifications-on-android/) of [de certificering en het wachtwoord voor iOS](http://developers.marketo.com/documentation/mobile/enabling-push-notifications-on-ios/) en stuurt deze naar de Marketo Admin
1. De Marketo-beheerder configureert de toegang tot pushberichten [met de Server API-sleutel (Android)](configure-mobile-app-android-push-access.md) of [met het certificaat (iOS)](configure-mobile-app-ios-push-access.md)

>[!TIP]
>
>Een Marketo-beheerder kan eenvoudig controleren of uw pushconfiguratie is geverifieerd. Ga gewoon [hier](verify-push-configuration.md).

## Aangepaste gebeurtenissen voor In-App-berichten {#custom-events-for-in-app-messages}

Voor berichten in de app is de trigger voor de weergave standaard ingesteld op **App Open** . Als u aangepaste gebeurtenissen wilt gebruiken om de weergave van berichten in de app te activeren (klik bijvoorbeeld op **Toevoegen aan winkelwagentje**, **Weergaveinstellingenpagina**), maakt u een lijst met gewenste gebeurtenissen en geeft u deze door aan de ontwikkelaar van mobiele apps. De ontwikkelaar voegt de aangepaste gebeurtenissen vervolgens toe aan de code. Nadat ze zijn goedgekeurd, worden ze weergegeven als weergave-triggers bij het instellen van het publiek. **Waarschuwing**: Het goedkeuringsproces voor aangepaste gebeurteniscodes kan enige tijd duren.

Nadat u al uw voorbereidingen voor in-app berichten en dupmeldingen hebt gedaan, is het tijd om aan de slag te gaan!

>[!NOTE]
>
>**Verwante artikelen**
>
>* [Een bericht in de app maken](http://docs.marketo.com/display/docs/create+an+in-app+message)
   >
   >
* [Een pushmelding maken](../../../product-docs/mobile-marketing/push-notifications/create-a-push-notification.md)

>



