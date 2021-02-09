---
unique-page-id: 12983291
description: Begrijpen van de tijdzone van de Ontvanger - Marketo Docs - de Documentatie van het Product
title: Tijdzone van ontvanger
translation-type: tm+mt
source-git-commit: 8d45a28e1c2adad3e04645f7150f1757414092f0
workflow-type: tm+mt
source-wordcount: '390'
ht-degree: 0%

---


# Tijdzone van ontvanger {#understanding-recipient-time-zone}

E-mail- en betrokkenheidsprogramma&#39;s kunnen zo worden geconfigureerd dat ze worden geleverd volgens de tijdzones van de ontvangers, zodat er geen meerdere programma&#39;s hoeven te worden gemaakt. Verzenden en Marketo houdt automatisch de e-mail tot de juiste lokale tijd.

>[!NOTE]
>
>Tijdzone van ontvanger werkt momenteel alleen **alleen** met e-mailinhoud. Het werkt niet voor standaardserviceprogramma&#39;s.

## E-mailprogramma&#39;s {#email-programs}

Er zijn twee primaire scenario&#39;s wanneer [het plannen van een e-mailprogramma](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/schedule-email-programs-with-recipient-time-zone.md):

1. Het programma wordt binnen 25 uur uitgevoerd.
1. Het programma wordt gepland voor meer dan 25 uur in de toekomst (dus volgende week).

Om elke tijdzone aan te passen, beginnen de e-mailprogramma&#39;s die met Ontvankelijke Tijdzone worden gepland om middernacht in **first/First** tijdzone in de wereld (UTC +14:00) te lopen.

## Betrokkenheidsprogramma&#39;s {#engagement-programs}

Wanneer u [een stroom van het betrokkenheidsprogramma plant](/help/marketo/product-docs/email-marketing/drip-nurturing/engagement-program-streams/set-stream-cadence/schedule-engagement-programs-with-recipient-time-zone.md) en de Ontvankelijke Tijdzone actief is, zal de programmagietvorm beginnen om middernacht in UTC +14:00. Wij vereisen u om de eerste gietvorm minstens 25 uren in de toekomst (24 uren + wat tijd te plannen om de campagne te beginnen) te plannen omdat de mensen voor de gietvorm in elke tijdzone over de wereld kunnen kwalificeren. Beginnen met verwerking op dit moment in UTC +14:00 garandeert dat we de e-mail op de geplande datum en tijd leveren voor elke persoon die voor deze cast in aanmerking komt.

## Tijdzone {#calculating-time-zone} berekenen

Marketo berekent de tijdzone op basis van de plaats, staat, land of postcode van een persoon. Als we de tijdzone van iemand niet kunnen berekenen van deze waarden, keren we terug naar de velden Ingetrokken plaats, Overgenomen staat, Ingetrokken land en Code Inferred Zip.

In gevallen waarin **only** Land of **only** Staat beschikbaar is:

* Voor landen met drie of minder tijdzones selecteren we de middelste tijdzone.
* Voor staten met twee tijdzones selecteren we de eerste van de twee tijdzones.

Als wij nog niet de tijdzone van iemand van om het even welke combinatie van deze gebieden kunnen bepalen, zullen wij **not** een tijdzone toewijzen en e-mail zal worden geleverd gebaseerd op uw streek van de het abonnementstijd van de Marketo. Dus als uw programma voor PDT 9:00am gepland is, zullen de mensen zonder toegewezen tijdzone de e-mail om PDT 9:00am ontvangen.

>[!NOTE]
>
>Marketo berekent automatisch de tijdzone van een persoon opnieuw wanneer een van de bovenstaande invoervelden wordt gewijzigd.

>[!MORELIKETHIS]
>
>* [E-mailprogramma&#39;s met tijdzone voor ontvangers plannen](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/schedule-email-programs-with-recipient-time-zone.md)
>* [Begin voor e-mailprogramma&#39;s](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/head-start-for-email-programs.md)

   >
   >
* [De Programma&#39;s van de Betrokkenheid van het programma met Ontvankelijke Tijdzone](/help/marketo/product-docs/email-marketing/drip-nurturing/engagement-program-streams/set-stream-cadence/schedule-engagement-programs-with-recipient-time-zone.md)

