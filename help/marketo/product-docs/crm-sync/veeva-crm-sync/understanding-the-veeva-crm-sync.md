---
description: Werken met de Veeva CRM Sync - Marketo Docs - Productdocumentatie
title: De Veeva CRM Sync begrijpen
hide: true
hidefromtoc: true
source-git-commit: 93e6bb881e10cda26b3a33569dc67627d628a178
workflow-type: tm+mt
source-wordcount: '248'
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

* Persoonlijke accounts
* Gebruikers
* De Vraag en roept Zeer belangrijke Voorwerpen
* Aangepaste objecten

## Informatie over {#things-to-know}

* De referenties die u in Marketo Engage for Veeva invoert, worden gebruikt om gegevens te synchroniseren. Alleen gegevens waartoe deze referenties toegang hebben, worden opgenomen.

* Veeva CRM is gebaseerd op force.com en de rijke ervaring die Marketo Engage heeft met het platform wordt geërft in deze synchronisatie.

* De Veeva CRM laat zien: Lood, Contact, accounts (Zakelijke accounts, Opportunity, Campagne en Activiteit). Ze worden echter niet ondersteund tijdens het synchroniseren met Marketo Engage.
