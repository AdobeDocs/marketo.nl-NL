---
unique-page-id: 7515131
description: Begrijp hoe lood en contactschrapping tussen Salesforce en Marketo werken. Meer informatie over SFDC Delete Person en Handelingen Verwijderen uit SFDC-stroom.
title: SFDC-synchronisatie - Een lead/contactpersoon verwijderen
exl-id: b859357e-09c5-48e5-940e-f5b4e955e374
feature: Salesforce Integration
source-git-commit: 2b29f05a27f847184e0968442012d443e9e0597d
workflow-type: tm+mt
source-wordcount: '149'
ht-degree: 0%

---

# SFDC-synchronisatie: een lead/contactpersoon verwijderen {#sfdc-sync-deleting-a-lead-contact}

Hier volgen enkele details:

* Marketo verwijdert niet automatisch personen alleen omdat leads zijn verwijderd in [!DNL Salesforce] . De markering &#39;&#39;SFDC is verwijderd&#39;&#39; in plaats daarvan is ingesteld op true. U kunt dit veld desgewenst uitschakelen om het te verwijderen in Marketo.
* [&#x200B; de stroomactie van de Persoon van de Schrapping &#x200B;](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/delete-person.md). Hiermee verwijdert u een persoon in MKTO, maar u kunt deze ook verwijderen in `Salesforce` .

* [&#x200B; Schrapping van SFDC &#x200B;](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/delete-person-from-sfdc.md) stroomactie: Dit schrapt een lood in SFDC maar u hebt een keus om een persoon in Marketo eveneens te schrappen.
* Als een lood in [!DNL Salesforce] wordt geschrapt (maar een persoon wordt niet geschrapt in Marketo) en dan door de [&#x200B; Synchronisatie met  [!DNL Salesforce]](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md) stroomactie loopt, dan zou het tot een nieuwe lood in [!DNL Salesforce] leiden.
