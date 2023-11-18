---
description: Salesforce-synchronisatiefouten - Marketo-documenten - Productdocumentatie
title: Salesforce-synchronisatiefouten
exl-id: 4819f423-30c6-48e3-8cec-5d298ceb7b56
feature: Salesforce Integration
source-git-commit: 4045f262889d06304111288d30da893529396e81
workflow-type: tm+mt
source-wordcount: '176'
ht-degree: 0%

---

# Salesforce-synchronisatiefouten {#salesforce-sync-errors}

Bekijk een overzicht van de fouten die tijdens het synchronisatieproces optreden. Dit geldt ook voor fouten die worden veroorzaakt door het niet synchroniseren van incompatibele gegevens.

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

## Synchronisatiefouten weergeven {#view-sync-errors}

1. Klik op **[!UICONTROL Admin]**.

   ![](assets/salesforce-sync-errors-1.png)

1. Klik onder Integratie op **Salesforce** en vervolgens de **[!UICONTROL Sync Errors]** tab.

   ![](assets/salesforce-sync-errors-2.png)

>[!NOTE]
>
>De vermelde fouten lopen van de huidige tijd tot vijf dagen vóór de huidige synchronisatie.

| Veld | Beschrijving |
|---|---|
| Mislukt | Recordniveau _of_ Taakniveau |
| Datum/tijd van de storing | Foutgegevens |
| Fouttype | SFDC Return-bericht |

>[!TIP]
>
>Wanneer u op de record op recordniveau klikt, worden de Marketo- en Salesforce-id&#39;s van het verwante object weergegeven. In sommige gevallen is de melding in de record en de fout op het taakniveau rechtstreeks afkomstig van Salesforce. Als u online naar deze bestanden zoekt, kunt u meer details opgeven.

## Fouten bij synchroniseren van filters {#filter-sync-errors}

1. Klik op het filterpictogram helemaal rechts van de pagina om de gegevens te filteren.

   ![](assets/salesforce-sync-errors-3.png)

1. Selecteer uw datum- en tijdbereik en filtreer vervolgens op Fouttype (Taakniveau of Recordniveau). Klikken **[!UICONTROL Apply]** wanneer gereed.

   ![](assets/salesforce-sync-errors-4.png)

**OPTIONELE STAP**: Als u synchronisatiefouten wilt exporteren, klikt u **[!UICONTROL Export]**. De gegevens worden geëxporteerd als een CSV.

![](assets/salesforce-sync-errors-5.png)
