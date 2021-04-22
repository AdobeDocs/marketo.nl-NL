---
unique-page-id: 4719287
description: Aanvankelijke veldtoewijzingen bewerken - Marketo Docs - Productdocumentatie
title: Aanvankelijke veldtoewijzingen bewerken
exl-id: 320613d1-3845-4e05-a704-0db0f8027dc8
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '278'
ht-degree: 0%

---

# Eerste veldtoewijzingen bewerken {#edit-initial-field-mappings}

>[!NOTE]
>
>Deze functie is alleen toegankelijk voor de eerste synchronisatie met Salesforce. Wanneer op de knop **Nu synchroniseren** is gedrukt, kan dit niet meer worden gedaan.

Tijdens de eerste synchronisatie met Salesforce combineert Marketo automatisch aangepaste velden met dezelfde naam tot één veld aan Marketo-zijde, zodat de gegevens kunnen worden uitgewisseld met objecten Lead en Contact in de CRM. In dit artikel wordt uitgelegd hoe u deze toewijzingen kunt aanpassen.

## Niet-toegewezen velden toewijzen {#map-unmapped-fields}

Wanneer u een veld ziet in de map Niet-toegewezen velden, betekent dit dat het veld niet is toegewezen aan een vergelijkbaar veld op de lead of contactpersoon in Salesforce. U kunt dat herstellen.

1. Klik **Toewijzingen bewerken**.

![](assets/image2014-12-9-13-3a31-3a0.png)

1. Open de map **Niet-toegewezen aangepaste velden**.

   ![](assets/two.png)

1. Sleep een niet-toegewezen aangepast veld naar een ander veld om de velden samen toe te wijzen.

   >[!NOTE]
   >
   >U kunt alleen aangepaste veldtoewijzingen bewerken. Standaardveldtoewijzingen kunnen niet worden gewijzigd.

   ![](assets/three.png)

1. Klik **Toewijzingen voltooien** wanneer u wordt gedaan.

   ![](assets/four.png)

## Bestaande toewijzing {#break-existing-mapping} verbreken

Als u velden met dezelfde naam op de lead en het contactobject hebt, wijst Marketo deze automatisch toe. U kunt ze anders vinden en verschillende gegevens bevatten. Breek de afbeelding zo uit.

1. Klik **Toewijzingen bewerken**.

   ![](assets/image2014-12-9-13-3a31-3a37.png)

1. Markeer een toegewezen veld en klik op **Toewijzing verbreken** om de velden te scheiden.

   ![](assets/image2014-12-9-13-3a31-3a47.png)

1. Klik **Toewijzingen voltooien** wanneer u wordt gedaan.

   ![](assets/image2014-12-9-13-3a31-3a58.png)

   Mooi! U bent bijna klaar met de eerste synchronisatie.

## Schema {#reset-schema} herstellen

1. Als u sommige veranderingen in het schema in Salesforce terwijl het werken aan de afbeeldingen aanbrengt, kunt u de veranderingen trekken door **Schema** van het Terugstellen te klikken.

   * Alle toewijzingswijzigingen worden opnieuw ingesteld.
   * Als u het schema opnieuw instelt, worden alleen velden toegevoegd en niet verwijderd (zelfs als u deze verbergt voor de synchronisatiegebruiker).
   ![](assets/image2014-12-9-13-3a32-3a8.png)
