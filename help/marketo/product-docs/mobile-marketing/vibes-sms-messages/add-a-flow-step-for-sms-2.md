---
description: Een stap toevoegen voor SMS - Marketo Docs - Productdocumentatie
title: Voeg een Stap van de Stroom voor SMS toe
hide: true
hidefromtoc: true
feature: Mobile Marketing
source-git-commit: fee2d692acd8d54f2e308e2d5edc9876d13d5a4d
workflow-type: tm+mt
source-wordcount: '377'
ht-degree: 0%

---

# Voeg een Stap van de Stroom voor SMS toe {#add-a-flow-step-for-sms}

Marketo Engage heeft drie Stappen van de Stroom u in uw Slimme Campagnes van SMS kunt gebruiken:

<table>
<tbody>
  <tr>
    <td style="width:25%">SMS-bericht verzenden</td>
    <td>Deze flowactie verzendt berichten naar mensen van de Smart List van Marketo die zijn geabonneerd op een door de gebruiker gekozen abonnementenlijst van Vibes. Het abonnementsproces wordt niet gestart. <a href="/help/marketo/product-docs/mobile-marketing/vibes-sms-messages/send-a-vibes-sms-message.md">Meer informatie</a>.</td>
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
>Bij het verzenden van SMS-berichten:
>
>* Marketo dedupliceert per telefoonnummer. Dus, als de veelvoudige mensen het zelfde telefoonaantal hebben, slechts zal één persoon het bericht ontvangen als zij een lid van slechts één lijst van het Abonnement van Vibes zijn. De-duping wordt gedaan op het niveau van de Abonnementenlijst van Vibes, niet het het programmaniveau van Marketo.
>* Marketo zal niet verzenden naar mensen die zijn gevoegd op lijst van gewenste personen of die het in de handel brengen hebben opgeschort.

Voor algemene informatie over het instellen van stroomstappen raadpleegt u [Een stroomstap toevoegen aan een slimme campagne](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md).

Hier zijn de grondbeginselen voor het gebruiken van SMS.

1. Klik in Mijn Marketo op **Marketingactiviteiten**.

   ![](assets/add-a-flow-step-for-sms-1.png)

1. Zoek en selecteer de slimme campagne waaraan u de SMS-flow wilt toevoegen.

   SCREENSHOT

1. Kies op het tabblad Slimme lijst de gewenste trigger(s) (bijvoorbeeld &quot;Formulier invullen&quot;).

   SCREENSHOT

1. In de **Stroom** Tab, slepen over de stroomstap (bijvoorbeeld **SMS-bericht verzenden**). Selecteer het SMS-bericht en de lijst Levendigheid in de keuzelijst.

   ![](assets/send-sms-message-hands.jpg)

   >[!NOTE]
   >
   >De kiezer in de lijst met virussen fungeert als een extra filter voor het publiek dat al in de slimme lijst is geïdentificeerd. Alleen de leads die tot die lijst met virussen behoren, worden geselecteerd.
   >
   >De **Abonneren op lijst met beeldschermen** en **Abonnement op Vibes List opzeggen** stromen hebben verschillende vereisten. Voor **Abonneren**, moet u de Vibes-lijst en de Vibes-acquisitiecampagne selecteren. Voor **Abonnement opzeggen**, is alleen de lijst met Vibes vereist.
