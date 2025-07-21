---
unique-page-id: 2953463
description: SFDC Sync - Lead/Account Owner Sync - Marketo Docs - Productdocumentatie
title: SFDC Sync - Lead/Account Owner Sync
exl-id: b9effcc2-f426-4390-aef1-42f4e525b182
feature: Salesforce Integration
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '212'
ht-degree: 0%

---

# SFDC Sync: Lead/Account Owner Sync {#sfdc-sync-lead-account-owner-sync}

Hiermee wordt de tabel &quot;gebruiker&quot; in [!DNL Salesforce] technisch gesynchroniseerd, maar deze wordt de velden Hoofd/Rekeningeigenaar genoemd.

## Welke velden worden gesynchroniseerd met Marketo Engage? {#which-fields-will-sync-to-marketo-engage}

Voor elke persoon die naar Marketo wordt gesynchroniseerd, synchroniseren we ook de volgende eigenaarvelden:

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

Absoluut, gebruik enkel de [ de stroomactie van de Eigenaar van de Verandering ](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/change-owner.md){target="_blank"}.

>[!NOTE]
>
>U kunt niet de eigenaarinformatie veranderen gebruikend [ Gebruikend de Pagina van het Detail van de Persoon ](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/using-the-person-detail-page.md){target="_blank"}.

## Wat kan ik met deze gegevens doen? {#what-can-i-do-with-this-data}

Er zijn veel redenen om deze gegevens te gebruiken, zoals

* Een persoonlijke e-mail verzenden met een handtekening van de eigenaar van de verkoop
* Filter op specifieke verkoopvertegenwoordigers voor marketing of zelfs om doeltreffendheid te analyseren
* Regels voor toewijzing (en hertoewijzing) in Marketo
* Gebruik hen in de [ Eigenaar van de Verandering ](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/change-owner.md){target="_blank"}, [ Persoon van de Synchronisatie aan SFDC ](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md){target="_blank"}, en [ creeer de 5} stroomacties van de Taak {](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/create-task.md){target="_blank"}

Marketo beschikt zeker over een indrukwekkende [!DNL Salesforce] sync. Niemand anders doet het zo goed!
