---
unique-page-id: 2359746
description: Pas uw bestemmingspagina-URL's aan met een CNAME - Marketo Docs - Productdocumentatie
title: De URL's van uw bestemmingspagina aanpassen met een CNAME
exl-id: 2cd87785-61e5-46cd-b1e0-6fbc145014d4
feature: Landing Pages
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '228'
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

## Je Munchkin-id zoeken {#find-your-munchkin-id}

1. Ga naar het **Admin** gebied.

   ![](assets/customize-your-landing-page-urls-with-a-cname-1.png)

1. Klik **Mijn Rekening**.

   ![](assets/customize-your-landing-page-urls-with-a-cname-2.png)

   >[!NOTE]
   >
   >**Vereiste Bevoegdheden Admin**

1. Blader omlaag naar &quot;Ondersteuningsinformatie&quot; en kopieer uw Munchkin-id.

   ![](assets/customize-your-landing-page-urls-with-a-cname-3.png)

## Verzoek verzenden naar IT {#send-request-to-it}

Vraag uw personeel van IT om volgende CNAME in te stellen: (Vervang het woord [ CNAME ] en [ identiteitskaart van Munchkin ] met de tekst van de vorige stap.)

[ .YourCompany.com ] identiteitskaart van Munchkin [ .mktoweb.com]

## CNAME-instelling voltooien {#complete-cname-setup}

1. Zodra uw IT CNAME heeft gecreeerd, ga naar het **Admin** gebied.

   ![](assets/customize-your-landing-page-urls-with-a-cname-4.png)

1. Klik **het Bestaan Pagina&#39;s**.

   ![](assets/customize-your-landing-page-urls-with-a-cname-5.png)

1. Onder de **sectie van Montages**, geeft de klik **&#x200B;**&#x200B;uit.

   ![](assets/customize-your-landing-page-urls-with-a-cname-6.png)

1. Voer uw CNAME in **[!UICONTROL Domain name for Landing Pages]** in, voer uw **[!UICONTROL Fallback page]** in, voer uw **[!UICONTROL Homepage]** in en klik op **[!UICONTROL Save]** .

   ![](assets/customize-your-landing-page-urls-with-a-cname-7.png)

>[!NOTE]
>
>De fallback-pagina is de pagina waarnaar de leads worden omgeleid als de Marketo Landing Page niet beschikbaar is.

Mooi werk! De landingspagina&#39;s zijn nu gecodeerd met uw bedrijfsdomein.
