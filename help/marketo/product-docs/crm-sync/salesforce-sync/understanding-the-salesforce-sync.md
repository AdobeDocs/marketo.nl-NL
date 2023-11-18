---
unique-page-id: 4719283
description: De Salesforce Sync - Marketo Docs - Productdocumentatie begrijpen
title: Werken met Salesforce Sync
exl-id: 658c81ff-5fb3-4ad8-8759-da55bbf4e263
feature: Salesforce Integration
source-git-commit: 4045f262889d06304111288d30da893529396e81
workflow-type: tm+mt
source-wordcount: '220'
ht-degree: 0%

---

# Werken met Salesforce Sync {#understanding-the-salesforce-sync}

Marketo Engage en Salesforce gaan samen als erwten en wortelen. We houden je verkoop- en marketinggegevens synchroon.

## Hoe synchroniseren werkt {#how-sync-works}

Marketo synchroniseert de hele dag met Salesforce, elke dag. Elke synchronisatie neemt wat tijd in beslag en pauzeert vervolgens 5 minuten en start vervolgens opnieuw.

>[!NOTE]
>
>De allereerste synchronisatie in uw abonnement kan uren of zelfs dagen in beslag nemen omdat Marketo de volledige database van Salesforce kopieert. Daarna neemt elke synchronisatie doorgaans seconden of minuten in beslag en worden alleen gegevens gesynchroniseerd die zijn gewijzigd.

![](assets/sync-illustration.png)

De synchronisatie tussen Salesforce en Marketo is bidirectioneel alleen voor leads, contacten en Salesforce-campagnes. In deze gevallen, wanneer u veranderingen in of Salesforce of Marketo aanbrengt, zullen uw updates in beide systemen worden weerspiegeld. Alle andere syncs zijn van Salesforce aan Marketo slechts. Klik op de onderstaande koppelingen voor meer informatie.

## Wat is Synced tussen Marketo en Salesforce? {#what-is-synced-between-marketo-and-salesforce}

* [Leads](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-lead-sync.md){target="_blank"}
* [Contactpersonen](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-contact-sync.md){target="_blank"}
* [Accounts](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-account-sync.md){target="_blank"}
* [Gebruikers](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-lead-account-owner-sync.md){target="_blank"}
* [Kansen](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-opportunity-sync.md){target="_blank"}
* [Salesforce-campagnes](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-campaign-sync.md){target="_blank"}
* [Aangepaste objecten](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-custom-object-sync.md){target="_blank"}
* [Activiteit](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-activity-sync.md){target="_blank"}

>[!NOTE]
>
>De [aanmeldingsgegevens die u in Marketo voor Salesforce hebt ingevoerd](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md){target="_blank"} worden gebruikt om gegevens te synchroniseren. Alleen gegevens waartoe deze referenties toegang hebben, worden opgenomen.

Marketo sync met Salesforce is het krachtigste van zijn soort ter wereld. Het voelt als magie; er wordt een verandering aangebracht en het andere systeem is binnenkort up-to-date.
