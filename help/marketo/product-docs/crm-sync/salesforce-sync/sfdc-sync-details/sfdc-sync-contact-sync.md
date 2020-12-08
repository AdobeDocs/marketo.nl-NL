---
unique-page-id: 2953457
description: SFDC Sync - Contact Sync - Marketo Docs - Productdocumentatie
title: SFDC-synchronisatie - Contactsynchronisatie
translation-type: tm+mt
source-git-commit: 96cc6a30c63c8e8dca793a52e4bf7ecaef8c08dc
workflow-type: tm+mt
source-wordcount: '286'
ht-degree: 0%

---


# SFDC-synchronisatie: Synchroniseren {#sfdc-sync-contact-sync}

>[!NOTE]
>
>**FYI**
>
>Marketo is nu bezig met het standaardiseren van de taal voor alle abonnementen, dus u ziet mogelijk leads/leads in uw abonnement en personen/personen in docs.marketo.com. Deze termen betekenen hetzelfde. het heeft geen invloed op de instructies van het artikel . Er zijn nog enkele andere veranderingen. [Meer](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)informatie.

Wist u dat Marketo uw gehele database synchroniseert met Salesforce? Het synchroniseert, wacht dan 5 minuten en synchroniseert dan opnieuw, de hele dag, elke dag. Hier zijn sommige details over hoe Marketo Contacten Salesforce specifiek behandelt.

## Richting synchroniseren {#sync-direction}

De contactsynchronisatie is bidirectioneel. Als u wijzigingen aanbrengt in een contactpersoon in Salesforce of Marketo, worden de updates weerspiegeld in beide systemen.

## Wat gebeurt er als beide systemen tegelijkertijd worden gewijzigd? {#what-if-changes-are-made-in-both-systems-at-the-same-time}

We zijn aardig en laten Salesforce winnen. Het is zeldzaam dat dit soort botsing van gegevens voorkomt.

## Kan ik een persoon omzetten in een contactpersoon in Marketo? {#can-i-convert-a-person-into-a-contact-in-marketo}

Ja, gebruik de stroomactie ** [Persoon](../../../../product-docs/core-marketo-concepts/smart-campaigns/flow-actions/convert-person.md)converteren**.

>[!CAUTION]
>
>Het omzetten van een persoon in Marketo leidt tot een nieuwe account en een nieuwe kans in Salesforce. Als u geen dubbele accounts wilt, gebruikt u Salesforce om te converteren.

## Kan ik een synchronisatie van een contact manueel dwingen? {#can-i-manually-force-a-sync-of-a-contact}

Ja, gebruik ** [Synchroniseer Persoon aan SFDC](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md) **flow actie en het zal in real time synchroniseren.

## Synchroniseert elke standaard veld met Marketo? {#does-every-single-standard-field-sync-to-marketo}

Nee, niet alle standaardvelden zijn nuttig. Alle aangepaste velden kunnen onderdeel zijn van de synchronisatie.

>[!NOTE]
>
>Marketo synchroniseert alleen de velden waartoe uw Marketo Sync User toegang heeft.

## Zal Marketo de validatieregels van Salesforce respecteren? {#will-marketo-respect-the-salesforce-validation-rules}

Ja, als er een conflict is zal het het resultaat in het Logboek van de activiteit van de leads registreren.
