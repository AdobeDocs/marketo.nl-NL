---
unique-page-id: 2953473
description: Meer informatie over hoe Salesforce activiteiten en taken synchroniseert met Marketo. Maak taken vanuit Marketo en gebruik activiteittriggers en filters in slimme campagnes.
title: SFDC Sync - Activity Sync
exl-id: 780e9cb7-b8b2-4a79-a0b8-d9d34a655330
feature: Salesforce Integration
source-git-commit: 2b29f05a27f847184e0968442012d443e9e0597d
workflow-type: tm+mt
source-wordcount: '175'
ht-degree: 0%

---

# SFDC Sync: Activity Sync {#sfdc-sync-activity-sync}

Marketo synchroniseert ook de gegevens van [!DNL Salesforce] activity. Hier zijn een paar vragen en antwoorden.

## Over welke soorten activiteitsgegevens synchroniseert Marketo? {#what-types-of-activity-data-does-marketo-sync-over}

Marketo synchroniseert zowel gebeurtenissen als taken die aan een lead of contactpersoon zijn gekoppeld.

## Hoe worden de activiteitsgegevens gesynchroniseerd tussen de twee systemen? {#how-are-activity-details-kept-in-sync-between-the-two-systems}

De synchronisatie verloopt in één richting, van [!DNL Salesforce] tot Marketo. Maar u kunt een taak in [!DNL Salesforce] tot stand brengen gebruikend [&#x200B; creëren de stap van de Taak &#x200B;](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/create-task.md) stroom of [&#x200B; aanpassen de Synchronisatie van Activiteiten &#x200B;](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/customize-activities-sync.md) aan [!DNL Salesforce].

## Kan ik een taak maken met Marketo? {#can-i-create-a-task-using-marketo}

Ja, kunt u [&#x200B; gebruiken creeer de actie van de Taakstroom &#x200B;](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/create-task.md){target="_blank"}.

## Wat zijn de triggers/filters gerelateerd aan activiteit? {#what-are-the-triggers-filters-related-to-activity}

Triggers

* De activiteit is geregistreerd
* Activiteit is bijgewerkt

Filters

* Activiteit is geregistreerd/Geen activiteit is geregistreerd
* Activiteit is bijgewerkt/Activiteit is niet bijgewerkt

>[!TIP]
>
>Niet zeker van die formulering &quot;Geen activiteit&quot;? De term &#39;niet&#39; verwijst naar een inactiviteitsfilter. Leer meer over hen hier: [&#x200B; de Filters van de Inactiviteit van het Gebruik in een Slimme Lijst &#x200B;](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/use-inactivity-filters-in-a-smart-list.md){target="_blank"}
