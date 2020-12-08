---
unique-page-id: 11385053
description: JavaScript implementeren voor Content-AI - Marketo Docs - Productdocumentatie
title: JavaScript implementeren voor Content-AI
translation-type: tm+mt
source-git-commit: 1a29614ec938074902af201b2ffc11cfaa625f7a
workflow-type: tm+mt
source-wordcount: '196'
ht-degree: 0%

---


# JavaScript implementeren voor Content-AI {#deploy-the-javascript-for-content-ai}

>[!NOTE]
>
>Afhankelijk van de aankoopdatum kan uw abonnement op Marketo de optie Voorspelende inhoud of Inhoud`<sup>AI</sup>`markeren bevatten. Marketo schakelt de functie Content`<sup>AI</sup>` Analytics voor gebruikers die gebruikmaken van voorspellende inhoud in tot 30 april 2018. Als u deze functies na die datum wilt behouden, neemt u contact op met de manager Succes bij Marketo-klanten om te upgraden naar Marketo-inhoud`<sup>AI</sup>`.

Om Voorspelende Inhoud te gebruiken, moet u produceren en opstelling uw RTP (de Personalisatie van het Web) `tag.`

## Label genereren {#generate-tag}

1. Meld u aan bij uw account voor voorspellende inhoud. Ga naar **Accountinstellingen**.

   ![](assets/settings-dropdown-account-hands.png)

1. Zoek in **Domeinconfiguratie** het relevante domein op en klik op Tag **genereren.**

   ![](assets/generate-tag.png)

1. Kopieer en plak de tag Web Personalization in de HTML van uw website.

   ![](assets/web-personalization-tag.png)

   >[!NOTE]
   >
   >Kopieer de JavaScript-tag Web Personalization en plak deze als het eerste script in de koptekst van uw pagina&#39;s, tussen de `<head> </head>` tags. Zie hier [gedetailleerdere](http://docs.marketo.com/display/docs/rtp+tag+implementation) implementatieinstructies [.](http://pages2.marketo.com/rtp-implementation.html)

1. Controleer of de tag op alle pagina&#39;s wordt weergegeven, inclusief bestemmingspagina&#39;s en subdomeinen. Controleer dit door met de rechtermuisknop op uw `website’s` pagina te klikken. Ga naar Paginabron **** weergeven in een webbrowser. Zoeken: &quot;RTP&quot;.
1. Bevestig dat de tagschakeloptie is ingesteld op **AAN**.

