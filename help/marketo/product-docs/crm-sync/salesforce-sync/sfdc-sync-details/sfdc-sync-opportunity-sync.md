---
unique-page-id: 2953467
description: SFDC Sync -Opportunity Sync - Marketo Docs - Productdocumentatie
title: SFDC Sync - Opportunity Sync
exl-id: f8acc528-c631-43f0-8899-2f3c6fdabe9e
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '291'
ht-degree: 0%

---

# SFDC-synchronisatie: Opportunity Sync {#sfdc-sync-opportunity-sync}

## Hoe worden de opportuniteitsgegevens gesynchroniseerd tussen de twee systemen? {#how-are-opportunity-details-kept-in-sync-between-the-two-systems}

U kunt het synchroniseren op één manier: van Salesforce naar Marketo. Updates van mogelijkheden in Salesforce worden gesynchroniseerd met Marketo.

>[!NOTE]
>
>De [referenties die u in Marketo voor Salesforce](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md) invoert, worden gebruikt om gegevens te synchroniseren. Alleen gegevens waartoe deze referenties toegang hebben, worden opgenomen.

## Kan ik een Opportunity Sync starten? {#can-i-initiate-an-opportunity-sync}

Nee, dat kan je niet. De wijzigingen in een opportuniteit in Salesforce worden automatisch doorgevoerd in Marketo.

## Biedt Marketo ondersteuning voor meer dan één valuta in het Opportunity Amount? {#does-marketo-support-more-than-one-currency-in-the-opportunity-amount}

Nee, Marketo ondersteunt slechts één valuta. Het opportuniteitsbedrag wordt gesynchroniseerd vanuit Salesforce, maar de valuta wordt de [standaardvaluta](/help/marketo/product-docs/administration/settings/set-default-location-settings-for-a-subscription.md#set-the-default-currency-settings-for-a-subscription) in uw Marketo-abonnement.

## Hoe associeert Marketo kansen en contacten? {#how-does-marketo-associate-opportunities-and-contacts}

Marketo associeert Kansen en contacten gebruikend [Rollen van het Contact van de Kanaal](https://help.salesforce.com/HTViewHelpDoc?id=contactroles.htm). De kansen zonder om het even welke toegewezen Rollen van het Contact zullen aan Marketo synchroniseren, maar zullen niet bij niemand horen. Bijvoorbeeld, zal de persoon niet het Bevat filter van de Mogelijkheid kwalificeren.

## Hoe kan ik alle mogelijkheden van een persoon zien? {#how-can-i-see-all-the-opportunities-of-a-person}

U kunt een lijst van kansen op het **lusje van Info** in [Persoonsdetail](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/using-the-person-detail-page.md) pagina bekijken.

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
