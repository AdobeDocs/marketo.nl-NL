---
unique-page-id: 4720151
description: Implementatie van RTP op Marketo-landingspagina's - Marketo Docs - Productdocumentatie
title: RTP implementeren op Marketo-landingspagina's
exl-id: fd19c3ad-d3f6-44a3-9f7a-d518e2d3f02a
feature: Web Personalization
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '169'
ht-degree: 0%

---

# RTP implementeren op Marketo-landingspagina&#39;s {#implementing-rtp-on-marketo-landing-pages}

Volg onderstaande installatie-instructies om uw [!UICONTROL RTP tag] te implementeren:

1. Ga naar de **[!UICONTROL Design Studio].** Open het item dat u wilt bewerken. Selecteer **[!UICONTROL Template Actions]** en selecteer **[!UICONTROL Edit Draft]** .

   ![](assets/image2015-4-26-18-3a27-3a4.png)

1. Breng uw malplaatjeveranderingen op het **HTML Source** lusje aan.

   ![](assets/image2015-4-26-18-3a28-3a17.png)

1. Ga in uw RTP-account naar **[!UICONTROL Account Settings]** .

   a. Als u uw JavaScript-tag al hebt ontvangen van Support, gaat u verder met stap 5.

   ![](assets/image2014-11-30-15-3a19-3a21-2.png)

1. Zoek onder [!UICONTROL Domain] het relevante domein op en klik op **[!UICONTROL Generate Tag]** .

   ![](assets/image2015-4-26-18-3a27-3a35.png)

   ![](assets/image2014-11-30-15-3a20-3a17-2.png)

1. Kopieer de JavaScript-tag RTP en plak deze tussen de **`<head> </head>`** -tags naar al uw sjablonen voor de bestemmingspagina.

1. Klik op **[!UICONTROL Save]** en **[!UICONTROL Close]** het venster.

1. Ga terug in **[!UICONTROL Design Studio]** en keur de openingspagina goed vanuit **[!UICONTROL Template Actions]** en klik op **[!UICONTROL Approve]** .

   ![](assets/image2015-4-26-18-3a28-3a30.png)

1. Tot slot zult u **** om het even welke het landen pagina&#39;s opnieuw moeten goedkeuren gebruikend dat malplaatje voor de malplaatjeveranderingen om van kracht te worden. U kunt ze allemaal tegelijk opnieuw goedkeuren vanuit de hoofdsectie van [!UICONTROL Landing Pages] .

   ![](assets/image2015-4-26-18-3a28-3a49.png)

1. Controleer of het wordt weergegeven op alle pagina&#39;s, inclusief bestemmingspagina&#39;s en subdomeinen.

   U kunt dit doen door met de rechtermuisknop op de pagina van uw website te klikken. Ga naar **[!UICONTROL View Page Source].** Zoek naar **[!UICONTROL RTP]** om de tag te zoeken.
