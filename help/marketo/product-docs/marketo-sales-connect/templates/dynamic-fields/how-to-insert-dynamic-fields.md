---
unique-page-id: 14352592
description: Dynamische velden invoegen - Marketo Docs - Productdocumentatie
title: Dynamische velden invoegen
translation-type: tm+mt
source-git-commit: 5c9683c6b00ccbf9e9d606fd4513432c9872ad00
workflow-type: tm+mt
source-wordcount: '231'
ht-degree: 0%

---


# Dynamische velden invoegen {#how-to-insert-dynamic-fields}

U kunt uw e-mailsjablonen aanpassen met vooraf gedefinieerde kenmerken, zoals `{{first_name}}` of `{{company}}`. Met deze velden kunt u meerdere contactpersonen per e-mail verzenden en deze velden automatisch aanvullen zonder dat u ze voor elk contact afzonderlijk hoeft in te voeren.

>[!TIP]
>
>Het veld &quot;first_name&quot; en &quot;bedrijf&quot; zijn het veld `only fields that will look to both Sales Connect and Salesforce.` Dit betekent dat als een contactpersoon niet bestaat in de [webtoepassing](http://toutapp.com/login), we in Salesforce kijken of we een contact-/lograprecord kunnen vinden met een bijbehorend e-mailadres. Vervolgens gebruiken we informatie uit die record om het veld te vullen.

## Een dynamisch veld invoegen in een sjabloon {#insert-a-dynamic-field-into-a-template}

1. Zoek in **Sjablonen en campagnes** de sjabloon die u wilt bewerken en klik op **Sjabloon bewerken**.
1. Klik **Tout Dynamic Fields**.

   >[!NOTE]
   >
   >Bij het e-mailen van contactpersonen in Sales Connect kunt u de standaard dynamische velden gebruiken. Deze zullen zich direct uit het contact trekken.

Als je contacten in Salesforce e-mailt, kun je profiteren van de dynamische velden van Salesforce. Deze beginnen allemaal met &quot;sfdc&quot;. Zolang u een verbinding aan Salesforce hebt, zullen deze gebieden direct aan lood/contact in Salesforce roepen om informatie in het malplaatje te bevolken.

## Dynamische velden invoegen in een onderwerpregel {#insert-dynamic-fields-in-a-subject-line}

Kopieer en plak ze gewoon handmatig in het onderwerpveld van een e-mail, waarbij u ervoor zorgt dat u de juiste opmaak hebt.
