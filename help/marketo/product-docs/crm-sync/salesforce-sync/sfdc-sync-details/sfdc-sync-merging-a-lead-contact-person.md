---
unique-page-id: 7515133
description: SFDC-synchronisatie - Een lead/contactpersoon/persoon samenvoegen - Marketo-documenten - Productdocumentatie
title: SFDC-synchronisatie - Een lead/contactpersoon/persoon samenvoegen
translation-type: tm+mt
source-git-commit: 96cc6a30c63c8e8dca793a52e4bf7ecaef8c08dc
workflow-type: tm+mt
source-wordcount: '244'
ht-degree: 0%

---


# SFDC-synchronisatie: Een lead/contactpersoon/persoon samenvoegen {#sfdc-sync-merging-a-lead-contact-person}

>[!NOTE]
>
>**FYI**
>
>Marketo is nu bezig met het standaardiseren van de taal voor alle abonnementen, dus u ziet mogelijk leads/leads in uw abonnement en personen/personen in docs.marketo.com. Deze termen betekenen hetzelfde. het heeft geen invloed op de instructies van het artikel . Er zijn nog enkele andere veranderingen. [Meer](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)informatie.

Soms is het beter om alleen de regels te vermelden. Hier gaan we:

* Wanneer u twee leads samenvoegt in **Salesforce**, vertelt de normale synchronisatie Marketo en de leads worden automatisch samengevoegd als mensen in Marketo.
* Het samenvoegen van twee mensen in **Marketo** impliceert eigenlijk hetzelfde proces als het samenvoegen van hen als leiders in Salesforce. Het werkt nog steeds automatisch.
* Het samenvoegen van een **lead (persoon) in een contactpersoon** werkt op dezelfde manier. U eindigt met één enkel contact aan beide kanten.
* Bij het samenvoegen wordt de standaardscore opgeteld.

>[!NOTE]
>
>**Voorbeeld**
>
>Wanneer 3 leads (mensen) worden samengevoegd met scores van elk 10, levert dit het resultaat op van 1 lead (persoon) met een score van 30.

* Conflicterende veldwaarden worden opgehaald uit de &quot;winnende record&quot;. (Record = de resulterende lood of contactpersoon)
* Als het &quot;verliesrecord&quot; (dat verdwijnt) een waarde had en het winnende record geen waarde, wordt het verliesoverzicht bewaard. Met andere woorden: &quot;Een waarde is beter dan geen waarde.&quot;
* Alle items in het activiteitenlog worden samengevoegd.

>[!NOTE]
>
>**Diep duiken**
>
>Diep duik voor meer informatie over het [samenvoegen van mensen in Marketo](../../../../product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/find-and-merge-duplicate-people.md).

