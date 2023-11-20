---
unique-page-id: 2953473
description: SFDC Sync - Activity Sync - Marketo Docs - Productdocumentatie
title: SFDC Sync - Activity Sync
exl-id: 780e9cb7-b8b2-4a79-a0b8-d9d34a655330
feature: Salesforce Integration
source-git-commit: 0087a5e88b8bd9601875f68a2e7cadeebdb5d682
workflow-type: tm+mt
source-wordcount: '159'
ht-degree: 0%

---

# SFDC Sync: Activity Sync {#sfdc-sync-activity-sync}

Marketo Engage synchroniseert ook de gegevens over de Salesforce-activiteiten. Hier zijn een paar vragen en antwoorden.

## Over welke soorten activiteitsgegevens synchroniseert Marketo? {#what-types-of-activity-data-does-marketo-sync-over}

Marketo synchroniseert zowel gebeurtenissen als taken die aan een lead of contactpersoon zijn gekoppeld.

## Hoe worden de activiteitsgegevens gesynchroniseerd tussen de twee systemen? {#how-are-activity-details-kept-in-sync-between-the-two-systems}

De synchronisatie is één manier, van Salesforce tot Marketo. Maar u kunt een taak maken in Salesforce met de [Taak maken](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/create-task.md){target="_blank"} flow step or [Customize Activities Sync](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/customize-activities-sync.md){target="_blank"} naar Salesforce.

## Kan ik een taak maken met Marketo? {#can-i-create-a-task-using-marketo}

Ja, u kunt de [Taakstroom maken, actie](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/create-task.md){target="_blank"}.

## Wat zijn de triggers/filters gerelateerd aan activiteit? {#what-are-the-triggers-filters-related-to-activity}

Triggers

* De activiteit is geregistreerd
* Activiteit is bijgewerkt

Filters

* Activiteit is geregistreerd/Geen activiteit is geregistreerd
* Activiteit is bijgewerkt/Activiteit is niet bijgewerkt

>[!TIP]
>
>Niet zeker van die formulering &quot;Geen activiteit&quot;? De term &#39;niet&#39; verwijst naar een inactiviteitsfilter. Meer informatie hierover vindt u hier: [Inactiviteitsfilters gebruiken in een slimme lijst](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/use-inactivity-filters-in-a-smart-list.md){target="_blank"}
