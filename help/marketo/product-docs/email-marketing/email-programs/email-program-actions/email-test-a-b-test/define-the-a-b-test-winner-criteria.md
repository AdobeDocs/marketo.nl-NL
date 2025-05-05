---
unique-page-id: 2359545
description: Bepaal de A/B criteria van de Winner van de Test - Marketo DOS - de Documentatie van het Product
title: Bepaal de Criteria van de Winner van de Test A/B
exl-id: be8a0887-70f4-4667-93a6-d982a16cdfdb
feature: Email Programs, A/B Testing
source-git-commit: d20a9bb584f69282eefae3704ce4be2179b29d0b
workflow-type: tm+mt
source-wordcount: '412'
ht-degree: 0%

---

# Bepaal de Criteria van de Winner van de Test A/B {#define-the-a-b-test-winner-criteria}

Wanneer [toevoegen van een A/B-test](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/email-test-a-b-test/add-an-a-b-test.md){target="_blank"} to your email program, you will need to pick a test type, [schedule the A/B test](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/email-test-a-b-test/schedule-the-a-b-test.md){target="_blank"}en definieert u vervolgens de criteria voor de winnaars. Hier is hoe je bepaalt welke e-mail wint.

>[!PREREQUISITES]
>
>[Een A/B-test toevoegen](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/email-test-a-b-test/add-an-a-b-test.md){target="_blank"}

## Winkelcriteria {#winner-criteria}

1. De standaardwaarde **Winkelcriteria** worden als eerste weergegeven.

   ![](assets/image2014-9-12-15-3a51-3a3.png)

   <table>
   <tr>
   <td><b>Openen</b></td>
   <td>Een open register wanneer afbeeldingen naar een e-mail worden gedownload. Zelfs als u geen afbeelding opneemt, voegt Marketo standaard één pixel achter elkaar in alle HTML-e-mails in.</td>
   </tr>
   <tr>
   <td><b>Klikken</b></td>
   <td>Standaard zijn koppelingen in e-mailberichten ingesloten, zodat u kunt zien wie op de koppeling heeft geklikt, hoeveel koppelingen er zijn geklikt, enzovoort.</td>
   </tr>
   <tr>
   <td><b>Klikken om % te openen</b></td>
   <td>Percentage e-mailberichten dat is geopend en waarop een koppeling is geklikt in het e-mailbericht. Dit meet de relevantie en de context van een e-mail door het aantal unieke kliks te nemen gedeeld door het aantal unieke opent, en dan het vermenigvuldigen met 100 om het als percentage te tonen.</td>
   </tr>
   <tr>
   <td><b>Engagement Score</b></td>
   <td>De <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/drip-nurturing/reports-and-notifications/understanding-the-engagement-score.html?lang=nl-NL" target="_blank">betrokkenheidsscore</a> helpt u de doeltreffendheid van uw inhoud te bepalen.</td>
   </tr>
   </table>

   >[!TIP]
   >
   >Als u Betrokkenheidsscore kiest, moet de test minstens 24 uur worden uitgevoerd. Meer informatie over [inzicht krijgen in de betrokkenheidsscore](/help/marketo/product-docs/email-marketing/drip-nurturing/reports-and-notifications/understanding-the-engagement-score.md){target="_blank"}.

1. U kunt uw criteria ook aanpassen door Aangepaste omzetting te selecteren en op Bewerken te klikken.

   ![](assets/image2014-9-12-15-3a51-3a53.png)

   >[!NOTE]
   >
   >Met Aangepaste omzetting kunt u elke gebeurtenis als een conversie kiezen met behulp van triggers en filters.

1. Er wordt een venster geopend. Zoek de trigger van uw keuze en sleep deze naar het canvas.

   ![](assets/image2014-9-12-15-3a52-3a18.png)

1. Definieer de trigger.

   ![](assets/image2014-9-12-15-3a53-3a11.png)

   >[!IMPORTANT]
   >
   >Marketo staat alleen triggers/filters toe voor mensen die de e-mail van dit e-mailprogramma hebben ontvangen. Het is dus niet nodig een filter &#39;Is e-mail verzonden&#39; toe te voegen. Wanneer u een trigger/filter voor e-mail gebruikt, moet u er bovendien voor zorgen dat &quot;gelijk aan&quot; wordt gebruikt als operator.

1. Klikken **Sluiten**.

   ![](assets/image2014-9-12-15-3a53-3a36.png)

   Geweldig! Nu is het tijd om te beslissen hoe de winnaar wordt bepaald.

## Winner declareren {#declare-winner}

1. Kies een van de twee beschikbare opties.

   ![](assets/image2014-9-12-15-3a53-3a44.png)

   >[!NOTE]
   >
   >Als u een **Datum/tijd** A/B test, u kunt slechts kiezen **Handmatig**.

   Als de A/B-test is afgelopen, kan Marketo de winnende e-mail automatisch verzenden op het geplande tijdstip. U kunt ook de resultaten bekijken en bepalen wanneer de e-mail wordt verzonden.

1. Automatisch is geweldig en is de standaardoptie. Alleen klikken **Volgende**.

   ![](assets/image2014-9-12-15-3a54-3a35.png)

   >[!TIP]
   >
   >Kiezen **Handmatig** stuurt de test uit en wacht tot je een winnaar hebt gedeclareerd. U ontvangt een rapport met de resultaten.

Perfect! Laten we nu [de A/B-test plannen](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/email-test-a-b-test/schedule-the-a-b-test.md){target="_blank"}.
