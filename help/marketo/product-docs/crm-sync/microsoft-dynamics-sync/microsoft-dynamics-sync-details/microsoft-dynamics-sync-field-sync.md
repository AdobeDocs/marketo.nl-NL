---
unique-page-id: 3571838
description: Microsoft Dynamics Sync -Field Sync - Marketo Docs - Productdocumentatie
title: Microsoft Dynamics Sync - Field Sync
exl-id: 78eef0eb-4086-45c5-bce3-a3399016f228
feature: Microsoft Dynamics
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '320'
ht-degree: 0%

---

# [!DNL Microsoft Dynamics] Sync: Field Sync {#microsoft-dynamics-sync-field-sync}

Marketo to [!DNL Dynamics] sync is superkrachtig. Hier zijn de details.

## Hoe worden de velddetails synchroon gehouden tussen de twee systemen? {#how-are-field-details-kept-in-sync-between-the-two-systems}

De synchronisatie is bidirectioneel voor lood en contactentiteiten. Als u wijzigingen aanbrengt in een lead of contactpersoon in [!DNL Dynamics] of een persoon in Marketo, worden de updates weerspiegeld in beide systemen.

Voor account, gebruiker, opportunity, team en aangepaste entiteiten is de synchronisatie eenrichtingsverkeer: [!DNL Dynamics] naar Marketo. Als u in [!DNL Dynamics] wijzigingen aanbrengt in deze entiteiten, worden de updates weergegeven in Marketo.

## Wat gebeurt er als er tegelijkertijd in beide systemen wijzigingen in hetzelfde veld worden aangebracht? (Gegevensconflict) {#what-if-changes-are-made-to-the-same-field-in-both-systems-at-the-same-time-data-collision}

Hoewel dit zeldzaam is, wint Marketo voor mensen (leads) en [!DNL Dynamics] wint voor contacten. Dit komt omdat wij de marketingafdeling als gezaghebbend voor mensen beschouwen, terwijl het officiële systeem van verslagen voor contacten in de verkoopafdeling (CRM) is. Bij enkelvoudige synchronisatie-entiteiten wint [!DNL Dynamics] altijd.

## Kan ik een veld maken in [!DNL Dynamics] met Marketo? {#can-i-create-a-field-in-dynamics-using-marketo}

Nee, dit wordt momenteel niet ondersteund.

## Ik heb een veld gemaakt in [!DNL Dynamics] . Kan ik het synchroniseren met Marketo? {#i-created-a-field-in-dynamics-can-i-sync-it-to-marketo}

Ja, kunt u het gebied [&#x200B; synchroniseren zolang uw synchronisatiegebruiker tot het in &#x200B;](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-4-of-4-connect.md#select-fields-to-sync) toegang heeft.[!DNL Dynamics]

## Welke velden worden gesynchroniseerd met Marketo? {#what-fields-will-sync-to-marketo}

U kunt [&#x200B; gebieden selecteren om &#x200B;](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-4-of-4-connect.md#select-fields-to-sync){target="_blank"} tijdens opstelling te synchroniseren.

## Wat gebeurt er als ik een aangepast veld moet toevoegen nadat Marketo en [!DNL Dynamics] zijn gesynchroniseerd? {#what-if-i-need-to-add-a-custom-field-after-marketo-and-dynamics-are-synced}

U kunt op elk gewenst moment velden toevoegen en verwachten dat de gegevens worden vernieuwd van [!DNL Dynamics] naar Marketo. Zie [&#x200B; Snelle Synchronisatie van het Gebruik met  [!DNL Microsoft Dynamics]  voor een Nieuw Gebied van de Douane &#x200B;](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-field-sync/use-quick-sync-with-microsoft-dynamics-for-a-new-custom-field.md) voor details.

## Wat gebeurt er als ik een veld in [!DNL Dynamics] wil verwijderen nadat het veld aan de synchronisatie is toegevoegd? {#what-if-i-want-to-delete-a-field-in-dynamics-after-the-field-has-been-added-to-sync}

Marketo slaat een verwijzing naar de te synchroniseren velden op. Als u een gebied in [!DNL Dynamics] schrapt, adviseerden wij het doen dit met [&#x200B; gehandicapte synchronisatie &#x200B;](/help/marketo/product-docs/crm-sync/salesforce-sync/enable-disable-the-salesforce-sync.md). Dan vernieuw het schema in Marketo door [&#x200B; Uitgezochte Gebieden uit te geven en op te slaan om &#x200B;](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-field-sync/editing-fields-to-sync-before-deleting-them-in-dynamics.md) te synchroniseren.
