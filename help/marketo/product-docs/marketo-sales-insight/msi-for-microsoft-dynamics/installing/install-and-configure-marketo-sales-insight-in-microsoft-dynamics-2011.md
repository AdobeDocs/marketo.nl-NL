---
unique-page-id: 3571735
description: Installeer en vorm het Inzicht van de Verkoop van de Marketo in de Dynamica 2011 van Microsoft - Marketo Docs - de Documentatie van het Product
title: Het Inzicht van de Verkoop van de Marketo in de Dynamica 2011 van Microsoft installeren en vormen
translation-type: tm+mt
source-git-commit: 6ae882dddda220f7067babbe5a057eec82601abf
workflow-type: tm+mt
source-wordcount: '397'
ht-degree: 0%

---


# Het Inzicht van de Verkoop van de Marketo in de Dynamica 2011 van Microsoft installeren en vormen {#install-and-configure-marketo-sales-insight-in-microsoft-dynamics}

Marketo Sales Insight is een fantastisch hulpmiddel voor uw verkoopteam. Hier is de geleidelijke instructie van hoe te om het in de Dynamica 2011 van Microsoft te installeren en te vormen On-Premises.

>[!PREREQUISITES]
>
>Voltooi uw integratie van Marketo-Microsoft.
>
>[Download de correcte ](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/download-the-marketo-sales-insight-solution-for-microsoft-dynamics.md) oplossing voor uw versie van CRM van de Dynamica van Microsoft.

## Oplossing {#import-solution} importeren

1. Meld u aan bij Microsoft Dynamics CRM. Klik op **Instellingen** linksonder in het menu.

   ![](assets/image2015-5-4-10-3a39-3a44.png)

1. Selecteer **Oplossingen** in de boom.

   ![](assets/image2015-5-4-10-3a41-3a56.png)

1. Klik **Importeren** ( ![](assets/image2015-5-4-10-3a45-3a44.png)).

   ![](assets/image2015-5-4-10-3a42-3a38.png)

   >[!NOTE]
   >
   >U zou [reeds moeten hebben geïnstalleerd en gevormd ](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/install-and-configure-marketo-sales-insight-in-microsoft-dynamics-2011.md) de oplossing van het Marketo alvorens zich vooruit te bewegen.

1. Klik **Bladeren**. Selecteer de oplossing van het Inzicht van de Verkoop van de Marketo u [downloadde](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/download-the-marketo-sales-insight-solution-for-microsoft-dynamics.md). Klik **Volgende**.

   ![](assets/image2015-5-4-10-3a55-3a15.png)

1. Verifieer de details van de oplossing, en klik **Next**.

   ![](assets/image2015-5-4-10-3a57-3a31.png)

1. Controleer of de optie voor het SDK-bericht is ingeschakeld. Klik **Volgende**.

   ![](assets/image2015-5-4-11-3a43-3a37.png)

1. Wacht nu tot het importeren is voltooid.

   ![](assets/image2015-5-4-11-3a0-3a58.png)

1. Klik **Close**.

   ![](assets/crmhand.png)

1. Het Inzicht van de Verkoop van de Marketo zal nu in de oplossingslijst verschijnen. Yay!

   ![](assets/image2015-5-4-11-3a2-3a37.png)

1. Selecteer Marktverkoop Inzicht en klik op **Alle aanpassingen publiceren** ( ![](assets/image2015-5-4-11-3a7-3a8.png)).

   ![](assets/image2015-5-4-11-3a8-3a27.png)

## {#connect-marketo-and-sales-insight}

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

1. Meld u aan bij Marketo en klik op **Admin**.

   ![](assets/image2014-12-12-9-3a6-3a50.png)

1. Klik onder **Sales Insight** op **API-configuratie bewerken**.

   ![](assets/image2014-12-12-9-3a7-3a0.png)

1. Kopieer **Marketo Host**, **API URL**, en **API Gebruiker ID** voor gebruik in een recentere stap. Voer een **API-beveiligingssleutel** van uw keuze in en klik op **Opslaan**.

   >[!CAUTION]
   >
   >Gebruik geen en-teken (&amp;) in de geheime API-sleutel.

   ![](assets/image2015-5-4-11-3a16-3a3.png)

   >[!NOTE]
   >
   >De volgende gebieden moeten met Marketo voor _zowel Lood als Contact_ voor het Inzicht van de Verkoop worden gesynchroniseerd om te werken:
   >
   >* Prioriteit
   >* Urgentie
   >* Relatieve score

   >
   >Als een van deze velden ontbreekt, wordt in Marketo een foutbericht weergegeven met de naam van de ontbrekende velden. Om dit te bevestigen, voer [deze procedure](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/required-fields-for-syncing-marketo-with-dynamics.md) uit.

1. Ga terug naar Dynamiek, uitgezochte **Montages**.

   ![](assets/image2015-5-4-10-3a39-3a44.png)

1. Selecteer **Marketo API Config** in de boomstructuur.

   ![](assets/image2015-5-4-11-3a22-3a41.png)

1. Klik **Standaardconfiguratie**.

   ![](assets/image2015-5-4-11-3a26-3a10.png)

1. Voer de gegevens in die u eerder van Marketo hebt ingevoerd.

   ![](assets/image2015-5-4-11-3a27-3a16.png)

1. Klik **Opslaan**.

   ![](assets/image2015-5-4-11-3a28-3a13.png)

## Gebruikerstoegang {#set-user-access} instellen

De gebruikersrollen van de opstelling om specifieke gebruikers toegang tot het Inzicht van de Verkoop te geven.

1. Selecteer **Instellingen**.

   ![](assets/image2015-5-4-11-3a30-3a54.png)

1. Selecteer **Beheer** in de boom.

   ![](assets/image2015-5-4-11-3a31-3a39.png)

1. Klik **Users**.

   ![](assets/image2015-5-4-11-3a32-3a25.png)

1. Selecteer de gebruiker(s) aan wie u toegang wilt verlenen en klik **Rollen beheren**.

   ![](assets/image2015-5-4-11-3a35-3a8.png)

1. Selecteer de rol **Marketo Sales Insight** en klik **OK**.

   ![](assets/image2015-5-4-11-3a36-3a59.png)

   En dat is het! Alle gebruikers hebben toegang zal nu de sectie van het verkoopinzicht in de lood/contactdetailmening kunnen zien.

   ![](assets/image2015-5-4-11-3a39-3a23.png)

   Gefeliciteerd. Je hebt nu de kracht van Marketo Sales Insight vrijgemaakt.

>[!MORELIKETHIS]
>
>[Sterren en vlammen instellen voor lead/contact-records](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/setting-up-stars-and-flames-for-lead-contact-records.md)
