---
unique-page-id: 3571737
description: Marketo Sales Insight installeren en configureren in Microsoft Dynamics 2013 - Marketo Docs - Productdocumentatie
title: Marketo Sales Insight installeren en configureren in Microsoft Dynamics 2013
exl-id: 290db451-47a6-4cfa-a36f-bc12ef7d3482
feature: Marketo Sales Insights
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '356'
ht-degree: 2%

---

# Installeren en configureren [!DNL Marketo Sales Insight] in [!DNL Microsoft Dynamics 2013] {#install-and-configure-marketo-sales-insight-in-microsoft-dynamics}

[!DNL Marketo Sales Insight] is een fantastisch hulpmiddel om uw verkoopteam een &quot;venster&quot;in de rijkdom van gegevens te geven het marketing team heeft. Hier is hoe te om het te installeren en te vormen.

>[!PREREQUISITES]
>
>Voltooi uw integratie tussen Marketo en Microsoft.
>
>[&#x200B; Download de correcte oplossing &#x200B;](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/download-the-marketo-sales-insight-solution-for-microsoft-dynamics.md) voor uw versie van [!DNL Microsoft Dynamics] CRM.

## Oplossing importeren {#import-solution}

Nu is het tijd om de [!DNL Marketo Sales Insight] -oplossing te importeren in [!DNL Microsoft Dynamics] .

1. Klik onder **[!UICONTROL Microsoft Dynamics CRM]** op **[!UICONTROL Settings]** .

   ![](assets/image2014-12-12-9-3a4-3a56.png)

1. Klik onder **[!UICONTROL Settings]** op **[!UICONTROL Customizations]** .

   ![](assets/image2014-12-12-9-3a5-3a6.png)

1. Klik op **[!UICONTROL Solutions]**.

   ![](assets/image2014-12-12-9-3a5-3a17.png)

   >[!NOTE]
   >
   >U had Marketo al geïnstalleerd en geconfigureerd moeten hebben voordat u verdergaat

1. Klik op **[!UICONTROL Import]**.

   ![](assets/image2014-12-12-9-3a5-3a27.png)

1. Klik in het nieuwe venster op **[!UICONTROL Browse]** .

   ![](assets/image2014-12-12-9-3a5-3a36.png)

1. Zoek en selecteer de hierboven gedownloade oplossing.

   ![](assets/image2014-12-12-9-3a5-3a45.png)

1. Klik op **[!UICONTROL Next]**.

   ![](assets/image2014-12-12-9-3a5-3a55.png)

1. De oplossing zal uploaden. U kunt de inhoud van het pakket desgewenst weergeven. Klik op **[!UICONTROL Next]**.

   ![](assets/image2014-12-12-9-3a6-3a10.png)

1. Zorg dat het selectievakje ingeschakeld blijft en klik op **[!UICONTROL Import]** .

   ![](assets/image2014-12-12-9-3a6-3a19.png)

1. U kunt het logbestand vrij downloaden. Klik op **[!UICONTROL Close]**.

   ![](assets/image2014-12-12-9-3a6-3a29.png)

1. Geweldig! U moet nu de oplossing zien. Als het er niet is, vernieuw uw scherm.

   ![](assets/image2014-12-12-9-3a6-3a40.png)

## Connect Marketo en Sales Insight {#connect-marketo-and-sales-insight}

Laten we uw Marketo-instantie koppelen aan [!DNL Sales Insight] in [!DNL Dynamics] .

>[!NOTE]
>
>Beheerdersrechten vereist.

1. Meld u aan bij Marketo en ga naar de sectie **[!UICONTROL Admin]** .

   ![](assets/image2014-12-12-9-3a6-3a50.png)

1. Klik onder de sectie **[!UICONTROL Sales Insight]** op **[!UICONTROL Edit API Configuration]** .

   ![](assets/image2014-12-12-9-3a7-3a0.png)

1. Kopieer **[!UICONTROL Marketo Host]** , **[!UICONTROL API URL]** en **[!UICONTROL API User Id]** voor gebruik in een latere stap. Voer een **[!UICONTROL API Secret Key]** van uw keuze in en klik op **[!UICONTROL Save]** .

   >[!CAUTION]
   >
   >Gebruik geen en-teken (&amp;) in de geheime API-sleutel.

   ![](assets/image2014-12-12-9-3a7-3a9.png)

   >[!NOTE]
   >
   >De volgende gebieden moeten met Marketo voor _zowel Lood als Contact_ voor Verkoop Insight worden gesynchroniseerd om te werken:
   >
   >* Prioriteit
   >* Urgentie
   >* Relatieve score
   >
   >Als een van deze velden ontbreekt, wordt in Marketo een foutbericht weergegeven met de naam van de ontbrekende velden. Om dit te bevestigen, voer [&#x200B; deze procedure &#x200B;](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/required-fields-for-syncing-marketo-with-dynamics.md) uit.

1. Ga terug in [!DNL Microsoft Dynamics] en ga naar **[!UICONTROL Settings]** .

   ![](assets/image2014-12-12-9-3a7-3a25.png)

1. Klik onder **[!UICONTROL Settings]** op **[!UICONTROL Marketo API Config]** .

   ![](assets/image2014-12-12-9-3a7-3a34.png)

1. Klik op **[!UICONTROL New]**.

   ![](assets/image2014-12-12-9-3a8-3a8.png)

1. Voer de informatie in die u eerder van Marketo hebt ontvangen en klik op **[!UICONTROL Save]** .

   ![](assets/image2014-12-12-9-3a8-3a17.png)

## Gebruikerstoegang instellen {#set-user-access}

Tot slot kunt u specifieke gebruikers toegang geven tot [!DNL Marketo Sales Insight] .

1. Ga naar **[!UICONTROL Settings]** .

   ![](assets/image2014-12-12-9-3a8-3a34.png)

1. Klik op **[!UICONTROL Users]**.

   ![](assets/image2014-12-12-9-3a8-3a42.png)

1. Selecteer de gebruiker(s) die je toegang wilt geven tot Sales Insight en klik op **[!UICONTROL Manage Roles]** .

   ![](assets/image2014-12-12-9-3a9-3a13.png)

1. Selecteer de **[!UICONTROL Marketo Sales Insight]** rol en klik op **[!UICONTROL OK]** .

   ![](assets/image2014-12-12-9-3a9-3a22.png)

   En jullie moeten allemaal klaar zijn! Als laatste test, meldt u zich aan bij [!DNL Dynamics] als een gebruiker die toegang heeft tot [!DNL Marketo Sales Insight] en bekijkt u een lead of contactpersoon.

   ![](assets/image2014-12-12-9-3a9-3a31.png)

U hebt nu de kracht van [!DNL Marketo Sales Insight] voor uw verkoopteam ontgrendeld.

>[!MORELIKETHIS]
>
>[&#x200B; de Sterren en Flames van de Opstelling voor Lood/de Verslagen van het Contact &#x200B;](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/setting-up-stars-and-flames-for-lead-contact-records.md)
