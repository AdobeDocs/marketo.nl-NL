---
unique-page-id: 2359449
description: Segmentregels definiëren - Marketo Docs - Productdocumentatie
title: Segmentregels definiëren
exl-id: e6631848-aa8c-4709-b182-4c88abbd365b
feature: Segmentation
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '367'
ht-degree: 0%

---

# Segmentregels definiëren {#define-segment-rules}

Door segmentregels te definiëren kunt u uw personen indelen in verschillende groepen die elkaar uitsluiten.

>[!PREREQUISITES]
>
>[&#x200B; creeer een Segmentatie &#x200B;](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/create-a-segmentation.md)

1. Ga naar de **[!UICONTROL Database]** .

   ![](assets/image2017-3-28-14-3a7-3a42.png)

1. Selecteer **[!UICONTROL Segmentations]** van de boom, dan klik een bepaald **Segment**.

   ![](assets/image2017-3-28-14-3a11-3a15.png)

1. Klik op **[!UICONTROL Smart List]** en voeg filters toe.

   ![](assets/image2017-3-28-14-3a18-3a19.png)

   >[!CAUTION]
   >
   >De segmenten steunen momenteel niet _in Afgelopen_ en _in Timeframe_ exploitanten op filters. Dat komt doordat segmentaties alleen controleren op updates wanneer een waarde van wijzigingsgegevens wordt geregistreerd. Deze waarden worden _niet_ geregistreerd voor dingen die automatisch, zoals formuleringsgebieden en data veranderen. Bovendien worden datumoperatoren met een relatief datumbereik niet ondersteund omdat ze worden berekend op het moment van segmenteringsgoedkeuring, niet op het moment van een Change Data Value-activiteit.

   >[!NOTE]
   >
   >De filters &quot;SFDC Type&quot; en &quot;Microsoft Type&quot; worden momenteel niet ondersteund in slimme segmentatielijsten.

1. Vul de juiste waarden voor de filters.

   ![](assets/image2017-3-28-14-3a18-3a33.png)

   >[!CAUTION]
   >
   >Het gedrag voor het registreren van de activiteit voor de gebieden van de Rekening kan kwalificatie beïnvloeden. Daarom adviseren wij tegen het gebruik van de gebieden van de Rekening wanneer het bepalen van segmentregels.

1. Klik op het tabblad **[!UICONTROL People (Draft)]** om de personen weer te geven die in aanmerking komen om lid te zijn van dit segment.

   ![](assets/image2017-3-28-14-3a20-3a15.png)

1. Ga naar **[!UICONTROL Segmentation Actions]** . Klik op **[!UICONTROL Approve]**.

   ![](assets/image2014-9-15-11-3a36-3a7.png)

   >[!CAUTION]
   >
   >Het totale aantal segmenten dat u in een segmentatie kunt maken, is afhankelijk van het aantal en het type filters dat wordt gebruikt en ook van de complexiteit van de logica van de segmenten. Hoewel u tot 100 segmenten kunt tot stand brengen gebruikend standaardgebieden, kan het gebruiken van andere types van filters de ingewikkeldheid verhogen, en uw segmentatie zou kunnen niet goedkeuren. Voorbeelden hiervan zijn: aangepaste velden, lijdenlijst, velden voor hoofdeigenaars en inkomstenstadia.
   >
   >Als u een foutenmelding tijdens goedkeuring krijgt en hulp in het verminderen van de ingewikkeldheid van uw segmentatie vereist, gelieve te contacteren {de Steun van 0} Marketo [.](https://nation.marketo.com/t5/Support/ct-p/Support)

1. Bekijk het dashboard voor een snel overzicht van de segmenten in een cirkeldiagram en de toegepaste regels.

   ![](assets/image2014-9-15-11-3a36-3a19.png)

Goed werk! Deze segmenten zullen op veel plaatsen in Marketo in de hand komen.

>[!NOTE]
>
>Een persoon zou voor verschillende segmenten kunnen kwalificeren, maar behoort uiteindelijk tot enkel die van de [&#x200B; prioritaire orde van de segmenten &#x200B;](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/segmentation-order-priority.md) afhangt.

>[!NOTE]
>
>In het scherm [!UICONTROL People (Draft)] worden alle personen weergegeven die in aanmerking komen om lid te zijn en dit is niet altijd de uiteindelijke lijst met personen. Goedkeuren van uw segment om de definitieve lijst weer te geven.

>[!MORELIKETHIS]
>
>[&#x200B; keur een Segmentatie &#x200B;](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/approve-a-segmentation.md) goed
