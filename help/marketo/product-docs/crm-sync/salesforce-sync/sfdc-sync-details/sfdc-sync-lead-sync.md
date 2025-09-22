---
unique-page-id: 2953455
description: SFDC Sync - Lead Sync - Marketo Docs - Productdocumentatie
title: SFDC Sync - Lead Sync
exl-id: cf38e091-7344-4b95-b9e1-77eda751c4a9
feature: Salesforce Integration
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '230'
ht-degree: 0%

---

# SFDC Sync: Lead Sync {#sfdc-sync-lead-sync}

Wist u Marketo-syncs van uw [!DNL Salesforce] -database? Het synchroniseert, wacht 5 minuten en synchroniseert vervolgens opnieuw. De hele dag, elke dag. Hier volgt een aantal details over hoe Marketo [!DNL Salesforce] specifiek behandelt.

## Richting synchroniseren {#sync-direction}

De lead- (persoon) en contactsynchronisatie hebben twee richtingen. Als u wijzigingen aanbrengt in een record in [!DNL Salesforce] of Marketo, worden de updates weerspiegeld in beide systemen.

## Wat gebeurt er als beide systemen tegelijkertijd worden gewijzigd? {#what-if-changes-are-made-in-both-systems-at-the-same-time}

Marketo wint. Het is zeldzaam dat dit soort botsing van gegevens voorkomt.

## Kan ik een lead maken in [!DNL Salesforce] met Marketo? {#can-i-create-a-lead-in-salesforce-using-marketo}

Ja, gebruik de [ Persoon van de Synchronisatie aan SFDC ](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md) stroomactie. Hierdoor wordt een lead in [!DNL Salesforce] gemaakt als de lead niet bestaat.

## Kan ik handmatig een persoon in Marketo synchroniseren naar een lead in [!DNL Salesforce]? {#can-i-manually-force-a-sync-of-a-person-in-marketo-to-a-lead-in-salesforce}

Ja, gebruik de [ Persoon van de Synchronisatie aan SFDC ](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md){target="_blank"} stroomactie en het zal in real time synchroniseren.

## Synchroniseert elke standaard veld met Marketo? {#does-every-single-standard-field-sync-to-marketo}

Nee, niet alle standaardvelden zijn nuttig. Alle aangepaste velden kunnen onderdeel zijn van de synchronisatie.

>[!NOTE]
>
>Marketo synchroniseert alleen de velden waartoe uw [!DNL Salesforce] synchronisatiegebruiker toegang heeft.

## Zal Marketo de validatieregels van [!DNL Salesforce] naleven? {#will-marketo-respect-the-salesforce-validation-rules}

Ja. De synchronisatie mislukt als de gegevensindeling onjuist is of als de vereiste veldgegevens ontbreken. Marketo registreert het resultaat in het activiteitenlog voor leads als dit gebeurt.
