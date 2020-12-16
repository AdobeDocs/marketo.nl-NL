---
unique-page-id: 2953465
description: SFDC-synchronisatie - Een lead converteren naar een contactpersoon in Salesforce - Marketo Docs - Productdocumentatie
title: SFDC Sync - Een lead converteren naar een contactpersoon in Salesforce
translation-type: tm+mt
source-git-commit: d7d6aee63144c472e02fe0221c4a164183d04dd4
workflow-type: tm+mt
source-wordcount: '158'
ht-degree: 0%

---


# SFDC-synchronisatie: Een lead omzetten in een contactpersoon in Salesforce {#sfdc-sync-converting-a-lead-into-a-contact-in-salesforce}

Stel je drie verschillende scenario&#39;s voor in Salesforce: (zonder de stap [Personstroom](../../../../product-docs/core-marketo-concepts/smart-campaigns/flow-actions/convert-person.md) omzetten in Marketo)

1. Een lead omzetten in een **nieuwe contactpersoon en een nieuwe account**
1. Een lead converteren naar een **nieuwe contactpersoon** in een **bestaande account**

1. Een lead omzetten in een **bestaande contactpersoon** in een **bestaande account** (dit werkt hetzelfde als [samenvoegen](sfdc-sync-merging-a-lead-contact-person.md))

In alle drie de gevallen belandt u met **1 contact en geen lood in Salesforce en 1 contact en geen mensen in Marketo.**

In Marketo heeft de record nu een SFDC Type = Contact.

>[!TIP]
>
>Wanneer u bestanden omzet in Salesforce, moet u ervoor zorgen dat de aangepaste velden voor [leads correct](https://help.salesforce.com/apex/HTViewHelpDoc?id=customize_mapleads.htm)worden toegewezen. U wilt geen gegevens verliezen.

U kunt triggeren en filteren met: &quot;Lood is omgezet&quot; en &quot;Lood is omgezet.&quot;