---
unique-page-id: 4719297
description: Aangepaste objectsynchronisatie inschakelen/uitschakelen - Marketo Docs - Productdocumentatie
title: Aangepaste objectsynchronisatie inschakelen/uitschakelen
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '220'
ht-degree: 0%

---


# Aangepaste objectsynchronisatie inschakelen/uitschakelen {#enable-disable-custom-object-sync}

Aangepaste objecten die in uw Salesforce-instantie zijn gemaakt, kunnen ook onderdeel zijn van Marketo. Hier is hoe je het instelt.

## Aangepaste objectsynchronisatie inschakelen/uitschakelen {#enable-disable-custom-object-sync-1}

>[!NOTE]
>
>Beheerdersrechten vereist.

1. Klik op **Beheerder**.

   ** ![](assets/one.png)

   **

1. Klik in het menu Databasebeheer op **Salesforce** **Objects Sync**.

   ![](assets/two-2.png)

1. Als dit het eerste aangepaste object is, klikt u op Schema **synchroniseren.** Klik anders op Schema **** vernieuwen om ervoor te zorgen dat u het meest recente schema hebt.

   ![](assets/image2014-12-10-10-3a14-3a44.png)

1. Als de globale synchronisatie wordt uitgevoerd, moet u deze uitschakelen door op Globale synchronisatie **uitschakelen te klikken.**

   ![](assets/image2014-12-10-10-3a14-3a54.png)

   >[!NOTE]
   >
   >Een synchronisatie van het schema van aangepaste Salesforce-objecten kan een paar minuten duren.

1. Klik op Schema **** vernieuwen.

   ![](assets/image2014-12-10-10-3a15-3a7.png)

1. Selecteer het object dat u wilt synchroniseren en klik op Synchronisatie **inschakelen**.

   >[!TIP]
   >
   >Marketo kan een aangepast object alleen synchroniseren als het een directe relatie heeft met het object Lead, Contact of Account in Salesforce.

   ![](assets/image2014-12-10-10-3a15-3a30.png)

1. Klik nogmaals **op Synchronisatie** inschakelen.

   ** ![](assets/image2014-12-10-10-3a15-3a40.png)

   **

1. Ga terug naar het tabblad **Salesforce** en klik op **Synchronisatie** inschakelen.

   ![](assets/image2014-12-10-10-3a15-3a49.png)

## Aangepaste objecten gebruiken {#using-your-custom-objects}

>[!NOTE]
>
>U kunt aangepaste objecten niet gebruiken in slimme campagnes met triggers.

1. Sleep in uw slimme lijst over het **filter** Heeft opportuniteit en stel dit in op **true**.

   ![](assets/image2015-8-26-9-3a39-3a28.png)

1. Gebruik vervolgens filterbeperkingen om de focus te beperken.

   ![](assets/image2015-8-24-14-3a18-3a53.png)

   Uitstekend! U kunt de gegevens van dit aangepaste object nu gebruiken in slimme campagnes en slimme lijsten.

>[!NOTE]
>
>**Verwante artikelen**
>
>* [Aangepast objectveld toevoegen/verwijderen als slimme lijst/triggerbeperkingen](add-remove-custom-object-field-as-smart-list-trigger-constraints.md)

>



