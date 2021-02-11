---
unique-page-id: 14352407
description: Overzicht van het leveringskanaal - Marketo Docs - Productdocumentatie
title: Overzicht van leveringskanaal
translation-type: tm+mt
source-git-commit: 1dd80b7de801df78ac7dde39002455063f9979b7
workflow-type: tm+mt
source-wordcount: '456'
ht-degree: 0%

---


# Overzicht leveringskanaal {#delivery-channel-overview}

We verdelen de drie verschillende kanalen waarop u een beroep kunt doen, hoe u ze kunt selecteren, wanneer u elkaar wilt selecteren en welke nuances er omheen staan.

>[!NOTE]
>
>Deze informatie is alleen relevant als u uw e-mails verzendt via de [webtoepassing](https://toutapp.com/login). Als u Sales Connect in Gmail of Outlook gebruikt, worden uw e-mailberichten via deze e-mailservers verzonden.

## MSC-e-mailservers (standaard) {#msc-email-servers-default}

Deze methode wordt standaard geselecteerd voor het verzenden van e-mails. MSC-e-mailservers zijn een goede optie voor gebruikers die geen Gmail of Outlook gebruiken. Bovendien, omdat zij onze servers zijn, hebben wij de capaciteit om het even welke foutenmeldingen betreffende stuitingen of mislukte leveringen te nemen en hen tot u in de &quot;Mislukte sectie van Leveringen&quot;van het lusje van Gesprek te oppervlakte.

Een ander voordeel van het gebruiken van de servers MSC is, wanneer het gebruiken van [E-mailIdentiteit](/help/marketo/product-docs/marketo-sales-connect/getting-started/email-settings/add-identity.md), zal de ontvanger het e-mailadres van de identiteit zien u hebt gecreeerd.

Wanneer u MSC-servers gebruikt, zien uw ontvangers mogelijk een tag &quot;via toutapp.com&quot;. Dit is hun e-mailclient die hen laat weten dat de e-mail is verzonden via Sales Connect.

Raadpleeg voor meer informatie dit [Gmail Help-artikel](https://support.google.com/mail/answer/1311182?hl=en).

>[!NOTE]
>
>Onze MSC-servers hebben geen [DMARC-record](https://dmarc.org/) die beschikbaar is gesteld. Ze kunnen niet op uw eigen servers worden gewhitelist.

## Gmail-server {#gmail-server}

Als de e-mailprovider van uw bedrijf Gmail is, kunt u uw bestaande account gebruiken om uw e-mails over Verkoopmanager Connect te verzenden. Dit is een goede optie als u de &quot;via toutapp.com&quot;informatie wilt vermijden, en als u van de reputatie van uw bedrijf het domein en de leverbaarheid zou verkiezen afhankelijk te zijn. Een extra voordeel van het gebruik van een Gmail-server is dat alles wat u uit de webtoepassing verzendt, automatisch wordt toegevoegd aan de Gmail-map die u verzendt.

We kunnen slechts verbinding maken met één Gmail-account (één e-mailadres) waarmee uw e-mails over Verkoopverbinding worden geleverd. Dit betekent dat als u meerdere e-mailidentiteiten gebruikt, alleen het adres van het account waarmee we verbonden zijn, wordt weergegeven wanneer u de details bekijkt.

In de webtoepassing wordt uw identiteit weergegeven zoals u deze hebt gemaakt (hierboven). Als u echter via Gmail-servers verzendt, wordt het adres van de verbonden account weergegeven.

>[!NOTE]
>
>Aangezien Sales Connect uw Gmail-servers niet rechtstreeks beheert, nemen we geen bekende e-mailgebeurtenissen op in de webtoepassing.

## Aangepaste SMTP-server {#custom-smtp-server}

Betaal voor je eigen server? Een Microsoft Exchange-omgeving gebruiken? Dit is een optie voor u. Raadpleeg [deze instructies](http://docs.marketo.com/x/zYTS) bij het starten. Net als Gmail-servers kunnen we, aangezien Sales Connect uw server niet rechtstreeks beheert, geen teruggestuurde e-mailgebeurtenissen opnemen in de webtoepassing.
