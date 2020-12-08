---
unique-page-id: 4719283
description: De Salesforce Sync - Marketo Docs - Productdocumentatie begrijpen
title: Werken met Salesforce Sync
translation-type: tm+mt
source-git-commit: 00887ea53e395bea3a11fd28e0ac98b085ef6ed8
workflow-type: tm+mt
source-wordcount: '265'
ht-degree: 0%

---


# Werken met Salesforce Sync {#understanding-the-salesforce-sync}

Marketo en Salesforce gaan samen als erwten en wortelen. We houden je verkoop- en marketinggegevens synchroon.

## Hoe synchroniseren werkt {#how-sync-works}

Marketo synchroniseert de hele dag met Salesforce. Elke synchronisatie neemt wat tijd in beslag en pauzeert vervolgens 5 minuten en start vervolgens opnieuw.

>[!NOTE]
>
>De allereerste synchronisatie in uw abonnement kan uren of zelfs dagen in beslag nemen omdat Marketo de volledige database van Salesforce kopieert. Daarna neemt elke synchronisatie doorgaans seconden of minuten in beslag en worden alleen gegevens gesynchroniseerd die zijn gewijzigd.

![](assets/sync-illustration.png)

De synchronisatie tussen Salesforce en Marketo is bidirectioneel slechts voor lood, contacten, en campagnes Salesforce. In deze gevallen, wanneer u veranderingen in of Salesforce of Marketo aanbrengt, zullen uw updates in beide systemen worden weerspiegeld. Alle andere syncs zijn van Salesforce aan Marketo slechts. Klik op de onderstaande koppelingen voor meer informatie.

## Wat is Synced tussen Marketo en Salesforce? {#what-is-synced-between-marketo-and-salesforce}

* [Leads](sfdc-sync-details/sfdc-sync-lead-sync.md)
* [Contactpersonen](sfdc-sync-details/sfdc-sync-contact-sync.md)
* [Accounts](sfdc-sync-details/sfdc-sync-account-sync.md)
* [Gebruikers](sfdc-sync-details/sfdc-sync-lead-account-owner-sync.md)
* [Kansen](sfdc-sync-details/sfdc-sync-opportunity-sync.md)
* [Salesforce-campagnes](sfdc-sync-details/sfdc-sync-campaign-sync.md)
* [Aangepaste objecten](sfdc-sync-details/sfdc-sync-custom-object-sync.md)
* [Activiteit](sfdc-sync-details/sfdc-sync-activity-sync.md)

>[!NOTE]
>
>De [referenties die u invoert in Marketo voor Salesforce](setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md) worden gebruikt om gegevens te synchroniseren. Alleen gegevens waartoe deze referenties toegang hebben, worden opgenomen.

Er zijn veel nuances en functies over de Salesforce-synchronisatie. Bekijk de details in de sectie [](http://docs.marketo.com/display/docs/sfdc+sync+details)SFDC-synchronisatiedetails.

>[!NOTE]
>
>**Verwante artikelen**
>
>* [Salesforce Sync Setup](http://docs.marketo.com/display/docs/setup)
>* [SFDC-synchronisatiedetails](http://docs.marketo.com/display/docs/sfdc+sync+details)

>



Marketo&#39;s synchronisatie met Salesforce is de krachtigste van zijn soort ter wereld. Het voelt als magie - er wordt een verandering aangebracht en het andere systeem is binnenkort up-to-date.