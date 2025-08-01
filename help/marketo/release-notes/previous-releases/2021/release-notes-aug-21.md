---
description: Opmerkingen bij de release - augustus 2021 - Marketo Docs - Productdocumentatie
title: Opmerkingen bij de release - augustus 2021
exl-id: 4aec4e0b-520e-4786-a110-8e68f1bf9950
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '903'
ht-degree: 0%

---

# Opmerkingen bij de release: augustus 2021 {#release-notes-aug-21}

De volgende functies zijn opgenomen in de release van augustus &#39;21. Raadpleeg de Marketo Engage-editie voor informatie over de beschikbaarheid van functies.

>[!AVAILABILITY]
>
>De eigenschappen die door een ster (![](assets/yellow-star.png)) worden vermeld worden betaalde toe:voegen-ons. Neem contact op met je Adobe Marketo Engage-vertegenwoordiger voor meer informatie.

**_Kwartaalversies_**

De volgende eigenschappen zullen op **Augustus 20, 2021** worden vrijgegeven.

## Experience Automation {#experience-automation}

* **de Authentificatie van de Gebruiker van Marketo Engage via de Identiteit van Adobe**: Binnenkort, zullen de nieuwe gebruikers van Marketo Engage met de pakketten van de Onderneming worden geregistreerd gebruikend de gebruikersgeloofsbrieven van Adobe ID. De migratie van huidige gebruikers naar het geïntegreerde identiteitssysteem zal pas medio 2022 plaatsvinden en tot nader order is geen actie vereist. Met Adobe-verificatie voor identiteitsgebruikers kunnen IT/Security-beheerders meerdere Marketo Engage-productinstanties beheren samen met andere Experience Cloud-oplossingen en SSO configureren via een gemeenschappelijke console. Beheerders kunnen gebruikersgroepen en gebruikersrechten eenvoudig op één locatie beheren.

* **Uitvoerbare Campagne het Nesten**: De uitvoerbare campagnes kunnen andere uitvoerbare campagnes nu ook roepen die u toestaan om hen tot drie niveaus diep te nesten. Dit maakt verdere consolidatie van gemeenschappelijke operationele stromen mogelijk en verbetert Slim Campagnebeheer.

* **Enige Actie van de Stroom in de Pagina van het Detail van de Persoon** (Beschikbaar door 9 september): Voer stroomacties als het verzenden van e-mail uit, verander persoonseigenaar, of een andere slimme campagneactie op individuele mensen van de pagina die van het persoondetail het menu van de stroomactie zonder het schakelen naar de mening van het gegevensbestandnet gebruiken.

* **[de Uitvoer van de Activiteiten van de Douane](/help/marketo/product-docs/administration/marketo-custom-activities/custom-activity-metadata-export.md)**: De uitvoer van meta-gegevens steunt nu alle voorwerpen en respectieve meta-gegevens die kunnen worden gebruikt om uw model van abonnementsgegevens te delen, te analyseren en te ontwerpen.

## API-verbeteringen {#api-enhancements}

* **leg Vorm API** voor: Wanneer een e-mailadres in twee of meer verslagen van de Lood wordt gedupliceerd, werken wij &quot;laatst bijgewerkt&quot;verslag in plaats van het overslaan. Biedt pariteit met Forms 2.0 API.

* **E-mail API**: Haal champion of uitdager e-mailactiva terug. E-mailmiddelen ophalen met het filter Datumbereik.

**_vrijstellend door het Kwartaal_**

De volgende functies bevinden zich op een niet-driemaandelijkse cyclus en worden de komende maanden vrijgegeven.

## [!DNL Sales Insight] {#sales-insight}

![ (star) ](assets/yellow-star.png)

* **Verbeterde zichtbaarheid in Lood, Contact, Rekening &amp; de Activiteiten van de Kans voor de Gebruikers van Salesforce CRM**: Betrokkenheid met vooruitzichten tijdens lange verkoopcycli wordt meer geïnformeerd toe te schrijven aan een verhoogd aantal betrokkenheidsverslagen in [!DNL Sales Insight]. Interesserende momenten, webactiviteit, e-mail en score worden weergegeven met maximaal 400 activiteiten over objecten Lead, Contact, Account en Opportunity.

## [!DNL Sales Connect] {#sales-connect}

![ (star) ](assets/yellow-star.png)

* **de Throttling van de Verbinding van de E-mail (Beta)**: Verbeter e-mailleverbaarheid en schaal gepersonaliseerde verkoopmededeling met de vertraging van de e-mailverbinding voor Verkoop verbindt. Deze nieuwe technologie beheert automatisch de tijdinstellingen voor het verzenden van e-mail, zodat [!DNL Exchange] - en Gmail-gebruikers er probleemloos mee kunnen werken. Verlaag of verwijder het gebruik van grote hoeveelheden e-mailberichten van derden en verzend alle e-mails van [!DNL Sales Connect] met vertrouwen.

>[!NOTE]
>
>E-mailvertraging is nu beschikbaar in Beta. [ leer meer ](/help/marketo/product-docs/marketo-sales-connect/email/email-delivery/email-connection-throttling.md).

* **Verbeterde Inzichten van de Activiteit van de Verkoop**: Vang en activeer gepersonaliseerde overeenkomst die op de vroegere activiteiten van uw verkoopteam wordt gebaseerd. De nieuwe attributen zoals de Verbinding van de Opname van de Vraag van de Verkoop, de Naam van de Campagne van de Verkoop, en Onderwerp van e-mail van de Verkoop kunnen in slimme lijsten van Marketo Engage worden gebruikt.  Deze activiteiten kunnen worden geëxporteerd en gerapporteerd via de Marketo Engage REST API of Bulk Export en zijn beschikbaar op filters en triggers als extra beperkingen voor slimme lijsten.

## [!DNL Bizible] {#bizible}

![](assets/yellow-star.png)

* **[!DNL Bizible][!DNL LinkedIn] Forms-integratie van leidende klasse** : marketers kunnen nu inkomstenattributie uitvoeren op conversies die optreden wanneer [!DNL LinkedIn] formuliervullingen vastlegt via hun leidende gen-Forms en -eenheden. Deze inzichten kunnen dan worden gebruikt om formulierprestaties en betaalde media-investeringen te optimaliseren. [!DNL LinkedIn] Leider-gen Forms is een van de snelst groeiende, betaalbare mediaproducties van [!DNL LinkedIn] en deze nieuwe functionaliteit is inbegrepen bij onze bestaande [!DNL LinkedIn] Advertentieverbinding met [!DNL Bizible] . 
 
* **Verbeterd dashboard van de Snelheid**: Wij hebben een nieuwe metrische snelheidsfilter en dashboardfilter voor diepere inzichten toegevoegd. Dit dashboard wordt door marketers gebruikt om de toonaangevende positie en opportuniteitssnelheid van de verschillende stadia en de efficiëntie van verschillende vormen van marketing en verkoopbetrokkenheid te begrijpen.

* **Nieuw Dashboard van de Reis van de Waterval van de Cohort**: Dit zal marketers toelaten om de vooruitgang van een geselecteerde cohort door een klassieke reeks van &quot;vraagwaterval&quot;stadia te bekijken, die een snel inzicht in omzettingspercentages en impliciete faseomzetting causaliteit op een stadium-door-stadium verstrekt.

## [!DNL Bizible] Integratie met Adobe Experience Cloud {#bizible-integration-with-adobe-experience-cloud}

Deze sectie bevat nieuwe functies voor Bizible-gebruikers die de migratie naar hun Adobe Identity Management System (IMS) hebben voltooid. Als u bent gemigreerd, wordt de nieuwe Adobe ID weergegeven in [!DNL Bizible] Instellingen onder het tabblad Adobe ID. Alle rekeningen zouden tegen eind 2021 moeten zijn gemigreerd.

* **[!DNL Bizible]Integratie met Adobe Privacy Service** (beschikbaar in september 2021): de integratie van [!DNL Bizible] met Adobe Privacy Service centraliseert naleving van kritieke gegevensprivacyverordeningen (zoals GDPR) over Adobe Experience Cloud-toepassingen. U kunt nu gebruikmaken van deze service en alle privacyverzoeken centraal beheren, zodat wijzigingsverzoeken die binnenkomen in [!DNL Bizible] en andere Adobe-producten in alle toepassingen worden doorgevoerd.

* **[!DNL Bizible]op Adobe Verenigde Shell**: [!DNL Bizible] de goedkeuring van Adobe Verenigde Shell geeft gebruikers nieuwe mogelijkheden die in de [!DNL Bizible] bar van de toepassingskopbal zullen verschijnen en betere toegang tot steunmiddelen en toepassingsomschakeling omvatten. Adobe Unified Shell helpt een consistente ervaring te creëren tussen [!DNL Bizible] en andere Adobe Experience Cloud-toepassingen.

* **[!DNL Bizible]Domeineigendom en Zelfbeheer** : [!DNL Bizible] gebruikers kunnen Adobe Admin Console gebruiken om de domeinen te beheren die ze in [!DNL Bizible] willen bijhouden. Dit brengt zelfbediening aan een eerder handproces en verstrekt een verenigbare ervaring in hoe domeineigendom en het volgen in de toepassingen van Adobe Experience Cloud worden beheerd.

## Aankondigingen {#announcements}

* **Update aan de Montages van de Universele identiteitskaart van het Abonnement**: Om de aanstaande integratie van de Identiteit van Marketo Engage en van Adobe voor bestaande gebruikers te steunen, zullen alle abonnementen van Marketo Engage in enablement van Universele identiteitskaart steun worden verenigd. Meer informatie [ kan hier ](/help/marketo/product-docs/administration/settings/using-a-universal-id-for-subscription-login.md) worden gevonden.

**_Webinar van de Versie van het Product_**

[ Augustus 2021 de Versie van Marketo Engage Webinar ](https://engage.marketo.com/August21_Release_Webinar.html)
