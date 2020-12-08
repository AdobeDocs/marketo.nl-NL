---
unique-page-id: 10092925
description: Een webcampagne voorvertonen en testen - Marketo Docs - Productdocumentatie
title: Een webcampagne voorvertonen en testen
translation-type: tm+mt
source-git-commit: 00887ea53e395bea3a11fd28e0ac98b085ef6ed8
workflow-type: tm+mt
source-wordcount: '378'
ht-degree: 0%

---


# Een webcampagne voorvertonen en testen {#preview-and-test-a-web-campaign}

In dit artikel worden verschillende manieren getoond waarop u een webcampagne kunt voorvertonen en ook hoe u deze kunt testen met behulp van een sandboxsegment dat live op uw website staat.

## Een webcampagne voorvertonen op de ontwerppagina {#preview-a-web-campaign-on-the-creation-page}

1. Ga naar **webcampagnes** **voor meer informatie**.

   ![](assets/image2016-8-18-15-3a59-3a35.png)

1. Klik op** Nieuwe webcampagne maken****** of op het pictogram om een bestaande campagne te bewerken.

   ![](assets/create-new-or-edit-web-campaign.png)

1. Voeg de pagina-URL toe in Voorvertonen op de site en klik op **Voorvertoning**. Er wordt een nieuw venster of tabblad geopend met de voorvertoning van de campagne.

   ![](assets/three-1.png)

   >[!TIP]
   >
   >Klik op **Delen** om een e-mail te openen met een vaste URL van de voorvertoning van de campagne.

   >[!NOTE]
   >
   >U kunt ook een browserplug-in ( [Chrome](https://chrome.google.com/webstore/detail/marketo-web-personalizati/ldiddonjplchallbngbccbfdfeldohkj) of [Firefox](http://docs.marketo.com/display/docs/assets/mwp-0.0.0.8.xpi)) installeren voor een optimale ervaring bij het voorvertonen van uw campagne. Zie de onderstaande paragraaf.

## Een webcampagne voorvertonen op de pagina Maken met de plug-in Browser {#preview-a-web-campaign-on-the-creation-page-using-the-browser-plug-in}

1. Voer stap 1 en 2 uit het `section above`deelvenster uit.
1. Klik op de koppeling naar de browserplug-in (in dit geval gebruiken we Chrome).

   ![](assets/4-1.png)

1. Er wordt een nieuw venster/tabblad geopend. Klik op **Toevoegen aan chroom**.

   ![](assets/five.png)

1. Klik op Extensie **toevoegen**.

   ![](assets/six.png)

1. Ga terug naar Marketo. Voeg de pagina-URL toe en klik op **Voorvertoning**.

   ![](assets/seven.png)

1. Er wordt een nieuw venster/tabblad geopend waarin u kunt zien hoe de campagne er op een bureaublad, telefoon of tablet uitziet.

   ![](assets/campaign-preview.png)

## Een webcampagne voorvertonen op de webpagina Campagnes {#preview-a-web-campaign-on-the-web-campaigns-page}

1. Als u de lijst met uw webcampagnes bekijkt, kiest u gewoon een campagne en klikt u op het pictogram **Voorvertoning** .

   ![](assets/web-campaigns-1-preview-hand.png)

   Eenvoudig!

## Een webcampagne voorvertonen op uw website {#preview-a-web-campaign-on-your-website}

Maak een sandboxsegment en -campagne.

1. Ga naar **Segmenten**.

   ![](assets/new-dropdown-segments-hand.jpg)

1. Klik op **Nieuw** maken.

   ![](assets/image2015-9-10-10-3a42-3a39.png)

1. Geef het segment een naam.
1. Sleep onder Gedrag de optie Inclusief pagina&#39;s naar het canvas. Voeg de waarde *sandbox=1* toe. Klik op Campagne opslaan en definiëren.

   ![](assets/segment.png)

1. Voor de Vastgestelde pagina van de Campagne van het Web, verander het Segment van het Doel in het zandbaksegment door het van de lijst te selecteren.

   ![](assets/set-web-campaign-target-segment.jpg)

1. Voltooi de creatieve campagne en klik op **Starten**.\
   ![](assets/click-launch.jpg)

1. Ga naar uw website en voeg de URL-parameter &quot;?sandbox=1&quot; toe aan het einde van de URL. Voorbeeld: [www.marketo.com?sandbox=1](http://www.marketo.com/?sandbox=1)
1. Bekijk de campagnereactie op uw website.

>[!NOTE]
>
>Campagnes reageren slechts eenmaal tijdens een bezoekerssessie. Wis de browsercookies om de campagne weer te zien.

>[!NOTE]
>
>Omleidingscampagnes kunnen niet worden voorvertoond. De enige manier om deze te testen is door een sandboxsegment te gebruiken (dat zich richt op specifieke pagina&#39;s - *sandbox=redirect*)

