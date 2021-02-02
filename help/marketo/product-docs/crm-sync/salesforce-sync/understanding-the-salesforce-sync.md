---
unique-page-id: 4719283
description: De Salesforce Sync - Marketo Docs - Productdocumentatie begrijpen
title: Werken met Salesforce Sync
translation-type: tm+mt
source-git-commit: 2b5ccd7220557a5e966d33436d0f0d2a65e4589d
workflow-type: tm+mt
source-wordcount: '219'
ht-degree: 0%

---


# De Salesforce Sync {#understanding-the-salesforce-sync} begrijpen

Marketo en Salesforce gaan samen als erwten en wortelen. We houden je verkoop- en marketinggegevens synchroon.

## Hoe synchroniseren werkt {#how-sync-works}

Marketo synchroniseert de hele dag met Salesforce. Elke synchronisatie neemt wat tijd in beslag en pauzeert vervolgens 5 minuten en start vervolgens opnieuw.

>[!NOTE]
>
>De allereerste synchronisatie in uw abonnement kan uren of zelfs dagen in beslag nemen omdat Marketo de volledige database van Salesforce kopieert. Daarna neemt elke synchronisatie doorgaans seconden of minuten in beslag en worden alleen gegevens gesynchroniseerd die zijn gewijzigd.

![](assets/sync-illustration.png)

De synchronisatie tussen Salesforce en Marketo is bidirectioneel slechts voor lood, contacten, en campagnes Salesforce. In deze gevallen, wanneer u veranderingen in of Salesforce of Marketo aanbrengt, zullen uw updates in beide systemen worden weerspiegeld. Alle andere syncs zijn van Salesforce aan Marketo slechts. Klik op de onderstaande koppelingen voor meer informatie.

## Wat is Synced tussen Marketo en Salesforce? {#what-is-synced-between-marketo-and-salesforce}

* [Leads](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-lead-sync.md)
* [Contactpersonen](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-contact-sync.md)
* [Accounts](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-account-sync.md)
* [Gebruikers](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-lead-account-owner-sync.md)
* [Kansen](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-opportunity-sync.md)
* [Salesforce-campagnes](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-campaign-sync.md)
* [Aangepaste objecten](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-custom-object-sync.md)
* [Activiteit](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-activity-sync.md)

>[!NOTE]
>
>De [geloofsbrieven u in Marketo voor Salesforce](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md) ingaat worden gebruikt om gegevens over te synchroniseren. Alleen gegevens waartoe deze referenties toegang hebben, worden opgenomen.

Marketo&#39;s synchronisatie met Salesforce is de krachtigste van zijn soort ter wereld. Het voelt als magie; er wordt een wijziging aangebracht en het andere systeem is binnenkort bijgewerkt.
