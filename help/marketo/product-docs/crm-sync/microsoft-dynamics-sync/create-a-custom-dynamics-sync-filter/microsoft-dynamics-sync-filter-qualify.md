---
unique-page-id: 10092977
description: Microsoft Dynamics Sync Filter -Qualify - Marketo Docs - Productdocumentatie
title: Microsoft Dynamics Sync Filter -Qualify
exl-id: 9b26795c-fc94-478e-a7f0-ac8e602792b1
feature: Microsoft Dynamics
source-git-commit: 2403ae0f1fdca3b8238f3f59e2a3b94129deb301
workflow-type: tm+mt
source-wordcount: '123'
ht-degree: 0%

---

# Filter voor synchronisatie met Microsoft-dynamiek: kwalificeren {#microsoft-dynamics-sync-filter-qualify}

Wanneer u een lood in een contact in de Dynamica van Microsoft wilt omzetten, zeker ben om dit gebrek te gebruiken kwalificeer proces. Synchroniseer het vervolgens met het Marketo Engage.

## Het omzettingsproces {#the-conversion-process}

Hieronder wordt beschreven hoe de filters werken tijdens het conversieproces.

| Als het loodsynchronisatiefilter is: | en het filter Contactsync is: | Dit is het resultaat in Marketo |
|---|---|---|
| Onwaar | Onwaar | Er wordt niets gesynchroniseerd in Marketo |
| Waar | Waar | De contactpersoon wordt gesynchroniseerd in Marketo |
| Onwaar | Waar | Nieuwe contactrecord wordt gemaakt in Marketo |
| Waar | Onwaar | Hoofdgegevens van updates voor MS Dynamics in Marketo, maar contactrecord is niet gesynchroniseerd |

>[!CAUTION]
>
>Wij steunen slechts het uit-van-de-doos kwalificeren omzettingsproces.
