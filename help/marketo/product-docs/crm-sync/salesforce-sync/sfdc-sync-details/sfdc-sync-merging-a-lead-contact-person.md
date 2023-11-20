---
unique-page-id: 7515133
description: SFDC-synchronisatie - Een lead/contactpersoon/persoon samenvoegen - Marketo-documenten - Productdocumentatie
title: SFDC-synchronisatie - Een lead/contactpersoon/persoon samenvoegen
exl-id: 0e755c80-27cd-4ba3-b540-d7918264c5f6
feature: Salesforce Integration
source-git-commit: 0087a5e88b8bd9601875f68a2e7cadeebdb5d682
workflow-type: tm+mt
source-wordcount: '191'
ht-degree: 0%

---

# SFDC-synchronisatie: een lead/contactpersoon/persoon samenvoegen {#sfdc-sync-merging-a-lead-contact-person}

Soms is het beter om alleen de regels te vermelden. Hier gaan we:

* Wanneer u twee leads samenvoegt in **Salesforce** De normale synchronisatie vertelt Marketo Engage en de leads worden automatisch samengevoegd als mensen in Marketo.
* Twee personen samenvoegen in **Marketo** In feite wordt hetzelfde proces gebruikt als het samenvoegen van de leiders in Salesforce. Het werkt nog steeds automatisch.
* Een samenvoegen **leiden (persoon) in een contact** werkt op dezelfde manier. U eindigt met één enkel contact aan beide kanten.
* Bij het samenvoegen wordt de standaardscore opgeteld.

>[!NOTE]
>
>Wanneer 3 leads (mensen) worden samengevoegd met scores van elk 10, levert dit het resultaat op van 1 lead (persoon) met een score van 30.

* Conflicterende veldwaarden worden opgehaald uit de &quot;winnende record&quot;. (Record = de resulterende lood of contactpersoon)
* Als het &quot;verliesrecord&quot; (dat verdwijnt) een waarde had en het winnende record geen waarde, wordt het verliesoverzicht bewaard. Met andere woorden: &quot;Een waarde is beter dan geen waarde.&quot;
* Alle items in het activiteitenlog worden samengevoegd.

>[!NOTE]
>
>Diep duiken voor meer informatie over [samenvoegen van mensen in Marketo](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/find-and-merge-duplicate-people.md){target="_blank"}.
