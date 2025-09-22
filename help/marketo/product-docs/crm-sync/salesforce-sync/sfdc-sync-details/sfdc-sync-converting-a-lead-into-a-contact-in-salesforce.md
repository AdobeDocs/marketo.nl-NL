---
unique-page-id: 2953465
description: SFDC Sync - Een lead converteren naar een contactpersoon in Salesforce - Marketo Docs - Productdocumentatie
title: SFDC Sync - Een lead converteren naar een contactpersoon in Salesforce
exl-id: 9c9dbe9a-80a6-4153-ac86-96f85025fe77
feature: Salesforce Integration
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '144'
ht-degree: 0%

---

# SFDC Sync: Een lead converteren naar een contactpersoon in [!DNL Salesforce] {#sfdc-sync-converting-a-lead-into-a-contact-in-salesforce}

Stel zich drie verschillende scenario&#39;s in [!DNL Salesforce] voor: (het gebruiken van [ de stap van de de stroom van de Persoon van de Bekeerling ](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/convert-person.md) in Marketo)

1. Het omzetten van een Lood in a **nieuw contact en nieuwe rekening**
1. Het omzetten van een Lood in a **nieuw contact** in een **bestaande rekening**

1. Het omzetten van aLood in een **bestaand contact** in een **bestaande rekening** (dit werkt identiek aan [ het samenvoegen ](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-merging-a-lead-contact-person.md){target="_blank"})

In alle drie gevallen beëindigt u omhoog met **1 contact en geen lood in [!DNL Salesforce] en 1 contact en geen mensen in Marketo.**

In Marketo heeft de record nu het SFDC Type = Contact.

>[!TIP]
>
>Wanneer het omzetten in [!DNL Salesforce], zorg ervoor uw [ lood douanegebieden goed ](https://help.salesforce.com/apex/HTViewHelpDoc?id=customize_mapleads.htm) in kaart worden gebracht. U wilt geen gegevens verliezen.

U kunt triggeren en filtreren gebruikend: &quot;[!UICONTROL Lead is Converted]&quot; en &quot;[!UICONTROL Lead was Converted]&quot;.
