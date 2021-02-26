---
unique-page-id: 17727823
description: Opmerkingen bij de release - Winter '19 - Marketo Docs - Productdocumentatie
title: Release-aantekeningen -Winter '19
translation-type: tm+mt
source-git-commit: b33f5ed707a1377daad51191cc6dd9f093138258
workflow-type: tm+mt
source-wordcount: '1109'
ht-degree: 0%

---


# Opmerkingen bij de release: Winter &#39;19 {#release-notes-winter}

De volgende functies zijn opgenomen in de release van Winter &#39;19. Controleer uw uitgave van de Marketo voor eigenschapbeschikbaarheid.

Klik op de titelkoppelingen om gedetailleerde artikelen voor elke functie weer te geven, indien beschikbaar.

>[!NOTE]
>
>Facebook heeft nu een Business Manager-account nodig om de integratie met het aangepaste publiek te kunnen benutten. Uw Facebook LaunchPoint-service *must* moet zijn gekoppeld aan een Business Manager-account, anders werkt uw integratie niet meer na 14 januari 2019 **.** Als u een Business Manager-account wilt instellen, raadpleegt u [Facebook Help](https://www.facebook.com/business/help/1710077379203657).

>[!NOTE]
>
>Microsoft duwt alle online klanten aan om aan de recentste versie van de Dynamica van Microsoft te bevorderen. Als u uw instantie van Marketo met Dynamica Online integreert, zult u aan [verbetering aan de recentste versie van de Oplossing van de Marketo ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/upgrade-the-marketo-solution-for-microsoft-dynamics.md) vóór **31 Januari, 2019** moeten verzekeren om ervoor te zorgen dat uw integratie zal blijven werken.

>[!NOTE]
>
>Marketo werkt aan een upgrade van de OAuth-versie voor GoToWebinar van 1.0 naar 2.0. De steun voor OAuth 1.0 wordt in januari 2019 afgekeurd. Als u een klant van GoToWebinar bent, zult u uw logins door LaunchPoint (in het Admin gebied) tegen **Januari 31, 2019** moeten opnieuw voor authentiek verklaren om ervoor te zorgen dat uw integratie zal blijven werken. Raadpleeg onze [Community-pagina](https://nation.marketo.com/docs/DOC-6739-gotowebinar-authentication-change-take-action-before-1312019) voor meer informatie.

## Verbeteringen voor kernPlatform {#core-platform-enhancements}

**[E-mail CC voor Marketo-e-mails](/help/marketo/product-docs/email-marketing/general/email-cc.md)**

Neem maximaal vijf CC-adressen per ontvanger op in e-mails die via Marketo worden verzonden.

**API**

* **Multi-Branding Domain Support for Asset API:** Goedkeuring en klonen van elementen leveren dezelfde resultaten op in de API en de UI.
* **E-mailCC-ondersteuning voor de API** voor middelen: Gebruikers die e-mailberichten klonen, goedkeuren en verwerken via de API, behouden de pariteit met de instellingen voor de gebruikersinterface.

**[Munchkin v155 (bèta)](https://developers.marketo.com/javascript-api/lead-tracking/configuration/)**

* **Modus** Alleen API: Gebruikers kunnen nu bepalen wanneer en hoe ze leden van hun database kunnen bijhouden door webapps van één pagina expliciet te laten bellen wanneer ze een bezoek aan een webpagina willen opnemen in plaats van te vertrouwen op de automatische tracering van Marketo.
* **Uitschakelen-beheer**: Beheer opt-outs eenvoudig door het uitschakelcookie-domein aan te passen aan het Cookie-domein van Munchkin.
* **Parameter** voor decider op domeinniveau: Domeinen met twee letters (d.w.z. &quot;  [website.io](https://website.io)&quot;) volgt automatisch Marketo zonder extra instellingsvereisten.

## Marketo Sales Engineering {#marketo-sales-engage}

* **Aangepast profiel** Salesforce: Verkoopservice biedt nu ondersteuning voor onbeperkte aangepaste profielen.

* **Aanpassing** Salesforce: Door niet-kritieke gebieden van de douaneactiviteit te verwijderen, kunnen de gebruikers de Ingenieur van de Verkoop in het platform van CRM efficiënter plaatsen.
* **E-mailservice**: Geniet van betere leverbaarheid plus verbeterde functionaliteit voor het bijhouden van antwoorden, geplande e-mailadressen en functies voor het bulkmail door verbinding te maken met Microsoft Outlook (via Office365 of On-Prem via het tabblad E-mailverbinding).
* **Nieuwe beheerinstellingen**: Er zijn twee beheerpagina&#39;s toegevoegd om uw exemplaar van Sales Engage te optimaliseren

   * _Teambeheer_ ondersteunt een naadloos proces voor het instellen van accounts door beheerders toe te staan abonnementen en teams te bewerken.
   * _Salesforce Admin_ Settingshelps-teams zetten hun SFDC-synchronisatie sneller en eenvoudiger dan ooit in.

* **OWA-insteekmodule voor Windows**: Met één enkele toe:voegen-binnen, zullen alle cliënten van Windows Office365 in de Ingenieur van de Verkoop worden gesteund, die de capaciteit verstrekken om Levende Diervoeders in Vooruitzichten te gebruiken. De nieuwe insteekmodule is beschikbaar in de Microsoft Store.
* **Activiteitenbuffer**: Synchroniseer Verkoopservice naar het core Marketo-platform om inzicht in real-time marketing te benutten.

## Marketo Sky {#marketo-sky}

>[!NOTE]
>
>Marketo Sky-releases komen vaker voor. De volgende functies en verbeteringen zullen naar verwachting beschikbaar komen in het laatste kwartaal van 2004 en begin van het eerste kwartaal. Raadpleeg onze [Sky-documentatie](https://help.marketo.com/) voor meer informatie en updates.

* **Optionele standaardervaring**: Marketo-gebruikers kunnen Marketo Sky instellen als hun standaardervaring als ze toegang hebben gekregen van een beheerder.

* **Mijn Marketo** is opnieuw in beeld gekomen: Pas uw ervaring aan door widgets toe te voegen die kritieke informatie, berichten en verbindingen aan uw vaakst bezochte gebieden verstrekken.

* **OntwerpStudio List Views &amp; Detail Pages**: Geniet van een hogere mate van organisatie en nauwkeurigheid met filterbare en doorzoekbare lijstweergaven van e-mails, landingspagina&#39;s en formulieren. De Pagina&#39;s van het Detail van activa verstrekken zeer belangrijke informatie rond elk middel, met inbegrip van welke programma&#39;s het middel door wordt gebruikt, het aantal fragmenten die, en meer worden gebruikt.

* **Globale zoekopdracht**: Marketo biedt nu een snellere en robuustere algemene zoekfunctie voor het hele platform. Zoekopdrachten worden nu uitgevoerd in alle toegankelijke werkruimten en kunnen bestanden (zowel actief als gearchiveerd), labels, campagnes en programma&#39;s zoeken. De zoekresultaten worden via een overlay geleverd en elk resultaat bevat het pad naar de bestandslocatie om aan te geven waar het element zich bevindt.

* **Verbeterde gebruikersinterface**: Nieuwe pictogrammen, modaliteiten en knoppen, samen met een nieuw kleurenpalet om onze merkvernieuwing te weerspiegelen en Marketo Sky nog verbluffender en functioneler te maken.

* **Verbeteringen** voor de bruikbaarheid van e-mailprogramma: We blijven streven naar pariteit in de functionaliteit van het e-mailprogramma tussen ons klassieke marktleidende managementplatform en de nieuwe Marketo Sky-ervaring.
* **Gebeurtenis-met-webinar programma&#39;s**: Gebeurtenis-met-webinar programma&#39;s zijn nu beschikbaar in Marketo Sky (opmerking: Alleen GoToWebinar wordt in deze release ondersteund, waarbij verdere integratie in de loop der tijd tot stand is gebracht.)

## Op account gebaseerde marketing {#account-based-marketing}

**[Segmentering en filteren op basis van ABM Persona](/help/marketo/product-docs/account-based-marketing/using-personas.md)**

Pas uw ABM-campagnes aan voor specifieke personen binnen benoemde accounts. Met de functie ABM Persona maakt u een standaardfunctie op basis van hoofdsegmentatie en kunt u aanvullende persoonlijke segmentaties configureren.

## Analyse {#analytics}

**Bizible**

* **Aangepaste berekende velden**: Gebruik een Bizible-kenmerk om aangepaste velden te maken die kunnen worden gebruikt voor dashboard-rapportage en -segmentatie.

* **SOC II Type II-certificering**: De nieuwe beveiligings- en privacycertificering is gebaseerd op de accreditatie van type I die eerder dit jaar is ingevoerd.

## Webpersonalisatie {#web-personalization}

**[Subdomeinen toevoegen aan accountinstellingen](/help/marketo/product-docs/web-personalization/getting-started/workspaces-in-web-personalization.md)**

Gebruikers kunnen nu subdomeinen toevoegen aan hun RTP-accountinstellingen om domeinen en subdomeinen efficiënter te beheren.

## Marketo Mobile Engagement (MME) {#marketo-mobile-engagement-mme}

**Bijgewerkte MME Software Development Kit (SDK) voor Android**

We hebben onze SDK voor Android bijgewerkt naar een modern, stabiel en schaalbaar framework dat meer flexibiliteit en nieuwe technische functies bevat. Ontwikkelaars van Android-apps kunnen nu direct gebruikmaken van het [Firebase Cloud Messaging](https://firebase.google.com/docs/cloud-messaging/) (FCM) van Google met deze nieuwe SDK.

* [Instructies voor ontwikkelaars](https://developers.marketo.com/mobile/installation/#android_adding_fcm_to_your_application)
* [Veelgestelde vragen over ontwikkelaars](https://developers.marketo.com/mobile/installation/#android_fcm_faq)

>[!NOTE]
>
>App-ontwikkelaars **must** moeten een update naar de nieuwe versie uitvoeren vóór 31 maart 2019. Als u de SDK niet uiterlijk op 31 maart 2019 hebt bijgewerkt, kunnen nieuwe gebruikers die uw app na deze datum downloaden, geen pushmeldingen ontvangen totdat u de nieuwste versie van de SDK hebt bijgewerkt. De SDK-update vereist niet dat uw huidige gebruikers van de mobiele app een nieuwe versie van uw app opnieuw downloaden.

## Aanvullende updates {#additional-updates}

**Extensible Webinar Platform**

Naast onze productrelease werkt ons partnerteam aan een nieuw kader dat webinar leveranciers toestaat om hun eigen integratie met Marketo te bouwen en te handhaven, die meer flexibiliteit in het bijwerken en verbeteren van hun oplossingen verstrekken terwijl het toelaten van marketeers om het beste uit hun gekozen integratie te halen.

We zijn van plan om ons nieuwe platform per geval uit te rollen met aanbieders. Voor meer informatie, zie onze [programmadetails](https://www.marketo.com/why-marketo/partners/technology/) of reik uit aan uw contact van de Marketo.
