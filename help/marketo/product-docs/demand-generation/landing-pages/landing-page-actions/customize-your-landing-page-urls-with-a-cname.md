---
unique-page-id: 2359746
description: Pas uw bestemmingspagina-URL's met een CNAME - Marketo Docs - Productdocumentatie aan
title: De URL's van uw bestemmingspagina aanpassen met een CNAME
translation-type: tm+mt
source-git-commit: 00887ea53e395bea3a11fd28e0ac98b085ef6ed8
workflow-type: tm+mt
source-wordcount: '273'
ht-degree: 0%

---


# De URL&#39;s van uw bestemmingspagina aanpassen met een CNAME {#customize-your-landing-page-urls-with-a-cname}

Hoewel Marketo uw landingspagina&#39;s host, kan de URL volledig worden aangepast. Hoe ziet het eruit zonder een CNAME:
`<pre data-theme="Confluence">http://na-sj02.marketo.com/lp/mktodemoaccount126/UnsubscribePage.html</pre>` De manier waarop het eruit moet zien:
`<pre data-theme="Confluence"> http://go.YourCompany.com/UnsubscribePage.html</pre>`

## Een CNAME kiezen {#choose-a-cname}

Kies een woord om aan het begin van de URL te gaan voor de bestemmingspagina&#39;s. Het is maar één woord en zou relatief kort moeten zijn. Voorbeelden:

* gaan. [YourCompany.com/NameOfPage.html](http://YourCompany.com/NameOfPage.html)
* info. [YourCompany.com/NameOfPage.html](http://YourCompany.com/NameOfPage.html)
* pagina&#39;s. [YourCompany.com/NameOfPage.html](http://YourCompany.com/NameOfPage.html)

Het ene woord (plus [YourCompany.com](http://YourCompany.com)) wordt een CNAME genoemd. U hebt dit later nodig, dus noteer het.

## De tekenreeks van uw account zoeken {#find-your-account-string}

1. Ga naar het **beheergebied** en klik op Pagina&#39;s **landen.**

   ![](assets/image2014-9-18-16-3a2-3a45.png)

   >[!NOTE]
   >
   >**Beheerdersmachtigingen vereist**

1. Kopieer onder het tabblad **Landing** **Pages** de **Account** - **tekenreeks** uit de sectie **Instellingen** .

   ![](assets/image2014-9-18-16-3a44-3a12.png)

1. U zult later ook nodig hebben, dus maak er een notitie van.

## Verzoek verzenden naar IT {#send-request-to-it}

Vraag uw personeel van IT om volgende CNAME te installeren: (Vervang het woord [CNAME] en REKENREEKS [] door de tekst uit de vorige stap.)

[CNAME]. [YourCompany.com](http://yourcompany.com/) > [ACCOUNT STRING]. [mktoweb.com](http://mktoweb.com/)

## CNAME-instelling voltooien {#complete-cname-setup}

1. Zodra uw IT CNAME heeft gecreeerd, ga naar **Admin** en klik op het **Landing** **Pagina**.

   ![](assets/image2014-9-18-17-3a15-3a11.png)

1. Klik onder de sectie **Instellingen** op **Bewerken**.

   ![](assets/image2014-9-18-17-3a15-3a18.png)

1. Ga uw NAAM in **Domein** **naam** **voor** het **Landen** **Pagina****** ******** **** in, ga uw Fallbackpage in, ga uwHomepage in en klikSave.

   ![](assets/image2014-9-18-17-3a15-3a25.png)

>[!NOTE]
>
>De fallback-pagina is de pagina waarnaar de leads worden omgeleid als de bestemmingspagina van Marketo niet beschikbaar is.

Mooi werk! De landingspagina&#39;s zijn nu gecodeerd met uw bedrijfsdomein.