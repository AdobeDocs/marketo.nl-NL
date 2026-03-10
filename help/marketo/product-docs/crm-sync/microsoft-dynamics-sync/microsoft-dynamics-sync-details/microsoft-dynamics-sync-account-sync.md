---
unique-page-id: 3571836
description: Meer informatie over hoe accountgegevens worden gesynchroniseerd van Microsoft Dynamics naar Marketo. Begrijp eenzijdige synchronisatie en de contact-rekening verhouding.
title: Microsoft Dynamics Sync - Account Sync
exl-id: 86249d33-60dd-47e1-a7c8-3996c9444084
feature: Microsoft Dynamics
source-git-commit: 2b29f05a27f847184e0968442012d443e9e0597d
workflow-type: tm+mt
source-wordcount: '218'
ht-degree: 0%

---

# [!DNL Microsoft Dynamics] Synchroniseren: accountsynchronisatie {#microsoft-dynamics-sync-account-sync}

Wist u dat Marketo uw gehele database synchroniseert met [!DNL Dynamics] ? Het synchroniseert, wacht dan 5 minuten en synchroniseert dan opnieuw, de hele dag, elke dag. Hier volgt een aantal details over hoe Marketo [!DNL Dynamics] -accounts specifiek behandelt.

## Op welke manier wordt de informatie gesynchroniseerd? {#which-way-does-the-information-sync}

Slechts één manier: van [!DNL Dynamics] naar Marketo.

## Hoe werken de updates? {#how-do-the-updates-work}

Als u een Account-veld bijwerkt voor een contactpersoon in Marketo, wijzigt dit de waarden van alle contactpersonen die bij die account horen in Marketo. Deze wordt niet gesynchroniseerd met [!DNL Dynamics] . De volgende keer dat dat account wordt bijgewerkt in [!DNL Dynamics] , worden alle accountgegevens in Marketo echter door de wijzigingen overschreven.

## Kan ik een account maken met Marketo? {#can-i-create-an-account-using-marketo}

Nee. Marketo kan geen accounts maken in [!DNL Dynamics] .

## Welke velden worden gesynchroniseerd met Marketo? {#which-fields-will-sync-to-marketo}

U kunt [ gebieden selecteren om ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-4-of-4-connect.md#select-fields-to-sync) tijdens opstelling te synchroniseren. Maar Marketo synchroniseert alleen de velden waartoe uw [!DNL Dynamics] synchronisatiegebruiker toegang heeft.

## Heeft een wijziging in een accountveld in [!DNL Dynamics] voor elke contactpersoon een activiteitenlog voor de gegevenswaarde wijzigen?  {#does-a-change-in-an-account-field-in-dynamics-results-in-a-change-data-value-activity-log-for-each-contact}

Meestal ja. Nochtans, als een rekening meer dan 5.000 contacten en een gebied op dat rekeningsveranderingen in [!DNL Dynamics] heeft, synchroniseren wij de verandering maar registreren niet de activiteit voor 5.000+ contacten.
