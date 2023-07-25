---
unique-page-id: 1146942
description: Slimme lijst definiëren voor slimme campagne | Trigger - Marketo Docs - Productdocumentatie
title: Slimme lijst definiëren voor slimme campagne | Trigger
exl-id: 14d9b15e-864a-47ef-8f39-3d65e6036a82
feature: Smart Campaigns
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '228'
ht-degree: 0%

---

# Slimme lijst definiëren voor slimme campagne | Trigger {#define-smart-list-for-smart-campaign-trigger}

Maak een slimme Campagne in werking gesteld op één persoon in een tijd die op levende gebeurtenissen wordt gebaseerd door trekkers toe te voegen.

1. Klik in uw slimme campagne op de knop **Slimme lijst** tab.

   ![](assets/define-smart-list-for-smart-campaign-trigger-1.png)

1. Zoek de gewenste trigger en sleep deze naar het canvas.

   ![](assets/define-smart-list-for-smart-campaign-trigger-2.png)

   >[!NOTE]
   >
   >Een slimme campagne met triggers wordt uitgevoerd in **Trigger** in. Deze wordt op één persoon tegelijk uitgevoerd op basis van gebeurtenissen die worden geactiveerd en eventuele aanvullende filters.

   >[!IMPORTANT]
   >
   >Wanneer u een Booleaans veld in een slimme lijst van een triggercampagne gebruikt, moet u deze expliciet instellen op &#39;false&#39; om het veld tijdens de uitvoering van de campagne correct te laten evalueren.

1. Klik op de vervolgkeuzelijst en kies een operator.

   ![](assets/define-smart-list-for-smart-campaign-trigger-3.png)

   >[!CAUTION]
   >
   >Rode kronkelige lijnen geven fouten of ontbrekende informatie aan. Als de campagne niet wordt gecorrigeerd, is deze ongeldig en wordt deze niet uitgevoerd.

   >[!TIP]
   >
   >In een Slimme Campagne met zowel trekkers als filters, gaan de trekkers bij de bovenkant en wanneer teweeggebracht, slechts mensen die aan de filtercriteria voldoen gaan door de stroom.

1. Definieer de trigger.

   ![](assets/define-smart-list-for-smart-campaign-trigger-4.png)

   >[!NOTE]
   >
   >Bij meerdere triggers gaat een persoon door de flow als **ALLE** een van de triggers wordt geactiveerd.

Leer hoe u de campagne op een aantal mensen tegelijk kunt uitvoeren [Slimme lijst definiëren voor slimme campagne | Batch](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-batch.md).

>[!MORELIKETHIS]
>
>[Een stroomstap toevoegen aan een slimme campagne](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md)
