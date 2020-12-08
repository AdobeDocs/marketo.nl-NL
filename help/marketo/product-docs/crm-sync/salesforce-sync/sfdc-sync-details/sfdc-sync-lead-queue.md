---
unique-page-id: 7516241
description: SFDC Sync -Lead Queue - Marketo Docs - Productdocumentatie
title: SFDC-synchronisatie - Wachtrij voor lead
translation-type: tm+mt
source-git-commit: 96cc6a30c63c8e8dca793a52e4bf7ecaef8c08dc
workflow-type: tm+mt
source-wordcount: '190'
ht-degree: 0%

---


# SFDC-synchronisatie: Wachtrij voor lead {#sfdc-sync-lead-queue}

Met Marketo kunt u mensen toevoegen aan [Salesforce-wachtrijen](https://help.salesforce.com/apex/HTViewHelpDoc?id=queues_overview.htm) voor hulp bij de distributie van leads. Hier zijn de details.

>[!NOTE]
>
>**FYI**
>
>Marketo is nu bezig met het standaardiseren van de taal voor alle abonnementen, dus u ziet mogelijk leads/leads in uw abonnement en personen/personen in docs.marketo.com. Deze termen betekenen hetzelfde. het heeft geen invloed op de instructies van het artikel . Er zijn nog enkele andere veranderingen. [Meer](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)informatie.

## Hoe te om een persoon aan een rij in Marketo toe te wijzen? {#how-to-assign-a-person-to-a-queue-in-marketo}

U kunt een persoon aan een Salesforce lood rij toewijzen gebruikend één van beiden van deze stroomacties:

* [Persoon synchroniseren naar SFDC](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md)
* [Eigenaar wijzigen](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/change-owner.md)

>[!NOTE]
>
>U kunt geen rijen in Marketo tot stand brengen of veranderen.

## Hoe wordt de informatie van de loodeigenaar opgeslagen als de persoon tot een rij behoort? {#how-is-lead-owner-information-stored-if-the-person-belongs-to-a-queue}

Als een lood door een rij in Salesforce wordt bezeten, worden deze gebieden van de verkoopeigenaar gehouden leeg tot de lood aan een eigenaar wordt toegewezen.

* Voornaam verkoopeigenaar
* Achternaam verkoopeigenaar
* Titel van verkoopeigenaar
* Telefoonnummer verkoopeigenaar
* E-mailadres van verkoopeigenaar

