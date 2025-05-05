---
unique-page-id: 17727823
description: Opmerkingen bij de release - Winter '19 - Marketo Docs - Productdocumentatie
title: Release-aantekeningen -Winter '19
exl-id: 0cb3b3a1-472e-41d4-84f4-47f06e65017c
feature: Release Information
source-git-commit: 2b610cc3486b745212b0b1f36018a83214d7ecd7
workflow-type: tm+mt
source-wordcount: '1079'
ht-degree: 0%

---

# Opmerkingen bij de release: Winter &#39;19 {#release-notes-winter}

De volgende functies zijn opgenomen in de release van Winter &#39;19. Raadpleeg de Marketo-editie voor informatie over de beschikbaarheid van functies.

Klik op de titelkoppelingen om gedetailleerde artikelen voor elke functie weer te geven, indien beschikbaar.

>[!NOTE]
>
>Facebook heeft nu een Business Manager-account nodig om de integratie met het aangepaste publiek te kunnen benutten. Uw Facebook-startpunt *moet* zijn gekoppeld aan een Business Manager-account of **uw integratie werkt niet meer na 14 januari 2019**. Als u een Business Manager-account wilt instellen, raadpleegt u [Facebook Help](https://www.facebook.com/business/help/1710077379203657).

>[!NOTE]
>
>Microsoft dringt er bij alle online klanten op aan een upgrade uit te voeren naar de nieuwste versie van Microsoft Dynamics. Als u uw Marketo-instantie integreert met Dynamics Online, moet u [upgrade naar de nieuwste versie van de Marketo Solution](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/update-the-marketo-solution-for-microsoft-dynamics.md) voor **31 januari 2019** om ervoor te zorgen dat uw integratie blijft werken.

>[!NOTE]
>
>Marketo voert een upgrade uit van de OAuth-versie voor GoToWebinar van 1.0 naar 2.0. De steun voor OAuth 1.0 wordt in januari 2019 afgekeurd. Als u een klant van GoToWebinar bent, zult u uw logins door LaunchPoint (in het Admin gebied) opnieuw moeten verifiëren door **31 januari 2019** om ervoor te zorgen dat uw integratie blijft werken. Voor meer informatie raadpleegt u onze [Communautaire pagina](https://nation.marketo.com/docs/DOC-6739-gotowebinar-authentication-change-take-action-before-1312019).

## Verbeteringen voor kernplatform {#core-platform-enhancements}

**[E-mail CC voor Marketo-e-mails](/help/marketo/product-docs/email-marketing/general/email-cc.md)**

Neem maximaal vijf CC-adressen per ontvanger op in e-mails die via Marketo worden verzonden.

**API**

* **Ondersteuning voor multi-branding-domeinen voor Asset API:** Het goedkeuren en klonen van elementen levert dezelfde resultaten op in de API en de gebruikersinterface.
* **E-mailCC-ondersteuning voor de API voor middelen**: Gebruikers die e-mailberichten klonen, goedkeuren en verwerken via de API, behouden de pariteit met de instellingen voor de gebruikersinterface.

**[Munchkin v155 (bèta)](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/javascriptapi/lead-tracking)**

* **Modus Alleen-API**: Gebruikers kunnen nu bepalen wanneer en hoe ze leden van hun database kunnen bijhouden door webapps van één pagina expliciet te laten bellen wanneer ze een bezoek aan een webpagina willen opnemen in plaats van te vertrouwen op automatische tracering door Marketo.
* **Uitschakelen van beheer**: Beheer opt-outs eenvoudig door het uitschakelcookie-domein aan te passen aan het Cookie-domein van Munchkin.
* **Decider-parameter op domeinniveau**: domeinen met twee letters (d.w.z. &quot; [website.io](https://website.io)&quot;) wordt automatisch bijgehouden in Marketo zonder extra instellingsvereisten.

## Marketo Sales Engage {#marketo-sales-engage}

* **Aangepast profiel Salesforce**: Verkoopservice biedt nu ondersteuning voor onbeperkte aangepaste profielen.

* **Aanpassing Salesforce**: Door niet-kritieke velden voor aangepaste activiteiten te verwijderen, kunnen gebruikers verkoopengine op een efficiëntere manier instellen op het CRM-platform.
* **Email Service**: Geniet van betere leverbaarheid plus verbeterde functionaliteit voor het bijhouden van antwoorden, geplande e-mailadressen en functies voor bulkmail door verbinding te maken met Microsoft Outlook (via Office365 of On-Prem via het tabblad E-mailverbinding).
* **Nieuwe beheerinstellingen**: Er zijn twee beheerpagina&#39;s toegevoegd om uw exemplaar van Sales Engage te optimaliseren

   * _Teambeheer_ ondersteunt een naadloos proces voor het instellen van accounts door beheerders toe te staan abonnementen en teams te bewerken.
   * _Salesforce-beheerinstellingen_ helpt teams hun SFDC-synchronisatie sneller en eenvoudiger dan ooit in te stellen.

* **OWA-insteekmodule voor Windows**: Met één enkele toe:voegen-binnen, zullen alle cliënten van Windows Office365 in de Ingenieur van de Verkoop worden gesteund, die de capaciteit verstrekken om Levende Diervoeders in Vooruitzichten te gebruiken. De nieuwe insteekmodule is beschikbaar in de Microsoft Store.
* **Activiteitenduwster**: Synchroniseer verkoopmogelijkheden met het belangrijkste Marketo-platform om inzicht in real-time marketing te benutten.

## Marketo Sky {#marketo-sky}

>[!NOTE]
>
>Marketo Sky-releases komen vaker voor. De volgende functies en verbeteringen zullen naar verwachting beschikbaar komen in het laatste kwartaal van 2004 en begin van het eerste kwartaal. Raadpleeg onze voor meer informatie en updates [Sky-documentatie](https://help.marketo.com/).

* **Optionele standaardervaring**: Marketo-gebruikers kunnen Marketo Sky instellen als hun standaardervaring als ze toegang hebben gekregen van een beheerder.

* **Mijn Marketo opnieuw bekeken**: Pas uw ervaring aan door widgets toe te voegen die kritieke informatie, meldingen en koppelingen naar de meest bezochte gebieden bieden.

* **OntwerpStudio List Views &amp; Detail Pages**: Geniet van een hogere mate van organisatie en nauwkeurigheid met filterbare en doorzoekbare lijstweergaven van e-mails, landingspagina&#39;s en formulieren. De Pagina&#39;s van het Detail van activa verstrekken zeer belangrijke informatie rond elk middel, met inbegrip van welke programma&#39;s het middel door wordt gebruikt, het aantal fragmenten die, en meer worden gebruikt.

* **Globaal zoeken**: Marketo biedt nu een snellere en robuustere wereldwijde zoekfunctie voor het hele platform. Zoekopdrachten worden nu uitgevoerd in alle toegankelijke werkruimten en kunnen bestanden (zowel actief als gearchiveerd), labels, campagnes en programma&#39;s zoeken. De zoekresultaten worden via een overlay geleverd en elk resultaat bevat het pad naar de bestandslocatie om aan te geven waar het element zich bevindt.

* **Verbeterde gebruikersinterface**: Nieuwe pictogrammen, modaliteiten en knoppen, samen met een nieuw kleurenpalet om onze merkvernieuwing te weerspiegelen en Marketo Sky nog verbluffender en functioneler te maken.

* **Verbeterde bruikbaarheid e-mailprogramma**: We blijven streven naar pariteit in de functionaliteit van het e-mailprogramma tussen ons klassieke Marketo Lead Management-platform en de nieuwe Marketo Sky-ervaring.
* **Gebeurtenis-met-webinar programma&#39;s**: Gebeurtenis-met-webinar programma&#39;s zijn nu beschikbaar in Marketo Sky (Opmerking: alleen GoToWebinar wordt ondersteund in deze release, met verdere integratie die in de loop der tijd tot stand is gebracht).

## Account-Based Marketing {#account-based-marketing}

**[Segmentering en filteren op basis van ABM Persona](/help/marketo/product-docs/target-account-management/using-personas.md)**

Pas uw ABM-campagnes aan voor specifieke personen binnen benoemde accounts. Met de functie ABM Persona maakt u een standaardfunctie op basis van hoofdsegmentatie en kunt u aanvullende persoonlijke segmentaties configureren.

## Analyse {#analytics}

**Bizible**

* **Aangepaste berekende velden**: Gebruik een Bizible-kenmerk om aangepaste velden te maken die kunnen worden gebruikt voor dashboard-rapportage en -segmentatie.

* **SOC II Type II-certificering**: Nieuwe beveiligings- en privacycertificering is gebaseerd op de accreditatie van type I van eerder dit jaar.

## Webpersonalisatie {#web-personalization}

**[Subdomeinen toevoegen aan accountinstellingen](/help/marketo/product-docs/web-personalization/getting-started/workspaces-in-web-personalization.md)**

Gebruikers kunnen nu subdomeinen toevoegen aan hun RTP-accountinstellingen om domeinen en subdomeinen efficiënter te beheren.

## Marketo Mobile Engagement (MME) {#marketo-mobile-engagement-mme}

**Bijgewerkte MME Software Development Kit (SDK) voor Android**

We hebben onze SDK voor Android bijgewerkt naar een modern, stabiel en schaalbaar framework dat meer flexibiliteit en nieuwe technische functies bevat. Ontwikkelaars van Android-apps kunnen nu direct Google gebruiken [Firebase Cloud Messaging](https://firebase.google.com/docs/cloud-messaging/) (FCM) met deze nieuwe SDK.

* [Instructies voor ontwikkelaars]https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/mobile/installation#how-to-install-marketo-sdk-on-android)

>[!NOTE]
>
>App-ontwikkelaars **moet** een update naar de nieuwe versie vóór 31 maart 2019. Als u de SDK niet uiterlijk op 31 maart 2019 hebt bijgewerkt, kunnen nieuwe gebruikers die uw app na deze datum downloaden, geen pushmeldingen ontvangen totdat u de nieuwste versie van de SDK hebt bijgewerkt. De SDK-update vereist niet dat uw huidige gebruikers van de mobiele app een nieuwe versie van uw app opnieuw downloaden.

## Aanvullende updates {#additional-updates}

**Extensible Webinar Platform**

Naast onze productrelease werkt ons partnerteam aan een nieuw kader dat webinar leveranciers toestaat om hun eigen integraties met Marketo te bouwen en te handhaven, die meer flexibiliteit in het bijwerken en verbeteren van hun oplossingen verstrekken terwijl het toelaten van marketeers om het beste uit hun gekozen integraties te halen.

We zijn van plan om ons nieuwe platform per geval uit te rollen met aanbieders. Voor meer informatie raadpleegt u onze [programmatiedetails](https://www.marketo.com/why-marketo/partners/technology/) of neem contact op met je Marketo-contactpersoon.
