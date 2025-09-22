---
unique-page-id: 10092977
description: Microsoft Dynamics Sync Filter -Qualify - Marketo Docs - Productdocumentatie
title: Microsoft Dynamics-synchronisatiefilter - Kwalificeren
exl-id: 9b26795c-fc94-478e-a7f0-ac8e602792b1
feature: Microsoft Dynamics
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '108'
ht-degree: 0%

---

# [!DNL Microsoft Dynamics] Filter synchroniseren: Kwalificeren {#microsoft-dynamics-sync-filter-qualify}

Wanneer u een lood in een contact in [!DNL Microsoft Dynamics] wilt omzetten, ben zeker om dit gebrek te gebruiken kwalificeer proces. Synchroniseer het vervolgens met Marketo.

## Het omzettingsproces {#the-conversion-process}

Hieronder wordt beschreven hoe de filters werken tijdens het conversieproces.

| Als het loodsynchronisatiefilter is: | en het filter Contactsync is: | Dit is het resultaat in Marketo |
|---|---|---|
| [!UICONTROL False] | [!UICONTROL False] | Er wordt niets gesynchroniseerd in Marketo |
| [!UICONTROL True] | [!UICONTROL True] | De contactpersoon wordt gesynchroniseerd in Marketo |
| [!UICONTROL False] | [!UICONTROL True] | Nieuwe contactrecord wordt gemaakt in Marketo |
| [!UICONTROL True] | [!UICONTROL False] | [!DNL MS Dynamics] werkt leidende informatie bij in Marketo, maar contactrecord is niet gesynchroniseerd |

>[!CAUTION]
>
>Wij steunen slechts het uit-van-de-doos kwalificeren omzettingsproces.
