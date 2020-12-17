---
unique-page-id: 7515131
description: SFDC Sync - Deleting a Lead/Contact - Marketo Docs - Productdocumentatie
title: SFDC-synchronisatie - Een lead/contactpersoon verwijderen
translation-type: tm+mt
source-git-commit: d7d6aee63144c472e02fe0221c4a164183d04dd4
workflow-type: tm+mt
source-wordcount: '148'
ht-degree: 0%

---


# SFDC-synchronisatie: Een lead/contactpersoon verwijderen {#sfdc-sync-deleting-a-lead-contact}

Hier volgen enkele details:

* Marketo verwijdert niet automatisch mensen alleen omdat leads zijn verwijderd in Salesforce. De markering &#39;SFDC is verwijderd&#39; in plaats van &#39;true&#39; in het veld. U kunt dit veld desgewenst uitschakelen om het te verwijderen in Marketo.
* [Handeling ](../../../../product-docs/core-marketo-concepts/smart-campaigns/flow-actions/delete-person.md) Persoonlijke gegevens verwijderen. Hierdoor wordt een persoon in MKTO verwijderd, maar u kunt de gegevens ook in `Salesforce` verwijderen.

* [Verwijderen uit ](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/delete-person-from-sfdc.md) SFDCflow-actie: Hierdoor wordt een lead in SFDC verwijderd, maar u kunt ook een persoon in Marketo verwijderen.
* Als een lood in Salesforce (maar een persoon wordt niet geschrapt in Marketo) wordt geschrapt en dan door de [synchroon met Salesforce](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md) stroomactie loopt, dan zou het tot een nieuwe lood in Salesforce leiden.

Met andere woorden, het werkt als magie!

![—](assets/image2015-5-20-15-3a3-3a27.png)

