---
unique-page-id: 3571844
description: Microsoft Dynamics Sync - Opportunity Sync - Marketo Docs - Productdocumentatie
title: Microsoft Dynamics Sync - Opportunity Sync
exl-id: dcb72f28-c980-4183-8473-a1e5ad0c8d3c
feature: Microsoft Dynamics
source-git-commit: 9a130e0b2ec84b638adf37188b65b565b090fe1b
workflow-type: tm+mt
source-wordcount: '311'
ht-degree: 0%

---

# Microsoft Dynamics Sync: Opportunity Sync {#microsoft-dynamics-sync-opportunity-sync}

Synchronisatie van Marketo Engage naar dynamiek is superkrachtig. Hier zijn alle details voor opportunitysynchronisatie.

## Hoe worden de opportuniteitsgegevens gesynchroniseerd tussen de twee systemen? {#how-are-opportunity-details-kept-in-sync-between-the-two-systems}

De opportuniteitssynchronisatie is één manier: Dynamics to Marketo. Als u wijzigingen aanbrengt aan een optie in Dynamics, wordt uw update weerspiegeld in Marketo.

## Kan ik een kans maken in Dynamics met Marketo? {#can-i-create-an-opportunity-in-dynamics-using-marketo}

Nee, u moet de mogelijkheid creëren in Dynamics en deze wordt automatisch gesynchroniseerd met Marketo.

## Welke velden worden gesynchroniseerd met Marketo? {#what-fields-will-sync-to-marketo}

U kunt [te synchroniseren velden selecteren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-4-of-4-connect.md#select-fields-to-sync){target="_blank"} tijdens installatie.

## Hoe wordt een account/contactpersoon gekoppeld aan een opportunity? {#how-is-an-account-contact-associated-with-an-opportunity}

Het contact/de Rekening kan aan Kans op twee manieren worden geassocieerd:

* Tijdens het maken van een opportuniteit kunt u het contactveld (opzoekveld op het formulier waarmee u contact wilt opnemen) en/of de account (opzoekveld op het formulier met account) instellen. In beide gevallen worden deze waarden opgeslagen in het veld Potentiële klant (CustomerID) in Dynamics. Dit veld wordt niet weergegeven in het opportuniteitsformulier, maar kan worden toegevoegd vanuit instellingen. Dit veld kan slechts 1 waarde bevatten, contactpersoon of account. Marketo doet het volgende:

   * Als de contactwaarde is ingesteld en het account leeg blijft, maakt Marketo een `opportunitycontactrole` en stelt de account bij de opportuniteit in op de account van de contactpersoon. Als de contactpersoon geen account heeft, is dit veld leeg.
   * Als de waarde van de account is ingesteld en de contactpersoon leeg blijft, stelt Marketo alleen de account bij gelegenheid in op deze account.
   * Als beide waarden zijn ingesteld, wordt de rekening Dynamics picks gebruikt als de waarde voor customerid, zodat het gedrag hetzelfde zou zijn als hierboven.


* Via belanghebbenden: de dynamiek gebruikt verbindingen om kans te verbinden om door belanghebbenden van de kans te contacteren creeert pagina. Hiervoor zullen we een `opportunitycontactrole` verslag voor elke nieuwe belanghebbende.
