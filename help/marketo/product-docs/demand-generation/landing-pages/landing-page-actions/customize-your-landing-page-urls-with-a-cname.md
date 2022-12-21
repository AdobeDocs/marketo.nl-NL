---
unique-page-id: 2359746
description: Pas uw bestemmingspagina-URL's aan met een CNAME - Marketo Docs - Productdocumentatie
title: De URL's van uw bestemmingspagina aanpassen met een CNAME
exl-id: 2cd87785-61e5-46cd-b1e0-6fbc145014d4
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '254'
ht-degree: 0%

---

# De URL&#39;s van uw bestemmingspagina aanpassen met een CNAME {#customize-your-landing-page-urls-with-a-cname}

Hoewel Marketo uw landingspagina&#39;s host, kan de URL volledig worden aangepast. Hoe ziet het eruit zonder een CNAME:

`https://na-sj02.marketo.com/lp/mktodemoaccount126/UnsubscribePage.html`

De manier waarop het eruit moet zien:

`https://go.YourCompany.com/UnsubscribePage.html`

## Een CNAME kiezen {#choose-a-cname}

Kies een woord om aan het begin van de URL te gaan voor de bestemmingspagina&#39;s. Het is maar één woord en zou relatief kort moeten zijn. Voorbeelden:

* go.YourCompany.com/NameOfPage.html
* info.YourCompany.com/NameOfPage.html
* pages.YourCompany.com/NameOfPage.html

Het ene woord (plus YourCompany.com) wordt een CNAME genoemd. U hebt dit later nodig, dus noteer het.

## De tekenreeks van uw account zoeken {#find-your-account-string}

1. Ga naar de **Beheer** gebied en klik op **Openingspagina&#39;s**.

   ![](assets/image2014-9-18-16-3a2-3a45.png)

   >[!NOTE]
   >
   >**Beheerdersmachtigingen vereist**

1. Onder de **Aanlanding** **Pagina&#39;s** kopiëren **Account** **String** van de **Instellingen** sectie.

   ![](assets/image2014-9-18-16-3a44-3a12.png)

1. U zult later ook nodig hebben, dus maak er een notitie van.

## Verzoek verzenden naar IT {#send-request-to-it}

Vraag uw personeel van IT om volgende CNAME te installeren: (Vervang het woord [CNAME] en [ACCOUNTTEKENREEKS] met de tekst uit de vorige stap.)

[CNAME].YourCompany.com > [ACCOUNTTEKENREEKS].mktoweb.com

## CNAME-instelling voltooien {#complete-cname-setup}

1. Als uw IT-afdeling de CNAME heeft gemaakt, gaat u naar **Beheer** en klik op **Openingspagina&#39;s**.

   ![](assets/image2014-9-18-17-3a15-3a11.png)

1. Onder de **Instellingen** sectie, klik op **Bewerken**.

   ![](assets/image2014-9-18-17-3a15-3a18.png)

1. Voer uw CNAME in **Domeinnaam voor bestemmingspagina&#39;s**, voer uw **Pagina voor alternatieven**, voer uw **Homepage** en klik op **Opslaan**.

   ![](assets/image2014-9-18-17-3a15-3a25.png)

>[!NOTE]
>
>De fallback-pagina is de pagina waarnaar de leads worden omgeleid als de Marketo Landing Page niet beschikbaar is.

Mooi werk! De landingspagina&#39;s zijn nu gecodeerd met uw bedrijfsdomein.
