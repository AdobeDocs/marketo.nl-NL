---
unique-page-id: 7515131
description: SFDC-synchronisatie - Een lead/contactpersoon verwijderen - Marketo-documenten - Productdocumentatie
title: SFDC-synchronisatie - Een lead/contactpersoon verwijderen
exl-id: b859357e-09c5-48e5-940e-f5b4e955e374
feature: Salesforce Integration
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '137'
ht-degree: 0%

---

# SFDC-synchronisatie: een lead/contactpersoon verwijderen {#sfdc-sync-deleting-a-lead-contact}

Hier volgen enkele details:

* Marketo verwijdert niet automatisch personen alleen omdat leads zijn verwijderd in [!DNL Salesforce] . De markering &#39;&#39;SFDC is verwijderd&#39;&#39; in plaats daarvan is ingesteld op true. U kunt dit veld desgewenst uitschakelen om het te verwijderen in Marketo.
* [ de stroomactie van de Persoon van de Schrapping ](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/delete-person.md). Hiermee verwijdert u een persoon in MKTO, maar u kunt deze ook verwijderen in `Salesforce` .

* [ Schrapping van SFDC ](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/delete-person-from-sfdc.md) stroomactie: Dit schrapt een lood in SFDC maar u hebt een keus om een persoon in Marketo eveneens te schrappen.
* Als een lood in [!DNL Salesforce] wordt geschrapt (maar een persoon wordt niet geschrapt in Marketo) en dan door de [ Synchronisatie met  [!DNL Salesforce]](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md) stroomactie loopt, dan zou het tot een nieuwe lood in [!DNL Salesforce] leiden.
