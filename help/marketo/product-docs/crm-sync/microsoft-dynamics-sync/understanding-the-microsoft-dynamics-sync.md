---
unique-page-id: 10098625
description: Microsoft Dynamics Sync - Marketo Docs - Productdocumentatie
title: Werken met Microsoft Dynamics Sync
exl-id: bc87f744-7f1c-421b-8507-1a6e23d27fa2
feature: Microsoft Dynamics
source-git-commit: 821d69736b1cbeac0c80718c58a7a3c471387545
workflow-type: tm+mt
source-wordcount: '246'
ht-degree: 0%

---

# Werken met Microsoft Dynamics Sync {#understanding-the-microsoft-dynamics-sync}

Marketo Engage en Microsoft Dynamics gaan samen. We houden je verkoop- en marketinggegevens synchroon.

>[!NOTE]
>
>Marketo ondersteunt alleen SSL-certificaten die op dit moment compatibel zijn met Java 7.

>[!CAUTION]
>
>Sandboxvernieuwing voor Marketo Dynamics Sync wordt momenteel niet ondersteund. Als u uw zandbak van CRM van de Dynamica moet verfrissen, zal een nieuwe zandbak van Marketo worden vereist. Neem contact op met het accountteam van de Adobe (uw accountmanager) voor meer informatie.

## Hoe synchroniseren werkt {#how-sync-works}

Marketo synchroniseert voortdurend gegevens met Microsoft Dynamics, de hele dag, elke dag. Het is klaar met achtergrondsynchronisatie, in batches, niet in real time.

>[!NOTE]
>
>De allereerste synchronisatie in uw abonnement neemt minuten tot uren in beslag, afhankelijk van de grootte van uw database. Marketo kopieert de gehele database van Dynamics. Daarna neemt elke synchronisatie doorgaans seconden of minuten in beslag en worden alleen gegevens gesynchroniseerd die zijn gewijzigd.

De synchronisatie tussen Marketo en Dynamics is bidirectioneel voor leads en contacten. Als u wijzigingen aanbrengt in Marketo of Dynamics, worden de updates weerspiegeld in beide systemen. Alle andere gebieden, zoals accounts en mogelijkheden, worden slechts op één manier gesynchroniseerd, van Dynamics tot Marketo.

## Wat is gesynchroniseerd tussen Marketo en Microsoft Dynamics? {#what-is-synced-between-marketo-and-microsoft-dynamics}

* [Leads](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-lead-sync.md)
* [Contactpersonen](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-contact-sync.md)
* [Accounts](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-account-sync.md)
* [Gebruikers](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-user-sync.md)
* Teams (groepen SystemUsers)
* [Kansen](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-opportunity-sync.md)
* [Aangepaste entiteiten](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/enable-sync-for-a-custom-entity.md)

De [gebruikersgegevens die u invoert in Marketo for Dynamics](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-2-of-4-set-up.md) worden gebruikt om gegevens te synchroniseren.

>[!NOTE]
>
>Instantiekopie wordt niet ondersteund als de broninstantie is geïntegreerd met Microsoft Dynamics.
