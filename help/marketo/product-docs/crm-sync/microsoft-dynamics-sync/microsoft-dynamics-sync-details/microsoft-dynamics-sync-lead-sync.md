---
unique-page-id: 3571848
description: Microsoft Dynamics Sync - Lead Sync - Marketo Docs - Productdocumentatie
title: Microsoft Dynamics Sync - Lead Sync
translation-type: tm+mt
source-git-commit: 2b5ccd7220557a5e966d33436d0f0d2a65e4589d
workflow-type: tm+mt
source-wordcount: '307'
ht-degree: 0%

---


# Microsoft Dynamics Sync: Synchronisatie van lead {#microsoft-dynamics-sync-lead-sync}

Synchronisatie tussen Marketo en Dynamics is bijzonder krachtig. Hier volgen de details:

## Hoe worden de details synchroon gehouden tussen beide systemen? {#how-are-details-kept-in-sync-between-the-two-systems}

De synchronisatie is bidirectioneel. Als u veranderingen in of een lood in Dynamiek of een persoon in Marketo aanbrengt, zal uw update in beide systemen worden weerspiegeld.

>[!NOTE]
>
>Verwijderen synchroniseert niet altijd automatisch in beide richtingen. Zie [Een lead of contact verwijderen](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/deleting-a-lead-or-contact.md).

## Wat gebeurt er als er tegelijkertijd in beide systemen wijzigingen in hetzelfde veld worden aangebracht? (Gegevensconflict) {#what-if-changes-are-made-to-the-same-field-in-both-systems-at-the-same-time-data-collision}

Hoewel dit zeldzaam is, zal Marketo voor mensen (lood) winnen en de Dynamiek voor contacten zal winnen. Dit komt omdat wij de marketingafdeling als gezaghebbend voor mensen beschouwen, terwijl het officiële systeem van verslagen voor contacten in de verkoopafdeling (CRM) is.

## Kan ik een lead maken in Dynamics met Marketo? {#can-i-create-a-lead-in-dynamics-using-marketo}

Ja, gebruik [Persoon synchroniseren naar Microsoft](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/microsoft-dynamics-flow-actions/sync-person-to-microsoft.md) stroomactie. Dit zal tot een lood in Dynamica leiden als de lood niet bestaat. Als de lead wel bestaat, voert de flowstap geen actie uit.

>[!NOTE]
>
>Wanneer het gebruiken van de &quot;Persoon van de Synchronisatie aan Microsoft&quot;stroomactie (in een trekkercampagne slechts), zal het lood/het contact in real time in Dynamiek worden gecreeerd.

## Kan ik handmatig een synchronisatie van een persoon van Marketo naar een lead in Dynamics forceren? {#can-i-manually-force-a-sync-of-a-person-from-marketo-to-a-lead-in-dynamics}

Nee, de geautomatiseerde achtergrondsynchronisatie is de enige manier om updates tussen Marketo en Dynamics te synchroniseren. Met de stroomactie [Persoon synchroniseren naar Microsoft](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/microsoft-dynamics-flow-actions/sync-person-to-microsoft.md) wordt geen synchronisatie van de lead geforceerd.

## Welke velden worden gesynchroniseerd met Marketo? {#what-fields-will-sync-to-marketo}

Tijdens de installatie kunt u [velden selecteren om te synchroniseren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365/step-3-of-3-connect.md#select-fields-to-sync).

## Zal Marketo de Dynamische bevestigingsregels naleven? {#will-marketo-respect-the-dynamics-validation-rules}

Ja. De synchronisatie mislukt als de gegevensindeling onjuist is of als de vereiste veldgegevens ontbreken. Marketo registreert het resultaat in het activiteitenlogboek van de persoon als dit gebeurt.
