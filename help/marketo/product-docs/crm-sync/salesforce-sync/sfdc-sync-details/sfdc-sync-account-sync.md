---
unique-page-id: 2953459
description: SFDC Sync - Account Sync - Marketo Docs - Productdocumentatie
title: SFDC-synchronisatie - Accountsynchronisatie
exl-id: 94f7a9e5-86ea-4bb4-9d78-96a09c61321d
feature: Salesforce Integration
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '225'
ht-degree: 0%

---

# SFDC-synchronisatie: Account synchroniseren {#sfdc-sync-account-sync}

Marketo synchroniseert ook je accountgegevens met Salesforce. Hier zijn een paar specifieke dingen die je zou moeten weten!

## Op welke manier wordt de informatie gesynchroniseerd? {#which-way-does-the-information-sync}

Slechts één manier: van SFDC naar Marketo.

## Hoe werken de updates? {#how-do-the-updates-work}

Als u een Account-veld bijwerkt voor een contactpersoon in Marketo, wijzigt dit de waarden van alle contactpersonen die bij die account horen in Marketo. Deze wordt niet gesynchroniseerd met SFDC. De volgende keer dat de account in SFDC wordt bijgewerkt, zullen de wijzigingen echter alle accountgegevens in Marketo overschrijven.

## Kan een contactpersoon tot meerdere accounts behoren?  {#can-a-contact-belong-to-multiple-accounts}

Nee. Een account kan vele contactpersonen hebben, een contactpersoon kan slechts één account hebben.

## Kan ik accounts maken van Marketo? {#can-i-create-accounts-from-marketo}

Meestal nee. Als u echter de opdracht [Persoon omzetten](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/convert-person.md) De stroomstap op een persoon, zal het tot een nieuw Contact, een nieuw Rekening, en een nieuwe Kans leiden.

>[!CAUTION]
>
>Deze stroomstap heeft een zeer beperkt gebruiksgeval. Als je het niet zeker weet, moet je het waarschijnlijk niet gebruiken.

## Leidt een verandering in een Gebied van de Rekening in Salesforce in een Logboek van de Activiteit van de Waarde van Gegevens van de Verandering voor elk contact?  {#does-a-change-in-an-account-field-in-salesforce-result-in-a-change-data-value-activity-log-for-each-contact}

Meestal ja. Nochtans, als een rekening meer dan 5.000 contacten en een gebied op die rekeningsveranderingen in SFDC heeft, synchroniseren wij de verandering maar registreren niet de activiteit voor 5.000+ contacten.
