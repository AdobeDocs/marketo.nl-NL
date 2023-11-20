---
unique-page-id: 2953461
description: SFDC Sync - Field Sync - Marketo Docs - Productdocumentatie
title: SFDC-synchronisatie - veldsynchronisatie
exl-id: fbd66829-53cb-47fd-a530-149d12baee0e
feature: Salesforce Integration
source-git-commit: 0087a5e88b8bd9601875f68a2e7cadeebdb5d682
workflow-type: tm+mt
source-wordcount: '414'
ht-degree: 0%

---

# SFDC-synchronisatie: veldsynchronisatie {#sfdc-sync-field-sync}

Marketo Engage syncs field information from Salesforce. Hier zijn de details.

## Welke velden worden gesynchroniseerd? {#which-fields-are-synced}

De meeste standaardvelden worden gesynchroniseerd in SFDC en elk aangepast veld dat de synchronisatiegebruiker mag zien.

## Hoe kunt u bepalen of een record in Marketo een lead of een contact in Salesforce is? {#how-do-you-determine-if-a-record-in-marketo-is-a-lead-or-a-contact-in-salesforce}

We hebben een veld in Marketo met de naam SFDC Type. Het heeft drie mogelijke waarden: lood, contact, of het is leeg. Als het leeg is, betekent het dat deze Marketo lead niet bestaat in SFDC.

## Hoe bepaalt u of een lood of een contact in SFDC wordt geschrapt? {#how-do-you-determine-if-a-lead-or-contact-is-deleted-in-sfdc}

We hebben een veld in Marketo met de naam SFDC isDelette. Als de waarde true is, is de lead verwijderd in SFDC.

## Hoe kan ik ervoor zorgen dat een nieuw veld dat ik in SFDC voeg, ook aan Marketo wordt toegevoegd? {#how-do-i-make-sure-a-new-field-i-add-in-sfdc-also-gets-added-to-marketo}

>[!TIP]
>
>Als u een veld wilt in beide systemen, maakt u het eerst in SFDC en synchroniseert het automatisch naar Marketo.

Als u een nieuw veld toevoegt in SFDC en de synchronisatiegebruiker toestemming heeft om dit te zien, wordt het automatisch toegevoegd aan Marketo.

## Wat gebeurt er als ik een veldlabel in SFDC verander? {#what-if-i-change-a-field-label-in-sfdc}

Het wijzigen van het veldlabel in SFDC heeft geen invloed op het veldlabel in Marketo.

## Wat als ik een veldtype in SFDC verander? {#what-if-i-change-a-field-type-in-sfdc}

Wanneer u een veldtype wijzigt, verwijdert Marketo de gegevens in de velden als deze niet overeenkomen (maar geeft eerst een waarschuwing). Als u de gegevens wilt behouden, moet u deze exporteren en opnieuw importeren nadat u het veldtype hebt gewijzigd.

## Wat gebeurt er als ik een API-naam in SFDC verander? {#what-if-i-change-an-api-name-in-sfdc}

Als u de API-naam van een veld wijzigt in SFDC, wordt een nieuw veld gemaakt in Marketo.

## Wat gebeurt er als ik een nieuwe picklist-waarde in SFDC voeg? {#what-happens-if-i-add-a-new-picklist-value-in-sfdc}

Als een nieuwe keuzelijstwaarde in SFDC aan een veld wordt toegevoegd, stuurt Marketo u een melding.

## Hoe zit het met aangepaste SFDC-opzoekvelden? {#what-about-custom-sfdc-lookup-fields}

Opzoekvelden in SFDC synchroniseren de id, maar niet de naam waarnaar wordt verwezen.

## Hoe zit het met SFDC Formula Fields? {#what-about-sfdc-formula-fields}

Formulervelden worden gesynchroniseerd, maar updates van de verwijzingen in de formule worden pas gesynchroniseerd als er een update naar een [System Mod Stamp](https://help.salesforce.com/apex/HTViewSolution?id=000193203&amp;language=en_US){target="_blank"}.

## Wat gebeurt er als ik een veld uit Salesforce verwijder dat eerder synchroniseerde met Marketo? {#what-happens-when-i-delete-a-field-from-salesforce-that-was-previously-syncing-with-marketo}

Als u een veld verwijdert in SFDC, wordt het veld niet automatisch verwijderd in Marketo, stopt het met synchroniseren.
