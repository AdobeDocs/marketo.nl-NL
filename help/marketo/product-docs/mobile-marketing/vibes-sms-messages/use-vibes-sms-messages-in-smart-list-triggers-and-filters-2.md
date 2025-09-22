---
description: SMS-berichten gebruiken in Smart List Triggers and Filters - Marketo Docs - Productdocumentatie
title: SMS-berichten over Vibes gebruiken in Smart List-triggers en -filters
hide: true
hidefromtoc: true
feature: Mobile Marketing
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '393'
ht-degree: 0%

---

# SMS-berichten over Vibes gebruiken in Smart List-triggers en -filters {#use-vibes-sms-messages-in-smart-list-triggers-and-filters}

Nadat u [ een bericht van SMS van Levenben ](/help/marketo/product-docs/mobile-marketing/vibes-sms-messages/create-a-vibes-sms-message.md){target="_blank"} creeert, zult u de Slimme trekkers en de filters van de Lijst binnen een Slimme Campagne willen gebruiken om de voordelen te krijgen. Zo gaat het.

1. Klik in Mijn Marketo op **[!UICONTROL Marketing Activities]** .

   ![](assets/use-vibes-sms-messages-in-smart-list-triggers-and-filters-1.png)

1. Kies een slimme campagne waarin u uw SMS-middelen wilt gebruiken. Sleep over een trigger. In dit voorbeeld gebruiken wij **Vult Vorm** uit.

   ![](assets/fills-out-form-pull-over.jpg)

## SMS-triggers {#sms-triggers}

Er zijn andere SMS-triggers beschikbaar. De triggers van SMS worden alleen weergegeven als de service Vibes is ingeschakeld.

EEN SMS-BERICHT VERZENDEN:

* Marketingactiviteiten > Nieuwe slimme campagne kiezen
   * Smart List > Choose Vibes List filter &amp; correct logic > Vibes list: Choose list from drop-down (mobile database list that syncs from Vibes platform)
      * Kan segmentatie verfijnen en SMS- en e-mailfilters en triggers gebruiken binnen één campagne
      * Vibes Filters: Geabonneerd op Vibes List vs. Member of Vibes List - logica is consistent met e-mail
         * Abonneren op de Vibes List - deelnemers die zich ooit op die Vibes-lijst hebben geabonneerd, zelfs als ze nu niet meer zijn geabonneerd.  - meestal gebruikt voor de afzet van producten over de kanalen
            * Opmerking: een SMS-bericht wordt niet verzonden naar iemand zonder abonnement als deze niet in de lijst Mobiele database van Vibes staat
         * Lid van de Lijst van Vibes - actieve, bevestigde abonnee
         * Toegevoegd aan lijst - De lijsten van Levensters zullen niet met dit filter bevolken; dit is voor Marketo lijsten

![](assets/new-sms-search2.png)

Hier volgen enkele voorbeelden:

De **trekker van de Bounces van het Bericht van SMS** stelt een stroom, zoals het verzenden van een e-mail in werking, wanneer een SMS-bericht stuitert.

![](assets/sms-message-bounces-real.jpg)

De trigger **[!UICONTROL Subscribes to Vibes List]** start een flow wanneer een persoon zich abonneert.

![](assets/subscribes-to-vibes-list-real.jpg)

De trigger **[!UICONTROL Clicks Link in SMS Message]** start een flow wanneer iemand op een koppeling in het SMS-bericht klikt.

![](assets/clicks-link-in-sms-message.jpg)

## SMS-filters {#sms-filters}

U kunt ook Vibes-filters gebruiken in slimme lijsten. Het **[!UICONTROL Subscribed to Vibes List]** filter vindt iedereen die ** heeft ingetekend aan Vibes. Dit geldt zowel voor niet-geabonneerde als voor verwijderde personen, ook al worden verwijderde personen weggelaten uit de stroom. Dit filter is het meest geschikt voor rapportage.

![](assets/subscribed-to-vibes-list-filter-real.jpg)

Door contrast, vindt het **Lid van de Lijst van Levenben** filter *iedereen* momenteel geabonneerd aan Levenben en is het meest geschikt voor gebruik in Slimme Campagnes of lijsten.

![](assets/image001.png)

>[!NOTE]
>
>Alle SMS-filters bevatten standaard de **[!UICONTROL Date of Activity]** -beperking.

Nadat u opstellingsVeldt trekkers en filters in uw slimme lijst, kunt u [ de stroom ](/help/marketo/product-docs/mobile-marketing/vibes-sms-messages/add-a-flow-step-for-sms.md) bepalen.

>[!MORELIKETHIS]
>
>* [ bepaalt Slimme Lijst voor Slimme Campagne | Trigger ](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-trigger.md)
>* [ vind en voeg Filters aan een Slimme Lijst ](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/find-and-add-filters-to-a-smart-list.md) toe
