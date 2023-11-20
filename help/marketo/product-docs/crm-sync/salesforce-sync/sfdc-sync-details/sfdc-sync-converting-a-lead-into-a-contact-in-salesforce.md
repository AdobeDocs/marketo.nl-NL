---
unique-page-id: 2953465
description: SFDC Sync - Een lead converteren naar een contactpersoon in Salesforce - Marketo Docs - Productdocumentatie
title: SFDC Sync - Een lead converteren naar een contactpersoon in Salesforce
exl-id: 9c9dbe9a-80a6-4153-ac86-96f85025fe77
feature: Salesforce Integration
source-git-commit: 0087a5e88b8bd9601875f68a2e7cadeebdb5d682
workflow-type: tm+mt
source-wordcount: '159'
ht-degree: 0%

---

# SFDC Sync: Een lead converteren naar een contactpersoon in Salesforce {#sfdc-sync-converting-a-lead-into-a-contact-in-salesforce}

Stel je drie verschillende scenario&#39;s voor in Salesforce: (geen gebruik maken van de [Stroom van persoon omzetten](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/convert-person.md){target="_blank"} in Marketo Engage)

1. Een lead omzetten in een **nieuwe contactpersoon en nieuwe account**
1. Een lead omzetten in een **nieuwe contactpersoon** in een **bestaande account**

1. Een lead omzetten in een **bestaande contactpersoon** in een **bestaande account** (dit werkt hetzelfde als [samenvoegen](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-merging-a-lead-contact-person.md){target="_blank"})

In alle drie gevallen is het resultaat **1 contact en geen lood in Salesforce en 1 contact en geen mensen in Marketo.**

In Marketo heeft de record nu een SFDC Type = Contact.

>[!TIP]
>
>Zorg er bij omzetting in Salesforce voor dat [aangepaste hoofdvelden worden goed toegewezen](https://help.salesforce.com/apex/HTViewHelpDoc?id=customize_mapleads.htm){target="_blank"}. U wilt geen gegevens verliezen.

U kunt de elementen Lead is omgezet en Lead is omgezet activeren en filteren.
