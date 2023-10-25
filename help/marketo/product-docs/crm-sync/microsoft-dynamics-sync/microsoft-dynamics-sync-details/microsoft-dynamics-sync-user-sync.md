---
unique-page-id: 3571840
description: Microsoft Dynamics Sync -User Sync - Marketo Docs - Productdocumentatie
title: Microsoft Dynamics Sync - User Sync
exl-id: d642d4d2-2beb-42c6-a6b2-3da5df1cd9c8
feature: Microsoft Dynamics
source-git-commit: 2403ae0f1fdca3b8238f3f59e2a3b94129deb301
workflow-type: tm+mt
source-wordcount: '155'
ht-degree: 0%

---

# Microsoft Dynamics Sync: User Sync {#microsoft-dynamics-sync-user-sync}

Wist u dat Marketo Engage uw volledige database synchroniseert met Dynamics? Het synchroniseert, wacht dan 5 minuten en synchroniseert dan opnieuw, de hele dag, elke dag. Hier zijn sommige details over hoe Marketo de Rekeningen van de Dynamiek specifiek behandelt.

Voor de integratie hebt u een speciale Microsoft Dynamics CRM-gebruiker nodig. Deze gebruiker wordt de synchronisatiegebruiker genoemd.

## Hoe worden de gebruikersdetails gehouden synchroon tussen de twee systemen? {#how-are-user-details-kept-in-sync-between-the-two-systems}

De gebruikerssynchronisatie is in één richting: Dynamics to Marketo. Als u wijzigingen aanbrengt in een gebruiker in Dynamics, worden de wijzigingen doorgevoerd in Marketo.

## Kan ik een gebruiker maken met Marketo? {#can-i-create-an-user-using-marketo}

Nee. Marketo kan geen gebruikers maken in Dynamics.

## Welke velden worden gesynchroniseerd met Marketo? {#which-fields-will-sync-to-marketo}

U kunt [te synchroniseren velden selecteren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-4-of-4-connect.md#select-fields-to-sync){target="_blank"} tijdens installatie. Maar Marketo synchroniseert alleen de velden waartoe de gebruiker van het Dynamic Sync toegang heeft.
