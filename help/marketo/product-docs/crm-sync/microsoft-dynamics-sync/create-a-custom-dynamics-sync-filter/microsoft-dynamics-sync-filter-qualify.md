---
unique-page-id: 10092977
description: Microsoft Dynamics Sync Filter -Qualify - Marketo Docs - Productdocumentatie
title: Microsoft Dynamics Sync Filter -Qualify
translation-type: tm+mt
source-git-commit: 2b5ccd7220557a5e966d33436d0f0d2a65e4589d
workflow-type: tm+mt
source-wordcount: '122'
ht-degree: 0%

---


# Microsoft Dynamics Sync Filter: {#microsoft-dynamics-sync-filter-qualify} kwalificeren

Wanneer u een lood in een contact in de Dynamiek van Microsoft wilt omzetten, ben zeker om dit gebrek te gebruiken kwalificeer proces. Synchroniseer het vervolgens met Marketo.

## Het omzettingsproces {#the-conversion-process}

Hieronder wordt beschreven hoe de filters werken tijdens het conversieproces.

| Als het loodsynchronisatiefilter is: | en het contactsynchronisatiefilter is: | Dit is het resultaat in Marketo |
|---|---|---|
| Onwaar | Onwaar | Er wordt niets gesynchroniseerd in Marketo |
| Waar | Waar | De contactpersoon wordt gesynchroniseerd in Marketo |
| Onwaar | Waar | Nieuwe contactrecord gemaakt in Marketo |
| Waar | Onwaar | De updates van de Dynamica van MS leiden info in Marketo maar het contactverslag is niet gesynchroniseerd |

>[!CAUTION]
>
>Wij steunen slechts het uit-van-de-doos kwalificeren omzettingsproces.
