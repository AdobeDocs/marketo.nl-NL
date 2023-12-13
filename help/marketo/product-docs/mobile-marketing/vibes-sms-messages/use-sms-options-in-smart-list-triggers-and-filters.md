---
description: SMS-opties gebruiken in Smart List Triggers and Filters - Marketo Docs - Productdocumentatie
title: SMS-opties gebruiken in Smart List-triggers en -filters
hide: true
hidefromtoc: true
feature: Mobile Marketing
source-git-commit: 8e56b571a34451d6b0436dc041efaf0fd575db36
workflow-type: tm+mt
source-wordcount: '247'
ht-degree: 0%

---

# SMS-opties gebruiken in Smart List-triggers en -filters {#use-sms-options-in-smart-list-triggers-and-filters}

NIEUWE DOC

Na u [een SMS-bericht maken](/help/marketo/product-docs/mobile-marketing/vibes-sms-messages/create-an-sms-message.md){target="_blank"}, zult u Slimme triggers en filters van de Lijst binnen een Slimme Campagne willen gebruiken om de voordelen te krijgen.

>[!PREREQUISITES]
>
>SMS-triggers/filters worden alleen weergegeven als de [De service Vibes is ingeschakeld](/help/marketo/product-docs/mobile-marketing/admin/add-vibes-as-a-launchpoint-service.md).

## SMS-triggers {#sms-triggers}

<table>
  <tr>
    <td><img src="assets/use-sms-options-in-smart-list-triggers-and-filters-1.png"></td>
    <td><img src="assets/use-sms-options-in-smart-list-triggers-and-filters-2.png"></td>
  </tr>
</table>

Hier volgen enkele voorbeelden:

De **Bounces voor SMS-berichten** activeert een stroom, zoals het verzenden van een e-mail, wanneer een SMS-bericht beweegt.

De **Abonneren op lijst met beeldbestanden** trigger start een flow wanneer een persoon zich abonneert.

De **Klik op Koppeling in SMS-bericht** activeert een stroom wanneer een persoon op een verbinding in het bericht van SMS klikt.

## SMS-filters {#sms-filters}

<table>
  <tr>
    <td><img src="assets/use-sms-options-in-smart-list-triggers-and-filters-3.png"></td>
    <td><img src="assets/use-sms-options-in-smart-list-triggers-and-filters-4.png"></td>
  </tr>
</table>

U kunt ook de filters Lagen in slimme lijsten gebruiken. De **Geabonneerd op de Levendenlijst** filter zoekt iedereen die *ooit* geabonneerd op Vibes. Dit geldt zowel voor niet-geabonneerde als voor verwijderde personen, ook al worden verwijderde personen weggelaten uit de stroom. Dit filter is het meest geschikt voor rapportage.

De **Lid van de lijst van Vibes** filtervondsten _iedereen_ momenteel geabonneerd op Vibes en is het meest geschikt voor gebruik in Slimme Campagnes of lijsten.

>[!NOTE]
>
>Alle SMS-filters bevatten de **Datum van activiteit** beperking standaard.

Nadat u Vibes-triggers en -filters hebt ingesteld in uw slimme lijst, kunt u [de flow definiëren](/help/marketo/product-docs/mobile-marketing/vibes-sms-messages/add-a-flow-step-for-sms.md).

>[!MORELIKETHIS]
>
>* [Een SMS-bericht verzenden](/help/marketo/product-docs/mobile-marketing/vibes-sms-messages/send-an-sms-message.md)
>* [Slimme lijst definiëren voor slimme campagne | Trigger](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-trigger.md)
>* [Filters zoeken en toevoegen aan een slimme lijst](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/find-and-add-filters-to-a-smart-list.md)
