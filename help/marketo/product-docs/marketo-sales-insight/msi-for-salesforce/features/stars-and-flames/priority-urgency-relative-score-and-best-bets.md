---
unique-page-id: 2950396
description: Prioriteit, Urgentie, Relatieve Score en Beste Bets - Marketo Docs - Productdocumentatie
title: Prioriteit, Urgentie, Relatieve Score en Beste Bets
exl-id: 391aae00-e4f5-4fb1-8728-f5224276dfc2
source-git-commit: 15263f9c23c958499aaa2e4e6491b4962c617358
workflow-type: tm+mt
source-wordcount: '452'
ht-degree: 0%

---

# Prioriteit, Urgentie, Relatieve Score en Beste Bets {#priority-urgency-relative-score-and-best-bets}

Marketo Sales Insight toont uw beste leads en contactpersonen op basis van hun prioriteit. De prioriteit van een lead of contactpersoon bestaat uit twee componenten: urgentie en relatieve score.

![](assets/priority-urgency-relative-score-and-best-bets-1.png)

Deze zijn afgeleid van de leadscore — een maat voor de interesse van de persoon in uw product(en). The higher the score, the more likely they will respond positively to a call from your sales team.

>[!NOTE]
>
>U hebt verschillende scoring campagnes nodig om de volledige waarde van prioriteit, urgentie en relatieve score te verkrijgen.  With too few or no scoring campaigns, these fields won&#39;t be useful.

## Urgentie {#urgency}

The flames represent urgency -- how much this person&#39;s lead score has changed recently. Een hoge urgentie (meer vlammen) betekent dat de score van deze lead de laatste tijd veel is gestegen; het is een goed teken dat deze lead geïnteresseerd is in je aanbieding . You should follow up with this person quickly!

Een lead die bijvoorbeeld een demo heeft aangevraagd en verschillende webpagina&#39;s heeft bezocht, zal waarschijnlijk een zeer hoge urgentie hebben. A lead who didn&#39;t visit your web page or open your emails will have a low urgency. Use urgency to prioritize who needs to be contacted next.

![](assets/priority-urgency-relative-score-and-best-bets-2.png)

## Relative Score {#relative-score}

De sterren vertegenwoordigen de relatieve score — een maat voor hoe de leadscore van deze persoon vergeleken wordt met die van alle anderen. Een hoge relatieve score betekent dat deze persoon waarschijnlijk interessanter en beter geïnformeerd is over je aanbieding dan mensen met lagere relatieve scores.

Als twee leiders de zelfde urgentie hebben, kunt u relatieve score gebruiken om te vertellen welke eerst een telefoongesprek verdient. De score met de hogere relatieve score kan gunstiger reageren op uw aanbod dan de lagere.

## Best Bets {#best-bets}

Uw Beste Bets zijn uw leads en contacten met de hoogste urgentie en de relatieve score. Only the leads you own are visible in that list, and the list is updated as lead scores change.

>[!NOTE]
>
>Als uw beste best niet de beste lood en contacten aanpast u bezit, praat met iemand bij uw bedrijf die toegang tot Marketo heeft over het bijwerken van uw [Scoreregels](/help/marketo/getting-started/quick-wins/simple-scoring.md).

### How Urgency and Relative Score are Calculated

Als u het aantal sterren en vlammen wilt berekenen, worden uw leads en contactpersonen eerst gesorteerd op score- of score-wijziging (voor respectievelijk Relatieve score en Urgentie). Dan zijn ze verdeeld in lagen — de bovenste laag krijgt de meeste sterren of vlammen, de volgende krijgt minder, enzovoort.

Naarmate de scores veranderen, worden de waarden voor urgentie, prioriteit en relatieve score direct opnieuw berekend. De urgentie- en relatieve score worden elke avond automatisch berekend op Marketo-servers.

>[!NOTE]
>
>Het aantal relatieve urgentie (vlammen) en relatieve score (sterren) zijn gehele getallen in Marketo. Mogelijke waarden voor elk zijn 0-3.
