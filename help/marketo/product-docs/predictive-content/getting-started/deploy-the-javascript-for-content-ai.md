---
unique-page-id: 11385053
description: JavaScript for Content-AI - Marketo Docs - Productdocumentatie implementeren
title: JavaScript for Content-AI implementeren
exl-id: d48bfd1b-73e8-4013-88d6-8750e4ef532b
feature: Predictive Content
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '129'
ht-degree: 0%

---

# JavaScript for Content-AI implementeren {#deploy-the-javascript-for-content-ai}

Als u voorspellende inhoud wilt gebruiken, moet u de RTP-tag (Web Personalization) genereren en instellen.

## Label genereren {#generate-tag}

1. Meld u aan bij uw account voor voorspellende inhoud. Ga naar **[!UICONTROL Account Settings]** .

   ![](assets/settings-dropdown-account-hands.png)

1. Zoek in **[!UICONTROL Domain Configuration]** het relevante domein op en klik op **[!UICONTROL Generate Tag]** .

   ![](assets/generate-tag.png)

1. Kopieer en plak de Web Personalization-tag naar de HTML van uw website.

   ![](assets/web-personalization-tag.png)

   >[!NOTE]
   >
   >Kopieer de Personalization JavaScript-tag Web en plak deze als het eerste script in de koptekst van uw pagina&#39;s, tussen de `<head> </head>` -tags. Zie meer gedetailleerde [ implementatieinstructies hier ](/help/marketo/product-docs/web-personalization/rtp-tag-implementation/deploy-the-rtp-javascript.md).

1. Controleer of de tag op alle pagina&#39;s wordt weergegeven, inclusief bestemmingspagina&#39;s en subdomeinen. Controleer dit door met de rechtermuisknop op de pagina van uw website te klikken. Ga naar **[!UICONTROL View Page Source]** in een webbrowser. Zoeken: &quot;RTP&quot;.

1. Controleer of de schakeloptie Tag is ingesteld op **[!UICONTROL ON]** .
