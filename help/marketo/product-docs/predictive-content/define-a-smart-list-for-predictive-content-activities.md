---
unique-page-id: 10097873
description: Een slimme lijst definiëren voor activiteiten met betrekking tot preventieve inhoud - Marketo Docs - Productdocumentatie
title: Een slimme lijst definiëren voor activiteiten met betrekking tot voorspellende inhoud
exl-id: 2c72b215-8c0b-48b4-8492-8e3fe832fae9
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '300'
ht-degree: 0%

---

# Een slimme lijst definiëren voor activiteiten met betrekking tot voorspellende inhoud {#define-a-smart-list-for-predictive-content-activities}

U kunt activiteiten met voorspellende inhoud gebruiken in triggers en filters wanneer u een slimme lijst definieert in een slimme campagne. U kunt een actie activeren voor iedereen die via het dialoogvenster [Rich Media-sjabloon](/help/marketo/product-docs/predictive-content/enabling-predictive-content/enable-predictive-content-for-web-rich-media.md)de [De balk met aanbevelingen voor inhoud](/help/marketo/product-docs/predictive-content/enabling-predictive-content/enable-the-content-recommendation-bar.md)of in een [email](/help/marketo/product-docs/predictive-content/enabling-predictive-content/enable-predictive-content-in-emails.md).

1. Navigeer in uw slimme campagne naar de **Slimme lijst** tab.

   ![](assets/smart-list-1.png)

   >[!NOTE]
   >
   >Slimme lijsten kunnen verbazingwekkende dingen doen. Meer informatie in het dialoogvenster [diepe duik voor slimme lijst](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/understanding-smart-campaigns.md).

1. Zoek de trigger en sleep deze naar het canvas.

   ![](assets/smart-list-drag-trigger-hands.png)

   >[!NOTE]
   >
   >Een slimme campagne met triggers wordt uitgevoerd in de triggermodus. De functie wordt op één persoon tegelijk uitgevoerd op basis van gebeurtenissen die worden geactiveerd en de filters worden toegevoegd.

1. Klik op de knop **Naam** en selecteert u een operator.

   ![](assets/smart-list-dropdown-hands.png)

1. Definieer de trigger.

   ![](assets/smart-lislt-select-content-hands.png)

1. Voeg de **Type** beperking.

   ![](assets/clicks-predictive-content-add-constraint-hands.png)

1. Selecteer de bron die u nodig hebt voor uw slimme lijst.

   ![](assets/pc-add-constraint.png)

1. Als u de e-mailbron voor uw voorspellende inhoud gebruikt, voegt u de **Klik op Koppeling in e-mail** trigger. Selecteer uw e-mail en voeg de **Is voorspelbaar** beperking, gedefinieerd als **true**.

   ![](assets/clicks-link-in-email-trigger-hands.png)

1. Voeg desgewenst andere filters toe.

   ![](assets/clicked-predictive-content-filter.png)

   >[!TIP]
   >
   >In een slimme campagne met zowel triggers als filters gaan de triggers bovenaan. Wanneer geactiveerd, gaan alleen mensen die aan de filtercriteria voldoen door de flow.

   >[!NOTE]
   >
   >Bij meerdere triggers gaat een persoon door naar de flow als een van de triggers wordt geactiveerd.

   Leer hoe u de campagne op een aantal mensen tegelijk kunt uitvoeren [een slimme lijst definiëren voor een &#39;batch smart&#39;-campagne](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-batch.md).

   >[!MORELIKETHIS]
   >
   >* [Slimme lijst definiëren voor slimme campagne | Batch](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-batch.md)
   >* [Een stroomstap toevoegen aan een slimme campagne](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md)
   >* [Een slimme lijst definiëren voor activiteiten van webpersonalisatie](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/define-a-smart-list-for-web-personalization-activities.md)
   >* [Voorspelende inhoud voor web-rijke media inschakelen](/help/marketo/product-docs/predictive-content/enabling-predictive-content/enable-predictive-content-for-web-rich-media.md)
   >* [De balk met aanbevelingen voor inhoud inschakelen](/help/marketo/product-docs/predictive-content/enabling-predictive-content/enable-the-content-recommendation-bar.md)

