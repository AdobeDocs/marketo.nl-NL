---
unique-page-id: 2953459
description: SFDC Sync - Account Sync - Marketo Docs - Productdocumentatie
title: SFDC Sync - Account Sync
exl-id: 94f7a9e5-86ea-4bb4-9d78-96a09c61321d
feature: Salesforce Integration
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '225'
ht-degree: 0%

---

# SFDC Sync: Account Sync {#sfdc-sync-account-sync}

Marketo synchroniseert ook uw accountgegevens met [!DNL Salesforce] . Hier zijn een paar specifieke dingen die je zou moeten weten!

## Op welke manier wordt de informatie gesynchroniseerd? {#which-way-does-the-information-sync}

Slechts één manier: van SFDC naar Marketo.

## Hoe werken de updates? {#how-do-the-updates-work}

Als u een Account-veld bijwerkt voor een contactpersoon in Marketo, wijzigt dit de waarden van alle contactpersonen die bij die account horen in Marketo. Deze wordt niet gesynchroniseerd met SFDC. De volgende keer dat dat account in SFDC wordt bijgewerkt, worden alle accountgegevens in Marketo echter door de wijzigingen overschreven.

## Kan een contactpersoon tot meerdere accounts behoren?  {#can-a-contact-belong-to-multiple-accounts}

Nee. Een account kan vele contactpersonen hebben, een contactpersoon kan slechts één account hebben.

## Kan ik accounts maken van Marketo? {#can-i-create-accounts-from-marketo}

Meestal, nee. Nochtans, als u [ gebruikt zet de de stroomstap van de Persoon ](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/convert-person.md){target="_blank"} op een persoon om, zal het tot een nieuw Contact, een nieuwe Rekening, en een nieuwe Kans leiden.

>[!CAUTION]
>
>Deze stroomstap heeft een zeer beperkt gebruiksgeval. Als je het niet zeker weet, moet je het waarschijnlijk niet gebruiken.

## Heeft een wijziging in een accountveld in [!DNL Salesforce] voor elke contactpersoon een activiteitenlog voor de gegevenswaarde wijzigen?  {#does-a-change-in-an-account-field-in-salesforce-result-in-a-change-data-value-activity-log-for-each-contact}

Meestal ja. Nochtans, als een rekening meer dan 5.000 contacten en een gebied op dat rekeningsveranderingen in SFDC heeft, synchroniseren wij de verandering maar registreren niet de activiteit voor 5.000+ contacten.
