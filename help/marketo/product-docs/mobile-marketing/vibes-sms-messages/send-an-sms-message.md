---
description: Een SMS-bericht verzenden - Marketo Docs - Productdocumentatie
title: Een SMS-bericht verzenden
feature: Mobile Marketing
exl-id: 2c863ded-f441-4217-9541-6dcc442d9831
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '321'
ht-degree: 0%

---

# Een SMS-bericht verzenden {#send-a-vibes-sms-message}

U hebt [ uw bericht van SMS ](/help/marketo/product-docs/mobile-marketing/vibes-sms-messages/create-an-sms-message.md){target="_blank"} gecreeerd, nu is het tijd om het te verzenden. U kunt het verzenden via Campagne of Trigger.

>[!NOTE]
>
>Bij het verzenden van SMS-berichten:
>
>* Marketo Engage dedupliceert per telefoonnummer. Dus, als de veelvoudige mensen het zelfde telefoonaantal hebben, slechts zal één persoon het bericht ontvangen als zij een lid van slechts één lijst van het Abonnement van Vibes zijn. De-duping wordt gedaan op het niveau van de Abonnementenlijst van Vibes, niet het het programmaniveau van Marketo.
>* Marketo zal niet verzenden naar mensen die zijn gevoegd op lijst van gewenste personen of die het in de handel brengen hebben opgeschort.
>* Een SMS-bericht wordt niet naar iemand verzonden die niet is geabonneerd als deze niet in de lijst Mobiele database van Vibes staat.

## Een SMS-bericht over een batch verzenden {#send-a-batch-sms}

1. In Mijn Marketo, klik **de Activiteiten van de Marketing**.

   ![](assets/send-an-sms-message-1.png)

1. Zoek en selecteer de gewenste slimme campagne.

   ![](assets/send-an-sms-message-2.png)

1. Klik het **Slimme lusje van de Lijst** en bepaal het publiek voor SMS. In dit voorbeeld sturen we naar iedereen in onze database met &quot;Adobe&quot; als bedrijf.

   ![](assets/send-an-sms-message-3.png)

1. In het **Stroom** lusje, sleep over **verzend het Bericht van SMS**. Selecteer de gewenste lijst van het Bericht van SMS en van Lagen van drop-down.

   ![](assets/send-an-sms-message-4.png)

   >[!NOTE]
   >
   >De kiezer van de Lijst van Levendigheden fungeert als een verder filter voor het publiek dat al in de Slimme Lijst wordt geïdentificeerd om slechts mensen te richten die tot die lijst van Levenben behoren.

1. Klik het **lusje van het Programma** en programma uw SMS.

   ![](assets/send-an-sms-message-5.png)

## SMS-en naar Trigger sturen {#send-a-trigger-sms}

1. In Mijn Marketo, klik **de Activiteiten van de Marketing**.

   ![](assets/send-an-sms-message-6.png)

1. Zoek en selecteer de gewenste slimme campagne.

   ![](assets/send-an-sms-message-7.png)

1. Klik het **Slimme lusje van de Lijst**, selecteer de gewenste trekker en bepaal zijn waarde. In dit voorbeeld, gebruiken wij **Vult Vorm** uit.

   ![](assets/send-an-sms-message-8.png)

1. In het **Stroom** lusje, sleep over **verzend het Bericht van SMS**. Selecteer de gewenste lijst van het Bericht van SMS en van Lagen van drop-down.

   ![](assets/send-an-sms-message-9.png)

   >[!NOTE]
   >
   >De kiezer van de Lijst van Levendigheden fungeert als een verder filter voor het publiek dat al in de Slimme Lijst wordt geïdentificeerd om slechts mensen te richten die tot die lijst van Levenben behoren.

1. Klik het **Programma** lusje, dan **activeert**.

   ![](assets/send-an-sms-message-10.png)

>[!MORELIKETHIS]
>
>* [ creeer een Bericht van Lagen ](/help/marketo/product-docs/mobile-marketing/vibes-sms-messages/create-an-sms-message.md){target="_blank"}
>* [ Gebruikend de Opties van SMS in een Slimme Campagne ](/help/marketo/product-docs/mobile-marketing/vibes-sms-messages/using-sms-options-in-a-smart-campaign.md){target="_blank"}
