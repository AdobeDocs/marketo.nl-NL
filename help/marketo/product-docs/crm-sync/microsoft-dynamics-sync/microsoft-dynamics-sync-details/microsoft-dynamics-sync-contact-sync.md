---
unique-page-id: 3571833
description: Microsoft Dynamics Sync - Contact Sync - Marketo Docs - Productdocumentatie
title: Microsoft Dynamics Sync - Contact opnemen met Sync
exl-id: d4583ea0-2b52-415e-b28c-a8eafebeff64
feature: Microsoft Dynamics
source-git-commit: 2403ae0f1fdca3b8238f3f59e2a3b94129deb301
workflow-type: tm+mt
source-wordcount: '278'
ht-degree: 0%

---

# Microsoft Dynamics Sync: Contact opnemen met Sync {#microsoft-dynamics-sync-contact-sync}

Wist u dat Marketo Engage uw volledige database synchroniseert met Dynamics? Het synchroniseert, wacht dan 5 minuten en synchroniseert dan opnieuw, de hele dag, elke dag. Hier zijn sommige details over hoe Marketo de Contacten van de Dynamiek specifiek behandelt.

## Hoe worden de details synchroon gehouden tussen beide systemen? {#how-are-details-kept-in-sync-between-the-two-systems}

De contactsynchronisatie is bidirectioneel. Als u wijzigingen aanbrengt in een contactpersoon in Dynamics of een persoon in Marketo, worden de updates weergegeven in beide systemen.

## Wat gebeurt er als er tegelijkertijd in beide systemen wijzigingen in hetzelfde veld worden aangebracht? (Gegevensconflict) {#what-if-changes-are-made-to-the-same-field-in-both-systems-at-the-same-time-data-collision}

Hoewel dit zeldzaam is, zal Marketo winnen voor mensen en Dynamics zal winnen voor contacten. Dit komt omdat wij de marketingafdeling als gezaghebbend voor mensen beschouwen, terwijl het officiële systeem van verslagen voor contacten in de verkoopafdeling (CRM) is.

## Kan ik een contactpersoon maken met Marketo? {#can-i-create-a-contact-using-marketo}

Ja. [Zo ziet u](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-lead-sync/create-a-contact-in-microsoft-dynamics.md){target="_blank"}.

>[!NOTE]
>
>Wanneer u de stroomactie &quot;persoon synchroniseren naar Microsoft&quot; gebruikt (alleen in een triggercampagne), wordt de lead/contactpersoon in realtime gemaakt in Dynamics.

## Kan ik een synchronisatie van een persoon of een contact manueel dwingen? {#can-i-manually-force-a-sync-of-a-person-or-a-contact}

Nee, de automatische achtergrondsynchronisatie is de enige manier om updates te synchroniseren tussen Marketo en Dynamics. De [Persoon synchroniseren naar Microsoft](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/microsoft-dynamics-flow-actions/sync-person-to-microsoft.md){target="_blank"} geen synchronisatie van de lead forceren.

## Welke velden worden gesynchroniseerd met Marketo? {#what-fields-will-sync-to-marketo}

U kunt [te synchroniseren velden selecteren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-4-of-4-connect.md#select-fields-to-sync){target="_blank"} tijdens installatie. Maar Marketo synchroniseert alleen de velden waartoe de gebruiker van het Dynamic Sync toegang heeft.

## Zal Marketo de regels voor Dynamische validatie naleven? {#will-marketo-respect-the-dynamics-validation-rules}

Ja, als er een conflict is zal het het resultaat in het Logboek van de activiteit van de leads registreren.
