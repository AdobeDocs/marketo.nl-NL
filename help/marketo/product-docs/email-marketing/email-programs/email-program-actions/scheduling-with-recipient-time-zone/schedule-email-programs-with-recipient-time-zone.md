---
unique-page-id: 12982903
description: E-mailprogramma's plannen met tijdzone voor ontvangers - Marketo Docs - Productdocumentatie
title: E-mailprogramma's met tijdzone voor ontvangers plannen
exl-id: d0c3f3c1-9f21-4081-818d-7c5cb1766915
feature: Email Programs
source-git-commit: 0c0dd3355f979577ec194f9e8f935615515905c0
workflow-type: tm+mt
source-wordcount: '792'
ht-degree: 0%

---

# E-mailprogramma&#39;s met tijdzone voor ontvangers plannen {#schedule-email-programs-with-recipient-time-zone}

Er zijn twee potentiële scenario&#39;s wanneer het plannen van een e-mailprogramma terwijl de Ontvankelijke Tijdzone wordt toegelaten:

1. Plannend het programma om **binnen** de volgende 25 uren in werking te stellen
1. Het programma plannen om **meer** dan 25 uren in de toekomst (namelijk volgende week) in werking te stellen

## Scenario 1: binnen 25 uur {#scenario-within-hours}

Stel dat u een e-mailprogramma goedkeurt met Tijdzone van ontvanger ingeschakeld en een geplande levertijd binnen de komende 25 uur. U kunt mensen in uw slimme lijst hebben die in tijdzones leven waar de geplande tijd reeds is overgegaan.

In dit scenario, staan wij u toe om te beslissen wat met deze ondergroep van gekwalificeerde mensen te doen. Klik op het tandwielpictogram naast **[!UICONTROL Recipient Time Zone]** in de tegel **[!UICONTROL Schedule]** van het e-mailprogramma.

![](assets/image2017-12-5-10-3a46-3a42.png)

Dit biedt u twee opties:

![](assets/image2017-12-5-10-3a31-3a28.png)

>[!NOTE]
>
>**Definitie**
>
>* **[!UICONTROL Deliver the following day in the recipient's time zone]**: als e-mail om op Dinsdag 9 :00am gepland is te gaan, zullen de gekwalificeerde mensen die in tijdstreken leven waar de geplande tijd reeds heeft overgegaan de e-mail op *Woensdag* bij 9 :00am ontvangen.
>
>* **[!UICONTROL Deliver using the program's default set time]**: als e-mail om op Dinsdag in 9 :00am gepland is te gaan, zullen de gekwalificeerde mensen die in tijdstreken leven waar de geplande tijd reeds heeft overgegaan e-mail *ontvangen die op uw montages van de de tijdzone van het abonnement* wordt gebaseerd. Zo, als uw [ montages van de de tijdzone van de abonnementstijd ](/help/marketo/product-docs/administration/settings/select-your-language-locale-and-time-zone.md) aan PDT America/Los Angeles worden geplaatst, zullen deze ontvangers nog e-mail op Dinsdag bij 9 :00am PDT ontvangen (welke tijd die in hun eigen tijdzones kan zijn).

>[!NOTE]
>
>[ leer meer ](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/understanding-recipient-time-zone.md#calculating-time-zone) over hoe Marketo tijdstreken voor ontvangers berekent.

Laten we dit scenario meer in detail bekijken. Zeg u in San Francisco bent, die een e-mail bij 7 :00am voor a **9:00am** plannen verzendt. In uw slimme lijst, zijn er mensen van de volgende gebieden:

* San Francisco
* Texas
* New York
* Italië

![](assets/image2017-12-6-10-3a52-3a41.png)

9 :00am is reeds overgegaan in New York en Italië, zo gekwalificeerde mensen in deze twee tijdzones ontvangen e-mail die op de **wordt gebaseerd de Montages van de Streek van de Tijd**:

* **[!UICONTROL Deliver the following day in the recipient's time zone]:** Woensdag bij 9 :00am in hun respectieve tijdstreken, **OF**

* **[!UICONTROL Deliver using the program's default set time]**: Dinsdag bij 9 :00am PDT (New York - 12 :00pm EDT en Italië - 6 :00pm CET).

Zodra u uw programma goedkeurt, begint het binnen 15 minuten lopen.

![](assets/screen-shot-2017-12-09-at-3.34.14-pm.png)

>[!NOTE]
>
>Hoewel het programma het *proces* begint van het verzenden van e-mails in 15 minuten, zullen de e-mails niet ** op dat ogenblik worden geleverd. Ontvangers ontvangen nog steeds e-mails op basis van de door u gekozen **[!UICONTROL Time Zone Settings]** .

## Scenario 2: Meer dan 25 uur {#scenario-more-than-hours}

In dit tweede scenario keurt u een e-mailprogramma goed met **[!UICONTROL Recipient Time Zone]** ingeschakeld en een geplande leveringstijd die in de toekomst meer dan 25 uur is. In dit geval, begint het programma lopend bij de geplande tijd in de **vroegste** tijdzone in de wereld (UTC + 14 :00). Er kunnen mensen zijn die voor uw slimme lijst in elke tijdzone over de wereld in aanmerking komen, zodat beginnend in de vroegste tijdzone ons toestaat om e-mail op de geplande datum/tijd aan alle ontvangers in hun respectieve tijdzones te leveren.

**Begin van het Kop**

Nu, laten we het hebben over hoe [[!UICONTROL Head Start]](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/head-start-for-email-programs.md) werkt met **[!UICONTROL Recipient Time Zone]** . Het programma moet ten minste 12 uur van tevoren worden gepland voor onze bestaande functie voor starten. Wat betekent dat voor de ontvangende tijdzone? Rappel dat wanneer de Ontvankelijke Tijdzone wordt toegelaten, beginnen wij het e-mailprogramma in de geplande tijd in de vroegste tijdzone (UTC +14 :00) in werking te stellen. Zo, om **zowel** HoofdBegin als Ontvankelijke Streek van de Tijd toe te laten, moeten de e-mailprogramma&#39;s **minstens 12 uren vóór de geplande tijd in UTC +14 :00 worden gepland.**

Dit betekent dat als u in Amerika/Los Angeles bent en zowel HoofdBegin als Ontvankelijke Tijdzone wilt toelaten, u het programma **34 uren** vooraf moet plannen. Hoe hebben we dit getal bereikt?

![](assets/image2017-12-5-13-3a11-3a38.png)

<br> 

Kortom, e-mailprogramma&#39;s die met de Ontvankelijke Tijdzone worden gepland moeten beginnen lopend bij de geplande tijd in de vroegste tijdzone (namelijk waar het middernacht eerst bereikt) om elke tijdzone aan te passen. Dus als u een e-mailprogramma plant...

* **met een leveringstijd *binnen* 25 uren**, begint het programma binnen 15 minuten lopen. Ontvangers die al zijn overgegaan tot de geplande tijd ontvangen de e-mail op basis van de instellingen voor de tijdzone die u hebt gekozen.
* **met een leveringstijd *meer dan* 25 uren in de toekomst**, begint het programma lopend bij de geplande tijd in de vroegste tijdzone (UTC +14 :00).
* **met het Begin van het Kop**, begint het programma 12 uren voorafgaand aan de geplande tijd in de vroegste tijdzone (UTC +14 :00) te verwerken.

>[!CAUTION]
>
>Iedereen die zich afmeldt tussen het moment dat u uw e-mail verzendt en het moment dat deze wordt verzonden, ontvangt de e-mail nog steeds. We raden je aan je abonnement aan te passen om uit te leggen dat het 1-2 werkdagen kan duren voordat je abonnement wordt opgezegd.

>[!MORELIKETHIS]
>
>* [ Begrijpend Ontvankelijke Tijdzone van de Tijd ](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/understanding-recipient-time-zone.md)
>* [ Begin van het Kop voor E-mailProgramma&#39;s ](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/head-start-for-email-programs.md)
>* [ Afbreken Levering van E-mailprogramma&#39;s die met de Ontvankelijke Streek van de Tijd worden gepland ](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/abort-delivery-of-email-programs-scheduled-with-recipient-time-zone.md)
