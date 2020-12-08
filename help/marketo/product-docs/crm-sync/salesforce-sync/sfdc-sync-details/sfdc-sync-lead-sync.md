---
unique-page-id: 2953455
description: SFDC Sync -Lead Sync - Marketo Docs - Productdocumentatie
title: SFDC Sync - Lead Sync
translation-type: tm+mt
source-git-commit: 96cc6a30c63c8e8dca793a52e4bf7ecaef8c08dc
workflow-type: tm+mt
source-wordcount: '288'
ht-degree: 0%

---


# SFDC-synchronisatie: Synchronisatie van lead {#sfdc-sync-lead-sync}

>[!NOTE]
>
>**FYI**
>
>Marketo is nu bezig met het standaardiseren van de taal voor alle abonnementen, dus u ziet mogelijk leads/leads in uw abonnement en personen/personen in docs.marketo.com. Deze termen betekenen hetzelfde. het heeft geen invloed op de instructies van het artikel . Er zijn nog enkele andere veranderingen. [Meer](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)informatie.

Wist u Marketo-syncs uit uw Salesforce-database? Het synchroniseert, wacht 5 minuten en synchroniseert vervolgens opnieuw. De hele dag, elke dag. Hier zijn een paar details over hoe Marketo Salesforce specifiek behandelt.

## Richting synchroniseren {#sync-direction}

De lead- (persoon) en contactsynchronisatie hebben twee richtingen. Als u wijzigingen aanbrengt in een record in Salesforce of Marketo, worden de updates weerspiegeld in beide systemen.

## Wat gebeurt er als beide systemen tegelijkertijd worden gewijzigd? {#what-if-changes-are-made-in-both-systems-at-the-same-time}

Marketo wint. Het is zeldzaam dat dit soort botsing van gegevens voorkomt.

## Kan ik een lead maken in Salesforce met Marketo? {#can-i-create-a-lead-in-salesforce-using-marketo}

Ja, gebruik de [stroomactie van de Persoon van de Synchronisatie aan SFDC](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md) . Dit zal een lood in Salesforce creëren als de lood niet bestaat.

## Kan ik handmatig een synchronisatie van een persoon in Marketo naar een lead in Salesforce forceren? {#can-i-manually-force-a-sync-of-a-person-in-marketo-to-a-lead-in-salesforce}

Ja, gebruik de [Synchronisatiepersoon naar SFDC](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md) -flowactie en deze synchroniseert in real-time.

## Synchroniseert elke standaard veld met Marketo? {#does-every-single-standard-field-sync-to-marketo}

Nee, niet alle standaardvelden zijn nuttig. Alle aangepaste velden kunnen onderdeel zijn van de synchronisatie.

>[!NOTE]
>
>Marketo synchroniseert alleen de velden waartoe uw Salesforce-synchronisatiegebruiker toegang heeft.

## Zal Marketo de validatieregels van Salesforce respecteren? {#will-marketo-respect-the-salesforce-validation-rules}

Ja. De synchronisatie mislukt als de gegevensindeling onjuist is of als de vereiste veldgegevens ontbreken. Marketo registreert het resultaat in het Logboek van de activiteit van de leads als dit gebeurt.
