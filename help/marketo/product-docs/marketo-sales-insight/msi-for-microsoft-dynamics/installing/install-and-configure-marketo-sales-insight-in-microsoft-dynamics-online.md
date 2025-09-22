---
unique-page-id: 37355602
description: Marketo Sales Insight installeren en configureren in Microsoft Dynamics Online - Marketo Docs - Productdocumentatie
title: Marketo Sales Insight online installeren en configureren
exl-id: 3b58b109-96f9-427e-be5c-a8db270ffe69
feature: Marketo Sales Insights
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '405'
ht-degree: 2%

---

# Installeren en configureren [!DNL Marketo Sales Insight] in [!DNL Microsoft Dynamics Online] {#install-and-configure-marketo-sales-insight-in-microsoft-dynamics-online}

[!DNL Marketo Sales Insight] is een fantastisch hulpmiddel om uw verkoopteam een &quot;venster&quot;in de rijkdom van gegevens te geven het team van de Marketing heeft. Hieronder wordt beschreven hoe u de toepassing installeert en configureert in [!DNL Microsoft Dynamics Online] .

>[!PREREQUISITES]
>
>Voltooi uw integratie tussen Marketo en Microsoft.
>
>[ Download de correcte oplossing ](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/download-the-marketo-sales-insight-solution-for-microsoft-dynamics.md) voor uw versie van [!DNL Microsoft Dynamics CRM].

## Oplossing importeren {#import-solution}

>[!NOTE]
>
>Als u de Verenigde Interface, voorafgaand aan Stap 1 hieronder gebruikt, klik het pictogram van Montages in de hoger-juiste hoek en selecteer **[!UICONTROL Advanced Settings]**.

1. Klik onder Microsoft Dynamics CRM op **[!UICONTROL Settings]** .

   ![](assets/image2014-12-12-9-3a4-3a56-1.png)

1. Klik onder Instellingen op **[!UICONTROL Customizations]** .

   ![](assets/image2015-4-29-14-3a22-3a1-1.png)

1. Klik op **[!UICONTROL Solutions]**.

   ![](assets/image2014-12-12-9-3a5-3a17-1.png)

   >[!NOTE]
   >
   >U had de Marketo-oplossing al moeten installeren en configureren voordat u verdergaat.

1. Klik op **[!UICONTROL Import]**.

   ![](assets/image2014-12-12-9-3a5-3a27-1.png)

1. Klik in het nieuwe venster op **[!UICONTROL Browse]** .

   ![](assets/image2014-12-12-9-3a5-3a36-1.png)

1. Zoek en installeer de zojuist gedownloade oplossing op uw computer.

1. Klik op **[!UICONTROL Next]**.

   ![](assets/seven.png)

1. De oplossing zal uploaden. U kunt de inhoud van het pakket desgewenst weergeven. Klik op **[!UICONTROL Next]**.

   ![](assets/image2014-12-12-9-3a6-3a10-1.png)

1. Zorg dat het selectievakje ingeschakeld blijft en klik op **[!UICONTROL Import]** .

   ![](assets/image2014-12-12-9-3a6-3a19-1.png)

1. U kunt het logbestand vrij downloaden en vervolgens op **[!UICONTROL Close]** klikken.

   ![](assets/image2014-12-12-9-3a6-3a29-1.png)

1. Geweldig! U moet nu de oplossing zien. Als het er niet is, vernieuw uw scherm.

   ![](assets/eleven.png)

1. Klik op **[!UICONTROL Publish Customization]**.

   >[!NOTE]
   >
   >Zorg ervoor dat u de globale synchronisatie [!DNL MS Dynamics] inschakelt.

## Connect Marketo en [!DNL Sales Insight] {#connect-marketo-and-sales-insight}

Laten we uw Marketo-instantie koppelen aan [!DNL Sales Insight] in [!DNL Dynamics] . Hieronder wordt beschreven hoe:

>[!NOTE]
>
>**Vereiste Bevoegdheden Admin**

1. Meld u aan bij Marketo en ga naar de sectie **[!UICONTROL Admin]** .

   ![](assets/image2014-12-12-9-3a6-3a50-1.png)

1. Klik onder de sectie [!UICONTROL Sales Insight] op **[!UICONTROL Edit API Configuration]** .

   ![](assets/image2014-12-12-9-3a7-3a0-1.png)

1. Kopieer **[!UICONTROL Marketo Host]** , **[!UICONTROL API URL]** en **[!UICONTROL API User Id]** voor gebruik in een latere stap. Voer de gewenste API-beveiligingssleutel in en klik op **[!UICONTROL Save]** .

   >[!CAUTION]
   >
   >Gebruik geen en-teken (&amp;) in de geheime API-sleutel.

   ![](assets/image2014-12-12-9-3a7-3a9-1.png)

   >[!NOTE]
   >
   >De volgende gebieden moeten met Marketo voor _zowel Lood als Contact_ voor [!DNL Sales Insight] worden gesynchroniseerd om te werken:
   >
   >* Prioriteit
   >* Urgentie
   >* Relatieve score
   >
   >Als een van deze velden ontbreekt, wordt in Marketo een foutbericht weergegeven met de naam van de ontbrekende velden. Om dit te bevestigen, voer [ deze procedure ](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/required-fields-for-syncing-marketo-with-dynamics.md) uit.

1. Ga terug in [!DNL Microsoft Dynamics] en ga naar **[!UICONTROL Settings]** .

   ![](assets/image2014-12-12-9-3a7-3a25-1.png)

1. Klik onder **[!UICONTROL Settings]** op **[!UICONTROL Marketo API Config]** .

   ![](assets/image2014-12-12-9-3a7-3a34-1.png)

1. Klik op **[!UICONTROL New]**.

   ![](assets/image2014-12-12-9-3a8-3a8-1.png)

1. Voer de informatie in die u eerder van Marketo hebt ontvangen en klik op **[!UICONTROL Save]** .

   ![](assets/image2014-12-12-9-3a8-3a17-1.png)

## Synchronisatie inschakelen {#enable-sync}

1. Klik in Marketo op **[!UICONTROL Admin]** .

   ![](assets/enable-one.png)

1. Selecteer onder Integratie **[!UICONTROL Microsoft Dynamics]** .

   ![](assets/enable-two.png)

1. Klik op **[!UICONTROL Enable Sync]**.

   ![](assets/enable-three.png)

1. Klik op **[!UICONTROL Edit]** naast [!UICONTROL Field Sync Details] .

   ![](assets/enable-four.png)

1. Dit zal __ automatisch de gebieden selecteren MSI die eerder onbruikbaar werden gemaakt ([!UICONTROL Urgency], [!UICONTROL Relative Score], en [!UICONTROL Priority]). Klik op **[!UICONTROL Save]** om te beginnen met het synchroniseren van gegevens.

   ![](assets/enable-five.png)

## Gebruikerstoegang instellen {#set-user-access}

Tot slot moet u specifieke gebruikers toegang geven tot het gebruik van [!DNL Marketo Sales Insight] .

1. Ga naar **[!UICONTROL Settings]** .

   ![](assets/image2014-12-12-9-3a8-3a34-1.png)

1. Ga naar **[!UICONTROL Security]** .

   ![](assets/image2015-4-29-14-3a56-3a33-1.png)

1. Klik op **[!UICONTROL Users]**.

   ![](assets/image2015-4-29-14-3a57-3a46-1.png)

1. Selecteer de gebruikers tot wie u toegang wilt geven [!DNL Sales Insight] en klik **[!UICONTROL Manage Roles]**.

   ![](assets/image2015-4-29-14-3a59-3a31-1.png)

1. Selecteer de [!DNL Marketo Sales Insight] rol en klik op **[!UICONTROL OK]** .

   ![](assets/image2014-12-12-9-3a9-3a22-1.png)

   En jullie moeten allemaal klaar zijn! Als u ten slotte een test wilt uitvoeren, meldt u zich aan bij [!DNL Dynamics] als een gebruiker die toegang heeft tot [!DNL Marketo Sales Insight] en bekijkt u een lead of contactpersoon.

   ![](assets/image2015-4-29-15-3a2-3a27-1.png)

>[!MORELIKETHIS]
>
>[ de Sterren en Flames van de Opstelling voor Lood/de Verslagen van het Contact ](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/setting-up-stars-and-flames-for-lead-contact-records.md)
