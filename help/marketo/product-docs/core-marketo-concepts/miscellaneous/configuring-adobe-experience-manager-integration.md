---
unique-page-id: 30081815
description: Adobe Experience Manager-integratie configureren - Marketo Docs - Productdocumentatie
title: Adobe Experience Manager-integratie configureren
hide: true
hidefromtoc: true
exl-id: 06b2c214-1afb-443f-ae01-0c00fed77dce
feature: Integrations
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '188'
ht-degree: 0%

---

# Adobe Experience Manager-integratie configureren {#configuring-adobe-experience-manager-integration}

Configureer Adobe Experience Manager (AEM) zodat u toegang hebt tot AEM-elementen en deze kunt selecteren en importeren in Marketo Engage Design Studio.

>[!NOTE]
>
>**Vereiste Bevoegdheden Admin**

>[!IMPORTANT]
>
>* Deze integratie werkt alleen met on-premise implementaties van AEM en wordt niet ondersteund voor implementaties van AEM Cloud Service.
>
>* Deze functie wordt momenteel alleen volledig ondersteund in Firefox. Deze functie wordt niet ondersteund in Safari en werkt mogelijk niet in de meest recente versie van Chrome, afhankelijk van uw SameSite cookie-instellingen.

1. Navigeer naar de Adobe Experience Manager (de URL is specifiek voor uw bedrijf).

   ![](assets/one.png)

1. U kunt zich aanmelden met Adobe of u kunt zich lokaal aanmelden. In dit voorbeeld zullen we ons lokaal aanmelden.

   ![](assets/two.png)

1. Klik in **[!UICONTROL Tools]** op **[!UICONTROL Operations]** en selecteer **[!UICONTROL Web Console]** .

   ![](assets/2a.png)

1. Zoek in uw browser (ctrl+f in Windows, cmd+f in Mac) naar &quot;[!UICONTROL Adobe Granite Cross-Origin Resource Sharing Policy]&quot;.

   ![](assets/three.png)

1. Klik op het **+** -teken aan de rechterkant.

   ![](assets/four.png)

1. Typ in het tekstvak **[!UICONTROL Allowed Origins (Regexp)]** in `https://.*\.marketo\.com` en klik op **[!UICONTROL Save]** .

   ![](assets/five-psd.png)

1. Klik in de koptekst boven aan de pagina op **[!UICONTROL Web Console]** en selecteer **[!UICONTROL System Information]** .

   ![](assets/six.png)

1. Klik onder Serverinformatie op de knop **[!UICONTROL Restart]** .

   ![](assets/seven.png)

1. Klik op **[!UICONTROL OK]** om te bevestigen.

   ![](assets/eight.png)

1. Klik in Marketo Engage op **[!UICONTROL Admin]** .

   ![](assets/nine.png)

1. Selecteer onder Integratie **[!UICONTROL Adobe Experience Manager]** .

   ![](assets/ten.png)

1. Klik op **[!UICONTROL Edit]**.

   ![](assets/eleven.png)

1. Voer de AEM-URL in en klik op **[!UICONTROL OK]** .

   ![](assets/twelve.png)
