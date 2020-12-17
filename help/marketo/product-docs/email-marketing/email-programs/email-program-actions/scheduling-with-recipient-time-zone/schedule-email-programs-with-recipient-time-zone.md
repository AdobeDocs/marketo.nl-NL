---
unique-page-id: 12982903
description: E-mailprogramma's plannen met tijdzone voor ontvangers - Marketo Docs - Productdocumentatie
title: E-mailprogramma's met tijdzone voor ontvangers plannen
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '825'
ht-degree: 0%

---


# E-mailprogramma&#39;s plannen met Tijdzone {#schedule-email-programs-with-recipient-time-zone} van de ontvanger

Er zijn twee potentiële scenario&#39;s wanneer het plannen van een e-mailprogramma terwijl de Ontvankelijke Tijdzone wordt toegelaten:

1. Het programma plannen om **binnen** de volgende 25 uren te lopen
1. Het programma wordt gepland om **meer** dan 25 uur in de toekomst (d.w.z., volgende week) te lopen

## Scenario 1: Binnen 25 uur {#scenario-within-hours}

Stel dat u een e-mailprogramma goedkeurt met Tijdzone van ontvanger ingeschakeld en een geplande levertijd binnen de komende 25 uur. U kunt mensen in uw slimme lijst hebben die in tijdzones leven waar de geplande tijd reeds is overgegaan.

In dit scenario, staan wij u toe om te beslissen wat met deze ondergroep van gekwalificeerde mensen te doen. Klik op het tandwielpictogram naast **Ontvangertijdzone** in de tegel **Planning** van het e-mailprogramma.

![](assets/image2017-12-5-10-3a46-3a42.png)

Dit biedt u twee opties:

![](assets/image2017-12-5-10-3a31-3a28.png)

>[!NOTE]
>
>**Definitie**
>
>* **Lever de volgende dag in de tijdzone** van de ontvanger: als het e-mailbericht op dinsdag om 9.00 uur wordt uitgezonden , ontvangen gekwalificeerde mensen die in tijdzones wonen waar de geplande tijd al voorbij is , de e-mail op  ** woensdag om 9.00 uur .
   >
   >
* **Leveren met de standaardtijd** van het programma: als de e-mail op Dinsdag om 9:00 wordt gepland te gaan, zullen de gekwalificeerde mensen die in tijdzones wonen waar de geplande tijd reeds is overgegaan de e-mail ontvangen  *die op uw montages* van de de tijdzone van het abonnement wordt gebaseerd. Dus als uw [s](../../../../../product-docs/administration/settings/select-your-language-locale-and-time-zone.md) [instellingen voor de abonnementstijd](../../../../../product-docs/administration/settings/set-default-location-settings-for-a-subscription.md) zijn ingesteld op PDT America/Los Angeles, ontvangen deze ontvangers nog steeds de e-mail op dinsdag om 9.00 uur PDT (op welk tijdstip dan ook in hun eigen tijdzones).

>



>[!NOTE]
>
>[Leer ](https://docs.marketo.com/display/DOCS/Understanding+Recipient+Time+Zone#UnderstandingRecipientTimeZone-CalculatingTimeZone) meer over hoe Marketo tijdzones voor ontvangers berekent.

Laten we dit scenario meer in detail bekijken. Zeg u in San Francisco bent, die een e-mail om 7:00am voor een **9:00am** plannen verzendt. In uw slimme lijst, zijn er mensen van de volgende gebieden:

* San Francisco
* Texas
* New York
* Italië

![](assets/image2017-12-6-10-3a52-3a41.png)

9:00am is reeds overgegaan in New York en Italië, zo zullen de gekwalificeerde mensen in deze twee tijdzones e-mail ontvangen die op **de Montages van de Tijdzone** wordt gebaseerd:

* **Lever de volgende dag in de tijdzone van de ontvanger:** Woensdag om 9:00 uur in hun respectieve tijdzones,  **OF**

* **Leveren met de standaardtijd** van het programma: Dinsdag om 9:00 uur PDT (New York - 12:00 uur EDT en Italië - 18:00 uur CET).

Zodra u uw programma goedkeurt, begint het binnen 15 minuten lopen.

![](assets/screen-shot-2017-12-09-at-3.34.14-pm.png)

>[!NOTE]
>
>Hoewel het programma het *proces* van het verzenden van e-mails in 15 minuten start, worden de e-mails op dat moment niet *bezorgd*. Ontvangers zullen nog steeds e-mails ontvangen op basis van de **Tijdzone-instellingen** die u kiest.

## Scenario 2: Meer dan 25 uur {#scenario-more-than-hours}

In dit tweede scenario, keurt u een e-mailprogramma goed met **Ontvankelijke Gebied van de Tijd** toegelaten en een geplande leveringstijd die meer dan 25 uren in de toekomst is. In dit geval wordt het programma gestart op het geplande tijdstip in de vroegste **tijdzone** in de wereld (UTC + 14:00). Er kunnen mensen zijn die voor uw slimme lijst in elke tijdzone over de wereld in aanmerking komen, zodat beginnend in de vroegste tijdzone ons toestaat om e-mail op de geplande datum/tijd aan alle ontvangers in hun respectieve tijdzones te leveren.

Begin kop

Nu, bespreken wij hoe [Kop Begin](../../../../../product-docs/email-marketing/email-programs/email-program-actions/head-start-for-email-programs.md) met **Ontvankelijke Tijdzone** werkt. Het programma moet ten minste 12 uur van tevoren worden gepland voor onze bestaande functie voor starten. Wat betekent dat voor de ontvangende tijdzone? Zoals u weet, wordt het e-mailprogramma uitgevoerd op de geplande tijd in de vroegste tijdzone (UTC +14:00) wanneer Tijdzone voor ontvangers is ingeschakeld. Om **beide** Tijdzone van het Begin en van de Ontvanger in te schakelen, moeten e-mailprogramma&#39;s **minstens 12 uur voor de geplande tijd in UTC +14:00 worden gepland.**

Dit betekent dat als u in Amerika/Los Angeles bent en zowel HoofdBegin als Ontvankelijke Tijdzone wilt toelaten, u het programma **34 uren** vooraf moet plannen. Hoe hebben we dit getal bereikt?

![](assets/image2017-12-5-13-3a11-3a38.png)

<br> 

Kortom, e-mailprogramma&#39;s die met de Ontvankelijke Tijdzone worden gepland, moeten beginnen lopend op de geplande tijd in de vroegste tijdzone (d.w.z., waar het middernacht eerst bereikt) om elke tijdzone aan te passen. Dus als u een e-mailprogramma plant...

* **met een levertijd  *binnen*  25 uur** begint het programma binnen 15 minuten . Ontvangers die al zijn geslaagd voor de geplande tijd ontvangen de e-mail op basis van de instellingen voor de tijdzone die u hebt gekozen.
* **met een leveringstijd van  ** *meer dan*  25 uur in de toekomst**, begint het programma op het geplande tijdstip in de vroegste tijdzone (UTC +14:00).
* **met Begin** begint het programma twaalf uur voor de geplande tijd in de vroegste tijdzone (UTC +14:00) te verwerken.

>[!CAUTION]
>
>Iedereen die zich afmeldt tussen het moment dat u uw e-mail verzendt en het moment dat deze wordt verzonden, ontvangt de e-mail nog steeds. We raden je aan je afmeldingsbericht aan te passen om aan te geven dat het 1-2 werkdagen kan duren voordat je afmeldt.

>[!MORELIKETHIS]
>
>* [Tijdzone van ontvanger](understanding-recipient-time-zone.md)
>* [Begin voor e-mailprogramma&#39;s](../../../../../product-docs/email-marketing/email-programs/email-program-actions/head-start-for-email-programs.md)
>* [Aflevering van e-mailprogramma&#39;s afbreken die zijn gepland met de tijdzone van de ontvanger](abort-delivery-of-email-programs-scheduled-with-recipient-time-zone.md)

>



