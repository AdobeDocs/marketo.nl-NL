---
unique-page-id: 7515133
description: SFDC-synchronisatie - Een lead/contactpersoon/persoon samenvoegen - Marketo-documenten - Productdocumentatie
title: SFDC-synchronisatie - Een lead/contactpersoon/persoon samenvoegen
translation-type: tm+mt
source-git-commit: ed83438ae5660d172e845f25c4d72d599574bd91
workflow-type: tm+mt
source-wordcount: '190'
ht-degree: 0%

---


# SFDC-synchronisatie: Een lead/contactpersoon/persoon samenvoegen {#sfdc-sync-merging-a-lead-contact-person}

Soms is het beter om alleen de regels te vermelden. Hier gaan we:

* Wanneer u twee lood in **Salesforce** samenvoegt, vertelt de normale synchronisatie Marketo en de lood automatisch als mensen in Marketo worden samengevoegd.
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
