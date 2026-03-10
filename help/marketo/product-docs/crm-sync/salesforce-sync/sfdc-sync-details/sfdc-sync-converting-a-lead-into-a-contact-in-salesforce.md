---
unique-page-id: 2953465
description: Meer informatie over wat er gebeurt wanneer u een lead converteert naar een contactpersoon in Salesforce. Zie hoe Marketo de wijziging weergeeft en hoe Lead wordt gebruikt voor geconverteerde triggers en filters.
title: SFDC Sync - Een lead converteren naar een contactpersoon in Salesforce
exl-id: 9c9dbe9a-80a6-4153-ac86-96f85025fe77
feature: Salesforce Integration
source-git-commit: 2b29f05a27f847184e0968442012d443e9e0597d
workflow-type: tm+mt
source-wordcount: '158'
ht-degree: 0%

---

# SFDC Sync: Een lead converteren naar een contactpersoon in [!DNL Salesforce] {#sfdc-sync-converting-a-lead-into-a-contact-in-salesforce}

Stel zich drie verschillende scenario&#39;s in [!DNL Salesforce] voor: (het gebruiken van [&#x200B; de stap van de de stroom van de Persoon van de Bekeerling &#x200B;](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/convert-person.md) in Marketo)

1. Het omzetten van een Lood in a **nieuw contact en nieuwe rekening**
1. Het omzetten van een Lood in a **nieuw contact** in een **bestaande rekening**

1. Het omzetten van aLood in een **bestaand contact** in een **bestaande rekening** (dit werkt identiek aan [&#x200B; het samenvoegen &#x200B;](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-merging-a-lead-contact-person.md){target="_blank"})

In alle drie gevallen beëindigt u omhoog met **1 contact en geen lood in [!DNL Salesforce] en 1 contact en geen mensen in Marketo.**

In Marketo heeft de record nu het SFDC Type = Contact.

>[!TIP]
>
>Wanneer het omzetten in [!DNL Salesforce], zorg ervoor uw [&#x200B; lood douanegebieden goed &#x200B;](https://help.salesforce.com/apex/HTViewHelpDoc?id=customize_mapleads.htm) in kaart worden gebracht. U wilt geen gegevens verliezen.

U kunt triggeren en filtreren gebruikend: &quot;[!UICONTROL Lead is Converted]&quot; en &quot;[!UICONTROL Lead was Converted]&quot;.
