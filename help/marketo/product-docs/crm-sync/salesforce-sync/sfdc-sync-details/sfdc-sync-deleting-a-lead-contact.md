---
unique-page-id: 7515131
description: SFDC-synchronisatie - Een lead/contactpersoon verwijderen - Marketo-documenten - Productdocumentatie
title: SFDC-synchronisatie - Een lead/contactpersoon verwijderen
exl-id: b859357e-09c5-48e5-940e-f5b4e955e374
feature: Salesforce Integration
source-git-commit: 0087a5e88b8bd9601875f68a2e7cadeebdb5d682
workflow-type: tm+mt
source-wordcount: '142'
ht-degree: 0%

---

# SFDC-synchronisatie: een lead/contactpersoon verwijderen {#sfdc-sync-deleting-a-lead-contact}

Hier volgen enkele details:

* Marketo Engage verwijdert niet automatisch mensen alleen omdat leads zijn verwijderd in Salesforce. De markering &#39;SFDC is verwijderd&#39; in plaats van &#39;true&#39; in het veld. U kunt dit veld desgewenst uitschakelen om het te verwijderen in Marketo.
* [Persoon verwijderen](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/delete-person.md){target="_blank"} Handeling flow. Hiermee verwijdert u een persoon in MKTO, maar u kunt deze ook verwijderen in `Salesforce` ook.

* [Verwijderen uit SFDC](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/delete-person-from-sfdc.md){target="_blank"} Stroomhandeling: hiermee verwijdert u een lead in SFDC, maar u kunt ook een persoon in Marketo verwijderen.
* Als een lood in Salesforce wordt verwijderd (maar een persoon niet in Marketo wordt verwijderd) en vervolgens door de [Synchroniseren met Salesforce](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md){target="_blank"} Dan zou er een nieuwe lead ontstaan in Salesforce.
