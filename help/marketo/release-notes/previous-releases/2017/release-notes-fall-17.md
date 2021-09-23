---
unique-page-id: 12983280
description: Opmerkingen bij de release - herfst '17 - Marketo Docs - Productdocumentatie
title: Opmerkingen bij de release - herfst '17
exl-id: 329022e6-f388-4ff9-9724-62aeed76c0b9
source-git-commit: 74effe9f8078f8d71e6de01d6e737ddc86978abb
workflow-type: tm+mt
source-wordcount: '597'
ht-degree: 0%

---

# Opmerkingen bij de release: Herfst &#39;17 {#release-notes-fall}

De volgende functies zijn opgenomen in de Fall &#39;17-release. Raadpleeg de Marketo-editie voor informatie over de beschikbaarheid van functies.

Klik op de titelkoppelingen om gedetailleerde artikelen voor elke functie weer te geven. Opmerking: Aan sommige functies in deze release zijn geen artikelen gekoppeld. Als een onderwerp veelvoudige onderverdelingen heeft, worden de verbindingen daar geplaatst.

## Systeembetrouwbaarheid {#system-reliability}

We hebben verdere verbeteringen aangebracht in de basisinfrastructuur van Marketo, zoals betere sequencing, minder wanverhoudingen en verbeterde Munchkin-stabiliteit.

## SFDC-synchronisatieprestaties {#sfdc-sync-performance}

Profiteer van rijkere en snellere synchronisatie in Marketo en Salesforce. Gegevenswijzigingen die bulkupdates op accounts of leads vereisen, kunnen worden gesplitst in parallelle wachtrijen om achterstand te voorkomen. Gebeurtenissen en taken worden nu tot 50% sneller gesynchroniseerd.

## Verbeteringen van analyseprestaties {#analytics-performance-improvements}

Recente infrastructuurverbeteringen bieden een verhoogde uptime en stabiliteit binnen de rapportage- en analyseprogramma&#39;s van Marketo, waardoor u sneller ad-hocrapporten kunt samenstellen.

## [Tijdzone ontvanger](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/understanding-recipient-time-zone.md) {#recipient-time-zone}

Met deze nieuwe functie kunt u nu een e-mail verzenden volgens de lokale tijdzones. E-mail- en betrokkenheidsprogramma&#39;s kunnen zo worden geconfigureerd dat ze in de tijdzones van de ontvangers worden geleverd, zodat er geen meerdere programma&#39;s hoeven te worden gemaakt. Verstuur deze eenmaal en Marketo houdt de e-mail automatisch in totdat de juiste lokale tijd is verstreken. Haal de metriek van e-mail op, houd lokale praktijken in acht, en bespaar tijd door één enkel programma globaal te gebruiken.

![](assets/image2017-11-29-8-3a45-3a47.png)

>[!NOTE]
>
>Als u de tijdzone voor ontvangers nog niet kunt inschakelen voor uw e-mail- en betrokkenheidsprogramma&#39;s, hoeft u niet te paniek! Deze functie wordt geleidelijk aan voor alle klanten beschikbaar gesteld.

## [Voorbeelde-mails per segment controleren](/help/marketo/product-docs/email-marketing/general/creating-an-email/send-a-sample-email.md) {#review-sample-emails-by-segment}

Marketo heeft een nieuwe optie om een segment te kiezen wanneer het verzenden van voorbeelde-mails ter controle. U hoeft niet meer handmatig te bepalen tot welk segment een lead behoort, waardoor het eenvoudiger wordt om e-mails met dynamische inhoud naar verschillende segmenten te verzenden.

## [Aangepaste vragen voor linkedIn-leider](/help/marketo/product-docs/demand-generation/social/social-functions/set-up-linkedin-lead-gen-forms.md) {#linkedin-lead-gen-custom-questions}

Pas uw LinkedIn Lead Gen-formulieren aan om aangepaste lead-kenmerken te verzamelen. U kunt nu maximaal drie aangepaste vragen per formulier stellen, kiezen uit tekstinvoer van één regel of meerkeuzevragen en terugkoppelen naar hoofdvelden van Marketo.

## Slack-integratie {#slack-integration}

We hebben twee functies uitgebracht als onderdeel van onze nieuwe Slack-integratie:

* Systeemmeldingen: Krijg Slack berichten over belangrijke gebeurtenissen in uw Marketo instantie, zoals alarm over huidige campagnestatus en om het even welke kwesties die directe aandacht vereisen.
* Interesserende momenten: Wanneer een bekende persoon een Marketo Insight heeft geactiveerd via een verkoopaccount, kunnen de hoofdeigenaars via Slack op de hoogte worden gesteld. Meldingen bevatten informatie over leads en informatie over de verkoopaccount.

## Verbeteringen voor ABM {#abm-enhancements}

**[Accounts weergeven zonder contactpersonen](https://docs.marketo.com/x/fKCt)**

Marketo ABM synchroniseert nu CRM-accounts en geeft deze weer zonder contactpersonen. Neem nieuwe accounts op zonder verkoopgeschiedenis of marketinggeschiedenis en volg de vorderingen door de volgende resultaten af te stemmen op de accounts.

## ContentAI-analyse {#contentai-analytics}

**[Nieuw ABM-accountlijstfilter](https://docs.marketo.com/x/1BPG)**

De prestaties van inhoud in ABM-accountlijsten bekijken en vergelijken om bestaande inhoud te optimaliseren. ContentAI laat u zien:

* bovenste inhoud weergegeven
* geconverteerde inhoud boven
* Door AI aangedreven gesuggereerde inhoud voor marketingactiviteiten

## Verbeteringen voor webpersonalisatie {#web-personalization-enhancements}

**[Tokens voor webcampagnes](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/using-the-web-personalization-rich-text-editor.md)**

Tokens zijn nu beschikbaar voor gebruik in webcampagnes. Gebruik tokens om gepersonaliseerde berichten en inhoud te leveren om de betrokkenheid bij uw webcampagnes te vergroten.

![](assets/image2017-11-16-11-3a25-3a7.png)

**[Studio-afbeeldingen ontwerpen in de webcampagneeditor](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/using-the-web-personalization-rich-text-editor.md)**

Bespaar tijd door creatieve middelen en afbeeldingen op meerdere kanalen in Marketo opnieuw te gebruiken.

![](assets/image2017-11-16-11-3a26-3a10.png)

## Integratie  {#integration}

**[E-mailvoorbeeld-API](https://developers.marketo.com/rest-api/assets/emails/)**

U kunt nu op afstand een voorbeeld van een e-mailbericht buiten Marketo bekijken, het lokalisatieproces voor e-mailinhoud vereenvoudigen en fouten reduceren.

**[HTML-API vervangen](https://developers.marketo.com/rest-api/assets/emails/)**

Ontwikkelaars kunnen HTML-inhoud van e-mailmiddelen op afstand bijwerken, zodat ze binnen één systeem kunnen werken om elementen te onderhouden.
