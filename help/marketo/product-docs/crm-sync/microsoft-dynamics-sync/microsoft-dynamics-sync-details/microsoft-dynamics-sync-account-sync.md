---
unique-page-id: 3571836
description: Microsoft Dynamics Sync -Account Sync - Marketo Docs - Productdocumentatie
title: Microsoft Dynamics Sync - Account Sync
exl-id: 86249d33-60dd-47e1-a7c8-3996c9444084
feature: Microsoft Dynamics
source-git-commit: 2403ae0f1fdca3b8238f3f59e2a3b94129deb301
workflow-type: tm+mt
source-wordcount: '218'
ht-degree: 0%

---

# Microsoft Dynamics Sync: Account Sync {#microsoft-dynamics-sync-account-sync}

Wist u dat Marketo Engage uw volledige database synchroniseert met Dynamics? Het synchroniseert, wacht dan 5 minuten en synchroniseert dan opnieuw, de hele dag, elke dag. Hier zijn sommige details over hoe Marketo de Rekeningen van de Dynamiek specifiek behandelt.

## Op welke manier wordt de informatie gesynchroniseerd? {#which-way-does-the-information-sync}

Slechts één manier: van Dynamics naar Marketo.

## Hoe werken de updates? {#how-do-the-updates-work}

Als u een Account-veld bijwerkt voor een contactpersoon in Marketo, wijzigt dit de waarden van alle contactpersonen die bij die account horen in Marketo. Deze wordt niet gesynchroniseerd met Dynamics. Nochtans, de volgende tijd dat dat rekening in Dynamica wordt bijgewerkt, zullen de veranderingen al rekeningsinformatie in Marketo met voeten treden.

## Kan ik een account maken met Marketo? {#can-i-create-an-account-using-marketo}

Nee. Marketo kan geen accounts maken in Dynamics.

## Welke velden worden gesynchroniseerd met Marketo? {#which-fields-will-sync-to-marketo}

U kunt [te synchroniseren velden selecteren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-4-of-4-connect.md#select-fields-to-sync){target="_blank"} tijdens installatie. Maar Marketo synchroniseert alleen de velden waartoe de gebruiker van het Dynamic Sync toegang heeft.

## Resulteert een verandering in een Gebied van de Rekening in Dynamica in een Logboek van de Activiteit van de Waarde van Gegevens van de Verandering voor Elke Contact?  {#does-a-change-in-an-account-field-in-dynamics-results-in-a-change-data-value-activity-log-for-each-contact}

Meestal ja. Nochtans, als een rekening meer dan 5.000 contacten en een gebied op dat rekeningsveranderingen in Dynamiek heeft, synchroniseren wij de verandering maar registreren niet de activiteit voor 5.000+ contacten.
