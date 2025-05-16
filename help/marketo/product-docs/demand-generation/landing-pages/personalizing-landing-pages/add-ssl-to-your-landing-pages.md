---
unique-page-id: 2359828
description: SSL toevoegen aan uw bestemmingspagina's - Marketo Docs - Productdocumentatie
title: SSL toevoegen aan uw bestemmingspagina's
exl-id: 8271d9fe-0575-430c-97c7-407e4b78cf1d
feature: Landing Pages
source-git-commit: 7ec3687c0c16738805394377b2080295c2f18032
workflow-type: tm+mt
source-wordcount: '367'
ht-degree: 0%

---

# SSL toevoegen aan uw bestemmingspagina&#39;s {#add-ssl-to-your-landing-pages}

Met SSL-codering (Secure Socket Layer) kunt u al uw bestemmingspagina&#39;s voor een Marketo Engage-instantie beveiligen.

Wanneer u een webformulier invult of een bestemmingspagina bezoekt die door Marketo Engage wordt gehost, wordt de informatie standaard verzonden via een niet-beveiligd protocol (HTTP). Volgens het beleid van uw bedrijf wilt u mogelijk de gegevens beveiligen die via HTTPS aan Marketo worden verzonden. Wanneer u bijvoorbeeld `http://info.mydomain.com/` bezoekt, wordt dit nu `https://info.mydomain.com/` .

Marketo Engage houdt standaard &quot;Bezochte webpagina&quot; en &quot;Klik op Koppeling op webpagina&quot; bij via een niet-beveiligd HTTP-protocol. Als u de trackingkoppelingen wilt beveiligen met een eigen certificaat, moet u Marketo een aparte, niet-gedeelde server laten bouwen om deze in te schakelen. Om alle aspecten van de interactie van een contact met u te beveiligen betekent typisch het beveiligen van zowel het Landen Pagina&#39;s als het volgen van verbindingen.

## SSL-certificering inschakelen {#enable-ssl-certification}

Voeg automatisch SSL toe voor alle domeinaliassen die u maakt als onderdeel van de regels voor de landingspagina.

1. Ga naar het **Admin** gebied.

   ![](assets/add-ssl-to-your-landing-pages-1.png)

1. Selecteer **het Bestaan Pagina&#39;s** van de boom. In het **lusje van Regels**, klik **Nieuwe** drop-down en selecteer **Nieuwe Alias van het Domein**.

   ![](assets/add-ssl-to-your-landing-pages-2.png)

1. Ga uw _Alias van het Domein_ en _StandaardPagina_ in. Selecteer **produceren SSL Certificaat** checkbox. Klik **creëren** wanneer gedaan.

   ![](assets/add-ssl-to-your-landing-pages-3.png)

Hiermee wordt automatisch een SSL-certificaat voor dit domein toegevoegd.

## SSL inschakelen voor uw standaarddomein {#enable-ssl-default-domain}

Voer de onderstaande stappen uit om SSL in te schakelen voor uw standaarddomein.

1. Nog in de **Admin** sectie, uitgezochte **Landing Pagina&#39;s**. Klik de oranje **uitgeven** knoop naast _Montages_.

   ![](assets/add-ssl-to-your-landing-pages-4.png){width="800" zoomable="yes"}

   >[!NOTE]
   >
   >U kunt desgewenst ook de domeinnaam hier wijzigen (een geldig domein is vereist).

1. Schakel het selectievakje SSL-certificaat genereren in en klik op Opslaan.

   ![](assets/add-ssl-to-your-landing-pages-5.png)

>[!NOTE]
>
>* In de kolom SSL-certificaat in de lijst wordt de certificaatstatus weergegeven voor alle domeinalias die is gemaakt nadat deze functie is uitgebracht (DATE). Als de SSL voor een domein via Marketo Support is ingeschakeld, blijft het certificaat bestaan, maar wordt het niet weergegeven in de tabel. In deze tabel worden alleen SSL-certificaten weergegeven voor domeinen die zijn toegevoegd met de stappen in dit artikel.
>
>* Het kan maximaal drie minuten duren voordat de status van SSL READY is ingeschakeld. De wijzigingen worden alleen weergegeven als u de pagina vernieuwt.
