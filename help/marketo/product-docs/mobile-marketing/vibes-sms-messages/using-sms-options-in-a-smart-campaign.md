---
description: SMS-opties gebruiken in een slimme campagne - Marketo Docs - Productdocumentatie
title: Het gebruiken van de Opties van SMS in een Slimme Campagne
feature: Mobile Marketing
exl-id: 199b7cae-86d2-42fe-8934-10aa780f4454
source-git-commit: 21bcdc10fe1f3517612efe0f8e2adaf2f4411a70
workflow-type: tm+mt
source-wordcount: '406'
ht-degree: 0%

---

# Het gebruiken van de Opties van SMS in een Slimme Campagne {#using-sms-options-in-a-smart-campaign}

Nadat u [ een bericht van SMS ](/help/marketo/product-docs/mobile-marketing/vibes-sms-messages/create-an-sms-message.md){target="_blank"} creeert, zult u de Slimme trekkers en de filters van de Lijst binnen een Slimme Campagne willen gebruiken om de voordelen te krijgen.

>[!NOTE]
>
>Als u een bericht van SMS wilt verzenden, hebben wij a [ specifiek artikel ](/help/marketo/product-docs/mobile-marketing/vibes-sms-messages/send-an-sms-message.md){target="_blank"} voor dat.

>[!PREREQUISITES]
>
>De trekkers/de filters van SMS verschijnen slechts als de [ dienst van Lagen ](/help/marketo/product-docs/mobile-marketing/admin/add-vibes-as-a-launchpoint-service.md){target="_blank"} is toegelaten.

## SMS-triggers {#sms-triggers}

<table style="width:600px">
  <tr>
    <td style="width:50%"><img src="assets/using-sms-options-in-a-smart-campaign-1.png"></td>
    <td style="width:50%"><img src="assets/using-sms-options-in-a-smart-campaign-2.png"></td>
  </tr>
</table>

Hier volgen enkele voorbeelden:

De **trekker van de Bounces van het Bericht van SMS** stelt een stroom, zoals het verzenden van een e-mail in werking, wanneer een SMS-bericht stuitert.

**abonneert aan de trekker van de Lijst van Levenben** een stroom in werking stelt wanneer een persoon zich abonneert.

De **Klik Verbinding in de trekker van het Bericht van SMS** stelt een stroom in werking wanneer een persoon op een verbinding in het bericht van SMS klikt.

## SMS-filters {#sms-filters}

<table style="width:600px">
  <tr>
    <td style="width:50%"><img src="assets/using-sms-options-in-a-smart-campaign-3.png"></td>
    <td style="width:50%"><img src="assets/using-sms-options-in-a-smart-campaign-4.png"></td>
  </tr>
</table>

Het **wordt ingetekend aan de filter van de Lijst van Levenben** vindt iedereen die ** heeft ooit ingetekend aan Levenben. Dit geldt zowel voor niet-geabonneerde als voor verwijderde personen, ook al worden verwijderde personen weggelaten uit de stroom. Dit filter is het meest geschikt voor rapportage.

Door contrast, vindt het **Lid van de Lijst van Levenben** filter *iedereen* momenteel geabonneerd aan Levenben en is het meest geschikt voor gebruik in Slimme Campagnes of lijsten.

>[!NOTE]
>
>Alle filters van SMS omvatten de **Datum van Activiteit** beperking door gebrek.

## Stappen voor SMS-stroom {#sms-flow-steps}

Er zijn drie SMS-stappen waaruit u kunt kiezen.

![](assets/using-sms-options-in-a-smart-campaign-5.png)

<table>
<tbody>
  <tr>
    <td style="width:20%"><b>SMS-bericht verzenden</b></td>
    <td>Deze flowactie verzendt berichten naar mensen van de Smart List van Marketo die zijn geabonneerd op een door de gebruiker gekozen abonnementenlijst van Vibes. Het abonnementsproces wordt niet gestart. <a href="/help/marketo/product-docs/mobile-marketing/vibes-sms-messages/send-an-sms-message.md"> leer meer </a>.</td>
  </tr>

<tr>
    <td style="width:20%"><b>Abonneren op lijst met beeldschermen</b></td>
    <td>Met deze flowactie wordt het SMS-abonnementsproces gestart via een door de gebruiker geselecteerde acquisitiecampagne van Vibes. Vibes stuurt vervolgens een bevestigingsbericht en de ontvanger antwoordt binnen 24 uur met "Y" om de opt-in te bevestigen. Nadat de gebruiker zich heeft aangemeld, worden deze lid van de abonnementenlijst met Vibes.</td>
  </tr>
  <tr>
    <td style="width:20%"><b>Abonnement op Vibes List opzeggen</b></td>
    <td>Met deze flowactie wordt elke persoon losgekoppeld van een gebruikerslijst met Vibes-abonnementen. Wanneer een gebruiker "STOP"aan uw code schrijft, wordt hun persoonverslag bijgewerkt om erop te wijzen zij niet meer een lid van de Lijst van het Abonnement van Vibes zijn.</td>
  </tr>
  </tbody>
</table>

>[!NOTE]
>
>Het **abonnement aan Lijst van Levenben** en **Unsubscribe van de stromen van de Lijst van Levendigs** hebben verschillende vereisten. Voor **Abonneren**, moet u de lijst van Levenben en de de acquisitiecampagne van Levenben selecteren. Voor **Unsubscribe**, slechts wordt de lijst van Lagen vereist.

>[!MORELIKETHIS]
>
>* [ verzend een Bericht van SMS ](/help/marketo/product-docs/mobile-marketing/vibes-sms-messages/send-an-sms-message.md){target="_blank"}
>* [ bepaalt Slimme Lijst voor Slimme Campagne | Trigger ](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-trigger.md){target="_blank"}
>* [ bepaalt Slimme Lijst voor Slimme Campagne | Batch ](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-batch.md){target="_blank"}
