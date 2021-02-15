---
unique-page-id: 2359449
description: Segmentregels definiëren - Marketo Docs - Productdocumentatie
title: Segmentregels definiëren
translation-type: tm+mt
source-git-commit: 6ae882dddda220f7067babbe5a057eec82601abf
workflow-type: tm+mt
source-wordcount: '391'
ht-degree: 0%

---


# Segmentregels {#define-segment-rules} definiëren

Door segmentregels te definiëren kunt u uw personen indelen in verschillende groepen die elkaar uitsluiten.

>[!PREREQUISITES]
>
>[Een segmentatie maken](create-a-segmentation.md)

1. Ga naar **Database.**

   ![](assets/image2017-3-28-14-3a7-3a42.png)

1. Klik op **Segmentation **van de boom, dan klik een bepaald **Segment**.

   ![](assets/image2017-3-28-14-3a11-3a15.png)

1. Klik op **Slimme lijst** en voeg filters toe.

   ![](assets/image2017-3-28-14-3a18-3a19.png)

   >[!CAUTION]
   >
   >Segmenten bieden momenteel geen ondersteuning voor *In verleden* en *In tijdframe *operatoren op filters. Dat komt doordat segmentaties alleen controleren op updates wanneer een waarde van wijzigingsgegevens wordt geregistreerd. Deze waarden worden *niet* geregistreerd voor dingen die automatisch veranderen, zoals formuleringsgebieden en data. Bovendien worden datumoperatoren met een relatief datumbereik niet ondersteund omdat ze worden berekend op het moment van segmenteringsgoedkeuring, niet op het moment van een Change Data Value-activiteit.

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
   >Slimme lijsten zijn geweldig. Leer alles u met [Slimme Lijsten en Statische Lijsten](https://docs.marketo.com/display/docs/smart+lists+and+static+lists) kunt doen.

1. Klik op het **tabblad Personen (Concept)** om de personen weer te geven die mogelijk in aanmerking komen om lid te zijn van dit segment.

   ![](assets/image2017-3-28-14-3a20-3a15.png)

1. Ga naar **Segmentatiehandelingen**. Klik **Goedkeuren**.

   ![](assets/image2014-9-15-11-3a36-3a7.png)

   >[!CAUTION]
   >
   >Het totale aantal segmenten dat u in een segmentatie kunt maken, is afhankelijk van het aantal en het type filters dat wordt gebruikt en ook van de complexiteit van de logica van de segmenten. Hoewel u tot 100 segmenten kunt tot stand brengen gebruikend standaardgebieden, kan het gebruiken van andere types van filters de ingewikkeldheid verhogen, en uw segmentatie zou kunnen niet goedkeuren. Enkele voorbeelden zijn: aangepaste velden, het lid van de lijst, de velden voor de eigenaar van leads en de inkomstenstadia.
   >
   >
   >Als u een foutenmelding tijdens goedkeuring krijgt en hulp bij het verminderen van de ingewikkeldheid van uw segmentatie vereist, gelieve [Marketo Steun](https://nation.marketo.com/t5/Support/ct-p/Support) te contacteren.

1. Bekijk het dashboard voor een snel overzicht van de segmenten in een cirkeldiagram en de toegepaste regels.

   ![](assets/image2014-9-15-11-3a36-3a19.png)

Goed werk! Deze segmenten zullen op veel plaatsen in Marketo in de hand komen.

>[!NOTE]
>
>Een persoon zou voor verschillende segmenten kunnen kwalificeren, maar uiteindelijk tot enkel één behoort die van de [prioritaire orde van segmenten ](segmentation-order-priority.md) afhangt.

>[!NOTE]
>
>**Herinnering**
>
>In het scherm Personen (concept) worden alle personen weergegeven die in aanmerking komen om lid te zijn en dit is niet altijd de uiteindelijke lijst met personen. Goedkeuren van het segment om de definitieve lijst weer te geven.

>[!MORELIKETHIS]
>
>* [Een segmentatie goedkeuren](approve-a-segmentation.md)

>



