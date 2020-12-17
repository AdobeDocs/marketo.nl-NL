---
unique-page-id: 30081815
description: Adobe Experience Manager-integratie configureren - Marketo Docs - Productdocumentatie
title: Adobe Experience Manager-integratie configureren
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '219'
ht-degree: 0%

---


# Adobe Experience Manager-integratie configureren {#configuring-adobe-experience-manager-integration}

Vorm AEM zodat kunt u, AEM activa in de Studio van het Ontwerp van Marketo toegang hebben selecteren en invoeren.

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

>[!CAUTION]
>
>Deze functie wordt momenteel alleen volledig ondersteund in Firefox. Deze functie wordt niet ondersteund in Safari en werkt mogelijk niet in de nieuwste versie van Chrome (v. 80), afhankelijk van de cookie-instellingen van SameSite.

1. Navigeer naar de Adobe Experience Manager (de URL is specifiek voor uw bedrijf).

   ![](assets/one.png)

1. U kunt zich aanmelden met Adobe of u kunt zich lokaal aanmelden. In dit voorbeeld zullen we ons lokaal aanmelden.

   ![](assets/two.png)

1. Klik in **Gereedschappen** op **Bewerkingen** en selecteer **Webconsole**.

   ![](assets/2a.png)

1. Zoek in uw browser (ctrl+f in Windows, cmd+f in Mac) naar &quot;Adobe Granite Cross-Origin Resource Sharing Policy.&quot;

   ![](assets/three.png)

1. Klik op het **+**-teken rechts.

   ![](assets/four.png)

1. Typ in het tekstvak **Toegestane oorsprong (Regexp)** &quot;https://.*\.marketo\.com&quot; (zonder de citaten) en klik **Save**.

   ![](assets/five-psd.png)

1. Klik in de koptekst boven aan de pagina op **Webconsole** en selecteer **Systeeminformatie**.

   ![](assets/six.png)

1. Klik onder Serverinformatie op de knop **Opnieuw starten**.

   ![](assets/seven.png)

1. Klik **OK** om te bevestigen.

   ![](assets/eight.png)

1. Klik in Marketo Classic op **Admin**.

   ![](assets/nine.png)

1. Selecteer **Adobe Experience Manager** onder Integratie.

   ![](assets/ten.png)

1. Klik **Bewerken**.

   ![](assets/eleven.png)

1. Voer uw AEM-URL in en klik op **OK**.

   ![](assets/twelve.png)

   U bent klaar! U kunt nu [AEM activa in de Studio van het Ontwerp in Marketo Sky ](http://help.marketo.com/hc/en-us/articles/360036765993) invoeren.

