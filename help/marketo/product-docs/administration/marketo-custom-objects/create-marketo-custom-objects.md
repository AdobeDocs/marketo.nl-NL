---
unique-page-id: 10093192
description: Aangepaste Marketo-objecten maken - Marketo Docs - Productdocumentatie
title: Aangepaste Marketo-objecten maken
exl-id: d68b41e1-a12b-436f-aad7-42c7264cd901
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '710'
ht-degree: 0%

---

# Aangepaste Marketo-objecten maken {#create-marketo-custom-objects}

Gebruik aangepaste objecten in Marketo om metrische gegevens bij te houden die specifiek zijn voor uw bedrijf. Dit kan van alles zijn, van auto&#39;s tot cursussen, wat u ook in Marketo wilt modelleren om uw campagnes uit te voeren.

>[!NOTE]
>
>U kunt aangepaste objecten zo instellen dat deze werken op een-op-veel- of een-op-veel-basis. U maakt het oorspronkelijke object op dezelfde manier, maar de stappen verschillen wanneer u velden aan het object toevoegt. Zie [Inzicht in aangepaste Marketo-objecten](/help/marketo/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md) voor meer informatie.

>[!NOTE]
>
>Als het aangepaste object is goedgekeurd, kunt u geen koppelings- of deduplicatieveld maken, bewerken of verwijderen.

## Een aangepast object maken voor een een-op-een-structuur {#create-a-custom-object-for-a-one-to-many-structure}

In dit voorbeeld ziet u een aangepast object Car voor gebruik in een structuur van één op vele. Later maakt u een aangepast cursusobject en een tussenliggend object voor gebruik in een veel-op-veel-structuur.

1. Klik op **Admin** en selecteer **Marketo Custom Objects** in **Databasebeheer**.

   ![](assets/image2016-1-18-13-3a12-3a19.png)

1. Klik **Nieuw aangepast object**.

   ![](assets/image2016-5-18-16-3a28-3a4.png)

   >[!NOTE]
   >
   >Op het tabblad Aangepaste objecten van Marketo worden alle aangepaste objecten aan de rechterkant weergegeven, evenals details voor goedgekeurde objecten, zoals het aantal records en velden bij de meest recente update.

1. Voer een weergavenaam in. De API-naam en de meervoudige naam worden automatisch ingevuld. Voer een beschrijving in (optioneel).

   ![](assets/image2015-9-15-16-3a29-3a17.png)

   >[!NOTE]
   >
   >U kunt deze velden bewerken wanneer u ze maakt, maar nadat u ze hebt opgeslagen, kunt u alleen het veld Plurale naam en de schuifregelaar **Tonen in regelafstandgegevens** bewerken.

1. Trek de **Tonen in Lead Detail** schuif over om **Show** te tonen als u de gegevens van het douanevoorwerp op de pagina van het Gegevensbestand van de Lood wilt bekijken. Klik **Opslaan**.

   ![](assets/image2015-9-15-16-3a32-3a2.png)

1. De informatie over aangepaste objecten geeft de inhoud weer die u hebt ingevoerd. Let op: het staat in het concept.

   ![](assets/image2015-9-15-16-3a38-3a22.png)

   De volgende stap is gebieden aan [bouwt uw douanevoorwerp](/help/marketo/product-docs/administration/marketo-custom-objects/add-marketo-custom-object-fields.md) toe.

   >[!NOTE]
   >
   >U kunt aangepaste objecten van Marketo alleen vullen via een lijstimport of de [API](https://developers.marketo.com/documentation/rest/).

## Een aangepast object maken voor een veel-op-veel-structuur {#create-a-custom-object-for-a-many-to-many-structure}

In dit voorbeeld ziet u een aangepast cursusobject dat u kunt gebruiken voor het maken van een vele-op-veel-relatie tussen personen/bedrijven en cursussen. Wanneer u wordt gedaan, zult u een intermediair voorwerp creëren om het met mensen of bedrijven in uw gegevensbestand te verbinden.

>[!NOTE]
>
>Voor een veel-aan-vele verhouding, te hoeven u om geen verbinding in het douanevoorwerp tot stand te brengen. In plaats daarvan voegt u twee koppelingen toe aan het intermediaire object (zie hieronder).

1. Klik op **Admin** en selecteer **Marketo Custom Objects** in **Databasebeheer**.

   ![](assets/image2016-1-18-13-3a16-3a25.png)

1. Klik **Nieuw aangepast object**.

   ![](assets/image2016-5-18-16-3a32-3a42.png)

1. Voer een weergavenaam in. De API-naam en de meervoudige naam worden automatisch ingevuld. Voer een beschrijving in (optioneel).

   ![](assets/image2016-1-14-13-3a38-3a46.png)

   >[!NOTE]
   >
   >U kunt deze velden bewerken wanneer u ze maakt, maar nadat u ze hebt opgeslagen, kunt u alleen het veld Plurale naam en de schuifregelaar **Tonen in regelafstandgegevens** bewerken.

1. Trek de **Tonen in Lead Detail** schuif over om **Show** te tonen als u de gegevens van het douanevoorwerp op de pagina van het Gegevensbestand van de Lood wilt bekijken. Klik **Opslaan**.

   ![](assets/image2016-1-14-13-3a42-3a56.png)

1. De informatie over aangepaste objecten geeft de inhoud weer die u hebt ingevoerd. Let op: het staat in het concept.

   ![](assets/image2016-1-18-8-3a38-3a58.png)

   >[!NOTE]
   >
   >U kunt aangepaste objecten van Marketo alleen vullen via een lijstimport of de [API](https://developers.marketo.com/documentation/rest/).

De volgende stap is dat u een tussenliggend object maakt (zie hieronder). Maar daarvoor moet u een veld maken om er een koppeling naar te maken.

## Een tussentijds object maken {#create-an-intermediary-object}

Gebruik een tussenliggend object om een aangepast object te koppelen aan personen of bedrijven. In dit voorbeeld, wordt het gebruikt om cursussen in uw cursusdouanevoorwerp met mensen of bedrijven in uw gegevensbestand te verbinden.

>[!NOTE]
>
>U hoeft geen tussenliggend object te maken voor een aangepaste objectstructuur van een-op-veel.

1. Klik **Admin**, en in **Databasebeheer**, selecteer **Aangepaste objecten van Marketo**.

   ![](assets/image2016-1-18-13-3a17-3a40.png)

1. Klik **Nieuw aangepast object**.

   ![](assets/image2016-5-18-16-3a33-3a16.png)

1. Voer een weergavenaam in. De API-naam en de meervoudige naam worden automatisch ingevuld. Voer een beschrijving in (optioneel).

   ![](assets/image2016-1-14-14-3a10-3a44.png)

   >[!NOTE]
   >
   >U kunt deze velden bewerken wanneer u ze maakt, maar nadat u ze hebt opgeslagen, kunt u alleen het veld Muurnaam en de schuifregelaar Tonen in regelafstandgegevens bewerken.

1. Trek de **Tonen in Lead Detail** schuif over om **Show** te tonen als u de gegevens van het douanevoorwerp op de pagina van het Gegevensbestand van de Lood wilt bekijken. Klik **Opslaan**.

   ![](assets/image2016-1-14-14-3a12-3a49.png)

1. De informatie over aangepaste objecten geeft de inhoud weer die u hebt ingevoerd. Let op: het staat in het concept.

   De volgende stap is voor u aan [toevoegt verbindingsgebieden](/help/marketo/product-docs/administration/marketo-custom-objects/add-marketo-custom-object-link-fields.md) om uw intermediair voorwerp met een persoon/bedrijf en een douanevoorwerp te verbinden.

>[!MORELIKETHIS]
>
>* [Aangepaste Marketo-objectvelden toevoegen](/help/marketo/product-docs/administration/marketo-custom-objects/add-marketo-custom-object-fields.md)
>* [Aangepaste Marketo-objectkoppelingsvelden toevoegen](/help/marketo/product-docs/administration/marketo-custom-objects/add-marketo-custom-object-link-fields.md)
>* [Aangepaste Marketo-objecten begrijpen](/help/marketo/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md)

