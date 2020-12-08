---
unique-page-id: 4720218
description: RTP implementeren met Adobe Tag Manager - Marketo Docs - Productdocumentatie
title: RTP implementeren met Adobe Tag Manager
translation-type: tm+mt
source-git-commit: d88fb92a00e4c20509617e6ef8b2e51b66cc085b
workflow-type: tm+mt
source-wordcount: '214'
ht-degree: 0%

---


# RTP implementeren met Adobe Tag Manager {#implementing-rtp-using-adobe-tag-manager}

Volg onderstaande installatie-instructies om uw RTP-tag te implementeren:

1. Meld u aan bij uw RTP-account.
1. Ga naar **Accountinstellingen.**

   Als u uw JavaScript-tag al hebt ontvangen van Support, gaat u verder met stap 4.

   ![](assets/image2014-11-30-15-3a19-3a21-4.png)

1. Zoek onder Domein het relevante domein en klik op Tag **** genereren.

   ![](assets/image2014-11-30-15-3a20-3a17-4.png)

1. Meld u aan bij uw Dynamic Tag Manager-account ([https://dtm.adobe.com/sign_in](https://dtm.adobe.com/sign_in)).
1. Ga naar **dashboard.** Klik op de relevante webeigenschap.

   ![](assets/image2014-12-3-17-3a58-3a17.png)

1. Ga naar **Regels,** klik **Create Nieuwe Regel.**

1. Vul het volgende in

   1. Naam: **Marketo RTP**
   1. Voorwaarden (samenvouwen): Triggerregel bij - **Boven aan pagina**
   1. JavaScript (samenvouwen): Klik op Nieuw script **toevoegen**

   ![](assets/image2014-12-3-17-3a59-3a40.png)

1. Roep de nieuwe tag aan: **Marketo RTP-tag**
1. Verwijder de volgende code uit de markering RTP

   * `<script type='text/javascript'>`
   * `</script>`

1. Plak de RTP JavaScript-tag.

   ![](assets/image2014-12-3-18-3a3-3a45.png)

   >[!CAUTION]
   >
   >Zorg ervoor dat u alle tags verwijdert en alleen het script zelf laat (geen `<script type='text/javascript'>` , `</script>` )

1. Klik op Code **** opslaan in de scripteditor en Regel **** opslaan in de regeleditor.

1. Zoek in het deelvenster Regels de regel voor het laden van de pagina Marketo RTP en selecteer in het vervolgkeuzemenu **Handelingen** de optie Regels **** activeren.

   ![](assets/image2014-12-3-18-3a4-3a14.png)

1. **Controleer** of deze code op alle pagina&#39;s wordt weergegeven, inclusief bestemmingspagina&#39;s en subdomeinen.

   U kunt dit doen door met de rechtermuisknop op de pagina&#39;s van uw website te klikken. Ga naar **Inspect Element**, klik op **Netwerk, **Onderzoek: **RTP**.
