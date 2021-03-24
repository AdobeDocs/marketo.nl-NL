---
unique-page-id: 3571838
description: Microsoft Dynamics Sync -Field Sync - Marketo Docs - Productdocumentatie
title: Microsoft Dynamics Sync - Field Sync
translation-type: tm+mt
source-git-commit: ed9399396c82a3b2fb93c83ffdaa1dc7b0827306
workflow-type: tm+mt
source-wordcount: '337'
ht-degree: 0%

---


# Microsoft Dynamics Sync: Veldsynchronisatie {#microsoft-dynamics-sync-field-sync}

Synchronisatie tussen Marketo en Dynamics is bijzonder krachtig. Hier zijn de details.

## Hoe worden de velddetails synchroon gehouden tussen de twee systemen? {#how-are-field-details-kept-in-sync-between-the-two-systems}

De synchronisatie is bidirectioneel voor lood en contactentiteiten. Als u veranderingen in een lood of een contact in Dynamiek of een persoon in Marketo aanbrengt, zullen uw updates in beide systemen worden weerspiegeld.

Voor account, gebruiker, opportunity, team en aangepaste entiteiten is de synchronisatie in één richting: Dynamiek naar Marketo. Als u wijzigingen aanbrengt in deze entiteiten in Dynamiek, worden uw updates weerspiegeld in Marketo.

## Wat gebeurt er als er tegelijkertijd in beide systemen wijzigingen in hetzelfde veld worden aangebracht? (Gegevensconflict) {#what-if-changes-are-made-to-the-same-field-in-both-systems-at-the-same-time-data-collision}

Hoewel dit zeldzaam is, zal Marketo voor mensen (lood) winnen en de Dynamiek voor contacten zal winnen. Dit komt omdat wij de marketingafdeling als gezaghebbend voor mensen beschouwen, terwijl het officiële systeem van verslagen voor contacten in de verkoopafdeling (CRM) is. Bij one-way sync-entiteiten wint Dynamics altijd.

## Kan ik een veld in Dynamiek creëren gebruikend Marketo? {#can-i-create-a-field-in-dynamics-using-marketo}

Nee, dit wordt momenteel niet ondersteund.

## Ik creëerde een veld in Dynamics. Kan ik het synchroniseren met Marketo? {#i-created-a-field-in-dynamics-can-i-sync-it-to-marketo}

Ja, u kunt [het veld ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365/step-3-of-3-connect.md#select-fields-to-sync) synchroniseren zolang uw synchronisatiegebruiker er toegang toe heeft in Dynamics.

## Welke velden worden gesynchroniseerd met Marketo? {#what-fields-will-sync-to-marketo}

Tijdens de installatie kunt u [velden selecteren om te synchroniseren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365/step-3-of-3-connect.md#select-fields-to-sync).

## Wat als ik een douanegebied moet toevoegen nadat de Marketo en de Dynamica worden gesynchroniseerd? {#what-if-i-need-to-add-a-custom-field-after-marketo-and-dynamics-are-synced}

U kunt velden op elk gewenst moment toevoegen en verwachten dat de gegevens worden vernieuwd van Dynamiek naar Marketo. Zie [Snelle Synchronisatie met de Dynamica van Microsoft voor een Nieuw Geëigend Gebied ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-field-sync/use-quick-sync-with-microsoft-dynamics-for-a-new-custom-field.md) voor details gebruiken.

## Wat gebeurt er als ik een veld in Dynamiek wil verwijderen nadat het veld is toegevoegd aan synchronisatie? {#what-if-i-want-to-delete-a-field-in-dynamics-after-the-field-has-been-added-to-sync}

Marketo slaat een verwijzing naar de te synchroniseren velden op. Als u een gebied in Dynamiek schrapt, adviseren wij dit met [sync gehandicapt](/help/marketo/product-docs/crm-sync/salesforce-sync/enable-disable-the-salesforce-sync.md). Vernieuw vervolgens het schema in Marketo door de [Selecteer te synchroniseren velden ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-field-sync/editing-fields-to-sync-before-deleting-them-in-dynamics.md) te bewerken en op te slaan.