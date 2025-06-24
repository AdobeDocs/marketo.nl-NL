---
description: Opmerkingen bij de release - jan 2021 - Marketo Docs - Productdocumentatie
title: Opmerkingen bij de release - jan 2021
exl-id: 24a5f955-ef4b-4adf-9478-2653db6f9d79
feature: Release Information
source-git-commit: ecd225af3ecfd7cb9159faf5a9d384d47ee6312c
workflow-type: tm+mt
source-wordcount: '1234'
ht-degree: 0%

---

# Opmerkingen bij de release: jan 2021 {#release-notes-jan-21}

De volgende functies zijn opgenomen in de release van 21 januari. Raadpleeg de Marketo-editie voor informatie over de beschikbaarheid van functies.

>[!AVAILABILITY]
>
>De eigenschappen die door een ster (![ worden aangegeven (ster) ](assets/yellow-star.png)) worden betaald toe:voegen-ons. Neem contact op met je Marketo Engage-vertegenwoordiger voor meer informatie.

**_Kwartaalversies_**

De volgende eigenschappen zullen op **Januari 15, 2021** worden vrijgegeven.

## Ervaring voor nieuwe gebruikers {#next-generation-user-experience}

* Ondersteuning voor Workspaces: de Marketo Engage-gebruikerservaring van de volgende generatie brengt het uiterlijk van Adobe Experience Cloud samen met productiviteitsvernieuwingen om marketingmensen te helpen sneller en slimmer te werken. In de meest recente versie, voegen wij volledige steun voor werkruimten en verdelingen, met inbegrip van de capaciteit toe om omslagen over werkruimten te delen. Het rechtercanvas biedt een schakeloptie waarmee u probleemloos kunt overschakelen tussen oude en nieuwe ervaringen per functie zonder dat de context verloren gaat. [ leer meer ](https://nation.marketo.com/t5/The-modern-ux/modern-ux-FAQ/ba-p/307124) van de volgende-generatieervaring FAQ op de Marketing Natie.

## Multi-Channel Personalization {#multi-channel-personalization}

* **[Fase 3 van de Synchronisatie van de Audience van Adobe Experience Cloud](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/static-lists/send-a-list-to-adobe-experience-cloud.md)**: Het bestaande vermogen van de Synchronisatie van het publiek van Adobe Experience Cloud (AEC) steunt nu ononderbroken, bidirectionele B2B publiekssynchronisatie van Marketo Engage aan andere toepassingen AEC, met inbegrip van Adobe Experience Platform (AEP) dienstenaanbod zoals het Platform van de Gegevens van de Klant in real time en de Activering van Adobe Experience Platform.  Als leads worden toegevoegd en verwijderd naar uw publiekssegmenten, synchroniseert Marketo Engage automatisch het bijgewerkte publiek in uw verbonden AEC-apps. Gebruik dit programma om te profiteren van de meerkanaals orchestratie, heroriëntering, onderdrukking van het publiek, personalisatie en rapportering van gebruiksgevallen in uw AEC-technologiestack.
* **[Ononderbroken Synchronisatie van het publiek aan Google,  [!DNL Facebook], en [!DNL LinkedIn]](/help/marketo/product-docs/demand-generation/ad-network-integrations/send-a-list-to-an-ad-network.md)**: Ononderbroken geautomatiseerde synchronisatie met een advertentienetwerk kan op een statische lijst worden toegelaten, die het advertentienetwerk bijwerken aangezien de veranderingen van het lijstlidmaatschap zonder gebruikersinterventie te vereisen.
* **[Tokens voor de Gebieden van de Douane van het Lid van het Programma](/help/marketo/product-docs/core-marketo-concepts/programs/tokens/program-member-custom-field-tokens.md)**: Wij hebben de eigenschappen van het de gebiedsgebied van het programmalid uitgebreid om het symbolische kader te steunen. Marketers kunnen tokens voor aangepaste velden voor programmaleden invoegen in e-mails, bestemmingspagina&#39;s, SMS-berichten, pushberichten en webhaken. Gebruik nieuwe tokens in de acties van de campagnestroom om gegevenswaarden te veranderen, een taak, of een interessant moment tot stand te brengen.

## Openingspagina&#39;s en Forms {#landing-pages-and-forms}

* **Vorm API**: Trek in loodinformatie of trekkercampagnes terwijl het trekken van gegevens uit niet-Marketo vormen. Niet-Marketo-formulieren kunnen met Marketo Engage worden geïntegreerd via REST API. De nieuwe API biedt de mogelijkheid om Marketo Engage-formulierverzendingen na te bootsen met alle bijbehorende functies.
* **het Bestaan Pagina&#39;s API**: Het stroomlijnen het uitgeven en vertaalwerkschema&#39;s in geïntegreerde toepassingen met nieuwe het Landing API van de Voorproef van de Pagina. Externe leveranciers kunnen nu volledig persoonlijke voorvertoningen van bestemmingspagina&#39;s weergeven zonder zich aan te melden bij Marketo Engage.  Met de API voor het voorvertonen van landingspagina kunt u end-to-end bewerkings- en lokalisatieworkflows in geïntegreerde toepassingen van derden inschakelen.

## E-mailmarketing {#email-marketing}

* **[Verhoogde Beperkingen van de Terugwinning van Objecten van de Douane van de Objecten van de Douane](/help/marketo/product-docs/administration/email-setup/change-custom-object-retrieval-limits-in-velocity-scripting.md)**: De ontwikkelaars van Scripting van de Snelheid E-mail kunnen snel het aantal douanevoorwerpen aan 100 door zelfserveropheffing verhogen. Marketers kunnen de doeltreffendheid van slimme campagnes verhogen door tot een groter aantal eerste en tweede niveaudouanevoorwerpen toegang te hebben.

## [!DNL Salesforce] CRM-integratie {#salesforce-crm-integration}

* [[!DNL Salesforce]  Authentificatie van CRM ](/help/marketo/product-docs/crm-sync/salesforce-sync/log-in-using-oauth-2-0.md): Het protocol van OAuth 2.0 is beschikbaar voor het synchroniseren van verrichtingen tussen Marketo Engage en [!DNL Salesforce] CRM. Voor nieuwe abonnees is deze optie standaard ingeschakeld. Huidige abonnees kunnen deze functie aanvragen via Marketo Support.
* [[!DNL Salesforce]  CRM die Dashboard ](/help/marketo/product-docs/crm-sync/salesforce-sync/salesforce-sync-errors.md) synchroniseert: Admins kan [!DNL Salesforce] de synchronisatiestatus van CRM van het dashboard snel herzien. De tijdsduur van het synchronisatierapport is verhoogd van 2 uur tot 5 dagen.
* **de Uitvoer van Meta-gegevens**: Verbeterd om opportuntobjecten attributen, genoemde rekeningen, de standaard van het programmalid en douanegebieden te steunen.

## Beheer {#administration}

* **werkte Mijn Pagina van de Rekening** bij: Herzie essentiële abonnementsinformatie over de Mijn pagina van de Rekening. Gebruikers met elk toegangsniveau kunnen de abonnementsnaam, de datacenteridentificatie en de [!DNL Munchkin] -id weergeven.

**_vrijstellend door het Kwartaal_**

De volgende functies bevinden zich op een niet-driemaandelijkse cyclus en worden de komende maanden vrijgegeven.

## [!DNL Sales Insight] {#sales-insight}

![ (star) ](assets/yellow-star.png)

* **[Verbeterde de Werkschema&#39;s van e-mail van de Test ([!DNL Salesforce] CRM)](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/actions-in-the-msi-panel/send-marketo-email/send-a-test-email.md)**: Verhoog de efficiency van uw verkoopteam met verbeterde [!DNL Sales Insight] werkschema&#39;s van de teste-mail. Verkopers kunnen teste-mails naar gekozen e-mailadressen verzenden voordat ze bulksgewijze e-mails naar maximaal 200 ontvangers verzenden.
* **[Inzichten in E-mailstatus ([!DNL Salesforce] CRM)](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/tabs-in-the-msi-panel/email-tab.md)**: De gebruikers zien een waarschuwingsbericht wanneer zij proberen om een e-mail naar een ongeldige e-mailidentiteitskaart of een unsubscribed e-mailadres te verzenden alvorens een e-mail te verzenden.  De leveringsstatus van e-mails kan worden gecontroleerd op het tabblad E-mail van [!DNL Sales Insight] .
* **verzend Bulk E-mail van [ Rekening ](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/msi-feature-overview.md#account-layout) en [ 4&rbrace; panelen van de Kans ([!DNL Salesforce] CRM)**: Verbeter de efficiency van het werkschema van de verkoper en verbind met een volledige rekening of lijst van het opportuniteitcontact door nieuwe bulkactiefuncties te gebruiken. ](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/msi-feature-overview.md#opportunity-layout) Verzend e-mails of voeg contacten aan de campagnes van Marketo Engage toe door de nieuwe drop-down optie op de rekening of opportuniteits lusjes in plaats van het werken met individuele contacten te gebruiken. Voeg accountcontactpersonen toe aan een lijst met wachtwoorden die u wilt waarschuwen wanneer leads hot worden.
* **[[!DNL Sales Insight] voor Niet-inheemse  [!DNL Salesforce]  Integraties van CRM](/help/marketo/product-docs/marketo-sales-insight/sales-insight-for-non-native-salesforce-integrations.md)**: De abonnementen van GA met de integratie van douaneSalesforce CRM kunnen het [!DNL Sales Insight] pakket installeren en de hulp verkoopteams voorrang geven en met de meest veelbelovende lood en kansen in wisselwerking staan.
* **[Beste Bets Verbeteringen](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/marketo-tab/best-bets.md)**: Snel contacteer hete lood van het Beste lusje van Bets door hen aan een Campagne van Marketo Engage te e-mailen of toe te voegen. Bekijk een lead in Marketo Engage of voeg deze toe aan je controlelijst. Bulkacties en sorteeropties op het tabblad [!UICONTROL Best Bets] besparen tijd en verbeteren de efficiëntie van het verkoopteam.

## [!DNL Sales Connect] {#sales-connect}

![ (star) ](assets/yellow-star.png)

* **Verbeter de Throttling van de Verbinding E-mail (BETA)**: Verbeter uw e-mailleverbaarheid en schaal uw 1:1 verkoopmededeling met het Throttling van de Verbinding E-mail voor [!DNL Sales Connect]. Onze nieuwe vertragingstechnologie beheert automatisch de timing van het verzenden van e-mail om naadloze ervaringen voor [!DNL Exchange] en gebruikers van Gmail te creëren. Verlaag of elimineer het gebruik van externe toepassingen voor het verzenden van grote hoeveelheden e-mail.
* **het Stuitvolgen van de Bounce van de Verbinding E-mail**: Versterk insight in lood kwaliteit en e-mailmalplaatjeprestaties met het nieuwe e-mailstuitrapport. [!DNL Exchange] en Gmail-gebruikers kunnen ervoor kiezen om stuitberichten te ontvangen die worden weergegeven bij Live Feed, E-mailmappen, Sjabloonanalyse en Campagneanalyse.
* **de Configuratie van de Pagina van het Profiel**: Beheer gebruikersvoorkeur met gemak in de nieuwe profielpagina. Wijzig het wachtwoord, bewerk de instellingen voor geolocatie en taal en bekijk de integratiestatus op één locatie.
* **Beheer van Malplaatjes**: Organiseer verkoop e-mailmalplaatjes in categorieën met een nieuwe belemmering-en-dalingseigenschap om snelle toegang tot relevante malplaatjes te verzekeren en onderzoekstijd te verminderen.
* **[!DNL Sales Connect]Updates van gebruikerservaring**: pas de rasterlay-out aan door de kolommen te vergroten of te verkleinen en opnieuw te ordenen. [!DNL Sales Connect] Uw weergavevoorkeuren worden automatisch opgeslagen.

**_Aankondigingen &amp; Afschrijvingen_**

* Alle gebruikers moeten aan de recentste versie van Verkoop Insight **vóór 15 Januari, 2021** bevorderen. Als u de upgrade niet hebt voltooid, wordt u gevraagd dit te doen wanneer u zich aanmeldt bij de toepassing. Volg de instructies [ in deze gids ](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/upgrading/upgrading-your-msi-package.md). De bijgewerkte versie bevat een patch voor een geïdentificeerde beveiligingskwetsbaarheid. De pleister werd oorspronkelijk vrijgegeven op 6 april 2016. Nota: **Versies 1.4363 of hierboven** te hoeven niet om een verbetering uit te voeren.
* De afschrijving van de dienst van Vorm 1.0 zal in **mei 2021** versie van kracht worden. De Forms 1.0-service wordt volledig afgekeurd, waardoor de functionaliteit van alle resterende Forms 1.0-middelen die nog in gebruik zijn, verloren gaat. Ook formulierverzendingen die zijn ingediend via niet-ondersteunde methoden, zoals POST&#39;s met programmatische formulieren voor de eindpunten leadCapture/save en leadCapture/save2, worden afgewezen. Voor meer informatie en sanering, verwijs naar [ onze post in de Marketing Nation ](https://nation.marketo.com/t5/Product-Documents/Upcoming-Changes-to-the-Marketo-Engage-Form-Platform/ta-p/306631).
* In 2021 brengt Marketo Engage wijzigingen aan in de URL-structuur voor het plaatsen van pagina&#39;s, formulieren en afbeeldingen en bestanden. Voor bestaande Marketo Engage-abonnementen beginnen we met de geleidelijke introductie op 1 april 2021. Meer informatie over het tijdschema voor de uitrol wordt in maart 2021 gepubliceerd. Voor details op hoe elk beïnvloed activatype zal veranderen, verwijs naar [ onze post in de Marketing Nation ](https://nation.marketo.com/t5/Product-Documents/Upcoming-Changes-to-Design-Studio-URLs/ta-p/306632).

**_Webinar van de Versie van het Product_**

Wilt u meer weten over deze functies en verbeteringen? Ben zeker om [ nu te registreren ](https://engage.marketo.com/January_21_Release_Webinar_Registration.html) om zich bij ons op 21 Januari bij 1:00 PM PT/4:00 PM ET voor een levende webinar met ons productteam aan te sluiten om een diepere duik in deze innovaties te nemen.
