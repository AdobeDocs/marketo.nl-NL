---
unique-page-id: 4720917
description: Persoonlijke opmerkingen in Facebook - Marketo Docs - Productdocumentatie
title: Persoonlijke opmerkingen in Facebook
exl-id: 47636afa-49df-40ba-8948-4f2850467c2f
feature: Web Personalization
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '309'
ht-degree: 0%

---

# Persoonlijke opmerkingen in Facebook {#personalized-remarketing-in-facebook}

De gepersonaliseerde Markeringen laat u met uw gebruikers opnieuw in dienst nemen gebruikend Gegevens RTP en de macht van de Markering van Facebook.

>[!PREREQUISITES]
>
>* Voltooi de [Opnieuw toewijzen met webpersonalisatiegegevens](/help/marketo/product-docs/web-personalization/website-retargeting/retargeting-with-web-personalization-data.md) instellen
>* Controleer de [&#128279;](https://developers.facebook.com/docs/ads-for-websites/website-custom-audiences/getting-started#install-the-pixel) [Facebook-documentatie over aangepast publiek](https://developers.facebook.com/docs/ads-for-websites/website-custom-audiences/getting-started#install-the-pixel) en Opmerking.

## Een publiek maken in Facebook {#creating-an-audience-in-facebook}

1. Ga in Facebook naar je [Tabblad Publiek](https://www.facebook.com/ads/audience_manager) in Advertentiebeheer.

1. Klikken **Gereedschappen** en selecteert u **Soorten publiek**.

   ![](assets/one-1.png)

1. Klikken **Een aangepast publiek maken**.

   ![](assets/two-1.png)

1. Selecteren **Websiteverkeer**.

   ![](assets/image2015-1-19-16-3a32-3a2.png)

1. Selecteer in de lijst Websites de optie **Aangepaste combinatie**.

   ![](assets/image2015-1-19-16-3a33-3a21.png)

1. Selecteer in de lijst Opnemen de optie **Gebeurtenis**.

   ![](assets/image2015-1-19-16-3a34-3a9.png)

1. Selecteer in de lijst Gebeurtenis de optie **RTP Opmerking** en selecteert u een parameter.

   ![](assets/image2015-1-19-16-3a52-3a29.png)

1. Selecteer in dit voorbeeld de optie Industrie om **Onderwijs**. Enter **Onderwijs** en bewerken **In de laatste** 180 dagen te zijn. Voer de naam van het publiek in: **Onderwijsindustrie**. Klikken **Publiek maken**.

   ![](assets/image2015-1-19-16-3a56-3a15.png)

1. U hebt nu een nieuw aangepast publiek gemaakt met RTP-gegevens in Facebook.

   ![](assets/image2015-1-19-16-3a59-3a2.png)

## RTP-gegevenspunten in Facebook {#rtp-data-points-in-facebook}

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
        <td>Marktsegment</td> 
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

## Doelgroep voor publiek met advertentie {#target-your-audience-with-an-ad}

Zie voor meer informatie [Facebook-documentatie](https://developers.facebook.com/docs/ads-for-websites/website-custom-audiences/getting-started#target-your-audience).

1. Ga naar Advertentiebeheer en klik op **Advertentie maken**.

   ![](assets/image2015-1-19-17-3a10-3a19.png)

1. Selecteren **Personen naar uw website verzenden** als het doel van uw campagne.

   ![](assets/image2015-1-19-17-3a11-3a20.png)

1. Voer de URL van uw website in.

   ![](assets/image2015-1-19-17-3a12-3a39.png)

1. Maak uw advertentieset. Selecteer een aangepast publiek in de lijst met soorten publiek die u hebt gemaakt, bijvoorbeeld Onderwijsindustrie.

   ![](assets/image2015-1-19-17-3a18-3a13.png)

1. Selecteer alle andere advertentieopties, stel uw budget in en definieer uw advertentiefilters.

   ![](assets/image2015-1-19-17-3a19-3a25.png)

1. U bent nu allemaal in Facebook met een gepersonaliseerde marketingcampagne opgezet.

>[!MORELIKETHIS]
>
>* [Opnieuw toewijzen met webpersonalisatiegegevens](/help/marketo/product-docs/web-personalization/website-retargeting/retargeting-with-web-personalization-data.md)
>* [Persoonlijke opmerkingen in Google](/help/marketo/product-docs/web-personalization/website-retargeting/personalized-remarketing-in-google.md)
