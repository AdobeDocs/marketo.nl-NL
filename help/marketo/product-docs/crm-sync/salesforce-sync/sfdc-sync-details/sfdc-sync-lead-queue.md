---
unique-page-id: 7516241
description: SFDC Sync - Lead Queue - Marketo Docs - Productdocumentatie
title: SFDC-synchronisatie - Wachtrij leiden
exl-id: b3b5e14c-f914-429c-a4b9-6b535ad8e882
source-git-commit: e04e2d6932830535493c431de50d6cf9e2298fb1
workflow-type: tm+mt
source-wordcount: '139'
ht-degree: 0%

---

# SFDC-synchronisatie: Wachtrij voor lead {#sfdc-sync-lead-queue}

Met Marketo kunt u personen toevoegen aan [Salesforce-loden wachtrijen](https://help.salesforce.com/apex/HTViewHelpDoc?id=queues_overview.htm) om te helpen bij de distributie van lood. Hier zijn de details.

## Hoe kan ik een persoon toewijzen aan een wachtrij in Marketo? {#how-to-assign-a-person-to-a-queue-in-marketo}

U kunt een persoon aan een Salesforce lood rij toewijzen gebruikend één van beiden van deze stroomacties:

* [Persoon synchroniseren naar SFDC](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md)
* [Eigenaar wijzigen](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/change-owner.md)

>[!NOTE]
>
>U kunt geen wachtrijen maken of wijzigen in Marketo.

## Hoe wordt de informatie van de loodeigenaar opgeslagen als de persoon tot een rij behoort? {#how-is-lead-owner-information-stored-if-the-person-belongs-to-a-queue}

Als een lood door een rij in Salesforce wordt bezeten, worden deze gebieden van de verkoopeigenaar gehouden leeg tot de lood aan een eigenaar wordt toegewezen.

* Voornaam verkoopeigenaar
* Achternaam verkoopeigenaar
* Titel van verkoopeigenaar
* Telefoonnummer verkoopeigenaar
* E-mailadres van verkoopeigenaar
