---
unique-page-id: 7515133
description: SFDC Sync - Merging a Lead/Contact/Person - Marketo Docs - Productdocumentatie
title: SFDC Sync - Samenvoegen van een lead/contactpersoon/persoon
exl-id: 0e755c80-27cd-4ba3-b540-d7918264c5f6
feature: Salesforce Integration
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '192'
ht-degree: 0%

---

# SFDC Sync: Een lead/contact/persoon samenvoegen {#sfdc-sync-merging-a-lead-contact-person}

Soms is het beter om alleen de regels te vermelden. Hier gaan we:

* Wanneer u twee leads samenvoegt in **[!DNL Salesforce]** , geeft de normale synchronisatie aan dat Marketo en de leads automatisch worden samengevoegd als mensen in Marketo.
* Het samenvoegen van twee mensen in **Marketo** roept eigenlijk het zelfde proces aan zoals het samenvoegen van hen zoals lood in [!DNL Salesforce]. Het werkt nog steeds automatisch.
* Het samenvoegen van a **lood (persoon) in een contact** werkt de zelfde manier. U eindigt met één enkel contact aan beide kanten.
* Bij het samenvoegen wordt de standaardscore opgeteld.

>[!NOTE]
>
>Wanneer 3 leads (mensen) worden samengevoegd met scores van elk 10, levert dit het resultaat op van 1 lead (persoon) met een score van 30.

* Conflicterende veldwaarden worden opgehaald uit de &quot;winnende record&quot;. (Record = de resulterende lood of contactpersoon)
* Als het &quot;verliesrecord&quot; (dat verdwijnt) een waarde had en het winnende record geen waarde, wordt het verliesoverzicht bewaard. Met andere woorden: &quot;Een waarde is beter dan geen waarde.&quot;
* Alle items in het activiteitenlog worden samengevoegd.

>[!NOTE]
>
>Diep duik voor meer informatie over [ het samenvoegen van mensen in Marketo ](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/find-and-merge-duplicate-people.md){target="_blank"}.
