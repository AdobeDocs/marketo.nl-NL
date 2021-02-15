---
unique-page-id: 2360401
description: Vergelijk de doeltreffendheid van het Kanaal met de Analysator van het Programma - Marketo Docs - de Documentatie van het Product
title: Kanaaleffectiviteit vergelijken met de programmaanalyse
translation-type: tm+mt
source-git-commit: 6ae882dddda220f7067babbe5a057eec82601abf
workflow-type: tm+mt
source-wordcount: '415'
ht-degree: 0%

---


# Kanaaldoeltreffendheid vergelijken met de Analysator {#compare-channel-effectiveness-with-the-program-analyzer} van het Programma

Gebruik Analyzer van het Programma om kanaalkosten, lidverwerving, pijpleiding, opbrengst en meer te vergelijken, om uw meest en minst efficiënte kanalen te identificeren.

>[!PREREQUISITES]
>
>* [Een programmaanalyse maken](create-a-program-analyzer.md)


1. Klik op **Analytics** in **My Marketo.**

   ![](assets/image2014-9-17-18-3a36-3a13.png)

1. Selecteer uw **Programmaanalyse.**

   ![](assets/image2014-9-17-18-3a36-3a40.png)

1. Wijzig de weergave in **Door** **Kanaal**.

   ![](assets/image2014-9-17-18-3a36-3a59.png)

1. Gebruik de vervolgkeuzelijst **X-as** om een metrische waarde voor de horizontale as te kiezen. Laten we beginnen met **Programmakosten**.

   ![](assets/image2014-9-17-18-3a37-3a7.png)

1. Gebruik de vervolgkeuzelijst Y-as om een metrische waarde voor de verticale as te kiezen. Hier gaan we met **(FT) Pipeline Created**.

   ![](assets/image2014-9-17-18-3a37-3a50.png)

   >[!NOTE]
   >
   >Veel van de metriek die u kunt kiezen in de programmaanalysator, zijn beschikbaar met first-touch (FT) en multi-touch (MT) berekeningen. Het is belangrijk om het [verschil tussen FT en MT attributie](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/understanding-attribution.md) te begrijpen.

1. Met de vervolgkeuzelijst **Y-as** kunt u **(MT) Pipeline maken** kiezen.

   ![](assets/image2014-9-17-18-3a39-3a5.png)

   In deze multitouch-attributieweergave zien we dat het Webinar-kanaal meer invloed heeft op het ontstaan van pijpleidingen en minder kosten dan de Tradeshow- en Online Advertising-kanalen.

   Laten we nu nog twee dimensies toevoegen!

1. Gebruik de vervolgkeuzelijst **Bubbelgrootte** om een extra maat te selecteren, zoals **Nieuwe namen**.

   ![](assets/image2014-9-17-18-3a39-3a36.png)

1. Kijk hoe de grafiek verandert.

   ![](assets/image2014-9-17-18-3a39-3a55.png)

   We zien dat het Webinar kanaal krimpt, zoals gemeten door **Nieuwe Namen**. We kunnen concluderen dat het, hoewel het veel leden heeft, minder effectief is in het genereren van nieuwe leads dan het Tradeshow-kanaal.

1. Tot slot gebruik drop-down Kleur om de vierde dimensie toe te voegen. Selecteer **(FT) Revenue** **Won**.

   ![](assets/image2014-9-17-18-3a41-3a7.png)

1. Kijk hoe de kleuren in de grafiek veranderen.

   ![](assets/image2014-9-17-18-3a41-3a19.png)

   Uit de kleuren leren we dat het Tradeshow-kanaal, de groenste bubbel, de grootste gewonnen omzet heeft beïnvloed, gemeten door first-touch attributie.

1. Nu, als wij metrisch van de Kleur in **(MT) Won** veranderen, zien wij dat het Online Reclamekanaal, nu het groenste, meer opbrengst - over tijd_ dan de kanalen van Webinar en van de Verkoop beïnvloedde.

   ![](assets/image2014-9-17-18-3a41-3a40.png)

In ons voorbeeld zien we dat het Tradeshow-kanaal zowel het duurste (het verst naar rechts) is als het meest succesvol (het hoogst op de Y-as) bij het meten van pijpleidingen die door eerste aanraking zijn gemaakt. Laten we nu eens kijken naar de pijplijn van elk kanaal die is gemaakt als gemeten door multi-aanraakkenmerk.

>[!TIP]
>
>De voorbeelden in deze stappen meten doeltreffendheid die op gecreeerde pijpleiding wordt gebaseerd. Gebruik de vervolgkeuzelijst Y-as om andere manieren te selecteren om de doeltreffendheid van kanalen te meten, zoals Nieuwe namen, leden, Kosten per succes, enz.

>[!MORELIKETHIS]
>
>* [Programma- en kanaalgegevens verkennen met de Program Analyzer](explore-program-and-channel-details-with-the-program-analyzer.md)
>* [De doeltreffendheid van het Programma met de Analysator van het Programma vergelijken](compare-program-effectiveness-with-the-program-analyzer.md)

>



>[!NOTE]
>
>Meer informatie over geavanceerde analysemogelijkheden vindt u in [Indelingscyclusverkenner](https://docs.marketo.com/display/docs/revenue+cycle+analytics).
