---
unique-page-id: 3571836
description: Microsoft Dynamics Sync -Account Sync - Marketo Docs - Productdocumentatie
title: Microsoft Dynamics Sync - Account Sync
exl-id: 86249d33-60dd-47e1-a7c8-3996c9444084
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '217'
ht-degree: 0%

---

# Microsoft Dynamics Sync: Accountsynchronisatie {#microsoft-dynamics-sync-account-sync}

Wist u dat Marketo uw gehele database synchroniseert met Dynamics? Het synchroniseert, wacht dan 5 minuten en synchroniseert dan opnieuw, de hele dag, elke dag. Hier zijn sommige details over hoe Marketo de Rekeningen van de Dynamiek specifiek behandelt.

## Op welke manier wordt de informatie gesynchroniseerd? {#which-way-does-the-information-sync}

Slechts één manier: van Dynamics naar Marketo.

## Hoe werken de updates? {#how-do-the-updates-work}

Als u een Account-veld bijwerkt voor een contactpersoon in Marketo, wijzigt dit de waarden van alle contactpersonen die bij die account horen in Marketo. Deze wordt niet gesynchroniseerd met Dynamics. Nochtans, de volgende tijd dat dat rekening in Dynamica wordt bijgewerkt, zullen de veranderingen al rekeningsinformatie in Marketo met voeten treden.

## Kan ik een account maken met Marketo? {#can-i-create-an-account-using-marketo}

Nee. Marketo kan geen accounts maken in Dynamics.

## Welke velden worden gesynchroniseerd met Marketo? {#which-fields-will-sync-to-marketo}

Tijdens de installatie kunt u [velden selecteren om te synchroniseren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365/step-3-of-3-connect.md#select-fields-to-sync). Maar Marketo synchroniseert alleen de velden waartoe de gebruiker van het Dynamic Sync toegang heeft.

## Resulteert een verandering in een Gebied van de Rekening in Dynamica in een Logboek van de Activiteit van de Waarde van Gegevens van de Verandering voor Elke Contact?  {#does-a-change-in-an-account-field-in-dynamics-results-in-a-change-data-value-activity-log-for-each-contact}

Meestal ja. Nochtans, als een rekening meer dan 5.000 contacten en een gebied op dat rekeningsveranderingen in Dynamiek heeft, synchroniseren wij de verandering maar registreren niet de activiteit voor 5.000+ contacten.
