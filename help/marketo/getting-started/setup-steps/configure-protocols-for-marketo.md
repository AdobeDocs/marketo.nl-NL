---
unique-page-id: 4720433
description: Protocollen configureren voor Marketo - Marketo Docs - Productdocumentatie
title: Protocollen voor Marketo configureren
exl-id: cf2fd4ac-9229-4e52-bb68-5732b44920ef
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '712'
ht-degree: 1%

---

# Protocollen configureren voor Marketo {#configure-protocols-for-marketo}

Uw marketinggroep maakt gebruik van Marketo om pagina&#39;s en e-mails met brandingcampagne te maken. Om ervoor te zorgen dat die landingspagina&#39;s en e-mails werken, hebben ze een beetje hulp van IT nodig. Stel de volgende protocollen in met de informatie die uw marketinggroep u per e-mail had moeten sturen.

Dit artikel zou met de afdeling van IT van het bedrijf moeten worden gedeeld die deze protocollen willen uitvoeren.

>[!NOTE]
>
>Als uw team van IT Webtoegang gebruikend een lijst van gewenste personen beperkt, vraag hen om de volgende domeinen (met inbegrip van de asterisk) toe te voegen om alle middelen en websockets van Marketo toe te staan:

* `*.marketo.com`

* `*.marketodesigner.com`

* `*.mktoweb.com`

## Stap 1: DNS-records maken voor bestemmingspagina&#39;s en e-mail {#step-create-dns-records-for-landing-pages-and-email}

**KoppelingsNAMEN bijhouden**

Uw marketing team zou u twee verzoeken om nieuwe verslagen van CNAME moeten hebben verzonden. De eerste is voor het landen van pagina URLs, zodat de landende pagina&#39;s in URLs verschijnen die uw domein en niet Marketo (de daadwerkelijke gastheer) weerspiegelen. De tweede is voor de trackingkoppelingen die zijn opgenomen in de e-mails die ze van Marketo verzenden.

`1` **CNAME toevoegen voor bestemmingspagina&#39;s**

Voeg de bestemmingspagina CNAME toe die zij u naar uw DNS verslag hebben verzonden, zodat `[YourLandingPageCNAME]` aan het unieke Koord van de Rekening richt dat aan uw Marketo landende pagina&#39;s wordt toegewezen. Meld u aan bij de site van uw domeinregistrar en voer de landingspagina CNAME en accounttekenreeks in. Dit betreft meestal drie velden:

* Alias: Voer `[YourLandingPageCNAME]` in (opgegeven door marketing)
* Type: CNAME
* Wijs aan: Voer `[MarketoAccountString].mktoweb.com` in (opgegeven door marketing)

`2` **CNAME toevoegen voor koppelingen voor e-mailtracking**

Voeg de e-mailmarketing toe die u van CNAME, zodat `[YourEmailCNAME]` richt aan [MktoTrackingLink], de standaard het volgen verbinding die Marketo, in het formaat toewees:\
`[YourEmailCNAME].[YourDomain].com` IN CNAME  `[MktoTrackingLink]`

Bijvoorbeeld:

`pages.abc.com IN CNAME mkto-a0244.com`

`3` **Uw marketingteam op de hoogte stellen**

Melden aan uw marketingteam wanneer u dit proces hebt voltooid.

## Stap 2: Marketo IP&#39;s van de Lijst van gewenste personen {#step-allowlist-marketo-ips}

Als uw marketinggroep Marketo gebruikt om teste-mails te verzenden (een aanbevolen werkwijze voordat e-mailberichten worden verzonden), worden de e-mails over de test soms geblokkeerd door anti-spamsystemen die afhankelijk zijn van IP-adressen van de afzender om te controleren of de e-mail geldig is. Voeg Marketo toe aan uw lijst van gewenste personen om ervoor te zorgen dat deze teste-mails arriveren.

Voeg deze IP adressen aan uw collectieve lijst van gewenste personen toe:

199.15.212.0/22\
192.28.144.0/20
192.28.160.0/19\
185.28.196.0/22\
130.248.172.0/24\
130.248.173.0/24\
103.237.104.0/22\
94.236.119.0/26

Sommige anti-anti-spamsystemen gebruiken het terug-weg van de e-mail gebied in plaats van het IP adres voor het toewijzen. In die gevallen, is de beste benadering lijst van gewenste personen &quot;*.mktomail.com&quot;, aangezien Marketo verscheidene brievenbussubdomeinen gebruikt. Andere anti-spamsystemen lijst van gewenste personen die op Van adres wordt gebaseerd. In deze situaties, ben zeker om alle verzendende (&quot;van) domeinen te omvatten die uw groep van de Marketing gebruikt om met mensen/leiders te communiceren.

>[!NOTE]
>
>Postini gebruikt een unieke technologie en vereist voegende op lijst van gewenste personen IP waaiers. Zie [Voegend op lijst van gewenste personen met Postini](https://nation.marketo.com/docs/DOC-1066).

## Stap 3: SPF en DKIM instellen {#step-set-up-spf-and-dkim}

Uw marketingteam had u ook DKIM-informatie moeten sturen die u wilt toevoegen aan uw DNS-resourcerecord (ook hieronder vermeld). Volg de stappen om DKIM en SPF met succes te vormen, dan uw marketing team mee te delen dat dit is bijgewerkt.

1. Aan opstelling SPF, voeg de volgende lijn aan onze DNS ingangen toe:

   `[CompanyDomain]` IN TXT v=spf1 mx ip4:`[CorpIP]`\
   omvatten: mktomail.com ~all

   Als wij reeds een bestaand SPF- verslag in onze DNS ingang hebben, voeg eenvoudig het volgende aan het toe:\
   omvatten: mktomail.com

   CompanyDomain vervangen door het hoofddomein van uw website (bijvoorbeeld: &quot;`(company.com/)`&quot;) en CorpIP met het IP adres van uw collectieve e-mailserver (bv. &quot;255.255.255.255&quot;). Als u e-mail van veelvoudige domeinen door Marketo gaat verzenden, zou u uw personeel van IT deze lijn voor elk domein (op één lijn) moeten hebben toevoegen.

1. Voor DKIM, creeer DNS Verslagen van het Middel voor elk domein wij zouden willen opstelling. Hieronder zijn de Verslagen van de Gastheer en de Waarden TXT voor elk domein wij zullen ondertekenen voor:

   `[DKIMDomain1]`: Hostrecord is  `[HostRecord1]` en de TXT-waarde is  `[TXTValue1]`.

   `[DKIMDomain2]`: Hostrecord is  `[HostRecord2]` en de TXT-waarde is  `[TXTValue2]`.

   Kopieer HostRecord en TXTValue voor elke DKIMDomain u opstelling na het volgen van [instructies hier](/help/marketo/product-docs/email-marketing/deliverability/set-up-a-custom-dkim-signature.md) hebt. Vergeet niet om elk domein in Admin > E-mail > DKIM te verifiëren nadat uw personeel van IT deze stap heeft voltooid.

## Stap 4: MX-records instellen voor uw domein {#step-set-up-mx-records-for-your-domain}

Met een MX-record kunt u e-mail ontvangen naar het domein waarvan u e-mail verzendt om reacties en auto-responders te verwerken. Als u vanuit uw bedrijfsdomein verzendt, is dit waarschijnlijk al geconfigureerd. Als niet, kunt u het gewoonlijk plaatsen aan kaart aan het MX verslag van uw collectief domein.
