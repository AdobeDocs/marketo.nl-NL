---
unique-page-id: 3571735
description: Installeer en vorm het Inzicht van de Verkoop van de Marketo in de Dynamica 2011 van Microsoft - Marketo Docs - de Documentatie van het Product
title: Het Inzicht van de Verkoop van de Marketo in de Dynamica 2011 van Microsoft installeren en vormen
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '412'
ht-degree: 0%

---


# Het Inzicht van de Verkoop van de Marketo in de Dynamica 2011 van Microsoft installeren en vormen {#install-and-configure-marketo-sales-insight-in-microsoft-dynamics}

Marketo Sales Insight is een fantastisch hulpmiddel voor uw verkoopteam. Hier is de geleidelijke instructie van hoe te om het in de Dynamica 2011 van Microsoft te installeren en te vormen On-Premises.

>[!PREREQUISITES]
>
>Voltooi uw integratie [van](http://docs.marketo.com/x/DoA2)Marketo-Microsoft.
>
>[Download de correcte oplossing](http://docs.marketo.com/x/LoJo) voor uw versie van CRM van de Dynamica van Microsoft.

## Oplossing importeren {#import-solution}

1. Meld u aan bij Microsoft Dynamics CRM. Klik op **Instellingen** linksonder in het menu.

   ![](assets/image2015-5-4-10-3a39-3a44.png)

1. Selecteer **Oplossingen** in de boom.

   ![](assets/image2015-5-4-10-3a41-3a56.png)

1. Klik op **Importeren** ( ![](assets/image2015-5-4-10-3a45-3a44.png)).

   ![](assets/image2015-5-4-10-3a42-3a38.png)

   >[!NOTE]
   >
   >**Herinnering**
   >
   >
   >U zou reeds de oplossing van de Marketo moeten [geïnstalleerd en gevormd](install-and-configure-marketo-sales-insight-in-microsoft-dynamics-2011.md) hebben alvorens zich vooruit te bewegen.

1. Klik op **Bladeren**. Selecteer de oplossing Marketo Sales Insight die u hebt [gedownload](download-the-marketo-sales-insight-solution-for-microsoft-dynamics.md). Klik op **Volgende**.

   ![](assets/image2015-5-4-10-3a55-3a15.png)

1. Controleer de details van de oplossing, en klik **daarna**.

   ![](assets/image2015-5-4-10-3a57-3a31.png)

1. Controleer of de optie voor het SDK-bericht is ingeschakeld. Klik op **Volgende**.

   ![](assets/image2015-5-4-11-3a43-3a37.png)

1. Wacht nu tot het importeren is voltooid.

   ![](assets/image2015-5-4-11-3a0-3a58.png)

1. Klik op **Sluiten**.

   ![](assets/crmhand.png)

1. Het Inzicht van de Verkoop van de Marketo zal nu in de oplossingslijst verschijnen. Yay!

   ![](assets/image2015-5-4-11-3a2-3a37.png)

1. Selecteer Marketo Sales Insight en klik op **Publish All Customizations** ( ![](assets/image2015-5-4-11-3a7-3a8.png)).

   ![](assets/image2015-5-4-11-3a8-3a27.png)

## Connect Marketo en Sales Insight  {#connect-marketo-and-sales-insight}

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

1. Meld u aan bij Marketo en klik op **Beheer**.

   ![](assets/image2014-12-12-9-3a6-3a50.png)

1. Klik onder de sectie **Sales Insight **op API-configuratie **** bewerken.

   ![](assets/image2014-12-12-9-3a7-3a0.png)

1. Kopieer de **Marketo-host**, de **API-URL** en de **API-gebruikersnaam** voor gebruik in een latere stap. Voer een **API-beveiligingssleutel** van uw keuze in en klik op **OPSLAAN**.

   >[!CAUTION]
   >
   >Gebruik geen en-teken (&amp;) in de geheime API-sleutel.

   ![](assets/image2015-5-4-11-3a16-3a3.png)

   >[!NOTE]
   >
   >De volgende velden moeten worden gesynchroniseerd met Marketo, zodat *zowel de Lead als de Contact* voor Verkoopinzicht kunnen werken:
   >
   >    
   >    
   >    * Prioriteit
   >    * Urgentie
   >    * Relatieve score

   >    
   >    
   >Als een van deze velden ontbreekt, wordt in Marketo een foutbericht weergegeven met de naam van de ontbrekende velden. Om dit te bevestigen, voer [deze procedure](../../../../product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/required-fields-for-syncing-marketo-with-dynamics.md)uit.

1. Ga terug naar Dynamiek, uitgezochte **Montages**.

   ![](assets/image2015-5-4-10-3a39-3a44.png)

1. Selecteer **Marketo API Config** in the tree.

   ![](assets/image2015-5-4-11-3a22-3a41.png)

1. Klik op **Standaardconfiguratie**.

   ![](assets/image2015-5-4-11-3a26-3a10.png)

1. Voer de gegevens in die u eerder van Marketo hebt ingevoerd.

   ![](assets/image2015-5-4-11-3a27-3a16.png)

1. Klik op **Opslaan.**

   ** ![](assets/image2015-5-4-11-3a28-3a13.png)

   **

## Gebruikerstoegang instellen {#set-user-access}

De gebruikersrollen van de opstelling om specifieke gebruikers toegang tot het Inzicht van de Verkoop te geven.

1. Selecteer **Instellingen**.

   ![](assets/image2015-5-4-11-3a30-3a54.png)

1. Selecteer **Beheer** in de boomstructuur.

   ![](assets/image2015-5-4-11-3a31-3a39.png)

1. Klik op **Gebruikers**.

   ![](assets/image2015-5-4-11-3a32-3a25.png)

1. Selecteer de gebruiker(s) aan wie u toegang wilt verlenen en klik op Rollen **** beheren.

   ![](assets/image2015-5-4-11-3a35-3a8.png)

1. Selecteer de rol **Marketo Sales Insight** en klik op **OK**.

   ![](assets/image2015-5-4-11-3a36-3a59.png)

   En dat is het! Alle gebruikers hebben toegang zal nu de sectie van het verkoopinzicht in de lood/contactdetailmening kunnen zien.

   ![](assets/image2015-5-4-11-3a39-3a23.png)

   Gefeliciteerd. Je hebt nu de kracht van Marketo Sales Insight vrijgemaakt.

>[!NOTE]
>
>**Verwante artikelen**
>
>[Sterren en vlammen instellen voor lead/contact-records](http://docs.marketo.com/x/BICMAg)

