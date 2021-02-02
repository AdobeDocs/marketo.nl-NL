---
unique-page-id: 3571833
description: Microsoft Dynamics Sync - Contact Sync - Marketo Docs - Productdocumentatie
title: Microsoft Dynamics Sync - Contact opnemen met Sync
translation-type: tm+mt
source-git-commit: 2b5ccd7220557a5e966d33436d0f0d2a65e4589d
workflow-type: tm+mt
source-wordcount: '277'
ht-degree: 0%

---


# Microsoft Dynamics Sync: Contactsynchronisatie {#microsoft-dynamics-sync-contact-sync}

Wist u Marketo uw volledige database synchroniseert met Dynamics? Het synchroniseert, wacht dan 5 minuten en synchroniseert dan opnieuw, de hele dag, elke dag. Hier zijn sommige details over hoe Marketo de Contacten van de Dynamiek specifiek behandelt.

## Hoe worden de details synchroon gehouden tussen beide systemen? {#how-are-details-kept-in-sync-between-the-two-systems}

De contactsynchronisatie is bidirectioneel. Als u veranderingen in een contact in Dynamiek of een persoon in Marketo aanbrengt, zullen uw updates in beide systemen worden weerspiegeld.

## Wat gebeurt er als er tegelijkertijd in beide systemen wijzigingen in hetzelfde veld worden aangebracht? (Gegevensconflict) {#what-if-changes-are-made-to-the-same-field-in-both-systems-at-the-same-time-data-collision}

Hoewel dit zeldzaam is, zal Marketo voor mensen winnen en de Dynamiek voor contacten zal winnen. Dit komt omdat wij de marketingafdeling als gezaghebbend voor mensen beschouwen, terwijl het officiële systeem van verslagen voor contacten in de verkoopafdeling (CRM) is.

## Kan ik een contactpersoon maken met Marketo? {#can-i-create-a-contact-using-marketo}

Ja. [Zo](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-lead-sync/create-a-contact-in-microsoft-dynamics.md).

>[!NOTE]
>
>Wanneer het gebruiken van de &quot;Persoon van de Synchronisatie aan Microsoft&quot;stroomactie (in een trekkercampagne slechts), zal het lood/het contact in real time in Dynamiek worden gecreeerd.

## Kan ik een synchronisatie van een persoon of een contact manueel dwingen? {#can-i-manually-force-a-sync-of-a-person-or-a-contact}

Nee, de geautomatiseerde achtergrondsynchronisatie is de enige manier om updates tussen Marketo en Dynamics te synchroniseren. De [Persoon synchroniseren naar Microsoft](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/microsoft-dynamics-flow-actions/sync-person-to-microsoft.md) zal geen synchronisatie van de lead afdwingen.

## Welke velden worden gesynchroniseerd met Marketo? {#what-fields-will-sync-to-marketo}

Tijdens de installatie kunt u [velden selecteren om te synchroniseren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365/step-3-of-3-connect.md#select-fields-to-sync). Marketo synchroniseert echter alleen de velden waartoe de synchronisatiegebruiker van de dynamiek toegang heeft.

## Zal Marketo de Dynamische bevestigingsregels naleven? {#will-marketo-respect-the-dynamics-validation-rules}

Ja, als er een conflict is zal het het resultaat in het Logboek van de activiteit van de leads registreren.
