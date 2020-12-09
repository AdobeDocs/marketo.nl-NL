---
unique-page-id: 10093192
description: Aangepaste objecten Marketo maken - Marketo Docs - Productdocumentatie
title: Aangepaste objecten markeren
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '710'
ht-degree: 0%

---


# Aangepaste objecten markeren {#create-marketo-custom-objects}

Gebruik aangepaste objecten in Marketo om metrische gegevens bij te houden die specifiek zijn voor uw bedrijf. Dit kan van alles zijn, van auto&#39;s tot cursussen, wat u ook maar wilt modelleren in Marketo om uw campagnes uit te voeren.

>[!NOTE]
>
>U kunt aangepaste objecten zo instellen dat deze werken op een-op-veel- of een-op-veel-basis. U maakt het oorspronkelijke object op dezelfde manier, maar de stappen verschillen wanneer u velden aan het object toevoegt. Zie [Inzicht in aangepaste objecten](understanding-marketo-custom-objects.md) markeren voor meer informatie.

>[!NOTE]
>
>Als het aangepaste object is goedgekeurd, kunt u geen koppelings- of deduplicatieveld maken, bewerken of verwijderen.

## Een aangepast object maken voor een een-op-een-structuur {#create-a-custom-object-for-a-one-to-many-structure}

In dit voorbeeld ziet u een aangepast object Car voor gebruik in een structuur van één op vele. Later maakt u een aangepast cursusobject en een tussenliggend object voor gebruik in een veel-op-veel-structuur.

1. Klik op **Beheer** en selecteer in **Databasebeheer** de optie **Marketo Custom Objects**.

   ** ![](assets/image2016-1-18-13-3a12-3a19.png)

   **

1. Klik op **Nieuw aangepast object**.

   ![](assets/image2016-5-18-16-3a28-3a4.png)

   >[!NOTE]
   >
   >Op het tabblad Aangepaste objecten markeren worden alle aangepaste objecten aan de rechterkant weergegeven, evenals details voor goedgekeurde objecten, zoals het aantal records en velden bij de meest recente update.

1. Voer een weergavenaam in. De API-naam en de meervoudige naam worden automatisch ingevuld. Voer een beschrijving in (optioneel).

   ![](assets/image2015-9-15-16-3a29-3a17.png)

   >[!NOTE]
   >
   >U kunt deze velden bewerken wanneer u ze maakt, maar nadat u ze hebt opgeslagen, kunt u alleen het veld Muurnaam en de schuifregelaar **Tonen in Details** lead bewerken.

1. Trek de **Show in het Detail **schuif van de Leiding over om **Show** te tonen als u de gegevens van douaneobjecten op de pagina van het Gegevensbestand van de Lood wilt bekijken. Klik op **Opslaan**.

   ![](assets/image2015-9-15-16-3a32-3a2.png)

1. De informatie over aangepaste objecten geeft de inhoud weer die u hebt ingevoerd. Let op: het staat in het concept.

   ![](assets/image2015-9-15-16-3a38-3a22.png)

   In de volgende stap voegt u velden toe om uw aangepaste object [](add-marketo-custom-object-fields.md)samen te stellen.

   >[!NOTE]
   >
   >U kunt Marketo-aangepaste objecten alleen vullen met een lijstimport of de [API](http://developers.marketo.com/documentation/rest/).

## Een aangepast object maken voor een veel-op-veel-structuur {#create-a-custom-object-for-a-many-to-many-structure}

In dit voorbeeld ziet u een aangepast cursusobject dat u kunt gebruiken voor het maken van een vele-op-veel-relatie tussen personen/bedrijven en cursussen. Wanneer u wordt gedaan, zult u een intermediair voorwerp creëren om het met mensen of bedrijven in uw gegevensbestand te verbinden.

>[!NOTE]
>
>Voor een veel-aan-vele verhouding, te hoeven u om geen verbinding in het douanevoorwerp tot stand te brengen. In plaats daarvan voegt u twee koppelingen toe aan het intermediaire object (zie hieronder).

1. Klik op **Beheer** en selecteer in **Databasebeheer** de optie **Marketo Custom Objects**.

   ![](assets/image2016-1-18-13-3a16-3a25.png)

1. Klik op **Nieuw aangepast object**.

   ![](assets/image2016-5-18-16-3a32-3a42.png)

1. Voer een weergavenaam in. De API-naam en de meervoudige naam worden automatisch ingevuld. Voer een beschrijving in (optioneel).

   ![](assets/image2016-1-14-13-3a38-3a46.png)

   >[!NOTE]
   >
   >U kunt deze velden bewerken wanneer u ze maakt, maar nadat u ze hebt opgeslagen, kunt u alleen het veld Muurnaam en de schuifregelaar **Tonen in Details** lead bewerken.

1. Trek de schuifregelaar **Tonen in regelafstandgegevens **tonen over om Tonen weer te geven als u aangepaste objectgegevens wilt weergeven op de pagina Database van lead. Klik op **Opslaan**.

   ![](assets/image2016-1-14-13-3a42-3a56.png)

1. De informatie over aangepaste objecten geeft de inhoud weer die u hebt ingevoerd. Let op: het staat in het concept.

   ![](assets/image2016-1-18-8-3a38-3a58.png)

   >[!NOTE]
   >
   >U kunt Marketo-aangepaste objecten alleen vullen met een lijstimport of de [API](http://developers.marketo.com/documentation/rest/).

De volgende stap is dat u een tussenliggend object maakt (zie hieronder). Maar daarvoor moet u een veld maken om er een koppeling naar te maken.

## Een tussentijds object maken {#create-an-intermediary-object}

Gebruik een tussenliggend object om een aangepast object te koppelen aan personen of bedrijven. In dit voorbeeld, wordt het gebruikt om cursussen in uw cursusdouanevoorwerp met mensen of bedrijven in uw gegevensbestand te verbinden.

>[!NOTE]
>
>U hoeft geen tussenliggend object te maken voor een aangepaste objectstructuur van een-op-veel.

1. Klik **Admin**, en in het Beheer **van het** Gegevensbestand, selecteer **Marketo Douane Voorwerpen**.

   ![](assets/image2016-1-18-13-3a17-3a40.png)

1. Klik op **Nieuw aangepast object**.

   ![](assets/image2016-5-18-16-3a33-3a16.png)

1. Voer een weergavenaam in. De API-naam en de meervoudige naam worden automatisch ingevuld. Voer een beschrijving in (optioneel).

   ![](assets/image2016-1-14-14-3a10-3a44.png)

   >[!NOTE]
   >
   >U kunt deze velden bewerken wanneer u ze maakt, maar nadat u ze hebt opgeslagen, kunt u alleen het veld Muurnaam en de schuifregelaar Tonen in regelafstandgegevens bewerken.

1. Trek de schuifregelaar **Tonen in regelafstandgegevens** over om Tonen weer te geven als u aangepaste objectgegevens wilt weergeven op de pagina Database lead. Klik op **Opslaan**.

   ![](assets/image2016-1-14-14-3a12-3a49.png)

1. De informatie over aangepaste objecten geeft de inhoud weer die u hebt ingevoerd. Let op: het staat in het concept.

   De volgende stap is dat u koppelingsgebieden [](add-marketo-custom-object-link-fields.md) toevoegt om uw intermediair voorwerp met een persoon/bedrijf en een douanevoorwerp te verbinden.

>[!MORELIKETHIS]
>
>* [Markeren toevoegen aan aangepaste objectvelden](add-marketo-custom-object-fields.md)
>* [Markeren toevoegen aan aangepaste objectkoppelingsvelden](add-marketo-custom-object-link-fields.md)
>* [Aangepaste objecten markeren](understanding-marketo-custom-objects.md)

>



