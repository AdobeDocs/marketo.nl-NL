---
unique-page-id: 3571739
description: Marketo Sales Insight installeren en configureren in Microsoft Dynamics 365 - Marketo Docs - Productdocumentatie
title: Marketo Sales Insight installeren en configureren in Microsoft Dynamics 365
exl-id: c1f06b8c-48fd-4015-9502-7c9693632589
feature: Marketo Sales Insights
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '386'
ht-degree: 2%

---

# Installeren en configureren [!DNL Marketo Sales Insight] in [!DNL Microsoft Dynamics 365] {#install-and-configure-marketo-sales-insight-in-microsoft-dynamics}

[!DNL Marketo Sales Insight] is een fantastisch hulpmiddel om uw verkoopteam een &quot;venster&quot;in de rijkdom van gegevens te geven het team van de Marketing heeft. Hier is hoe te installeren en te vormen.

>[!PREREQUISITES]
>
>Voltooi uw integratie tussen Marketo en Microsoft.
>
>[ Download de correcte oplossing ](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/download-the-marketo-sales-insight-solution-for-microsoft-dynamics.md) voor uw versie van [!DNL Microsoft Dynamics CRM].

## Oplossing importeren {#import-solution}

1. Meld u aan bij [[!DNL Microsoft Office 365] ](https://login.microsoftonline.com/) .

   ![](assets/image2015-3-16-15-58-55.png)

1. Klik ![ - ](assets/image2015-3-16-16-1-13.png) menu en selecteer **CRM**.

   ![](assets/image2015-3-16-16-0-10.png)

1. Klik op het menu ![— ](assets/image2015-5-13-10-5-8.png) . Selecteer in de vervolgkeuzelijst **[!DNL Settings]** en selecteer vervolgens **[!DNL Solutions]** .

   ![](assets/image2015-5-13-10-4-1.png)

   >[!NOTE]
   >
   >U zou reeds [ geïnstalleerd en de oplossing van Marketo ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-1-of-4-install.md) moeten gevormd hebben alvorens zich vooruit te bewegen.

1. Klik op **[!UICONTROL Import]**.

   ![](assets/image2014-12-12-9-3a5-3a27.png)

1. Klik in het nieuwe venster op **[!UICONTROL Browse]** . Kies de [ oplossing van Insight van de Verkoop van Marketo u in stap 1 ](#msi) downloadde. Klik op **[!UICONTROL Next]**.

   ![](assets/image2015-5-13-15-3a38-3a49.png)

1. De oplossing zal uploaden. U kunt de inhoud van het pakket desgewenst weergeven. Klik op **[!UICONTROL Next]**.

   ![](assets/image2014-12-12-9-3a6-3a10.png)

1. Laat het vak **[!UICONTROL checked]** staan en klik op **[!UICONTROL Import]** .

   ![](assets/image2014-12-12-9-3a6-3a19.png)

1. U kunt het logbestand vrij downloaden. Klik op **[!UICONTROL Close]**.

   ![](assets/image2014-12-12-9-3a6-3a29.png)

1. Geweldig! U moet nu de oplossing zien. Als het er niet is, vernieuw uw scherm.

   ![](assets/image2015-5-13-15-3a42-3a29.png)

1. Klik op **[!UICONTROL Publish All Customizations]**.

   ![](assets/image2015-11-10-11-3a15-3a40.png)

## Connect Marketo en [!DNL Sales Insight] {#connect-marketo-and-sales-insight}

Laten we uw Marketo-instantie koppelen aan [!DNL Sales Insight] in [!DNL Dynamics] . Hieronder wordt beschreven hoe:

>[!NOTE]
>
>**Vereiste Bevoegdheden Admin**

1. Meld u aan bij Marketo en ga naar de sectie **[!UICONTROL Admin]** .

   ![](assets/image2014-12-12-9-3a6-3a50.png)

1. Onder de **[!UICONTROL Sales Insight]** sectie, geeft de klik **API Configuratie** uit.

   ![](assets/image2014-12-12-9-3a7-3a0.png)

1. Kopieer de **[!UICONTROL Marketo Host]** , **[!UICONTROL API URL]** en **[!UICONTROL API User Id]** voor gebruik in een latere stap. Voer een **[!UICONTROL API Secret Key]** van uw keuze in en klik op **[!UICONTROL Save]** .

   >[!CAUTION]
   >
   >Gebruik geen en-teken (&amp;) in de geheime API-sleutel.

   ![](assets/image2014-12-12-9-3a7-3a9.png)

   >[!NOTE]
   >
   >De volgende gebieden moeten met Marketo voor _zowel Lood als Contact_ voor [!DNL Sales Insight] worden gesynchroniseerd om te werken:
   >
   > * Prioriteit
   > * Urgentie
   > * Relatieve score
   >
   >Als een van deze velden ontbreekt, wordt in Marketo een foutbericht weergegeven met de naam van de ontbrekende velden. Om dit te bevestigen, voer [ deze procedure ](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/required-fields-for-syncing-marketo-with-dynamics.md) uit.

1. Klik in [!DNL Microsoft Dynamics] weer op het pictogram ![](assets/image2015-5-13-15-3a49-3a19.png) naast [!UICONTROL Settings] en selecteer vervolgens **[!UICONTROL Marketo API Config]** in het vervolgkeuzemenu.

   ![](assets/image2015-5-13-16-3a4-3a1.png)

1. Klik op **[!UICONTROL Default Configuration]**.

   ![](assets/image2015-5-13-16-3a5-3a2.png)

1. Voer de gegevens in die u eerder uit Marketo hebt gekopieerd.

   ![](assets/image2015-5-13-16-3a7-3a6.png)

1. Klik op het pictogram ![](assets/image2015-5-13-16-3a8-3a51.png) in de rechterbenedenhoek om de wijzigingen op te slaan.

## Gebruikerstoegang instellen {#set-user-access}

U moet gebruikers machtigingen geven om [!DNL Sales Insight] te gebruiken.

1. Klik op het menu ![](assets/image2015-5-13-10-3a5-3a8.png) . Selecteer **[!UICONTROL Settings]** in het vervolgkeuzemenu en selecteer vervolgens **[!UICONTROL Security]** .

   ![](assets/image2015-5-13-16-3a12-3a12.png)

1. Klik op **[!UICONTROL Users]**.

   ![](assets/image2015-4-29-14-3a57-3a46.png)

1. Selecteer de gebruiker(s) tot wie u toegang wilt geven [!DNL Sales Insight] en klik op **[!UICONTROL Manage Roles]** .

   ![](assets/image2015-4-29-14-3a59-3a31.png)

1. Selecteer de **[!UICONTROL Marketo Sales Insight]** rol en klik op **[!UICONTROL OK]** .

   ![](assets/image2014-12-12-9-3a9-3a22.png)

   En jullie moeten allemaal klaar zijn! Als u ten slotte een test wilt uitvoeren, meldt u zich aan bij [!DNL Dynamics] als een gebruiker die toegang heeft tot [!DNL Marketo Sales Insight] en bekijkt u een lead of contactpersoon.

   ![](assets/image2015-4-29-15-3a2-3a27.png)

U hebt nu de kracht van [!DNL Marketo Sales Insight] voor uw verkoopteam ontgrendeld.

>[!MORELIKETHIS]
>
>[ de Sterren en Flames van de Opstelling voor Lood/de Verslagen van het Contact ](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/setting-up-stars-and-flames-for-lead-contact-records.md)
