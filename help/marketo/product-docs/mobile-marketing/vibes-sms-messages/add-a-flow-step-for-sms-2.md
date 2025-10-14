---
description: Een stap toevoegen voor SMS - Marketo Docs - Productdocumentatie
title: Voeg een Stap van de Stroom voor SMS toe
hide: true
hidefromtoc: true
feature: Mobile Marketing
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '377'
ht-degree: 0%

---

# Voeg een Stap van de Stroom voor SMS toe {#add-a-flow-step-for-sms}

Marketo Engage heeft drie stappen die u kunt gebruiken in uw slimme SMS-campagnes:

<table>
<tbody>
  <tr>
    <td style="width:25%">SMS-bericht verzenden</td>
    <td>Deze flowactie verzendt berichten naar mensen van de Smart List van Marketo die zijn geabonneerd op een door de gebruiker gekozen abonnementenlijst van Vibes. Het abonnementsproces wordt niet gestart. <a href="/help/marketo/product-docs/mobile-marketing/vibes-sms-messages/send-a-vibes-sms-message.md"> leer meer </a>.</td>
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

Voor algemene informatie bij de stappen van de opstellingsstroom, zie [&#x200B; een Stap van de Stroom aan een Slimme Campagne &#x200B;](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md) toevoegen.

Hier zijn de grondbeginselen voor het gebruiken van SMS.

1. In Mijn Marketo, klik **de Activiteiten van de Marketing**.

   ![](assets/add-a-flow-step-for-sms-1.png)

1. Zoek en selecteer de slimme campagne waaraan u de SMS-flow wilt toevoegen.

   SCREENSHOT

1. Kies op het tabblad Slimme lijst de gewenste trigger(s) (bijvoorbeeld &quot;Formulier invullen&quot;).

   SCREENSHOT

1. In het **lusje van de Stroom**, sleep over de stroomstap (b.v., **verzend het Bericht van SMS**). Selecteer het SMS-bericht en de lijst Levendigheid in de keuzelijst.

   ![](assets/send-sms-message-hands.jpg)

   >[!NOTE]
   >
   >De kiezer in de lijst met virussen fungeert als een extra filter voor het publiek dat al in de slimme lijst is geïdentificeerd. Alleen de leads die tot die lijst met virussen behoren, worden geselecteerd.
   >
   >Het **abonnement aan Lijst van Levenben** en **Unsubscribe van de stromen van de Lijst van Levendigs** hebben verschillende vereisten. Voor **Abonneren**, moet u de lijst van Levenben en de de acquisitiecampagne van Levenben selecteren. Voor **Unsubscribe**, slechts wordt de lijst van Lagen vereist.
