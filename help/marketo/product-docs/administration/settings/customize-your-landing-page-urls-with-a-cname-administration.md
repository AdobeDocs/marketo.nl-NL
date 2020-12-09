---
unique-page-id: 2360189
description: De URL's van uw bestemmingspagina aanpassen met een CNAME (Beheer) - Marketo Docs - Productdocumentatie
title: De URL's van uw bestemmingspagina aanpassen met een CNAME (Beheer)
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '251'
ht-degree: 0%

---


# De URL&#39;s van uw bestemmingspagina aanpassen met een CNAME (Beheer) {#customize-your-landing-page-urls-with-a-cname-administration}

Alhoewel Marketo uw landingspagina&#39;s bewaart, zou URL voor uw bedrijf moeten worden aangepast.

>[!NOTE]
>
>Geen CNAME:
>
>https://na-sj02.marketo.com/lp/mktodemoaccount126/UnsubscribePage.html
>
>merknaam:
>
>https://go.**Uw bedrijf**.com/UnsuscribePage.html

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

Laten we je oprichten!

1. Kies een NAAM.

   Het is het eerste deel van de URL. Voorbeelden:

   * **Ga naar**.YourCompany.com/NameOfPage.html
   * **info**.YourCompany.com/NameOfPage.html
   * **pagina**.YourCompany.com/NameOfPage.html

   Het ene woord (plus YourCompany.com) wordt een CNAME genoemd. U hebt dit later nodig, dus noteer het.

1. Zoek de tekenreeks van uw account.

1. Ga naar het **beheergebied** en klik op **Pagina&#39;s** landen.

   ![](assets/image2014-9-16-13-3a9-3a44.png)

1. Kopieer onder het tabblad **Landingpagina** de accounttekenreeks uit het gedeelte Instellingen.

   ![](assets/image2014-9-16-13-3a9-3a57.png)

1. U hebt dit later ook nodig, dus noteer het.

1. Verzoek naar IT verzenden.

1. Vraag uw personeel van IT om volgende CNAME (vervang het woord [CNAME] en de TEKENREEKS [van de] REKENING door de tekst van de vorige stap) te plaatsen:

   [CNAME].YourCompany.com > [ACCOUNT STRING].mktoweb.com

1. Volledige CNAME-instelling.

1. Als uw IT-afdeling de CNAME heeft gemaakt, gaat u naar **Admin** en klikt u op **Landing Pages**.

   ![](assets/image2014-9-16-13-3a10-3a14.png)

1. Klik onder de sectie **Instellingen** op **Bewerken**.

   ![](assets/image2014-9-16-13-3a10-3a31.png)

1. Ga uw NAAM in de naam van het **Domein voor het Bestaan van Pagina**&#39;s in, ga uw pagina **van de** Fallback in, ga uw **Homepage** in, en klik **sparen**.

   ![](assets/image2014-9-16-13-3a10-3a45.png)

Je fallback-pagina is waar mensen omgeleid worden als je bestemmingspagina Marketo niet beschikbaar is.

Mooi werk! De landingspagina&#39;s zijn nu gecodeerd met uw bedrijfsdomein.
