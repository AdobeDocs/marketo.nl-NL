---
description: Salesforce-synchronisatiefouten - Marketo-documenten - Productdocumentatie
title: Salesforce-synchronisatiefouten
exl-id: 4819f423-30c6-48e3-8cec-5d298ceb7b56
source-git-commit: 4d88547ecdc25a2a1e0de49fab1493bbefd6800b
workflow-type: tm+mt
source-wordcount: '181'
ht-degree: 0%

---

# Salesforce-synchronisatiefouten {#salesforce-sync-errors}

Bekijk een overzicht van de fouten die tijdens het synchronisatieproces optreden. Dit geldt ook voor fouten die worden veroorzaakt door het niet synchroniseren van incompatibele gegevens.

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

## Synchronisatiefouten weergeven {#view-sync-errors}

1. Klikken **Beheer**.

   ![](assets/salesforce-sync-errors-1.png)

1. Klik onder Integratie op **Salesforce** en de **Fouten synchroniseren** tab.

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

## Fouten bij synchroniseren van filter {#filter-sync-errors}

1. Als u de gegevens wilt filteren, klikt u op het filterpictogram helemaal rechts van de pagina.

   ![](assets/salesforce-sync-errors-3.png)

1. Selecteer uw datum- en tijdbereik en filtreer vervolgens op Fouttype (Taakniveau of Recordniveau). Klikken **Toepassen** wanneer gereed.

   ![](assets/salesforce-sync-errors-4.png)

**OPTIONELE STAP**: Als u synchronisatiefouten wilt exporteren, klikt u op **Exporteren**. De gegevens worden geëxporteerd als een CSV-bestand.

![](assets/salesforce-sync-errors-5.png)
