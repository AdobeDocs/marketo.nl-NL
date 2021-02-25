---
unique-page-id: 4720218
description: RTP implementeren met Adobe Tag Manager - Marketo Docs - Productdocumentatie
title: RTP implementeren met Adobe Tag Manager
translation-type: tm+mt
source-git-commit: fbaf57ec4f3532c2d71acf23171d60873b1c997c
workflow-type: tm+mt
source-wordcount: '216'
ht-degree: 0%

---


# RTP implementeren met Adobe Tag Manager {#implementing-rtp-using-adobe-tag-manager}

Volg onderstaande installatie-instructies om uw RTP-tag te implementeren:

1. Meld u aan bij uw RTP-account.

1. Ga naar **Accountinstellingen**.

   a. Als u uw JavaScript-tag al hebt ontvangen van Support, gaat u verder met stap 4.

   ![](assets/image2014-11-30-15-3a19-3a21-4.png)

1. Zoek onder Domein het relevante domein en klik op **Tag genereren**.

   ![](assets/image2014-11-30-15-3a20-3a17-4.png)

1. Meld u aan bij uw Dynamic Tag Manager-account ([https://dtm.adobe.com/sign_in](https://dtm.adobe.com/sign_in)).

1. Ga naar **dashboard.** Klik op de relevante webeigenschap.

   ![](assets/image2014-12-3-17-3a58-3a17.png)

1. Ga naar **Regels**, klik **Nieuwe Regel maken**.

1. Vul het volgende in

   1. Naam: **Marketo RTP**
   1. Voorwaarden (samenvouwen): Triggerregel bij - **Boven aan pagina**
   1. JavaScript (samenvouwen): Klik **Nieuw script toevoegen**

   ![](assets/image2014-12-3-17-3a59-3a40.png)

1. Roep de nieuwe tag aan: **Marketo RTP-tag**

1. Verwijder de volgende code uit de markering RTP

   * `<script type='text/javascript'>`
   * `</script>`

1. Plak de RTP JavaScript-tag.

   ![](assets/image2014-12-3-18-3a3-3a45.png)

   >[!CAUTION]
   >
   >Zorg ervoor u alle markeringen verwijdert en slechts het manuscript zelf verlaat (geen `<script type='text/javascript'>`, `</script>`)

1. Klik **sparen Code** in de manuscripteditor en **sparen Regel** in de regelredacteur.

1. Zoek in het deelvenster Regels de regel voor het laden van de pagina Marketo RTP en selecteer **Acties** vervolgkeuzelijst **Regels activeren**.

   ![](assets/image2014-12-3-18-3a4-3a14.png)

1. **Controleer** of deze code op alle pagina&#39;s wordt weergegeven, inclusief bestemmingspagina&#39;s en subdomeinen.

   U kunt dit doen door met de rechtermuisknop op de pagina&#39;s van uw website te klikken. Ga naar **Inspect Element**, klik op **Netwerk**, Onderzoek: **RTP**.
