---
unique-page-id: 4719283
description: Salesforce Sync - Marketo Docs - Productdocumentatie begrijpen
title: Werken met Salesforce Sync
exl-id: 658c81ff-5fb3-4ad8-8759-da55bbf4e263
feature: Salesforce Integration
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '212'
ht-degree: 0%

---

# Werken met [!DNL Salesforce] synchroniseren {#understanding-the-salesforce-sync}

Marketo Engage en Salesforce gaan samen als erwten en wortelen. We houden je verkoop- en marketinggegevens synchroon.

## Hoe synchroniseren werkt {#how-sync-works}

Marketo synchroniseert met [!DNL Salesforce] de hele dag, elke dag. Elke synchronisatie neemt wat tijd in beslag en pauzeert vervolgens 5 minuten en start vervolgens opnieuw.

>[!NOTE]
>
>De allereerste synchronisatie in uw abonnement kan uren of zelfs dagen in beslag nemen omdat Marketo de volledige database kopieert vanuit [!DNL Salesforce] . Daarna neemt elke synchronisatie doorgaans seconden of minuten in beslag en worden alleen gegevens gesynchroniseerd die zijn gewijzigd.

![](assets/sync-illustration.png)

De synchronisatie tussen [!DNL Salesforce] en Marketo is alleen in twee richtingen voor leads, contactpersonen en [!DNL Salesforce] -campagnes. In deze gevallen geldt dat wanneer u wijzigingen aanbrengt in [!DNL Salesforce] of Marketo, de updates worden weerspiegeld in beide systemen. Alle andere syncs zijn van [!DNL Salesforce] aan slechts Marketo. Klik op de onderstaande koppelingen voor meer informatie.

## Wat is gesynchroniseerd tussen Marketo en [!DNL Salesforce]? {#what-is-synced-between-marketo-and-salesforce}

* [ Leads ](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-lead-sync.md){target="_blank"}
* [ Contacten ](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-contact-sync.md){target="_blank"}
* [ Rekeningen ](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-account-sync.md){target="_blank"}
* [ Gebruikers ](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-lead-account-owner-sync.md){target="_blank"}
* [ Kansen ](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-opportunity-sync.md){target="_blank"}
* [ campagnes van Salesforce ](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-campaign-sync.md){target="_blank"}
* [ de voorwerpen van de Douane ](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-custom-object-sync.md){target="_blank"}
* [ Activiteit ](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-activity-sync.md){target="_blank"}

>[!NOTE]
>
>De [ geloofsbrieven u in Marketo voor Salesforce ](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md){target="_blank"} ingaat worden gebruikt om gegevens over te synchroniseren. Alleen gegevens waartoe deze referenties toegang hebben, worden opgenomen.

Marketo synchroniseren met [!DNL Salesforce] is het krachtigste van zijn soort ter wereld. Het voelt als magie; er wordt een verandering aangebracht en het andere systeem is binnenkort up-to-date.
