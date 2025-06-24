---
description: Opmerkingen bij de release - mei 2021 - Marketo Docs - Productdocumentatie
title: Opmerkingen bij de release - mei 2021
exl-id: e3de60a2-17bd-4760-848e-6e931ad85b3c
feature: Release Information
source-git-commit: ecd225af3ecfd7cb9159faf5a9d384d47ee6312c
workflow-type: tm+mt
source-wordcount: '1436'
ht-degree: 0%

---

# Opmerkingen bij de release: mei 2021 {#release-notes-may-21}

De volgende functies zijn opgenomen in de release van mei 1921. Raadpleeg de Marketo-editie voor informatie over de beschikbaarheid van functies.

>[!AVAILABILITY]
>
>De eigenschappen die door een ster (![](assets/yellow-star.png)) worden vermeld worden betaalde toe:voegen-ons. Neem contact op met je Marketo Engage-vertegenwoordiger voor meer informatie.

**_Kwartaalversies_**

De volgende eigenschappen zullen op **7 Mei, 2021** worden vrijgegeven.

## Op account gebaseerde ervaringen {#Account-based-eaperiences}

* **Slimme Lijsten van de Rekening (algemene beschikbaarheid)** ![](assets/yellow-star.png): identificeer en kwalificeer dynamisch rekeningen met gewenste rekening en persoonattributen aan doel in dwars-kanaal marketing campagnes en verzend tijdige alarm naar Verkoop om overeenkomsten sneller te sluiten. Dankzij deze nieuwe functie kunnen marketingstrategieën op basis van account robuust worden geautomatiseerd. De slimme Lijsten van de Rekening zijn beschikbaar voor klanten met het Beheer van de Rekening van het Doel die op de volgende generatie gebruikerservaring zijn.

## Ervaring voor nieuwe gebruikers {#next-generation-user-experience}

Met algemene zoekvoorvertoning kunnen marketers snel zien waar een gedeeld element in hun exemplaar bestaat. Op de tabbladen van de browser wordt de locatie weergegeven waar u de navigatie in [!UICONTROL Marketing Activities] of [!UICONTROL Design Studio] wilt verbeteren. Met extra boomstructuur en globale zoekfilters kunt u uw zoekcriteria verfijnen. De functionaliteit voor slepen en neerzetten in de boomstructuur is opnieuw geïnstalleerd, zodat u mappen en elementen snel en efficiënt kunt verplaatsen binnen de hoofdtoepassingsgebieden. Met nieuw bijgewerkte pictogrammen (die voldoen aan de toegankelijkheidsstandaarden van Adobe) en statusbadges kunnen marketers snel en eenvoudig onderscheid maken tussen mappen en elementen in de structuur en de status van programma&#39;s en middelen identificeren.

## Experience Automation {#experience-automation}

* **voert de Stappen van de Stroom van de Stroom van de Campagne uit**: De werkschema&#39;s van de de campagneverwezenlijking stroomt en campagneprestaties met een nieuwe stroomstap voor Slimme Campagnes verbetert. Maak en sla gecentraliseerde sjablooncampagnes op voor herhalende taken in uw werkruimte, zoals het normaliseren van landcodes, die moeten worden aangeroepen en uitgevoerd vanaf elke slimme campagne via de nieuwe stap Campagne uitvoeren. Gekoppelde campagnes worden in de aangegeven volgorde uitgevoerd en zorgen ervoor dat de taak is voltooid voordat u naar de volgende stap gaat. Bewerk snel de stroom in slechts één gecentraliseerde campagne om elke slimme campagne bij te werken die deze gebruikt om gegevensbeheer te stroomlijnen, workflows voor scoring en routering te leiden.

## Cross-Channel Orchestration {#cross-channel-orchestration}

* **Gevoelige Gebieden van Gegevens in Forms**: Bescherm persoonlijk identificeerbare informatie van de klant (PII) tegen het tonen in de vormen van Adobe Marketo Engage door gegevensgebieden als gevoelig te bepalen en vormprefill voor die gebieden te beperken. Wanneer een bezoeker een formulier op de bestemmingspagina weergeeft, worden in de velden die als gevoelig zijn gedefinieerd, geen vooraf ingevulde gegevens weergegeven.

* **de Indieningen van de Vorm van het Blok Spam**: Bescherm uw gegevensbestand van Adobe Marketo Engage tegen junkgegevens die ongeldige alarm aan verkoop kunnen veroorzaken, campagnegollogs teactiveren, en ongewenste activiteiten tot stand brengen. Het nieuwe validatiemechanisme wijst ongeldige formulierverzendingen af en stopt beide aanvallen. Uw gegevens zijn schoner en uw marketingcampagnes worden op de beoogde wijze uitgevoerd, waardoor het risico dat ongekwalificeerde leads naar verkoop worden verzonden, tot een minimum wordt beperkt.

* **Waarschuwing van de Goedkeuring van het E-mailProgramma**: Vermijd verzendend onjuiste e-mails wanneer de nieuwe uitgeeft aan een eerder goedgekeurd programma werd gemaakt.  De waarschuwing fungeert als leidraad wanneer een markeerteken wijzigingen toepast op een e-mailbericht dat al is goedgekeurd, maar vervolgens vergeet de laatste wijzigingen goed te keuren en het e-mailbericht verstuurt naar een groot publiek zonder inhoud, slechte inhoud of oude inhoud.

* **filter-uit E-mailBots Activiteit**: Voorkom onbedoelde verkoopalarm en onnauwkeurige e-mail rapportering door het nieuwe e-mailbot activiteit filtrerend vermogen. Identificeer en filter uit opent en klikt die met e-mailbots kunnen worden geassocieerd inspecterend verbindingen die tot valse trekkers en verkoopalarm, of onjuiste rapportering leiden.

## API-verbeteringen {#api-enhancements}

Verscheidene kritieke updates aan Bulk en Lood APIs, met inbegrip van de capaciteit om de gegevens van douaneobjecten in bulk uit te voeren, bedrijf met lood in bulk te associëren, capaciteit om bulkactiviteitsextract te filtreren dat op een primair attribuut wordt gebaseerd, en de capaciteit om programmalidmaatschap tot stand te brengen en bij te werken.

* **Nest de Programma&#39;s van de Gebeurtenis**: In Adobe Marketo Engage kunt u tot stand brengen, klonen, of gebeurtenisprogramma&#39;s bewegen onder andere programmatypes. Deze functionaliteit is nu toegestaan in de API voor middelen.

* **Verbeterde Uitgebreide het Programma API van de Schrapping**: Staat geïntegreerde toepassingen toe om programma&#39;s te schrappen die extra types van activa bevatten, zonder gebruikers te vereisen om dit van Adobe Marketo Engage manueel te doen.

* **Lidmaatschap van het Programma**: De verkopers kunnen alle verslagen van het programmalid voor een geselecteerd programma vragen bepaalde verschillende criteria, zoals de status van het programmalid. Deze informatie delen met een externe toepassing, een hulpprogramma voor bedrijfsintelligentie of Adobe Experience Cloud om de segmentatie te verbeteren en meer gerichte betrokkenheid te creëren.

* **het Bulk Uittreksel van de Objecten van de Douane van het Bulk**: De bulkgegevensuitvoer vult de invoermogelijkheden aan die de gegevensanalisten reeds in Adobe Marketo Engage genieten. Nu kunnen ze gegevens die in Adobe Marketo Engage Custom Objects van het eerste niveau zijn opgeslagen bulksgewijs extraheren, deze gegevens laden in een andere toepassing, data warec of BI (Business Intelligence) om meer inzicht te krijgen in de gegevens in de Adobe Marketo Engage-instantie.  De verplaatsing van bulkgegevens van aangepaste objecten is bidirectioneel en kan op een geschikt moment worden gepland.

* **Meta-gegevens van de Gebieden van de Douane API**: Sparen tijd door de verwezenlijking van douanegebieden te automatiseren terwijl vestiging uw integratie van Adobe Marketo Engage met een derdetoepassing. Deze automatisering is vooral gunstig voor klanten met meerdere Adobe Marketo Engage-instanties die nu in staat zijn om het maken van aangepaste velden te stroomlijnen waarvoor handmatig werk nodig was. Het maken van aangepaste velden stroomlijnen en tijd besparen op deze bronverbruikende activiteit.

* **Uittreksel API van de Activiteit van het Bulk**: De controle van de aanwinst over de hoeveelheid en het type van gegevens wanneer het uitvoeren van bulkextracties. Filter onnodige gegevenspunten uit en controleer het aantal API-aanroepen dat nodig is om activiteitengegevens bulksgewijs te extraheren.  Selecteer bijvoorbeeld E-mailberichten openen, ga naar een webpagina of wijzig de leadscore en laat andere waardewijzigingen achter die u niet wilt analyseren. Het proces stroomlijnen om het aantal API-aanroepen en het opschonen van gegevens te verminderen.

* **Lood API**: Identificeer lood in Adobe Marketo Engage die Adobe ECID (identiteitskaart van Experience Cloud) verbonden aan hen hebben.  Adobe Marketo Engage-klanten kunnen een lijst met leads maken van een geselecteerde campagne en de ECID&#39;s (Experience Cloud ID) gebruiken om rapportage in Adobe Analytics voor die specifieke lijst te maken. De integratie tussen Adobe Marketo Engage en Adobe Experience Cloud biedt onbeperkte mogelijkheden voor segmentatie, doelgerichtheid en rapportage.

* **BulkLood de Invoer API van de Lood**: De invoer van het bulklood van de controle en middelen het neemt. Deze verbetering leidt tot associatie tussen lood en bedrijf tijdens het proces van de invoer van bulklood. Verhoog de efficiëntie en gebruik van gegevens en verlaag het gebruik van API-aanroepen.

* **Web API gebaseerde Integratie voor de [!DNL Microsoft Dynamics Online] Klanten**: [!DNL MS Dynamics] Web API werd geïntroduceerd met versie 8.0 het protocol van de REST en voert OData (Open Protocol van Gegevens) v4 uit. OData is een OASIS-norm (Organisation for the Advancement of Structured Information Standards) voor het bouwen en consumeren van RESTful-diensten boven rijke gegevens. Adobe Marketo Engage-klanten die deze methode willen gebruiken en die integratie met [!DNL Microsoft Dynamics] nodig hebben, worden momenteel vanuit SOAP (Simple Object Access Protocol) gemigreerd naar een web API-verbinding.

## Omgeving met marketinggegevens {#marketing-data-environment}

* **Uitvoer XLSX**: Wij bevorderden uitvoermogelijkheden door het product om XLSX in plaats van XLS te steunen. Dit betekent dat overal in het product waar XLS-export momenteel wordt ondersteund, deze optie wordt vervangen door een optie voor het exporteren naar XLSX. Deze wijziging is van invloed op de bestandsnamen voor alle Excel-exportbewerkingen van rapporten en andere gegevens uit Adobe Marketo Engage.

* **Onderzoek door identiteitskaart van de Lood**: Snel toegang leadverslag dat door Adobe Marketo Engage lood ID binnen het loodgegevensbestand of de statische lijst zoekt. Typ `[id]` in het venster Snel zoeken gewoon met het corresponderende nummer, waarna de informatie over de lead wordt weergegeven. Gebruikers kunnen snel de hoofd-, bedrijf- of opportuniteitsgegevens controleren.

## Bizible {#bizible}

![](assets/yellow-star.png)

* **Integratie met [!DNL LinkedIn] Leider Gen Forms (Beta)**: Vergroot diep zicht in uw [!DNL LinkedIn] kanaal besteedt en ROI met Bizible Premium attribution oplossing. Dankzij de meest recente integratie met de leidende gen. Forms van [!DNL LinkedIn] krijgt Bizible insight toegang tot formulieren die zijn verzonden binnen het [!DNL LinkedIn] -platform. Deze formuliervullingen worden vergeleken met leads van uw CRM- (Customer Relationship Management) of Adobe Marketo Engage-exemplaar, zodat ze in aanmerking komen voor toewijzing en kunnen worden bijgehouden op basis van uw andere marketingafspraken.

## Aankondigingen {#announcements}

* **de Platforms van de Omschakeling van Docs van het Product van Marketo**: Wij zijn opgetogen om aan te kondigen dat het Docs van het Product van Marketo zich bij de Liga van de Ervaring van Adobe per vrijdag, 7 mei heeft aangesloten. U kunt de URL docs.marketo.com nog steeds gebruiken. Als u bestaande artikelen hebt gemarkeerd als bladwijzer, wordt u omgeleid. Alle productdocumenten zijn beschikbaar op het nieuwe platform, met verbeteringen gepland voor later dit jaar.

* **Gestroomlijnd Beleid van de Gebruiker en Enige Sign-On aangedreven door het Systeem van de Identiteit van Adobe**: Begin Juli 2021, zullen de nieuwe klanten van Adobe Marketo Engage gebruikend de gebruikersgeloofsbrieven van Adobe worden bezet. De migratie van huidige klanten naar het geïntegreerde identiteitssysteem zal pas medio 2022 plaatsvinden en er is geen actie van de klant nodig tot nader order. Single Sign-On stelt IT/Security-beheerders in staat om meerdere Adobe Marketo Engage-productinstanties samen met andere Experience Cloud-oplossingen te beheren en SSO (Shared Services Organization) via een gemeenschappelijke console te configureren. Beheerders kunnen eenvoudig gebruikersgroepen en gebruikersrechten beheren via een algemene Admin Console.

**_Webinar van de Versie van het Product_**

[ Mei 2021 de Versie van Marketo Engage Webinar ](https://engage.marketo.com/May_21_Release_webinar_RegistrationPage.html)
