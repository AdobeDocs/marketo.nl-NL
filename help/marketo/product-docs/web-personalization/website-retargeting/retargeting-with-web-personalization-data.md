---
unique-page-id: 4720796
description: Opnieuw toewijzen met Personalization-gegevens op het web - Marketo Docs - Productdocumentatie
title: Opnieuw toewijzen met Personalization-gegevens op het web
exl-id: b5af1f84-2061-4d0d-9d1f-2fff9191f028
feature: Web Personalization
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '381'
ht-degree: 1%

---

# Opnieuw toewijzen met [!DNL Web Personalization] gegevens {#retargeting-with-web-personalization-data}

>[!AVAILABILITY]
>
>Het opnieuw plaatsen van websites valt nu onder de Web Personalization-tegel. Als u slechts het Terugwinnen kocht, zult u deze tegel zien en tot het [!DNL Web Personalization] product met **slechts** toegang hebben toegelaten het opnieuw samenbrengen eigenschappen. Op deze manier hebt u toegang tot accountinstellingen, de pagina Opnieuw rangschikken, segmenten en extra pagina&#39;s voor bijhouden.

Opmerkingen zijn gericht op de vooruitzichten die uw site in het verleden hebben bezocht, met behulp van weergaveadvertenties op basis van wie ze zijn en wat ze hebben gedaan. Speciale doelgroepen richten zich op specifieke doelgroepen met relevante advertenties op basis van de industrie, benoemde accounts en bekende persoongegevens.

Web Personalization voegt momenteel gegevens toe aan de volgende remarketing platforms:

* [Google](/help/marketo/product-docs/web-personalization/website-retargeting/personalized-remarketing-in-google.md)
* [Facebook](/help/marketo/product-docs/web-personalization/website-retargeting/personalized-remarketing-in-facebook.md)

[!DNL Web Personalization] stuurt de volgende gegevens door naar de wedermarketingplatforms om een publiek te maken en advertentiecampagnes voor opnieuw marketing uit te voeren:

<table>
 <tbody>
  <tr>
   <th colspan="1">[!DNL Web Personalization] Data</th>
  </tr>
  <tr>
   <th><p>Marktsegment</p></th>
  </tr>
  <tr>
   <th><p>Groep (Enterprise, SMB)</p></th>
  </tr>
  <tr>
   <th><p>Categorie (Fortune 500/1000, Global 2000)</p></th>
  </tr>
  <tr>
   <th><p>ABM-lijst (lijst met benoemde accounts)</p></th>
  </tr>
  <tr>
   <th><p>Gesegmenteerd publiek (op basis van segmenten)</p></th>
  </tr>
  <tr>
   <th><p>Webcampagnes geklikt</p></th>
  </tr>
 </tbody>
</table>

## Opmerking configuratie {#remarketing-configuration}

1. Ga naar **[!UICONTROL Retargeting]** .

   ![](assets/one.png)

   >[!NOTE]
   >
   >De configuratie voor opnieuw toewijzen is per domein of subdomein. Activeer de andere domeinen als u gegevens van die domeinen door aan het opnieuw richten platform wilt verzenden.

1. Activeer Instellingen voor Google Analytics of [!DNL Google Universal Analytics] per domein.

   >[!NOTE]
   >
   >De Google-tag voor opnieuw plaatsen moet op uw website zijn geïmplementeerd.
   >
   >Als u al een integratie hebt ingesteld met Web Personalization en Google Analytics, hoeft u dit onderdeel niet te bewerken omdat het dezelfde configuratie is onder Accountinstellingen.

   ![](assets/two.png)

1. Activeer de configuratie voor Facebook. Klik op de accordeon [!DNL Facebook] en vouw deze uit. Klik op **[!UICONTROL On]** om de desbetreffende gebeurtenis en gegevens naar Facebook Audience Manager te verzenden. Klik op **[!UICONTROL Save]**.

   >[!NOTE]
   >
   >U moet [[!DNL Facebook]  het Pixel van het Publiek van de Douane hebben &#x200B;](https://developers.facebook.com/docs/ads-for-websites/website-custom-audiences/getting-started#install-the-pixel) uw website voor deze eigenschap geïnstalleerd om te werken.

   ![](assets/three.png)

## Gesegmenteerde doelgroep maken {#creating-segmented-audience}

Met een gesegmenteerd publiek kunt u een bestaand segment selecteren als een publiek dat u wilt gebruiken voor het opnieuw toewijzen van campagnes. U kunt bijvoorbeeld de segmenten van uw bekende persoon selecteren.

>[!TIP]
>
>Er is geen behoefte om een Gesegmenteerd Publiek voor de industrie of andere gegevens tot stand te brengen die reeds door in de Configuratie van het Domein zijn verzonden. Het is best om Gesegmenteerde Publiek voor segmenten te gebruiken die op bekende persoongegevens worden gebaseerd.

1. Klik op **[!UICONTROL Create Segmented Audience]**.

   ![](assets/image2015-1-15-16-3a36-3a38.png)

1. Ga publieksnaam in, selecteer Kanalen, en selecteer Segment van de lijst van bestaande Segmenten.

   ![](assets/image2015-1-15-16-3a40-3a17.png)

1. Klik op **[!UICONTROL Save]**.

   U hebt nu de instelling Opnieuw voorbereiden in [!DNL Web Personalization] voltooid, zich aan te melden bij heroriënterende platforms en op basis van deze gegevens een publiek te maken en uw opnieuw gerichte advertentiecampagnes in te stellen.
