---
description: Integratie van Dynamics Chat - Marketo Docs - Productdocumentatie
title: Dynamische chatintegratie
exl-id: b2e3b4da-9ca7-4299-9c50-f52e0de91e36
feature: Marketo Sales Insights
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '388'
ht-degree: 0%

---

# Dynamische chatintegratie {#dynamic-chat-integration}

Meer weten over de integratie van Dynamics Chat met Sales Insight?

>[!PREREQUISITES]
>
>* Het SFDC-pakket voor het instellen van verkoopgegevens moet een versie zijn [1,9 of hoger](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/upgrading/upgrading-your-msi-package.md){target="_blank"}
>
>* U moet beschikken over de [Dynamic Chat-integratie](/help/marketo/product-docs/demand-generation/dynamic-chat/dynamic-chat-overview.md){target="_blank"} instellen

## Marketo Sales Insight Configuration Tab {#marketo-sales-insight-configuration-tab}

Volg de onderstaande stappen om de integratie van de Dynamic Chat in te schakelen.

1. Meld u aan bij uw Salesforce-account, klik op + aan het einde van de tabbalk en klik op **Marketo Sales Insight Config**.

1. Klik om het deelvenster Visualforce ongedaan te maken.

   ![](assets/dynamic-chat-integration-1.png)

1. Selecteer **Gegevens Dynamic Chat inschakelen** selectievakje.

   ![](assets/dynamic-chat-integration-2.png)

## Overzicht van functies {#feature-overview}

De volgende activiteiten van de Dynamic Chat kunnen door de gebruikers van het Inzicht van de Verkoop worden gebruikt...

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

Interactie met document: Aangemeld in Marketo en ingevuld in Sales Insight wanneer een bezoeker communiceert met een document dat via het chatbot wordt gedeeld.

* Dialoognaam
* Document
* Status

De activiteiten van het Praatje zijn beschikbaar in het Dashboard van Inzichten.

![](assets/dynamic-chat-integration-3.png)

Het tabblad Chat is beschikbaar in de deelvensters Lood en Contactpersoon. Het omvat Type van Activiteit, de Naam van de Dialoog en de kolommen van de Datum.

![](assets/dynamic-chat-integration-4.png)

U kunt meer over een type activiteit leren door op het te klikken.

![](assets/dynamic-chat-integration-5.png)

Ook de deelvensters Account en Opportunity bevatten de kolommen Naam, Type activiteit, Naam van dialoogvenster en Datum.

![](assets/dynamic-chat-integration-6.png)

Het tabblad Chatten vindt u ook op het tabblad Global Marketo. Het omvat drie activiteitstypes (de Geëngageerde Dialoog, Geplande Benoeming, Gebereikt Doel), samen met de volgende kolommen:

* Persoon
* Account
* Type activiteit (dialoog met deelnemers, geplande benoeming, bereikt doel)
* Dialoognaam
* Datum- en tijdstempel

U kunt meer informatie over een type activiteit krijgen door erop te klikken.

![](assets/dynamic-chat-integration-7.png)

>[!NOTE]
>
>Als het selectievakje Gegevens Dynamic Chat inschakelen is uitgeschakeld, worden de volgende functies uitgeschakeld:
>
>* Rij met chatactiviteiten op het dashboard Inzichten (weergave van slimme rasters en wekelijkse lijsten)
>* Tabblad Chatten in de deelvensters Lead, Contact, Account en Opportunity
>* Het tabblad Chatten op het tabblad Global Marketo
>
>Het is niet mogelijk om slechts één van deze eigenschappen onbruikbaar te maken.

