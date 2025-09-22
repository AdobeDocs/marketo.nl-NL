---
unique-page-id: 3571848
description: Microsoft Dynamics Sync -Lead Sync - Marketo Docs - Productdocumentatie
title: Microsoft Dynamics Sync - Lead Sync
exl-id: ea04a039-32f7-41f9-85fb-18df8e236390
feature: Microsoft Dynamics
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '284'
ht-degree: 0%

---

# [!DNL Microsoft Dynamics] Synchroniseren: Lead Sync {#microsoft-dynamics-sync-lead-sync}

Marketo to [!DNL Dynamics] sync is superkrachtig. Hier volgen de details:

## Hoe worden de details synchroon gehouden tussen beide systemen? {#how-are-details-kept-in-sync-between-the-two-systems}

De synchronisatie is bidirectioneel. Als u wijzigingen aanbrengt in een lead in [!DNL Dynamics] of in een persoon in Marketo, wordt de update weerspiegeld in beide systemen.

>[!NOTE]
>
>Verwijderen synchroniseert niet altijd automatisch in beide richtingen. Zie [ Deleting a Lood of Contact ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/deleting-a-lead-or-contact.md){target="_blank"}.

## Wat gebeurt er als er tegelijkertijd in beide systemen wijzigingen in hetzelfde veld worden aangebracht? (Gegevensconflict) {#what-if-changes-are-made-to-the-same-field-in-both-systems-at-the-same-time-data-collision}

Hoewel dit zeldzaam is, wint Marketo voor mensen (leads) en [!DNL Dynamics] wint voor contacten. Dit komt omdat wij de marketingafdeling als gezaghebbend voor mensen beschouwen, terwijl het officiële systeem van verslagen voor contacten in de verkoopafdeling (CRM) is.

## Kan ik een lead maken in [!DNL Dynamics] met Marketo? {#can-i-create-a-lead-in-dynamics-using-marketo}

Ja, gebruik de [[!UICONTROL Sync Person to Microsoft]](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/microsoft-dynamics-flow-actions/sync-person-to-microsoft.md) flow-actie. Hierdoor wordt een lead in [!DNL Dynamics] gemaakt als de lead niet bestaat. Als de lead wel bestaat, voert de flowstap geen actie uit.

>[!NOTE]
>
>Wanneer u de stroomactie &quot;[!UICONTROL Sync Person to Microsoft]&quot; gebruikt (alleen in een triggercampagne), wordt de lead/contactpersoon in real-time gemaakt in [!DNL Dynamics] .

## Kan ik handmatig een synchronisatie van een persoon van Marketo naar een lead in [!DNL Dynamics] forceren? {#can-i-manually-force-a-sync-of-a-person-from-marketo-to-a-lead-in-dynamics}

Nee, de automatische achtergrondsynchronisatie is de enige manier om updates te synchroniseren tussen Marketo en [!DNL Dynamics] . De [[!UICONTROL Sync Person to Microsoft]](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/microsoft-dynamics-flow-actions/sync-person-to-microsoft.md) -flowactie forceert geen synchronisatie van de lead.

## Welke velden worden gesynchroniseerd met Marketo? {#what-fields-will-sync-to-marketo}

U kunt [ gebieden selecteren om ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-4-of-4-connect.md#select-fields-to-sync){target="_blank"} tijdens opstelling te synchroniseren.

## Zal Marketo de validatieregels van [!DNL Dynamics] naleven? {#will-marketo-respect-the-dynamics-validation-rules}

Ja. De synchronisatie mislukt als de gegevensindeling onjuist is of als de vereiste veldgegevens ontbreken. Marketo registreert het resultaat in het activiteitenlogboek van de persoon als dit gebeurt.
