---
description: Opmerkingen bij de release - augustus 2021 - Marketo Docs - Productdocumentatie
title: Opmerkingen bij de release - augustus 2021
exl-id: 4aec4e0b-520e-4786-a110-8e68f1bf9950
source-git-commit: 7a062683a3c38d8765eb966041bf7ee3db665f5a
workflow-type: tm+mt
source-wordcount: '925'
ht-degree: 0%

---

# Opmerkingen bij de release: augustus 2021 {#release-notes-aug-21}

De volgende functies zijn opgenomen in de release van augustus &#39;21. Controleer uw Marketo Engage-editie voor de beschikbaarheid van functies.

>[!AVAILABILITY]
>
>Kenmerken die door een ster worden aangeduid (![](assets/yellow-star.png)) worden betaald als extra&#39;s. Neem contact op met je Adobe Marketo Engage-vertegenwoordiger voor meer informatie.

**_Kwartaalreleases_**

De volgende functies worden vrijgegeven op **20 augustus 2021**.

## Experience Automation {#experience-automation}

* **Marketo Engage Gebruikersverificatie via Adobe-id**: Binnenkort worden nieuwe Marketo Engage-gebruikers met Enterprise-pakketten ingeschakeld met Adobe ID-gebruikersgegevens. De migratie van huidige gebruikers naar het geïntegreerde identiteitssysteem zal pas medio 2022 plaatsvinden en tot nader order is geen actie vereist. Met gebruikersverificatie voor Adobe-identiteit kunnen IT/Security-beheerders meerdere Marketo Engage-productinstanties beheren samen met andere Experience Cloud-oplossingen en SSO configureren via een gemeenschappelijke console. Beheerders kunnen gebruikersgroepen en gebruikersrechten eenvoudig op één locatie beheren.

* **Uitvoerbare campagne nesten**: Uitvoerbare campagnes kunnen nu ook andere uitvoerbare campagnes roepen die u toestaan om hen tot drie niveaus diep te nesten. Dit maakt verdere consolidatie van gemeenschappelijke operationele stromen mogelijk en verbetert Slim Campagnebeheer.

* **Single Flow-actie in persoonlijke detailpagina** (Beschikbaar vanaf 9 september): Voer stroomacties zoals het verzenden van e-mail, verandering persoonseigenaar, of een andere slimme campagneactie op individuele mensen van de pagina van het persoondetail uit gebruikend het menu van de stroomactie zonder het schakelen naar de mening van het gegevensbestandnet.

* **[Aangepaste activiteiten exporteren](/help/marketo/product-docs/administration/marketo-custom-activities/custom-activity-metadata-export.md)**: Metagegevens exporteren ondersteunt nu alle objecten en de bijbehorende metagegevens die kunnen worden gebruikt voor het delen, analyseren en ontwerpen van uw gegevensmodel voor abonnementen.

## API-verbeteringen {#api-enhancements}

* **Formulier-API verzenden**: Wanneer een e-mailadres wordt gedupliceerd in twee of meer lead-records, wordt de record &#39;laatst bijgewerkt&#39; bijgewerkt in plaats van deze helemaal over te slaan. Biedt pariteit met Forms 2.0 API.

* **E-mailAPI**: Ontvang champion- of e-mailmiddelen van de uitdager. E-mailmiddelen ophalen met het filter Datumbereik.

**_Vrijgeven door het Kwartaal_**

De volgende functies bevinden zich op een niet-driemaandelijkse cyclus en worden de komende maanden vrijgegeven.

## Verkoopoverzicht {#sales-insight}

![(ster)](assets/yellow-star.png)

* **Verbeterde zichtbaarheid in leads, contact, account en opportuniteitsactiviteiten voor Salesforce CRM-gebruikers**: Betrokkenheid met vooruitzichten tijdens lange verkoopcycli wordt beter geïnformeerd toe te schrijven aan een verhoogd aantal betrokkenheidsrecords in Sales Insight. Interesserende momenten, webactiviteit, e-mail en score worden weergegeven met maximaal 400 activiteiten over objecten Lead, Contact, Account en Opportunity.

## Verkoop Connect {#sales-connect}

![(ster)](assets/yellow-star.png)

* **E-mailverbindingsThrottling (bèta)**: Verbeter de e-mailleverbaarheid en schaal persoonlijke verkoopcommunicatie met de snelheid van de e-mailverbinding voor Sales Connect. Deze nieuwe technologie beheert automatisch de timing van het verzenden van e-mail om naadloze ervaringen voor gebruikers van de Uitwisseling en van Gmail te creëren. Verlaag of verwijder het gebruik van grote hoeveelheden e-mailberichten van derden en verzend al uw e-mails vanuit Sales Connect met vertrouwen.

>[!NOTE]
>
>E-mailvertraging is nu beschikbaar in bètaversie. [Meer informatie](/help/marketo/product-docs/marketo-sales-connect/email/email-delivery/email-connection-throttling.md).

* **Verbeterde informatie over verkoopactiviteiten**: Leg persoonlijke betrokkenheid vast en activeer deze op basis van eerdere activiteiten van uw verkoopteam. De nieuwe attributen zoals de Verbinding van de Opname van de Vraag van de Verkoop, de Naam van de Campagne van de Verkoop, en Onderwerp van e-mail van de Verkoop kunnen in Marketo Engage slimme lijsten worden gebruikt.  Deze activiteiten kunnen worden geëxporteerd en gerapporteerd via de Marketo Engage REST API of Bulk Export en zijn beschikbaar op filters en triggers als extra beperkingen voor slimme lijsten.

## Bizible {#bizible}

![](assets/yellow-star.png)

* **Bizible LinkedIn Lead Gen Forms Integration**: Marketers kunnen nu inkomstentoerekening uitvoeren op conversies die plaatsvinden wanneer LinkedIn formuliervullingen vastlegt via hun leidende gen Forms en eenheden. Deze inzichten kunnen dan worden gebruikt om formulierprestaties en betaalde media-investeringen te optimaliseren. linkedIn-leider-gen Forms is een van de snelst groeiende betaalmediapakketten van LinkedIn en deze nieuwe functionaliteit is inbegrepen bij onze bestaande LinkedIn Ads-integratie met Bizible.

* **Verbeterd klapperdashboard**: We hebben een nieuw metrisch en dashboardfilter toegevoegd voor dieper inzicht. Dit dashboard wordt door marketers gebruikt om de toonaangevende positie en opportuniteitssnelheid van de verschillende stadia en de efficiëntie van verschillende vormen van marketing en verkoopbetrokkenheid te begrijpen.

* **Nieuw kleurendashboard voor watervalreis**: Op die manier kunnen de marktpartijen de voortgang van een geselecteerd cohort zien door middel van een klassieke reeks &quot;vraagwaterval&quot;-fasen, die een snel inzicht verschaffen in de omrekeningskoersen en de impliciete oorzaken van de omzetting in het stadium per fase.

## Bizible Integration in Adobe Experience Cloud {#bizible-integration-with-adobe-experience-cloud}

Deze sectie bevat nieuwe functies voor Bizible-gebruikers die hun Adobe Identity Management System (IMS)-migratie hebben voltooid. Als u bent gemigreerd, ziet u uw nieuwe Adobe ID in Bizible Settings onder het tabblad Adobe ID. Alle rekeningen zouden tegen eind 2021 moeten zijn gemigreerd.

* **Bizible Integration met Adobe Privacy Service** (beschikbaar september 2021): De integratie van Bizible met de Privacy Service van de Adobe centraliseert naleving van kritieke gegevensprivacyverordeningen (zoals GDPR) over Adobe Experience Cloud toepassingen. U kunt nu gebruikmaken van deze service en alle privacyverzoeken centraal beheren, zodat wijzigingsverzoeken die in Bizible en andere Adobe-producten worden ingediend, in alle toepassingen worden doorgevoerd.

* **Bizible op Adobe Experience Cloud Interface**: De acceptatie door Bizible van Adobe Experience Cloud Interface biedt gebruikers nieuwe mogelijkheden die in de Bizible-toepassingskoptekstbalk worden weergegeven en die een betere toegang tot ondersteuningsbronnen en het schakelen tussen toepassingen omvatten. De Experience Cloud Interface helpt een consistente ervaring te creëren tussen Bizible- en andere Adobe Experience Cloud-toepassingen.

* **Bizible Domain Owownership and Self-Management**: Bizible-gebruikers kunnen Adobe Admin Console gebruiken om de domeinen te beheren die Bizible wil bijhouden. Dit brengt zelfbediening aan een eerder handproces en verstrekt een verenigbare ervaring in hoe domeineigendom en het volgen in de toepassingen van Adobe Experience Cloud worden beheerd.

## Aankondigingen {#announcements}

* **Instellingen voor Universal-id voor abonnement bijwerken**: Om de komende Marketo Engage en Adobe Identiteitsintegratie voor bestaande gebruikers te steunen, zullen alle Marketo Engage abonnementen in de Inschakelen van de Universele steun van identiteitskaart worden verenigd. Meer informatie [hier te vinden](/help/marketo/product-docs/administration/settings/using-a-universal-id-for-subscription-login.md).

**_Webinar productrelease_**

[Augustus 2021 Marketo Engage Release Webinar](https://engage.marketo.com/August21_Release_Webinar.html)
