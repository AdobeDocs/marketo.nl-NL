---
unique-page-id: 2953455
description: SFDC Sync - Lead Sync - Marketo Docs - Productdocumentatie
title: SFDC Sync - Lead Sync
exl-id: cf38e091-7344-4b95-b9e1-77eda751c4a9
feature: Salesforce Integration
source-git-commit: 0087a5e88b8bd9601875f68a2e7cadeebdb5d682
workflow-type: tm+mt
source-wordcount: '238'
ht-degree: 0%

---

# SFDC Sync: Lead Sync {#sfdc-sync-lead-sync}

Wist u Marketo Engage syncs van uw gegevensbestand Salesforce? Het synchroniseert, wacht 5 minuten en synchroniseert vervolgens opnieuw. De hele dag, elke dag. Hier zijn wat details over hoe Marketo Salesforce specifiek behandelt.

## Richting synchroniseren {#sync-direction}

De lead- (persoon) en contactsynchronisatie hebben twee richtingen. Als u wijzigingen aanbrengt in een record in Salesforce of Marketo, worden de updates weerspiegeld in beide systemen.

## Wat gebeurt er als beide systemen tegelijkertijd worden gewijzigd? {#what-if-changes-are-made-in-both-systems-at-the-same-time}

Marketo wint. Het is zeldzaam dat dit soort botsing van gegevens voorkomt.

## Kan ik een lead maken in Salesforce met Marketo? {#can-i-create-a-lead-in-salesforce-using-marketo}

Ja, gebruik de [Persoon synchroniseren naar SFDC](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md){target="_blank"} Handeling flow. Dit zal een lood in Salesforce creëren als de lood niet bestaat.

## Kan ik handmatig een persoon in Marketo synchroniseren naar een leider in Salesforce? {#can-i-manually-force-a-sync-of-a-person-in-marketo-to-a-lead-in-salesforce}

Ja, gebruik de [Persoon synchroniseren naar SFDC](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md){target="_blank"} en wordt in real-time gesynchroniseerd.

## Synchroniseert elke standaard veld met Marketo? {#does-every-single-standard-field-sync-to-marketo}

Nee, niet alle standaardvelden zijn nuttig. Alle aangepaste velden kunnen onderdeel zijn van de synchronisatie.

>[!NOTE]
>
>Marketo synchroniseert alleen de velden waartoe uw Salesforce-synchronisatiegebruiker toegang heeft.

## Zal Marketo de regels voor de validatie van Salesforce naleven? {#will-marketo-respect-the-salesforce-validation-rules}

Ja. De synchronisatie mislukt als de gegevensindeling onjuist is of als de vereiste veldgegevens ontbreken. Marketo registreert het resultaat in het activiteitenlog voor leads als dit gebeurt.
