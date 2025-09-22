---
description: Verkoopgegevens synchroniseren met Marketo en Salesforce - Marketo Docs - Productdocumentatie
title: Verkoopgegevens synchroniseren met Marketo en Salesforce
exl-id: bb213d50-be22-492d-b74c-b8cfb834b2ca
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '1068'
ht-degree: 0%

---

# Verkoopgegevens synchroniseren met Marketo en Salesforce {#sync-sales-action-data-with-marketo-and-salesforce}

Met de Data Unification field sync for Sales Insight Actions kan het systeem persoongegevens uit uw Marketo Engage-database ophalen in uw Sales Insight Actions-database.

Dit verstrekt bijgewerkte personengegevens in het Web-app van Acties van de Handelingen van Insight van de Verkoop en staat het systeem toe om unieke IDs voor overeenkomstige persoonverslagen in Marketo en lood/contact/rekening/opportuniteitsverslagen in Salesforce te verzamelen, zodat kunnen de verslagen behoorlijk voor registrerengegevens worden referenced.

Deze synchronisatie kan worden ingeschakeld via het tabblad Configuratie Handelingen van Insight verkopen in de sectie Beheer van Marketo Engage. Voor meer informatiecontrole [ leidt de Synchronisatie van Gegevens ](/help/marketo/product-docs/marketo-sales-insight/actions/getting-started/sales-insight-actions-admin-setup-guide.md#initiate-data-sync) in.

![](assets/actions-data-sync-faq-1.png)

Het diagram hierboven toont hoe de menselijke activiteit en de taakgegevens tussen systemen kunnen synchroniseren. Een paar dingen:

* Personenrecords worden gesynchroniseerd met Verkoopacties van Insight vanuit Marketo Engage, waardoor Marketo Engage de bron van de waarheid wordt voor de gegevens van Sales Insight Actions
* Zowel hebben de Acties van Marketo Engage als van Insight van de Verkoop [ een mechanisme ](/help/marketo/product-docs/marketo-sales-insight/actions/email/unsubscribes/syncing-unsubscribes-with-salesforce.md) voor het verzamelen van en het synchroniseren van unsubscript status aan Salesforce
* De status van Unsubscribe synchroniseert niet van de Acties van de Verkoop aan Marketo Engage, maar de Acties van Insight van de Verkoop kunnen worden gevormd om de status van Marketo te controleren Unsubscribe van mensen alvorens verkopers toe te staan om een e-mail met [ te verzenden Marketo Unsubscribe Controle ](/help/marketo/product-docs/marketo-sales-insight/actions/email/unsubscribes/marketo-unsubscribe-check.md).

Hieronder volgen enkele veelgestelde vragen over de werking van het synchroniseren van gegevens.

## Welke lood/contacten worden gesynchroniseerd aan de Acties van Insight van de Verkoop? {#what-lead-contacts-are-synced}

![](assets/actions-data-sync-faq-2.png)

De leiders en de contacten die een verkoopeigenaar hebben aan hen wordt toegewezen zullen in de Acties van de Verkoop worden gesynchroniseerd.

U kunt zien of heeft een lood/contact een verkoopeigenaar in Salesforce door het standaard eigenaargebied te bekijken dat bestaat.

De eigenaar van de verkoop hoeft niet de synchronisatiegebruiker van Marketo of een specifieke Salesforce of verkoopgebruiker te zijn. Alles wat we nodig hebben, is dat er een gebruiker wordt vermeld in het veld voor de eigenaar van de lead en de eigenaar van de contactpersoon in Salesforce, zodat we deze kunnen identificeren als verkooplead en synchroniseren met Sales Insight Actions. Alle updates van de velden waarmee we synchroniseren, worden ook gedetecteerd en bijgewerkt in Handelingen van Sales Insight.

## Waar worden de activiteitsgegevens die worden weergegeven in het Smart Grid van Sales Insight vandaan gehaald? {#where-does-the-activity-data-get-sourced-from}

![](assets/actions-data-sync-faq-3.png)

De activiteitsgegevens, zoals email, call, interessant moment en web, zijn allemaal afkomstig uit de Marketo Engage-database. Het Smart Grid van de Verkoop Insight richt een verzoek aan de instantie van Marketo Engage om dit terug te winnen telkens als een verkoopgebruiker het paneel van Insight van de Verkoop laadt.

![](assets/actions-data-sync-faq-4.png)

Om ervoor te zorgen dat alle activiteitsgegevens van Marketo Engage kunnen worden aangeschaft, synchroniseert Sales Insight Actions alle activiteitsgegevens naar Marketo Engage.

## Welke velden voor persoonrecords synchroniseren van Marketo Engage naar Handelingen voor Insight voor verkoop? {#what-fields-sync}

Er zijn 11 velden die worden gesynchroniseerd van Marketo Engage naar Sales Insight Actions:

* Voornaam
* Achternaam
* Salesforce contact-id
* Salesforce lead-id
* Salesforce-account-id
* ID Salesforce-opportuniteit
* Marketo-id
* Bedrijf
* Titel
* E-mail
* Telefoonnummer
* Koppeling in URL
* Bron

## Zijn de gebieden die tussen de Acties van Marketo Engage en van Insight van de Verkoop configureerbaar? {#are-the-fields-that-sync-configurable}

Het configureren van welke Marketo Engage-velden worden gesynchroniseerd met Sales Insight Actions is niet beschikbaar en het is ook niet mogelijk om velden toe te wijzen. Bij de synchronisatie vanuit Marketo worden standaard Marketo-velden automatisch toegewezen aan standaardvelden in je Verkoopactie-exemplaar.

## Waarom heeft de Acties van Insight van de Verkoop zijn eigen gegevensbestand? {#why-does-actions-have-its-own-database}

De Acties van Insight van de verkoop hebben zijn eigen Webtoepassing met een specifieke persoon en activiteitengegevensbestand om een geoptimaliseerde werkruimte te verstrekken die voor verkoopteams wordt gebouwd en wordt ontworpen. Zo kunnen verkoopmanagers en verkopers over voldoende ruimte beschikken om hun servicestrategie uit te werken en te beheren   zonder toegang of privileges toe te kennen aan de primaire Marketo Engage-werkruimte, die is geoptimaliseerd voor marketingspecialisten.

## Hoe worden duplicaten afgehandeld? {#how-are-duplicates-handled}

Uw database met verkoopacties bevat een kopie van de gekwalificeerde personen (leads/contacten met een eigenaar van de verkoop) die in uw Marketo Engage-database aanwezig zijn. Dit betekent dat als er twee records zijn met hetzelfde e-mailadres dat in Marketo is gemaakt, er een dubbele record wordt gemaakt in Verkoopacties.

## Hoe lang duurt het voordat de eerste synchronisatie is voltooid? {#how-long-initial-sync}

Het eerste proces voor het synchroniseren van al uw gegevens van de verkooplood in een nieuwe instantie van de Acties van Insight van de Verkoop zal typisch mensen bij ongeveer 1.000 om de 1-2 minuten verwerken. Dit is slechts een schatting en kan variëren.

Zodra de eerste synchronisatie plaatsvindt en al uw verkoopinstructies zijn ingevuld in uw exemplaar van de Sales Insight Actions-webapp, wordt er een incrementele synchronisatie uitgevoerd telkens wanneer een update wordt uitgevoerd naar een van de ondersteunde velden die worden gesynchroniseerd.

## Kunnen gebruikers van Handelingen van de Handelingen van de Verkoop Insight de gegevens van mensen van de Web app van Acties uitgeven? {#can-actions-users-edit-people-data}

Nee, de mogelijkheid om records voor personen te maken en te bewerken in Handelingen is niet beschikbaar voor zowel gebruikers als beheerders van de webapp Handelingen. Het maken en bewerken van mensen moet in Salesforce of Marketo Engage gebeuren. Sales Insight Actions gebruikt Marketo als bron van waarheid voor gegevens van mensen door voortdurend nieuwe gegevens te synchroniseren. Als een persoon in Marketo wordt bijgewerkt of gemaakt op basis van een workflow in Marketo of wordt gesynchroniseerd vanaf Salesforce, worden deze updates doorgegeven aan de database van de Sales Insight Actions-webtoepassing.

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

Ja, de activiteiten van de verkoopovereenkomst zullen aan Salesforce als inheemse taken registreren. Deze taken kunnen dan in de rapporten van Salesforce aan machtsteam dashboards worden gebruikt die verkoopactiviteiten volgen.

De Acties van Insight van de verkoop staan beheerders toe om te vormen welke verkoopactiviteiten aan Salesforce worden geregistreerd. Deze activiteiten omvatten e-mails, oproepen en open herinneringstaken.

![](assets/actions-data-sync-faq-6.png)

Het diagram hierboven toont welke informatie aan Salesforce wordt geregistreerd. De activiteiten zoals e-mail en de vraag worden geregistreerd aan Salesforce in a [ unidirectionele synchronisatie ](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-integration/sync-sales-activities-to-salesforce.md). [ Unsubscribes ](/help/marketo/product-docs/marketo-sales-insight/actions/email/unsubscribes/syncing-unsubscribes-with-salesforce.md) en [ de Taken van de Herinnering ](/help/marketo/product-docs/marketo-sales-insight/actions/tasks/reminder-task-sync-with-salesforce.md) worden gehouden bijgewerkt met een 2-wegsynchronisatie. Elk van deze gegevenssyncs is configureerbaar van de Web-app interface van Acties van de Handelingen van de Verkoop.

>[!MORELIKETHIS]
>
>* [ synchroniserend Unsubscribes met Salesforce ](/help/marketo/product-docs/marketo-sales-insight/actions/email/unsubscribes/syncing-unsubscribes-with-salesforce.md)
>* [ Marketo Unsubscribe Controle ](/help/marketo/product-docs/marketo-sales-insight/actions/email/unsubscribes/marketo-unsubscribe-check.md)
>* [ de Activiteiten van de Verkoop van de Synchronisatie aan Salesforce ](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-integration/sync-sales-activities-to-salesforce.md)
>* [ de Synchronisatie van de Taak van de herinnering met Salesforce ](/help/marketo/product-docs/marketo-sales-insight/actions/tasks/reminder-task-sync-with-salesforce.md)
>* [ initieert de Synchronisatie van Gegevens ](/help/marketo/product-docs/marketo-sales-insight/actions/getting-started/sales-insight-actions-admin-setup-guide.md#initiate-data-sync)
