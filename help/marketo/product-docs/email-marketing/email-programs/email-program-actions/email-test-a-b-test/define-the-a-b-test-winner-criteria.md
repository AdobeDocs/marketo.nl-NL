---
unique-page-id: 2359545
description: Bepaal de Criteria van de Winner van de Test A/B - Marketo Docs - de Documentatie van het Product
title: Bepaal de Criteria van de Winner van de Test A/B
translation-type: tm+mt
source-git-commit: 8d45a28e1c2adad3e04645f7150f1757414092f0
workflow-type: tm+mt
source-wordcount: '401'
ht-degree: 0%

---


# Bepaal de Criteria van de Winner van de Test A/B {#define-the-a-b-test-winner-criteria}

Wanneer [een A/B test](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/email-test-a-b-test/add-an-a-b-test.md) aan uw e-mailprogramma toevoegt, zult u een testtype moeten kiezen, [plant de A/B test](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/email-test-a-b-test/schedule-the-a-b-test.md), dan bepaalt de winnende criteria. Hier is hoe je bepaalt welke e-mail wint.

>[!PREREQUISITES]
>
>[Een A/B-test toevoegen](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/email-test-a-b-test/add-an-a-b-test.md)

## Criteria van winnende bieder {#winner-criteria}

1. De standaardopties **Winnercriteria** worden als eerste vermeld.

   ![](assets/image2014-9-12-15-3a51-3a3.png)

   | **Openen** | Een open register wanneer afbeeldingen naar een e-mail worden gedownload. Zelfs als u geen afbeelding opneemt, voegt standaard Marketo één pixel achter elkaar in alle HTML-e-mails in. |
   |---|---|
   | **Klikken** | Standaard zijn koppelingen in e-mailberichten ingesloten, zodat u kunt zien wie op de koppeling heeft geklikt, hoeveel koppelingen er zijn geklikt, enzovoort. |
   | **Klikken om % te openen** | Percentage e-mailberichten dat is geopend en waarop een koppeling is geklikt in het e-mailbericht. Dit meet de relevantie en de context van een e-mail door het aantal unieke kliks te nemen gedeeld door het aantal unieke opent, en dan het vermenigvuldigen met 100 om het als percentage te tonen. |
   | **Engagement Score** | Met de [betrokkenheidsscore](/help/marketo/product-docs/email-marketing/drip-nurturing/reports-and-notifications/understanding-the-engagement-score.md) kunt u de effectiviteit van uw inhoud bepalen. |

   >[!TIP]
   >
   >Als u Betrokkenheidsscore kiest, moet de test minstens 24 uur worden uitgevoerd. Meer informatie over [de betrokkenheidsscore](/help/marketo/product-docs/email-marketing/drip-nurturing/reports-and-notifications/understanding-the-engagement-score.md).

1. U kunt uw criteria ook aanpassen door Aangepaste omzetting te selecteren en op Bewerken te klikken.

   ![](assets/image2014-9-12-15-3a51-3a53.png)

   >[!NOTE]
   >
   >Met Aangepaste omzetting kunt u elke gebeurtenis als een conversie kiezen met behulp van triggers en filters.

1. Er wordt een venster geopend. Zoek de trigger van uw keuze en sleep deze naar het canvas.

   ![](assets/image2014-9-12-15-3a52-3a18.png)

1. Definieer de trigger.

   ![](assets/image2014-9-12-15-3a53-3a11.png)

   >[!NOTE]
   >
   >Marketo staat alleen triggers toe voor mensen die de e-mail van dit e-mailprogramma hebben ontvangen. U hoeft het filter &#39;&#39;Is verzonden via e-mail&#39;&#39; niet toe te voegen.

1. Klik **Close**.

   ![](assets/image2014-9-12-15-3a53-3a36.png)

   Geweldig! Nu is het tijd om te beslissen hoe de winnaar wordt bepaald.

## Winnaar {#declare-winner} declareren

1. Kies een van de twee beschikbare opties.

   ![](assets/image2014-9-12-15-3a53-3a44.png)

   >[!NOTE]
   >
   >Als u een **Datum/tijd** A/B test doet, kunt u slechts **Handmatig** kiezen.

   Als de A/B-test voorbij is, kan Marketo de winnende e-mail automatisch verzenden op het geplande tijdstip. U kunt ook de resultaten bekijken en bepalen wanneer de e-mail wordt verzonden.

1. Automatisch is geweldig en is de standaardoptie. Klik **Volgende**.

   ![](assets/image2014-9-12-15-3a54-3a35.png)

   >[!TIP]
   >
   >Als u **Manual** kiest, wordt de test verzonden en wordt gewacht totdat u een winnaar opgeeft. U ontvangt een rapport met de resultaten.

Perfect! Laten we nu [de A/B-test plannen](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/email-test-a-b-test/schedule-the-a-b-test.md).
