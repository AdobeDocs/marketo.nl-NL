---
unique-page-id: 2953465
description: SFDC Sync - Een lead converteren naar een contactpersoon in Salesforce - Marketo Docs - Productdocumentatie
title: SFDC Sync - Een lead converteren naar een contactpersoon in Salesforce
exl-id: 9c9dbe9a-80a6-4153-ac86-96f85025fe77
feature: Salesforce Integration
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '158'
ht-degree: 0%

---

# SFDC-synchronisatie: Een lead omzetten in een contactpersoon in Salesforce {#sfdc-sync-converting-a-lead-into-a-contact-in-salesforce}

Stel je drie verschillende scenario&#39;s voor in Salesforce: (niet met de [Stroom van persoon omzetten](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/convert-person.md) in Marketo)

1. Een lead omzetten in een **nieuwe contactpersoon en nieuwe account**
1. Een lead omzetten in een **nieuwe contactpersoon** in een **bestaande account**

1. Een lead omzetten in een **bestaande contactpersoon** in een **bestaande account** (dit werkt hetzelfde als [samenvoegen](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-merging-a-lead-contact-person.md))

In alle drie gevallen is het resultaat **1 contact en geen lood in Salesforce en 1 contact en geen mensen in Marketo.**

In Marketo heeft de record nu een SFDC Type = Contact.

>[!TIP]
>
>Zorg er bij omzetting in Salesforce voor dat [aangepaste hoofdvelden worden goed toegewezen](https://help.salesforce.com/apex/HTViewHelpDoc?id=customize_mapleads.htm). U wilt geen gegevens verliezen.

U kunt triggeren en filteren met: &quot;Lood is omgezet&quot; en &quot;Lood is omgezet.&quot;
