---
unique-page-id: 3571840
description: Microsoft Dynamics Sync - User Sync - Marketo Docs - Productdocumentatie
title: Microsoft Dynamics Sync - User Sync
translation-type: tm+mt
source-git-commit: 96cc6a30c63c8e8dca793a52e4bf7ecaef8c08dc
workflow-type: tm+mt
source-wordcount: '164'
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

U kunt velden [selecteren die u tijdens de installatie wilt synchroniseren](https://docs.marketo.com/pages/viewpage.action?pageId=3571830#Step3of3:ConnectMicrosoftDynamicswithMarketo(Online)-SelectFieldstoSync) . Marketo synchroniseert echter alleen de velden waartoe de synchronisatiegebruiker van de dynamiek toegang heeft.
