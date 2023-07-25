---
unique-page-id: 2953471
description: SFDC Sync - Custom Object Sync - Marketo Docs - Productdocumentatie
title: SFDC-synchronisatie - Aangepaste objectsynchronisatie
exl-id: e491e0bc-04a9-4e78-97c3-a25b945d546a
feature: Salesforce Integration
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '234'
ht-degree: 0%

---

# SFDC-synchronisatie: Aangepaste objectsynchronisatie {#sfdc-sync-custom-object-sync}

Aangepaste objecten die in uw Salesforce-instantie zijn gemaakt, kunnen ook deel uitmaken van Marketo.  Hier is hoe je het instelt.

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

>[!PREREQUISITES]
>
>Als u een aangepast object wilt gebruiken, moet het zijn gekoppeld aan een [leiden](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-field-sync.md), [contact](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-contact-sync.md), of [account](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-account-sync.md) object in Salesforce.

>[!IMPORTANT]
>
>De Marketo Sync-gebruiker heeft leestoegang nodig tot het aangepaste object om het object weer te geven en te synchroniseren.

## Aangepast object inschakelen  {#enable-custom-object}

1. Klikken **Beheer** en de **Salesforce-objecten synchroniseren** koppeling.

   ![](assets/image2015-11-19-10-3a28-3a5.png).

1. Als dit uw eerste aangepaste object is, klikt u op **Schema synchroniseren**.

   ![](assets/rtaimage-2.png)

1. Klikken **Globale synchronisatie uitschakelen**.

   ![](assets/image2015-4-22-10-3a45-3a0.png)

   >[!NOTE]
   >
   >Een eerste synchronisatie van het schema van aangepaste Salesforce-objecten kan een paar minuten duren.

   ![](assets/image2015-4-22-10-3a45-3a18.png)

1. Sleep het aangepaste object dat u wilt synchroniseren naar het canvas.

   ![](assets/image2015-4-22-10-3a45-3a30.png)

   >[!NOTE]
   >
   >Aangepaste objecten moeten unieke namen hebben. Marketo ondersteunt geen twee verschillende aangepaste objecten met dezelfde naam.

1. Klikken **Sync inschakelen**.

   ![](assets/image2015-4-22-10-3a45-3a50.png)

1. Klikken **Sync inschakelen** opnieuw.

   ![](assets/image2015-4-22-10-3a46-3a10.png)

   >[!NOTE]
   >
   >Vergeet niet om uw wereldwijde synchronisatie opnieuw in te schakelen!

1. Ga terug naar de **Salesforce** tab.

   ![](assets/image2015-4-22-10-3a46-3a25.png)

1. Klikken **Sync inschakelen**.

   ![](assets/image2015-4-22-10-3a50-3a26.png)

1. Als u al uw aangepaste Salesforce-objecten wilt weergeven, klikt u op **Beheer** en de **Salesforce-objecten synchroniseren** koppeling (zelfde als bovenstaande stap 1).

   ![](assets/image2016-6-23-9-3a28-3a23.png)

   >[!NOTE]
   >
   >Marketo ondersteunt alleen aangepaste entiteiten die een of twee niveaus diep zijn gekoppeld aan standaardentiteiten.

### Volgende: {#whats-next}

[Aangepast objectveld toevoegen/verwijderen als slimme lijst/triggerbeperkingen](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/add-remove-custom-object-field-as-smart-list-trigger-constraints.md)

Uitstekend! U kunt nu gegevens uit dit aangepaste object gebruiken in slimme campagnes en slimme lijsten.
