---
unique-page-id: 30081815
description: Adobe Experience Manager-integratie configureren - Marketo Docs - Productdocumentatie
title: Adobe Experience Manager-integratie configureren
hide: true
hidefromtoc: true
exl-id: 06b2c214-1afb-443f-ae01-0c00fed77dce
source-git-commit: 3105fb33fb457d4dfb63081b80d4d1def717ad34
workflow-type: tm+mt
source-wordcount: '235'
ht-degree: 0%

---

# Adobe Experience Manager-integratie configureren {#configuring-adobe-experience-manager-integration}

Vorm AEM zodat kunt u, AEM activa in de Studio van het Ontwerp van Marketo toegang hebben selecteren en invoeren.

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

1. In **Gereedschappen**, klikt u op **Bewerkingen** en selecteert u **Webconsole**.

   ![](assets/2a.png)

1. Zoek in uw browser (ctrl+f in Windows, cmd+f in Mac) naar &quot;Beleid voor het delen van bronnen van Adobe Granite voor kruisoorsprong.&quot;

   ![](assets/three.png)

1. Klik op de knop **+** teken aan de rechterkant.

   ![](assets/four.png)

1. In de **Toegestane oorsprong (Regexp)** tekstvak, typen in `https://.*\.marketo\.com` en klik op **Opslaan**.

   ![](assets/five-psd.png)

1. Klik in de koptekst boven aan de pagina op **Webconsole** en selecteert u **Systeeminformatie**.

   ![](assets/six.png)

1. Klik onder Serverinformatie op de knop **Opnieuw starten** knop.

   ![](assets/seven.png)

1. Klikken **OK** ter bevestiging.

   ![](assets/eight.png)

1. Klik in Marketo Classic op **Beheer**.

   ![](assets/nine.png)

1. Selecteer onder Integratie **Adobe Experience Manager**.

   ![](assets/ten.png)

1. Klikken **Bewerken**.

   ![](assets/eleven.png)

1. Voer uw AEM-URL in en klik op **OK**.

   ![](assets/twelve.png)

   U bent klaar! U kunt nu [de invoer AEM activa in de Studio van het Ontwerp in Marketo Sky](https://experienceleague.adobe.com/docs/marketo/sky/design-studio/importing-assets-with-adobe-experience-manager.html?lang=en#design-studio).
