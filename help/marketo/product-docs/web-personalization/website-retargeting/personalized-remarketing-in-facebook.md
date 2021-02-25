---
unique-page-id: 4720917
description: Persoonlijke opmerkingen op Facebook - Marketo Docs - Productdocumentatie
title: Persoonlijke opmerkingen op Facebook
translation-type: tm+mt
source-git-commit: fbaf57ec4f3532c2d71acf23171d60873b1c997c
workflow-type: tm+mt
source-wordcount: '309'
ht-degree: 0%

---


# Persoonlijke opmerkingen op Facebook {#personalized-remarketing-in-facebook}

Met gepersonaliseerde opmerkingen kunt u opnieuw contact opnemen met uw gebruikers via RTP-gegevens en de kracht van Facebook-marketing.

>[!PREREQUISITES]
>
>* Voltooi [Opnieuw rangschikken met de Gegevens van de Personalisatie van het Web](/help/marketo/product-docs/web-personalization/website-retargeting/retargeting-with-web-personalization-data.md) opstelling
>* Raadpleeg de [](https://developers.facebook.com/docs/ads-for-websites/website-custom-audiences/getting-started#install-the-pixel) [Facebook-documentatie over Aangepast publiek](https://developers.facebook.com/docs/ads-for-websites/website-custom-audiences/getting-started#install-the-pixel) en Opmerking.


## Een publiek maken op Facebook {#creating-an-audience-in-facebook}

1. Ga op Facebook naar het tabblad [Publiek](https://www.facebook.com/ads/audience_manager) in Advertentiebeheer.

1. Klik **Gereedschappen** en selecteer **Soorten publiek**.

   ![](assets/one-1.png)

1. Klik **Een aangepast publiek maken**.

   ![](assets/two-1.png)

1. Selecteer **Websiteverkeer**.

   ![](assets/image2015-1-19-16-3a32-3a2.png)

1. Selecteer **Aangepaste combinatie** in de lijst Verkeer website.

   ![](assets/image2015-1-19-16-3a33-3a21.png)

1. Selecteer **Event** in de lijst Opnemen.

   ![](assets/image2015-1-19-16-3a34-3a9.png)

1. Selecteer **RTP-markering** in de lijst Gebeurtenis en selecteer een parameter.

   ![](assets/image2015-1-19-16-3a52-3a29.png)

1. Voor dit voorbeeld, uitgezochte Industrie om **Onderwijs** te bevatten. Voer **Onderwijs** in en bewerk **In de laatste** om 180 dagen te zijn. Voer de naam van het publiek in: **Onderwijsindustrie**. Klik **Publiek maken**.

   ![](assets/image2015-1-19-16-3a56-3a15.png)

1. U hebt nu een nieuw aangepast publiek gemaakt met RTP-gegevens op Facebook.

   ![](assets/image2015-1-19-16-3a59-3a2.png)

## RTP-gegevenspunten op Facebook {#rtp-data-points-in-facebook}

<table> 
 <tbody> 
  <tr> 
   <th>Gebeurtenisnaam</th> 
   <th> </th> 
  </tr> 
  <tr> 
   <td>RTP Opmerking</td> 
   <td> 
    <div> 
     <table> 
      <tbody> 
       <tr> 
        <th>Parameter</th> 
        <th>Waarde</th> 
       </tr> 
       <tr> 
        <td>ABM-lijst</td> 
        <td>(Naam van lijst op basis van account)</td> 
       </tr> 
       <tr> 
        <td colspan="1">Categorie</td> 
        <td colspan="1"><p>Fortune 500</p><p>Fortune 1000</p><p>Globaal 2000</p></td> 
       </tr> 
       <tr> 
        <td colspan="1">Groep</td> 
        <td colspan="1"><p>Enterprise</p><p>SMB</p></td> 
       </tr> 
       <tr> 
        <td>Industrie</td> 
        <td><p>Defensie</p><p>Onderwijs</p><p>Financiële diensten</p><p>Overheid</p><p>Gezondheidszorg, Pharma, Biotech</p><p>Software en internet</p><p>enz. (volgens de opties van de Industrie RTP)</p></td> 
       </tr> 
       <tr> 
        <td colspan="1">Gesegmenteerd publiek</td> 
        <td colspan="1">(Naam van Gesegmenteerde Publiek dat in RTP wordt gecreeerd)</td> 
       </tr> 
      </tbody> 
     </table> 
    </div></td> 
  </tr> 
 </tbody> 
</table>

## Uw publiek richten met een Advertentie {#target-your-audience-with-an-ad}

Zie [Documentatie van Facebook](https://developers.facebook.com/docs/ads-for-websites/website-custom-audiences/getting-started#target-your-audience) voor meer informatie.

1. Ga naar Advertentiebeheer, klik **Create Advertentie**.

   ![](assets/image2015-1-19-17-3a10-3a19.png)

1. Selecteer **Personen naar uw website verzenden** als het doel van uw campagne.

   ![](assets/image2015-1-19-17-3a11-3a20.png)

1. Voer de URL van uw website in.

   ![](assets/image2015-1-19-17-3a12-3a39.png)

1. Maak uw advertentieset. Selecteer een aangepast publiek in de lijst met soorten publiek die u hebt gemaakt, bijvoorbeeld Onderwijsindustrie.

   ![](assets/image2015-1-19-17-3a18-3a13.png)

1. Selecteer alle andere advertentieopties, stel uw budget in en definieer uw advertentiefilters.

   ![](assets/image2015-1-19-17-3a19-3a25.png)

1. U bent nu allemaal ingesteld met een persoonlijke marketingcampagne op Facebook.

>[!MORELIKETHIS]
>
>* [Opnieuw toewijzen met webpersonalisatiegegevens](/help/marketo/product-docs/web-personalization/website-retargeting/retargeting-with-web-personalization-data.md)
>* [Persoonlijke opmerkingen in Google](/help/marketo/product-docs/web-personalization/website-retargeting/personalized-remarketing-in-google.md)

