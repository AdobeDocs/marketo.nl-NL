---
unique-page-id: 2953471
description: SFDC Sync - Custom Object Sync - Marketo Docs - Productdocumentatie
title: SFDC-synchronisatie - Aangepaste objectsynchronisatie
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '215'
ht-degree: 0%

---


# SFDC-synchronisatie: Aangepaste objectsync {#sfdc-sync-custom-object-sync}

Aangepaste objecten die in uw Salesforce-instantie zijn gemaakt, kunnen ook onderdeel zijn van Marketo.  Hier is hoe je het instelt.

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

>[!PREREQUISITES]
>
>Als u een aangepast object wilt gebruiken, moet het worden gekoppeld aan een [lead](sfdc-sync-lead-sync.md), [contact](sfdc-sync-contact-sync.md)of [account](sfdc-sync-account-sync.md)object in Salesforce.

## Aangepast object {#enable-custom-object} inschakelen

1. Klik op **Admin** en de ** Salesforce-objecten synchroniseren **link**.**

   ![](assets/image2015-11-19-10-3a28-3a5.png).

1. Als dit uw eerste Voorwerp van de Douane is, klik **Schema van de Synchronisatie.**

   ![](assets/rtaimage-2.png)

1. Klik **Globale synchronisatie uitschakelen**

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

1. Klik **Synchronisatie inschakelen.**

   ![](assets/image2015-4-22-10-3a45-3a50.png)

1. Klik **Schakel Sync** opnieuw in.

   ![](assets/image2015-4-22-10-3a46-3a10.png)

   >[!NOTE]
   >
   >**Herinnering**
   >
   >
   >Vergeet niet om uw wereldwijde synchronisatie opnieuw in te schakelen!

1. Ga terug naar de tab **Salesforce **.

   ![](assets/image2015-4-22-10-3a46-3a25.png)

1. Klik **Synchronisatie inschakelen.**

   ![](assets/image2015-4-22-10-3a50-3a26.png)

1. Als u al uw aangepaste Salesforce-objecten wilt weergeven, klikt u op **Admin** en de koppeling *** Salesforce-objecten synchroniseren **(dezelfde koppeling als in stap 1 hierboven).

   ![](assets/image2016-6-23-9-3a28-3a23.png)

   >[!NOTE]
   >
   >Marketo ondersteunt alleen aangepaste entiteiten die een of twee niveaus diep zijn gekoppeld aan standaardentiteiten.

### Volgende: {#whats-next}

[Aangepast objectveld toevoegen/verwijderen als slimme lijst/triggerbeperkingen](../../../../product-docs/crm-sync/salesforce-sync/setup/optional-steps/add-remove-custom-object-field-as-smart-list-trigger-constraints.md)

Uitstekend! U kunt nu gegevens uit dit aangepaste object gebruiken in slimme campagnes en slimme lijsten.

