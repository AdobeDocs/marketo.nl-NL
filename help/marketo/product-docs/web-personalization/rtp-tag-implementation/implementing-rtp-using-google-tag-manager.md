---
unique-page-id: 4720145
description: RTP implementeren met Google Tag Manager - Marketo Docs - Productdocumentatie
title: RTP implementeren met Google-tagbeheer
exl-id: f7f06779-8abe-4c8c-9197-9d0c6bcfed49
feature: Web Personalization
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '129'
ht-degree: 0%

---

# RTP implementeren met [!DNL Google Tag Manager] {#implementing-rtp-using-google-tag-manager}

Volg onderstaande installatie-instructies om uw RTP-tag te implementeren.

1. Meld u aan bij uw [!DNL Google Tag Manager] -account.

1. Voeg een nieuwe **[!UICONTROL Tag]** > **[!UICONTROL Tag Configurations]** > **[!UICONTROL Custom HTML Tag]toe.** roep het **RTP**.

1. Login aan uw **rekening RTP**.

1. Ga naar **[!UICONTROL Account Settings]** .

   a. Als u uw JavaScript-tag al hebt ontvangen van Support, gaat u verder met stap 6.

   ![](assets/image2014-11-30-15-3a19-3a21.png)

1. Zoek onder [!UICONTROL Domain] het relevante domein op en klik op **[!UICONTROL Generate Tag]** .

   ![](assets/image2014-11-30-15-3a20-3a17.png)

1. Kopieer de markering van JavaScript RTP en kleef het aan de nieuwe **Markering van HTML van de Douane** u creeerde (Stap 1).

1. Klik op **[!UICONTROL Add Rule to Fire Tag]**. Selecteer **[!UICONTROL All Pages]** .

1. Klik **[!UICONTROL Save]** en [ publiceren de nieuwe versie ](https://support.google.com/tagmanager/answer/2699097?hl=en).

1. Controleer of deze code op alle pagina&#39;s wordt weergegeven, inclusief bestemmingspagina&#39;s en subdomeinen.

   a. U kunt dit doen door met de rechtermuisknop op de pagina van uw website te klikken. Ga naar **[!UICONTROL Inspect Element]**, Onderzoek naar **RTP** om van de markering de plaats te bepalen.
