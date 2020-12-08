---
unique-page-id: 42762409
description: De Pagina van het Inzicht van de verkoop voor Marketo Admins - Marketo Docs - de Documentatie van het Product
title: Pagina met verkoopinzicht voor marktexploitanten
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '321'
ht-degree: 0%

---


# Pagina met verkoopinzicht voor marktexploitanten {#sales-insight-page-for-marketo-admins}

Marketo Admins heeft bepaalde rechten in Sales Insight. Leer hieronder wat ze zijn.

## Soap API-configuratie {#soap-api-configuration}

Deze gegevens worden gebruikt om uw Salesforce-account aan te sluiten op uw Marketo-instantie, zodat u MSI in Salesforce kunt gebruiken.

![](assets/one-1.png)

## API-configuratie opnieuw instellen {#rest-api-configuration}

Deze gegevens worden gebruikt om uw Salesforce-account aan te sluiten op uw Marketo-instantie, zodat u het MSI Insights-dashboard in Salesforce kunt gebruiken.

![](assets/two-1.png)

U kunt ervoor kiezen om de Rest API-referenties te verwijderen in SFDC en alleen Soap API&#39;s te gebruiken. Hierdoor wordt het dashboard met inzichten uitgeschakeld

![](assets/three-1.png)

## Instellingen persoonlijke score {#person-score-settings}

| **Sterren:** | Sterren geven de totale loodscore aan in vergelijking met andere leads. |
|---|---|
| **Vlamjes:** | Flames geven urgentie aan - hoeveel de score van een lead de laatste tijd is veranderd. |

Standaard gebruikt Marketo Sales Insight het veld Score voor het berekenen van sterren en vlammen. Maar als je een ander veld wilt kiezen, is dit hoe:

1. Klik in het gebied **Beheer** van Marketo op **Verkoopoverzicht**.

   ![](assets/four.png)

1. Klik onder Scoreinstellingen voor lead op **Bewerken**.

   ![](assets/five.png)

1. Selecteer het veld dat u voor sterren wilt gebruiken.

   ![](assets/six.png)

1. Selecteer het veld dat u voor vlammen wilt gebruiken.

   ![](assets/seven.png)

1. Klik op **Opslaan**. Verkoopinzicht neemt enige tijd in beslag om opnieuw te berekenen. U kunt uw CRM later controleren om de sterren en de vlammen te zien.

   ![](assets/eight.png)

   >[!TIP]
   >
   >Als u nog geen aangepaste score hebt, kunt u deze [maken](http://docs.marketo.com/x/3wMk).

   >[!NOTE]
   >
   >**Verwante artikelen**
   >
   >
   >[Sterren en lamellen](http://docs.marketo.com/x/qgU6Ag)

## Instellingen {#settings}

![](assets/nine.png)

**Abonnementsinstellingen opzeggen: **

U kunt kiezen uit de volgende instellingen voor abonnementen voor Geen sjabloon, Standaard e-mails en Operationele e-mails

* Instelling voor afmelden respecteren
* Abonnementsinstellingen respecteren wanneer meer dan 1 ontvanger
* Abonnementsinstellingen respecteren wanneer meer dan 5 ontvangers
* Abonnementsinstellingen negeren

**Mogelijkheid om sjablonen te vergrendelen inschakelen: **

Indien ingeschakeld, kunnen MSI-gebruikers geen sjablonen bewerken tijdens het verzenden van e-mails van Salesforce

**RSS-feed inschakelen:**

Als deze optie is ingeschakeld, kunnen MSI-gebruikers hun voer voor leads bekijken in een RSS-feed (in aanvulling op het voer voor leads in Salesforce)**.**
