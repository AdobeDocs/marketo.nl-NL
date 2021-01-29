---
unique-page-id: 10098625
description: Werken met Microsoft Dynamics Sync - Marketo Docs - Productdocumentatie
title: Werken met Microsoft Dynamics Sync
translation-type: tm+mt
source-git-commit: 20d4c8a079916f47267df3dab5a8e663f6eb019b
workflow-type: tm+mt
source-wordcount: '228'
ht-degree: 0%

---


# Werken met Microsoft Dynamics Sync {#understanding-the-microsoft-dynamics-sync}

Marketo en Microsoft Dynamics gaan samen. We houden je verkoop- en marketinggegevens synchroon.

>[!NOTE]
>
>Marketo ondersteunt alleen SSL-certificaten die op dit moment compatibel zijn met Java 7.

## Hoe synchroniseren werkt {#how-sync-works}

Marketo synchroniseert voortdurend gegevens met de Dynamica van Microsoft de hele dag, elke dag. Het is klaar met achtergrondsynchronisatie, in batches, niet in real time.

>[!NOTE]
>
>De allereerste synchronisatie in uw abonnement neemt minuten tot uren in beslag, afhankelijk van de grootte van uw database. Marketo kopieert de volledige database van Dynamics. Daarna neemt elke synchronisatie doorgaans seconden of minuten in beslag en worden alleen gegevens gesynchroniseerd die zijn gewijzigd.

De synchronisatie tussen Marketo en Dynamics is bidirectioneel voor leads en contacten. Als u veranderingen in of Marketo of Dynamiek aanbrengt, zullen uw updates in beide systemen worden weerspiegeld. Alle andere gebieden, zoals rekeningen en kansen, worden slechts één manier gesynchroniseerd, van Dynamiek aan Marketo.

## Wat is Gesynchroniseerd tussen Marketo en de Dynamica van Microsoft? {#what-is-synced-between-marketo-and-microsoft-dynamics}

* [Leads](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-lead-sync.md)
* [Contactpersonen](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-contact-sync.md)
* [Accounts](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-account-sync.md)
* [Gebruikers](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-user-sync.md)
* Teams (groepen SystemUsers)
* [Kansen](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-opportunity-sync.md)
* [Aangepaste entiteiten](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-custom-entity-sync.md)

>[!NOTE]
>
>De [geloofsbrieven u in Marketo voor Dynamiek ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365/step-2-of-3-set-up.md) ingaat worden gebruikt om gegevens over te synchroniseren.

>[!CAUTION]
>
>Momenteel ondersteunen we sandbox-vernieuwing voor Marketo Dynamics Sync niet. Als u uw zandbak van CRM van de Dynamica moet verfrissen, zal een nieuwe zandbak van de Marketo worden vereist. Neem contact op met de succesmanager van de klant voor meer informatie.
