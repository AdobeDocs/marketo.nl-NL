---
unique-page-id: 3571735
description: Marketo Sales Insight installeren en configureren in Microsoft Dynamics 2011 - Marketo Docs - Productdocumentatie
title: Marketo Sales Insight installeren en configureren in Microsoft Dynamics 2011
exl-id: 40622dcc-7129-4392-95dc-ca829c15c3a6
source-git-commit: fda1bf51d4016a61c41be9acba4771db1797a552
workflow-type: tm+mt
source-wordcount: '397'
ht-degree: 0%

---

# Marketo Sales Insight installeren en configureren in Microsoft Dynamics 2011 {#install-and-configure-marketo-sales-insight-in-microsoft-dynamics}

Marketo Sales Insight is een fantastisch hulpmiddel voor je verkoopteam. Hier volgt de stapsgewijze instructies voor het installeren en configureren van de software in Microsoft Dynamics 2011 On-Premises.

>[!PREREQUISITES]
>
>Voltooi uw integratie tussen Marketo en Microsoft.
>
>[Download de juiste oplossing](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/download-the-marketo-sales-insight-solution-for-microsoft-dynamics.md) voor uw versie van Microsoft Dynamics CRM.

## Oplossing importeren {#import-solution}

1. Meld u aan bij Microsoft Dynamics CRM. Klikken **Instellingen** in het menu linksonder.

   ![](assets/image2015-5-4-10-3a39-3a44.png)

1. Selecteren **Oplossingen** in de boom.

   ![](assets/image2015-5-4-10-3a41-3a56.png)

1. Klikken **Importeren** ( ![](assets/image2015-5-4-10-3a45-3a44.png)).

   ![](assets/image2015-5-4-10-3a42-3a38.png)

   >[!NOTE]
   >
   >U moet al [geïnstalleerd en geconfigureerd](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/install-and-configure-marketo-sales-insight-in-microsoft-dynamics-2011.md) de Marketo-oplossing voordat er vooruitgang wordt geboekt.

1. Klikken **Bladeren**. Selecteer de Marketo Sales Insight-oplossing [gedownload](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/download-the-marketo-sales-insight-solution-for-microsoft-dynamics.md). Klikken **Volgende**.

   ![](assets/image2015-5-4-10-3a55-3a15.png)

1. Controleer de details van de oplossing en klik op **Volgende**.

   ![](assets/image2015-5-4-10-3a57-3a31.png)

1. Controleer of de optie voor het SDK-bericht is ingeschakeld. Klikken **Volgende**.

   ![](assets/image2015-5-4-11-3a43-3a37.png)

1. Wacht nu tot het importeren is voltooid.

   ![](assets/image2015-5-4-11-3a0-3a58.png)

1. Klikken **Sluiten**.

   ![](assets/crmhand.png)

1. Marketo Sales Insight wordt nu weergegeven in de lijst met oplossingen. Yay!

   ![](assets/image2015-5-4-11-3a2-3a37.png)

1. Selecteer Marketo Sales Insight en klik op **Alle aanpassingen publiceren** ( ![](assets/image2015-5-4-11-3a7-3a8.png)).

   ![](assets/image2015-5-4-11-3a8-3a27.png)

## Connect Marketo en Sales Insight  {#connect-marketo-and-sales-insight}

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

1. Meld u aan bij Marketo en klik op **Beheer**.

   ![](assets/image2014-12-12-9-3a6-3a50.png)

1. Onder de **Verkoopoverzicht** sectieklik **API-configuratie bewerken**.

   ![](assets/image2014-12-12-9-3a7-3a0.png)

1. Kopieer de **Marketo-host**, **API-URL**, en **API-gebruikersnaam** voor gebruik in een latere stap. Voer een **API-beveiligingssleutel** van uw keuze en klik op **Opslaan**.

   >[!CAUTION]
   >
   >Gebruik geen en-teken (&amp;) in de geheime API-sleutel.

   ![](assets/image2015-5-4-11-3a16-3a3.png)

   >[!NOTE]
   >
   >De volgende velden moeten met Marketo worden gesynchroniseerd voor _Zowel lead als contact_ voor Sales Insight om te werken:
   >
   >* Prioriteit
   >* Urgentie
   >* Relatieve score

   >
   >Als een van deze velden ontbreekt, wordt in Marketo een foutbericht weergegeven met de naam van de ontbrekende velden. Om dit te verhelpen, voert u [deze procedure](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/required-fields-for-syncing-marketo-with-dynamics.md).

1. Ga terug naar Dynamiek, selecteer **Instellingen**.

   ![](assets/image2015-5-4-10-3a39-3a44.png)

1. Selecteren **Marketo API Config** in de boom.

   ![](assets/image2015-5-4-11-3a22-3a41.png)

1. Klikken **Standaardconfiguratie**.

   ![](assets/image2015-5-4-11-3a26-3a10.png)

1. Voer de gegevens in die je eerder van Marketo hebt ontvangen.

   ![](assets/image2015-5-4-11-3a27-3a16.png)

1. Klikken **Opslaan**.

   ![](assets/image2015-5-4-11-3a28-3a13.png)

## Gebruikerstoegang instellen {#set-user-access}

De gebruikersrollen van de opstelling om specifieke gebruikers toegang tot het Inzicht van de Verkoop te geven.

1. Selecteren **Instellingen**.

   ![](assets/image2015-5-4-11-3a30-3a54.png)

1. Selecteren **Beheer** in de boom.

   ![](assets/image2015-5-4-11-3a31-3a39.png)

1. Klikken **Gebruikers**.

   ![](assets/image2015-5-4-11-3a32-3a25.png)

1. Selecteer de gebruiker(s) aan wie u toegang wilt verlenen en klik op **Rollen beheren**.

   ![](assets/image2015-5-4-11-3a35-3a8.png)

1. Selecteer **Marketo Sales Insight** rol en klik **OK**.

   ![](assets/image2015-5-4-11-3a36-3a59.png)

   En dat is het! Alle gebruikers hebben toegang zal nu de sectie van het verkoopinzicht in de lood/contactdetailmening kunnen zien.

   ![](assets/image2015-5-4-11-3a39-3a23.png)

   Gefeliciteerd. Je hebt nu de kracht van Marketo Sales Insight vrijgemaakt.

>[!MORELIKETHIS]
>
>[Sterren en vlammen instellen voor lead/contact-records](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/setting-up-stars-and-flames-for-lead-contact-records.md)
