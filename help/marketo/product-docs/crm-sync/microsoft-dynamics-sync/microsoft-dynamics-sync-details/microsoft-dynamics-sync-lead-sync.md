---
unique-page-id: 3571848
description: Microsoft Dynamics Sync - Lead Sync - Marketo Docs - Productdocumentatie
title: Microsoft Dynamics Sync - Lead Sync
exl-id: ea04a039-32f7-41f9-85fb-18df8e236390
feature: Microsoft Dynamics
source-git-commit: 2403ae0f1fdca3b8238f3f59e2a3b94129deb301
workflow-type: tm+mt
source-wordcount: '308'
ht-degree: 0%

---

# Microsoft Dynamics Sync: Lead Sync {#microsoft-dynamics-sync-lead-sync}

Synchronisatie van Marketo Engage naar dynamiek is superkrachtig. Hier zijn de details.

## Hoe worden de details synchroon gehouden tussen beide systemen? {#how-are-details-kept-in-sync-between-the-two-systems}

De synchronisatie is bidirectioneel. Als u wijzigingen aanbrengt in een lead in Dynamics of in een persoon in Marketo, wordt de update weerspiegeld in beide systemen.

>[!NOTE]
>
>Verwijderen synchroniseert niet altijd automatisch in beide richtingen. Zie [Een lead of contactpersoon verwijderen](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/deleting-a-lead-or-contact.md){target="_blank"}.

## Wat gebeurt er als er tegelijkertijd in beide systemen wijzigingen in hetzelfde veld worden aangebracht? (Gegevensconflict) {#what-if-changes-are-made-to-the-same-field-in-both-systems-at-the-same-time-data-collision}

Hoewel dit zeldzaam is, zal Marketo winnen voor mensen (leads) en Dynamics zal winnen voor contacten. Dit komt omdat wij de marketingafdeling als gezaghebbend voor mensen beschouwen, terwijl het officiële systeem van verslagen voor contacten in de verkoopafdeling (CRM) is.

## Kan ik met Marketo een lead maken in Dynamics? {#can-i-create-a-lead-in-dynamics-using-marketo}

Ja, gebruik de [Persoon synchroniseren naar Microsoft](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/microsoft-dynamics-flow-actions/sync-person-to-microsoft.md){target="_blank"} Handeling flow. Dit zal tot een lood in Dynamica leiden als de lood niet bestaat. Als de lead wel bestaat, voert de flowstap geen actie uit.

>[!NOTE]
>
>Wanneer u de stroomactie &quot;persoon synchroniseren naar Microsoft&quot; gebruikt (alleen in een triggercampagne), wordt de lead/contactpersoon in realtime gemaakt in Dynamics.

## Kan ik handmatig een persoon van Marketo synchroniseren naar een lead in Dynamics? {#can-i-manually-force-a-sync-of-a-person-from-marketo-to-a-lead-in-dynamics}

Nee, de automatische achtergrondsynchronisatie is de enige manier om updates te synchroniseren tussen Marketo en Dynamics. De [Persoon synchroniseren naar Microsoft](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/microsoft-dynamics-flow-actions/sync-person-to-microsoft.md){target="_blank"} De stroomactie zal geen synchronisatie van het lood dwingen.

## Welke velden worden gesynchroniseerd met Marketo? {#what-fields-will-sync-to-marketo}

U kunt [te synchroniseren velden selecteren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-4-of-4-connect.md#select-fields-to-sync){target="_blank"} tijdens installatie.

## Zal Marketo de regels voor Dynamische validatie naleven? {#will-marketo-respect-the-dynamics-validation-rules}

Ja. De synchronisatie mislukt als de gegevensindeling onjuist is of als de vereiste veldgegevens ontbreken. Marketo registreert het resultaat in het activiteitenlogboek van de persoon als dit gebeurt.
