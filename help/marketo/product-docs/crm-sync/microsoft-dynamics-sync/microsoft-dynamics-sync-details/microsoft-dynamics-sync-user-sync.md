---
unique-page-id: 3571840
description: Microsoft Dynamics Sync - User Sync - Marketo Docs - Productdocumentatie
title: Microsoft Dynamics Sync - User Sync
translation-type: tm+mt
source-git-commit: 2b5ccd7220557a5e966d33436d0f0d2a65e4589d
workflow-type: tm+mt
source-wordcount: '154'
ht-degree: 0%

---


# Microsoft Dynamics Sync: Gebruikerssynchronisatie {#microsoft-dynamics-sync-user-sync}

Wist u Marketo uw volledige database synchroniseert met Dynamics? Het synchroniseert, wacht dan 5 minuten en synchroniseert dan opnieuw, de hele dag, elke dag. Hier zijn sommige details over hoe Marketo de Rekeningen van de Dynamiek specifiek behandelt.

U zult een specifieke gebruiker van CRM van de Dynamica van Microsoft voor het doel van de integratie nodig hebben. Deze gebruiker wordt de synchronisatiegebruiker genoemd.

## Hoe worden de gebruikersdetails gehouden synchroon tussen de twee systemen? {#how-are-user-details-kept-in-sync-between-the-two-systems}

De gebruikerssynchronisatie is in één richting: Dynamiek naar Marketo. Als u veranderingen in een gebruiker in Dynamiek aanbrengt zullen de veranderingen in Marketo worden weerspiegeld.

## Kan ik een gebruiker maken met Marketo? {#can-i-create-an-user-using-marketo}

Nee. Marketo kan geen gebruikers maken in Dynamics.

## Welke velden worden gesynchroniseerd met Marketo? {#which-fields-will-sync-to-marketo}

Tijdens de installatie kunt u [velden selecteren om te synchroniseren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365/step-3-of-3-connect.md#select-fields-to-sync). Marketo synchroniseert echter alleen de velden waartoe de synchronisatiegebruiker van de dynamiek toegang heeft.
