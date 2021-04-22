---
unique-page-id: 3571840
description: Microsoft Dynamics Sync -User Sync - Marketo Docs - Productdocumentatie
title: Microsoft Dynamics Sync - User Sync
exl-id: d642d4d2-2beb-42c6-a6b2-3da5df1cd9c8
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '154'
ht-degree: 0%

---

# Microsoft Dynamics Sync: Gebruikerssynchronisatie {#microsoft-dynamics-sync-user-sync}

Wist u dat Marketo uw gehele database synchroniseert met Dynamics? Het synchroniseert, wacht dan 5 minuten en synchroniseert dan opnieuw, de hele dag, elke dag. Hier zijn sommige details over hoe Marketo de Rekeningen van de Dynamiek specifiek behandelt.

U zult een specifieke gebruiker van CRM van de Dynamica van Microsoft voor het doel van de integratie nodig hebben. Deze gebruiker wordt de synchronisatiegebruiker genoemd.

## Hoe worden de gebruikersdetails gehouden synchroon tussen de twee systemen? {#how-are-user-details-kept-in-sync-between-the-two-systems}

De gebruikerssynchronisatie is in één richting: Dynamics to Marketo. Als u wijzigingen aanbrengt in een gebruiker in Dynamics, worden de wijzigingen doorgevoerd in Marketo.

## Kan ik een gebruiker maken met Marketo? {#can-i-create-an-user-using-marketo}

Nee. Marketo kan geen gebruikers maken in Dynamics.

## Welke velden worden gesynchroniseerd met Marketo? {#which-fields-will-sync-to-marketo}

Tijdens de installatie kunt u [velden selecteren om te synchroniseren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365/step-3-of-3-connect.md#select-fields-to-sync). Maar Marketo synchroniseert alleen de velden waartoe de gebruiker van het Dynamic Sync toegang heeft.
