---
unique-page-id: 2950561
description: Conversiescript voor Aangepaste gebeurtenissen - Marketo Docs - Productdocumentatie
title: Conversiescript voor aangepaste gebeurtenissen
translation-type: tm+mt
source-git-commit: 1a29614ec938074902af201b2ffc11cfaa625f7a
workflow-type: tm+mt
source-wordcount: '280'
ht-degree: 0%

---


# Conversiescript voor aangepaste gebeurtenissen {#conversion-script-for-custom-events}

U bepaalt het doel van de vervulling wanneer het creëren van een verwijzingsaanbieding. Als de actie die telt om het doel te bereiken een specifieke gebeurtenis op uw eigen Web-pagina is, kunt u een omzettingsmanuscript gebruiken om onze JavaScript API te roepen.

## Conversiescript ophalen {#retrieve-the-conversion-script}

1. Klik in de editor voor de verwijzingsaanbieding op **Aanbiedingsgegevens** en selecteer JavaScript-gebeurtenis **van** klant in de vervolgkeuzelijst voor het uitvoeringsdoel.

   ![](assets/image2015-4-20-17-3a22-3a15.png)

1. Kopieer het bovenste script in het grijze vak en plaats het binnen de `<body>` tags op de webpagina. Het onderste script wordt binnen de `<header>` tags geplaatst.

   ![](assets/image2015-4-20-17-3a29-3a7.png)

   >[!NOTE]
   >
   >**Herinnering**
   >
   >
   >Vergeet niet beide scripts te kopiëren en te plakken als ze naar een niet-Marketo-website gaan.

## Het Loader-script ophalen {#retrieve-the-loader-script}

1. Selecteer de verwijzingsaanbieding van de boom, dan klik de Acties **van de Aanbieding van de Verwijzing en** bedt Code **** in.

   ![](assets/image2015-4-20-17-3a34-3a46.png)

1. Klik met de rechtermuisknop op de **koptekstcode** en voeg deze in de koptekst van de webpagina in. Doe dan het zelfde voor de Code **van het** Lichaam.

   ![](assets/image2015-4-20-20-3a49-3a19.png)

## Scripts op uw webpagina plakken {#pasting-the-scripts-onto-your-webpage}

Plak de conversiescripts in de HTML voor de hoofdtekst en koptekst. Plaats vervolgens de lader-scripts voor de hoofdtekst en koptekst in de HTML.

![](assets/image2015-4-20-21-3a0-3a16.png)

## Conversiescript verbinden {#connecting-the-conversion-script}

Hier schrijft u een JavaScript-functie die de specifieke HTML-id gebruikt van het pagina-element waarop u de voltooiing van het doel wilt activeren. Bijvoorbeeld:

`<pre><em><!-- Referral offer conversion script --></em> <script> cf_scripts.afterload(function (){ jQuery("#myButtonId").click(function (){ CF.insight.conversion(); }); }); </script></pre>` `<pre>`

In dit voorbeeld bevindt zich een knop op de webpagina met de id &quot;#myButtonId&quot;. Wanneer op die knop wordt geklikt, wordt de persoon geregistreerd dat hij het doel heeft bereikt.

Geweldig! Op uw website worden nu aangepaste doelen voor sociale bevordering vastgelegd met Marketo.

>[!NOTE]
>
>**Verwante artikelen**
>
>* [Doel voor doorverwijzing opgeven](../../../../product-docs/demand-generation/social/referral-offers/specify-goal-for-referral-offer.md)
>* [Verwijzingsvoorstel maken](../../../../product-docs/demand-generation/social/referral-offers/create-a-referral-offer.md)
>* [Sociaal op uw website implementeren](deploy-social-on-your-website.md)

