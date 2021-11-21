---
unique-page-id: 2359449
description: Segmentregels definiëren - Marketo Docs - Productdocumentatie
title: Segmentregels definiëren
exl-id: e6631848-aa8c-4709-b182-4c88abbd365b
source-git-commit: 4699b17a670655820946cd277adf28f2233f04d3
workflow-type: tm+mt
source-wordcount: '379'
ht-degree: 0%

---

# Segmentregels definiëren {#define-segment-rules}

Door segmentregels te definiëren kunt u uw personen indelen in verschillende groepen die elkaar uitsluiten.

>[!PREREQUISITES]
>
>[Een segmentatie maken](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/create-a-segmentation.md)

1. Ga naar de **Database.**

   ![](assets/image2017-3-28-14-3a7-3a42.png)

1. Selecteren **Segmentering** van de boom, dan klik een bepaald **Segment**.

   ![](assets/image2017-3-28-14-3a11-3a15.png)

1. Klikken **Slimme lijst** en voegt filters toe.

   ![](assets/image2017-3-28-14-3a18-3a19.png)

   >[!CAUTION]
   >
   >Segmenten worden momenteel niet ondersteund _In het verleden_ en _In tijdframe_  operatoren op filters. Dat komt doordat segmentaties alleen controleren op updates wanneer een waarde van wijzigingsgegevens wordt geregistreerd. Deze waarden zijn _niet_ geregistreerd voor dingen die automatisch veranderen, zoals formules gebieden en data. Bovendien worden datumoperatoren met een relatief datumbereik niet ondersteund omdat ze worden berekend op het moment van segmenteringsgoedkeuring, niet op het moment van een Change Data Value-activiteit.

   >[!NOTE]
   >
   >De filters &quot;SFDC Type&quot; en &quot;Microsoft Type&quot; worden momenteel niet ondersteund in slimme segmentatielijsten.

1. Vul de juiste waarden voor de filters.

   ![](assets/image2017-3-28-14-3a18-3a33.png)

   >[!CAUTION]
   >
   >Wij adviseren _tegen_ het gebruik van de gebieden van de Rekening wanneer het bepalen van segmentregels, aangezien het activiteitenregistreren kwesties kan veroorzaken.

1. Klik op de knop **Personen (concept)** tabblad om de personen weer te geven die in aanmerking komen om lid te zijn van dit segment.

   ![](assets/image2017-3-28-14-3a20-3a15.png)

1. Ga naar **Segmentatiehandelingen**. Klikken **Goedkeuren**.

   ![](assets/image2014-9-15-11-3a36-3a7.png)

   >[!CAUTION]
   >
   >Het totale aantal segmenten dat u in een segmentatie kunt maken, is afhankelijk van het aantal en het type filters dat wordt gebruikt en ook van de complexiteit van de logica van de segmenten. Hoewel u tot 100 segmenten kunt tot stand brengen gebruikend standaardgebieden, kan het gebruiken van andere types van filters de ingewikkeldheid verhogen, en uw segmentatie zou kunnen niet goedkeuren. Enkele voorbeelden zijn: aangepaste velden, het lid van de lijst, de velden voor de eigenaar van leads en de inkomstenstadia.
   >
   >Als u een foutbericht krijgt tijdens de goedkeuring en hulp nodig hebt bij het verminderen van de complexiteit van de segmentatie, kunt u contact opnemen met [Marketo-ondersteuning](https://nation.marketo.com/t5/Support/ct-p/Support).

1. Bekijk het dashboard voor een snel overzicht van de segmenten in een cirkeldiagram en de toegepaste regels.

   ![](assets/image2014-9-15-11-3a36-3a19.png)

Goed werk! Deze segmenten zullen op veel plaatsen in Marketo in de hand komen.

>[!NOTE]
>
>Een persoon kan in aanmerking komen voor verschillende segmenten, maar behoort uiteindelijk tot één segment dat afhankelijk is van de [prioriteitsvolgorde van de segmenten](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/segmentation-order-priority.md).

>[!NOTE]
>
>In het scherm Personen (concept) worden alle personen weergegeven die in aanmerking komen om lid te zijn en dit is niet altijd de uiteindelijke lijst met personen. Goedkeuren van uw segment om de definitieve lijst weer te geven.

>[!MORELIKETHIS]
>
>[Een segmentatie goedkeuren](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/approve-a-segmentation.md)
