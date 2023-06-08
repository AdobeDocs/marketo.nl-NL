---
unique-page-id: 2360217
description: Kenmerken wijzigen voor Analytics - Marketo Docs - Productdocumentatie
title: Kenmerkinstellingen wijzigen voor Analytics
exl-id: 4740b0fa-ddaf-46ed-87d6-8b3f8d35afe3
source-git-commit: b71729a678ff4a676bb60803d845d0a44118f7e5
workflow-type: tm+mt
source-wordcount: '171'
ht-degree: 0%

---

# Kenmerkinstellingen wijzigen voor Analytics {#change-attribution-settings-for-analytics}

U kunt de manier veranderen waarop Marketo contacten verbindt met kansen voor eerste en multi-aanraking attributie, lood omzettingsmetriek, en de marketing-beïnvloede opportuniteitsvlag.

Deze instellingen zijn van invloed op [!UICONTROL Revenue Explorer] verslagen in het kader van de [Analyse van programmamogelijkheden](/help/marketo/product-docs/reporting/revenue-cycle-analytics/program-analytics/understanding-the-program-opportunity-analysis-area.md), [Opportuniteitsanalyse](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-explorer/understanding-opportunity-analysis-in-revenue-explorer.md), en gebieden van de Analyse van het Lood. Dit heeft ook gevolgen voor de [!UICONTROL Program Analyzer] verslag.

1. Ga naar de **[!UICONTROL Admin]** gebied.

   ![](assets/change-attribution-settings-for-analytics-1.png)

1. Klik op **[!UICONTROL Revenue Cycle Analytics]**.

   ![](assets/change-attribution-settings-for-analytics-2.png)

1. Klik op de knop **[!UICONTROL Edit]** link onder **[!UICONTROL Attribution]**.

   ![](assets/change-attribution-settings-for-analytics-3.png)

   >[!TIP]
   >
   >Als u deze instelling wijzigt, worden Marketo-gegevens niet gewijzigd. het verandert eenvoudig de manier waarop uw rapporten lopen. Dit kan op elk ogenblik worden omgekeerd.

1. Selecteer een optie en klik op **[!UICONTROL Save]**.

   ![](assets/change-attribution-settings-for-analytics-4.png)

   >[!NOTE]
   >
   >**Definitie**
   >
   >**[!UICONTROL Explicit]**: Alleen contacten met rollen (standaard).
   >
   >**[!UICONTROL Hybrid]**: Contactpersonen met rollen, indien beschikbaar. Als niets beschikbaar is, gebruikt het alle contacten in rekeningen.
   >
   >**[!UICONTROL Implicit]**: Alle contacten ongeacht rol.

>[!CAUTION]
>
>Wanneer u **[!UICONTROL Implicit]**, zal Marketo altijd alle contacten onderzoeken verbonden aan de rekening ongeacht rol. **Marketo raadt u ten zeerste aan [!UICONTROL Explicit] mode**. Gebruiken [!UICONTROL Implicit] kan leiden tot valse positieven; dat wil zeggen, mensen die een kans verdienen ondanks het feit dat ze geen echte invloed op de kansen hebben. Gebruiken [!UICONTROL Implicit] met voorzichtigheid.
