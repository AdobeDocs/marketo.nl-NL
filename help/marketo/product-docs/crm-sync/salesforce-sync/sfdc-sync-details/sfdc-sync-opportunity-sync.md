---
unique-page-id: 2953467
description: SFDC Sync - Opportunity Sync - Marketo Docs - Productdocumentatie
title: SFDC Sync - Opportunity Sync
exl-id: f8acc528-c631-43f0-8899-2f3c6fdabe9e
feature: Salesforce Integration
source-git-commit: 0087a5e88b8bd9601875f68a2e7cadeebdb5d682
workflow-type: tm+mt
source-wordcount: '292'
ht-degree: 0%

---

# SFDC Sync: Opportunity Sync {#sfdc-sync-opportunity-sync}

## Hoe worden de opportuniteitsgegevens gesynchroniseerd tussen de twee systemen? {#how-are-opportunity-details-kept-in-sync-between-the-two-systems}

De synchronisatie is één manier: van Salesforce naar Marketo Engage. Updates van mogelijkheden in Salesforce worden gesynchroniseerd met Marketo.

>[!NOTE]
>
>De [aanmeldingsgegevens die u in Marketo voor Salesforce hebt ingevoerd](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md){target="_blank"} worden gebruikt om gegevens te synchroniseren. Alleen gegevens waartoe deze referenties toegang hebben, worden opgenomen.

## Kan ik een Opportunity Sync starten? {#can-i-initiate-an-opportunity-sync}

Nee, dat kan je niet. De wijzigingen in een opportuniteit in Salesforce worden automatisch doorgevoerd in Marketo.

## Biedt Marketo ondersteuning voor meer dan één valuta in het Opportunity Amount? {#does-marketo-support-more-than-one-currency-in-the-opportunity-amount}

Nee, Marketo ondersteunt slechts één valuta. Het opportuniteitsbedrag wordt gesynchroniseerd vanuit Salesforce, maar de valuta wordt [standaardvaluta](/help/marketo/product-docs/administration/settings/set-default-location-settings-for-a-subscription.md#set-the-default-currency-settings-for-a-subscription){target="_blank"} in uw Marketo-abonnement.

## Hoe associeert Marketo kansen en contacten? {#how-does-marketo-associate-opportunities-and-contacts}

Marketo associeert Opportunity en contacten die gebruiken [Functies contactpersoon opportunity](https://help.salesforce.com/HTViewHelpDoc?id=contactroles.htm){target="_blank"}. De kansen zonder om het even welke toegewezen Rollen van het Contact zullen aan Marketo synchroniseren, maar zullen niet bij niemand horen. Bijvoorbeeld, zal de persoon niet het Bevat filter van de Mogelijkheid kwalificeren.

## Hoe kan ik alle mogelijkheden van een persoon zien? {#how-can-i-see-all-the-opportunities-of-a-person}

U kunt een lijst met mogelijkheden weergeven in het dialoogvenster **Opportunity-info** in de [Persoonsgegevens](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/using-the-person-detail-page.md){target="_blank"} pagina.

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
