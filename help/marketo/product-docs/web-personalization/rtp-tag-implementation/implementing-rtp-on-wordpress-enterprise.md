---
unique-page-id: 4720215
description: Implementatie van RTP op Wordpress Enterprise - Marketo Docs - Productdocumentatie
title: RTP implementeren op Wordpress Enterprise
exl-id: 61cfd3f8-0811-4352-9752-0081ce19257b
feature: Web Personalization
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '95'
ht-degree: 1%

---

# RTP implementeren op Wordpress Enterprise {#implementing-rtp-on-wordpress-enterprise}

Volg onderstaande installatie-instructies om uw [!UICONTROL RTP tag] te implementeren:

1. Ga naar **[!UICONTROL Account Settings]** .

   a. Als u uw JavaScript-tag al hebt ontvangen van Support, gaat u verder met stap 3.

   ![](assets/image2014-11-30-15-3a19-3a21-3.png)

1. Zoek onder [!UICONTROL Domain] het relevante domein op en klik op **[!UICONTROL Generate Tag]** .

   ![](assets/image2014-11-30-15-3a20-3a17-3.png)

1. Kopieer de JavaScript-tag RTP.

1. Meld u aan bij uw [!DNL WordPress] -account als Admin-gebruiker

   a. Ga onder **[!UICONTROL Appearance]** naar **[!UICONTROL Custom JavaScript]** .
b. Plak de Javascript-tag RTP naar rechts na de bestaande code.

   ![](assets/image2014-12-3-17-3a51-3a46.png)

   >[!CAUTION]
   >
   >Wanneer u de code plakt, sluit u de volgende labels UIT:
   >
   >* `<!-- RTP tag -->`
   >* `<script type='text/javascript'>`
   >* `</script>`
   >* `<!-- End of RTP tag -->`
   >
   >Voeg ALLEEN het script in.

1. Klik op **[!UICONTROL Update]**.
