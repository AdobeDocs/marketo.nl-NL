---
description: Werken met de Veeva CRM Sync - Marketo Docs - Productdocumentatie
title: De Veeva CRM Sync begrijpen
exl-id: 99ade106-7f32-40e8-8b9a-2b1d0e769b9c
source-git-commit: 2ce44b7c44517a6fdb3f616a3d69b25158ea4ec9
workflow-type: tm+mt
source-wordcount: '256'
ht-degree: 0%

---

# De Veeva CRM Sync begrijpen {#understanding-the-veeva-crm-sync}

In een paar eenvoudige stappen is het eenvoudig om een synchronisatie uit te voeren tussen Adobe Marketo Engage en de Veeva CRM.

## Hoe de Synchronisatie werkt {#how-the-sync-works}

Marketo Engage synchroniseert de hele dag met Veeva CRM. Elke synchronisatie neemt enige tijd in beslag, pauzeert 5 minuten en start opnieuw.

>[!NOTE]
>
>De allereerste synchronisatie kan uren of zelfs dagen in beslag nemen omdat Marketo Engage de gehele database van Veeva kopieert. Daarna neemt elke synchronisatie doorgaans minuten (soms seconden) in beslag en worden alleen gegevens gesynchroniseerd die zijn gewijzigd.

![](assets/understanding-the-veeva-sync-1.png)

De synchronisatie tussen Veva en Marketo Engage is bidirectioneel slechts voor de gebieden van het Contact op het de rekeningsvoorwerp van de Persoon. In deze gevallen, wanneer u veranderingen in of Veeva of Marketo Engage aanbrengt, zullen uw updates in beide systemen worden weerspiegeld. Alle andere syncs zijn van Veeva tot Marketo Engage. Klik op de onderstaande koppelingen voor meer informatie.

## Wat is gesynchroniseerd tussen Marketo Engage en Veeva {#what-is-synced-between-marketo-engage-and-veeva}

* [Persoonlijke accounts](/help/marketo/product-docs/crm-sync/veeva-crm-sync/sync-details/person-account-sync-faq.md){target=&quot;_blank&quot;}
* Gebruikers
* [De Vraag en roept Zeer belangrijke Voorwerpen](/help/marketo/product-docs/crm-sync/veeva-crm-sync/sync-details/syncing-call-and-call-key-messages.md){target=&quot;_blank&quot;}
* [Aangepaste objecten](/help/marketo/product-docs/crm-sync/veeva-crm-sync/sync-details/veeva-crm-custom-object-sync.md){target=&quot;_blank&quot;}

## Informatie over {#things-to-know}

* De [aanmeldingsgegevens die u hebt ingevoerd in Marketo Engage voor Veeva](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md){target=&quot;_blank&quot;} worden gebruikt om gegevens te synchroniseren. Alleen gegevens waartoe deze referenties toegang hebben, worden opgenomen.

* Veeva CRM is gebaseerd op force.com en de rijke ervaring die Marketo Engage heeft met het platform wordt geërft in deze synchronisatie.

* De Veeva CRM laat zien: Lood, Contact, accounts (Zakelijke accounts, Opportunity, Campagne en Activiteit). Ze worden echter niet ondersteund tijdens het synchroniseren met Marketo Engage.
