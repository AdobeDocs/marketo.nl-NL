---
unique-page-id: 4720215
description: Implementatie van RTP op Wordpress Enterprise - Marketo Docs - Productdocumentatie
title: RTP implementeren op Wordpress Enterprise
exl-id: 61cfd3f8-0811-4352-9752-0081ce19257b
feature: Web Personalization
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '106'
ht-degree: 0%

---

# RTP implementeren op Wordpress Enterprise {#implementing-rtp-on-wordpress-enterprise}

Volg onderstaande installatie-instructies om uw RTP-tag te implementeren:

1. Ga naar **Accountinstellingen**.

   a. Als u uw JavaScript-tag al hebt ontvangen van Support, gaat u verder met stap 3.

   ![](assets/image2014-11-30-15-3a19-3a21-3.png)

1. Zoek onder Domein het relevante domein en klik op **Label genereren**.

   ![](assets/image2014-11-30-15-3a20-3a17-3.png)

1. Kopieer de RTP JavaScript-tag.

1. Aanmelden bij uw WordPress-account als Admin-gebruiker

   a. Onder **Weergave**, ga naar **Aangepast JavaScript**.
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

1. Klikken **Bijwerken**.
