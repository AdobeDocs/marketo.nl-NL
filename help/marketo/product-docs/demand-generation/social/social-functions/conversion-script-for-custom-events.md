---
unique-page-id: 2950561
description: Conversiescript voor aangepaste gebeurtenissen - Marketo-documenten - Productdocumentatie
title: Conversiescript voor aangepaste gebeurtenissen
exl-id: 202b7e66-af83-42fd-8067-a5808eba7c32
feature: Social
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '276'
ht-degree: 0%

---

# Conversiescript voor aangepaste gebeurtenissen {#conversion-script-for-custom-events}

U bepaalt het doel van de vervulling wanneer het creëren van een verwijzingsaanbieding. Als de actie die telt om het doel te bereiken een specifieke gebeurtenis op uw eigen Web-pagina is, kunt u een omzettingsmanuscript gebruiken om onze JavaScript API te roepen.

## Conversiescript ophalen {#retrieve-the-conversion-script}

1. Klik in de editor met het verwijzingsaanbod op **Aanbiedingsgegevens** en selecteer vervolgens **JavaScript-gebeurtenis van klant** uit de vervolgkeuzelijst van het uitvoeringsdoel.

   ![](assets/image2015-4-20-17-3a22-3a15.png)

1. Kopieer het bovenste script in het grijze vak en plaats het op uw webpagina in het dialoogvenster `<body>` -tags. Het onderste script wordt geplaatst in het dialoogvenster `<header>` -tags.

   ![](assets/image2015-4-20-17-3a29-3a7.png)

   >[!NOTE]
   >
   >Vergeet niet beide scripts te kopiëren en te plakken als ze naar een niet-Marketo-website gaan.

## Het Loader-script ophalen {#retrieve-the-loader-script}

1. Selecteer het verwijzingsaanbod in de boomstructuur en klik vervolgens op **Verwijzingsvoorstellen** en **Code insluiten**.

   ![](assets/image2015-4-20-17-3a34-3a46.png)

1. Klik met de rechtermuisknop op de knop **Koptekstcode** en voeg het in uw webpaginakoptekst in. Doe dan het zelfde voor **Bodycode**.

   ![](assets/image2015-4-20-20-3a49-3a19.png)

## Scripts op uw webpagina plakken {#pasting-the-scripts-onto-your-webpage}

Plak de conversiescripts in de HTML voor de hoofdtekst en koptekst. Plaats vervolgens de lader-scripts in de HTML voor de hoofdtekst en koptekst.

![](assets/image2015-4-20-21-3a0-3a16.png)

## Conversiescript verbinden {#connecting-the-conversion-script}

Hier schrijft u een JavaScript-functie die de specifieke HTML-id gebruikt van het pagina-element waarop u de voltooiing van het doel wilt activeren. Bijvoorbeeld:

`<pre><em><!-- Referral offer conversion script --></em> <script> cf_scripts.afterload(function (){ jQuery("#myButtonId").click(function (){ CF.insight.conversion(); }); }); </script></pre>` `<pre>`

In dit voorbeeld bevindt zich een knop op de webpagina met de id &quot;#myButtonId&quot;. Wanneer op die knop wordt geklikt, wordt de persoon geregistreerd dat hij het doel heeft bereikt.

Geweldig! Op uw website worden nu aangepaste doelen voor sociale bevordering vastgelegd met Marketo.

>[!MORELIKETHIS]
>
>* [Doel voor doorverwijzing opgeven](/help/marketo/product-docs/demand-generation/social/referral-offers/specify-goal-for-referral-offer.md)
>* [Verwijzingsvoorstel maken](/help/marketo/product-docs/demand-generation/social/referral-offers/create-a-referral-offer.md)
>* [Sociaal op uw website implementeren](/help/marketo/product-docs/demand-generation/social/social-functions/deploy-social-on-your-website.md)
