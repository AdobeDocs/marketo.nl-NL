---
unique-page-id: 2953461
description: SFDC Sync - Field Sync - Marketo Docs - Productdocumentatie
title: SFDC Sync - Field Sync
exl-id: fbd66829-53cb-47fd-a530-149d12baee0e
feature: Salesforce Integration
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '403'
ht-degree: 0%

---

# SFDC Sync: Field Sync {#sfdc-sync-field-sync}

Marketo synchroniseert veldinformatie uit [!DNL Salesforce] . Hier zijn de details.

## Welke velden worden gesynchroniseerd? {#which-fields-are-synced}

De meeste standaardvelden worden gesynchroniseerd in SFDC en elk aangepast veld dat de synchronisatiegebruiker mag zien.

## Hoe kunt u bepalen of een record in Marketo een lead of een contactpersoon in [!DNL Salesforce] is? {#how-do-you-determine-if-a-record-in-marketo-is-a-lead-or-a-contact-in-salesforce}

We hebben een veld in Marketo met de naam SFDC Type. Het heeft drie mogelijke waarden: lood, contact, of het is leeg. Als het leeg is, betekent het dat deze Marketo lead niet bestaat in SFDC.

## Hoe bepaalt u of een lood of een contact in SFDC wordt geschrapt? {#how-do-you-determine-if-a-lead-or-contact-is-deleted-in-sfdc}

We hebben een veld in Marketo met de naam SFDC isDelette. Als de waarde true is, is de lead verwijderd in SFDC.

## Hoe zorg ik ervoor dat een nieuw veld dat ik in SFDC voeg, ook aan Marketo wordt toegevoegd? {#how-do-i-make-sure-a-new-field-i-add-in-sfdc-also-gets-added-to-marketo}

>[!TIP]
>
>Als u een veld wilt in beide systemen, maakt u het eerst in SFDC en synchroniseert het automatisch naar Marketo.

Als u een nieuw veld toevoegt in SFDC en de synchronisatiegebruiker beschikt over de machtiging om dit te zien, wordt het automatisch toegevoegd aan Marketo.

## Wat gebeurt er als ik een veldlabel verander in SFDC? {#what-if-i-change-a-field-label-in-sfdc}

Het wijzigen van het veldlabel in SFDC heeft geen invloed op het veldlabel in Marketo.

## Wat gebeurt er als ik een veldtype verander in SFDC? {#what-if-i-change-a-field-type-in-sfdc}

Wanneer u een veldtype wijzigt, verwijdert Marketo de gegevens in de velden als deze niet overeenkomen (maar geeft eerst een waarschuwing). Als u de gegevens wilt behouden, moet u deze exporteren en opnieuw importeren nadat u het veldtype hebt gewijzigd.

## Wat gebeurt er als ik een API-naam in SFDC wijzig? {#what-if-i-change-an-api-name-in-sfdc}

Als u de API-naam van een veld wijzigt in SFDC, wordt een nieuw veld gemaakt in Marketo.

## Wat gebeurt er als ik een nieuwe keuzelijstwaarde in SFDC voeg? {#what-happens-if-i-add-a-new-picklist-value-in-sfdc}

Als in SFDC een nieuwe keuzelijstwaarde wordt toegevoegd aan een veld, stuurt Marketo je een melding.

## En aangepaste SFDC-opzoekvelden? {#what-about-custom-sfdc-lookup-fields}

Opzoekvelden in SFDC synchroniseren de id, maar niet de naam waarnaar wordt verwezen.

## Hoe zit het met SFDC Formula Fields? {#what-about-sfdc-formula-fields}

De gebieden van de formule worden gesynchroniseerd, echter, worden de updates aan de verwijzingen in de formule niet gesynchroniseerd tot er een update aan de Stempel van de Mod van het Systeem van a [&#128279;](https://help.salesforce.com/apex/HTViewSolution?id=000193203&language=en_US){target="_blank"} is.

## Wat gebeurt er als ik een veld uit [!DNL Salesforce] verwijder dat eerder synchroniseerde met Marketo? {#what-happens-when-i-delete-a-field-from-salesforce-that-was-previously-syncing-with-marketo}

Als u een veld verwijdert in SFDC, wordt het veld niet automatisch verwijderd in Marketo, wordt de synchronisatie gestopt.
