---
description: Dynamic Chat Integration - Marketo Docs - Productdocumentatie
title: Dynamische chatintegratie
exl-id: b2e3b4da-9ca7-4299-9c50-f52e0de91e36
source-git-commit: 676bd1c43fc62b2eae0e4536fb738b5be863e196
workflow-type: tm+mt
source-wordcount: '316'
ht-degree: 0%

---

# Dynamische chatintegratie {#dynamic-chat-integration}

Meer informatie over de Dynamic Chat-integratie met Sales Insight.

>[!PREREQUISITES]
>
>* Het SFDC-pakket voor het instellen van verkoopgegevens moet een versie zijn [1,9 of hoger](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/upgrading/upgrading-your-msi-package.md){target=&quot;_blank&quot;}
>
>* U moet beschikken over de [Dynamische chatintegratie](/help/marketo/product-docs/demand-generation/dynamic-chat/dynamic-chat-overview.md){target=&quot;_blank&quot;} instellen


## Marketo Sales Insight Configuration Tab {#marketo-sales-insight-configuration-tab}

Voer de onderstaande stappen uit om de Dynamic Chat-integratie in te schakelen.

1. Meld u aan bij uw Salesforce-account, klik op + aan het einde van de tabbalk en klik op **Marketo Sales Insight Config**.

1. Klik om het deelvenster Visualforce ongedaan te maken.

   ![](assets/dynamic-chat-integration-1.png)

1. Selecteer **Dynamische chatgegevens inschakelen** selectievakje.

   ![](assets/dynamic-chat-integration-2.png)

## Overzicht van functies {#feature-overview}

De volgende dynamische activiteiten van het Praatje kunnen door de gebruikers van het Inzicht van de Verkoop worden gebruikt...

Dialoogvenster Ingesloten: Aangemeld in Marketo en ingevuld in Sales Insight wanneer een bezoeker op een chatbot klikt en de dialoog aansluit.

* Dialoognaam
* Pagina-URL
* Status (geïnitieerd/verwijderd/voltooid)

Geplande benoeming: Aangemeld in Marketo en ingevuld in Sales Insight wanneer een bezoeker een afspraak via het chatbot heeft gepland.

* Dialoognaam
* Agent
* Pagina-URL
* Gepland op (datum- en tijdstempel invoegen)
* Status (Gepland, Opnieuw gechedeld, Geannuleerd)

Doel bereikt: Aangemeld in Marketo en ingevuld in Verkoopinzicht wanneer een bezoeker een doel bereikt in een willekeurige dialoogstroom.

* Dialoognaam
* Doelnaam
* Pagina-URL

Het tabblad Chat is beschikbaar in de deelvensters Lood en Contactpersoon. Het omvat Type van Activiteit, de Naam van de Dialoog en de kolommen van de Datum.

![](assets/dynamic-chat-integration-3.png)

U kunt meer over een type activiteit leren door op het te klikken.

![](assets/dynamic-chat-integration-4.png)

Ook de deelvensters Account en Opportunity bevatten de kolommen Naam, Type activiteit, Naam van dialoogvenster en Datum.

![](assets/dynamic-chat-integration-5.png)

Het tabblad Chatten vindt u ook op het tabblad Global Marketo. Het omvat drie activiteitstypes (de Geëngageerde Dialoog, Geplande Benoeming, Gebereikt Doel), samen met de volgende kolommen:

* Persoon
* Account
* Type activiteit (dialoog met deelnemers, geplande benoeming, bereikt doel)
* Dialoognaam
* Datum- en tijdstempel

U kunt meer informatie over een type activiteit krijgen door erop te klikken.

![](assets/dynamic-chat-integration-6.png)

>[!NOTE]
>
>De activiteit &quot;in wisselwerking met Document&quot;zal in MSI in een aanstaande versie beschikbaar zijn.
