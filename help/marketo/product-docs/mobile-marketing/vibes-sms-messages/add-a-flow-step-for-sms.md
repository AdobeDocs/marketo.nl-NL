---
unique-page-id: 11379045
description: Voeg een Stap van de Stroom voor SMS toe - Marketo Docs - de Documentatie van het Product
title: Voeg een Stap van de Stroom voor SMS toe
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '283'
ht-degree: 0%

---


# Voeg een Stap van de Stroom voor SMS toe {#add-a-flow-step-for-sms}

Marketo heeft drie stroomstappen die u in uw slimme campagnes van SMS kunt gebruiken:

* **SMS-bericht** verzenden - Met deze flowactie worden berichten verzonden naar mensen van de smartlist Marketo die zijn geabonneerd op een door de gebruiker geselecteerde abonnementenlijst met Vibes. Het abonnementsproces wordt niet gestart.
* **Abonneren op lijst met** Vibes - Deze flowactie start het SMS-abonnementsproces via een door de gebruiker geselecteerde Acquisition Campaign. Vibes stuurt vervolgens een bevestigingsbericht; de ontvanger moet hierop reageren om het abonnementsproces te voltooien.
* **Abonnement op Vibes List** opzeggen - Met deze flowactie wordt elke persoon losgekoppeld van een door de gebruiker geselecteerde abonnementenlijst met Vibes.

>[!NOTE]
>
>Bij het verzenden van SMS-berichten:
>
>* Marketo de-dupes per telefoonnummer. Dus als meerdere mensen hetzelfde telefoonnummer hebben, ontvangt slechts één persoon het bericht.
>* Marketo zal niet verzenden naar mensen die zijn toegevoegd op lijst van gewenste personen of die het in de handel brengen hebben opgeschort.

>



Voor algemene informatie over de stappen van de opstellingsstroom, zie een Stap van de Stroom aan een Slimme Campagne [toevoegen](../../../product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md).

Hier zijn de grondbeginselen voor het gebruiken van SMS.

1. Klik in Mijn Marketo op **Marketingactiviteiten**.

   ![](assets/image2016-7-28-11-3a41-3a17.png)

1. Zoek de slimme campagne waaraan u de SMS-flow wilt toevoegen. Klik op het tabblad **Stroom** .

   ![](assets/image2016-7-28-11-3a43-3a41.png)

1. Sleep over de flow, bijvoorbeeld SMS-bericht **** verzenden. Selecteer het SMS-bericht en de lijst Levendigheid in de keuzelijst.

   ![](assets/send-sms-message-hands.jpg)

   >[!NOTE]
   >
   >De kiezer in de lijst met virussen fungeert als een extra filter voor het publiek dat al in de slimme lijst is geïdentificeerd. Alleen de leads die tot die lijst met virussen behoren, worden geselecteerd.
   >
   >
   >De **Abonneren op Lijst** vanLevendigs en **Unsubscribe van de stromen van de Lijst** van Levendigs hebben verschillende vereisten. Voor **Abonneren**, moet u de lijst van Vibes en de de acquisitiecampagne van Vibes selecteren. Voor **Unsubscribe** is alleen de lijst met Vibes vereist.

