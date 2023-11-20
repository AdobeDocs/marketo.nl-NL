---
unique-page-id: 4719297
description: Aangepaste objectsynchronisatie inschakelen/uitschakelen - Marketo Docs - Productdocumentatie
title: Aangepaste objectsynchronisatie inschakelen/uitschakelen
exl-id: f17d9135-b33e-48c0-9220-131fb437e9e5
feature: Salesforce Integration
source-git-commit: 756a38ba87dd5af9ee783e9709056d444d4f415b
workflow-type: tm+mt
source-wordcount: '196'
ht-degree: 1%

---

# Aangepaste objectsynchronisatie inschakelen/uitschakelen {#enable-disable-custom-object-sync}

Aangepaste objecten die in uw Salesforce-instantie zijn gemaakt, kunnen ook deel uitmaken van het Marketo Engage. Hier is hoe u het kunt instellen.

## Aangepaste objectsynchronisatie inschakelen/uitschakelen {#enable-disable-custom-object-sync-1}

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

1. Klik op **[!UICONTROL Admin]**.

   ![](assets/one.png)

1. Klik in het menu Database Management op **[!UICONTROL Salesforce Objects Sync]**.

   ![](assets/two-2.png)

1. Als dit uw eerste aangepaste object is, klikt u op **[!UICONTROL Sync schema]**. Anders klikken **[!UICONTROL Refresh Schema]** om ervoor te zorgen dat u over de nieuwste informatie beschikt.

   ![](assets/image2014-12-10-10-3a14-3a44.png)

1. Als de algemene synchronisatie wordt uitgevoerd, moet u deze uitschakelen door op **[!UICONTROL Disable Global Sync]**.

   ![](assets/image2014-12-10-10-3a14-3a54.png)

   >[!NOTE]
   >
   >Een synchronisatie van het schema van aangepaste Salesforce-objecten kan een paar minuten duren.

1. Klik op **[!UICONTROL Refresh Schema]**.

   ![](assets/image2014-12-10-10-3a15-3a7.png)

1. Selecteer het object dat u wilt synchroniseren en klik **[!UICONTROL Enable Sync]**.

   >[!TIP]
   >
   >Marketo kan een aangepast object alleen synchroniseren als het een directe relatie heeft met het object Lead, Contact of Account in Salesforce.

   ![](assets/image2014-12-10-10-3a15-3a30.png)

1. Klikken **[!UICONTROL Enable Sync]** opnieuw.

   ![](assets/image2014-12-10-10-3a15-3a40.png)

1. Ga terug naar de **[!DNL Salesforce]** en klik op **[!UICONTROL Enable Sync]**.

   ![](assets/image2014-12-10-10-3a15-3a49.png)

## Aangepaste objecten gebruiken {#using-your-custom-objects}

>[!NOTE]
>
>U kunt geen aangepaste objecten gebruiken in slimme campagnes met triggers.

1. Sleep in de slimme lijst over de **[!UICONTROL Has Opportunity]** filter en instellen op **[!UICONTROL true]**.

   ![](assets/image2015-8-26-9-3a39-3a28.png)

1. Gebruik vervolgens filterbeperkingen om de focus te beperken.

   ![](assets/image2015-8-24-14-3a18-3a53.png)

   Uitstekend! U kunt de gegevens van dit aangepaste object nu gebruiken in slimme campagnes en slimme lijsten.

>[!MORELIKETHIS]
>
>[Aangepast objectveld toevoegen/verwijderen als slimme lijst/triggerbeperkingen](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/add-remove-custom-object-field-as-smart-list-trigger-constraints.md){target="_blank"}
