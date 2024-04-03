---
description: veelgestelde vragen over gegevenssynchronisatie voor handelingen - Marketo-documenten - productdocumentatie
title: Veelgestelde vragen over gegevenssynchronisatie voor handelingen
feature: Sales Insight Actions
exl-id: bb213d50-be22-492d-b74c-b8cfb834b2ca
source-git-commit: 26173379c89393596b3ece18c7f7e945a79588d9
workflow-type: tm+mt
source-wordcount: '1054'
ht-degree: 0%

---

# Veelgestelde vragen over gegevenssynchronisatie voor handelingen {#actions-data-sync-faq}

De het gebiedssynchronisatie van de gegevenseenmaking voor de Acties van het Inzicht van de Verkoop laat het systeem toe om persooninformatie van uw gegevensbestand van het Marketo Engage in uw gegevensbestand van de Acties van het Inzicht van de Verkoop te trekken.

Dit verstrekt bijgewerkte personengegevens in het Web-app van Acties van het Inzicht van de Verkoop en staat het systeem toe om unieke IDs voor overeenkomstige persoonverslagen in Marketo en lood/contact/rekening/opportuniteitsverslagen in Salesforce te verzamelen, zodat kunnen de verslagen behoorlijk voor registreren gegevens worden referenced.

Deze synchronisatie kan worden ingeschakeld via het tabblad Configuratie van handelingen voor het instellen van verkoopgegevens in de sectie Beheer van het Marketo Engage. Meer informatie vindt u in [Gegevenssynchronisatie starten](/help/marketo/product-docs/marketo-sales-insight/actions/getting-started/sales-insight-actions-admin-setup-guide.md#initiate-data-sync).

![](assets/actions-data-sync-faq-1.png)

Het diagram hierboven toont hoe de menselijke activiteit en de taakgegevens tussen systemen kunnen synchroniseren. Een paar dingen:

* De verslagen van de mensen worden gesynchroniseerd aan de Acties van het Inzicht van de Verkoop van Marketo Engage, die Marketo Engage tot de bron van waarheid voor de Acties van het Inzicht van de Verkoop maken de gegevens van de mensen
* Handelingen voor zowel Marketo Engage als verkoopinzicht [een mechanisme](/help/marketo/product-docs/marketo-sales-insight/actions/email/unsubscribes/syncing-unsubscribes-with-salesforce.md) voor het verzamelen en synchroniseren van de afmeldingsstatus bij Salesforce
* Abonnementsstatus wordt niet gesynchroniseerd van Verkoopacties naar Marketo Engage, maar Handelingen voor Verkoopcontrole kunnen worden geconfigureerd om de status voor afmelden bij Marketo te controleren voordat verkopers een e-mail met [Marketo Unsubscribe Check](/help/marketo/product-docs/marketo-sales-insight/actions/email/unsubscribes/marketo-unsubscribe-check.md).

Hieronder volgen enkele veelgestelde vragen over de werking van het synchroniseren van gegevens.

## Welke lood/contacten worden gesynchroniseerd aan de Acties van het Inzicht van de Verkoop? {#what-lead-contacts-are-synced}

![](assets/actions-data-sync-faq-2.png)

De leiders en de contacten die een verkoopeigenaar hebben aan hen wordt toegewezen zullen in de Acties van de Verkoop worden gesynchroniseerd.

U kunt zien of heeft een lood/contact een verkoopeigenaar in Salesforce door het standaardeigenaargebied te bekijken dat bestaat.

De eigenaar van de verkoop hoeft niet de synchronisatiegebruiker van Marketo of een specifieke Salesforce- of verkoopgebruiker te zijn. Alles wat we nodig hebben, is dat er een gebruiker is die vermeld staat in het veld voor de eigenaar van de lead en de eigenaar van de contactpersoon in Salesforce, zodat we deze kunnen identificeren als verkooplead en synchroniseren met Handelingen voor het toezicht op de verkoop. Alle updates van de velden waarmee we synchroniseren, worden ook gedetecteerd en bijgewerkt in Handelingen voor Verkoopcontrole.

## Waar worden de activiteitsgegevens die in het Slimme Net van het Inzicht van de Verkoop worden getoond waar vandaan gehaald? {#where-does-the-activity-data-get-sourced-from}

![](assets/actions-data-sync-faq-3.png)

De activiteitsgegevens zoals e-mail, vraag, interessant moment en Web, zijn allemaal afkomstig uit de database van het Marketo Engage. Het slimme Net van het Inzicht van de Verkoop richt een verzoek aan de instantie van het Marketo Engage om dit terug te winnen telkens als een verkoopgebruiker het paneel van het Inzicht van de Verkoop laadt.

![](assets/actions-data-sync-faq-4.png)

Om ervoor te zorgen dat alle activiteitsgegevens van Marketo Engage kunnen worden ingekocht, synchroniseert de Acties van het Inzicht van de Verkoop alle activiteitengegevens aan Marketo Engage.

## Welke gebieden met betrekking tot mensen synchroniseren van Marketo Engage aan de Acties van het Inzicht van de Verkoop? {#what-fields-sync}

Er zijn 11 gebieden die van Marketo Engage aan de Acties van het Inzicht van de Verkoop synchroniseren:

* Voornaam
* Achternaam
* Contactpersoon-id Salesforce
* lood-id Salesforce
* Salesforce-account-id
* ID Salesforce-kans
* Marketo-id
* Bedrijf
* Titel
* E-mail
* Telefoonnummer
* Koppeling in URL
* Bron

## Zijn de gebieden die tussen Marketo Engage en de Acties van het Inzicht van de Verkoop configureerbaar? {#are-the-fields-that-sync-configurable}

Het vormen welke gebieden van het Marketo Engage synchronisatie aan de Acties van het Inzicht van de Verkoop niet beschikbaar zijn, noch de capaciteit is om gebieden in kaart te brengen. Bij de synchronisatie vanuit Marketo worden standaard Marketo-velden automatisch toegewezen aan standaardvelden in je Verkoopactie-exemplaar.

## Waarom hebben de Acties van het Inzicht van de Verkoop zijn eigen gegevensbestand? {#why-does-actions-have-its-own-database}

Handelingen van het Inzicht van de verkoop hebben zijn eigen Webtoepassing met een specifiek persoon en activiteitengegevensbestand om een geoptimaliseerde werkruimte te verstrekken die voor verkoopteams wordt gebouwd en wordt ontworpen. Dit stelt verkoopmanagers en verkopers in staat om ruimte te hebben om hun betrokkenheidsstrategie uit te werken en te beheren zonder toegang of privileges te verlenen aan de werkruimte van het primaire Marketo Engage, die is geoptimaliseerd voor marketingspecialisten.

## Hoe worden duplicaten afgehandeld? {#how-are-duplicates-handled}

Uw gegevensbestand van de Acties van de Verkoop zal een exemplaar van die gekwalificeerde mensen (lood/contacten met een verkoopeigenaar) zijn die in uw gegevensbestand van het Marketo Engage bestaan. Dit betekent dat als er twee records zijn met hetzelfde e-mailadres dat in Marketo is gemaakt, er een dubbele record wordt gemaakt in Verkoopacties.

## Hoe lang duurt het voordat de eerste synchronisatie is voltooid? {#how-long-initial-sync}

Het aanvankelijke proces om al uw gegevens van de verkooplood in een nieuwe instantie van de Acties van het Inzicht van de Verkoop te synchroniseren zal typisch mensen bij ongeveer 1.000 om de 1-2 minuten verwerken. Dit is slechts een schatting en kan variëren.

Zodra de eerste synchronisatie plaatsvindt en al uw verkoopkansen in uw exemplaar van het Web-app van Acties van het Inzicht van de Verkoop zijn bevolkt, zal er een stijgende synchronisatie zijn die zal lopen telkens als er een update aan één van de gesteunde gebieden is die worden gesynchroniseerd.

## Kunnen gebruikers van Handelingen van het Inzicht van de Verkoop personengegevens van het Web van Acties uitgeven? {#can-actions-users-edit-people-data}

Nee, de mogelijkheid om records voor personen te maken en te bewerken in Handelingen is niet beschikbaar voor zowel gebruikers als beheerders van de webapp Handelingen. Het creëren en het uitgeven van mensen moeten in of Salesforce of Marketo Engage worden gedaan. Handelingen van het Inzicht van de verkoop gebruiken Marketo als bron van waarheidsgegevens voor mensen door nieuwe gegevens onophoudelijk te synchroniseren, zodat als een persoon in Marketo of van een werkschema in Marketo of gesynchroniseerd over van Salesforce wordt bijgewerkt of wordt gecreeerd, zullen die updates aan het Web-app gegevensbestand van Acties van het Inzicht van de Verkoop worden overgegaan.

## Meld je verkoopactiviteiten aan bij Marketo? {#do-sales-activities-log-to-marketo}

Ja, de activiteiten van de verkoopovereenkomst zullen aan Marketo als inheemse activiteiten registreren. Deze activiteiten omvatten ook inheemse filters die met beperkingen kunnen worden gebruikt om lood te richten die op de attributen van de verkoopactiviteit wordt gebaseerd.

![](assets/actions-data-sync-faq-5.png)

Hieronder volgt een lijst van de activiteiten die aan Marketo registreren:

* Verkoop-e-mail verzenden
* Verkoopbericht openen
* Klik op E-mail verkoop
* Reageerd op e-mail over verkoop
* Verkoop-e-mail teruggestuurd
* Verkoopoproep ontvangen
* Toevoegen aan verkoopcampagne
* Verwijderd uit verkoopcampagne

## Meld je verkoopactiviteiten aan bij Salesforce? {#do-sales-activities-log-to-salesforce}

Ja, de activiteiten van de verkoopovereenkomst zullen aan Salesforce als inheemse taken registreren. Deze taken kunnen dan in Salesforce- rapporten aan machtsteam dashboards worden gebruikt die verkoopactiviteiten volgen.

De Acties van het Inzicht van de verkoop staan beheerders toe om te vormen welke verkoopactiviteiten aan Salesforce worden geregistreerd. Deze activiteiten omvatten e-mails, oproepen en open herinneringstaken.

![](assets/actions-data-sync-faq-6.png)

Het diagram hierboven toont welke informatie aan Salesforce wordt geregistreerd. Activiteiten zoals e-mails en oproepen worden bij Salesforce aangemeld in een [eenzijdige synchronisatie](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-integration/salesforce-sync-settings.md). [Abonnementen opzeggen](/help/marketo/product-docs/marketo-sales-insight/actions/email/unsubscribes/syncing-unsubscribes-with-salesforce.md) en [Herinneringstaken](/help/marketo/product-docs/marketo-sales-insight/actions/tasks/reminder-task-sync-with-salesforce.md) voortdurend worden gesynchroniseerd. Elk van deze gegevenssyncs is configureerbaar van het Web-app interface van Acties van het Inzicht van de Verkoop.

>[!MORELIKETHIS]
>
>* [Abonnementen synchroniseren met Salesforce](/help/marketo/product-docs/marketo-sales-insight/actions/email/unsubscribes/syncing-unsubscribes-with-salesforce.md)
>* [Marketo Unsubscribe Check](/help/marketo/product-docs/marketo-sales-insight/actions/email/unsubscribes/marketo-unsubscribe-check.md)
>* [Instellingen voor Salesforce Sync](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-integration/salesforce-sync-settings.md)
>* [Herinnering taaksynchronisatie met Salesforce](/help/marketo/product-docs/marketo-sales-insight/actions/tasks/reminder-task-sync-with-salesforce.md)
>* [Gegevenssynchronisatie starten](/help/marketo/product-docs/marketo-sales-insight/actions/getting-started/sales-insight-actions-admin-setup-guide.md#initiate-data-sync)

