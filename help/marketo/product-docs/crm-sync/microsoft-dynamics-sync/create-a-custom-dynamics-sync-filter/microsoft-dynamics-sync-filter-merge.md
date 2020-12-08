---
unique-page-id: 10092969
description: Microsoft Dynamics Sync Filter -Merge - Marketo Docs - Productdocumentatie
title: Microsoft Dynamics Sync Filter -Merge
translation-type: tm+mt
source-git-commit: 96cc6a30c63c8e8dca793a52e4bf7ecaef8c08dc
workflow-type: tm+mt
source-wordcount: '172'
ht-degree: 0%

---


# Microsoft Dynamics Sync Filter: Samenvoegen {#microsoft-dynamics-sync-filter-merge}

Bij het samenvoegen van leads in Microsoft Dynamics wordt het type Two Options gebruikt: Sync filter = Yes (TRUE) en Sync filter = No (FALSE). Wanneer u twee verslagen samenvoegt, varieert het resultaat, afhankelijk van welke verslag waar is en die vals is.

De hoofdrecords worden waar of onwaar op basis van de workflowregels die door de beheerder zijn gedefinieerd om de winnaar te bepalen. Het synchronisatiefilter voor het winnen van verslag is wat uiteindelijk bepaalt als het verslag van de Dynamiek van MS met Marketo synchroniseert.

Wanneer één record waar is en één onwaar is, wordt het lastig.

| Als het synchronisatiefilter voor het verlies van verslag is: | en het synchronisatiefilter voor de winnende record is: | Dit is het resultaat in Marketo |
|---|---|---|
| Waar | Waar | De winnende record wordt gesynchroniseerd met Marketo |
| Onwaar | Onwaar | De winnende record blijft **niet** synchroniseren met Marketo |
| Onwaar | Waar | De winnende record wordt gesynchroniseerd met Marketo |
| Waar | Onwaar | De winnende record wordt niet gesynchroniseerd met Marketo |

