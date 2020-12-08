---
unique-page-id: 2953467
description: SFDC Sync - Opportunity Sync - Marketo Docs - Productdocumentatie
title: SFDC Sync - Opportunity Sync
translation-type: tm+mt
source-git-commit: 96cc6a30c63c8e8dca793a52e4bf7ecaef8c08dc
workflow-type: tm+mt
source-wordcount: '312'
ht-degree: 0%

---


# SFDC-synchronisatie: Opportunity synchroniseren {#sfdc-sync-opportunity-sync}

## Hoe worden de opportuniteitsgegevens gesynchroniseerd tussen de twee systemen? {#how-are-opportunity-details-kept-in-sync-between-the-two-systems}

U kunt het synchroniseren op één manier: van Salesforce naar Marketo. Updates van mogelijkheden in Salesforce worden gesynchroniseerd met Marketo.

>[!NOTE]
>
>De [referenties die u invoert in Marketo voor Salesforce](../../../../product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md) worden gebruikt om gegevens te synchroniseren. Alleen gegevens waartoe deze referenties toegang hebben, worden opgenomen.

## Kan ik een Opportunity Sync starten? {#can-i-initiate-an-opportunity-sync}

Nee, dat kan je niet. De wijzigingen in een opportuniteit in Salesforce worden automatisch doorgevoerd in Marketo.

## Steunt Marketo meer dan één munt in het Bedrag van de Kans? {#does-marketo-support-more-than-one-currency-in-the-opportunity-amount}

Nee, Marketo ondersteunt slechts één valuta. Het opportuniteitsbedrag wordt gesynchroniseerd vanuit Salesforce, maar de valuta wordt de [standaardvaluta](https://docs.marketo.com/display/DOCS/Set+Default+Location+Settings+for+a+Subscription#SetDefaultLocationSettingsforaSubscription-SettheDefaultCurrencySettingsforaSubscription) in uw abonnement op Marketo.

## Hoe associeert Marketo kansen en contacten? {#how-does-marketo-associate-opportunities-and-contacts}

Marketo associeert Kansen en contacten gebruikend de Rollen [van het Contact van de](https://help.salesforce.com/HTViewHelpDoc?id=contactroles.htm)Kans. De kansen zonder om het even welke toegewezen Rollen van het Contact zullen aan Marketo synchroniseren, maar zullen niet bij niemand horen. Bijvoorbeeld, zal de persoon niet het Bevat filter van de Mogelijkheid kwalificeren.

## Hoe kan ik alle mogelijkheden van een persoon zien? {#how-can-i-see-all-the-opportunities-of-a-person}

U kunt een lijst met mogelijkheden weergeven op het tabblad **Opportunity Info** op de pagina [Persondetails](../../../../product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/using-the-person-detail-page.md) .

## Welke triggers/filters hebben betrekking op opportuniteit? {#what-are-the-triggers-filters-related-to-opportunity}

Triggers:

* Toegevoegd aan opportuniteit
* Verwijderd uit opportuniteit
* Opportunity wordt bijgewerkt

Filters:

* Heeft mogelijkheid
* Opportunity is bijgewerkt/Geen opportunity is bijgewerkt
* Is toegevoegd aan opportunity/niet toegevoegd aan opportunity
* Is verwijderd uit opportunity/not is verwijderd uit Opportunity
* Totaal aantal opty&#39;s
* Aantal opties
* Totaal verwachte opty-inkomsten

>[!TIP]
>
>Ontdek de beperkingen op filters en triggers. Veel coole details hier.
>
>Maak een nieuw veld in het opportuniteitsobject in Salesforce en het wordt automatisch een beperking!

Marketo heeft de beste salesforce-synchronisatie ter wereld!