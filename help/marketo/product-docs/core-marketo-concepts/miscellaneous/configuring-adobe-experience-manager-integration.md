---
unique-page-id: 30081815
description: Adobe Experience Manager-integratie configureren - Marketo Docs - Productdocumentatie
title: Adobe Experience Manager-integratie configureren
hide: true
hidefromtoc: true
exl-id: 06b2c214-1afb-443f-ae01-0c00fed77dce
feature: Integrations
source-git-commit: 0abb315be0f9cb5f42fa41d72b446de8c2f62c1e
workflow-type: tm+mt
source-wordcount: '194'
ht-degree: 0%

---

# Adobe Experience Manager-integratie configureren {#configuring-adobe-experience-manager-integration}

Vorm Adobe Experience Manager (AEM) zodat kunt u, AEM activa in de Studio van het Ontwerp van het Marketo Engage toegang hebben selecteren en invoeren.

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

>[!IMPORTANT]
>
>* Deze integratie werkt alleen met implementaties van AEM op locatie en wordt niet ondersteund voor AEM Cloud Service-implementaties.
>
>* Deze functie wordt momenteel alleen volledig ondersteund in Firefox. Deze functie wordt niet ondersteund in Safari en werkt mogelijk niet in de meest recente versie van Chrome, afhankelijk van de cookie-instellingen van SameSite.

1. Navigeer naar de Adobe Experience Manager (de URL is specifiek voor uw bedrijf).

   ![](assets/one.png)

1. U kunt zich aanmelden met Adobe of u kunt zich lokaal aanmelden. In dit voorbeeld zullen we ons lokaal aanmelden.

   ![](assets/two.png)

1. In **[!UICONTROL Tools]**, klikt u op **[!UICONTROL Operations]** en selecteert u **[!UICONTROL Web Console]**.

   ![](assets/2a.png)

1. Zoek in uw browser (ctrl+f in Windows, cmd+f in Mac) naar &quot;Beleid voor het delen van bronnen met verschillende herkomst van graniet Adoben&quot;.

   ![](assets/three.png)

1. Klik op de knop **+** teken aan de rechterkant.

   ![](assets/four.png)

1. In de **[!UICONTROL Allowed Origins (Regexp)]** tekstvak, typen in `https://.*\.marketo\.com` en klik op **[!UICONTROL Save]**.

   ![](assets/five-psd.png)

1. Klik in de koptekst boven aan de pagina op **[!UICONTROL Web Console]** en selecteert u **[!UICONTROL System Information]**.

   ![](assets/six.png)

1. Klik onder Serverinformatie op de knop **[!UICONTROL Restart]** knop.

   ![](assets/seven.png)

1. Klikken **[!UICONTROL OK]** ter bevestiging.

   ![](assets/eight.png)

1. Klik in Marketo Engage op **[!UICONTROL Admin]**.

   ![](assets/nine.png)

1. Selecteer onder Integratie **[!UICONTROL Adobe Experience Manager]**.

   ![](assets/ten.png)

1. Klik op **[!UICONTROL Edit]**.

   ![](assets/eleven.png)

1. Voer uw AEM-URL in en klik op **[!UICONTROL OK]**.

   ![](assets/twelve.png)
