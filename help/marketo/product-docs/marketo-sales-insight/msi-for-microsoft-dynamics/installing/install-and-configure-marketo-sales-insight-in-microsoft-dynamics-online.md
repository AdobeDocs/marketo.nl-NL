---
unique-page-id: 37355602
description: Marketo Sales Insight installeren en configureren in Microsoft Dynamics Online - Marketo Docs - Productdocumentatie
title: Marketo Sales Insight installeren en configureren in Microsoft Dynamics Online
exl-id: 3b58b109-96f9-427e-be5c-a8db270ffe69
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '496'
ht-degree: 0%

---

# Marketo Sales Insight installeren en configureren in Microsoft Dynamics Online {#install-and-configure-marketo-sales-insight-in-microsoft-dynamics-online}

Marketo Sales Insight is een fantastisch hulpmiddel om uw verkoopteam een &quot;venster&quot; te geven in de schat aan gegevens die het marketingteam heeft. Hieronder wordt beschreven hoe u het programma installeert en configureert in Microsoft Dynamics Online.

>[!PREREQUISITES]
>
>Voltooi uw integratie tussen Marketo en Microsoft.
>
>[Download de juiste oplossing](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/download-the-marketo-sales-insight-solution-for-microsoft-dynamics.md) voor uw versie van Microsoft Dynamics CRM.

## Oplossing importeren {#import-solution}

>[!NOTE]
>
>Als u de Verenigde Interface, voorafgaand aan Stap 1 hieronder gebruikt, klik het pictogram van Montages in de hoger-juiste hoek en selecteer **Geavanceerde instellingen**.

1. Klik onder Microsoft Dynamics CRM op **Instellingen**.

   ![](assets/image2014-12-12-9-3a4-3a56-1.png)

1. Klik onder Instellingen op **Aanpassingen**.

   ![](assets/image2015-4-29-14-3a22-3a1-1.png)

1. Klikken **Oplossingen**.

   ![](assets/image2014-12-12-9-3a5-3a17-1.png)

   >[!NOTE]
   >
   >U had de Marketo-oplossing al moeten installeren en configureren voordat u verdergaat.

1. Klikken **Importeren**.

   ![](assets/image2014-12-12-9-3a5-3a27-1.png)

1. Klik in het nieuwe venster op **Bladeren**.

   ![](assets/image2014-12-12-9-3a5-3a36-1.png)

1. Zoek en installeer de zojuist gedownloade oplossing op uw computer.

1. Klikken **Volgende**.

   ![](assets/seven.png)

1. De oplossing wordt geüpload. U kunt de inhoud van het pakket desgewenst weergeven. Klikken **Volgende**.

   ![](assets/image2014-12-12-9-3a6-3a10-1.png)

1. Laat het selectievakje ingeschakeld en klik op **Importeren**.

   ![](assets/image2014-12-12-9-3a6-3a19-1.png)

1. U kunt het logbestand gratis downloaden en klik vervolgens op **Sluiten**.

   ![](assets/image2014-12-12-9-3a6-3a29-1.png)

1. Geweldig! U moet nu de oplossing zien. Als het er niet is, vernieuw uw scherm.

   ![](assets/eleven.png)

1. Klikken **Aanpassing publiceren**.

   >[!NOTE]
   >
   >Zorg ervoor dat u de synchronisatie van Global MS Dynamics inschakelt.

## Connect Marketo en Sales Insight {#connect-marketo-and-sales-insight}

Laten we je Marketo-exemplaar koppelen aan Sales Insight in Dynamics. Hieronder wordt beschreven hoe:

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

1. Meld u aan bij Marketo en ga naar de **Beheer** sectie.

   ![](assets/image2014-12-12-9-3a6-3a50-1.png)

1. Klik onder het gedeelte Verkoopoverzicht op **API-configuratie bewerken**.

   ![](assets/image2014-12-12-9-3a7-3a0-1.png)

1. Kopieer de **Marketo-host**, **API-URL**, en **API-gebruikersnaam** voor gebruik in een latere stap. Voer een API-beveiligingssleutel naar keuze in en klik op **Opslaan**.

   >[!CAUTION]
   >
   >Gebruik geen en-teken (&amp;) in de geheime API-sleutel.

   ![](assets/image2014-12-12-9-3a7-3a9-1.png)

   >[!NOTE]
   >
   >De volgende velden moeten met Marketo worden gesynchroniseerd voor _Zowel lead als contact_ voor Sales Insight om te werken:
   >
   >* Prioriteit
   >* Urgentie
   >* Relatieve score

   >
   >Als een van deze velden ontbreekt, wordt in Marketo een foutbericht weergegeven met de naam van de ontbrekende velden. Om dit te verhelpen, voert u [deze procedure](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/required-fields-for-syncing-marketo-with-dynamics.md).

1. Terug in Microsoft Dynamics, ga naar **Instellingen**.

   ![](assets/image2014-12-12-9-3a7-3a25-1.png)

1. Onder **Instellingen**, klikt u op **Marketo API Config**.

   ![](assets/image2014-12-12-9-3a7-3a34-1.png)

1. Klikken **Nieuw**.

   ![](assets/image2014-12-12-9-3a8-3a8-1.png)

1. Voer de informatie in die je eerder van Marketo hebt ontvangen en klik op **Opslaan**.

   ![](assets/image2014-12-12-9-3a8-3a17-1.png)

## Sync inschakelen {#enable-sync}

1. Klik in Marketo op **Beheer**.

   ![](assets/enable-one.png)

1. Selecteer onder Integratie **Microsoft Dynamics**.

   ![](assets/enable-two.png)

1. Klikken **Sync inschakelen**.

   ![](assets/enable-three.png)

1. Klikken **Bewerken** naast Veldsynchronisatiedetails.

   ![](assets/enable-four.png)

1. Dit zal _automatisch_ Selecteer MSI-velden die eerder waren uitgeschakeld (Urgentie, Relatieve score en Prioriteit). Eenvoudig klikken **Opslaan** om de synchronisatie van gegevens te starten.

   ![](assets/enable-five.png)

## Gebruikerstoegang instellen {#set-user-access}

Tot slot moet u specifieke gebruikers toegang geven tot Marketo Sales Insight.

1. Ga naar **Instellingen**.

   ![](assets/image2014-12-12-9-3a8-3a34-1.png)

1. Ga naar **Beveiliging**.

   ![](assets/image2015-4-29-14-3a56-3a33-1.png)

1. Klikken **Gebruikers**.

   ![](assets/image2015-4-29-14-3a57-3a46-1.png)

1. Selecteer de gebruikers u toegang tot het Inzicht van de Verkoop wilt verlenen aan en klik **Rollen beheren**.

   ![](assets/image2015-4-29-14-3a59-3a31-1.png)

1. Selecteer de rol Marketo Sales Insight en klik op **OK**.

   ![](assets/image2014-12-12-9-3a9-3a22-1.png)

   En jullie moeten allemaal klaar zijn! Tot slot om te testen, login als gebruiker die toegang tot het Inzicht van de Verkoop van Marketo heeft en bekijk een lood of een contact.

   ![](assets/image2015-4-29-15-3a2-3a27-1.png)

>[!MORELIKETHIS]
>
>[Sterren en vlammen instellen voor lead/contact-records](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/setting-up-stars-and-flames-for-lead-contact-records.md)
