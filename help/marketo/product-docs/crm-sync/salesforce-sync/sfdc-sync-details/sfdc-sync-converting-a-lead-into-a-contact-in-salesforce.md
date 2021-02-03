---
unique-page-id: 2953465
description: SFDC-synchronisatie - Een lead converteren naar een contactpersoon in Salesforce - Marketo Docs - Productdocumentatie
title: SFDC Sync - Een lead converteren naar een contactpersoon in Salesforce
translation-type: tm+mt
source-git-commit: ed83438ae5660d172e845f25c4d72d599574bd91
workflow-type: tm+mt
source-wordcount: '158'
ht-degree: 0%

---


# SFDC-synchronisatie: Een lead omzetten in een contactpersoon in Salesforce {#sfdc-sync-converting-a-lead-into-a-contact-in-salesforce}

Stel je drie verschillende scenario&#39;s voor in Salesforce: (geen [Personstroom converteren](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/convert-person.md) in Marketo)

1. Een lead converteren naar een **nieuwe contactpersoon en een nieuwe account**
1. Een lead converteren naar een **nieuwe contactpersoon** in een **bestaande account**

1. Een lead omzetten in een **bestaand contact** in een **bestaande account** (dit werkt identiek aan [samenvoegen](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-merging-a-lead-contact-person.md))

In alle drie gevallen krijgt u **1 contact en geen leads in Salesforce en 1 contact en geen personen in Marketo.**

In Marketo heeft de record nu een SFDC Type = Contact.

>[!TIP]
>
>Wanneer het omzetten in Salesforce, zorg ervoor uw [lood douanegebieden goed worden in kaart gebracht](https://help.salesforce.com/apex/HTViewHelpDoc?id=customize_mapleads.htm). U wilt geen gegevens verliezen.

U kunt triggeren en filteren met: &quot;Lood is omgezet&quot; en &quot;Lood is omgezet.&quot;
