---
unique-page-id: 2953457
description: Meer informatie over hoe contactsynchronisatie werkt tussen Salesforce en Marketo. Begrijp bidirectionele synchronisatie, zet mensen in contacten, en forceer synchronisatie met stroomacties.
title: SFDC Sync - Contact opnemen met Sync
exl-id: 537bbc95-9233-4454-892e-81f962cf729d
feature: Salesforce Integration
source-git-commit: 2b29f05a27f847184e0968442012d443e9e0597d
workflow-type: tm+mt
source-wordcount: '244'
ht-degree: 0%

---

# SFDC Sync: Contact opnemen met Sync {#sfdc-sync-contact-sync}

Wist u dat Marketo uw gehele database synchroniseert met [!DNL Salesforce] ? Het synchroniseert, wacht dan 5 minuten en synchroniseert dan opnieuw, de hele dag, elke dag. Hier volgt een aantal details over hoe Marketo [!DNL Salesforce] Contactpersonen specifiek behandelt.

## Richting synchroniseren {#sync-direction}

De contactsynchronisatie is bidirectioneel. Als u wijzigingen aanbrengt in een contactpersoon in [!DNL Salesforce] of Marketo, worden de updates weerspiegeld in beide systemen.

## Wat gebeurt er als beide systemen tegelijkertijd worden gewijzigd? {#what-if-changes-are-made-in-both-systems-at-the-same-time}

We zijn aardig en laten [!DNL Salesforce] winnen. Het is zeldzaam dat dit soort botsing van gegevens voorkomt.

## Kan ik een persoon omzetten in een contactpersoon in Marketo? {#can-i-convert-a-person-into-a-contact-in-marketo}

Ja, gebruik **[de stroomactie van de Persoon van de Bekeerling](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/convert-person.md){target="_blank"}**.

>[!CAUTION]
>
>Het converteren van een persoon in Marketo resulteert in een nieuwe account en in een nieuwe mogelijkheid in [!DNL Salesforce] . Als u geen dubbele accounts wilt, gebruikt u [!DNL Salesforce] om te converteren.

## Kan ik een synchronisatie van een contact manueel dwingen? {#can-i-manually-force-a-sync-of-a-contact}

Ja, gebruik de **[Persoon van de Synchronisatie aan SFDC](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md){target="_blank"}** stroomactie en het zal in real time synchroniseren.

## Synchroniseert elke standaard veld met Marketo? {#does-every-single-standard-field-sync-to-marketo}

Nee, niet alle standaardvelden zijn nuttig. Alle aangepaste velden kunnen onderdeel zijn van de synchronisatie.

>[!NOTE]
>
>Marketo synchroniseert alleen de velden waartoe uw Marketo Sync-gebruiker toegang heeft.

## Zal Marketo de validatieregels van [!DNL Salesforce] naleven? {#will-marketo-respect-the-salesforce-validation-rules}

Ja, als er een conflict is zal het het resultaat in het Logboek van de activiteit van de leads registreren.
