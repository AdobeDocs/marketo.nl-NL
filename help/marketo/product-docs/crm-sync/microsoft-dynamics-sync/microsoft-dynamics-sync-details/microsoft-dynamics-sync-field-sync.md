---
unique-page-id: 3571838
description: Microsoft Dynamics Sync -Field Sync - Marketo Docs - Productdocumentatie
title: Microsoft Dynamics Sync - Field Sync
exl-id: 78eef0eb-4086-45c5-bce3-a3399016f228
feature: Microsoft Dynamics
source-git-commit: 2403ae0f1fdca3b8238f3f59e2a3b94129deb301
workflow-type: tm+mt
source-wordcount: '323'
ht-degree: 0%

---

# Microsoft Dynamics Sync: Field Sync {#microsoft-dynamics-sync-field-sync}

Synchronisatie van Marketo Engage naar dynamiek is superkrachtig. Hier zijn de details.

## Hoe worden de velddetails synchroon gehouden tussen de twee systemen? {#how-are-field-details-kept-in-sync-between-the-two-systems}

De synchronisatie is bidirectioneel voor lood en contactentiteiten. Als u wijzigingen aanbrengt in een lead of contactpersoon in Dynamics of een persoon in Marketo, worden de updates weergegeven in beide systemen.

Voor account, gebruiker, opportunity, team, en douaneentiteiten, is de synchronisatie unidirectioneel: Dynamiek aan Marketo. Als u wijzigingen aanbrengt in deze entiteiten in Dynamics, worden de updates weergegeven in Marketo.

## Wat gebeurt er als er tegelijkertijd in beide systemen wijzigingen in hetzelfde veld worden aangebracht? (Gegevensconflict) {#what-if-changes-are-made-to-the-same-field-in-both-systems-at-the-same-time-data-collision}

Hoewel dit zeldzaam is, zal Marketo winnen voor mensen (leads) en Dynamics zal winnen voor contacten. Dit komt omdat wij de marketingafdeling als gezaghebbend voor mensen beschouwen, terwijl het officiële systeem van verslagen voor contacten in de verkoopafdeling (CRM) is. Bij enkelvoudige synchronisatie-entiteiten wint Dynamics altijd.

## Kan ik een veld in Dynamics maken met Marketo? {#can-i-create-a-field-in-dynamics-using-marketo}

Nee, dit wordt momenteel niet ondersteund.

## Ik creëerde een veld in Dynamics. Kan ik het synchroniseren met Marketo? {#i-created-a-field-in-dynamics-can-i-sync-it-to-marketo}

Ja, u kunt [het veld synchroniseren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-4-of-4-connect.md#select-fields-to-sync){target="_blank"} zolang de synchronisatiegebruiker toegang heeft tot het programma in Dynamics.

## Welke velden worden gesynchroniseerd met Marketo? {#what-fields-will-sync-to-marketo}

U kunt [te synchroniseren velden selecteren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-4-of-4-connect.md#select-fields-to-sync){target="_blank"} tijdens installatie.

## Wat gebeurt er als ik een aangepast veld moet toevoegen nadat Marketo en Dynamics zijn gesynchroniseerd? {#what-if-i-need-to-add-a-custom-field-after-marketo-and-dynamics-are-synced}

U kunt op elk gewenst moment velden toevoegen en verwachten dat de gegevens worden vernieuwd van Dynamics naar Marketo. Zie [Snelle synchronisatie gebruiken met Microsoft Dynamics voor een nieuw aangepast veld](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-field-sync/use-quick-sync-with-microsoft-dynamics-for-a-new-custom-field.md){target="_blank"} voor meer informatie.

## Wat gebeurt er als ik een veld in Dynamiek wil verwijderen nadat het veld is toegevoegd aan synchronisatie? {#what-if-i-want-to-delete-a-field-in-dynamics-after-the-field-has-been-added-to-sync}

Marketo slaat een verwijzing naar de te synchroniseren velden op. Als u een veld verwijdert in Dynamics, wordt u aangeraden dit te doen met de opdracht [sync uitgeschakeld](/help/marketo/product-docs/crm-sync/salesforce-sync/enable-disable-the-salesforce-sync.md){target="_blank"}. Then refresh the schema in Marketo by editing and saving the [Select Fields to Sync](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-field-sync/editing-fields-to-sync-before-deleting-them-in-dynamics.md){target="_blank"}.
