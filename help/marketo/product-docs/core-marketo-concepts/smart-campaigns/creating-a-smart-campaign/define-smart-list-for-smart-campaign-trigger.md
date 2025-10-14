---
unique-page-id: 1146942
description: Slimme lijst definiëren voor slimme campagne | Trigger - Marketo Docs - Productdocumentatie
title: Slimme lijst definiëren voor slimme campagne | Trigger
exl-id: 14d9b15e-864a-47ef-8f39-3d65e6036a82
feature: Smart Campaigns
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '251'
ht-degree: 0%

---

# Slimme lijst definiëren voor slimme campagne | Trigger {#define-smart-list-for-smart-campaign-trigger}

Maak een slimme Campagne in werking gesteld op één persoon in een tijd die op levende gebeurtenissen wordt gebaseerd door trekkers toe te voegen.

>[!CAUTION]
>
>Het maken van Slimme Lijst of de Stap van de Stroom geeft aan een actieve campagne kan zijn functionaliteit potentieel breken. Als u dit wilt doen, moet u voorzichtig te werk gaan.

1. Klik in de slimme campagne op het tabblad **[!UICONTROL Smart List]** .

   ![](assets/define-smart-list-for-smart-campaign-trigger-1.png)

1. Zoek de gewenste trigger en sleep deze naar het canvas.

   ![](assets/define-smart-list-for-smart-campaign-trigger-2.png)

   >[!NOTE]
   >
   >Een slimme Campagne met trekkerlooppas op _Trigger_ wijze. De functie wordt op één persoon tegelijk uitgevoerd op basis van gebeurtenissen die worden geactiveerd en eventuele aanvullende filters.

   >[!IMPORTANT]
   >
   >Wanneer u een Booleaans veld in een triggercampagne Slimme lijst gebruikt, moet u deze expliciet instellen op &#39;false&#39;, zodat het veld de actie tijdens de uitvoering correct kan evalueren.

1. Klik op de vervolgkeuzelijst en kies een operator.

   ![](assets/define-smart-list-for-smart-campaign-trigger-3.png)

   >[!CAUTION]
   >
   >Rode kronkelige lijnen geven fouten of ontbrekende informatie aan. Als de campagne niet wordt gecorrigeerd, is deze ongeldig en wordt deze niet uitgevoerd.

   >[!TIP]
   >
   >In een Slimme Campagne met zowel trekkers als filters, gaan de trekkers bij de bovenkant en wanneer teweeggebracht, slechts mensen die aan de filtercriteria voldoen gaan door de stroom.

1. Geef de trigger op.

   ![](assets/define-smart-list-for-smart-campaign-trigger-4.png)

   >[!NOTE]
   >
   >Met veelvoudige trekkers, gaat een persoon door de stroom als _OM HET EVEN WELKE_ één van de trekkers wordt geactiveerd.

Om de campagne op een reeks mensen in werking te stellen allen tezelfdertijd, leer hoe te [&#x200B; bepalen Slimme Lijst voor Slimme Campagne | Batch &#x200B;](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-batch.md){target="_blank"} .

>[!MORELIKETHIS]
>
>[&#x200B; voeg een Stap van de Stroom aan een Slimme Campagne toe &#x200B;](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md){target="_blank"}
