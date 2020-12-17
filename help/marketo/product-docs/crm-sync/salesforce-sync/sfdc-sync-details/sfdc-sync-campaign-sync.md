---
unique-page-id: 2953469
description: SFDC Sync - Campagne Sync - Marketo Docs - Productdocumentatie
title: SFDC Sync - Campagne Sync
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '377'
ht-degree: 0%

---


# SFDC-synchronisatie: Campagne synchroniseren {#sfdc-sync-campaign-sync}

Marketo-programma&#39;s kunnen worden gesynchroniseerd met Salesforce-campagnes. Hier volgt een overzicht van hoe dit werkt.

## Waarom zou ik Marketo-programma&#39;s synchroniseren met Salesforce-campagnes? {#why-should-i-sync-marketo-programs-with-salesforce-campaigns}

* Gebruik de krachtige functies van een Marketo-programma.
* Houd leden en hun status synchroon tussen een Marketo-programma en een Salesforce-campagne.
* Tik op de rapportfuncties in Marketo en Salesforce.

## Hoe wordt een Marketo-programma en een Salesforce-campagne gesynchroniseerd? {#how-is-a-marketo-program-and-a-salesforce-campaign-synced}

In Marketo kunt u een-op-een-koppeling maken tussen een programma en een Salesforce-campagne.

![](assets/image2015-7-8-9-3a43-3a8.png)

Het ** [kanaal](../../../../product-docs/administration/tags/create-a-program-channel.md) **en ** [punt kosten](../../../../product-docs/core-marketo-concepts/programs/working-with-programs/understanding-period-costs.md)** in Marketo sync to Salesforce als **campagetype** en **werkelijke kosten**. Deze synchronisatie is **één manier**, van Marketo aan Salesforce.

Marketo **programmaleden** en hun ** [progressiestatus](../../../../product-docs/core-marketo-concepts/programs/creating-programs/understanding-program-membership.md)** worden gesynchroniseerd met de **leden van de Salesforce-campagne** en **status van campagelid**. Dit is een **bidirectionele** **sync**, zodat om het even welke veranderingen die in of Marketo of Salesforce worden aangebracht worden weerspiegeld in beide systemen.

>[!NOTE]
>
>Als er leden in het Marketo-programma zijn die niet bestaan in Salesforce, creëert Marketo die mensen als leider in Salesforce.

## Welke triggers/filters hebben betrekking op campagnes? {#what-are-the-triggers-filters-related-to-campaigns}

Triggers:

* Toegevoegd aan SFDC-campagne
* Verwijderd uit SFDC-campagne
* Status is gewijzigd in SFDC-campagne

Filters:

* Lid van SFDC-campagne

## Kan ik Marketo People toevoegen aan mijn SFDC-campagne? {#can-i-add-marketo-people-to-my-sfdc-campaign}

Ja, gebruik [Add aan SFDC campagne flow action](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/add-to-sfdc-campaign.md). Als deze persoon niet in Salesforce bestaat, zal Marketo het in Salesforce creëren en dan hem/haar toevoegen aan de campagne.

## Kan ik leden verwijderen uit mijn SFDC-campagne met Marketo? {#can-i-remove-members-from-my-sfdc-campaign-using-marketo}

Ja, gebruik [Verwijderen uit SFDC Campagne flow action](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/remove-from-sfdc-campaign.md).

## Kan ik de status van een campagnetelid wijzigen met Marketo? {#can-i-change-campaign-member-status-using-marketo}

Ja, gebruik [Status wijzigen in SFDC Campagne flow action](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/change-status-in-sfdc-campaign.md).

## Waarom kan ik geen van mijn Salesforce-campagnes zien? {#why-cant-i-see-any-of-my-salesforce-campaigns}

U kunt de volgende dingen controleren:

1. Zorg ervoor [campagnecsync wordt toegelaten](../../../../product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync.md).
1. Bevestig dat uw [Marketo Sync User](../../../../product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md) een [Marketing User](../../../../product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync/make-marketo-sync-user-a-marketing-user.md) in Salesforce is.

>[!NOTE]
>
>Als de Salesforce-campagne en het Marketo-programma in kaart zijn gebracht, niet-compatibele programmastatussen hebben, ontvangt u mogelijk een foutbericht. Wij adviseren dat u [de programmastatussen voorafgaand aan sync](sfdc-errors/how-to-match-program-statuses-and-salesforce-campaign-statuses-prior-to-sync.md) aanpast.

>[!MORELIKETHIS]
>
>* [Een SFDC-campagne synchroniseren met een programma](../../../../product-docs/core-marketo-concepts/programs/working-with-programs/sync-an-sfdc-campaign-with-a-program.md)
>* [Werken met het lidmaatschap van het programma](../../../../product-docs/core-marketo-concepts/programs/creating-programs/understanding-program-membership.md)
>* [Campagnesynchronisatie inschakelen/uitschakelen](../../../../product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync.md)
>* [Een marketinggebruiker synchroniseren met Marketo](../../../../product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync/make-marketo-sync-user-a-marketing-user.md)

>



