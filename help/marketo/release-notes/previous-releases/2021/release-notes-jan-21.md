---
description: Opmerkingen bij de release - jan 2021 - Marketo Docs - Productdocumentatie
title: Opmerkingen bij de release - jan 2021
exl-id: 24a5f955-ef4b-4adf-9478-2653db6f9d79
feature: Release Information
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '1268'
ht-degree: 0%

---

# Opmerkingen bij de release: 2021 jan. {#release-notes-jan-21}

De volgende functies zijn opgenomen in de release van 21 januari. Raadpleeg de Marketo-editie voor informatie over de beschikbaarheid van functies.

>[!AVAILABILITY]
>
>Kenmerken die door een ster worden aangeduid (![(ster)](assets/yellow-star.png)) worden betaald als extra&#39;s. Neem contact op met uw Marketo Engage-vertegenwoordiger voor meer informatie.

**_Kwartaalreleases_**

De volgende functies worden vrijgegeven op **15 januari 2021**.

## Ervaring voor gebruikers van de volgende generatie {#next-generation-user-experience}

* Ondersteuning voor werkruimten: De Marketo Engage-gebruikerservaring van de volgende generatie combineert het uiterlijk van Adobe Experience Cloud met productiviteitsinnovaties om marketingmensen te helpen sneller en slimmer te werken. In de meest recente versie, voegen wij volledige steun voor werkruimten en verdelingen, met inbegrip van de capaciteit toe om omslagen over werkruimten te delen. Het rechtercanvas biedt een schakeloptie waarmee u probleemloos kunt overschakelen tussen oude en nieuwe ervaringen per functie zonder dat de context verloren gaat. [Meer informatie](https://nation.marketo.com/t5/The-modern-ux/modern-ux-FAQ/ba-p/307124) van de volgende-generatieervaring FAQ op Marketing Nation.

## Multi-Channel personalisatie {#multi-channel-personalization}

* **[Adobe Experience Cloud Audience Sync Fase 3](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/static-lists/send-a-list-to-adobe-experience-cloud.md)**: De bestaande Adobe Experience Cloud (AEC) Audience Sync mogelijkheden bieden nu ondersteuning voor continue, bidirectionele B2B-publiekssynchronisatie van Marketo Engage naar andere AEC-toepassingen, waaronder Adobe Experience Platform (AEP)-aanbiedingen zoals Real-time Customer Data Platform en Adobe Experience Platform Activation.  Als leads worden toegevoegd en verwijderd naar uw publiekssegmenten, synchroniseert Marketo Engage automatisch het bijgewerkte publiek in uw verbonden AEC-apps. Gebruik dit programma om te profiteren van de meerkanaals orchestratie van Adobe, heroriëntering, onderdrukking van het publiek, personalisatie en rapportering van gebruiksgevallen in uw AEC-technische stack.
* **[Continuous Audience Sync to Google, Facebook, and LinkedIn](/help/marketo/product-docs/demand-generation/ad-network-integrations/send-a-list-to-an-ad-network.md)**: Doorlopend geautomatiseerde synchronisatie met een advertentienetwerk kan op een statische lijst worden toegelaten, bijwerkt het advertentienetwerk aangezien de veranderingen van het lijstlidmaatschap zonder gebruikersinterventie vereisen.
* **[Tokens voor aangepaste velden voor programmaleden](/help/marketo/product-docs/core-marketo-concepts/programs/tokens/program-member-custom-field-tokens.md)**: Wij hebben de eigenschappen van het programmalid van het douanegebied uitgebreid om het symbolische kader te steunen. Marketers kunnen tokens voor aangepaste velden voor programmaleden invoegen in e-mails, bestemmingspagina&#39;s, SMS-berichten, pushberichten en webhaken. Gebruik nieuwe tokens in de acties van de campagnestroom om gegevenswaarden te veranderen, een taak, of een interessant moment tot stand te brengen.

## Openingspagina&#39;s en Forms {#landing-pages-and-forms}

* **Formulier-API**: Trek informatie over lood in of activeer de aanplant terwijl u gegevens uit niet-Marketo-formulieren haalt. Niet-Marketo-formulieren kunnen met Marketo Engage worden geïntegreerd via REST API. De nieuwe API biedt de mogelijkheid om het verzenden van Marketo Engage-formulieren te simuleren met alle bijbehorende functies.
* **Openingspagina&#39;s-API**: Workflows voor bewerken en vertalen stroomlijnen in geïntegreerde toepassingen met de nieuwe API voor het voorvertonen van landingspagina. Externe leveranciers kunnen nu volledig persoonlijke voorvertoningen van bestemmingspagina&#39;s weergeven zonder zich aan te melden bij Marketo Engage.  Met de API voor het voorvertonen van landingspagina kunt u end-to-end bewerkings- en lokalisatieworkflows in geïntegreerde toepassingen van derden inschakelen.

## E-mailmarketing {#email-marketing}

* **[Ophaallimieten voor aangepaste objecten verhoogd](/help/marketo/product-docs/administration/email-setup/change-custom-object-retrieval-limits-in-velocity-scripting.md)**: Ontwikkelaars van scripts voor e-mailsnelheid kunnen het aantal aangepaste objecten snel verhogen tot 100 door deze te overschrijven. Marketers kunnen de doeltreffendheid van slimme campagnes verhogen door tot een groter aantal eerste en tweede niveaudouanevoorwerpen toegang te hebben.

## Integratie van Salesforce CRM {#salesforce-crm-integration}

* [Salesforce CRM-verificatie](/help/marketo/product-docs/crm-sync/salesforce-sync/log-in-using-oauth-2-0.md): Het protocol van OAuth 2.0 is beschikbaar voor het synchroniseren van verrichtingen tussen Marketo Engage en Salesforce CRM. Voor nieuwe abonnees is deze optie standaard ingeschakeld. Huidige abonnees kunnen deze functie aanvragen via Marketo Support.
* [Salesforce CRM-synchronisatiedashboard](/help/marketo/product-docs/crm-sync/salesforce-sync/salesforce-sync-errors.md): Beheerders kunnen de synchronisatiestatus van Salesforce CRM snel controleren vanaf het dashboard. De tijdsduur van het synchronisatierapport is verhoogd van 2 uur tot 5 dagen.
* **Metagegevens exporteren**: Verbeterd voor ondersteuning van opportuntobjectkenmerken, benoemde accounts, de standaard- en aangepaste velden van het programmalid.

## Beheer {#administration}

* **Pagina Mijn account is bijgewerkt**: Bekijk essentiële abonnementsgegevens op de pagina Mijn account. Gebruikers met elk toegangsniveau kunnen de abonnementsnaam, de datacenteridentificatie en de Munchkin-id bekijken.

**_Vrijgeven door het Kwartaal_**

De volgende functies bevinden zich op een niet-driemaandelijkse cyclus en worden de komende maanden vrijgegeven.

## Verkoopoverzicht {#sales-insight}

![(ster)](assets/yellow-star.png)

* **[Verbeterde e-mailworkflows voor tests (Salesforce CRM)](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/actions-in-the-msi-panel/send-marketo-email/send-a-test-email.md)**: Verhoog de efficiëntie van uw verkoopteam met de verbeterde e-mailworkflows voor het testen van het verkoopinzicht. Verkopers kunnen teste-mails naar gekozen e-mailadressen verzenden voordat ze bulksgewijze e-mails naar maximaal 200 ontvangers verzenden.
* **[Inzichten in e-mailstatus (Salesforce CRM)](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/tabs-in-the-msi-panel/email-tab.md)**: Gebruikers zien een waarschuwingsbericht wanneer ze een e-mail proberen te verzenden naar een ongeldige e-mail-id of een niet-geabonneerd e-mailadres voordat ze een e-mail verzenden.  De leveringsstatus van e-mails kan worden gecontroleerd op het tabblad E-mail van Verkoopoverzicht.
* **Bulke-mails verzenden vanuit [Account](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/msi-feature-overview.md#account-layout) en [Opportunity](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/msi-feature-overview.md#opportunity-layout) Deelvensters (Salesforce CRM)**: Verbeter de efficiëntie van de workflow van de verkoper en neem contact op met een volledige account of lijst met opportuniteitscontactpersonen door nieuwe functies voor bulkacties te gebruiken. Verzend e-mails of voeg contacten aan Marketo Engage campagnes toe door de nieuwe drop-down optie in de rekening of opportuniteitslusjes in plaats van het werken met individuele contacten te gebruiken. Voeg accountcontactpersonen toe aan een lijst met wachtwoorden die u wilt waarschuwen wanneer leads hot worden.
* **[Verkoopoverzicht voor niet-native integratie van Salesforce CRM](/help/marketo/product-docs/marketo-sales-insight/sales-insight-for-non-native-salesforce-integrations.md)**: GA-abonnementen met aangepaste integratie van Salesforce CRM kunnen het Sales Insight-pakket installeren en verkoopteams helpen bij het bepalen van prioriteiten en het communiceren met de meest veelbelovende mogelijkheden en mogelijkheden.
* **[Verbeteringen voor beste beets](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/marketo-tab/best-bets.md)**: Neem via het tabblad Best Bets snel contact op met hot leads door deze te e-mailen of toe te voegen aan een Marketo Engage-campagne. Geef een lead weer in Marketo Engage of voeg deze toe aan uw controlelijst. Bulkacties en sorteeropties op het tabblad Best Bets besparen tijd en verbeteren de efficiëntie van het verkoopteam.

## Verkoop Connect {#sales-connect}

![(ster)](assets/yellow-star.png)

* **E-mailverbindingsThrottling (BETA)**: Verbeter uw e-mailprestaties en schaalt uw 1:1-verkoopcommunicatie met de Throttling van de E-mailverbinding voor Sales Connect. Met onze nieuwe vertragingstechnologie wordt het verzenden van e-mail automatisch beheerd, zodat Exchange- en Gmail-gebruikers probleemloos kunnen genieten van hun ervaringen. Verlaag of elimineer het gebruik van externe toepassingen voor het verzenden van grote hoeveelheden e-mail.
* **Bounce voor e-mailverbinding bijhouden**: Bekijk meer inzicht in de kwaliteit van leads en de prestaties van e-mailsjablonen met het nieuwe e-mailstuitrapport. Gebruikers van Exchange en Gmail kunnen ervoor kiezen om stuiteringsberichten te ontvangen die worden weergegeven bij Live Feed, E-mailmappen, Sjabloonanalyse en Campagneanalyse.
* **Configuratie van profielpagina**: Beheer gebruikersvoorkeuren eenvoudig in de nieuwe profielpagina. Wijzig het wachtwoord, bewerk de instellingen voor geolocatie en taal en bekijk de integratiestatus op één locatie.
* **Sjabloonbeheer**: U kunt e-mailsjablonen voor verkoop indelen in categorieën met een nieuwe functie voor slepen en neerzetten, zodat u snel toegang hebt tot relevante sjablonen en de zoektijd verkort.
* **Updates voor Connect-gebruikers**: Pas de lay-out van het raster Verkoop aan door kolommen te vergroten of te verkleinen en opnieuw te ordenen. Uw weergavevoorkeuren worden automatisch opgeslagen.

**_Aankondigingen en afwaarderingen_**

* Alle gebruikers moeten aan de recentste versie van het Inzicht van de Verkoop bevorderen **vóór 15 januari 2021**. Als u de upgrade niet hebt voltooid, wordt u gevraagd dit te doen wanneer u zich aanmeldt bij de toepassing. Volg de instructies [in deze handleiding](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/upgrading/upgrading-your-msi-package.md). De bijgewerkte versie bevat een patch voor een geïdentificeerde beveiligingskwetsbaarheid. De pleister werd oorspronkelijk vrijgegeven op 6 april 2016. Opmerking: **Versies 1.4363 of hoger** hoeft geen upgrade uit te voeren.
* De service Veroudering van formulier 1.0 gaat in **mei 2021** vrijgeven. De Forms 1.0-service wordt volledig afgekeurd, waardoor de functionaliteit van alle resterende Forms 1.0-middelen die nog in gebruik zijn, verloren gaat. Ook formulierverzendingen die zijn ingediend via niet-ondersteunde methoden, zoals POST&#39;s met programmatische formulieren voor de eindpunten leadCapture/save en leadCapture/save2, worden afgewezen. Raadpleeg voor meer informatie en herstel [Ons bericht in Marketing Nation](https://nation.marketo.com/t5/Product-Documents/Upcoming-Changes-to-the-Marketo-Engage-Form-Platform/ta-p/306631).
* In 2021 brengt Marketo Engage wijzigingen aan in de URL-structuur voor het plaatsen van pagina&#39;s, formulieren en afbeeldingen en bestanden. Voor bestaande Marketo Engage-abonnementen beginnen we op 1 april 2021 met de geleidelijke invoering. Meer informatie over het tijdschema voor de uitrol wordt in maart 2021 gepubliceerd. Zie voor meer informatie over de manier waarop elk betrokken elementtype wordt gewijzigd [Ons bericht in Marketing Nation](https://nation.marketo.com/t5/Product-Documents/Upcoming-Changes-to-Design-Studio-URLs/ta-p/306632).

**_Webinar productrelease_**

Wilt u meer weten over deze functies en verbeteringen? Zorg ervoor dat u [nu registreren](https://engage.marketo.com/January_21_Release_Webinar_Registration.html) om op 21 januari om 13:00 uur PT / 4:00 uur Midden-Europese tijd met ons mee te doen voor een live webinar met ons productteam om deze innovaties dieper te bestuderen.
