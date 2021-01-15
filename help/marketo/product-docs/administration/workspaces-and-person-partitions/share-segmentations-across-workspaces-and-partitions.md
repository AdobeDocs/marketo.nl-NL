---
unique-page-id: 7515767
description: Segmenten delen op werkruimten en partities - Marketo Docs - Productdocumentatie
title: Segmenten delen over werkruimten en partities
translation-type: tm+mt
source-git-commit: f79909ce8f2e37bf0748596774fe47ac03618696
workflow-type: tm+mt
source-wordcount: '469'
ht-degree: 0%

---


# Segmenten delen over werkruimten en partities {#share-segmentations-across-workspaces-and-partitions}

>[!PREREQUISITES]
>
>Dit artikel is alleen bedoeld voor klanten met werkruimten en partities.

## Wat is een segmentatie? {#whats-a-segmentation}

Marketo is geweldig in het uitkiezen van de juiste mensen voor een programma of slimme campagne. Voor meer permanente personen moet u echter segmentaties gebruiken. Ze zijn nodig om geavanceerde dynamische inhoud in Marketo te gebruiken.

>[!NOTE]
>
>Leer [segmentaties maken](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/create-a-segmentation.md).

Zodra u deze persona opstelling (_en_ hebt u werkruimten gebruikt), zult u hen over uw werkruimten willen delen. Hier zijn een paar goede dingen om te weten:

## Regels en tips {#rules-tips}

* Elk Marketo-abonnement kan maximaal 20 segmenten &quot;totaal&quot; bevatten in meerdere werkruimten (**niet 20 per werkruimte**).
* U kunt een Segmentatie met werkruimten slechts delen die u toegang tot hebt.
* Zorg ervoor om een **Standaardwerkruimte te creëren en te gebruiken die zicht in alle verdelingen** heeft.

* De verwerking van de segmentatie loopt slechts op de mensen in de werkruimte waar de Segmentatie wordt gecreeerd.

   * Maak de segmentatie die u wilt delen in de standaardwerkruimte.
      * De segmentatie goedkeuren
      * De gedeelde werkruimte ziet een vergrendelde map en de segmentatie is alleen-lezen.
      * De gedeelde versie kan niet worden bewerkt. U kunt de oorspronkelijke segmentatie alleen bewerken op de plaats waar deze is gemaakt.
   * Wanneer u op een Segment (b.v. Gezondheidszorg) binnen een gedeelde Segmentatie klikt, zullen de mensen u ziet slechts mensen in de verdeling verbonden aan de werkruimte zijn u bekijkt.
      * Als u een Segmentatie in Werkruimte 1 (WS1) creeert en het met WS2 deelt en WS1 heeft geen toegang tot de verdeling voor WS2, ZAL het NIET de Segmentatie opnieuw berekenen.
      * Als u een Segmentatie in een werkruimte creeert die verdelingen heeft, en het dan met een andere werkruimte deelt, zal die werkruimte die de gedeelde Segmentatie ontving slechts mensen zien als zij overlappen hebben.


>[!NOTE]
>
>Sommige van deze regels zijn een beetje complex. De eenvoudigste manier om aan de slag te gaan is met specifieke mensen te testen. Je kunt altijd nieuwe segmentaties maken en oude weghalen.

## Voorbeeldscenario&#39;s {#example-scenarios}

![](assets/image2015-5-27-16-3a26-3a25.png)

![](assets/image2015-5-27-16-3a26-3a48.png)

## Een segmentatie delen {#share-a-segmentation}

1. Ga naar **Database**.

   ![](assets/image2017-3-29-8-3a15-3a40.png)

1. Klik met de rechtermuisknop **Segmentaties** en selecteer **Nieuwe mappen**.

   ![](assets/image2017-3-29-8-3a40-3a31.png)

1. Geef een naam op voor de map die u wilt delen in de verschillende werkruimten (bijvoorbeeld: Segmentaties delen).

   ![](assets/image2017-3-29-8-3a40-3a45.png)

1. Verplaats de segmentatie(s) die u wilt delen naar de map.

   ![](assets/image2017-3-29-8-3a41-3a3.png)

1. Klik met de rechtermuisknop op de map en selecteer **Map delen**.

   ![](assets/image2017-3-29-8-3a41-3a19.png)

1. Selecteer de werkruimte(n) waarmee u de map wilt delen. Klik **Opslaan**.

   ![](assets/image2015-5-27-11-3a6-3a40.png)

   >[!NOTE]
   >
   >In het dialoogvenster worden de werkruimten weergegeven die u kunt weergeven. Marketo raadt u daarom aan om Segmentaties te maken en te delen vanuit de werkruimte Standaard die zichtbaar is in alle werkruimten en partities.

De voortkomende omslag toont in de boom van het Gegevensbestand met een pijl erop wijst die dat het met andere werkruimten wordt gedeeld. Vanuit de gedeelde werkruimte wordt in de map een vergrendeling weergegeven om aan te geven dat de inhoud van de map is gedeeld vanuit een andere werkruimte en alleen-lezen is.
