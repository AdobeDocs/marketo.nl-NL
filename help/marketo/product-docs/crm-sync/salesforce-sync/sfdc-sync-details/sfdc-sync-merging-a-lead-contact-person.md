---
unique-page-id: 7515133
description: SFDC-synchronisatie - Een lead/contactpersoon/persoon samenvoegen - Marketo-documenten - Productdocumentatie
title: SFDC-synchronisatie - Een lead/contactpersoon/persoon samenvoegen
exl-id: 0e755c80-27cd-4ba3-b540-d7918264c5f6
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '190'
ht-degree: 0%

---

# SFDC-synchronisatie: Een lead/contactpersoon/persoon samenvoegen {#sfdc-sync-merging-a-lead-contact-person}

Soms is het beter om alleen de regels te vermelden. Hier gaan we:

* Wanneer u twee leads samenvoegt in **Salesforce**, vertelt de normale synchronisatie Marketo en de leads worden automatisch samengevoegd als mensen in Marketo.
* Het samenvoegen van twee mensen in **Marketo** roept eigenlijk het zelfde proces aan zoals het samenvoegen van hen zoals lood in Salesforce. Het werkt nog steeds automatisch.
* Het samenvoegen van een **lead (person) in een contact** werkt op dezelfde manier. U eindigt met één enkel contact aan beide kanten.
* Bij het samenvoegen wordt de standaardscore opgeteld.

>[!NOTE]
>
>Wanneer 3 leads (mensen) worden samengevoegd met scores van elk 10, levert dit het resultaat op van 1 lead (persoon) met een score van 30.

* Conflicterende veldwaarden worden opgehaald uit de &quot;winnende record&quot;. (Record = de resulterende lood of contactpersoon)
* Als het &quot;verliesrecord&quot; (dat verdwijnt) een waarde had en het winnende record geen waarde, wordt het verliesoverzicht bewaard. Met andere woorden: &quot;Een waarde is beter dan geen waarde.&quot;
* Alle items in het activiteitenlog worden samengevoegd.

>[!NOTE]
>
>Diep duik voor meer informatie over [het samenvoegen van mensen in Marketo](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/find-and-merge-duplicate-people.md).
