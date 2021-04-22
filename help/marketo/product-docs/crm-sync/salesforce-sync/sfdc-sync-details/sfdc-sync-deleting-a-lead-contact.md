---
unique-page-id: 7515131
description: SFDC Sync - Deleting a Lead/Contact - Marketo Docs - Productdocumentatie
title: SFDC-synchronisatie - Een lead/contactpersoon verwijderen
exl-id: b859357e-09c5-48e5-940e-f5b4e955e374
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '141'
ht-degree: 0%

---

# SFDC-synchronisatie: Een lead/contactpersoon verwijderen {#sfdc-sync-deleting-a-lead-contact}

Hier volgen enkele details:

* Marketo verwijdert niet automatisch mensen alleen omdat leads zijn verwijderd in Salesforce. De markering &#39;SFDC is verwijderd&#39; in plaats van &#39;true&#39; in het veld. U kunt dit veld desgewenst uitschakelen om het te verwijderen in Marketo.
* [Handeling ](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/delete-person.md) Persoonlijke gegevens verwijderen. Hierdoor wordt een persoon in MKTO verwijderd, maar u kunt de gegevens ook in `Salesforce` verwijderen.

* [Verwijderen uit ](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/delete-person-from-sfdc.md) SFDCflow-actie: Hiermee verwijdert u een lead in SFDC, maar u kunt ook een persoon in Marketo verwijderen.
* Als een lood in Salesforce (maar een persoon wordt niet geschrapt in Marketo) wordt geschrapt en dan door de [synchroon met Salesforce](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md) stroomactie loopt, dan zou het tot een nieuwe lood in Salesforce leiden.
