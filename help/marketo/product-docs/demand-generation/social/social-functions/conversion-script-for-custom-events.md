---
unique-page-id: 2950561
description: Conversiescript voor Aangepaste gebeurtenissen - Marketo Docs - Productdocumentatie
title: Conversiescript voor aangepaste gebeurtenissen
translation-type: tm+mt
source-git-commit: 074701d1a5f75fe592ac7f44cce6fb3571e94710
workflow-type: tm+mt
source-wordcount: '276'
ht-degree: 0%

---


# Conversiescript voor aangepaste gebeurtenissen {#conversion-script-for-custom-events}

U bepaalt het doel van de vervulling wanneer het creëren van een verwijzingsaanbieding. Als de actie die telt om het doel te bereiken een specifieke gebeurtenis op uw eigen Web-pagina is, kunt u een omzettingsmanuscript gebruiken om onze JavaScript API te roepen.

## Het conversiescript {#retrieve-the-conversion-script} ophalen

1. Klik in de editor voor de verwijzingsaanbieding op **Details aanbieden** en selecteer **JavaScript-gebeurtenis van klant** in de vervolgkeuzelijst voor het uitvoeringsdoel.

   ![](assets/image2015-4-20-17-3a22-3a15.png)

1. Kopieer het bovenste script in het grijze vak en plaats het binnen de `<body>`-tags op uw webpagina. Het onderste script wordt binnen de `<header>`-tags geplaatst.

   ![](assets/image2015-4-20-17-3a29-3a7.png)

   >[!NOTE]
   >
   >Vergeet niet beide scripts te kopiëren en te plakken als ze naar een niet-Marketo-website gaan.

## Het Loader-script {#retrieve-the-loader-script} ophalen

1. Selecteer de verwijzingsaanbieding van de boom, dan klik **Verwijzingsaanbiedingen Acties** en **bed Code** in.

   ![](assets/image2015-4-20-17-3a34-3a46.png)

1. Klik met de rechtermuisknop op **Koptekstcode** en voeg deze in de koptekst van de webpagina in. Dan doe het zelfde voor **Code van het Lichaam**.

   ![](assets/image2015-4-20-20-3a49-3a19.png)

## Scripts op uw webpagina plakken {#pasting-the-scripts-onto-your-webpage}

Plak de conversiescripts in de HTML voor de hoofdtekst en koptekst. Plaats vervolgens de lader-scripts voor de hoofdtekst en koptekst in de HTML.

![](assets/image2015-4-20-21-3a0-3a16.png)

## Conversiescript {#connecting-the-conversion-script} verbinden

Hier schrijft u een JavaScript-functie die de specifieke HTML-id gebruikt van het pagina-element waarop u de voltooiing van het doel wilt activeren. Bijvoorbeeld:

`<pre><em><!-- Referral offer conversion script --></em> <script> cf_scripts.afterload(function (){ jQuery("#myButtonId").click(function (){ CF.insight.conversion(); }); }); </script></pre>` `<pre>`

In dit voorbeeld bevindt zich een knop op de webpagina met de id &quot;#myButtonId&quot;. Wanneer op die knop wordt geklikt, wordt de persoon geregistreerd dat hij het doel heeft bereikt.

Geweldig! Op uw website worden nu aangepaste doelen voor sociale bevordering vastgelegd met Marketo.

>[!MORELIKETHIS]
>
>* [Doel voor doorverwijzing opgeven](/help/marketo/product-docs/demand-generation/social/referral-offers/specify-goal-for-referral-offer.md)
>* [Verwijzingsvoorstel maken](/help/marketo/product-docs/demand-generation/social/referral-offers/create-a-referral-offer.md)
>* [Sociaal op uw website implementeren](/help/marketo/product-docs/demand-generation/social/social-functions/deploy-social-on-your-website.md)

