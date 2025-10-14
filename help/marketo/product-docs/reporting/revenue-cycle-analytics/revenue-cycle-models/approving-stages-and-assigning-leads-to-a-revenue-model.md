---
unique-page-id: 4718683
description: Het goedkeuren van Stages en het toewijzen van Leidingen aan een Model van de Inkomsten - de Documenten van Marketo - de Documentatie van het Product
title: Het goedkeuren van Stages en het toewijzen van Leidingen aan een model van de Inkomsten
exl-id: 0c93dfe4-8950-444c-a65b-080620816ba2
feature: Reporting, Revenue Cycle Analytics
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '303'
ht-degree: 1%

---

# Het goedkeuren van Stages en het toewijzen van Leidingen aan een model van de Inkomsten {#approving-stages-and-assigning-leads-to-a-revenue-model}

Krijg uw **Model van de Opbrengst** omhoog en lopend door bestaande lood toe te voegen, die toewijzingsregels voor om het even welke nieuwe lood creëren.

## Fases goedkeuren {#approving-stages}

Wij keuren de stadia van uw model goed alvorens u om het even welke lood toevoegt.

1. Ga naar het **[!UICONTROL Analytics]** -gebied.

   ![](assets/image2015-4-28-17-3a8-3a8.png)

1. Selecteer het model waarvan de stadia u wilt goedkeuren.

   ![](assets/image2015-4-28-17-3a10-3a3.png)

1. Selecteer onder **[!UICONTROL Model Actions]** de optie **[!UICONTROL Approve Stages]** .

   ![](assets/image2015-4-28-17-3a12-3a37.png)

1. U wordt begroet met een waarschuwing. Klik op **[!UICONTROL Assign Leads]** .

   ![](assets/image2015-4-28-17-3a5-3a39.png)

Uitstekend! Laten we verder gaan en die leads toewijzen.

## Bestaande leads toewijzen {#assigning-existing-leads}

[&#x200B; creeer een Slimme Lijst &#x200B;](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md) om de lood voor één stadium van uw model in uw Gegevensbestand van de Lood te identificeren.

1. Zodra u [&#x200B; uw Slimme Lijst &#x200B;](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md) hebt gecreeerd, klik het **[!UICONTROL Leads]** lusje.

   ![](assets/image2015-4-29-11-3a37-3a30.png)

1. Klik op **[!UICONTROL Select All]** om de leads te selecteren.

   ![](assets/image2015-4-29-11-3a39-3a39.png)

1. Open de vervolgkeuzelijst **[!UICONTROL Lead Actions]** en selecteer **[!UICONTROL Special]** . Klik op **[!UICONTROL Change Revenue Stage...]**.

   ![](assets/image2015-4-29-11-3a40-3a38.png)

1. Selecteer de juiste **[!UICONTROL Model]** en de juiste **[!UICONTROL Stage]** . Klik op **[!UICONTROL Run Now]**.

   ![](assets/image2015-4-29-11-3a43-3a41.png)

1. Herhaal deze bewerking totdat alle leads zijn toegewezen aan de verschillende stadia van uw model.

Geweldig! Om te specificeren hoe de nieuwe lood aan stadia worden toegewezen, creeer toewijzingsregels.

>[!NOTE]
>
>Als uw model in de Goedgekeurde staat van Stages is, zult u geen gebeurtenissen van het Stadium van de Opbrengst van de Verandering in de de activiteitenlogboeken van de lood zien. Als uw model volledig is goedgekeurd, wordt deze stap overgeslagen als u een lood in het zelfde stadium beweegt het momenteel in is.

## Nieuwe leads: toewijzingsregels maken  {#new-leads-create-assignment-rules}

1. Klik **Begin van Marketo** opnieuw, dan selecteren **[!UICONTROL Analytics]**.

   ![](assets/image2015-4-28-17-3a8-3a8.png)

1. Klik op het model in de structuur, selecteer vervolgens het menu **[!UICONTROL Model Actions]** en selecteer **[!UICONTROL Assignment Rules]** .

   ![](assets/image2015-4-29-11-3a52-3a17.png)

1. Als uw toewijzingsregels meer dan één standaardkeuzeklik **[!UICONTROL Stage]** bevatten, maakt u uw selectie en klikt u op **[!UICONTROL Add Choice]** .

   ![](assets/image2015-4-29-12-3a5-3a46.png)

## Voorbeeld van toewijzingsregel {#example-assignment-rule}

Maak een [!UICONTROL Lead Score] -regel om de nieuwe leads met een minimumscore toe te wijzen aan een geschikte stap.

1. Selecteer onder **[!UICONTROL If]** de optie **[!UICONTROL Lead Score]**. Kies vervolgens **[!UICONTROL at least]** .

   ![](assets/image2015-4-29-13-3a27-3a8.png)

1. Ga **40** op het gebied in en selecteer **[!UICONTROL Sales Lead]** als [!UICONTROL Stage]. Klik op **[!UICONTROL Save]** om te voltooien.

   ![](assets/image2015-4-29-14-3a4-3a23.png)

>[!MORELIKETHIS]
>
>Om uw model goed te keuren, lees onze hulppagina op **[goedkeurend en het Ongoedkeuren van een Model van de Ontvangsten](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-cycle-models/approve-unapprove-a-revenue-model.md)**.
