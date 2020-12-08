---
unique-page-id: 4719316
description: Personen gebruiken - Marketo Docs - Productdocumentatie
title: Persoonlijke accounts gebruiken
translation-type: tm+mt
source-git-commit: 728066ab05de82f6123bfaa1f0b05af8632e32b2
workflow-type: tm+mt
source-wordcount: '291'
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
>De aangepaste velden voor een persoonaccount worden gekopieerd naar zowel bedrijf als persoon in Marketo.

## Hoe maak ik onderscheid tussen zakelijke accounts en persoonlijke accounts? {#how-do-i-differentiate-business-accounts-and-person-accounts}

Gebruik het filter **Is Personrekening** in uw slimme lijst om persoonrekeningen van standaardbedrijfsrekeningen te scheiden.

## Waar wordt de informatie van mijn persoonlijke rekeningen getoond in het Inzicht van de Verkoop van Marketo? {#where-is-my-person-accounts-information-displayed-in-marketo-sales-insight}

De activiteiten met betrekking tot persoonaccounts worden weergegeven in het **venster Account** .

>[!NOTE]
>
>Marketo Sales Insight **Add to Marketo Campaign **and **Send Email **Options zijn momenteel niet beschikbaar voor persoonlijke accounts.

## Hoe associeer ik kansen aan een persoonrekening? {#how-do-i-associate-opportunities-to-a-person-account}

Marketo is afhankelijk van de rol van het opportuniteitcontact om te bepalen aan welke persoon de mogelijkheid moet worden gekoppeld. U moet de rol van het opportuniteitcontact voor elke persoonrekening toevoegen om de kans met de aangewezen persoon in Marketo te verbinden. Wij adviseren dat u opstelling een werkschema om de rol van het opportuniteitscontact automatisch toe te voegen.

## Welk e-mailveld moet ik gebruiken voor persoonaccounts? {#which-email-field-should-i-use-for-person-accounts}

Er zijn twee e-mailvelden voor een persoonaccount. Gebruik het veld **E-mailadres** in uw formulieren (niet het **persoonlijke e-mailadres**) om ervoor te zorgen dat de duplicatie en andere e-mailverwerking van Marketo goed werken.
