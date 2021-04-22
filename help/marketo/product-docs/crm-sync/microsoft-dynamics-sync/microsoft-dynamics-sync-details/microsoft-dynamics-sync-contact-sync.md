---
unique-page-id: 3571833
description: Microsoft Dynamics Sync - Contact Sync - Marketo Docs - Productdocumentatie
title: Microsoft Dynamics Sync - Contact opnemen met Sync
exl-id: d4583ea0-2b52-415e-b28c-a8eafebeff64
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '277'
ht-degree: 0%

---

# Microsoft Dynamics Sync: Contactsynchronisatie {#microsoft-dynamics-sync-contact-sync}

Wist u dat Marketo uw gehele database synchroniseert met Dynamics? Het synchroniseert, wacht dan 5 minuten en synchroniseert dan opnieuw, de hele dag, elke dag. Hier zijn sommige details over hoe Marketo de Contacten van de Dynamiek specifiek behandelt.

## Hoe worden de details synchroon gehouden tussen beide systemen? {#how-are-details-kept-in-sync-between-the-two-systems}

De contactsynchronisatie is bidirectioneel. Als u wijzigingen aanbrengt in een contactpersoon in Dynamics of een persoon in Marketo, worden de updates weergegeven in beide systemen.

## Wat gebeurt er als er tegelijkertijd in beide systemen wijzigingen in hetzelfde veld worden aangebracht? (Gegevensconflict) {#what-if-changes-are-made-to-the-same-field-in-both-systems-at-the-same-time-data-collision}

Hoewel dit zeldzaam is, zal Marketo winnen voor mensen en Dynamics zal winnen voor contacten. Dit komt omdat wij de marketingafdeling als gezaghebbend voor mensen beschouwen, terwijl het officiële systeem van verslagen voor contacten in de verkoopafdeling (CRM) is.

## Kan ik een contactpersoon maken met Marketo? {#can-i-create-a-contact-using-marketo}

Ja. [Zo](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-lead-sync/create-a-contact-in-microsoft-dynamics.md).

>[!NOTE]
>
>Wanneer het gebruiken van de &quot;Persoon van de Synchronisatie aan Microsoft&quot;stroomactie (in een trekkercampagne slechts), zal het lood/het contact in real time in Dynamiek worden gecreeerd.

## Kan ik een synchronisatie van een persoon of een contact manueel dwingen? {#can-i-manually-force-a-sync-of-a-person-or-a-contact}

Nee, de automatische achtergrondsynchronisatie is de enige manier om updates te synchroniseren tussen Marketo en Dynamics. De [Persoon synchroniseren naar Microsoft](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/microsoft-dynamics-flow-actions/sync-person-to-microsoft.md) zal geen synchronisatie van de lead afdwingen.

## Welke velden worden gesynchroniseerd met Marketo? {#what-fields-will-sync-to-marketo}

Tijdens de installatie kunt u [velden selecteren om te synchroniseren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365/step-3-of-3-connect.md#select-fields-to-sync). Maar Marketo synchroniseert alleen de velden waartoe de gebruiker van het Dynamic Sync toegang heeft.

## Zal Marketo de regels voor Dynamische validatie naleven? {#will-marketo-respect-the-dynamics-validation-rules}

Ja, als er een conflict is zal het het resultaat in het Logboek van de activiteit van de leads registreren.
