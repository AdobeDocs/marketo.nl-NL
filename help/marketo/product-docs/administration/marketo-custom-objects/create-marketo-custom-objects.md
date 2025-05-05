---
unique-page-id: 10093192
description: Aangepaste Marketo-objecten maken - Marketo Docs - Productdocumentatie
title: Aangepaste Marketo-objecten maken
exl-id: d68b41e1-a12b-436f-aad7-42c7264cd901
feature: Custom Objects
source-git-commit: 2b610cc3486b745212b0b1f36018a83214d7ecd7
workflow-type: tm+mt
source-wordcount: '619'
ht-degree: 1%

---

# Aangepaste Marketo-objecten maken {#create-marketo-custom-objects}

Gebruik aangepaste objecten in Marketo om metrische gegevens bij te houden die specifiek zijn voor uw bedrijf. Dit kan van alles zijn, van auto&#39;s tot cursussen, wat u ook in Marketo wilt modelleren om uw campagnes uit te voeren.

>[!NOTE]
>
>U kunt aangepaste objecten zo instellen dat deze werken op een-op-veel- of een-op-veel-basis. U maakt het oorspronkelijke object op dezelfde manier, maar de stappen verschillen wanneer u velden aan het object toevoegt. Zie  [Aangepaste Marketo-objecten](/help/marketo/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md) voor meer informatie .

>[!NOTE]
>
>Als het aangepaste object is goedgekeurd, kunt u geen koppelings- of deduplicatieveld maken, bewerken of verwijderen.

## Een aangepast object maken voor een een-op-een-structuur {#create-a-custom-object-for-a-one-to-many-structure}

In dit voorbeeld ziet u een aangepast object Car voor gebruik in een structuur van één op vele. Later maakt u een aangepast cursusobject en een tussenliggend object voor gebruik in een veel-op-veel-structuur.

1. Ga naar de **[!UICONTROL Admin]** gebied.

   ![](assets/create-marketo-custom-objects-1.png)

1. Klik op **[!UICONTROL Marketo Custom Objects]**.

   ![](assets/create-marketo-custom-objects-2.png)

1. Klik op **[!UICONTROL New Custom Object]**.

   ![](assets/create-marketo-custom-objects-3.png)

   >[!NOTE]
   >
   >De [!UICONTROL Marketo Custom Objects] worden alle aangepaste objecten aan de rechterkant weergegeven en worden details voor alle goedgekeurde objecten weergegeven, inclusief het aantal records en velden bij de meest recente update.

1. Voer een [!UICONTROL Display Name]. De [!UICONTROL API Name] en [!UICONTROL Plural Name] automatisch vullen. Voer een [!UICONTROL Description] (optioneel).

   ![](assets/create-marketo-custom-objects-4.png)

   >[!NOTE]
   >
   >U kunt deze velden bewerken wanneer u ze maakt, maar nadat ze zijn opgeslagen, kunt u alleen de [!UICONTROL Plural Name] en de **[!UICONTROL Show in Lead Detail]** schuifregelaar

1. Trek de **[!UICONTROL Show in Lead Detail]** schuifregelaar voor weergave **[!UICONTROL Show]** als u de gegevens van douaneobjecten op de pagina van het Gegevensbestand wilt bekijken. Klik op **[!UICONTROL Save]**.

   ![](assets/create-marketo-custom-objects-5.png)

1. De informatie over aangepaste objecten geeft de inhoud weer die u hebt ingevoerd. Let op: het staat in het concept.

   ![](assets/create-marketo-custom-objects-6.png)

   De volgende stap bestaat uit het toevoegen van velden aan [een aangepast object maken](/help/marketo/product-docs/administration/marketo-custom-objects/add-marketo-custom-object-fields.md).

   >[!NOTE]
   >
   >U kunt aangepaste Marketo-objecten alleen vullen met een lijstimport of de opdracht [API](https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/rest/rest-api).

## Een aangepast object maken voor een veel-op-veel-structuur {#create-a-custom-object-for-a-many-to-many-structure}

In dit voorbeeld ziet u een aangepast cursusobject dat u kunt gebruiken voor het maken van een vele-op-veel-relatie tussen personen/bedrijven en cursussen. Wanneer u wordt gedaan, zult u een intermediair voorwerp creëren om het met mensen of bedrijven in uw gegevensbestand te verbinden.

>[!NOTE]
>
>Voor een veel-aan-vele verhouding, te hoeven u om geen verbinding in het douanevoorwerp tot stand te brengen. In plaats daarvan voegt u twee koppelingen toe aan het intermediaire object (zie hieronder).

1. Ga naar de **[!UICONTROL Admin]** gebied.

   ![](assets/create-marketo-custom-objects-7.png)

1. Klik op **[!UICONTROL Marketo Custom Objects]**.

   ![](assets/create-marketo-custom-objects-8.png)

1. Klik op **[!UICONTROL New Custom Object]**.

   ![](assets/create-marketo-custom-objects-9.png)

1. Voer een [!UICONTROL Display Name]. De [!UICONTROL API Name] en [!UICONTROL Plural Name] automatisch vullen. Voer een [!UICONTROL Description] (optioneel).

   ![](assets/create-marketo-custom-objects-10.png)

   >[!NOTE]
   >
   >U kunt deze velden bewerken wanneer u ze maakt, maar nadat ze zijn opgeslagen, kunt u alleen de [!UICONTROL Plural Name] en de **[!UICONTROL Show in Lead Detail]** schuifregelaar

1. Trek de **[!UICONTROL Show in Lead Detail]** schuifregelaar voor weergave **[!UICONTROL Show]** als u de gegevens van douaneobjecten op de pagina van het Gegevensbestand wilt bekijken. Klik op **[!UICONTROL Save]**.

   ![](assets/create-marketo-custom-objects-11.png)

1. De informatie over aangepaste objecten geeft de inhoud weer die u hebt ingevoerd. Let op: het staat in het concept.

   ![](assets/create-marketo-custom-objects-12.png)

   >[!NOTE]
   >
   >U kunt aangepaste Marketo-objecten alleen vullen met een lijstimport of de opdracht [API](https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/rest/rest-api).

De volgende stap is dat u een tussenliggend object maakt (zie hieronder). Maar daarvoor moet u een veld maken om er een koppeling naar te maken.

## Een tussenliggend object maken {#create-an-intermediary-object}

Gebruik een tussenliggend object om een aangepast object te koppelen aan personen of bedrijven. In dit voorbeeld, wordt het gebruikt om cursussen in uw cursusdouanevoorwerp met mensen of bedrijven in uw gegevensbestand te verbinden.

>[!NOTE]
>
>U hoeft geen intermediair object te maken voor een een-op-veel aangepaste objectstructuur.

1. Ga naar de **[!UICONTROL Admin]** gebied.

   ![](assets/create-marketo-custom-objects-13.png)

1. Klik op **[!UICONTROL Marketo Custom Objects]**.

   ![](assets/create-marketo-custom-objects-14.png)

1. Klik op **[!UICONTROL New Custom Object]**.

   ![](assets/create-marketo-custom-objects-15.png)

1. Voer een [!UICONTROL Display Name]. De [!UICONTROL API Name] en [!UICONTROL Plural Name] automatisch vullen. Voer een [!UICONTROL Description] (optioneel).

   ![](assets/create-marketo-custom-objects-16.png)

   >[!NOTE]
   >
   >U kunt deze velden bewerken wanneer u ze maakt, maar nadat ze zijn opgeslagen, kunt u alleen de [!UICONTROL Plural Name] en de [!UICONTROL Show in Lead Detail] schuifregelaar

1. Trek de **[!UICONTROL Show in Lead Detail]** schuifregelaar voor weergave **Tonen** als u de gegevens van douaneobjecten op de pagina van het Gegevensbestand wilt bekijken. Klikken **Opslaan**.

   ![](assets/create-marketo-custom-objects-17.png)

1. De informatie over aangepaste objecten geeft de inhoud weer die u hebt ingevoerd. Let op: het staat in het concept.

   De volgende stap is dat u [koppelingsvelden toevoegen](/help/marketo/product-docs/administration/marketo-custom-objects/add-marketo-custom-object-link-fields.md) om het tussenliggende object te koppelen aan een persoon/bedrijf en een aangepast object.

>[!MORELIKETHIS]
>
>* [Aangepaste Marketo-objectvelden toevoegen](/help/marketo/product-docs/administration/marketo-custom-objects/add-marketo-custom-object-fields.md)
>* [Aangepaste Marketo-objectkoppelingsvelden toevoegen](/help/marketo/product-docs/administration/marketo-custom-objects/add-marketo-custom-object-link-fields.md)
>* [Aangepaste Marketo-objecten](/help/marketo/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md)
