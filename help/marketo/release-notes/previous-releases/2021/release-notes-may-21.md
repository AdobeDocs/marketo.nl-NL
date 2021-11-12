---
description: Opmerkingen bij de release - mei 2021 - Marketo Docs - Productdocumentatie
title: Opmerkingen bij de release - mei 2021
exl-id: e3de60a2-17bd-4760-848e-6e931ad85b3c
source-git-commit: 115b6e97978778a1d1e13478adf6fee625aa5257
workflow-type: tm+mt
source-wordcount: '1446'
ht-degree: 0%

---

# Opmerkingen bij de release: mei 2021 {#release-notes-may-21}

De volgende functies zijn opgenomen in de release van mei 1921. Raadpleeg de Marketo-editie voor informatie over de beschikbaarheid van functies.

>[!AVAILABILITY]
>
>Kenmerken die door een ster worden aangeduid (![](assets/yellow-star.png)) worden betaald als extra&#39;s. Neem contact op met uw Marketo Engage-vertegenwoordiger voor meer informatie.

**_Kwartaalreleases_**

De volgende functies worden vrijgegeven op **7 mei 2021**.

## Ervaringen op basis van account {#Account-based-eaperiences}

* **Slimme accountlijsten (algemene beschikbaarheid)** ![](assets/yellow-star.png): Zoek en kwalificeer accounts met de gewenste account- en persoonkenmerken om ze te kunnen gebruiken in marketingcampagnes tussen kanalen en verstuur tijdige waarschuwingen naar Sales om deals sneller te sluiten. Dankzij deze nieuwe functie kunnen marketingstrategieën op basis van account robuust worden geautomatiseerd. De slimme Lijsten van de Rekening zijn beschikbaar voor klanten met het Beheer van de Rekening van het Doel die op de volgende generatie gebruikerservaring zijn.

## Ervaring voor gebruikers van de volgende generatie {#next-generation-user-experience}

Met algemene zoekvoorvertoning kunnen marketers snel zien waar een gedeeld element bestaat. De browser lusjes tonen de plaats om navigatie in de Activiteiten van de Marketing of Studio van het Ontwerp te verbeteren. Met extra boomstructuur en globale zoekfilters kunt u uw zoekcriteria verfijnen. De functionaliteit voor slepen en neerzetten in de boomstructuur is opnieuw geïnstalleerd, zodat u mappen en elementen snel en efficiënt kunt verplaatsen binnen de hoofdtoepassingsgebieden. Met nieuw bijgewerkte pictogrammen (die voldoen aan de toegankelijkheidsstandaarden van Adobe) en statusbadges kunnen marketers snel en eenvoudig onderscheid maken tussen mappen en elementen in de structuur en de status van programma&#39;s en middelen identificeren.

## Experience Automation {#experience-automation}

* **Stappen voor campagnestroom uitvoeren**: Workflows voor het maken van campagnes stroomlijnen en de prestaties van de campagne verbeteren met een nieuwe stap voor slimme campagnes. Maak en sla gecentraliseerde sjablooncampagnes op voor herhalende taken in uw werkruimte, zoals het normaliseren van landcodes, die moeten worden aangeroepen en uitgevoerd vanaf elke slimme campagne via de nieuwe stap Campagne uitvoeren. Gekoppelde campagnes worden in de aangegeven volgorde uitgevoerd en zorgen ervoor dat de taak is voltooid voordat u naar de volgende stap gaat. Bewerk snel de stroom in slechts één gecentraliseerde campagne om elke slimme campagne bij te werken die deze gebruikt om gegevensbeheer te stroomlijnen, workflows voor scoring en routering te leiden.

## Cross-Channel Orchestration {#cross-channel-orchestration}

* **Gevoelige gegevensvelden in Forms**: PII&#39;s (Persoonlijk identificeerbare informatie) van Protect-klanten kunnen in Adobe Marketo Engage-formulieren niet worden weergegeven door gegevensvelden als gevoelig te definiëren en de vooraf ingevulde formulieren voor deze velden te beperken. Wanneer een bezoeker een formulier op de bestemmingspagina weergeeft, worden in de velden die als gevoelig zijn gedefinieerd geen vooraf ingevulde gegevens weergegeven.

* **Spam-formulierverzendingen blokkeren**: Protect uw Adobe Marketo Engage-database van junk-gegevens die tot ongeldige waarschuwingen bij verkoop kunnen leiden, campagneruglogs kunnen activeren en ongewenste activiteiten kunnen maken. Het nieuwe validatiemechanisme wijst ongeldige formulierverzendingen af en stopt beide aanvallen. Uw gegevens zijn schoner en uw marketingcampagnes worden op de beoogde wijze uitgevoerd, waardoor het risico dat ongekwalificeerde leads naar verkoop worden verzonden, tot een minimum wordt beperkt.

* **Waarschuwing goedkeuring e-mailprogramma**: Voorkomen dat onjuiste e-mailberichten worden verzonden wanneer de nieuwe bewerkingen zijn aangebracht in een eerder goedgekeurd programma.  De waarschuwing fungeert als leidraad wanneer een markeerteken wijzigingen toepast op een e-mailbericht dat al is goedgekeurd, maar vervolgens vergeet de laatste wijzigingen goed te keuren en het e-mailbericht verstuurt naar een groot publiek zonder inhoud, slechte inhoud of oude inhoud.

* **Filter E-mailboxactiviteit**: Voorkom onbedoelde verkoopwaarschuwingen en onjuiste e-mailrapportage via de nieuwe functie voor het filteren van bestandsactiviteiten via e-mail. Identificeer en filter uit opent en klikt die met e-mailbots kunnen worden geassocieerd inspecterend verbindingen die tot valse trekkers en verkoopalarm, of onjuiste rapportering leiden.

## API-verbeteringen {#api-enhancements}

Verscheidene kritieke updates aan Bulk en Lood APIs, met inbegrip van de capaciteit om de gegevens van douaneobjecten in bulk uit te voeren, bedrijf met lood in bulk te associëren, capaciteit om bulkactiviteitsextract te filtreren dat op een primair attribuut wordt gebaseerd, en de capaciteit om programmalidmaatschap tot stand te brengen en bij te werken.

* **Gebeurtenisprogramma&#39;s nesten**: In Adobe Marketo Engage kunt u gebeurtenisprogramma&#39;s maken, klonen of verplaatsen in andere programmatypen. Deze functionaliteit is nu toegestaan in de API voor middelen.

* **Enhanced Delete Program API**: Hiermee kunnen geïntegreerde toepassingen programma&#39;s verwijderen die aanvullende typen elementen bevatten, zonder dat gebruikers dit handmatig moeten doen vanaf Adobe Marketo Engage.

* **Programmalidmaatschap**: De verkopers kunnen alle verslagen van het programmalid voor een geselecteerd programma vragen bepaalde verschillende criteria, zoals de status van het programmalid. Deze informatie delen met een externe toepassing, een hulpprogramma voor bedrijfsintelligentie of Adobe Experience Cloud om de segmentatie te verbeteren en meer gerichte betrokkenheid te creëren.

* **Bulk aangepast object extraheren**: Bulkgegevensexport is een aanvulling op de importmogelijkheden die gegevensanalisten al genieten in Adobe Marketo Engage. Nu kunnen zij gegevens halen die in de Aangepaste Voorwerpen van de Marketo Engage van 1st niveau Adobe in bulk worden opgeslagen, deze gegevens in een andere toepassing, een gegevenspakhuis, of een hulpmiddel van BI (Business Intelligence) laden om betere inzichten in de gegevens in de instantie van de Marketo Engage van Adobe te krijgen.  De verplaatsing van bulkgegevens van aangepaste objecten is bidirectioneel en kan op een geschikt moment worden gepland.

* **API voor metagegevens van aangepaste velden**: Bespaar tijd door het maken van aangepaste velden te automatiseren terwijl u de Adobe Marketo Engage-integratie instelt met een toepassing van derden. Deze automatisering komt vooral klanten met veelvoudige instanties van de Marketo Engage van Adobe ten ten goede die nu de verwezenlijking van douanegebieden kunnen stroomlijnen die vroeger handwerk in elke instantie vereiste. Het maken van aangepaste velden stroomlijnen en tijd besparen op deze bronverbruikende activiteit.

* **Extraheren voor bulkactiviteiten**: De controle van de aanwinst over de hoeveelheid en het type van gegevens wanneer het uitvoeren van bulkextracties. Filter onnodige gegevenspunten uit en controleer het aantal API-aanroepen dat nodig is om activiteitengegevens bulksgewijs te extraheren.  Selecteer bijvoorbeeld E-mailberichten openen, ga naar een webpagina of wijzig de leadscore en laat andere waardewijzigingen achter die u niet wilt analyseren. Het proces stroomlijnen om het aantal API-aanroepen en het opschonen van gegevens te verminderen.

* **API voor lead**: Identificeer lood in Adobe Marketo Engage die Adobe ECID (Experience Cloud ID) verbonden aan hen hebben.  Adobe Marketo Engage-klanten kunnen een lijst met leads maken van een geselecteerde campagne en de ECID&#39;s (Experience Cloud-id) gebruiken om rapporten te maken in Adobe Analytics voor die specifieke lijst. Integratie tussen Adobe Marketo Engage en Adobe Experience Cloud biedt onbeperkte mogelijkheden voor segmentatie, doelgerichtheid en rapportage.

* **Bulklead-import-API**: De invoer van lood in bulk en de middelen van de controle het nemen. Deze verbetering leidt tot associatie tussen lood en bedrijf tijdens het proces van de invoer van bulklood. Verhoog de efficiëntie en gebruik van gegevens en verlaag het gebruik van API-aanroepen.

* **Web API-gebaseerde Integratie voor de Online Klanten van de Dynamica van Microsoft**: MS Dynamics Web API werd geïntroduceerd met versie 8.0 REST protocol en implementeert OData (Open Data Protocol) v4. OData is een OASIS-norm (Organisation for the Advancement of Structured Information Standards) voor het bouwen en consumeren van RESTful-diensten boven rijke gegevens. De klanten van Adobe Marketo Engage die integratie met de Dynamica van Microsoft gebruikend deze methode vereisen worden momenteel gemigreerd aan Web API-Gebaseerde verbinding van ZEEP (het Eenvoudige Protocol van de Toegang van Objecten).

## Omgeving met marketinggegevens {#marketing-data-environment}

* **XLSX-export**: We hebben de exportmogelijkheden van het hele product verbeterd en XLSX in plaats van XLS ondersteund. Dit betekent dat overal in het product waar XLS-export momenteel wordt ondersteund, deze optie wordt vervangen door een optie voor het exporteren naar XLSX. Deze verandering zal de dossiernamen voor alle uitvoer van Excel van rapporten en andere gegevens van Adobe Marketo Engage beïnvloeden.

* **Zoeken op lead-id**: Open snel toegang tot het zoeken van lead records door de Adobe Marketo Engage lood-id te gebruiken in de hoofddatabase of in de statische lijst. Typ in het venster Snel zoeken gewoon `[id]` met het corresponderende nummer, worden de leidende gegevens weergegeven. Gebruikers kunnen snel de hoofd-, bedrijf- of opportuniteitsgegevens controleren.

## Bizible {#bizible}

![](assets/yellow-star.png)

* **Integratie met LinkedIn Lead Gen Forms (Beta)**: Vergroot de zichtbaarheid van uw LinkedIn-kanaaluitgaven en ROI met Bizible premium attribution-oplossing. Dankzij de meest recente integratie met LinkedIn&#39;s leider-gen Forms krijgt Bizible inzicht in formulieren die zijn ingediend binnen het LinkedIn-platform. Deze formuliervullingen worden vergeleken met leads van uw CRM-instantie (Customer Relationship Management) of Adobe Marketo Engage-instantie, zodat ze in aanmerking komen voor toewijzing en kunnen worden bijgehouden op basis van uw andere marketingafspraken.

## Aankondigingen {#announcements}

* **Marketo Product Docs Switching Platforms**: We zijn blij te kunnen aankondigen dat de Marketo Product Docs op vrijdag 7 mei is toegetreden tot de Adobe Experience League. U kunt de URL nog steeds gebruiken: docs.marketo.com. Als u bestaande artikelen hebt gemarkeerd als bladwijzer, wordt u omgeleid. Alle productdocumenten zijn beschikbaar op het nieuwe platform, met verbeteringen gepland voor later dit jaar.

* **Gestroomlijnd gebruikersbeheer en Single Sign-On met Adobe Identity System**: Vanaf juli 2021 worden de nieuwe Adobe Marketo Engage-klanten met gebruikersgegevens voor Adobe ingeschakeld. De migratie van huidige klanten naar het geïntegreerde identiteitssysteem zal pas medio 2022 plaatsvinden en er is geen actie van de klant nodig tot nader order. Single Sign-On stelt IT/Security-beheerders in staat om meerdere Adobe Marketo Engage-productinstanties samen met andere Experience Cloud-oplossingen te beheren en SSO (Shared Services Organisation) via een gemeenschappelijke console te configureren. Beheerders kunnen gebruikersgroepen en gebruikersrechten eenvoudig beheren via een algemene Admin Console.

**_Webinar productrelease_**

[Release-webinar mei 2021 Marketo Engage](https://engage.marketo.com/May_21_Release_webinar_RegistrationPage.html)
