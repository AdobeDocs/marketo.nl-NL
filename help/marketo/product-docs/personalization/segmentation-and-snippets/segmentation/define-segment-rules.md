---
unique-page-id: 2359449
description: Segmentregels definiëren - Marketo Docs - Productdocumentatie
title: Segmentregels definiëren
translation-type: tm+mt
source-git-commit: d7d6aee63144c472e02fe0221c4a164183d04dd4
workflow-type: tm+mt
source-wordcount: '393'
ht-degree: 0%

---


# Segmentregels definiëren {#define-segment-rules}

Door segmentregels te definiëren kunt u uw personen indelen in verschillende groepen die elkaar uitsluiten.

>[!PREREQUISITES]
>
>[Een segmentatie maken](create-a-segmentation.md)

1. Ga naar de **database.**

   ![](assets/image2017-3-28-14-3a7-3a42.png)

1. Klik op **Segmentatie **van de boom, dan klik een bepaald **Segment**.

   ![](assets/image2017-3-28-14-3a11-3a15.png)

1. Klik op **Slimme lijst** en voeg filters toe.

   ![](assets/image2017-3-28-14-3a18-3a19.png)

   >[!CAUTION]
   >
   >Segmenten bieden momenteel geen ondersteuning voor *de operatoren In verleden* en *In tijdframe *op filters. Dat komt doordat segmentaties alleen controleren op updates wanneer een waarde van wijzigingsgegevens wordt geregistreerd. Deze waarden worden *niet* geregistreerd voor dingen die automatisch veranderen, zoals formuleringsgebieden en data. Bovendien worden datumoperatoren met een relatief datumbereik niet ondersteund omdat ze worden berekend op het moment van segmenteringsgoedkeuring, niet op het moment van een Change Data Value-activiteit.

   >[!NOTE]
   >
   >De filters &quot;SFDC Type&quot; en &quot;Microsoft Type&quot; worden momenteel niet ondersteund in slimme segmentatielijsten.

1. Vul de juiste waarden voor de filters.

   ![](assets/image2017-3-28-14-3a18-3a33.png)

   >[!NOTE]
   >
   >**Diep duiken**
   >
   >
   >Slimme lijsten zijn geweldig. Leer alles wat u kunt doen met [slimme lijsten en statische lijsten](http://docs.marketo.com/display/docs/smart+lists+and+static+lists).

1. Klik op het tabblad **Personen (concept)** om de personen weer te geven die mogelijk in aanmerking komen om lid te zijn van dit segment.

   ![](assets/image2017-3-28-14-3a20-3a15.png)

1. Ga naar **Segmentatiehandelingen**. Klik op **Goedkeuren**.

   ![](assets/image2014-9-15-11-3a36-3a7.png)

   >[!CAUTION]
   >
   >Het totale aantal segmenten dat u in een segmentatie kunt maken, is afhankelijk van het aantal en het type filters dat wordt gebruikt en ook van de complexiteit van de logica van de segmenten. Hoewel u tot 100 segmenten kunt tot stand brengen gebruikend standaardgebieden, kan het gebruiken van andere types van filters de ingewikkeldheid verhogen, en uw segmentatie zou kunnen niet goedkeuren. Enkele voorbeelden zijn: aangepaste velden, het lid van de lijst, de velden voor de eigenaar van leads en de inkomstenstadia.
   >
   >
   >Neem contact op met [Marketo Support](http://nation.marketo.com/t5/Support/ct-p/Support)als u tijdens de goedkeuring een foutbericht krijgt en hulp nodig hebt bij het verminderen van de complexiteit van de segmentatie.

1. Bekijk het dashboard voor een snel overzicht van de segmenten in een cirkeldiagram en de toegepaste regels.

   ![](assets/image2014-9-15-11-3a36-3a19.png)

Goed werk! Deze segmenten zullen op veel plaatsen in Marketo in de hand komen.

>[!NOTE]
>
>Een persoon kan voor verschillende segmenten in aanmerking komen, maar behoort uiteindelijk tot slechts één die van de [prioritaire orde van de segmenten](segmentation-order-priority.md)afhangt.

>[!NOTE]
>
>**Herinnering**
>
>In het scherm Personen (concept) worden alle personen weergegeven die in aanmerking komen om lid te zijn en dit is niet altijd de uiteindelijke lijst met personen. Goedkeuren van het segment om de definitieve lijst weer te geven.

>[!NOTE]
>
>**Verwante artikelen**
>
>* [Een segmentatie goedkeuren](approve-a-segmentation.md)

>



