---
unique-page-id: 4719297
description: Aangepaste objectsynchronisatie inschakelen/uitschakelen - Marketo Docs - Productdocumentatie
title: Aangepaste objectsynchronisatie inschakelen/uitschakelen
exl-id: f17d9135-b33e-48c0-9220-131fb437e9e5
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '218'
ht-degree: 0%

---

# Aangepaste objectsynchronisatie inschakelen/uitschakelen {#enable-disable-custom-object-sync}

Aangepaste objecten die in uw Salesforce-instantie zijn gemaakt, kunnen ook deel uitmaken van Marketo. Hier is hoe je het instelt.

## Aangepaste objectsynchronisatie inschakelen/uitschakelen {#enable-disable-custom-object-sync-1}

>[!NOTE]
>
>Beheerdersrechten vereist.

1. Klikken **Beheer**.

   ![](assets/one.png)

1. Klik in het menu Databasebeheer op **Salesforce-objecten synchroniseren**.

   ![](assets/two-2.png)

1. Als dit uw eerste aangepaste object is, klikt u op **Schema synchroniseren.** Anders klikken **Schema vernieuwen** om ervoor te zorgen dat u over de nieuwste informatie beschikt.

   ![](assets/image2014-12-10-10-3a14-3a44.png)

1. Als de algemene synchronisatie wordt uitgevoerd, moet u deze uitschakelen door op **Globale synchronisatie uitschakelen.**

   ![](assets/image2014-12-10-10-3a14-3a54.png)

   >[!NOTE]
   >
   >Een synchronisatie van het schema van aangepaste Salesforce-objecten kan een paar minuten duren.

1. Klikken **Schema vernieuwen**.

   ![](assets/image2014-12-10-10-3a15-3a7.png)

1. Selecteer het object dat u wilt synchroniseren en klik op **Sync inschakelen**.

   >[!TIP]
   >
   >Marketo kan een aangepast object alleen synchroniseren als het een directe relatie heeft met het object Lead, Contact of Account in Salesforce.

   ![](assets/image2014-12-10-10-3a15-3a30.png)

1. Klikken **Sync inschakelen** opnieuw.

   ![](assets/image2014-12-10-10-3a15-3a40.png)

1. Ga terug naar de **Salesforce** en klik op **Sync inschakelen**.

   ![](assets/image2014-12-10-10-3a15-3a49.png)

## Aangepaste objecten gebruiken {#using-your-custom-objects}

>[!NOTE]
>
>U kunt aangepaste objecten niet gebruiken in slimme campagnes met triggers.

1. Sleep in uw slimme lijst over de **Heeft mogelijkheid** filter en instellen op **true**.

   ![](assets/image2015-8-26-9-3a39-3a28.png)

1. Gebruik vervolgens filterbeperkingen om de focus te beperken.

   ![](assets/image2015-8-24-14-3a18-3a53.png)

   Uitstekend! U kunt de gegevens van dit aangepaste object nu gebruiken in slimme campagnes en slimme lijsten.

>[!MORELIKETHIS]
>
>[Aangepast objectveld toevoegen/verwijderen als slimme lijst/triggerbeperkingen](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/add-remove-custom-object-field-as-smart-list-trigger-constraints.md)
