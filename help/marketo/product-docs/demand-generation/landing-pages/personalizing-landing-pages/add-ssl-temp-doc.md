---
description: SSL toevoegen aan uw bestemmingspagina's - Marketo Docs - Productdocumentatie
title: SSL toevoegen aan uw bestemmingspagina's
hide: true
hidefromtoc: true
feature: Landing Pages
exl-id: 00ec2d91-3d4f-4671-af9d-9750c1642d40
source-git-commit: 1112af01c08835876f4a2385f304a33e2ddd48ff
workflow-type: tm+mt
source-wordcount: '313'
ht-degree: 0%

---

# SSL toevoegen aan uw bestemmingspagina&#39;s {#add-ssl-to-your-landing-pages}

Met SSL-codering (Secure Socket Layer) kunt u al uw bestemmingspagina&#39;s voor een Marketo Engage-instantie beveiligen.

Wanneer u een webformulier invult of een bestemmingspagina bezoekt die wordt gehost door Marketo Engage, wordt de informatie standaard verzonden via een niet-beveiligd protocol (HTTP). Volgens het beleid van uw bedrijf wilt u mogelijk de gegevens beveiligen die via HTTPS aan Marketo worden verzonden. Wanneer u bijvoorbeeld `http://info.mydomain.com/` bezoekt, wordt dit nu `https://info.mydomain.com/` .

Marketo Engage houdt standaard &quot;Bezochte webpagina&quot; en &quot;Klik op Koppeling op webpagina&quot; bij via een niet-beveiligd HTTP-protocol. Als u de trackingkoppelingen wilt beveiligen met een eigen certificaat, moet u Marketo een aparte, niet-gedeelde server laten bouwen om deze in te schakelen. Om alle aspecten van de interactie van een contact met u te beveiligen betekent typisch het beveiligen van zowel het Landen Pagina&#39;s als het volgen van verbindingen.

SCREENSHOT

## SSL-certificering inschakelen {#enable-ssl-certification}

Voeg automatisch SSL toe voor alle domeinaliassen die u maakt als onderdeel van de regels voor de landingspagina.

1. Ga naar het **Admin** gebied.

   SCREENSHOT

1. Selecteer **het Bestaan Pagina&#39;s** van de boom. In het **lusje van Regels**, klik **Nieuwe** drop-down en selecteer **Nieuwe Alias van het Domein**.

   SCREENSHOT

1. Selecteer **produceren SSL Certificaat** checkbox.

   SCREENSHOT

Hiermee wordt automatisch een SSL-certificaat voor dit domein toegevoegd.

SCREENSHOT

## SSL inschakelen voor uw standaarddomein {#enable-ssl-default-domain}

SCREENSHOT

>[!NOTE]
>
>* In de kolom SSL-certificaat in de lijst wordt de certificaatstatus weergegeven voor alle domeinalias die is gemaakt nadat deze functie is uitgebracht (DATE). Als de SSL voor een domein via Marketo Support is ingeschakeld, blijft het certificaat bestaan, maar wordt het niet weergegeven in de tabel. In deze tabel worden alleen SSL-certificaten weergegeven voor domeinen die zijn toegevoegd met de stappen in dit artikel.
>
>* Het kan maximaal drie minuten duren voordat de status van SSL READY is ingeschakeld. De wijzigingen worden alleen weergegeven als u de pagina vernieuwt.
