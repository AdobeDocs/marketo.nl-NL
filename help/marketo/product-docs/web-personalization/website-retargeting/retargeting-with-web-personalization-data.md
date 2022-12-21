---
unique-page-id: 4720796
description: Opnieuw toewijzen met persoonlijke gegevens op het web - Marketo Docs - Productdocumentatie
title: Opnieuw toewijzen met webpersonalisatiegegevens
exl-id: b5af1f84-2061-4d0d-9d1f-2fff9191f028
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '406'
ht-degree: 0%

---

# Opnieuw toewijzen met webpersonalisatiegegevens {#retargeting-with-web-personalization-data}

>[!AVAILABILITY]
>
>Het opnieuw plaatsen van websites valt nu onder de tegel voor webpersonalisatie. Als u alleen Retargeting hebt aangeschaft, wordt deze tegel weergegeven en kunt u het product voor webpersonalisatie openen met **alleen** Functies voor opnieuw groeperen ingeschakeld. Op deze manier hebt u toegang tot accountinstellingen, de pagina Opnieuw rangschikken, segmenten en extra pagina&#39;s voor bijhouden.

Opmerkingen zijn gericht op de vooruitzichten die uw site in het verleden hebben bezocht, met behulp van weergaveadvertenties op basis van wie ze zijn en wat ze hebben gedaan. Speciale doelgroepen richten zich op specifieke doelgroepen met relevante advertenties op basis van de industrie, benoemde accounts en bekende persoongegevens.

De Personalisering van het Web voegt momenteel gegevens aan de volgende remarketing platforms toe:

* [Google](/help/marketo/product-docs/web-personalization/website-retargeting/personalized-remarketing-in-google.md)
* [Facebook](/help/marketo/product-docs/web-personalization/website-retargeting/personalized-remarketing-in-facebook.md)

De Personalisering van het Web verzendt de volgende gegevens door naar de remarketing platforms om publiek tot stand te brengen en remarketing ad campagnes in werking te stellen:

<table> 
 <tbody> 
  <tr> 
   <th colspan="1">Gegevens voor webpersonalisatie</th> 
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

1. Ga naar **Opnieuw rangschikken**.

   ![](assets/one.png)

   >[!NOTE]
   >
   >De configuratie voor opnieuw toewijzen is per domein of subdomein. Activeer de andere domeinen als u gegevens van die domeinen door aan het opnieuw richten platform wilt verzenden.

1. Activeer Instellingen voor Google Analytics of Google Universal Analytics per domein.

   >[!NOTE]
   >
   >De Google-tag voor opnieuw plaatsen moet op uw website zijn geïmplementeerd.
   >
   >Als u reeds uw Integratie met de Personalisering van het Web en Google Analytics opstelde, te hoeven u niet om dit deel uit te geven aangezien het de zelfde configuratie onder de Montages van de Rekening is.

   ![](assets/two.png)

1. Activeer de configuratie voor Facebook. Klik en vouw de accordeon van Facebook uit, klik **Aan** om de desbetreffende gebeurtenis en gegevens door te sturen naar Facebook Audience Manager. Klikken **Opslaan**.

   >[!NOTE]
   >
   >U moet [Pixel aangepast publiek facebook](https://developers.facebook.com/docs/ads-for-websites/website-custom-audiences/getting-started#install-the-pixel)Deze functie werkt pas nadat u uw website hebt geïnstalleerd.

   ![](assets/three.png)

## Gesegmenteerde doelgroep maken {#creating-segmented-audience}

Met een gesegmenteerd publiek kunt u een bestaand segment selecteren als een publiek dat u wilt gebruiken voor het opnieuw toewijzen van campagnes. U kunt bijvoorbeeld de segmenten van uw bekende persoon selecteren.

>[!TIP]
>
>Er is geen behoefte om een Gesegmenteerd Publiek voor de industrie of andere gegevens tot stand te brengen die reeds door in de Configuratie van het Domein zijn verzonden. Het is best om Gesegmenteerde Publiek voor segmenten te gebruiken die op bekende persoongegevens worden gebaseerd.

1. Klikken **Gesegmenteerd publiek maken**.

   ![](assets/image2015-1-15-16-3a36-3a38.png)

1. Ga publieksnaam in, selecteer Kanalen, en selecteer Segment van de lijst van bestaande Segmenten.

   ![](assets/image2015-1-15-16-3a40-3a17.png)

1. Klikken **Opslaan**.

   U hebt nu de Opnieuw richtende Opstelling in de Personalisering van het Web voltooid, login aan uw het opnieuw richten platforms en creeer uw publiek dat op deze gegevens wordt gebaseerd en opstelling uw het opnieuw richten advertentiecampagnes.
