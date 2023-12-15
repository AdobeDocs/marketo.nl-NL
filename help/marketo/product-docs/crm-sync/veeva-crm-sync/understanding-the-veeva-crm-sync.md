---
description: Werken met de Veeva CRM Sync - Marketo Docs - Productdocumentatie
title: Werken met de Veeva CRM Sync
exl-id: 99ade106-7f32-40e8-8b9a-2b1d0e769b9c
feature: Veeva CRM
source-git-commit: bebf61037f37a06b40b4d9c1df872f1cf62a1403
workflow-type: tm+mt
source-wordcount: '249'
ht-degree: 0%

---

# Werken met de Veeva CRM Sync {#understanding-the-veeva-crm-sync}

In een paar eenvoudige stappen is het eenvoudig om een synchronisatie uit te voeren tussen Adobe Marketo Engage en de Veeva CRM.

## Hoe de Synchronisatie werkt {#how-the-sync-works}

Marketo Engage synchroniseert de hele dag met Veeva CRM. Elke synchronisatie neemt enige tijd in beslag, pauzeert 5 minuten en start opnieuw.

>[!NOTE]
>
>De allereerste synchronisatie kan uren of zelfs dagen in beslag nemen omdat Marketo Engage de gehele database van Veeva kopieert. Daarna neemt elke synchronisatie doorgaans minuten (soms seconden) in beslag en worden alleen gegevens gesynchroniseerd die zijn gewijzigd.

![](assets/understanding-the-veeva-sync-1.png)

De synchronisatie tussen Veva en Marketo Engage is bidirectioneel alleen voor Contactvelden op het Person-accountobject. In deze gevallen, wanneer u veranderingen in of Veeva of Marketo Engage aanbrengt, zullen uw updates in beide systemen worden weerspiegeld. Alle andere synthesen zijn alleen van Veeva naar Marketo Engage. Klik op de onderstaande koppelingen voor meer informatie.

## Wat is de Synthese tussen Marketo Engage en Veeva {#what-is-synced-between-marketo-engage-and-veeva}

* [Persoonlijke accounts](/help/marketo/product-docs/crm-sync/veeva-crm-sync/sync-details/person-account-sync-faq.md){target="_blank"}
* Gebruikers
* [De Vraag en roept Zeer belangrijke Voorwerpen](/help/marketo/product-docs/crm-sync/veeva-crm-sync/sync-details/syncing-call-and-call-key-messages.md){target="_blank"}
* [Aangepaste objecten](/help/marketo/product-docs/crm-sync/veeva-crm-sync/sync-details/custom-object-sync.md){target="_blank"}

## Informatie over dingen {#things-to-know}

* De [aanmeldingsgegevens die u in Marketo Engage voor Veeva hebt ingevoerd](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md){target="_blank"} worden gebruikt om gegevens te synchroniseren. Alleen gegevens waartoe deze referenties toegang hebben, worden opgenomen.

* Veeva CRM is gebaseerd op force.com en het rijke Marketo Engage van de ervaring met het platform wordt geërft in deze synchronisatie.

* De Veeva CRM toont: Lead, Contact, Accounts, Business Accounts, Opportunity, Campaign en Activity. Ze worden echter niet ondersteund tijdens het synchroniseren met Marketo Engage.
