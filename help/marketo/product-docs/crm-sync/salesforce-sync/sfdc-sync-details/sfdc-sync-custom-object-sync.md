---
unique-page-id: 2953471
description: SFDC Sync - Custom Object Sync - Marketo Docs - Productdocumentatie
title: SFDC Sync - Aangepast object synchroniseren
exl-id: e491e0bc-04a9-4e78-97c3-a25b945d546a
feature: Salesforce Integration
source-git-commit: 79ae0d56dd4bb8bf563c6546cba54b89b5841425
workflow-type: tm+mt
source-wordcount: '283'
ht-degree: 1%

---

# SFDC-synchronisatie: Aangepaste objectsynchronisatie {#sfdc-sync-custom-object-sync}

Aangepaste objecten die in een Salesforce-instantie zijn gemaakt, kunnen ook deel uitmaken van het Marketo Engage. Hier is hoe u het kunt instellen.

>[!NOTE]
>
>**Vereiste Bevoegdheden Admin**

>[!PREREQUISITES]
>
>Om een douanevoorwerp te gebruiken, moet het aan a [ lood ](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-field-sync.md){target="_blank"}, [ contact ](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-contact-sync.md){target="_blank"}, of [ rekening ](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-account-sync.md){target="_blank"} voorwerp in Salesforce worden geassocieerd.

>[!IMPORTANT]
>
>De Marketo Sync-gebruiker heeft leestoegang nodig tot het aangepaste object om het object weer te geven en te synchroniseren.

## Aangepast object inschakelen  {#enable-custom-object}

1. Klik op **[!UICONTROL Admin]** en de koppeling **[!UICONTROL Salesforce Objects Sync]** .

   ![](assets/image2015-11-19-10-3a28-3a5.png).

1. Klik op **[!UICONTROL Sync Schema]** als dit uw eerste aangepaste object is.

   ![](assets/rtaimage-2.png)

1. Klik op **[!UICONTROL Disable Global Sync]**.

   ![](assets/image2015-4-22-10-3a45-3a0.png)

   >[!NOTE]
   >
   >Een eerste synchronisatie van het schema voor aangepaste Salesforce-objecten kan een paar minuten duren.

   ![](assets/image2015-4-22-10-3a45-3a18.png)

1. Sleep het aangepaste object dat u wilt synchroniseren naar het canvas.

   ![](assets/image2015-4-22-10-3a45-3a30.png)

   >[!NOTE]
   >
   >Aangepaste objecten moeten unieke namen hebben. Marketo ondersteunt geen twee verschillende aangepaste objecten met dezelfde naam.

1. Klik op **[!UICONTROL Enable Sync]**.

   ![](assets/image2015-4-22-10-3a45-3a50.png)

1. Klik nogmaals op **[!UICONTROL Enable Sync]** .

   ![](assets/image2015-4-22-10-3a46-3a10.png)

   >[!NOTE]
   >
   >Vergeet niet om uw wereldwijde synchronisatie opnieuw in te schakelen!

1. Ga terug naar **Salesforce** tabel.

   ![](assets/image2015-4-22-10-3a46-3a25.png)

1. Klik op **[!UICONTROL Enable Sync]**.

   ![](assets/image2015-4-22-10-3a50-3a26.png)

1. Als u al uw aangepaste Salesforce-objecten wilt weergeven, klikt u op **[!UICONTROL Admin]** en de koppeling **[!UICONTROL Salesforce Objects Sync]** (net als in stap 1 hierboven).

   ![](assets/image2016-6-23-9-3a28-3a23.png)

   >[!NOTE]
   >
   >* Marketo ondersteunt alleen aangepaste entiteiten die een of twee niveaus diep zijn gekoppeld aan standaardentiteiten.
   >
   >* In de aangepaste objectstructuur kan hetzelfde object meer dan één keer worden weergegeven, vanwege de directe verbindingen met een van de belangrijkste objecten (bijvoorbeeld leads, contactpersonen of accounts of indirecte verbindingen via een intermediair object). In dergelijke gevallen kiest u het object dat zich het dichtst bij het hoofdobject bevindt en slechts één object. Het meerdere keren selecteren van hetzelfde object kan de synchronisatie van dat aangepaste object belemmeren.

### Volgende functies: {#whats-next}

[ voeg/verwijder het Gebied van de Objecten van de Douane als Slimme Beperkingen List/Trigger ](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/add-remove-custom-object-field-as-smart-list-trigger-constraints.md){target="_blank"} toe

Uitstekend! U kunt nu gegevens uit dit aangepaste object gebruiken in slimme campagnes en slimme lijsten.
