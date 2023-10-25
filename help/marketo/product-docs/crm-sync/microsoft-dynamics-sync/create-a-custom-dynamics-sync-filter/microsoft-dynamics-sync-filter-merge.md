---
unique-page-id: 10092969
description: Microsoft Dynamics Sync Filter -Merge - Marketo Docs - Productdocumentatie
title: Filter voor synchronisatie met Microsoft-dynamiek - Samenvoegen
exl-id: f8da9c3c-0f04-4f61-be03-7e7953d25afe
feature: Microsoft Dynamics
source-git-commit: 2403ae0f1fdca3b8238f3f59e2a3b94129deb301
workflow-type: tm+mt
source-wordcount: '172'
ht-degree: 0%

---

# Filter voor synchronisatie bij Microsoft: samenvoegen {#microsoft-dynamics-sync-filter-merge}

Bij het samenvoegen van leads in Microsoft Dynamics wordt het type Two Options gebruikt: Sync filter = Yes (TRUE) en Sync filter = No (FALSE). Wanneer u twee verslagen samenvoegt, varieert het resultaat, afhankelijk van welke verslag waar is en die vals is.

De hoofdrecords worden waar of onwaar op basis van de workflowregels die door de beheerder zijn gedefinieerd om de winnaar te bepalen. Het synchronisatiefilter voor het winnen van verslag is wat uiteindelijk bepaalt als het verslag van de Dynamica van MS met Marketo synchroniseert.

Wanneer één record waar is en één onwaar is, wordt het lastig.

| Als het synchronisatiefilter voor het verlies van verslag is: | en het synchronisatiefilter voor de winnende record is: | Dit is het resultaat in Marketo |
|---|---|---|
| Waar | Waar | De winnende record wordt gesynchroniseerd met Marketo |
| Onwaar | Onwaar | De winnende record blijft _niet_ synchroniseren met Marketo |
| Onwaar | Waar | De winnende record synchroniseert met Marketo |
| Waar | Onwaar | De winnende record wordt niet gesynchroniseerd met Marketo |
