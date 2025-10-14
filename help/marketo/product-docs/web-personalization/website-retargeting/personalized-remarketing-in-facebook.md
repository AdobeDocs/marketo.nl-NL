---
unique-page-id: 4720917
description: Persoonlijke opmerkingen op Facebook - Marketo Docs - Productdocumentatie
title: Persoonlijke opmerkingen op Facebook
exl-id: 47636afa-49df-40ba-8948-4f2850467c2f
feature: Web Personalization
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '254'
ht-degree: 2%

---

# Speciale opmerkingen in [!DNL Facebook] {#personalized-remarketing-in-facebook}

Met gepersonaliseerde opmerkingen kunt u opnieuw contact opnemen met uw gebruikers met behulp van RTP-gegevens en de kracht van Facebook-marketing.

>[!PREREQUISITES]
>
>* Voltooi [&#x200B; opnieuw het richten met de Gegevens van Personalization van het Web &#x200B;](/help/marketo/product-docs/web-personalization/website-retargeting/retargeting-with-web-personalization-data.md) opstelling
>* Herzie de [&#128279;](https://developers.facebook.com/docs/ads-for-websites/website-custom-audiences/getting-started#install-the-pixel) [&#x200B; documentatie van Facebook over het publiek van de Douane &#x200B;](https://developers.facebook.com/docs/ads-for-websites/website-custom-audiences/getting-started#install-the-pixel) en het Opmerken.

## Een publiek maken in [!DNL Facebook] {#creating-an-audience-in-facebook}

1. In [!DNL Facebook], ga naar uw [&#x200B; lusje van het Publiek &#x200B;](https://www.facebook.com/ads/audience_manager) in de Manager van Advertenties.

1. Klik op **[!UICONTROL Tools]** en selecteer **[!UICONTROL Audiences]** .

![](assets/one-1.png)

1. Klik op **[!UICONTROL Create a Custom Audience]**.

![](assets/two-1.png)

1. Selecteer **[!UICONTROL Website Traffic]**.

![](assets/image2015-1-19-16-3a32-3a2.png)

1. Selecteer [!UICONTROL Website traffic] in de lijst **[!UICONTROL Custom Combination]** .

![](assets/image2015-1-19-16-3a33-3a21.png)

1. Selecteer **[!UICONTROL Event]** in de lijst Opnemen.

![](assets/image2015-1-19-16-3a34-3a9.png)

1. Selecteer [!UICONTROL Event] in de lijst **[!UICONTROL RTP Remarketing]** en selecteer een parameter.

![](assets/image2015-1-19-16-3a52-3a29.png)

1. In dit voorbeeld selecteert u [!UICONTROL Industry] om **[!UICONTROL Education]** te bevatten. Voer **[!UICONTROL Education]** in en bewerk **[!UICONTROL In the Last]** om 180 dagen te duren. Ga de Naam van het publiek in: **Onderwijsindustrie**. Klik op **[!UICONTROL Create Audience]**.

![](assets/image2015-1-19-16-3a56-3a15.png)

1. U hebt nu een nieuw aangepast publiek gemaakt met RTP-gegevens in [!DNL Facebook] .

![](assets/image2015-1-19-16-3a59-3a2.png)

## RTP-gegevenspunten in [!DNL Facebook] {#rtp-data-points-in-facebook}

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

Voor extra details, zie {de documentatie van 0} Facebook [.](https://developers.facebook.com/docs/ads-for-websites/website-custom-audiences/getting-started#target-your-audience)

1. Ga naar Advertentiebeheer en klik op **[!UICONTROL Create Ad]** .

   ![](assets/image2015-1-19-17-3a10-3a19.png)

1. Selecteer **[!UICONTROL Send people to your website]** als het doel van uw campagne.

   ![](assets/image2015-1-19-17-3a11-3a20.png)

1. Voer de URL van uw website in.

   ![](assets/image2015-1-19-17-3a12-3a39.png)

1. Maak uw advertentieset. Selecteer een aangepast publiek in de lijst met soorten publiek die u hebt gemaakt, bijvoorbeeld Onderwijsindustrie.

   ![](assets/image2015-1-19-17-3a18-3a13.png)

1. Selecteer alle andere advertentieopties, stel uw budget in en definieer uw advertentiefilters.

   ![](assets/image2015-1-19-17-3a19-3a25.png)

1. U bent nu allemaal ingesteld met een gepersonaliseerde marketingcampagne in [!DNL Facebook] .

>[!MORELIKETHIS]
>
>* [&#x200B; het opnieuw samenkomen met de Gegevens van Personalization van het Web &#x200B;](/help/marketo/product-docs/web-personalization/website-retargeting/retargeting-with-web-personalization-data.md)
>* [&#x200B; Gepersonaliseerde Markering in Google &#x200B;](/help/marketo/product-docs/web-personalization/website-retargeting/personalized-remarketing-in-google.md)
