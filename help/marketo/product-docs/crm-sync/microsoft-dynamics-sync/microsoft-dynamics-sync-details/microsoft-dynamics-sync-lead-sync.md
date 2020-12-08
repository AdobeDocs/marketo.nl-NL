---
unique-page-id: 3571848
description: Microsoft Dynamics Sync - Lead Sync - Marketo Docs - Productdocumentatie
title: Microsoft Dynamics Sync - Lead Sync
translation-type: tm+mt
source-git-commit: 96cc6a30c63c8e8dca793a52e4bf7ecaef8c08dc
workflow-type: tm+mt
source-wordcount: '322'
ht-degree: 0%

---


# Microsoft Dynamics Sync: Synchronisatie van lead {#microsoft-dynamics-sync-lead-sync}

Synchronisatie tussen Marketo en Dynamics is bijzonder krachtig. Hier volgen de details:

## Hoe worden de details synchroon gehouden tussen beide systemen? {#how-are-details-kept-in-sync-between-the-two-systems}

De synchronisatie is bidirectioneel. Als u veranderingen in of een lood in Dynamiek of een persoon in Marketo aanbrengt, zal uw update in beide systemen worden weerspiegeld.

>[!NOTE]
>
>Verwijderen synchroniseert niet altijd automatisch in beide richtingen. Zie [Een lead of contactpersoon](http://docs.marketo.com/x/agO1Ag)verwijderen.

## Wat gebeurt er als er tegelijkertijd in beide systemen wijzigingen in hetzelfde veld worden aangebracht? (Gegevensconflict) {#what-if-changes-are-made-to-the-same-field-in-both-systems-at-the-same-time-data-collision}

Hoewel dit zeldzaam is, zal Marketo voor mensen (lood) winnen en de Dynamiek voor contacten zal winnen. Dit komt omdat wij de marketingafdeling als gezaghebbend voor mensen beschouwen, terwijl het officiële systeem van verslagen voor contacten in de verkoopafdeling (CRM) is.

## Kan ik een lead maken in Dynamics met Marketo? {#can-i-create-a-lead-in-dynamics-using-marketo}

Ja, gebruik de actie Person [synchroniseren met Microsoft](../../../../product-docs/core-marketo-concepts/smart-campaigns/microsoft-dynamics-flow-actions/sync-person-to-microsoft.md) -stroom. Dit zal tot een lood in Dynamica leiden als de lood niet bestaat. Als de lead wel bestaat, voert de flowstap geen actie uit.

>[!NOTE]
>
>Wanneer het gebruiken van de &quot;Persoon van de Synchronisatie aan Microsoft&quot;stroomactie (in een trekkercampagne slechts), zal het lood/het contact in real time in Dynamiek worden gecreeerd.

## Kan ik handmatig een synchronisatie van een persoon van Marketo naar een lead in Dynamics forceren? {#can-i-manually-force-a-sync-of-a-person-from-marketo-to-a-lead-in-dynamics}

Nee, de geautomatiseerde achtergrondsynchronisatie is de enige manier om updates tussen Marketo en Dynamics te synchroniseren. Met de [stroomactie Persoon synchroniseren naar Microsoft](../../../../product-docs/core-marketo-concepts/smart-campaigns/microsoft-dynamics-flow-actions/sync-person-to-microsoft.md) wordt geen synchronisatie van de lead geforceerd.

## Welke velden worden gesynchroniseerd met Marketo? {#what-fields-will-sync-to-marketo}

U kunt velden [selecteren die u tijdens de installatie wilt synchroniseren](https://docs.marketo.com/pages/viewpage.action?pageId=3571830#Step3of3:ConnectMicrosoftDynamicswithMarketo(Online)-SelectFieldstoSync) .

## Zal Marketo de Dynamische bevestigingsregels naleven? {#will-marketo-respect-the-dynamics-validation-rules}

Ja. De synchronisatie mislukt als de gegevensindeling onjuist is of als de vereiste veldgegevens ontbreken. Marketo registreert het resultaat in het activiteitenlogboek van de persoon als dit gebeurt.

