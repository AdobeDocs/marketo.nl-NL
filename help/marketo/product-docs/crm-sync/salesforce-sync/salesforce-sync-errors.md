---
description: Salesforce-synchronisatiefouten - Marketo Docs - Productdocumentatie
title: Salesforce-synchronisatiefouten
exl-id: 4819f423-30c6-48e3-8cec-5d298ceb7b56
feature: Salesforce Integration
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '173'
ht-degree: 1%

---

# [!DNL Salesforce] Fouten synchroniseren {#salesforce-sync-errors}

Bekijk een overzicht van de fouten die tijdens het synchronisatieproces optreden. Dit geldt ook voor fouten die worden veroorzaakt door het niet synchroniseren van incompatibele gegevens.

>[!NOTE]
>
>**Vereiste Bevoegdheden Admin**

## Synchronisatiefouten weergeven {#view-sync-errors}

1. Klik op **[!UICONTROL Admin]**.

   ![](assets/salesforce-sync-errors-1.png)

1. Onder Integratie, klik **Salesforce**, toen het **[!UICONTROL Sync Errors]** lusje.

   ![](assets/salesforce-sync-errors-2.png)

>[!NOTE]
>
>De vermelde fouten lopen van de huidige tijd tot vijf dagen vóór de huidige synchronisatie.

| Veld | Beschrijving |
|---|---|
| Mislukt | Het Niveau van het verslag _of_ Niveau van de Taak |
| Datum/tijd van de storing | Foutgegevens |
| Fouttype | SFDC Return-bericht |

>[!TIP]
>
>Wanneer u op de record op recordniveau klikt, worden de Marketo- en [!DNL Salesforce] id&#39;s van het verwante object weergegeven. In sommige gevallen is het bericht op de record- en taakniveaufouten rechtstreeks afkomstig uit [!DNL Salesforce] . Als u online naar deze bestanden zoekt, kunt u meer details opgeven.

## Fouten bij synchroniseren van filters {#filter-sync-errors}

1. Klik op het filterpictogram helemaal rechts van de pagina om de gegevens te filteren.

   ![](assets/salesforce-sync-errors-3.png)

1. Selecteer uw datum- en tijdbereik en filtreer vervolgens op Fouttype (Taakniveau of Recordniveau). Klik op **[!UICONTROL Apply]** als u klaar bent.

   ![](assets/salesforce-sync-errors-4.png)

**OPTIONELE STAP**: Om synchronisatiefouten uit te voeren, klik **[!UICONTROL Export]**. De gegevens worden geëxporteerd als een CSV.

![](assets/salesforce-sync-errors-5.png)
