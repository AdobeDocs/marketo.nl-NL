---
unique-page-id: 11385053
description: JavaScript implementeren voor Content-AI - Marketo Docs - Productdocumentatie
title: JavaScript implementeren voor Content-AI
translation-type: tm+mt
source-git-commit: 06e0f5489e6375a97e2fe77834bf45fa41f23ea6
workflow-type: tm+mt
source-wordcount: '139'
ht-degree: 0%

---


# JavaScript implementeren voor inhouds-AI {#deploy-the-javascript-for-content-ai}

Als u voorspellende inhoud wilt gebruiken, moet u de RTP-tag (Web Personalization) genereren en instellen.

## Label {#generate-tag} genereren

1. Meld u aan bij uw account voor voorspellende inhoud. Ga naar **Accountinstellingen**.

   ![](assets/settings-dropdown-account-hands.png)

1. Zoek in **Domeinconfiguratie** het relevante domein en klik op **Label genereren**.

   ![](assets/generate-tag.png)

1. Kopieer en plak de tag Web Personalization in de HTML van uw website.

   ![](assets/web-personalization-tag.png)

   >[!NOTE]
   >
   >Kopieer de JavaScript-tag Web Personalization en plak deze als het eerste script in de koptekst van uw pagina&#39;s, tussen de `<head> </head>`-tags. Zie meer gedetailleerde [implementatieinstructies hier](/help/marketo/product-docs/web-personalization/rtp-tag-implementation/deploy-the-rtp-javascript.md).

1. Controleer of de tag op alle pagina&#39;s wordt weergegeven, inclusief bestemmingspagina&#39;s en subdomeinen. Controleer dit door met de rechtermuisknop op de pagina van uw website te klikken. Ga naar **Paginabron weergeven** in een webbrowser. Zoeken: &quot;RTP&quot;.

1. Bevestig dat de Tagknevel aan **ON** wordt geplaatst.
