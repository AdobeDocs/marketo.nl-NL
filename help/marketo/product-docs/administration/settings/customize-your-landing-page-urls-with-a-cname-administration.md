---
unique-page-id: 2360189
description: De URL's van uw bestemmingspagina aanpassen met een CNAME (Administration) - Marketo Docs - Productdocumentatie
title: De URL's van uw bestemmingspagina aanpassen met een CNAME (Beheer)
exl-id: a5aa1c76-15f7-4e8c-a736-77c79f65c368
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '251'
ht-degree: 0%

---

# De URL&#39;s van uw bestemmingspagina aanpassen met een CNAME (Beheer) {#customize-your-landing-page-urls-with-a-cname-administration}

Hoewel Marketo uw landingspagina&#39;s host, moet de URL voor uw bedrijf worden aangepast.

>[!NOTE]
>
>Geen CNAME:
>
>https://na-sj02.marketo.com/lp/mktodemoaccount126/UnsubscribePage.html
>
>merknaam:
>
>https://go.**YourCompany**.com/UnsuscribePage.html

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

Laten we je oprichten!

1. Kies een NAAM.

   Het is het eerste deel van de URL. Voorbeelden:

   * **gaan**.YourCompany.com/NameOfPage.html
   * **info**.YourCompany.com/NameOfPage.html
   * **pagina&#39;s**.YourCompany.com/NameOfPage.html

   Het ene woord (plus YourCompany.com) wordt een CNAME genoemd. U hebt dit later nodig, dus noteer het.

1. Zoek de tekenreeks van uw account.

1. Ga naar de **Beheer** gebied en klik op **Openingspagina&#39;s**.

   ![](assets/image2014-9-16-13-3a9-3a44.png)

1. Onder de **Openingspagina&#39;s** , kopieert u de tekenreeks Account vanuit het gedeelte Instellingen.

   ![](assets/image2014-9-16-13-3a9-3a57.png)

1. U hebt dit later ook nodig, dus noteer het.

1. Verzoek naar IT verzenden.

1. Vraag uw personeel van IT om volgende CNAME (vervang het woord [CNAME] en [ACCOUNTTEKENREEKS] met de tekst van de vorige stap):

   [CNAME].YourCompany.com > [ACCOUNTTEKENREEKS].mktoweb.com

1. Volledige CNAME-instelling.

1. Als uw IT-afdeling de CNAME heeft gemaakt, gaat u naar **Beheer** en klik op **Openingspagina&#39;s**.

   ![](assets/image2014-9-16-13-3a10-3a14.png)

1. Onder de **Instellingen** sectie, klikt u op **Bewerken**.

   ![](assets/image2014-9-16-13-3a10-3a31.png)

1. Voer uw CNAME in **Domeinnaam voor bestemmingspagina&#39;s**, voer uw **Pagina voor alternatieven**, voer uw **Homepage** en klik op **Opslaan**.

   ![](assets/image2014-9-16-13-3a10-3a45.png)

Je fallback-pagina is waar mensen worden omgeleid als je Marketo-landingspagina niet beschikbaar is.

Mooi werk! De landingspagina&#39;s zijn nu gecodeerd met uw bedrijfsdomein.
