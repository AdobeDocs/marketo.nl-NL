---
unique-page-id: 2953469
description: SFDC Sync - Campagne Sync - Marketo Docs - Productdocumentatie
title: SFDC Sync - Campagne Sync
exl-id: 62435e00-9c59-4dee-a9b7-ccf1d1f41b78
feature: Salesforce Integration
source-git-commit: 0087a5e88b8bd9601875f68a2e7cadeebdb5d682
workflow-type: tm+mt
source-wordcount: '370'
ht-degree: 0%

---

# SFDC-synchronisatie: Campagne synchroniseren {#sfdc-sync-campaign-sync}

Marketo&#39;s Engage kunnen worden gesynchroniseerd met Salesforce Campaigns. Hier is een overzicht van hoe dit werkt.

## Waarom zou ik Marketo-programma&#39;s synchroniseren met Salesforce-campagnes? {#why-should-i-sync-marketo-programs-with-salesforce-campaigns}

* Gebruik de krachtige functies van een Marketo-programma.
* Houd leden en hun status synchroon tussen een Marketo-programma en een Salesforce-campagne.
* Tik op de rapportfuncties in Marketo en Salesforce.

## Hoe wordt een Marketo-programma en een Salesforce-campagne gesynchroniseerd? {#how-is-a-marketo-program-and-a-salesforce-campaign-synced}

In Marketo kunt u een-op-een-koppeling maken tussen een programma en een Salesforce-campagne.

![](assets/image2015-7-8-9-3a43-3a8.png)

De **[kanaal](/help/marketo/product-docs/administration/tags/create-a-program-channel.md){target="_blank"}** and **[period cost](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/understanding-period-costs.md){target="_blank"}** in Marketo synchroniseren met Salesforce als de **campagneretype** en **werkelijke kosten**. Deze synchronisatie is **één weg**, van Marketo tot Salesforce.

Marketo **programmeurs** en hun **[progressiestatus](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-program-membership.md){target="_blank"}** worden gesynchroniseerd met de **Leden van de Salesforce-campagne** en **beelden van leden van campagne**. Dit is een **tweerichtingssync** en dus worden alle wijzigingen die in Marketo of Salesforce zijn aangebracht, weerspiegeld in beide systemen.

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

Ja, gebruik de [Toevoegen aan SFDC-actie voor stroom van campagne](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/add-to-sfdc-campaign.md){target="_blank"}. Als deze persoon niet in Salesforce bestaat, zal Marketo het in Salesforce creëren en dan hem/haar aan de campagne toevoegen.

## Kan ik leden uit mijn SFDC-campagne verwijderen met Marketo? {#can-i-remove-members-from-my-sfdc-campaign-using-marketo}

Ja, gebruik de [Verwijderen uit SFDC Campaign Flow-actie](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/remove-from-sfdc-campaign.md){target="_blank"}.

## Kan ik de status van een lid van een campagne wijzigen met Marketo? {#can-i-change-campaign-member-status-using-marketo}

Ja, gebruik de [Status wijzigen in SFDC Campagne Flow-actie](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/change-status-in-sfdc-campaign.md){target="_blank"}.

## Waarom kan ik geen van mijn Salesforce-campagnes zien? {#why-cant-i-see-any-of-my-salesforce-campaigns}

Hier volgen enkele zaken die u kunt controleren:

1. Zorg ervoor dat de [campagnecsync ingeschakeld](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync.md){target="_blank"}.
1. Bevestig dat uw [Marketo Sync-gebruiker](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md){target="_blank"} is a [Marketing User](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync/make-marketo-sync-user-a-marketing-user.md){target="_blank"} in Salesforce.

>[!NOTE]
>
>Als uw Salesforce-campagne en het toegewezen Marketo-programma niet-compatibele programmastatussen hebben, ontvangt u mogelijk een foutbericht. We raden u aan [overeenkomen met de status van het programma voordat de synchronisatie wordt uitgevoerd](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/how-to-match-program-statuses-and-salesforce-campaign-statuses-prior-to-sync.md){target="_blank"}.

>[!MORELIKETHIS]
>
>* [Een SFDC-campagne synchroniseren met een programma](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/sync-an-sfdc-campaign-with-a-program.md){target="_blank"}
>* [Werken met het lidmaatschap van het programma](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-program-membership.md){target="_blank"}
>* [Campagne synchroniseren inschakelen/uitschakelen](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync.md){target="_blank"}
>* [Marketo Sync gebruiker instellen als marketinggebruiker](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync/make-marketo-sync-user-a-marketing-user.md){target="_blank"}
