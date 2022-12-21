---
unique-page-id: 4720149
description: Implementatie van RTP op Wordpress - Marketo Docs - Productdocumentatie
title: RTP implementeren op Wordpress
exl-id: f010942b-02bb-447b-a272-c4237782b2d7
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '187'
ht-degree: 0%

---

# RTP implementeren op Wordpress {#implementing-rtp-on-wordpress}

Volg onderstaande installatie-instructies om uw RTP-tag te implementeren:

1. Open de **header.php** bestand van uw **Het thema WordPress**.

   U kunt een FTP-client gebruiken om toegang te krijgen tot uw server of de themabestanden rechtstreeks vanuit het WordPress-dashboard bewerken. De bestandseditor bevindt zich onder de **Weergave** in het zijbalkmenu.

   ![](assets/image2014-11-30-15-3a35-3a30.png)

1. Zoek in de lijst met sjabloonbestanden rechts van de teksteditor naar **header.php** en open.

1. Ga naar **Accountinstellingen**.

   a. Als u al een JavaScript-tag hebt ontvangen van Support, gaat u verder met stap 5.

   ![](assets/image2014-11-30-15-3a19-3a21-1.png)

1. Zoek onder Domein het relevante domein en klik op **Label genereren**.

   ![](assets/image2014-11-30-15-3a20-3a17-1.png)

1. Kopieer de RTP JavaScript-tag en plak deze naar uw websitesjablonen.

   a. Zorg ervoor dat dit het eerste script in de koptekst van de pagina is - tussen de **`<head> </head>`** -tags.

   ![](assets/image2014-11-30-15-3a36-3a31.png)

1. Klikken op **Bestand bijwerken** voor het bestand header.php.

1. Controleer of het wordt weergegeven op alle pagina&#39;s, inclusief bestemmingspagina&#39;s en subdomeinen.

   a. U kunt dit doen door met de rechtermuisknop op de pagina van uw website te klikken. Ga naar **Pagina-bron weergeven.** Zoeken naar **RTP** om de tag te zoeken.
