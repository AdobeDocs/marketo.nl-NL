---
description: Protocollen configureren voor Marketo - Marketo Docs - Productdocumentatie
title: Protocollen voor Marketo configureren
hide: true
hidefromtoc: true
feature: Getting Started
source-git-commit: 8473c4d59210bb18c3968a56883034febf00c320
workflow-type: tm+mt
source-wordcount: '2184'
ht-degree: 0%

---

# De eerste Taken van de Opstelling voor Marketo Engage{#initial-setup-tasks-for-marketo-engage}

Wanneer u uw gloednieuwe Adobe Marketo Engage-exemplaar gaat instellen, hebt u een handvol taken nodig. We raden u ten zeerste aan deze taken uit te voeren.

Na deze eerste installatie kunt u onze [Beste praktijken voor een Nieuwe Instantie van het Marketo Engage](/help/marketo/temp-getting-started-section/temp-best-practice-checklists/where-to-start.md) om optimaal te profiteren van uw investering en zichzelf op te zetten voor succes op de lange termijn.

## Taak 1: Domeinen Lijst van gewenste personen {#allowlist-domains}

Als u of uw organisatie restrictieve firewall of proxyserverinstellingen gebruikt, moet u of uw netwerkbeheerder bepaalde domeinen en IP-adresbereiken lijsten van gewenste personen om ervoor te zorgen dat Adobe Marketo Engage naar behoren werkt.

Deel dit artikel met uw IT-afdeling voor hulp bij het implementeren van de onderstaande protocollen. Als deze webtoegang beperken via een lijst van gewenste personen, moet u ervoor zorgen dat de volgende domeinen (inclusief het sterretje) worden toegevoegd om alle Marketo-bronnen en -websockets toe te staan:

* `*.marketo.com`
* `*.marketodesigner.com`
* `*.mktoweb.com`
* `*.experience.adobe.com`
* `*.adobe.net`

## Taak 2: DNS-records maken voor het porteren van pagina&#39;s en e-mail {#step-create-dns-records-for-landing-pages-and-email}

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

## Taak 3: Lijst van gewenste personen Marketo IPs {#step-allowlist-marketo-ips}

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

## Taak 4: Opstelling SPF en DKIM {#step-set-up-spf-and-dkim}

Uw marketingteam had u ook DKIM (Domain Keys Identified Mail)-informatie moeten sturen die aan uw DNS-resourcerecord (ook hieronder vermeld) moet worden toegevoegd. Volg de stappen om DKIM en SPF (het Kader van het Beleid van de Afzender) met succes te vormen, dan uw marketing team mee te delen dat dit is bijgewerkt.

1. Aan opstelling SPF, voeg de volgende lijn aan onze DNS ingangen toe:

   `[CompanyDomain]` IN TXT v=spf1 mx ip4:`[CorpIP]`\
   include: mktomail.com ~all

   Als wij reeds een bestaand SPF- verslag in onze DNS ingang hebben, voeg eenvoudig het volgende aan het toe:\
   include: mktomail.com

   CompanyDomain vervangen door het hoofddomein van uw website (bijvoorbeeld: &quot;`(company.com/)`&quot;) en CorpIP met het IP-adres van uw e-mailserver van uw bedrijf (bijvoorbeeld &quot;25.255.255.255&quot;). Als u e-mail van veelvoudige domeinen door Marketo gaat verzenden, zou u uw personeel van IT deze lijn voor elk domein (op één lijn) moeten hebben toevoegen.

1. Voor DKIM, creeer DNS Verslagen van het Middel voor elk domein wij opstelling zouden willen. Hieronder zijn de Verslagen van de Gastheer en de Waarden TXT voor elk domein wij zullen ondertekenen voor:

   `[DKIMDomain1]`: hostrecord is `[HostRecord1]` en de TXT-waarde is `[TXTValue1]`.

   `[DKIMDomain2]`: hostrecord is `[HostRecord2]` en de TXT-waarde is `[TXTValue2]`.

   Kopieer de waarden HostRecord en TXTV voor elke DKIMDomain u opstelling na het volgen van hebt [instructies hier](/help/marketo/product-docs/email-marketing/deliverability/set-up-a-custom-dkim-signature.md){target="_blank"}. Vergeet niet om elk domein in Admin > E-mail > DKIM te verifiëren nadat uw personeel van IT deze stap heeft voltooid.

## Taak 5: DMARC instellen {#set-up-dmarc}

DMARC (Domain-based Message Authentication, Reporting &amp; Conformance) is een verificatieprotocol dat wordt gebruikt om organisaties te helpen hun domein te beschermen tegen ongeoorloofd gebruik. DMARC breidt de bestaande authentificatieprotocollen, zoals SPF en DKIM uit, om ontvankelijke servers te informeren over welke acties zij zouden moeten nemen als een mislukking in authentificatie op hun domein voorkomt. Hoewel DMARC momenteel optioneel is, wordt het ten zeerste aanbevolen omdat het uw merk en reputatie van uw organisatie beter beschermt. Belangrijke leveranciers zoals Google en Yahoo zullen het gebruik van DMARC voor bulkafzenders vanaf februari 2024 vereisen.

DMARC werkt alleen als u ten minste een van de volgende DNS TXT-records hebt:

* Een geldige SPF
* Een geldige DKIM Record voor uw FROM: Domain (aanbevolen voor Marketo Engage)

Daarnaast moet u een DMARC-specifieke DNS TXT-record voor uw FROM: Domain hebben. Naar keuze, kan een e-mailadres van uw keuze worden bepaald om erop te wijzen waar de DMARC- rapporten binnen uw organisatie zouden moeten gaan, zodat kunt u rapporten controleren.

Als beste praktijken, wordt het geadviseerd om implementatie DMARC langzaam uit te voeren door uw beleid DMARC van p=none, aan p=quarantaine, aan p=diskette te escaleren aangezien u inzicht in de potentiële invloed van DMARC krijgt, en uw beleid DMARC te plaatsen aan ontspannen groepering op SPF en DKIM.

### DMARC-voorbeeldworkflow {#dmarc-example-workflow}

1. Als u wordt gevormd om rapporten te ontvangen DMARC, zou u het volgende moeten doen...

   I. Analyseer terugkoppelen en de rapporten u (p=none) ontvangt en gebruikt, die de ontvanger vertelt om geen acties tegen berichten uit te voeren die authentificatie ontbreken, maar nog e-mailrapporten naar de afzender verzenden.

   II. Het overzicht en lost kwesties met SPF/DKIM op als de wettige berichten authentificatie ontbreken.

   III. Bepaal of SPF of DKIM is uitgelijnd en of verificatie voor alle legitieme e-mailadressen wordt doorgestuurd.

   IV. De rapporten van het overzicht om de resultaten te verzekeren zijn wat u op uw SPF/DKIM beleid baseert.

1. Ga verder om het beleid aan (p=quarantaine) aan te passen, dat de ontvangende e-mailserver aan quarantaine e-mail vertelt die authentificatie ontbreekt (dit betekent typisch het plaatsen van die berichten in de spamomslag).

   I. Herzie verslagen om ervoor te zorgen dat de resultaten zijn wat u verwacht.

1. Als u met het gedrag van berichten op p=quarantaineniveau tevreden bent, kunt u beleid aan (p=weiger) aanpassen. Het p=weigeringsbeleid vertelt de ontvanger om het even welke e-mail voor het domein volledig te ontkennen (stuit) dat authentificatie ontbreekt. Als dit beleid is ingeschakeld, heeft alleen e-mail die is geverifieerd als 100% en die is geverifieerd door uw domein, een kans op plaatsing in het postvak.

>[!CAUTION]
>
>Gebruik dit beleid met voorzichtigheid en bepaal als het voor uw organisatie aangewezen is.

### DMARC-rapportage {#dmarc-reporting}

DMARC biedt de mogelijkheid om rapporten te ontvangen over e-mailberichten die niet voldoen aan SPF/DKIM. Er zijn twee verschillende die rapporten door ISP diensten als deel van het authentificatieproces worden geproduceerd dat de afzenders door de markeringen RUA/RUF in hun beleid kunnen ontvangen DMARC.

* Samengevoegde rapporten (RUA): bevat geen PII (persoonlijk identificeerbare informatie) die gevoelig zou zijn voor GDPR (algemene gegevensbeschermingsverordening).

* Forensische rapporten (RUF): bevat e-mailadressen die gevoelig zijn voor GDPR. Alvorens te gebruiken, is het best om intern te controleren hoe te om te gaan met informatie die GDPR volgzaam moet zijn.

Deze rapporten worden vooral gebruikt om een overzicht te krijgen van e-mails die spoofing proberen te maken. Dit zijn hoogst technische rapporten die het best door een derdehulpmiddel worden verteerd.

### Voorbeeld-DMARC-records {#example-dmarc-records}

* Minimumrecord van schijf: `v=DMARC1; p=none`

* Opnemen dat wordt verwezen naar een e-mailadres voor het ontvangen van rapporten: `v=DMARC1; p=none;  rua=mailto:emaill@domain.com;     ruf=mailto:email@domain.com`

### DMARC-tags en wat ze doen {#dmarc-tags-and-what-they-do}

DMARC-records hebben meerdere componenten, DMARC-tags genoemd. Elke tag heeft een waarde die een bepaald aspect van DMARC opgeeft.

<table>
<thead>
  <tr>
    <th>Tagnaam </th>
    <th>Vereist/optioneel </th>
    <th>Functie </th>
    <th>Voorbeeld </th>
    <th>Standaardwaarde </th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>v</td>
    <td>Vereist</td>
    <td>Met deze DMARC-tag wordt de versie opgegeven. Er is momenteel slechts één versie, dus deze heeft een vaste waarde van v=DMARC1</td>
    <td>V=DMARC1 DMARC1</td>
    <td>DMARC1</td>
  </tr>
  <tr>
    <td>p</td>
    <td>Vereist</td>
    <td>Toont het geselecteerde beleid DMARC en geeft de ontvanger opdracht om post te melden, in quarantaine te plaatsen of te verwerpen die authentificatiecontroles ontbreekt.</td>
    <td>p=none, quarantaine of afwijzen</td>
    <td>-</td>
  </tr>
  <tr>
    <td>fo</td>
    <td>Optioneel</td>
    <td>Staat de domeineigenaar toe om rapporteringsopties te specificeren.</td>
    <td>0: Rapport genereren als alles mislukt 
    <br>1: Rapport genereren als iets ontbreekt 
    <br>d: Rapport genereren als DKIM mislukt 
    <br>s: Rapport genereren als SPF mislukt</td>
    <td>1 (aanbevolen voor DMARC-rapporten)</td>
  </tr>
  <tr>
    <td>pct</td>
    <td>Optioneel</td>
    <td>Vertelt het percentage berichten die aan het filtreren worden onderworpen.</td>
    <td>pct=20</td>
    <td>100</td>
  </tr>
  <tr>
    <td>ruw</td>
    <td>Optioneel (aanbevolen)</td>
    <td>Identificeert waar de samengevoegde rapporten zullen worden geleverd.</td>
    <td>rua=mailto:aggrep@example.com</td>
    <td>-</td>
  </tr>
  <tr>
    <td>ruf</td>
    <td>Optioneel (aanbevolen)</td>
    <td>Identificeert waar forensische rapporten zullen worden geleverd.</td>
    <td>ruf=mailto:authfail@example.com</td>
    <td>-</td>
  </tr>
  <tr>
    <td>sp</td>
    <td>Optioneel</td>
    <td>Specificeert beleid DMARC voor subdomeinen van het ouderdomein.</td>
    <td>sp=deny</td>
    <td>-</td>
  </tr>
  <tr>
    <td>adkim</td>
    <td>Optioneel</td>
    <td>Kan strikt (s) of Relaxed ® zijn. Relaxed alignment betekent dat het domein dat wordt gebruikt in de DKIM-handtekening een subdomein kan zijn van het adres 'Van'. Strikte uitlijning betekent dat het domein dat wordt gebruikt in de DKIM-handtekening een exacte overeenkomst moet zijn met het domein dat wordt gebruikt in het Van-adres.</td>
    <td>adkim=r </td>
    <td>r</td>
  </tr>
  <tr>
    <td>aspf</td>
    <td>Optioneel</td>
    <td>Kan strikt (s) of Relaxed ® zijn. De opnieuw geconcentreerde groepering betekent dat het Domein ReturnPath een subdomein van Van Adres kan zijn. Strikte uitlijning houdt in dat het domein van het Return-Path een exacte overeenkomst moet zijn met het Van-adres.</td>
    <td>aspf=r</td>
    <td>r</td>
  </tr>
</tbody>
</table>

Ga voor volledige informatie over DMARC en alle opties ervan naar [https://dmarc.org/](https://dmarc.org/){target="_blank"}.

### DMARC en Marketo Engage {#dmarc-and-marketo-engage}

Er zijn twee soorten groepering voor DMARC-uitlijning DKIM en SPF groepering.

>[!NOTE]
>
>Het wordt aanbevolen DMARC-uitlijning uit te voeren op DKIM versus SPF voor Marketo.

* DKIM-align DMARC-Aan opstelling DKIM richt DMARC moet u:

   * Opstelling DKIM voor VAN: Domein van uw bericht. De instructies gebruiken [in dit artikel](/help/marketo/product-docs/email-marketing/deliverability/set-up-a-custom-dkim-signature.md){target="_blank"}.
   * Vorm DMARC voor VAN:/DKIM Domein dat vroeger werd gevormd

* DMARC-Uitgelijnde SPF-aan opstelling DMARC gerichte SPF via branded terugkeer-weg, moet u:

   * Brandd Return-Path-domein instellen
      * Vorm het aangewezen SPF verslag
      * Wijzig de MX-record om terug te wijzen naar de standaard MX voor het datacenter waarvan de e-mail wordt verzonden

   * Vorm DMARC voor het brandde terugkeer-weg Domein

* Als u post van Marketo door specifieke IP verzendt en geen branded terugkeer-weg reeds hebt uitgevoerd, of niet zeker als u hebt, te openen gelieve een kaartje met [Marketo-ondersteuning](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"}.

* Als u post van Marketo door een gedeelde pool van IPs verzendt, kunt u zien of kwalificeert u voor Vertrouwde IPs door [hier toepassen](http://na-sjg.marketo.com/lp/marketoprivacydemo/Trusted-IP-Sending-Range-Program.html){target="_blank"}. Branded return-path wordt gratis aangeboden aan diegenen die van Marketo Trusted IP&#39;s verzenden. Als dit programma is goedgekeurd, vraagt u Marketo Support om een retourpad met branding in te stellen.

   * Vertrouwde IPs: Een gedeelde pool van IPs die voor lagere volumegebruikers wordt gereserveerd die &lt;75K/maand verzenden die niet voor specifieke IP kwalificeren. Deze gebruikers moeten ook aan beste praktijkvereisten voldoen.

* Als u post van Marketo door gedeelde IPs verzendt en u niet voor Vertrouwde IPs kwalificeert en meer dan 100.000 berichten per maand verzendt, zult u het Team van de Rekening van de Adobe (uw rekeningsmanager) moeten contacteren om een specifieke IP te kopen.

* Strikte SPF-uitlijning wordt niet ondersteund en wordt niet aanbevolen in Marketo.

## Taak 6: Opstelling MX Verslagen voor Uw Domein {#step-set-up-mx-records-for-your-domain}

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
   <td>13.237.155.2007</td>
  </tr>
   <tr>
   <td>13.5.192.247</td>
  </tr>
  <tr>
   <td>18.200.2011.81</td>
  </tr>
  <tr>
   <td>34 247 24 245</td>
  </tr>
  <tr>
   <td>35 165 244 220</td>
  </tr>
  <tr>
   <td>44 235 171 179</td>
  </tr>
  <tr>
   <td>52.20.211,99</td>
  </tr>
  <tr>
   <td>52 64 109,86</td>
  </tr>
  <tr>
   <td>54 160 246 246</td>
  </tr>
  <tr>
   <td>54 212 167,17</td>
  </tr>
  <tr>
   <td>54 220 138,65</td>
  </tr>
   <tr>
   <td>54 237 141 197</td>
  </tr>
  </tr>
   <tr>
   <td>130 248 168,16</td>
  </tr>
  </tr>
   <tr>
   <td>130 248 168 17</td>
  </tr>
 </tbody>
</table>
