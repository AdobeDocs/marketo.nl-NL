---
unique-page-id: 2953473
description: SFDC Sync - Activity Sync - Marketo Docs - Productdocumentatie
title: SFDC Sync - Activity Sync
translation-type: tm+mt
source-git-commit: 96cc6a30c63c8e8dca793a52e4bf7ecaef8c08dc
workflow-type: tm+mt
source-wordcount: '164'
ht-degree: 0%

---


# SFDC-synchronisatie: Activiteitensynchronisatie {#sfdc-sync-activity-sync}

Marketo synchroniseert ook de gegevens van de Salesforce-activiteiten. Hier zijn een paar vragen en antwoorden.

## Welke soorten activiteitsgegevens synchroniseert Marketo? {#what-types-of-activity-data-does-marketo-sync-over}

Marketo synchroniseert over zowel gebeurtenissen als taken die aan een lead of contactpersoon zijn gekoppeld.

## Hoe worden de activiteitsgegevens gesynchroniseerd tussen de twee systemen? {#how-are-activity-details-kept-in-sync-between-the-two-systems}

De synchronisatie is één manier, van Salesforce tot Marketo. Maar u kunt een taak in Salesforce tot stand brengen gebruikend [Create Taak](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/create-task.md) stroomstap of [Customize Activiteiten Sync](../../../../product-docs/crm-sync/salesforce-sync/setup/optional-steps/customize-activities-sync.md) aan Salesforce.

## Kan ik een taak maken met Marketo? {#can-i-create-a-task-using-marketo}

Ja, kunt u [de actie van de Stroom van de Taak creëren](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/create-task.md) gebruiken.

## Wat zijn de triggers/filters gerelateerd aan activiteit? {#what-are-the-triggers-filters-related-to-activity}

Triggers

* De activiteit is geregistreerd
* Activiteit is bijgewerkt

Filters

* Activiteit is geregistreerd/Geen activiteit is geregistreerd
* Activiteit is bijgewerkt/Activiteit is niet bijgewerkt

>[!TIP]
>
>Niet zeker van die formulering &quot;Geen activiteit&quot;? De term &#39;niet&#39; verwijst naar een inactiviteitsfilter. Meer informatie hierover vindt u hier: [Inactiviteitsfilters gebruiken in een slimme lijst](../../../../product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/use-inactivity-filters-in-a-smart-list.md)

