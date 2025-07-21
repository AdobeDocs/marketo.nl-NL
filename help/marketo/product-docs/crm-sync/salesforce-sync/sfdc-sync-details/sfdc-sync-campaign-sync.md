---
unique-page-id: 2953469
description: SFDC Sync - Campagne Sync - Marketo Docs - Productdocumentatie
title: SFDC Sync - Campagne Sync
exl-id: 62435e00-9c59-4dee-a9b7-ccf1d1f41b78
feature: Salesforce Integration
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '360'
ht-degree: 0%

---

# SFDC Sync: Campagne Sync {#sfdc-sync-campaign-sync}

Marketo-programma&#39;s kunnen worden gesynchroniseerd met [!DNL Salesforce] -campagnes. Hier volgt een overzicht van hoe dit werkt.

## Waarom zou ik Marketo programma&#39;s met [!DNL Salesforce] campagnes moeten synchroniseren? {#why-should-i-sync-marketo-programs-with-salesforce-campaigns}

* Gebruik de krachtige functies van een Marketo-programma.
* Leden en hun status synchroon houden tussen een Marketo-programma en een [!DNL Salesforce] -campagne.
* Tik op de rapportfuncties in Marketo en [!DNL Salesforce] .

## Hoe worden een Marketo-programma en een [!DNL Salesforce] -campagne gesynchroniseerd? {#how-is-a-marketo-program-and-a-salesforce-campaign-synced}

In Marketo kunt u een-op-een-toewijzing maken tussen een programma en een [!DNL Salesforce] -campagne.

![](assets/image2015-7-8-9-3a43-3a8.png)

Het **[kanaal](/help/marketo/product-docs/administration/tags/create-a-program-channel.md)** en **[periode kosten](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/understanding-period-costs.md)** in de synchronisatie van Marketo [!DNL Salesforce] als **campagnetype** en **daadwerkelijke kosten**. Deze synchronisatie is **één manier**, van Marketo aan [!DNL Salesforce].

Marketo **programmeleden** en hun **[progressiestatus](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-program-membership.md)** worden gehouden synchroon met de **[!DNL Salesforce]campagnegeleden** en **status van het campagnetelid**. Dit is a **bidirectionele synchronisatie**, zodat worden om het even welke veranderingen die in of Marketo of [!DNL Salesforce] worden aangebracht weerspiegeld in beide systemen.

>[!NOTE]
>
>Als het Marketo-programma leden bevat die niet voorkomen in [!DNL Salesforce] , maakt Marketo deze personen als leads in [!DNL Salesforce] .

## Welke triggers/filters hebben betrekking op campagnes? {#what-are-the-triggers-filters-related-to-campaigns}

Triggers:

* Toegevoegd aan SFDC-campagne
* Verwijderd uit SFDC-campagne
* Status is gewijzigd in SFDC-campagne

Filters:

* Lid van SFDC Campaign

## Kan ik Marketo People toevoegen aan mijn SFDC-campagne? {#can-i-add-marketo-people-to-my-sfdc-campaign}

Ja, gebruik [ toevoegen aan de actie van de de campagnestroom van SFDC ](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/add-to-sfdc-campaign.md). Als deze persoon niet bestaat in [!DNL Salesforce] , maakt Marketo deze in [!DNL Salesforce] en voegt hij/zij deze toe aan de campagne.

## Kan ik leden uit mijn SFDC-campagne verwijderen met Marketo? {#can-i-remove-members-from-my-sfdc-campaign-using-marketo}

Ja, gebruik [ verwijderen uit de stroomactie van de Campagne van SFDC ](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/remove-from-sfdc-campaign.md){target="_blank"}.

## Kan ik de status van een lid van een campagne wijzigen met Marketo? {#can-i-change-campaign-member-status-using-marketo}

Ja, gebruik de [ Status van de Verandering in de stroomactie van de Campagne van SFDC ](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/change-status-in-sfdc-campaign.md){target="_blank"}.

## Waarom kan ik geen van mijn [!DNL Salesforce] campagnes zien? {#why-cant-i-see-any-of-my-salesforce-campaigns}

Hier volgen enkele zaken die u kunt controleren:

1. Zorg ervoor de [ campagnecsync ](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync.md) wordt toegelaten.
1. Bevestig dat uw [ Gebruiker van de Synchronisatie van Marketo ](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md) a [ Marketing Gebruiker ](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync/make-marketo-sync-user-a-marketing-user.md) in [!DNL Salesforce] is.

>[!NOTE]
>
>Als uw [!DNL Salesforce] -campagne en het toegewezen Marketo-programma niet-compatibele programmastatussen hebben, ontvangt u mogelijk een foutbericht. Wij adviseren dat u [ de programmastatussen voorafgaand aan de synchronisatie ](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/how-to-match-program-statuses-and-salesforce-campaign-statuses-prior-to-sync.md) aanpast.

>[!MORELIKETHIS]
>
>* [ Synchroniseer een Campagne van SFDC met een Programma ](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/sync-an-sfdc-campaign-with-a-program.md){target="_blank"}
>* [ Begrijpend het Lidmaatschap van het Programma ](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-program-membership.md){target="_blank"}
>* [ toelaten/onbruikbaar maken de Synchronisatie van de Campagne ](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync.md){target="_blank"}
>* [ maak de Gebruiker van de Synchronisatie van Marketo een Gebruiker van de Marketing ](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync/make-marketo-sync-user-a-marketing-user.md){target="_blank"}
