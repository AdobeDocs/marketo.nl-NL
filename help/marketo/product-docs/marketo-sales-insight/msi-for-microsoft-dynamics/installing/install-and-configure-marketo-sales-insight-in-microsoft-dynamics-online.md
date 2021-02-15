---
unique-page-id: 37355602
description: Het Inzicht van de Verkoop van de Marketo in de Dynamica van Microsoft online installeren en vormen - Marketo Docs - de Documentatie van het Product
title: Het Inzicht van de Verkoop van de Marketo in de Dynamica van Microsoft online installeren en vormen
translation-type: tm+mt
source-git-commit: 6ae882dddda220f7067babbe5a057eec82601abf
workflow-type: tm+mt
source-wordcount: '496'
ht-degree: 0%

---


# Het Inzicht van de Verkoop van de Marketo in de Dynamica van Microsoft Online {#install-and-configure-marketo-sales-insight-in-microsoft-dynamics-online} installeren en vormen

Marketo Sales Insight is een fantastisch hulpmiddel om uw verkoopteam een &quot;venster&quot;in de rijkdom aan gegevens te geven het team van de Marketing heeft. Hier is hoe te om het in de Dynamica van Microsoft Online te installeren en te vormen.

>[!PREREQUISITES]
>
>Voltooi uw integratie van Marketo-Microsoft.
>
>[Download de correcte ](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/download-the-marketo-sales-insight-solution-for-microsoft-dynamics.md) oplossing voor uw versie van CRM van de Dynamica van Microsoft.

## Oplossing {#import-solution} importeren

>[!NOTE]
>
>Als u de Verenigde Interface, voorafgaand aan Stap 1 hieronder gebruikt, klik het pictogram van Montages in de hoger-juiste hoek en selecteer **Geavanceerde Montages**.

1. Klik onder Microsoft Dynamics CRM op **Settings**.

   ![](assets/image2014-12-12-9-3a4-3a56-1.png)

1. Klik onder Instellingen op **Aanpassingen**.

   ![](assets/image2015-4-29-14-3a22-3a1-1.png)

1. Klik **Oplossingen**.

   ![](assets/image2014-12-12-9-3a5-3a17-1.png)

   >[!NOTE]
   >
   >U zou reeds de oplossing van het Marketo geïnstalleerd en gevormd moeten hebben alvorens zich vooruit te bewegen.

1. Klik **Importeren**.

   ![](assets/image2014-12-12-9-3a5-3a27-1.png)

1. Klik in het nieuwe venster op **Bladeren**.

   ![](assets/image2014-12-12-9-3a5-3a36-1.png)

1. Zoek en installeer de zojuist gedownloade oplossing op uw computer.

1. Klik **Volgende**.

   ![](assets/seven.png)

1. De oplossing wordt geüpload. U kunt de inhoud van het pakket desgewenst weergeven. Klik **Volgende**.

   ![](assets/image2014-12-12-9-3a6-3a10-1.png)

1. Zorg ervoor dat het selectievakje ingeschakeld blijft en klik op **Importeren**.

   ![](assets/image2014-12-12-9-3a6-3a19-1.png)

1. Voel vrij om het logboekdossier te downloaden, dan klik **Close**.

   ![](assets/image2014-12-12-9-3a6-3a29-1.png)

1. Geweldig! U moet nu de oplossing zien. Als het er niet is, vernieuw uw scherm.

   ![](assets/eleven.png)

1. Klik **Aanpassing publiceren**.

   >[!NOTE]
   >
   >Zorg ervoor dat u de synchronisatie van Global MS Dynamics inschakelt.

## {#connect-marketo-and-sales-insight}

Laten we je Marketo-instantie aan Sales Insight in Dynamics koppelen. Hieronder wordt beschreven hoe:

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

1. Meld u aan bij Marketo en ga naar de sectie **Admin**.

   ![](assets/image2014-12-12-9-3a6-3a50-1.png)

1. Onder de sectie van het Inzicht van de Verkoop, klik **geef API Configuratie** uit.

   ![](assets/image2014-12-12-9-3a7-3a0-1.png)

1. Kopieer **Marketo Host**, **API URL**, en **API Gebruiker ID** voor gebruik in een recentere stap. Voer een API-beveiligingssleutel van uw keuze in en klik op **Opslaan**.

   >[!CAUTION]
   >
   >Gebruik geen en-teken (&amp;) in de geheime API-sleutel.

   ![](assets/image2014-12-12-9-3a7-3a9-1.png)

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

   ![](assets/image2014-12-12-9-3a7-3a25-1.png)

1. Klik onder **Instellingen** op **Marketo API Config**.

   ![](assets/image2014-12-12-9-3a7-3a34-1.png)

1. Klik **Nieuw**.

   ![](assets/image2014-12-12-9-3a8-3a8-1.png)

1. Voer de informatie in die u van Marketo eerder hebt ingevoerd en klik op **Opslaan**.

   ![](assets/image2014-12-12-9-3a8-3a17-1.png)

## Sync {#enable-sync} inschakelen

1. Klik in Marketo op **Admin**.

   ![](assets/enable-one.png)

1. Selecteer **Microsoft Dynamics** onder Integratie.

   ![](assets/enable-two.png)

1. Klik **Sync inschakelen**.

   ![](assets/enable-three.png)

1. Klik op **Bewerken** naast Veldsynchronisatiedetails.

   ![](assets/enable-four.png)

1. Dit zal _automatisch_ uitgezochte gebieden MSI die eerder onbruikbaar werden gemaakt (Urgentie, Relatieve Score, en Prioriteit). Klik **Opslaan** om te beginnen met het synchroniseren van gegevens.

   ![](assets/enable-five.png)

## Gebruikerstoegang {#set-user-access} instellen

Tot slot moet u specifieke gebruikers toegang geven om het Inzicht van de Verkoop van de Marketo te gebruiken.

1. Ga naar **Instellingen**.

   ![](assets/image2014-12-12-9-3a8-3a34-1.png)

1. Ga naar **Beveiliging**.

   ![](assets/image2015-4-29-14-3a56-3a33-1.png)

1. Klik **Users**.

   ![](assets/image2015-4-29-14-3a57-3a46-1.png)

1. Selecteer de gebruikers u toegang tot het Inzicht van de Verkoop aan wilt geven en **Manage Rollen** klikken.

   ![](assets/image2015-4-29-14-3a59-3a31-1.png)

1. Selecteer de rol van het Inzicht van de Verkoop van de Marketo en klik **OK**.

   ![](assets/image2014-12-12-9-3a9-3a22-1.png)

   En jullie moeten allemaal klaar zijn! Tot slot om te testen, login als gebruiker die toegang tot het Inzicht van de Verkoop van de Marketo heeft en bekijk een lood of een contact.

   ![](assets/image2015-4-29-15-3a2-3a27-1.png)

>[!MORELIKETHIS]
>
>[Sterren en vlammen instellen voor lead/contact-records](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/setting-up-stars-and-flames-for-lead-contact-records.md)
