---
unique-page-id: 42762409
description: De Pagina van het Inzicht van de verkoop voor Marketo Admins - Marketo Docs - de Documentatie van het Product
title: Pagina met verkoopinzicht voor marktexploitanten
translation-type: tm+mt
source-git-commit: 6ae882dddda220f7067babbe5a057eec82601abf
workflow-type: tm+mt
source-wordcount: '310'
ht-degree: 0%

---


# Pagina met verkoopinzicht voor markeringsbeheerders {#sales-insight-page-for-marketo-admins}

Marketo Admins heeft bepaalde rechten in Sales Insight. Leer hieronder wat ze zijn.

## Soap API-configuratie {#soap-api-configuration}

Deze gegevens worden gebruikt om uw Salesforce-account aan te sluiten op uw Marketo-instantie, zodat u MSI in Salesforce kunt gebruiken.

![](assets/one-1.png)

## Configuratie {#rest-api-configuration} voor rest-API

Deze gegevens worden gebruikt om uw Salesforce-account aan te sluiten op uw Marketo-instantie, zodat u het MSI Insights-dashboard in Salesforce kunt gebruiken.

![](assets/two-1.png)

U kunt ervoor kiezen de referenties voor de rest-API te verwijderen in SFDC en alleen Soap-API&#39;s te gebruiken. Hierdoor wordt het dashboard met inzichten uitgeschakeld

![](assets/three-1.png)

## Persoonlijke score-instellingen {#person-score-settings}

* **Sterren**: Sterren geven de totale loodscore aan in vergelijking met andere leads.
* **Vlamjes**: Flames geven urgentie aan - hoeveel de score van een lead de laatste tijd is veranderd.

Standaard gebruikt Marketo Sales Insight het veld Score voor het berekenen van sterren en vlammen. Maar als je een ander veld wilt kiezen, is dit hoe:

1. In **Admin** gebied van Marketo, klik **Inzicht van de Verkoop**.

   ![](assets/four.png)

1. Klik onder Scoreinstellingen voor lead op **Bewerken**.

   ![](assets/five.png)

1. Selecteer het veld dat u voor sterren wilt gebruiken.

   ![](assets/six.png)

1. Selecteer het veld dat u voor vlammen wilt gebruiken.

   ![](assets/seven.png)

1. Klik **Opslaan**. Verkoopinzicht neemt enige tijd in beslag om opnieuw te berekenen. U kunt uw CRM later controleren om de sterren en de vlammen te zien.

   ![](assets/eight.png)

   >[!TIP]
   >
   >Als u uw gebieden van de douanescore nog niet hebt, is hier hoe te om [hen te creëren](/help/marketo/product-docs/administration/field-management/create-a-custom-field-in-marketo.md).

   >[!MORELIKETHIS]
   >
   >[Sterren en lamellen](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/stars-and-flames/customize-stars-and-flames.md)

## Instellingen {#settings}

![](assets/nine.png)

**Abonnementsinstellingen opzeggen:**

U kunt kiezen uit de volgende instellingen voor abonnementen voor Geen sjabloon, Standaard e-mails en Operationele e-mails

* Instelling voor afmelden respecteren
* Abonnementsinstellingen respecteren wanneer meer dan 1 ontvanger
* Abonnementsinstellingen respecteren wanneer meer dan 5 ontvangers
* Abonnementsinstellingen negeren

**Sjablonen vergrendelen:**

Indien ingeschakeld, kunnen MSI-gebruikers geen sjablonen bewerken tijdens het verzenden van e-mails van Salesforce

**RSS-feed inschakelen:**

Als deze optie is ingeschakeld, kunnen MSI-gebruikers hun voer voor leads bekijken in een RSS-feed (in aanvulling op het voer voor leads in Salesforce).
