---
unique-page-id: 10098625
description: Werken met Microsoft Dynamics Sync - Marketo Docs - Productdocumentatie
title: Werken met Microsoft Dynamics Sync
translation-type: tm+mt
source-git-commit: dc20aede0894a09e6c0bcd3d1580859b5fecb5f1
workflow-type: tm+mt
source-wordcount: '278'
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

* [Leads](microsoft-dynamics-sync-details/microsoft-dynamics-sync-lead-sync.md)
* [Contactpersonen](microsoft-dynamics-sync-details/microsoft-dynamics-sync-contact-sync.md)
* [Accounts](microsoft-dynamics-sync-details/microsoft-dynamics-sync-account-sync.md)
* [Gebruikers](microsoft-dynamics-sync-details/microsoft-dynamics-sync-user-sync.md)
* Teams (groepen SystemUsers)
* [Kansen](microsoft-dynamics-sync-details/microsoft-dynamics-sync-opportunity-sync.md)
* [Aangepaste entiteiten](microsoft-dynamics-sync-details/microsoft-dynamics-sync-custom-entity-sync.md)

>[!NOTE]
>
>De [geloofsbrieven u in Marketo voor Dynamiek](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365/step-2-of-3-set-up.md) ingaat worden gebruikt om gegevens over te synchroniseren.

Er zijn vele nuances en eigenschappen over de synchronisatie van de Dynamica. Bekijk de details in de sectie [Details van de Synchronisatie van de Dynamica van](http://docs.marketo.com/display/docs/microsoft+dynamics+sync+details)Microsoft.

>[!CAUTION]
>
>Momenteel ondersteunen we sandbox-vernieuwing voor Marketo Dynamics Sync niet. Als u uw zandbak van CRM van de Dynamica moet verfrissen, zal een nieuwe zandbak van de Marketo worden vereist. Neem contact op met de succesmanager van de klant voor meer informatie.

>[!NOTE]
>
>**Verwante artikelen**
>
>* [Instellingen synchroniseren](http://docs.marketo.com/display/docs/sync+setup)
   >
   >
* [Gegevens Microsoft Dynamics Sync](http://docs.marketo.com/display/docs/microsoft+dynamics+sync+details)

