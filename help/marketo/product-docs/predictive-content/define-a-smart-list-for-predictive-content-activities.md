---
unique-page-id: 10097873
description: Een slimme lijst definiëren voor activiteiten met betrekking tot preventieve inhoud - Marketo Docs - Productdocumentatie
title: Een slimme lijst definiëren voor activiteiten met betrekking tot voorspellende inhoud
translation-type: tm+mt
source-git-commit: 00887ea53e395bea3a11fd28e0ac98b085ef6ed8
workflow-type: tm+mt
source-wordcount: '352'
ht-degree: 0%

---


# Een slimme lijst definiëren voor activiteiten met betrekking tot voorspellende inhoud {#define-a-smart-list-for-predictive-content-activities}

>[!NOTE]
>
>Afhankelijk van de aankoopdatum kan uw abonnement op Marketo de optie Voorspelende inhoud of Inhoud`<sup>AI</sup>`markeren bevatten. Marketo schakelt de functie Content`<sup>AI</sup>` Analytics voor gebruikers die gebruikmaken van voorspellende inhoud in tot 30 april 2018. Als u deze functies na die datum wilt behouden, neemt u contact op met de manager Succes bij Marketo-klanten om te upgraden naar Marketo-inhoud`<sup>AI</sup>`.

U kunt activiteiten met voorspellende inhoud gebruiken in triggers en filters wanneer u een slimme lijst definieert in een slimme campagne. U kunt een actie voor iedereen teweegbrengen die voorspelbare inhoud via het malplaatje [van de Media](enabling-predictive-content/enable-predictive-content-for-web-rich-media.md)Rich, de Bar [van de Aanbeveling van de](enabling-predictive-content/enable-the-content-recommendation-bar.md)Inhoud, of in een e-mail klikt.

1. Navigeer in uw slimme campagne naar het tabblad **Slimme lijst** .

   ![](assets/smart-list-1.png)

   >[!NOTE]
   >
   >**Diep duiken**
   >
   >
   >Slimme lijsten kunnen verbazingwekkende dingen doen. Meer informatie vindt u in de diepe duik van de [slimme lijst](../../product-docs/core-marketo-concepts/smart-campaigns/understanding-smart-campaigns.md).

1. Zoek de trigger en sleep deze naar het canvas.

   ![](assets/smart-list-drag-trigger-hands.png)

   >[!NOTE]
   >
   >Een slimme campagne met triggers wordt uitgevoerd in de triggermodus. De functie wordt op één persoon tegelijk uitgevoerd op basis van gebeurtenissen die worden geactiveerd en de filters worden toegevoegd.

1. Klik op de vervolgkeuzelijst **Naam** en selecteer een operator.

   ![](assets/smart-list-dropdown-hands.png)

1. Definieer de trigger.

   ![](assets/smart-lislt-select-content-hands.png)

1. Voeg de beperking **Type** toe.

   ![](assets/clicks-predictive-content-add-constraint-hands.png)

1. Selecteer de bron die u nodig hebt voor uw slimme lijst.

   ![](assets/pc-add-constraint.png)

1. Als u de e-mailbron voor uw vooruitlopende inhoud gebruikt, voegt u de **Klik Verbinding in de trekker van E-mail **toe. Selecteer uw e-mail en voeg de restrictie **Is voorspelbaar** toe, die als **waar** wordt gedefinieerd.

   ![](assets/clicks-link-in-email-trigger-hands.png)

1. Voeg desgewenst andere filters toe.

   ![](assets/clicked-predictive-content-filter.png)

   >[!TIP]
   >
   >In een slimme campagne met zowel triggers als filters gaan de triggers bovenaan. Wanneer geactiveerd, gaan alleen mensen die aan de filtercriteria voldoen door de flow.

   >[!NOTE]
   >
   >Bij meerdere triggers gaat een persoon door naar de flow als een van de triggers wordt geactiveerd.

   [een slimme lijst definiëren voor een &#39;batch smart&#39;-campagne](../../product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-batch.md)

   >[!NOTE]
   >
   >**Verwante artikelen**
   >
   >    
   >    
   >    * [Slimme lijst definiëren voor slimme campagne | Batch](../../product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-batch.md)
   >    * [Een stroomstap toevoegen aan een slimme campagne](../../product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md)
   >    * [Een slimme lijst definiëren voor activiteiten van webpersonalisatie](../../product-docs/web-personalization/working-with-web-campaigns/define-a-smart-list-for-web-personalization-activities.md)
   >    * [Voorspelende inhoud voor web-rijke media inschakelen](enabling-predictive-content/enable-predictive-content-for-web-rich-media.md)
   >    * [De balk met aanbevelingen voor inhoud inschakelen](enabling-predictive-content/enable-the-content-recommendation-bar.md)


Leer hoe u de campagne op een aantal mensen tegelijk kunt uitvoeren.