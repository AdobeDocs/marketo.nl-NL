---
unique-page-id: 4720151
description: Implementatie van RTP op Marketo-landingspagina's - Marketo Docs - Productdocumentatie
title: RTP implementeren op Marketo-landingspagina's
exl-id: fd19c3ad-d3f6-44a3-9f7a-d518e2d3f02a
feature: Web Personalization
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '194'
ht-degree: 0%

---

# RTP implementeren op Marketo-landingspagina&#39;s {#implementing-rtp-on-marketo-landing-pages}

Volg onderstaande installatie-instructies om uw RTP-tag te implementeren:

1. Ga naar de **Design Studio.** Open het item dat u wilt bewerken. Selecteren **Sjabloonhandelingen**, selecteert u **Concept bewerken**.

   ![](assets/image2015-4-26-18-3a27-3a4.png)

1. Wijzig de sjabloon in de **HTML-bron** tab.

   ![](assets/image2015-4-26-18-3a28-3a17.png)

1. Ga in uw RTP-account naar **Accountinstellingen**.

   a. Als u al een JavaScript-tag hebt ontvangen van Support, gaat u verder met stap 5.

   ![](assets/image2014-11-30-15-3a19-3a21-2.png)

1. Zoek onder Domein het relevante domein en klik op **Label genereren**.

   ![](assets/image2015-4-26-18-3a27-3a35.png)

   ![](assets/image2014-11-30-15-3a20-3a17-2.png)

1. Kopieer de RTP JavaScript-tag en plak deze naar alle sjablonen voor de bestemmingspagina tussen de **`<head> </head>`** -tags.

1. Klikken **Opslaan** en **Sluiten** het venster.

1. Terug in de **Design Studio**, keurt de landingspagina goed vanaf **Sjabloonhandelingen**, klikt u op **Goedkeuren**.

   ![](assets/image2015-4-26-18-3a28-3a30.png)

1. Tot slot moet u **opnieuw goedkeuren** landingspagina&#39;s die gebruikmaken van die sjabloon voor de wijzigingen van de sjabloon, worden van kracht. U kunt ze allemaal tegelijk opnieuw goedkeuren vanuit de hoofdsectie Landing Pages.

   ![](assets/image2015-4-26-18-3a28-3a49.png)

1. Controleer of het wordt weergegeven op alle pagina&#39;s, inclusief bestemmingspagina&#39;s en subdomeinen.

   U kunt dit doen door met de rechtermuisknop op de pagina van uw website te klikken. Ga naar **Pagina-bron weergeven.** Zoeken naar **RTP** om de tag te zoeken.
