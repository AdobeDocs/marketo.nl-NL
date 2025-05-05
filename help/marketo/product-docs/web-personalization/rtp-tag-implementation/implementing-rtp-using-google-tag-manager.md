---
unique-page-id: 4720145
description: RTP implementeren met Google Tag Manager - Marketo Docs - Productdocumentatie
title: RTP implementeren met Google-tagbeheer
exl-id: f7f06779-8abe-4c8c-9197-9d0c6bcfed49
feature: Web Personalization
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '159'
ht-degree: 0%

---

# RTP implementeren met Google-tagbeheer {#implementing-rtp-using-google-tag-manager}

Volg onderstaande installatie-instructies om uw RTP-tag te implementeren.

1. Meld u aan bij uw Google Tag Manager-account.

1. Voeg een nieuwe tag toe > Tagconfiguraties > Aangepaste HTML-tag&#x200B;**.** Roep het **RTP**.

1. Meld u aan bij uw RTP-account&#x200B;**.**

1. Ga naar **Accountinstellingen**.

   a. Ga naar stap 6 als u al een JavaScript-tag hebt ontvangen van Support.

   ![](assets/image2014-11-30-15-3a19-3a21.png)

1. Zoek onder Domein het relevante domein en klik op **Label genereren**.

   ![](assets/image2014-11-30-15-3a20-3a17.png)

1. Kopieer de RTP JavaScript-tag en plak deze naar het nieuwe **Aangepaste HTML-tag** u hebt gemaakt (Stap 1).

1. Klikken **+Regel toevoegen aan brandcode**. Selecteren **Alle pagina&#39;s**.

1. Klikken **Opslaan** en [de nieuwe versie publiceren](https://support.google.com/tagmanager/answer/2699097?hl=en).

1. Controleer of deze code op alle pagina&#39;s wordt weergegeven, inclusief bestemmingspagina&#39;s en subdomeinen.

   a. U kunt dit doen door met de rechtermuisknop op de pagina van uw website te klikken. Ga naar **Inspect-element**, Zoeken naar **RTP** om de tag te zoeken.
