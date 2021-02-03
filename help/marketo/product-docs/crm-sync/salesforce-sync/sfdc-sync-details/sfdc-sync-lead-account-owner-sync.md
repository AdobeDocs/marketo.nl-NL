---
unique-page-id: 2953463
description: SFDC Sync -Lead/Account Owner Sync - Marketo Docs - Productdocumentatie
title: SFDC Sync - Lead/Account Owner Sync
translation-type: tm+mt
source-git-commit: ed83438ae5660d172e845f25c4d72d599574bd91
workflow-type: tm+mt
source-wordcount: '213'
ht-degree: 0%

---


# SFDC-synchronisatie: Sync {#sfdc-sync-lead-account-owner-sync}

Hiermee wordt de tabel &quot;gebruiker&quot; in Salesforce technisch gesynchroniseerd, maar we zullen deze als de velden Lead/Account Owner noemen.

## Welke velden worden gesynchroniseerd met Marketo? {#which-fields-will-sync-to-marketo}

Voor elke persoon die met Marketo wordt gesynchroniseerd, synchroniseren wij ook de volgende eigenaargebieden:

* Voornaam verkoopeigenaar
* Achternaam verkoopeigenaar
* Titel van verkoopeigenaar
* Telefoonnummer verkoopeigenaar
* E-mailadres van verkoopeigenaar

Voor elke contactpersoon synchroniseren we de bovenstaande vijf velden voor de eigenaar van leads en de volgende velden voor de accounteigenaar:

* Voornaam eigenaar account
* Achternaam eigenaar account
* E-mailadres eigenaar account

## Kan ik de hoofdeigenaar in Marketo wijzigen? {#can-i-change-the-lead-owner-in-marketo}

Absoluut, gebruik enkel [de stroomactie van de Eigenaar van de Verandering ](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/change-owner.md).

>[!NOTE]
>
>U kunt de gegevens van de eigenaar niet wijzigen met de [Detailpagina voor persoon gebruiken](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/using-the-person-detail-page.md).

## Wat kan ik met deze gegevens doen? {#what-can-i-do-with-this-data}

Er zijn veel redenen om deze gegevens te gebruiken, zoals

* Een persoonlijke e-mail verzenden met een handtekening van de eigenaar van de verkoop
* Filter op specifieke verkoopvertegenwoordigers voor marketing of zelfs om doeltreffendheid te analyseren
* Regels voor toewijzing (en opnieuw toewijzen) in Marketo
* Gebruik ze in de [Eigenaar wijzigen](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/change-owner.md), [Persoon synchroniseren naar SFDC](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md) en [Taak maken](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/create-task.md)-stroomhandelingen

Marketo heeft zeker een fantastische Salesforce-synchronisatie. Niemand anders doet het zo goed!
