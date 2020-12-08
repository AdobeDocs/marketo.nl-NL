---
unique-page-id: 12983280
description: Opmerkingen bij de release - herfst '17 - Marketo Docs - Productdocumentatie
title: Opmerkingen bij de release - herfst '17
translation-type: tm+mt
source-git-commit: 96cc6a30c63c8e8dca793a52e4bf7ecaef8c08dc
workflow-type: tm+mt
source-wordcount: '617'
ht-degree: 0%

---


# Opmerkingen bij de release: Herfst &#39;17 {#release-notes-fall}

De volgende functies zijn opgenomen in de Fall &#39;17-release. Controleer uw uitgave van de Marketo voor eigenschapbeschikbaarheid.

Klik op de titelkoppelingen om gedetailleerde artikelen voor elke functie weer te geven. Opmerking: Aan sommige functies in deze release zijn geen artikelen gekoppeld. Als een onderwerp veelvoudige onderverdelingen heeft, worden de verbindingen daar geplaatst.

## Systeembetrouwbaarheid {#system-reliability}

We hebben verdere verbeteringen aangebracht in de basisinfrastructuur van Marketo, waaronder betere sequencing, minder mismatches en verbeterde Munchkin-stabiliteit.

## SFDC-synchronisatieprestaties {#sfdc-sync-performance}

Profiteer van rijkere en snellere synchronisatie tussen Marketo en Salesforce. Gegevenswijzigingen die bulkupdates op accounts of leads vereisen, kunnen worden gesplitst in parallelle wachtrijen om achterstand te voorkomen. Gebeurtenissen en taken worden nu tot 50% sneller gesynchroniseerd.

## Verbeteringen van analyseprestaties {#analytics-performance-improvements}

De recente infrastructuurverbeteringen bieden verhoogde uptime en stabiliteit binnen Marketo rapportering en analysehulpmiddelen, die u toestaan om ad hoc rapporten sneller te bouwen.

## [Tijdzone ontvanger](https://docs.marketo.com/x/_xvG) {#recipient-time-zone}

Met deze nieuwe functie kunt u nu een e-mail verzenden volgens de lokale tijdzones. De e-mail en de betrokkenheidsprogramma&#39;s kunnen worden gevormd om in de tijdstreken van de ontvangers te worden geleverd, eliminerend de behoefte om veelvoudige programma&#39;s-verzendt eens en Marketo automatisch zal e-mail tot de correcte lokale tijd houden. Haal de metriek van e-mail op, houd lokale praktijken in acht, en bespaar tijd door één enkel programma globaal te gebruiken.

![](assets/image2017-11-29-8-3a45-3a47.png)

>[!NOTE]
>
>Als u de tijdzone voor ontvangers nog niet kunt inschakelen voor uw e-mail- en betrokkenheidsprogramma&#39;s, hoeft u niet te paniek! Deze functie wordt geleidelijk aan voor alle klanten beschikbaar gesteld.

## [Voorbeelde-mails per segment controleren](https://docs.marketo.com/x/2IER) {#review-sample-emails-by-segment}

Marketo heeft een nieuwe optie om een segment te kiezen wanneer u voorbeelde-mails ter controle verzendt. U hoeft niet meer handmatig te bepalen tot welk segment een lead behoort, waardoor het eenvoudiger wordt om e-mails met dynamische inhoud naar verschillende segmenten te verzenden.

## [Aangepaste vragen voor LinkedInLead Gen](https://docs.marketo.com/x/ngLG) {#linkedin-lead-gen-custom-questions}

Pas uw LinkedIn Gen-formulieren aan om aangepaste hoofdkenmerken te verzamelen. U kunt nu maximaal drie aangepaste vragen per formulier stellen, kiezen uit tekstinvoer van één regel of meerkeuzevragen en terugkoppelen naar loodvelden voor Marketo.

## [Slack-integratie](../../product-docs/administration/additional-integrations/add-slack-as-a-launchpoint-service.md) {#slack-integration}

We hebben twee functies uitgebracht als onderdeel van onze nieuwe Slack-integratie:

* Systeemmeldingen: Krijg Slack berichten betreffende belangrijke gebeurtenissen in uw instantie Marketo, zoals alarm over huidige campagnestatus en om het even welke kwesties die directe aandacht vereisen.
* Interesserende momenten: Wanneer een bekende persoon van een verkoopaccount een marktonderzoek heeft gestart, kunnen de eigenaars van leads via Slack op de hoogte worden gebracht. Meldingen bevatten informatie over leads en informatie over de verkoopaccount.

## Verbeteringen voor ABM {#abm-enhancements}

** [Accounts weergeven zonder contactpersonen](https://docs.marketo.com/x/fKCt)**

Marketo ABM synchroniseert nu CRM-accounts en geeft deze weer zonder contactpersonen. Neem nieuwe accounts op zonder verkoopgeschiedenis of marketinggeschiedenis en volg de vorderingen door de volgende resultaten af te stemmen op de accounts.

## `<sup>AI </sup>`ContentAnalytics {#contentai-analytics}

** [Nieuw ABM-accountlijstfilter](https://docs.marketo.com/x/1BPG) **

De prestaties van inhoud in ABM-accountlijsten bekijken en vergelijken om bestaande inhoud te optimaliseren. Inhoud`<sup>AI</sup>` laat u zien:

* bovenste inhoud weergegeven
* geconverteerde inhoud boven
* Door AI aangedreven gesuggereerde inhoud voor marketingactiviteiten

## Verbeteringen voor webpersonalisatie {#web-personalization-enhancements}

** [Tokens voor webcampagnes](https://docs.marketo.com/x/SwJI)**

Tokens zijn nu beschikbaar voor gebruik in webcampagnes. Gebruik tokens om gepersonaliseerde berichten en inhoud te leveren om de betrokkenheid bij uw webcampagnes te vergroten.

![](assets/image2017-11-16-11-3a25-3a7.png)

** [Design Studio Images in Web Campaign Editor](https://docs.marketo.com/x/SwJI)**

Bespaar tijd door creatieve elementen en afbeeldingen op meerdere kanalen in Marketo opnieuw te gebruiken.

![](assets/image2017-11-16-11-3a26-3a10.png)

## Integratie  {#integration}

** [E-mailvoorbeeld-API](https://developers.marketo.com/rest-api/assets/emails/)**

U kunt nu op afstand een voorbeeld van een e-mailbericht weergeven buiten Marketo, het lokalisatieproces voor e-mailinhoud vereenvoudigen en fouten verminderen.

** [HTML API](https://developers.marketo.com/rest-api/assets/emails/)vervangen**

Ontwikkelaars kunnen HTML-inhoud van e-mailmiddelen op afstand bijwerken, zodat ze binnen één systeem kunnen werken om elementen te onderhouden.
