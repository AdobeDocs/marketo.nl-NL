---
unique-page-id: 11385053
description: JavaScript implementeren voor Content-AI - Marketo Docs - Productdocumentatie
title: JavaScript implementeren voor Content-AI
translation-type: tm+mt
source-git-commit: 6ae882dddda220f7067babbe5a057eec82601abf
workflow-type: tm+mt
source-wordcount: '196'
ht-degree: 0%

---


# JavaScript implementeren voor inhouds-AI {#deploy-the-javascript-for-content-ai}

>[!NOTE]
>
>Afhankelijk van de aankoopdatum kan uw Marketo-abonnement ofwel Voorspelende inhoud markeren of Inhoud`<sup>AI</sup>` bevatten. Voor degenen die Voorspelende Inhoud gebruiken, maakt Marketo tot 30 april 2018 de eigenschappen van de Analyse van de Inhoud`<sup>AI</sup>` toe. Als u deze functies na die datum wilt behouden, neemt u contact op met de manager succes van de klant van Marketo om te upgraden naar Marketo Content`<sup>AI</sup>`.

Als u voorspellende inhoud wilt gebruiken, moet u de RTP (Web Personalization) `tag.` genereren en instellen

## Label {#generate-tag} genereren

1. Meld u aan bij uw account voor voorspellende inhoud. Ga naar **Accountinstellingen**.

   ![](assets/settings-dropdown-account-hands.png)

1. Zoek in **Domeinconfiguratie** het relevante domein en klik op **Label genereren.**

   ![](assets/generate-tag.png)

1. Kopieer en plak de tag Web Personalization in de HTML van uw website.

   ![](assets/web-personalization-tag.png)

   >[!NOTE]
   >
   >Kopieer de JavaScript-tag Web Personalization en plak deze als het eerste script in de koptekst van uw pagina&#39;s, tussen de `<head> </head>`-tags. Zie meer gedetailleerde [implementatieinstructies hier](https://docs.marketo.com/display/docs/rtp+tag+implementation) [](https://pages2.marketo.com/rtp-implementation.html)

1. Controleer of de tag op alle pagina&#39;s wordt weergegeven, inclusief bestemmingspagina&#39;s en subdomeinen. Controleer dit door met de rechtermuisknop op uw `website’s` pagina te klikken. Ga naar **Paginabron weergeven** in een webbrowser. Zoeken: &quot;RTP&quot;.
1. Bevestig dat de Tagknevel aan **ON** wordt geplaatst.

