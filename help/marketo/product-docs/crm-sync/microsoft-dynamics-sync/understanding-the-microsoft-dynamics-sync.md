---
unique-page-id: 10098625
description: Begrijpen van  [!DNL Microsoft Dynamics]  Synchronisatie - de Documenten van Marketo - de Documentatie van het Product
title: Werken met Microsoft Dynamics Sync
exl-id: bc87f744-7f1c-421b-8507-1a6e23d27fa2
feature: Microsoft Dynamics
source-git-commit: 0c0dd3355f979577ec194f9e8f935615515905c0
workflow-type: tm+mt
source-wordcount: '209'
ht-degree: 0%

---

# Werken met [!DNL Microsoft Dynamics] synchroniseren {#understanding-the-microsoft-dynamics-sync}

Marketo en [!DNL Microsoft Dynamics] gaan samen. We houden je verkoop- en marketinggegevens synchroon.

>[!CAUTION]
>
>Sandboxvernieuwing voor [!DNL Marketo Dynamics] synchronisatie wordt momenteel niet ondersteund. Als u de [!DNL Dynamics] CRM-sandbox moet vernieuwen, is een nieuwe Marketo-sandbox vereist. Neem contact op met de succesmanager van de klant voor meer informatie.

## Hoe synchroniseren werkt {#how-sync-works}

Marketo synchroniseert voortdurend gegevens met [!DNL Microsoft Dynamics] de hele dag, elke dag. Het is klaar met achtergrondsynchronisatie, in batches, niet in real time.

>[!NOTE]
>
>De allereerste synchronisatie in uw abonnement neemt minuten tot uren in beslag, afhankelijk van de grootte van uw database. Marketo kopieert de gehele database vanuit [!DNL Dynamics] . Daarna neemt elke synchronisatie doorgaans seconden of minuten in beslag en worden alleen gegevens gesynchroniseerd die zijn gewijzigd.

De synchronisatie tussen Marketo en [!DNL Dynamics] is bidirectioneel voor leads en contactpersonen. Als u wijzigingen aanbrengt in Marketo of [!DNL Dynamics] , worden de updates weerspiegeld in beide systemen. Alle andere velden, zoals accounts en mogelijkheden, worden slechts in één richting gesynchroniseerd, van [!DNL Dynamics] tot Marketo.

## Wat is gesynchroniseerd tussen Marketo en [!DNL Microsoft Dynamics]? {#what-is-synced-between-marketo-and-microsoft-dynamics}

* [Leads](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-lead-sync.md)
* [Contactpersonen](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-contact-sync.md)
* [Accounts](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-account-sync.md)
* [Gebruikers](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-user-sync.md)
* Teams (groepen SystemUsers)
* [Kansen](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-opportunity-sync.md)
* [Aangepaste entiteiten](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/enable-sync-for-a-custom-entity.md)

De [ geloofsbrieven u in Marketo voor  [!DNL Dynamics]](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-2-of-4-set-up.md) ingaat worden gebruikt om gegevens over te synchroniseren.

>[!NOTE]
>
>Instantiekopie wordt niet ondersteund als de broninstantie is geïntegreerd met [!DNL Microsoft Dynamics] .
