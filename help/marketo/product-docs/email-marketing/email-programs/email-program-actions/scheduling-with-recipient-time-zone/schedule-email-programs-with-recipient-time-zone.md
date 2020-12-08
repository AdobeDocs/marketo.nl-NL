---
unique-page-id: 12982903
description: E-mailprogramma's plannen met tijdzone voor ontvangers - Marketo Docs - Productdocumentatie
title: E-mailprogramma's met tijdzone voor ontvangers plannen
translation-type: tm+mt
source-git-commit: 313266a67243f0c70c25010cb4825efb7f3db0ab
workflow-type: tm+mt
source-wordcount: '827'
ht-degree: 0%

---


# E-mailprogramma&#39;s met tijdzone voor ontvangers plannen {#schedule-email-programs-with-recipient-time-zone}

Er zijn twee potentiële scenario&#39;s wanneer het plannen van een e-mailprogramma terwijl de Ontvankelijke Tijdzone wordt toegelaten:

1. Het programma wordt **binnen** 25 uur uitgevoerd
1. Het programma wordt **meer** dan 25 uur in de toekomst gepland (volgende week dus)

## Scenario 1: Binnen 25 uur {#scenario-within-hours}

Stel dat u een e-mailprogramma goedkeurt met Tijdzone van ontvanger ingeschakeld en een geplande levertijd binnen de komende 25 uur. U kunt mensen in uw slimme lijst hebben die in tijdzones leven waar de geplande tijd reeds is overgegaan.

In dit scenario, staan wij u toe om te beslissen wat met deze ondergroep van gekwalificeerde mensen te doen. Klik op het tandwielpictogram naast **Tijdzone** ontvanger in de tegel **Planning** van het e-mailprogramma.

![](assets/image2017-12-5-10-3a46-3a42.png)

Dit biedt u twee opties:

![](assets/image2017-12-5-10-3a31-3a28.png)

>[!NOTE]
>
>**Definitie**
>
>* **Lever de volgende dag in de tijdzone** van de ontvanger: als het e-mailbericht op dinsdag om 9.00 uur wordt uitgezonden, ontvangen gekwalificeerde mensen die in tijdzones wonen waar de geplande tijd al voorbij is, het e-mailbericht op *woensdag* om 9.00 uur.
   >
   >
* **Leveren met de standaardtijd** van het programma: als de e-mail op Dinsdag om 9:00 wordt gepland te gaan, zullen de gekwalificeerde mensen die in tijdzones wonen waar de geplande tijd reeds is overgegaan de e-mail ontvangen *die op uw montages* van de de tijdzone van het abonnement wordt gebaseerd. Dus als uw instellingen voor [de](../../../../../product-docs/administration/settings/select-your-language-locale-and-time-zone.md) abonnementstijd [](../../../../../product-docs/administration/settings/set-default-location-settings-for-a-subscription.md) zijn ingesteld op PDT America/Los Angeles, ontvangen deze ontvangers nog steeds de e-mail op dinsdag om 9.00 uur PDT (op welk tijdstip dan ook in hun eigen tijdzones).

>



>[!NOTE]
>
>[Meer](https://docs.marketo.com/display/DOCS/Understanding+Recipient+Time+Zone#UnderstandingRecipientTimeZone-CalculatingTimeZone) informatie over hoe Marketo tijdzones voor ontvangers berekent.

Laten we dit scenario meer in detail bekijken. Stel dat je in San Francisco bent en een e-mail om 7:00 uur plant voor een **verzending van 9:00 uur** . In uw slimme lijst, zijn er mensen van de volgende gebieden:

* San Francisco
* Texas
* New York
* Italië

![](assets/image2017-12-6-10-3a52-3a41.png)

9:00 uur is al verstreken in New York en Italië, dus gekwalificeerde mensen in deze twee tijdzones ontvangen de e-mail op basis van de instellingen **voor** tijdzone:

* **Lever de volgende dag in de tijdzone van de ontvanger:** Woensdag om 9:00 uur in de respectieve tijdzones, **OF**

* **Leveren met de standaardtijd** van het programma: Dinsdag om 9:00 uur PDT (New York - 12:00 uur EDT en Italië - 18:00 uur CET).

Zodra u uw programma goedkeurt, begint het binnen 15 minuten lopen.

![](assets/screen-shot-2017-12-09-at-3.34.14-pm.png)

>[!NOTE]
>
>Hoewel het programma binnen 15 minuten begint met het *verzenden* van e-mails, worden de e-mails op dat moment niet *bezorgd* . Ontvangers ontvangen nog steeds e-mails op basis van de door u gekozen instellingen voor **de** tijdzone.

## Scenario 2: Meer dan 25 uur {#scenario-more-than-hours}

In dit tweede scenario, keurt u een e-mailprogramma goed met **Ontvankelijke Toegelaten Gebied** van de Tijd en een geplande leveringstijd die meer dan 25 uren in de toekomst is. In dit geval wordt het programma gestart op het geplande tijdstip in de **vroegste** tijdzone ter wereld (UTC + 14:00). Er kunnen mensen zijn die voor uw slimme lijst in elke tijdzone over de wereld in aanmerking komen, zodat beginnend in de vroegste tijdzone ons toestaat om e-mail op de geplande datum/tijd aan alle ontvangers in hun respectieve tijdzones te leveren.

Begin kop

Nu, laten we het hebben over hoe [Head Start](../../../../../product-docs/email-marketing/email-programs/email-program-actions/head-start-for-email-programs.md) werkt met **Recipient Time Zone**. Het programma moet ten minste 12 uur van tevoren worden gepland voor onze bestaande functie voor starten. Wat betekent dat voor de ontvangende tijdzone? Zoals u weet, wordt het e-mailprogramma uitgevoerd op de geplande tijd in de vroegste tijdzone (UTC +14:00) wanneer Tijdzone voor ontvangers is ingeschakeld. Om **zowel** Head Start- als Ontvangertijd Zone mogelijk te maken, moeten e-mailprogramma&#39;s ten **minste 12 uur voor de geplande tijd in UTC +14:00 worden gepland.**

Dit betekent dat als u in Amerika/Los Angeles bent en zowel HoofdBegin als Ontvankelijke Tijdzone wilt toelaten, u het programma **34 uur** van tevoren moet plannen. Hoe hebben we dit getal bereikt?

![](assets/image2017-12-5-13-3a11-3a38.png)

<br> 

Kortom, e-mailprogramma&#39;s die met de Ontvankelijke Tijdzone worden gepland, moeten beginnen lopend op de geplande tijd in de vroegste tijdzone (d.w.z., waar het middernacht eerst bereikt) om elke tijdzone aan te passen. Dus als u een e-mailprogramma plant...

* **met een levertijd *binnen* 25 uur** begint het programma binnen 15 minuten . Ontvangers die al zijn geslaagd voor de geplande tijd ontvangen de e-mail op basis van de instellingen voor de tijdzone die u hebt gekozen.
* **met een leveringstijd van *meer* *dan* 25 uur in de toekomst**, begint het programma op de geplande tijd in de vroegste tijdzone (UTC +14:00).
* **met Begin** begint het programma twaalf uur voor de geplande tijd in de vroegste tijdzone (UTC +14:00) te verwerken.

>[!CAUTION]
>
>Iedereen die zich afmeldt tussen het moment dat u uw e-mail verzendt en het moment dat deze wordt verzonden, ontvangt de e-mail nog steeds. We raden je aan je afmeldingsbericht aan te passen om aan te geven dat het 1-2 werkdagen kan duren voordat je afmeldt.

>[!NOTE]
>
>**Verwante artikelen**
>
>* [Tijdzone van ontvanger](understanding-recipient-time-zone.md)
>* [Begin voor e-mailprogramma&#39;s](../../../../../product-docs/email-marketing/email-programs/email-program-actions/head-start-for-email-programs.md)
>* [Aflevering van e-mailprogramma&#39;s afbreken die zijn gepland met de tijdzone van de ontvanger](abort-delivery-of-email-programs-scheduled-with-recipient-time-zone.md)

>



