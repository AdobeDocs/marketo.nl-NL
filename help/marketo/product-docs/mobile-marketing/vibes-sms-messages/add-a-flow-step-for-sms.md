---
unique-page-id: 11379045
description: Een stap toevoegen voor SMS - Marketo Docs - Productdocumentatie
title: Voeg een Stap van de Stroom voor SMS toe
exl-id: 8e96f6ad-43c9-4d64-8cb6-241664956d72
feature: Mobile Marketing
source-git-commit: cd09ad43c08855af63131aa385c4fd406c963926
workflow-type: tm+mt
source-wordcount: '283'
ht-degree: 0%

---

# Voeg een Stap van de Stroom voor SMS toe {#add-a-flow-step-for-sms}

Marketo heeft drie stroomstappen die je kunt gebruiken in je SMS Smart-campagnes:

* **SMS-bericht verzenden** - Deze flowactie verzendt berichten naar mensen van de Marketo-smartlist die zijn geabonneerd op een door de gebruiker geselecteerde Vibes-abonnementenlijst. Het abonnementsproces wordt niet gestart.
* **Abonneren op lijst met beeldschermen** - Deze flowactie start het SMS-abonnementsproces via een door de gebruiker geselecteerde Vibes Acquisition Campaign. Vibes verzendt dan een bevestigingsbericht; de ontvanger moet het antwoorden om het abonnementsproces te voltooien.
* **Abonnement op Vibes List opzeggen** - Met deze flowactie wordt elke persoon losgekoppeld van een door de gebruiker geselecteerde abonnementenlijst met Vibes.

>[!NOTE]
>
>Bij het verzenden van SMS-berichten:
>
>* Marketo dedupliceert per telefoonnummer. Dus als meerdere mensen hetzelfde telefoonnummer hebben, ontvangt slechts één persoon het bericht.
>* Marketo zal niet verzenden naar mensen die zijn gevoegd op lijst van gewenste personen of die het in de handel brengen hebben opgeschort.

Voor algemene informatie over het instellen van stroomstappen raadpleegt u [Een stroomstap toevoegen aan een slimme campagne](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md).

Hier zijn de grondbeginselen voor het gebruiken van SMS.

1. Klik in Mijn Marketo op **Marketingactiviteiten**.

   ![](assets/add-a-flow-step-for-sms-1.png)

1. Zoek de slimme campagne waaraan u de SMS-flow wilt toevoegen. Klik op de knop **Stroom** tab.

   ![](assets/image2016-7-28-11-3a43-3a41.png)

1. Sleep bijvoorbeeld over de flow **SMS-bericht verzenden**. Selecteer het SMS-bericht en de lijst Levendigheid in de keuzelijst.

   ![](assets/send-sms-message-hands.jpg)

   >[!NOTE]
   >
   >De kiezer in de lijst met virussen fungeert als een extra filter voor het publiek dat al in de slimme lijst is geïdentificeerd. Alleen de leads die tot die lijst met virussen behoren, worden geselecteerd.
   >
   >De **Abonneren op lijst met beeldschermen** en **Abonnement op Vibes List opzeggen** stromen hebben verschillende vereisten. Voor **Abonneren**, moet u de Vibes-lijst en de Vibes-acquisitiecampagne selecteren. Voor **Abonnement opzeggen**, is alleen de lijst met Vibes vereist.
