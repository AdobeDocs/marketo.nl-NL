---
unique-page-id: 4719316
description: Persoonlijke accounts gebruiken - Marketo Docs - Productdocumentatie
title: Persoonlijke accounts gebruiken
exl-id: 3cc67ff2-f689-4dfb-8b67-2b5b8d389aaf
source-git-commit: 7376804bda915d7ff25cdc50cb78a6686bd36882
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# Persoonlijke accounts gebruiken {#using-person-accounts}

Persoonlijke accounts kunnen in Salesforce worden ingesteld om aan de behoeften van uw organisatie te voldoen. Zo behandelt Marketo persoonrekeningen.

>[!NOTE]
>
>De standaardrekeningen van Salesforce zijn bedrijfsrekeningen. Uw Salesforce-beheerder moet persoonlijke accounts afzonderlijk instellen.

## Wat is een persoonaccount? {#what-is-a-person-account}

Een persoonaccount lijkt sterk op het rekeningobject in Salesforce. Een persoonlijke account heeft echter toegang tot zowel accountvelden als contactvelden.

## Wat gebeurt er als een persoonaccount wordt gesynchroniseerd met Marketo? {#what-happens-when-a-person-account-is-synced-to-marketo}

Een persoonaccount wordt als bedrijf en als persoon gesynchroniseerd met Marketo.

>[!NOTE]
>
>De aangepaste velden voor een persoonaccount worden naar zowel bedrijf als persoon in Marketo gekopieerd.

## Hoe maak ik onderscheid tussen zakelijke accounts en persoonlijke accounts? {#how-do-i-differentiate-business-accounts-and-person-accounts}

Gebruik de **Is een persoonlijke account** filter in uw slimme lijst om persoonaccounts te scheiden van standaardzakelijke accounts.

## Waar wordt de informatie van mijn persoonlijke accounts weergegeven in Marketo Sales Insight? {#where-is-my-person-accounts-information-displayed-in-marketo-sales-insight}

De activiteiten met betrekking tot persoonrekeningen worden weergegeven in de **Account** deelvenster.

>[!NOTE]
>
>Marketo Sales Insight **Toevoegen aan Marketo-campagne** en **E-mail verzenden** er zijn momenteel geen opties beschikbaar voor persoonlijke accounts.

## Hoe associeer ik kansen aan een persoonrekening? {#how-do-i-associate-opportunities-to-a-person-account}

Marketo is afhankelijk van de rol van het opportuniteitcontact om te bepalen aan welke persoon de mogelijkheid moet worden gekoppeld. U moet de rol van de opportuniteitcontact voor elke persoonaccount toevoegen om de mogelijkheid te koppelen aan de juiste persoon in Marketo. Wij adviseren dat u opstelling een werkschema om de rol van het opportuniteitscontact automatisch toe te voegen.

## Welk e-mailveld moet ik gebruiken voor persoonaccounts? {#which-email-field-should-i-use-for-person-accounts}

Er zijn twee e-mailvelden voor een persoonaccount. Gebruik de **E-mailadres** in uw formulieren (niet de **E-mailadres persoon**) om ervoor te zorgen dat Marketo-deduplicatie en andere e-mailverwerking correct werken.
