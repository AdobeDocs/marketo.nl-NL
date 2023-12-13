---
description: SMS-opties gebruiken in een slimme campagne - Marketo Docs - Productdocumentatie
title: Het gebruiken van de Opties van SMS in een Slimme Campagne
hide: true
hidefromtoc: true
feature: Mobile Marketing
source-git-commit: c3bad3c7d32259a9989227c1d6fa43bc693dd814
workflow-type: tm+mt
source-wordcount: '406'
ht-degree: 0%

---

# Het gebruiken van de Opties van SMS in een Slimme Campagne {#using-sms-options-in-a-smart-campaign}

Na u [een SMS-bericht maken](/help/marketo/product-docs/mobile-marketing/vibes-sms-messages/create-an-sms-message-2.md){target="_blank"}, zult u Slimme triggers en filters van de Lijst binnen een Slimme Campagne willen gebruiken om de voordelen te krijgen.

>[!NOTE]
>
>Als je een SMS-bericht wilt verzenden, hebben we een [specifiek artikel](/help/marketo/product-docs/mobile-marketing/vibes-sms-messages/send-an-sms-message.md) daarvoor.

>[!PREREQUISITES]
>
>SMS-triggers/filters worden alleen weergegeven als de [De service Vibes is ingeschakeld](/help/marketo/product-docs/mobile-marketing/admin/add-vibes-as-a-launchpoint-service.md).

## SMS-triggers {#sms-triggers}

<table>
  <tr>
    <td><img src="assets/using-sms-options-in-a-smart-campaign-1.png"></td>
    <td><img src="assets/using-sms-options-in-a-smart-campaign-2.png"></td>
  </tr>
</table>

Hier volgen enkele voorbeelden:

De **Bounces voor SMS-berichten** activeert een stroom, zoals het verzenden van een e-mail, wanneer een SMS-bericht beweegt.

De **Abonneren op lijst met beeldbestanden** trigger start een flow wanneer een persoon zich abonneert.

De **Klik op Koppeling in SMS-bericht** activeert een stroom wanneer een persoon op een verbinding in het bericht van SMS klikt.

## SMS-filters {#sms-filters}

<table>
  <tr>
    <td><img src="assets/using-sms-options-in-a-smart-campaign-3.png"></td>
    <td><img src="assets/using-sms-options-in-a-smart-campaign-4.png"></td>
  </tr>
</table>

De **Geabonneerd op de Levendenlijst** filter zoekt iedereen die *ooit* geabonneerd op Vibes. Dit geldt zowel voor niet-geabonneerde als voor verwijderde personen, ook al worden verwijderde personen weggelaten uit de stroom. Dit filter is het meest geschikt voor rapportage.

De **Lid van de lijst van Vibes** filtervondsten _iedereen_ momenteel geabonneerd op Vibes en is het meest geschikt voor gebruik in Slimme Campagnes of lijsten.

>[!NOTE]
>
>Alle SMS-filters bevatten de **Datum van activiteit** beperking standaard.

## Stappen voor SMS-stroom {#sms-flow-steps}

Er zijn drie SMS-stappen waaruit u kunt kiezen.

![](assets/using-sms-options-in-a-smart-campaign-5.png)

<table>
<tbody>
  <tr>
    <td style="width:25%">SMS-bericht verzenden</td>
    <td>Deze flowactie verzendt berichten naar mensen van de Smart List van Marketo die zijn geabonneerd op een door de gebruiker gekozen abonnementenlijst van Vibes. Het abonnementsproces wordt niet gestart. <a href="/help/marketo/product-docs/mobile-marketing/vibes-sms-messages/send-an-sms-message.md">Meer informatie</a>.</td>
  </tr>

<tr>
    <td style="width:25%">Abonneren op lijst met beeldschermen</td>
    <td>Met deze flowactie wordt het SMS-abonnementsproces gestart via een door de gebruiker geselecteerde acquisitiecampagne van Vibes. Vibes stuurt vervolgens een bevestigingsbericht en de ontvanger antwoordt binnen 24 uur met "Y" om de opt-in te bevestigen. Nadat de gebruiker zich heeft aangemeld, worden deze lid van de abonnementenlijst met Vibes.</td>
  </tr>
  <tr>
    <td style="width:25%">Abonnement op Vibes List opzeggen</td>
    <td>Met deze flowactie wordt elke persoon losgekoppeld van een gebruikerslijst met Vibes-abonnementen. Wanneer een gebruiker "STOP"aan uw code schrijft, wordt hun persoonverslag bijgewerkt om erop te wijzen zij niet meer een lid van de Lijst van het Abonnement van Vibes zijn.</td>
  </tr>
  </tbody>
</table>

>[!NOTE]
>
>De **Abonneren op lijst met beeldschermen** en **Abonnement op Vibes List opzeggen** stromen hebben verschillende vereisten. Voor **Abonneren**, moet u de Vibes-lijst en de Vibes-acquisitiecampagne selecteren. Voor **Abonnement opzeggen**, is alleen de lijst met Vibes vereist.

>[!MORELIKETHIS]
>
>* [Een SMS-bericht verzenden](/help/marketo/product-docs/mobile-marketing/vibes-sms-messages/send-an-sms-message.md)
>* [Slimme lijst definiëren voor slimme campagne | Trigger](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-trigger.md)
>* [Slimme lijst definiëren voor slimme campagne | Batch](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-batch.md)
