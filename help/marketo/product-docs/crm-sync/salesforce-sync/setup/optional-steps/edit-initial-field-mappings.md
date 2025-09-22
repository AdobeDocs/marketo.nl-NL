---
unique-page-id: 4719287
description: Aanvankelijke veldtoewijzingen bewerken - Marketo Docs - Productdocumentatie
title: Aanvankelijke veldtoewijzingen bewerken
exl-id: 320613d1-3845-4e05-a704-0db0f8027dc8
feature: Salesforce Integration
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '259'
ht-degree: 0%

---

# Aanvankelijke veldtoewijzingen bewerken {#edit-initial-field-mappings}

>[!NOTE]
>
>Deze functie is alleen toegankelijk voordat u de toepassing voor het eerst synchroniseert met Salesforce. Wanneer op de knop **[!UICONTROL Sync Now]** is geklikt, kan dit niet meer worden gedaan.

Tijdens de eerste synchronisatie met Salesforce combineert Marketo Engage automatisch aangepaste velden met dezelfde naam tot één veld aan de Marketo-zijde om ervoor te zorgen dat de gegevens kunnen worden uitgewisseld met objecten Lead en Contact in de CRM. In dit artikel wordt uitgelegd hoe u deze toewijzingen kunt aanpassen.

## Niet-toegewezen velden toewijzen {#map-unmapped-fields}

Wanneer een veld in de map [!UICONTROL Unmapped Fields] wordt weergegeven, betekent dit dat het niet is toegewezen aan een vergelijkbaar veld op de lijst met leads of in Salesforce. U kunt dat herstellen.

1. Klik op **[!UICONTROL Edit Mappings]**.

![](assets/image2014-12-9-13-3a31-3a0.png)

1. Open de map **[!UICONTROL Unmapped Custom Fields]** .

   ![](assets/two.png)

1. Sleep een niet-toegewezen aangepast veld naar een ander veld om de velden samen toe te wijzen.

   >[!NOTE]
   >
   >U kunt alleen aangepaste veldtoewijzingen bewerken. Standaardveldtoewijzingen kunnen niet worden gewijzigd.

   ![](assets/three.png)

1. Klik op **[!UICONTROL Finish Mappings]** wanneer u klaar bent.

   ![](assets/four.png)

## Bestaande toewijzing verbreken {#break-existing-mapping}

Als u velden met dezelfde naam op de lead en het contactobject hebt, wijst Marketo deze automatisch toe. U kunt ze anders vinden en verschillende gegevens bevatten. Breek de afbeelding zo uit.

1. Klik op **[!UICONTROL Edit Mappings]**.

   ![](assets/image2014-12-9-13-3a31-3a37.png)

1. Markeer een toegewezen veld en klik op **[!UICONTROL Break Mapping]** om de velden van elkaar te scheiden.

   ![](assets/image2014-12-9-13-3a31-3a47.png)

1. Klik op **[!UICONTROL Finish Mappings]** wanneer u klaar bent.

   ![](assets/image2014-12-9-13-3a31-3a58.png)

   Mooi! U bent bijna klaar met de eerste synchronisatie.

## Schema opnieuw instellen {#reset-schema}

1. Als u in Salesforce wijzigingen aanbrengt in het schema terwijl u aan de toewijzingen werkt, kunt u de wijzigingen terugtrekken door op **[!UICONTROL Reset Schema]** te klikken.

   * Alle toewijzingswijzigingen worden opnieuw ingesteld.
   * Als u het schema opnieuw instelt, worden alleen velden toegevoegd en niet verwijderd (zelfs als u deze verbergt voor de synchronisatiegebruiker).

   ![](assets/image2014-12-9-13-3a32-3a8.png)
