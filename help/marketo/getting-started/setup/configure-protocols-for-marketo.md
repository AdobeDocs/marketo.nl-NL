---
unique-page-id: 4720433
description: Protocollen configureren voor Marketo - Marketo Docs - Productdocumentatie
title: Protocollen voor Marketo configureren
exl-id: cf2fd4ac-9229-4e52-bb68-5732b44920ef
feature: Getting Started
source-git-commit: 1152e81462fb77dd23ff57e26ded7f9b3c02c258
workflow-type: tm+mt
source-wordcount: '968'
ht-degree: 3%

---

# Protocollen voor Marketo configureren {#configure-protocols-for-marketo}

Als u of uw organisatie restrictieve firewall of proxyserverinstellingen gebruikt, moet u of uw netwerkbeheerder bepaalde domeinen en IP-adresbereiken lijsten van gewenste personen om ervoor te zorgen dat Adobe Marketo Engage naar behoren werkt.

Deel dit artikel met uw IT-afdeling voor hulp bij het implementeren van de onderstaande protocollen. Als deze webtoegang beperken via een lijst van gewenste personen, moet u ervoor zorgen dat de volgende domeinen (inclusief het sterretje) worden toegevoegd om alle Marketo-bronnen en -websockets toe te staan:

* `*.marketo.com`
* `*.marketodesigner.com`
* `*.mktoweb.com`
* `*.experience.adobe.com`
* `*.adobe.net`

## Stap 1: Maak DNS-records voor Landing Pages en e-mail {#step-create-dns-records-for-landing-pages-and-email}

**KoppelingsNAAM&#39;s bijhouden**

Uw marketing team zou u twee verzoeken om nieuwe verslagen van CNAME moeten hebben verzonden. De eerste is voor het landen van pagina URLs, zodat de landende pagina&#39;s in URLs verschijnen die uw domein en niet Marketo (de daadwerkelijke gastheer) weerspiegelen. De tweede is voor de trackingkoppelingen die zijn opgenomen in de e-mails die ze van Marketo verzenden.

`1` **CNAME toevoegen voor bestemmingspagina&#39;s**

Voeg de bestemmingspagina CNAME toe die zij u naar uw DNS verslag hebben verzonden, zodat `[YourLandingPageCNAME]` wijst naar de unieke tekenreeks Account die is toegewezen aan uw Marketo-bestemmingspagina&#39;s. Meld u aan bij de site van uw domeinregistrar en voer de landingspagina CNAME en accounttekenreeks in. Dit betreft meestal drie velden:

* Alias: Enter `[YourLandingPageCNAME]` (verstrekt door marketing)
* Type: CNAME
* Punt tot: Enter `[MunchkinID].mktoweb.com` (verstrekt door marketing)

`2` **CNAME toevoegen voor koppelingen voor e-mailtracking**

Voeg de e-mailmarketing toe die u van CNAME hebt ontvangen, zodat `[YourEmailCNAME]` punten naar [MktoTrackingLink], de standaardkoppeling voor bijhouden die Marketo heeft toegewezen, in de volgende notatie:\
`[YourEmailCNAME].[YourDomain].com` IN CNAME `[MktoTrackingLink]`

Bijvoorbeeld:

`pages.abc.com IN CNAME mkto-a0244.com`

>[!NOTE]
>
>`[MktoTrackingLink]` moet het standaardbrandingdomein zijn.

`3` **Uw marketingteam op de hoogte stellen**

Melden aan uw marketingteam wanneer u dit proces hebt voltooid.

`4` **Contact [Marketo-ondersteuning](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"} om het proces van levering van een SSL Certificaat te beginnen.**

Dit proces kan maximaal 3 werkdagen duren.

## Stap 2: Lijst van gewenste personen Marketo IPs {#step-allowlist-marketo-ips}

Als uw marketinggroep Marketo gebruikt om teste-mails te verzenden (een aanbevolen werkwijze voordat e-mailberichten worden verzonden), worden de e-mails over de test soms geblokkeerd door anti-spamsystemen die afhankelijk zijn van IP-adressen van de afzender om te controleren of de e-mail geldig is. Voeg Marketo toe aan uw lijst van gewenste personen om ervoor te zorgen dat deze teste-mails arriveren.

Voeg deze IP adressen aan uw collectieve lijst van gewenste personen toe:

94.236.119.0/26

103.237.104.0/22

130.248.172.0/24

130.248.173.0/24

130.248.244.88/29

185.28.196.0/22

192.28.144.0/20

192.28.160.0/19

199.15.212.0/22

Sommige anti-anti-spamsystemen gebruiken het terug-weg van e-mail gebied in plaats van het IP adres voor het toewijzen. In die gevallen is de beste aanpak lijst van gewenste personen &quot;&#42;.mktomail.com&#39;, aangezien Marketo verscheidene brievenbussubdomeinen gebruikt. Andere anti-spamsystemen lijst van gewenste personen die op Van adres wordt gebaseerd. In deze situaties, ben zeker om alle verzendende (&#39;van&#39;) domeinen te omvatten die uw groep van de Marketing gebruikt om met mensen/leiders te communiceren.

>[!NOTE]
>
>Postini gebruikt een unieke technologie en vereist voegende op lijst van gewenste personen IP waaiers. Zie [Voegend op lijst van gewenste personen maken met Postini](https://nation.marketo.com/docs/DOC-1066).

## Stap 3: Opstelling SPF en DKIM {#step-set-up-spf-and-dkim}

Uw marketingteam had u ook DKIM-informatie moeten sturen die u wilt toevoegen aan uw DNS-resourcerecord (ook hieronder vermeld). Volg de stappen om DKIM en SPF met succes te vormen, dan uw marketing team mee te delen dat dit is bijgewerkt.

1. Aan opstelling SPF, voeg de volgende lijn aan onze DNS ingangen toe:

   `[CompanyDomain]` IN TXT v=spf1 mx ip4:`[CorpIP]`\
   include: mktomail.com ~all

   Als wij reeds een bestaand SPF- verslag in onze DNS ingang hebben, voeg eenvoudig het volgende aan het toe:\
   include: mktomail.com

   CompanyDomain vervangen door het hoofddomein van uw website (bijvoorbeeld: &quot;`(company.com/)`&quot;) en CorpIP met het IP-adres van uw e-mailserver van uw bedrijf (bijvoorbeeld &quot;255.255.255.255&quot;). Als u e-mail van veelvoudige domeinen door Marketo gaat verzenden, zou u uw personeel van IT deze lijn voor elk domein (op één lijn) moeten hebben toevoegen.

1. Voor DKIM, creeer DNS Verslagen van het Middel voor elk domein wij opstelling zouden willen. Hieronder zijn de Verslagen van de Gastheer en de Waarden TXT voor elk domein wij zullen ondertekenen voor:

   `[DKIMDomain1]`: hostrecord is `[HostRecord1]` en de TXT-waarde is `[TXTValue1]`.

   `[DKIMDomain2]`: hostrecord is `[HostRecord2]` en de TXT-waarde is `[TXTValue2]`.

   Kopieer de waarden HostRecord en TXTV voor elke DKIMDomain u opstelling na het volgen van hebt [instructies hier](/help/marketo/product-docs/email-marketing/deliverability/set-up-a-custom-dkim-signature.md){target="_blank"}. Vergeet niet om elk domein in Admin > E-mail > DKIM te verifiëren nadat uw personeel van IT deze stap heeft voltooid.

## Stap 4: Opstelling MX Verslagen voor Uw Domein {#step-set-up-mx-records-for-your-domain}

Met een MX-record kunt u e-mail ontvangen naar het domein waarvan u e-mail verzendt om reacties en auto-responders te verwerken. Als u van uw collectief domein verzendt, hebt u waarschijnlijk reeds gevormd dit. Als niet, kunt u het gewoonlijk plaatsen aan kaart aan het MX verslag van uw collectief domein.

## Uitgaande IP Adressen {#outbound-ip-addresses}

Een uitgaande verbinding wordt gemaakt door het Marketo Engage naar een server op internet namens u. Sommige partners/verkopers u met, of uw eigen organisatie van IT werkt, kunnen lijsten van gewenste personen gebruiken om toegang tot servers te beperken. Als zo, moet u hen van Marketo Engage uitgaande IP adresblokken voorzien om aan hun lijsten van gewenste personen toe te voegen.

**Webhaken**

Marketo Engage [Webhaken](/help/marketo/product-docs/administration/additional-integrations/create-a-webhook.md){target="_blank"} are an outbound integration mechanism. When a [Call Webhook](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/call-webhook.md){target="_blank"} De stroomactie wordt uitgevoerd als deel van een slimme campagne, een HTTP- verzoek wordt gemaakt aan een externe Webdienst. Als de uitgever van de Webdienst een lijst van gewenste personen op de firewall van het netwerk gebruikt waar de externe Webdienst wordt gevestigd, dan moet de uitgever de IP hieronder vermelde adresblokken aan hun lijst van gewenste personen toevoegen.

**CRM-synchronisatie**

Marketo Engage [Salesforce CRM-synchronisatie](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/add-an-existing-salesforce-field-to-the-marketo-sync.md){target="_blank"} and [Microsoft Dynamics Sync](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/understanding-the-microsoft-dynamics-sync.md){target="_blank"} zijn integratiemechanismen die uitgaande HTTP- verzoeken aan APIs maken die door uw verkoper van CRM worden gepubliceerd. U moet ervoor zorgen dat uw organisatie van IT om het even welke IP adresblokken hieronder van de toegang tot van uw leverancier APIs van CRM niet blokkeert.

**Uitgaande IP van het Marketo Engage Blokken van het Adres**

De volgende lijsten behandelen alle servers van het Marketo Engage die uitgaande vraag maken. Gebruik de lijsten hieronder als u om het even welke IP lijst van gewenste personen, server, firewall, toegangsbeheerlijst, veiligheidsgroep, of derdedienst vormt om uitgaande verbindingen van Marketo Engage te ontvangen.

<table>
 <tbody>
  <tr>
   <th>IP-blok (CIDR-notatie)</th>
  </tr>
  <tr>
   <td>94.236.119.0/26</td>
  </tr>
  <tr>
   <td>103.237.104.0/22</td>
  </tr>
   <tr>
   <td>130.248.172.0/24</td>
  </tr>
   <tr>
   <td>130.248.173.0/24</td>
  </tr>
  <tr>
   <td>130.248.244.88/29</td>
  </tr>
  <tr>
   <td>185.28.196.0/22</td>
  </tr>
  <tr>
   <td>192.28.144.0/20</td>
  </tr>
  <tr>
   <td>192.28.160.0/19</td>
  </tr>
  <tr>
   <td>199.15.212.0/22</td>
  </tr>
 </tbody>
</table>

<table>
 <tbody>
  <tr>
   <th>Individueel IP adres</th>
  </tr>
  <tr>
   <td>13.237.155.207</td>
  </tr>
   <tr>
   <td>13.55.192.247</td>
  </tr>
  <tr>
   <td>18.200.201.81</td>
  </tr>
  <tr>
   <td>34.247.24.245</td>
  </tr>
  <tr>
   <td>35.165.244.220</td>
  </tr>
  <tr>
   <td>44.235.171.179</td>
  </tr>
  <tr>
   <td>52.20.211.99</td>
  </tr>
  <tr>
   <td>52.64.109.86</td>
  </tr>
  <tr>
   <td>54.160.246.246</td>
  </tr>
  <tr>
   <td>54.212.167.17</td>
  </tr>
  <tr>
   <td>54.220.138.65</td>
  </tr>
   <tr>
   <td>54.237.141.197</td>
  </tr>
  </tr>
   <tr>
   <td>130.248.168.16</td>
  </tr>
  </tr>
   <tr>
   <td>130.248.168.17</td>
  </tr>

</tbody>
</table>
