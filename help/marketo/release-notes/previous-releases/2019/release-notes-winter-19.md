---
unique-page-id: 17727823
description: Opmerkingen bij de release - Winter '19 - Marketo Docs - Productdocumentatie
title: Release-aantekeningen -Winter '19
exl-id: 0cb3b3a1-472e-41d4-84f4-47f06e65017c
source-git-commit: 21bcdc10fe1f3517612efe0f8e2adaf2f4411a70
workflow-type: tm+mt
source-wordcount: '1050'
ht-degree: 0%

---

# Opmerkingen bij de release: Winter &#39;19 {#release-notes-winter}

De volgende functies zijn opgenomen in de release van Winter &#39;19. Raadpleeg de Marketo-editie voor informatie over de beschikbaarheid van functies.

Klik op de titelkoppelingen om gedetailleerde artikelen voor elke functie weer te geven, indien beschikbaar.

>[!NOTE]
>
>[!DNL Facebook] heeft nu een Business Manager-account nodig om de integratie met het aangepaste publiek te kunnen gebruiken. Uw [!DNL Facebook] dienst van LaunchPoint *moet* met een rekening van BedrijfsManager worden geassocieerd of **uw integratie zal niet meer na 14 Januari, 2019** werken. Om een rekening van de BedrijfsManager op te zetten, gelieve te verwijzen naar [[!DNL Facebook]  Hulp ](https://www.facebook.com/business/help/1710077379203657).

>[!NOTE]
>
>Microsoft dringt er bij alle online klanten op aan een upgrade uit te voeren naar de nieuwste versie van [!DNL Microsoft Dynamics] . Als u uw instantie van Marketo met [!DNL Dynamics Online] integreert, zult u aan [ verbetering aan de recentste versie van de Oplossing van Marketo ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/update-the-marketo-solution-for-microsoft-dynamics.md) vóór **Januari 31, 2019** moeten verzekeren dat uw integratie zal blijven werkend.

>[!NOTE]
>
>Marketo voert een upgrade uit van de OAuth-versie voor GoToWebinar van 1.0 naar 2.0. De steun voor OAuth 1.0 wordt in januari 2019 afgekeurd. Als u een klant GoToWebinar bent, zult u uw logins door LaunchPoint (in het Admin gebied) door **31 Januari, 2019** moeten opnieuw voor authentiek verklaren om ervoor te zorgen dat uw integratie zal blijven werkend. Voor meer details, gelieve te verwijzen naar onze [ communautaire pagina ](https://nation.marketo.com/docs/DOC-6739-gotowebinar-authentication-change-take-action-before-1312019).

## Verbeteringen voor kernplatform {#core-platform-enhancements}

**[E-mail CC voor e-mails van Marketo](/help/marketo/product-docs/email-marketing/general/email-cc.md)**

Neem maximaal vijf CC-adressen per ontvanger op in e-mails die via Marketo worden verzonden.

**API**

* **Multi-Branding Steun van het Domein voor Activum API:** het goedkeuren en het klonen van activa veroorzaken de zelfde resultaten binnen API en UI.
* **Steun van de E-mailCC voor Activa API**: De gebruikers klonen, goedkeuren, en verwerken e-mails via API zullen pariteit met de montages handhaven UI.

**[[!DNL Munchkin] v155 (Beta) ](https://developers.marketo.com/javascript-api/lead-tracking/configuration/)**

* **API-Enige Wijze**: De gebruikers kunnen nu bepalen wanneer en hoe te om leden van hun gegevensbestand te volgen door single-page Web apps toe te staan om uitdrukkelijk te roepen wanneer zij een webpaginabezoek willen registreren in plaats van zich op het automatisch volgen van Marketo te baseren.
* **Opt-uit Beheer**: Beheer gemakkelijk opt-outs door het opt-out koekjesdomein met het [!DNL Munchkin] volgende koekjesdomein aan te passen.
* **domein-Vlakke Parameter van de Decider**: Tweetalige domeinen (d.w.z. &quot; [ website.io ](https://website.io)&quot;) zullen automatisch in Marketo zonder extra opstellingsvereisten volgen.

## Marketo Sales Engage {#marketo-sales-engage}

* **[!DNL Salesforce]Aangepast profiel**: verkoopservice ondersteunt nu onbeperkte aangepaste profielen.

* **[!DNL Salesforce]Aanpassing**: Door niet-kritieke gebieden van de douaneactiviteit te verwijderen, kunnen de gebruikers de Ingenieur van de Verkoop in het platform van CRM efficiënter plaatsen.
* **E-maildienst**: Geniet betere leverbaarheid plus betere het Volgen van het Antwoord, Geplande E-mailfunctionaliteit, en bulke-mailfunctionaliteit door met [!DNL Microsoft Outlook] (of door Office365 of op-Prem door het lusje van de Verbinding E-mail) te verbinden.
* **Nieuwe Admin Montages**: Twee admin pagina&#39;s zijn toegevoegd om uw instantie van de Ingenieur van de Verkoop te optimaliseren

   * *Beheer van het Team* steunt een naadloos proces van de rekeningsopstelling door beheerders toe te staan om abonnementen en teams uit te geven.
   * *de Montages van Admin van Salesforce* hulp teams opstelling hun synchronisatie van SFDC sneller en gemakkelijker dan ooit voordien.

* **Insteekmodule OWA voor[!DNL Windows]**: Met één enkele toe:voegen-binnen, zullen alle [!DNL Windows Office365] cliënten in de Ingenieur van de Verkoop worden gesteund, die de capaciteit verstrekt om Levende Diervoeders in Vooruitzichten te gebruiken. De nieuwe insteekmodule is beschikbaar in de Microsoft Store.
* **Pusher van de Activiteiten**: De Ingenieur van de Verkoop van de synchronisatie aan het platform van kernMarketo aan hefboomwerking marketinginzichten in real time.

## [!DNL Marketo Sky] {#marketo-sky}

>[!NOTE]
>
>[!DNL Marketo Sky] wordt vaker afgespeeld. De volgende functies en verbeteringen zullen naar verwachting beschikbaar komen in het laatste kwartaal van 2004 en begin van het eerste kwartaal. Voor meer details en updates, controleer onze [ documentatie van het Lucht ](https://help.marketo.com/).

* **Facultatieve StandaardErvaring**: De gebruikers van Marketo kunnen [!DNL Marketo Sky] als hun standaardervaring plaatsen als zij toegang door Admin zijn verleend.

* **stelde Mijn Marketo** opnieuw voor: Pas uw ervaring aan door widgets toe te voegen die kritieke informatie, berichten, en verbindingen aan uw vaakst bezochte gebieden verstrekken.

* **de Mening van de Lijst van de Studio van het Ontwerp &amp; de Pagina&#39;s van het Detail**: Geniet van een verhoogd niveau van organisatie en nauwkeurigheid met filterbare en doorzoekbare lijstmeningen van e-mail, landende pagina&#39;s, en vormen. De Pagina&#39;s van het Detail van activa verstrekken zeer belangrijke informatie rond elk middel, met inbegrip van welke programma&#39;s het middel door wordt gebruikt, het aantal fragmenten die, en meer worden gebruikt.

* **Globaal Onderzoek**: Marketo biedt nu een snellere en robuustere globale onderzoeksfunctie over het platform aan. Zoekopdrachten worden nu uitgevoerd in alle toegankelijke werkruimten en kunnen bestanden (zowel actief als gearchiveerd), labels, campagnes en programma&#39;s zoeken. De zoekresultaten worden via een overlay geleverd en elk resultaat bevat het pad naar de bestandslocatie om aan te geven waar het element zich bevindt.

* **Verbeterd Gebruikersinterface**: De nieuwe pictogrammen, modals, en knopen, samen met een nieuw kleurenpalet om op ons merk te wijzen verfrissen zich en [!DNL Marketo Sky] nog verbluffender en functioneel maken.

* **Verbeteringen van de Gebruiksmogelijkheden van het E-mailProgramma**: Wij blijven naar pariteit in de functionaliteit van het E-mailProgramma tussen ons klassieke Marketo Lead Management platform en de nieuwe [!DNL Marketo Sky] ervaring bewegen.
* **gebeurtenis-met-Webinar Programma&#39;s**: Gebeurtenis-met-Webinar programma&#39;s zijn nu beschikbaar in [!DNL Marketo Sky] (nota: slechts zal GoToWebinar in deze versie, met verdere die integratie in tijd worden gevestigd) worden gesteund.

## Account-Based Marketing {#account-based-marketing}

**[ABM Persoonlijk-Gebaseerde Segmentatie &amp; het Filtreren](/help/marketo/product-docs/target-account-management/using-personas.md)**

Pas uw ABM-campagnes aan voor specifieke personen binnen benoemde accounts. Met de functie ABM Persona maakt u een standaardfunctie op basis van hoofdsegmentatie en kunt u aanvullende persoonlijke segmentaties configureren.

## Analytics {#analytics}

**[!DNL Bizible]**

* **Douane Berekende Gebieden**: Gebruik om het even welk [!DNL Bizible] attribuut om douanegebieden te bouwen die voor dashboard rapportering en segmentatie kunnen worden gebruikt.

* **SOC II Type II Certificatie**: De nieuwe veiligheid en privacycertificatie bouwt op Type I accreditatie van vroeger dit jaar voort.

## [!DNL Web Personalization] {#web-personalization}

**[voeg Subdomeinen in de Montages van de Rekening toe](/help/marketo/product-docs/web-personalization/getting-started/workspaces-in-web-personalization.md)**

Gebruikers kunnen nu subdomeinen toevoegen aan hun RTP-accountinstellingen om domeinen en subdomeinen efficiënter te beheren.

## Marketo Mobile Engagement (MME) {#marketo-mobile-engagement-mme}

**Bijgewerkte Kit van de Ontwikkeling van de Software MME (SDK) voor Android**

We hebben onze SDK for Android bijgewerkt naar een modern, stabiel en schaalbaar framework dat meer flexibiliteit en nieuwe technische functies bevat. Android app-ontwikkelaars kunnen nu direct het 0} Firebase Cloud Messaging [ (FCM) van Google gebruiken met deze nieuwe SDK.](https://firebase.google.com/docs/cloud-messaging/)

* [ instructies van de Ontwikkelaar ](https://developers.marketo.com/mobile/installation/#android_adding_fcm_to_your_application)
* [ Veelgestelde vragen van de Ontwikkelaar ](https://developers.marketo.com/mobile/installation/#android_fcm_faq)

>[!NOTE]
>
>De ontwikkelaars van de toepassing **moeten** aan de nieuwe versie vóór 31 Maart, 2019 bijwerken. Als u uw SDK niet uiterlijk op 31 maart 2019 hebt bijgewerkt, kunnen nieuwe gebruikers die uw app na deze datum downloaden, geen pushberichten ontvangen totdat u de nieuwste versie van de SDK hebt bijgewerkt. Voor de SDK-update is het niet nodig dat uw huidige gebruikers van de mobiele app een nieuwe versie van uw app opnieuw downloaden.

## Aanvullende updates {#additional-updates}

**Extensible Webinar Platform**

Naast onze productrelease werkt ons partnerteam aan een nieuw kader dat webinar leveranciers toestaat om hun eigen integraties met Marketo te bouwen en te handhaven, die meer flexibiliteit in het bijwerken en verbeteren van hun oplossingen verstrekken terwijl het toelaten van marketeers om het beste uit hun gekozen integraties te halen.

We zijn van plan om ons nieuwe platform per geval uit te rollen met aanbieders. Voor meer informatie, zie onze [ programmadetails ](https://www.marketo.com/why-marketo/partners/technology/) of reik uit aan uw contact van Marketo.
