---
unique-page-id: 3571836
description: Microsoft Dynamics Sync - Account Sync - Marketo Docs - Productdocumentatie
title: Microsoft Dynamics Sync - Account Sync
translation-type: tm+mt
source-git-commit: 96cc6a30c63c8e8dca793a52e4bf7ecaef8c08dc
workflow-type: tm+mt
source-wordcount: '227'
ht-degree: 0%

---


# Microsoft Dynamics Sync: Account synchroniseren {#microsoft-dynamics-sync-account-sync}

Wist u Marketo uw volledige database synchroniseert met Dynamics? Het synchroniseert, wacht dan 5 minuten en synchroniseert dan opnieuw, de hele dag, elke dag. Hier zijn sommige details over hoe Marketo de Rekeningen van de Dynamiek specifiek behandelt.

## Op welke manier wordt de informatie gesynchroniseerd? {#which-way-does-the-information-sync}

Slechts één manier: van Dynamics naar Marketo.

## Hoe werken de updates? {#how-do-the-updates-work}

Als u een Account-veld bijwerkt voor een contactpersoon in Marketo, wijzigt dit de waarden van alle contactpersonen die bij dat account horen in Marketo. Deze wordt niet gesynchroniseerd met Dynamics. Nochtans, de volgende tijd dat de rekening in Dynamiek wordt bijgewerkt, zullen de veranderingen al rekeningsinformatie in Marketo met voeten treden.

## Kan ik een account maken met Marketo? {#can-i-create-an-account-using-marketo}

Nee. Marketo kan geen accounts maken in Dynamics.

## Welke velden worden gesynchroniseerd met Marketo? {#which-fields-will-sync-to-marketo}

U kunt velden [selecteren die u tijdens de installatie wilt synchroniseren](https://docs.marketo.com/pages/viewpage.action?pageId=3571830#Step3of3:ConnectMicrosoftDynamicswithMarketo(Online)-SelectFieldstoSync) . Marketo synchroniseert echter alleen de velden waartoe de synchronisatiegebruiker van de dynamiek toegang heeft.

## Resulteert een verandering in een Gebied van de Rekening in Dynamica in een Logboek van de Activiteit van de Waarde van Gegevens van de Verandering voor Elke Contact?  {#does-a-change-in-an-account-field-in-dynamics-results-in-a-change-data-value-activity-log-for-each-contact}

Meestal ja. Nochtans, als een rekening meer dan 5.000 contacten en een gebied op dat rekeningsveranderingen in Dynamiek heeft, synchroniseren wij de verandering maar registreren niet de activiteit voor 5.000+ contacten.
