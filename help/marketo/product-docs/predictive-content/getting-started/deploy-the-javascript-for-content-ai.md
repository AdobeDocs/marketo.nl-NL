---
unique-page-id: 11385053
description: JavaScript implementeren voor Content-AI - Marketo Docs - Productdocumentatie
title: JavaScript implementeren voor Content-AI
exl-id: d48bfd1b-73e8-4013-88d6-8750e4ef532b
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '139'
ht-degree: 0%

---

# JavaScript implementeren voor Content-AI {#deploy-the-javascript-for-content-ai}

Als u voorspellende inhoud wilt gebruiken, moet u de RTP-tag (Web Personalization) genereren en instellen.

## Label genereren {#generate-tag}

1. Meld u aan bij uw account voor voorspellende inhoud. Ga naar **Accountinstellingen**.

   ![](assets/settings-dropdown-account-hands.png)

1. In **Domeinconfiguratie**, zoek het relevante domein en klik op **Label genereren**.

   ![](assets/generate-tag.png)

1. Kopieer en plak de tag Web Personalization in de HTML van uw website.

   ![](assets/web-personalization-tag.png)

   >[!NOTE]
   >
   >Kopieer de JavaScript-tag Web Personalization en plak deze als het eerste script in de koptekst van uw pagina&#39;s, tussen de `<head> </head>` -tags. Meer details bekijken [implementatieinstructies hier](/help/marketo/product-docs/web-personalization/rtp-tag-implementation/deploy-the-rtp-javascript.md).

1. Controleer of de tag op alle pagina&#39;s wordt weergegeven, inclusief bestemmingspagina&#39;s en subdomeinen. Controleer dit door met de rechtermuisknop op de pagina van uw website te klikken. Ga naar **Paginabron weergeven** in een webbrowser. Zoeken: &quot;RTP&quot;.

1. Bevestig dat de tagschakelaar is ingesteld op **ON**.
