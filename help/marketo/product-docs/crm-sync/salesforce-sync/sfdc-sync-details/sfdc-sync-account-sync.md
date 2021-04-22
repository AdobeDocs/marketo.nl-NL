---
unique-page-id: 2953459
description: SFDC Sync -Account Sync - Marketo Docs - Productdocumentatie
title: SFDC Sync - Account Sync
exl-id: 94f7a9e5-86ea-4bb4-9d78-96a09c61321d
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '225'
ht-degree: 0%

---

# SFDC-synchronisatie: Accountsynchronisatie {#sfdc-sync-account-sync}

Marketo synchroniseert ook je accountgegevens met Salesforce. Hier zijn een paar specifieke dingen die je zou moeten weten!

## Op welke manier wordt de informatie gesynchroniseerd? {#which-way-does-the-information-sync}

Slechts één manier: van SFDC naar Marketo.

## Hoe werken de updates? {#how-do-the-updates-work}

Als u een Account-veld bijwerkt voor een contactpersoon in Marketo, wijzigt dit de waarden van alle contactpersonen die bij die account horen in Marketo. Deze wordt niet gesynchroniseerd met SFDC. De volgende keer dat de account in SFDC wordt bijgewerkt, zullen de wijzigingen echter alle accountgegevens in Marketo overschrijven.

## Kan een contactpersoon tot meerdere accounts behoren?  {#can-a-contact-belong-to-multiple-accounts}

Nee. Een account kan vele contactpersonen hebben, een contactpersoon kan slechts één account hebben.

## Kan ik accounts maken van Marketo? {#can-i-create-accounts-from-marketo}

Meestal nee. Nochtans, als u [de stroomstap van de Persoon van de Bekeerling ](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/convert-person.md) op een persoon gebruikt, zal het tot een nieuw Contact, een nieuw Rekening, en een nieuwe Kans leiden.

>[!CAUTION]
>
>Deze stroomstap heeft een zeer beperkt gebruiksgeval. Als je het niet zeker weet, moet je het waarschijnlijk niet gebruiken.

## Leidt een verandering in een Gebied van de Rekening in Salesforce in een Logboek van de Activiteit van de Waarde van Gegevens van de Verandering voor elk contact?  {#does-a-change-in-an-account-field-in-salesforce-result-in-a-change-data-value-activity-log-for-each-contact}

Meestal ja. Nochtans, als een rekening meer dan 5.000 contacten en een gebied op die rekeningsveranderingen in SFDC heeft, synchroniseren wij de verandering maar registreren niet de activiteit voor 5.000+ contacten.
