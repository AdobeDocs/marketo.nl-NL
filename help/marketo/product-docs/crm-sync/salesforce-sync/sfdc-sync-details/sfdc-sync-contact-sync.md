---
unique-page-id: 2953457
description: SFDC-synchronisatie - Contactsynchronisatie - Marketo-documenten - Productdocumentatie
title: SFDC-synchronisatie - Contactsynchronisatie
exl-id: 537bbc95-9233-4454-892e-81f962cf729d
feature: Salesforce Integration
source-git-commit: 0087a5e88b8bd9601875f68a2e7cadeebdb5d682
workflow-type: tm+mt
source-wordcount: '236'
ht-degree: 0%

---

# SFDC-synchronisatie: contact opnemen met Synchronisatie {#sfdc-sync-contact-sync}

Wist je dat Marketo Engage je hele database synchroniseert met Salesforce? Het synchroniseert, wacht dan 5 minuten en synchroniseert dan opnieuw, de hele dag, elke dag. Hier zijn een paar details over hoe Marketo Salesforce Contacten specifiek behandelt.

## Richting synchroniseren {#sync-direction}

De contactsynchronisatie is bidirectioneel. Als u wijzigingen aanbrengt in een contactpersoon in Salesforce of Marketo, worden uw updates weerspiegeld in beide systemen.

## Wat gebeurt er als beide systemen tegelijkertijd worden gewijzigd? {#what-if-changes-are-made-in-both-systems-at-the-same-time}

We zijn aardig en laten Salesforce winnen. Het is zeldzaam dat dit soort botsing van gegevens voorkomt.

## Kan ik een persoon omzetten in een contactpersoon in Marketo? {#can-i-convert-a-person-into-a-contact-in-marketo}

Ja, gebruik de **[Persoon omzetten](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/convert-person.md){target="_blank"}** Handeling flow.

>[!CAUTION]
>
>Het omzetten van een persoon in Marketo leidt tot een nieuwe account en een nieuwe kans in Salesforce. Als u geen dubbele accounts wilt, gebruikt u Salesforce om te zetten.

## Kan ik een synchronisatie van een contact manueel dwingen? {#can-i-manually-force-a-sync-of-a-contact}

Ja, gebruik de **[Persoon synchroniseren naar SFDC](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md){target="_blank"}** en wordt in real-time gesynchroniseerd.

## Synchroniseert elke standaard veld met Marketo? {#does-every-single-standard-field-sync-to-marketo}

Nee, niet alle standaardvelden zijn nuttig. Alle aangepaste velden kunnen onderdeel zijn van de synchronisatie.

>[!NOTE]
>
>Marketo synchroniseert alleen de velden waartoe uw Marketo Sync-gebruiker toegang heeft.

## Zal Marketo de regels voor de validatie van Salesforce naleven? {#will-marketo-respect-the-salesforce-validation-rules}

Ja, als er een conflict is zal het het resultaat in het Logboek van de activiteit van de leads registreren.
