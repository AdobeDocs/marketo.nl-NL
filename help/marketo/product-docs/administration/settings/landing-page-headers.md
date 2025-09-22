---
description: Landingspagina-headers - Marketo Docs - Productdocumentatie
title: Landingspaginakoppen
exl-id: 58eaa0cd-2a2b-4abe-9180-f60a2a1dcc87
feature: Administration, Landing Pages
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '122'
ht-degree: 0%

---

# Landingspaginakoppen {#landing-page-headers}

Voer de onderstaande stappen uit om een aantal HTTP-headers in de domeinen van de bestemmingspagina aan te passen.

1. Klik in Marketo op **[!UICONTROL Admin]** .

   ![](assets/landing-page-headers-1.png)

1. Klik op **[!UICONTROL Landing Pages]**.

   ![](assets/landing-page-headers-2.png)

1. Klik op **[!UICONTROL Edit]** naast HTTP-headers van bestemmingspagina.

   ![](assets/landing-page-headers-3.png)

1. Kies de gewenste instellingen en klik op **[!UICONTROL Save]** als u klaar bent.

   ![](assets/landing-page-headers-4.png)

<table>
 <tr>
  <td><strong>[!UICONTROL Strict-Transport-Security]</strong></td>
  <td>Gebruik deze optie om te garanderen dat verbindingen met bestemmingspagina's altijd via HTTPS worden aangeboden (moet alleen worden ingesteld voor abonnementen met bestemmingspagina's die zijn beveiligd door SSL)</td>
 </tr>
 <tr>
  <td><strong>[!UICONTROL X-Frame-Options]</strong></td>
  <td>Hiermee kunt u bepalen of door Marketo Engage gehoste elementen kunnen worden ingesloten in externe webpagina's</td>
 </tr>
</table>

>[!CAUTION]
>
>Het is belangrijk om deze montages met uw team van IT te herzien om te bepalen wat het beleid van uw organisatie zou moeten worden geplaatst aan. Onjuiste instellingen kunnen voorkomen dat sommige bezoekers toegang krijgen tot uw bestemmingspagina&#39;s.
