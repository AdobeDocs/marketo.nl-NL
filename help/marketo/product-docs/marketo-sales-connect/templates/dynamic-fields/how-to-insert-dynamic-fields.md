---
unique-page-id: 14352592
description: Dynamische velden invoegen - Marketo Docs - Productdocumentatie
title: Dynamische velden invoegen
exl-id: e4989350-872d-47a1-84b0-210e631ae23a
feature: Marketo Sales Connect
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '222'
ht-degree: 0%

---

# Dynamische velden invoegen {#how-to-insert-dynamic-fields}

U kunt uw e-mailsjablonen aanpassen met vooraf gedefinieerde kenmerken, zoals `{{first_name}}` of `{{company}}` . Met deze velden kunt u meerdere contactpersonen per e-mail verzenden en deze velden automatisch aanvullen zonder dat u ze voor elk contact afzonderlijk hoeft in te voeren.

>[!TIP]
>
>Het veld &quot;first_name&quot; en &quot;bedrijf&quot; zijn de enige velden die zowel naar [!DNL Sales Connect] als naar [!DNL Salesforce] kijken. Dat betekent als een contact niet in de [&#x200B; Webtoepassing &#x200B;](https://toutapp.com/login) bestaat, kijken wij binnen [!DNL Salesforce] om te zien of kunnen wij een contact/loodverslag met een passend e-mailadres vinden. Vervolgens gebruiken we informatie uit die record om het veld te vullen.

## Een dynamisch veld invoegen in een sjabloon {#insert-a-dynamic-field-into-a-template}

1. Zoek in **[!UICONTROL Templates & Campaigns]** de sjabloon die u wilt bewerken en klik op **[!UICONTROL Edit Template]** .

1. Klik op **[!UICONTROL Tout Dynamic Fields]**.

   >[!NOTE]
   >
   >Bij het e-mailen van contactpersonen in [!DNL Sales Connect] kunt u de standaard dynamische velden gebruiken. Deze zullen zich direct uit het contact trekken.

Als u contactpersonen per e-mail verzendt die in [!DNL Salesforce] voorkomen, kunt u gebruikmaken van de dynamische velden van [!DNL Salesforce] . Deze beginnen allemaal met &quot;sfdc&quot;. Zolang u verbinding hebt met [!DNL Salesforce] , worden deze velden rechtstreeks aangeroepen bij de lead/contactpersoon in [!DNL Salesforce] om informatie in de sjabloon te vullen.

## Dynamische velden invoegen in een onderwerpregel {#insert-dynamic-fields-in-a-subject-line}

Kopieer en plak ze gewoon handmatig in het onderwerpveld van een e-mail, waarbij u ervoor zorgt dat u de juiste opmaak hebt.
