---
unique-page-id: 7516241
description: SFDC Sync - Lead Queue - Marketo Docs - Productdocumentatie
title: SFDC Sync - Lead Queue
exl-id: b3b5e14c-f914-429c-a4b9-6b535ad8e882
feature: Salesforce Integration
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '130'
ht-degree: 0%

---

# SFDC Sync: Wachtrij leiden {#sfdc-sync-lead-queue}

Marketo staat u toe om mensen aan [[!DNL Salesforce]  loodrijen ](https://help.salesforce.com/apex/HTViewHelpDoc?id=queues_overview.htm) toe te voegen om met looddistributie te helpen. Hier zijn de details.

## Hoe kan ik een persoon toewijzen aan een wachtrij in Marketo? {#how-to-assign-a-person-to-a-queue-in-marketo}

U kunt een persoon aan een [!DNL Salesforce] lood rij toewijzen gebruikend één van beiden van deze stroomacties:

* [ Persoon van de Synchronisatie aan SFDC ](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md){target="_blank"}
* [ Eigenaar van de Verandering ](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/change-owner.md){target="_blank"}

>[!NOTE]
>
>U kunt geen wachtrijen maken of wijzigen in Marketo.

## Hoe wordt de informatie van de loodeigenaar opgeslagen als de persoon tot een rij behoort? {#how-is-lead-owner-information-stored-if-the-person-belongs-to-a-queue}

Als een lead eigendom is van een wachtrij in [!DNL Salesforce] , worden deze velden voor de eigenaar van de verkoop leeg gehouden totdat de lead aan een eigenaar wordt toegewezen.

* Voornaam verkoopeigenaar
* Achternaam verkoopeigenaar
* Titel van verkoopeigenaar
* Telefoonnummer verkoopeigenaar
* E-mailadres van verkoopeigenaar
