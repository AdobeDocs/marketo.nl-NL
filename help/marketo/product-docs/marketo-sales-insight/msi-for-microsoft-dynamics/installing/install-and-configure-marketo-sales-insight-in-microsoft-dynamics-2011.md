---
unique-page-id: 3571735
description: Marketo Sales Insight installeren en configureren in Microsoft Dynamics 2011 - Marketo Docs - Productdocumentatie
title: Marketo Sales Insight installeren en configureren in Microsoft Dynamics 2011
exl-id: 40622dcc-7129-4392-95dc-ca829c15c3a6
feature: Marketo Sales Insights
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '331'
ht-degree: 2%

---

# Installeren en configureren [!DNL Marketo Sales Insight] in [!DNL Microsoft Dynamics 2011] {#install-and-configure-marketo-sales-insight-in-microsoft-dynamics}

[!DNL Marketo Sales Insight] is een fantastisch hulpmiddel voor uw verkoopteam. Hier volgt een stapsgewijze instructie over het installeren en configureren van de software in [!DNL Microsoft Dynamics 2011] Op locatie.

>[!PREREQUISITES]
>
>Voltooi uw integratie tussen Marketo en Microsoft.
>
>[ Download de correcte oplossing ](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/download-the-marketo-sales-insight-solution-for-microsoft-dynamics.md) voor uw versie van [!DNL Microsoft Dynamics] CRM.

## Oplossing importeren {#import-solution}

1. Log in bij [!DNL Microsoft Dynamics] CRM. Klik op **[!UICONTROL Settings]** in het menu linksonder.

   ![](assets/image2015-5-4-10-3a39-3a44.png)

1. Selecteer **[!UICONTROL Solutions]** in de structuur.

   ![](assets/image2015-5-4-10-3a41-3a56.png)

1. Klik **Invoer** ( ![](assets/image2015-5-4-10-3a45-3a44.png)).

   ![](assets/image2015-5-4-10-3a42-3a38.png)

   >[!NOTE]
   >
   >U zou reeds [ geïnstalleerd en gevormd moeten hebben ](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/install-and-configure-marketo-sales-insight-in-microsoft-dynamics-2011.md) de oplossing van Marketo alvorens zich vooruit te bewegen.

1. Klik op **[!UICONTROL Browse]**. Selecteer de [!DNL Marketo Sales Insight] oplossing u [ ](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/download-the-marketo-sales-insight-solution-for-microsoft-dynamics.md) downloadde. Klik op **[!UICONTROL Next]**.

   ![](assets/image2015-5-4-10-3a55-3a15.png)

1. Controleer de details van de oplossing en klik op **[!UICONTROL Next]** .

   ![](assets/image2015-5-4-10-3a57-3a31.png)

1. Controleer of de optie SDK-bericht is ingeschakeld. Klik op **[!UICONTROL Next]**.

   ![](assets/image2015-5-4-11-3a43-3a37.png)

1. Wacht nu tot het importeren is voltooid.

   ![](assets/image2015-5-4-11-3a0-3a58.png)

1. Klik op **[!UICONTROL Close]**.

   ![](assets/crmhand.png)

1. [!DNL Marketo Sales Insight] wordt nu weergegeven in de lijst met oplossingen. Yay!

   ![](assets/image2015-5-4-11-3a2-3a37.png)

1. Selecteer [!DNL Marketo Sales Insight] en klik op **publiceren Alle Aanpassingen** ( ![](assets/image2015-5-4-11-3a7-3a8.png)).

   ![](assets/image2015-5-4-11-3a8-3a27.png)

## Connect Marketo en Sales Insight  {#connect-marketo-and-sales-insight}

>[!NOTE]
>
>**Vereiste Bevoegdheden Admin**

1. Meld u aan bij Marketo en klik op **[!UICONTROL Admin]** .

   ![](assets/image2014-12-12-9-3a6-3a50.png)

1. Klik onder de sectie **[!UICONTROL Sales Insight]** op **[!UICONTROL Edit API Configuration]** .

   ![](assets/image2014-12-12-9-3a7-3a0.png)

1. Kopieer **[!UICONTROL Marketo Host]** , **[!UICONTROL API URL]** en **[!UICONTROL API User Id]** voor gebruik in een latere stap. Voer een **[!UICONTROL API Secret Key]** van uw keuze in en klik op **[!UICONTROL Save]** .

   >[!CAUTION]
   >
   >Gebruik geen en-teken (&amp;) in de geheime API-sleutel.

   ![](assets/image2015-5-4-11-3a16-3a3.png)

   >[!NOTE]
   >
   >De volgende gebieden moeten met Marketo voor _zowel Lood als Contact_ voor Verkoop Insight worden gesynchroniseerd om te werken:
   >
   >* Prioriteit
   >* Urgentie
   >* Relatieve score
   >
   >Als een van deze velden ontbreekt, wordt in Marketo een foutbericht weergegeven met de naam van de ontbrekende velden. Om dit te bevestigen, voer [ deze procedure ](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/required-fields-for-syncing-marketo-with-dynamics.md) uit.

1. Ga terug naar Dynamiek, selecteer **[!UICONTROL Settings]**.

   ![](assets/image2015-5-4-10-3a39-3a44.png)

1. Selecteer **[!UICONTROL Marketo API Config]** in de structuur.

   ![](assets/image2015-5-4-11-3a22-3a41.png)

1. Klik op **[!UICONTROL Default Configuration]**.

   ![](assets/image2015-5-4-11-3a26-3a10.png)

1. Voer de gegevens in die je eerder van Marketo hebt ontvangen.

   ![](assets/image2015-5-4-11-3a27-3a16.png)

1. Klik op **[!UICONTROL Save]**.

   ![](assets/image2015-5-4-11-3a28-3a13.png)

## Gebruikerstoegang instellen {#set-user-access}

Stel gebruikersrollen in om specifieke gebruikers toegang te geven tot [!DNL Sales Insight] .

1. Selecteer **[!UICONTROL Settings]** .

   ![](assets/image2015-5-4-11-3a30-3a54.png)

1. Selecteer **[!UICONTROL Administration]** in de structuur.

   ![](assets/image2015-5-4-11-3a31-3a39.png)

1. Klik op **[!UICONTROL Users]**.

   ![](assets/image2015-5-4-11-3a32-3a25.png)

1. Selecteer de gebruiker(s) aan wie u toegang wilt verlenen en klik op **[!UICONTROL Manage Roles]** .

   ![](assets/image2015-5-4-11-3a35-3a8.png)

1. Selecteer de **[!UICONTROL Marketo Sales Insight]** rol en klik op **[!UICONTROL OK]** .

   ![](assets/image2015-5-4-11-3a36-3a59.png)

   En dat is het! Alle gebruikers hebben nu toegang tot de sectie Sales insight in de detailweergave voor leads/contactpersonen.

   ![](assets/image2015-5-4-11-3a39-3a23.png)

   Gefeliciteerd. U hebt nu de kracht van [!DNL Marketo Sales Insight] ontketend.

>[!MORELIKETHIS]
>
>[ de Sterren en Flames van de Opstelling voor Lood/de Verslagen van het Contact ](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/setting-up-stars-and-flames-for-lead-contact-records.md)
