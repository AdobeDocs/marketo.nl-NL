---
unique-page-id: 14352592
description: Dynamische velden invoegen - Marketo Docs - Productdocumentatie
title: Dynamische velden invoegen
translation-type: tm+mt
source-git-commit: 6ae882dddda220f7067babbe5a057eec82601abf
workflow-type: tm+mt
source-wordcount: '242'
ht-degree: 0%

---


# Dynamische velden invoegen {#how-to-insert-dynamic-fields}

U kunt uw e-mailsjablonen aanpassen met vooraf gedefinieerde kenmerken, zoals `{{first_name}}` of `{{company}}`. Met deze velden kunt u meerdere contactpersonen per e-mail verzenden en deze velden automatisch aanvullen zonder dat u ze voor elk contact afzonderlijk hoeft in te voeren.

>[!TIP]
>
>Het veld &quot;first_name&quot; en &quot;bedrijf&quot; zijn de enige velden die zowel op Sales Connect als op Salesforce worden weergegeven. Dat betekent als een contact niet in [Webtoepassing ](https://toutapp.com/login) bestaat, kijken wij in Salesforce om te zien of kunnen wij een contact/loodverslag met een passend e-mailadres vinden. Vervolgens gebruiken we informatie uit die record om het veld te vullen.

## Een dynamisch veld invoegen in een sjabloon {#insert-a-dynamic-field-into-a-template}

1. Zoek in **Sjablonen en campagnes** de sjabloon die u wilt bewerken en klik op **Sjabloon bewerken**.

1. Klik **Tout Dynamic Fields**.

   >[!NOTE]
   >
   >Bij het e-mailen van contactpersonen in Sales Connect kunt u de standaard dynamische velden gebruiken. Deze zullen zich direct uit het contact trekken.

Als je contacten in Salesforce e-mailt, kun je profiteren van de dynamische velden van Salesforce. Deze beginnen allemaal met &quot;sfdc&quot;. Zolang u een verbinding aan Salesforce hebt, zullen deze gebieden direct aan lood/contact in Salesforce roepen om informatie in het malplaatje te bevolken.

## Dynamische velden invoegen in een onderwerpregel {#insert-dynamic-fields-in-a-subject-line}

Kopieer en plak ze gewoon handmatig in het onderwerpveld van een e-mail, waarbij u ervoor zorgt dat u de juiste opmaak hebt.
