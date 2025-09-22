---
unique-page-id: 4719297
description: Aangepaste objectsynchronisatie inschakelen/uitschakelen - Marketo Docs - Productdocumentatie
title: Aangepaste objectsynchronisatie inschakelen/uitschakelen
exl-id: f17d9135-b33e-48c0-9220-131fb437e9e5
feature: Salesforce Integration
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '197'
ht-degree: 0%

---

# Aangepaste objectsynchronisatie inschakelen/uitschakelen {#enable-disable-custom-object-sync}

Aangepaste objecten die in een Salesforce-instantie zijn gemaakt, kunnen ook deel uitmaken van Marketo Engage. Hier is hoe u het kunt instellen.

## Aangepaste objectsynchronisatie inschakelen/uitschakelen {#enable-disable-custom-object-sync-1}

>[!NOTE]
>
>**vereiste toestemmingen Admin**

1. Ga naar het **[!UICONTROL Admin]** -gebied.

   ![](assets/enable-disable-custom-object-sync-1.png)

1. Klik in het menu Databasebeheer op **[!UICONTROL Salesforce Objects Sync]** .

   ![](assets/enable-disable-custom-object-sync-2.png)

1. Klik op **[!UICONTROL Sync schema]** als dit uw eerste aangepaste object is. Klik anders op **[!UICONTROL Refresh Schema]** om ervoor te zorgen dat u de meest recente versie hebt.

   ![](assets/enable-disable-custom-object-sync-3.png)

1. Als de algemene synchronisatie wordt uitgevoerd, moet u deze uitschakelen door op **[!UICONTROL Disable Global Sync]** te klikken.

   ![](assets/image2014-12-10-10-3a14-3a54.png)

   >[!NOTE]
   >
   >Een synchronisatie van het schema voor aangepaste objecten van [!DNL Salesforce] kan een paar minuten duren.

1. Klik op **[!UICONTROL Refresh Schema]**.

   ![](assets/image2014-12-10-10-3a15-3a7.png)

1. Selecteer het object dat u wilt synchroniseren en klik op **[!UICONTROL Enable Sync]** .

   >[!TIP]
   >
   >Marketo kan een aangepast object alleen synchroniseren als het een directe relatie heeft met het object Lead, Contact of Account in [!DNL Salesforce] .

   ![](assets/image2014-12-10-10-3a15-3a30.png)

1. Klik nogmaals op **[!UICONTROL Enable Sync]** .

   ![](assets/image2014-12-10-10-3a15-3a40.png)

1. Ga terug naar de tab **[!DNL Salesforce]** en klik op **[!UICONTROL Enable Sync]** .

   ![](assets/image2014-12-10-10-3a15-3a49.png)

## Aangepaste objecten gebruiken {#using-your-custom-objects}

>[!NOTE]
>
>U kunt geen aangepaste objecten gebruiken in slimme campagnes met triggers.

1. Sleep in de slimme lijst over het filter **[!UICONTROL Has Opportunity]** en stel dit in op **[!UICONTROL true]** .

   ![](assets/image2015-8-26-9-3a39-3a28.png)

1. Gebruik vervolgens filterbeperkingen om de focus te beperken.

   ![](assets/image2015-8-24-14-3a18-3a53.png)

   Uitstekend! U kunt de gegevens van dit aangepaste object nu gebruiken in slimme campagnes en slimme lijsten.

>[!MORELIKETHIS]
>
>[ voeg/verwijder het Gebied van de Objecten van de Douane als Slimme Beperkingen List/Trigger ](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/add-remove-custom-object-field-as-smart-list-trigger-constraints.md){target="_blank"} toe
