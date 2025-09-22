---
unique-page-id: 12983291
description: Begrijpen van tijdzone voor ontvangers - Marketo Docs - Productdocumentatie
title: Tijdzone van ontvanger
exl-id: 8895241e-94c9-43a2-9158-11c1994df09b
feature: Email Programs
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '381'
ht-degree: 0%

---

# Tijdzone van ontvanger {#understanding-recipient-time-zone}

E-mail- en betrokkenheidsprogramma&#39;s kunnen zo worden geconfigureerd dat ze worden geleverd volgens de tijdzones van de ontvangers, zodat er geen meerdere programma&#39;s hoeven te worden gemaakt—en Marketo houdt de e-mail automatisch bij tot de juiste lokale tijd.

>[!NOTE]
>
>[!UICONTROL Recipient Time Zone] werkt momenteel **slechts** met e-mailinhoud. Het werkt niet voor standaardserviceprogramma&#39;s.

## E-mailprogramma&#39;s {#email-programs}

Er zijn twee primaire scenario&#39;s wanneer [ plannend een e-mailprogramma ](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/schedule-email-programs-with-recipient-time-zone.md):

1. Het programma wordt binnen 25 uur uitgevoerd.
1. Het programma is gepland voor meer dan 25 uur in de toekomst (dus volgende week).

Om elke tijdzone aan te passen, e-mailprogramma&#39;s die met [!UICONTROL Recipient Time Zone] worden gepland beginnen bij middernacht in **eerste/vroegste** tijdzone in de wereld (UTC +14 :00).

## Betrokkenheidsprogramma&#39;s {#engagement-programs}

Wanneer u [ een stroom van het betrokkenheidsprogramma ](/help/marketo/product-docs/email-marketing/drip-nurturing/engagement-program-streams/set-stream-cadence/schedule-engagement-programs-with-recipient-time-zone.md) plant en [!UICONTROL Recipient Time Zone] actief is, begint de programmagietvorm bij middernacht in UTC +14 :00 te lopen. Wij vereisen u om de eerste gietvorm minstens 25 uren in de toekomst (24 uren + wat tijd te plannen om de campagne te beginnen) te plannen omdat de mensen voor de gietvorm in elke tijdzone over de wereld kunnen kwalificeren. Beginnend verwerking op dit ogenblik in UTC +14 :00 garandeert dat e-mail op de geplande datum en de tijd voor elke persoon wordt verzonden die voor deze gietvorm in aanmerking komt.

## Tijdzone berekenen {#calculating-time-zone}

Marketo berekent de tijdzone op basis van de plaats, staat, land of postcode van een persoon. Als we de tijdzone van iemand niet kunnen berekenen van deze waarden, keren we terug naar de velden Ingetrokken plaats, Overgenomen staat, Ingetrokken land en Code Inferred Zip.

In gevallen waar wij **slechts** Land of **slechts** beschikbare Staat hebben:

* Voor landen met drie of minder tijdzones selecteren we de middelste tijdzone.
* Voor staten met twee tijdzones selecteren we de eerste van de twee.

Als wij nog niet de tijdzone van iemand van om het even welke combinatie deze gebieden kunnen bepalen, zullen wij **niet** een tijdzone toewijzen en e-mail zal worden verzonden gebaseerd op uw de tijdzone van het Marketo abonnement. Zo, als uw programma voor 9 :00am PDT gepland is, zullen de mensen zonder toegewezen tijdzone de e-mail bij 9 :00am PDT worden verzonden.

>[!NOTE]
>
>Marketo berekent automatisch de tijdzone van een persoon opnieuw wanneer een van de bovenstaande invoervelden wordt gewijzigd.

>[!MORELIKETHIS]
>
>* [ Plan e-mailprogramma&#39;s met [!UICONTROL Recipient Time Zone]](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/schedule-email-programs-with-recipient-time-zone.md)
>* [ Begin van het Kop voor E-mailProgramma&#39;s ](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/head-start-for-email-programs.md)
>
>* [ Programma&#39;s van de Betrokkenheid van het Programma met [!UICONTROL Recipient Time Zone]](/help/marketo/product-docs/email-marketing/drip-nurturing/engagement-program-streams/set-stream-cadence/schedule-engagement-programs-with-recipient-time-zone.md)
