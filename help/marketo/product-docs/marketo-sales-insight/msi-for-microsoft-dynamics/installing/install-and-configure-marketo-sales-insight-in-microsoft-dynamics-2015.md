---
unique-page-id: 7513865
description: Marketo Sales Insight installeren en configureren in Microsoft Dynamics 2015 - Marketo Docs - Productdocumentatie
title: Marketo Sales Insight installeren en configureren in Microsoft Dynamics 2015
exl-id: 26c1f02c-c910-445d-8560-0b37961eadcb
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '442'
ht-degree: 0%

---

# Marketo Sales Insight installeren en configureren in Microsoft Dynamics 2015 {#install-and-configure-marketo-sales-insight-in-microsoft-dynamics}

Marketo Sales Insight is een fantastisch hulpmiddel om uw verkoopteam een &quot;venster&quot; te geven in de schat aan gegevens die het marketingteam heeft. Hieronder wordt beschreven hoe u het programma installeert en configureert in Microsoft Dynamics 2011.

>[!PREREQUISITES]
>
>Voltooi uw integratie tussen Marketo en Microsoft.
>
>[Download de juiste oplossing](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/download-the-marketo-sales-insight-solution-for-microsoft-dynamics.md) voor uw versie van Microsoft Dynamics CRM.

## Oplossing importeren {#import-solution}

Nu is het tijd om de Marketo Sales Insight-oplossing te importeren in Microsoft Dynamics. Hieronder wordt beschreven hoe:

1. Klik onder Microsoft Dynamics CRM op **Instellingen**.

   ![](assets/image2014-12-12-9-3a4-3a56.png)

1. Klik onder INSTELLINGEN op **Aanpassingen**.

   ![](assets/image2015-4-29-14-3a22-3a1.png)

1. Klikken **Oplossingen**.

   ![](assets/image2014-12-12-9-3a5-3a17.png)

   >[!NOTE]
   >
   >U had de Marketo-oplossing al moeten installeren en configureren voordat u verdergaat.

1. Klikken **Importeren**.

   ![](assets/image2014-12-12-9-3a5-3a27.png)

1. Klik in het nieuwe venster op **Bladeren**.

   ![](assets/image2014-12-12-9-3a5-3a36.png)

1. Zoek en selecteer de hierboven gedownloade oplossing.

   ![](assets/image2014-12-12-9-3a5-3a45.png)

1. Klikken **Volgende**.

   ![](assets/image2014-12-12-9-3a5-3a55.png)

1. De oplossing wordt geüpload. U kunt de inhoud van het pakket desgewenst weergeven. Klikken **Volgende**.

   ![](assets/image2014-12-12-9-3a6-3a10.png)

1. Laat het selectievakje ingeschakeld en klik op **Importeren**.

   ![](assets/image2014-12-12-9-3a6-3a19.png)

1. U kunt het logbestand gratis downloaden en klik vervolgens op **Sluiten**.

   ![](assets/image2014-12-12-9-3a6-3a29.png)

1. Geweldig! U moet nu de oplossing zien. Als het er niet is, vernieuw uw scherm.

   ![](assets/image2014-12-12-9-3a6-3a40.png)

## Connect Marketo en Sales Insight {#connect-marketo-and-sales-insight}

Laten we je Marketo-exemplaar koppelen aan Sales Insight in Dynamics. Hieronder wordt beschreven hoe:

>[!NOTE]
>
>Beheerdersrechten vereist.

1. Meld u aan bij Marketo en ga naar de **Beheer** sectie.

   ![](assets/image2014-12-12-9-3a6-3a50.png)

1. Klik onder het gedeelte Verkoopoverzicht op **API-configuratie bewerken**.

   ![](assets/image2014-12-12-9-3a7-3a0.png)

1. Kopieer de **Marketo-host**, **API-URL**, en **API-gebruikersnaam** voor gebruik in een latere stap. Voer een API-beveiligingssleutel naar keuze in en klik op **Opslaan**.

   >[!CAUTION]
   >
   >Gebruik geen en-teken (&amp;) in de geheime API-sleutel.

   ![](assets/image2014-12-12-9-3a7-3a9.png)

   >[!NOTE]
   >
   >De volgende velden moeten met Marketo worden gesynchroniseerd voor *Zowel lead als contact* voor Sales Insight om te werken:
   >
   >* Prioriteit
   >* Urgentie
   >* Relatieve score

   >
   >Als een van deze velden ontbreekt, wordt in Marketo een foutbericht weergegeven met de naam van de ontbrekende velden. Om dit te verhelpen, voert u [deze procedure](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/required-fields-for-syncing-marketo-with-dynamics.md).

1. Terug in Microsoft Dynamics, ga naar **Instellingen**.

   ![](assets/image2014-12-12-9-3a7-3a25.png)

1. Onder **Instellingen**, klikt u op **Marketo API Config**.

   ![](assets/image2014-12-12-9-3a7-3a34.png)

1. Klikken **Nieuw**.

   ![](assets/image2014-12-12-9-3a8-3a8.png)

1. Voer de informatie in die je eerder van Marketo hebt ontvangen en klik op **Opslaan**.

   ![](assets/image2014-12-12-9-3a8-3a17.png)

## Gebruikerstoegang instellen {#set-user-access}

Tot slot moet u specifieke gebruikers toegang geven tot Marketo Sales Insight.

1. Ga naar **Instellingen**.

   ![](assets/image2014-12-12-9-3a8-3a34.png)

1. Ga naar **Beveiliging**.

   ![](assets/image2015-4-29-14-3a56-3a33.png)

1. Klikken **Gebruikers**.

   ![](assets/image2015-4-29-14-3a57-3a46.png)

1. Selecteer de gebruikers u toegang tot het Inzicht van de Verkoop wilt verlenen aan en klik **Rollen beheren**.

   ![](assets/image2015-4-29-14-3a59-3a31.png)

1. Selecteer de rol Marketo Sales Insight en klik op **OK**.

   ![](assets/image2014-12-12-9-3a9-3a22.png)

   En jullie moeten allemaal klaar zijn! Tot slot om te testen, login als gebruiker die toegang tot het Inzicht van de Verkoop van Marketo heeft en bekijk een lood of een contact.

   ![](assets/image2015-4-29-15-3a2-3a27.png)

Je hebt nu de kracht van Marketo Sales Insight voor je verkoopteam ontgrendeld.

>[!MORELIKETHIS]
>
>[Sterren en vlammen instellen voor lead/contact-records](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/setting-up-stars-and-flames-for-lead-contact-records.md)
