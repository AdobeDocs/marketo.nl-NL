---
unique-page-id: 3571833
description: Microsoft Dynamics Sync -Contact Sync - Marketo Docs - Productdocumentatie
title: Microsoft Dynamics Sync - Contact opnemen met Sync
exl-id: d4583ea0-2b52-415e-b28c-a8eafebeff64
feature: Microsoft Dynamics
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '268'
ht-degree: 0%

---

# [!DNL Microsoft Dynamics] Synchroniseren: contact opnemen met Synchronisatie {#microsoft-dynamics-sync-contact-sync}

Wist u dat Marketo uw gehele database synchroniseert met [!DNL Dynamics] ? Het synchroniseert, wacht dan 5 minuten en synchroniseert dan opnieuw, de hele dag, elke dag. Hier volgt een aantal details over hoe Marketo [!DNL Dynamics] Contactpersonen specifiek behandelt.

## Hoe worden de details synchroon gehouden tussen beide systemen? {#how-are-details-kept-in-sync-between-the-two-systems}

De contactsynchronisatie is bidirectioneel. Als u wijzigingen aanbrengt in een contactpersoon in [!DNL Dynamics] of in een persoon in Marketo, worden de updates weerspiegeld in beide systemen.

## Wat gebeurt er als er tegelijkertijd in beide systemen wijzigingen in hetzelfde veld worden aangebracht? (Gegevensconflict) {#what-if-changes-are-made-to-the-same-field-in-both-systems-at-the-same-time-data-collision}

Hoewel dit zeldzaam is, zal Marketo winnen voor mensen en [!DNL Dynamics] zal winnen voor contacten. Dit komt omdat wij de marketingafdeling als gezaghebbend voor mensen beschouwen, terwijl het officiële systeem van verslagen voor contacten in de verkoopafdeling (CRM) is.

## Kan ik een contactpersoon maken met Marketo? {#can-i-create-a-contact-using-marketo}

Ja. [&#x200B; hier is hoe &#x200B;](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-lead-sync/create-a-contact-in-microsoft-dynamics.md){target="_blank"}.

>[!NOTE]
>
>Wanneer u de stroomactie &quot;Persoon synchroniseren naar Microsoft&quot; gebruikt (alleen in een triggercampagne), wordt de lead/contactpersoon in real-time gemaakt in [!DNL Dynamics] .

## Kan ik een synchronisatie van een persoon of een contact manueel dwingen? {#can-i-manually-force-a-sync-of-a-person-or-a-contact}

Nee, de automatische achtergrondsynchronisatie is de enige manier om updates te synchroniseren tussen Marketo en [!DNL Dynamics] . De [&#x200B; Persoon van de Synchronisatie aan Microsoft &#x200B;](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/microsoft-dynamics-flow-actions/sync-person-to-microsoft.md) zal geen synchronisatie van lood dwingen.

## Welke velden worden gesynchroniseerd met Marketo? {#what-fields-will-sync-to-marketo}

U kunt [&#x200B; gebieden selecteren om &#x200B;](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-4-of-4-connect.md#select-fields-to-sync) tijdens opstelling te synchroniseren. Maar Marketo synchroniseert alleen de velden waartoe uw [!DNL Dynamics] synchronisatiegebruiker toegang heeft.

## Zal Marketo de validatieregels van [!DNL Dynamics] naleven? {#will-marketo-respect-the-dynamics-validation-rules}

Ja, als er een conflict is zal het het resultaat in het Logboek van de activiteit van de leads registreren.
