---
unique-page-id: 10092977
description: Leer over het de synchronisatiefilter van de Dynamiek kwalificeren proces wanneer het omzetten van een lood in een contact. Begrijp hoe de filterwaarden voor lood en contactsynchronisatie invloed hebben op Marketo-synchronisatie.
title: Microsoft Dynamics-synchronisatiefilter - Kwalificeren
exl-id: 9b26795c-fc94-478e-a7f0-ac8e602792b1
feature: Microsoft Dynamics
source-git-commit: 2b29f05a27f847184e0968442012d443e9e0597d
workflow-type: tm+mt
source-wordcount: '125'
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
