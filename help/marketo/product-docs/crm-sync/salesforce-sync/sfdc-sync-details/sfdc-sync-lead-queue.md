---
unique-page-id: 7516241
description: SFDC Sync -Lead Queue - Marketo Docs - Productdocumentatie
title: SFDC-synchronisatie - Wachtrij voor lead
exl-id: b3b5e14c-f914-429c-a4b9-6b535ad8e882
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '139'
ht-degree: 0%

---

# SFDC-synchronisatie: Wachtrij voor lead {#sfdc-sync-lead-queue}

Met Marketo kunt u personen toevoegen aan [Salesforce-loodwachtrijen](https://help.salesforce.com/apex/HTViewHelpDoc?id=queues_overview.htm) voor hulp bij de distributie van leads. Hier zijn de details.

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
