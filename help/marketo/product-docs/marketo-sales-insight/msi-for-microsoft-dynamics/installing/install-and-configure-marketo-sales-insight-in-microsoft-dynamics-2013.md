---
unique-page-id: 3571737
description: Installeer en vorm het Inzicht van de Verkoop van de Marketo in de Dynamica 2013 van Microsoft - Marketo Docs - de Documentatie van het Product
title: Het Inzicht van de Verkoop van de Marketo in de Dynamica 2013 van Microsoft installeren en vormen
translation-type: tm+mt
source-git-commit: 6ae882dddda220f7067babbe5a057eec82601abf
workflow-type: tm+mt
source-wordcount: '429'
ht-degree: 0%

---


# Het Inzicht van de Verkoop van de Marketo in de Dynamica 2013 van Microsoft installeren en vormen {#install-and-configure-marketo-sales-insight-in-microsoft-dynamics}

Marketo Sales Insight is een fantastisch hulpmiddel om uw verkoopteam een &quot;venster&quot; te geven in de schat aan gegevens die het marketingteam heeft. Hier is hoe te om het te installeren en te vormen.

>[!PREREQUISITES]
>
>Voltooi uw integratie van Marketo-Microsoft.
>
>[Download de correcte ](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/download-the-marketo-sales-insight-solution-for-microsoft-dynamics.md) oplossing voor uw versie van CRM van de Dynamica van Microsoft.

## Oplossing {#import-solution} importeren

OK, nu is het tijd om de oplossing van het Inzicht van de Verkoop van de Marketo in de Dynamiek van Microsoft in te voeren.

1. Klik onder **Microsoft Dynamics CRM** op **Settings**.

   ![](assets/image2014-12-12-9-3a4-3a56.png)

1. Klik onder **Instellingen** op **Aanpassingen**.

   ![](assets/image2014-12-12-9-3a5-3a6.png)

1. Klik **Oplossingen**.

   ![](assets/image2014-12-12-9-3a5-3a17.png)

   >[!NOTE]
   >
   >U had Marketo al geïnstalleerd en geconfigureerd moeten hebben voordat u verdergaat

1. Klik **Importeren**.

   ![](assets/image2014-12-12-9-3a5-3a27.png)

1. Klik in het nieuwe venster op **Bladeren**.

   ![](assets/image2014-12-12-9-3a5-3a36.png)

1. Zoek en selecteer de hierboven gedownloade oplossing.

   ![](assets/image2014-12-12-9-3a5-3a45.png)

1. Klik **Volgende**.

   ![](assets/image2014-12-12-9-3a5-3a55.png)

1. De oplossing wordt geüpload. U kunt de inhoud van het pakket desgewenst weergeven. Klik **Volgende**.

   ![](assets/image2014-12-12-9-3a6-3a10.png)

1. Zorg ervoor dat het selectievakje ingeschakeld blijft en klik op **Importeren**.

   ![](assets/image2014-12-12-9-3a6-3a19.png)

1. U kunt het logbestand vrij downloaden. Klik **Close**.

   ![](assets/image2014-12-12-9-3a6-3a29.png)

1. Geweldig! U moet nu de oplossing zien. Als het er niet is, vernieuw uw scherm.

   ![](assets/image2014-12-12-9-3a6-3a40.png)

## {#connect-marketo-and-sales-insight}

Laten we je Marketo-instantie aan Sales Insight in Dynamics koppelen.

>[!NOTE]
>
>Beheerdersrechten vereist.

1. Meld u aan bij Marketo en ga naar de sectie **Admin**.

   ![](assets/image2014-12-12-9-3a6-3a50.png)

1. Klik onder **Sales Insight** op **API-configuratie bewerken**.

   ![](assets/image2014-12-12-9-3a7-3a0.png)

1. Kopieer **Marketo Host**, **API URL**, en **API Gebruiker ID** voor gebruik in een recentere stap. Voer een **API-beveiligingssleutel** van uw keuze in en klik op **Opslaan**.

   >[!CAUTION]
   >
   >Gebruik geen en-teken (&amp;) in de geheime API-sleutel.

   ![](assets/image2014-12-12-9-3a7-3a9.png)

   >[!NOTE]
   >
   >De volgende gebieden moeten met Marketo voor _zowel Lood als Contact_ voor het Inzicht van de Verkoop worden gesynchroniseerd om te werken:
   >
   >* Prioriteit
   >* Urgentie
   >* Relatieve score

   >
   >Als een van deze velden ontbreekt, wordt in Marketo een foutbericht weergegeven met de naam van de ontbrekende velden. Om dit te bevestigen, voer [deze procedure](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/required-fields-for-syncing-marketo-with-dynamics.md) uit.

1. Terug in de Dynamiek van Microsoft, ga naar **Montages**.

   ![](assets/image2014-12-12-9-3a7-3a25.png)

1. Klik onder **Instellingen** op **Marketo API Config**.

   ![](assets/image2014-12-12-9-3a7-3a34.png)

1. Klik **Nieuw**.

   ![](assets/image2014-12-12-9-3a8-3a8.png)

1. Voer de informatie in die u van Marketo eerder hebt ingevoerd en klik op **Opslaan**.

   ![](assets/image2014-12-12-9-3a8-3a17.png)

## Gebruikerstoegang {#set-user-access} instellen

Tot slot kunt u specifieke gebruikers toegang tot het Inzicht van de Verkoop van de Marketo verlenen.

1. Ga naar **Instellingen**.

   ![](assets/image2014-12-12-9-3a8-3a34.png)

1. Klik **Users**.

   ![](assets/image2014-12-12-9-3a8-3a42.png)

1. Selecteer de gebruiker(s) u toegang tot het Inzicht van de Verkoop wilt geven aan en **Rollen beheren** klikken.

   ![](assets/image2014-12-12-9-3a9-3a13.png)

1. Selecteer de rol **Marketo Sales Insight** en klik **OK**.

   ![](assets/image2014-12-12-9-3a9-3a22.png)

   En jullie moeten allemaal klaar zijn! Tot slot om te testen, login aan Dynamica als gebruiker die toegang tot het Inzicht van de Verkoop van de Marketo heeft en bekijk een lood of een contact.

   ![](assets/image2014-12-12-9-3a9-3a31.png)

U hebt nu de macht van het Inzicht van de Verkoop van de Marketo voor uw verkoopteam ontgrendeld.

>[!MORELIKETHIS]
>
>[Sterren en vlammen instellen voor lead/contact-records](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/setting-up-stars-and-flames-for-lead-contact-records.md)
