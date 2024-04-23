---
unique-page-id: 1146940
description: Slimme lijst definiëren voor slimme campagne | Batch - Marketo-documenten - productdocumentatie
title: Slimme lijst definiëren voor slimme campagne | Batch
exl-id: 0e0061a9-df24-4cf6-8f1e-09ff0ee62efa
feature: Smart Campaigns
source-git-commit: a9d902bf40e6193838a931ecb96a080bae098d68
workflow-type: tm+mt
source-wordcount: '273'
ht-degree: 0%

---

# Slimme lijst definiëren voor slimme campagne | Batch {#define-smart-list-for-smart-campaign-batch}

De slimme Lijsten zijn het mechanisme door Marketo Engage om &quot;te bepalen wie&quot;(welke mensen) om te omvatten, of het een rapport, een lijst, of een Slimme Campagne is. Hier is hoe te om een Slimme Lijst voor een partijcampagne te bepalen.

>[!CAUTION]
>
>Het maken van Slimme Lijst of de Stap van de Stroom geeft aan een actieve campagne kan zijn functionaliteit potentieel breken. Als u dit wilt doen, moet u voorzichtig te werk gaan.

1. Kies een slimme campagne en klik op **[!UICONTROL Smart List]**.

   ![](assets/define-smart-list-for-smart-campaign-batch-1.png)

1. Typ om een filter te zoeken en sleep het naar het canvas. Herhaal deze bewerking voor meerdere filters.

   ![](assets/define-smart-list-for-smart-campaign-batch-2.png)

   >[!NOTE]
   >
   >Een slimme campagne met alleen filters wordt uitgevoerd in _Batch_ -modus. Het vindt mensen in het gegevensbestand die op de filters worden gekwalificeerd en stelt alle hen door de stroom in werking tegelijkertijd.

   >[!NOTE]
   >
   >U kunt een slimme campagne per persoon laten uitvoeren op basis van live gebeurtenissen door triggers toe te voegen, waardoor de slimme campagne _Trigger_ -modus.

1. Klik op de vervolgkeuzelijst en kies een filteroperator voor het filter dat u hebt gekozen.

   ![](assets/define-smart-list-for-smart-campaign-batch-3.png)

   >[!CAUTION]
   >
   >Rode kronkelige lijnen geven fouten of ontbrekende informatie aan. Als de campagne niet wordt gecorrigeerd, is deze ongeldig en wordt deze niet uitgevoerd.

1. Voer de filterwaarde in.

   ![](assets/define-smart-list-for-smart-campaign-batch-4.png)

   >[!NOTE]
   >
   >Door gebrek, worden de mensen die ALLE Slimme regels van de Lijst voldoen gekwalificeerd. Dit kan worden aangepast aan uw campagnebehoeften. Uitchecken  [Slimme lijstregels voor complexe logica](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/using-advanced-smart-list-rule-logic.md){target="_blank"} voor meer informatie.

   Leer hoe u live gebeurtenissen één persoon tegelijk kunt activeren [Slimme lijst definiëren voor slimme campagne | Trigger](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-trigger.md){target="_blank"}.

   >[!MORELIKETHIS]
   >
   >* [Slimme lijst definiëren voor slimme campagne | Trigger](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-trigger.md){target="_blank"}
   >* [Een stroomstap toevoegen aan een slimme campagne](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md){target="_blank"}
