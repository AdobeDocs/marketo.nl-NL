---
unique-page-id: 12982903
description: E-mailprogramma's plannen met tijdzone voor ontvangers - Marketo Docs - Productdocumentatie
title: E-mailprogramma's met tijdzone voor ontvangers plannen
exl-id: d0c3f3c1-9f21-4081-818d-7c5cb1766915
feature: Email Programs
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '815'
ht-degree: 0%

---

# E-mailprogramma&#39;s met tijdzone voor ontvangers plannen {#schedule-email-programs-with-recipient-time-zone}

Er zijn twee potentiële scenario&#39;s wanneer het plannen van een e-mailprogramma terwijl de Ontvankelijke Tijdzone wordt toegelaten:

1. Het programma wordt uitgevoerd **binnen** de volgende 25 uur
1. Het programma wordt uitgevoerd **meer** meer dan 25 uur in de toekomst (dus volgende week)

## Scenario 1: Binnen 25 uur {#scenario-within-hours}

Stel dat u een e-mailprogramma goedkeurt met Tijdzone van ontvanger ingeschakeld en een geplande levertijd binnen de komende 25 uur. U kunt mensen in uw slimme lijst hebben die in tijdzones leven waar de geplande tijd reeds is overgegaan.

In dit scenario, staan wij u toe om te beslissen wat met deze ondergroep van gekwalificeerde mensen te doen. Klik op het tandwielpictogram naast **Tijdzone ontvanger** in de **Schema** onderdeel van het e-mailprogramma.

![](assets/image2017-12-5-10-3a46-3a42.png)

Dit biedt u twee opties:

![](assets/image2017-12-5-10-3a31-3a28.png)

>[!NOTE]
>
>**Definitie**
>
>* **Lever de volgende dag in de tijdzone van de ontvanger**: als het e-mailbericht op dinsdag om 9.00 uur wordt uitgezonden, ontvangen gekwalificeerde personen die in tijdzones wonen waar de geplande tijd al voorbij is *woensdag* om 9:00 uur.
>
>* **Afleveren met de standaardtijd van de set**: als het e-mailbericht op dinsdag om 9.00 uur wordt uitgezonden, ontvangen gekwalificeerde personen die in tijdzones wonen waar de geplande tijd al voorbij is _op basis van de instellingen voor uw abonnementstijd_. Dus als uw [Instellingen voor tijdzone voor abonnementen](/help/marketo/product-docs/administration/settings/select-your-language-locale-and-time-zone.md) zijn ingesteld op PDT America/Los Angeles, ontvangen deze ontvangers nog steeds de e-mail op dinsdag om 9.00 uur PDT (op welk tijdstip dan ook in hun eigen tijdzones).

>[!NOTE]
>
>[Meer informatie](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/understanding-recipient-time-zone.md#calculating-time-zone) over hoe Marketo tijdzones voor ontvangers berekent.

Laten we dit scenario meer in detail bekijken. Stel dat je in San Francisco bent en om 7:00 uur een e-mail plant voor een **09:00** verzenden. In uw slimme lijst, zijn er mensen van de volgende gebieden:

* San Francisco
* Texas
* New York
* Italië

![](assets/image2017-12-6-10-3a52-3a41.png)

9.00 uur is al verstreken in New York en Italië, dus gekwalificeerde mensen in deze twee tijdzones zullen de e-mail ontvangen op basis van de **Instellingen tijdzone**:

* **Lever de volgende dag in de tijdzone van de ontvanger:** Woensdag om 9.00 uur in hun respectieve tijdzones, **OF**

* **Afleveren met de standaardtijd van de set**: Dinsdag om 9:00 uur PDT (New York - 12:00 uur EDT en Italië - 18:00 uur CET).

Zodra u uw programma goedkeurt, begint het binnen 15 minuten lopen.

![](assets/screen-shot-2017-12-09-at-3.34.14-pm.png)

>[!NOTE]
>
>Hoewel het programma de _proces_ van het verzenden van e-mails over 15 minuten, worden e-mails niet verzonden _bezorgd_ op dat moment. Ontvangers ontvangen nog steeds e-mails op basis van de **Instellingen tijdzone** kiest u.

## Scenario 2: Meer dan 25 uur {#scenario-more-than-hours}

In dit tweede scenario keurt u een e-mailprogramma goed met **Tijdzone ontvanger** en een geplande levertijd die meer dan 25 uur in de toekomst is. In dit geval wordt het programma gestart op het geplande tijdstip in het dialoogvenster **zo** tijdzone in de wereld (UTC + 14:00). Er kunnen mensen zijn die voor uw slimme lijst in elke tijdzone over de wereld in aanmerking komen, zodat beginnend in de vroegste tijdzone ons toestaat om e-mail op de geplande datum/tijd aan alle ontvangers in hun respectieve tijdzones te leveren.

**Begin kop**

Nu, laten we het hebben over hoe [Begin kop](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/head-start-for-email-programs.md) werkt met **Tijdzone ontvanger**. Het programma moet ten minste 12 uur van tevoren worden gepland voor onze bestaande functie voor starten. Wat betekent dat voor de ontvangende tijdzone? Zoals u weet, wordt het e-mailprogramma uitgevoerd op de geplande tijd in de vroegste tijdzone (UTC +14:00) wanneer Tijdzone voor ontvangers is ingeschakeld. Om **beide** Tijdzone voor begin en ontvanger, e-mailprogramma&#39;s moeten worden gepland **ten minste 12 uur voor de geplande tijd in UTC +14:00.**

Dit betekent dat als u in Amerika/Los Angeles bent en zowel HoofdBegin als Ontvankelijke Tijdzone wilt toelaten, u het programma moet plannen **34 uur** vooraf. Hoe hebben we dit getal bereikt?

![](assets/image2017-12-5-13-3a11-3a38.png)

<br> 

Kortom, e-mailprogramma&#39;s die met de Ontvankelijke Tijdzone worden gepland, moeten beginnen lopend op de geplande tijd in de vroegste tijdzone (d.w.z., waar het middernacht eerst bereikt) om elke tijdzone aan te passen. Dus als u een e-mailprogramma plant...

* **met een leveringstijd _binnen_ 25 uur**, begint het programma binnen 15 minuten. Ontvangers die al zijn geslaagd voor de geplande tijd ontvangen de e-mail op basis van de instellingen voor de tijdzone die u hebt gekozen.
* **met een leveringstijd _meer dan_ 25 uur in de toekomst**, wordt het programma gestart op het geplande tijdstip in de vroegste tijdzone (UTC +14:00).
* **met Begin kop** begint het programma twaalf uur voor de geplande tijd in de vroegste tijdzone (UTC +14:00) te verwerken.

>[!CAUTION]
>
>Iedereen die zich afmeldt tussen het moment dat u uw e-mail verzendt en het moment dat deze wordt verzonden, ontvangt de e-mail nog steeds. We raden je aan je afmeldingsbericht aan te passen om aan te geven dat het 1-2 werkdagen kan duren voordat je afmeldt.

>[!MORELIKETHIS]
>
>* [Tijdzone van ontvanger](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/understanding-recipient-time-zone.md)
>* [Begin voor e-mailprogramma&#39;s](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/head-start-for-email-programs.md)
>* [Aflevering van e-mailprogramma&#39;s afbreken die zijn gepland met de tijdzone van de ontvanger](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/abort-delivery-of-email-programs-scheduled-with-recipient-time-zone.md)
