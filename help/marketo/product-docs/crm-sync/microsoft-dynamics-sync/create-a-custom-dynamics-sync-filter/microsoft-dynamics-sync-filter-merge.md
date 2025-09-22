---
unique-page-id: 10092969
description: Microsoft Dynamics Sync Filter -Merge - Marketo Docs - Productdocumentatie
title: Microsoft Dynamics Sync Filter -Merge
exl-id: f8da9c3c-0f04-4f61-be03-7e7953d25afe
feature: Microsoft Dynamics
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '159'
ht-degree: 0%

---

# [!DNL Microsoft] Dynamisch synchronisatiefilter: Samenvoegen {#microsoft-dynamics-sync-filter-merge}

Bij samenvoegen van leads in [!DNL Microsoft Dynamics] wordt het type Two Options gebruikt: Sync filter = Yes (TRUE) en Sync filter = No (FALSE). Wanneer u twee verslagen samenvoegt, varieert het resultaat, afhankelijk van welke verslag waar is en die vals is.

De hoofdrecords worden waar of onwaar op basis van de workflowregels die door de beheerder zijn gedefinieerd om de winnaar te bepalen. Het synchronisatiefilter voor de winnende record is wat uiteindelijk bepaalt of de [!DNL MS Dynamics] -record wordt gesynchroniseerd met Marketo.

Wanneer één record waar is en één onwaar is, wordt het lastig.

| Als het synchronisatiefilter voor het verlies van verslag is: | en het synchronisatiefilter voor de winnende record is: | Dit is het resultaat in Marketo |
|---|---|---|
| [!UICONTROL True] | [!UICONTROL True] | De winnende record wordt gesynchroniseerd met Marketo |
| [!UICONTROL False] | [!UICONTROL False] | Het winnen verslag blijft **niet** synchronisatie met Marketo |
| [!UICONTROL False] | [!UICONTROL True] | De winnende record synchroniseert met Marketo |
| [!UICONTROL True] | [!UICONTROL False] | De winnende record wordt niet gesynchroniseerd met Marketo |
