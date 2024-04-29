---
description: Stappen instellen - Marketo Docs - Productdocumentatie
title: Stappen instellen
hide: true
hidefromtoc: true
feature: Getting Started
source-git-commit: 2910b81de3eabb0793b9a339eb4fc934d620d525
workflow-type: tm+mt
source-wordcount: '1711'
ht-degree: 0%

---

# Stappen instellen {#setup-steps}

**DIT ARTIKEL BIJWERKEN**

Welkom bij Marketo Engage!

Voordat u begint met het gebruik van Marketo, moet u een aantal stappen uitvoeren.

Deze stappen omvatten:

* Eenvoudige accountinstellingen
* URL&#39;s van uw landingspagina en e-mailkoppelingen markeren om het vertrouwen en de leverbaarheid te verbeteren
* Uw CRM synchroniseren
* Trackingcode toevoegen aan uw bedrijfswebsite

>[!NOTE]
>
>U hoeft deze stappen alleen uit te voeren als uw bedrijf **nieuw voor Marketo**. Als dat niet het geval is, is de installatie mogelijk al uitgevoerd.

Sommige stappen vereisen hulp van uw team van IT.

## De URL&#39;s van uw bestemmingspagina aanpassen met een CNAME {#customize-your-landing-page-urls-with-a-cname}

>[!NOTE]
>
>Bent u een klant van het Pak van de Lancering? U kunt deze stap overslaan. Uw consultant zal u een document met instructies voor de IT-installatie geven tijdens uw gesprek.

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

Kies een NAAM voor de bestemmingspagina&#39;s. Enkele voorbeelden:

    * * **go**.[CompanyDomain].com
    * ***www2**.[CompanyDomain].com
    * * ** lp**.[CompanyDomain].com

>[!TIP]
>
>Houd het kort! Kortere URL&#39;s zijn gemakkelijker te onthouden. We stellen voor om &quot;te gaan&quot; als domein.

Het eerste deel (vet weergegeven) is het `[LandingPageCNAME]`. Je hebt het nodig in Stap 5.

Ga naar het beheergebied om de Munchkin-id op te halen die u vervangt door de CNAME van de bestemmingspagina.

SCREENSHOT: setup-stappen-9.png

Klikken **Mijn account**.

SCREENSHOT: setup-stappen-10.png

De [!UICONTROL Account String] van de instellingen van de bestemmingspagina.

SCREENSHOT: setup-stappen-11.png

Dit is het `[Munchkin ID]`. Sla het bestand op. U moet het aan IT in Stap 5 geven.

Configureer uw domeininstellingen zodat bestemmingspagina&#39;s het domein van uw bedrijf gebruiken in plaats van Marketo (waar ze worden gehost).

## E-maillevering garanderen {#ensure-email-deliverability}

>[!NOTE]
>
>Bent u een klant van het Pak van de Lancering? U kunt deze stap overslaan. Uw consultant zal u een document met instructies voor de IT-installatie geven tijdens uw gesprek.

Er zijn verschillende maatregelen die u kunt nemen om ervoor te zorgen dat de e-mails zoveel mogelijk van uw mensen bereiken.

* **Koppelingen markeren**. U kunt een CNAME kiezen om uw eigen domein (in plaats van Marketo) te gebruiken in de koppelingen die u opneemt in e-mails van Marketo. Dit versterkt uw domeinbranding en verhoogt vertrouwen en leverbaarheid met uw ontvangers.
* **Voeg Marketo toe aan uw lijst van gewenste personen voor e-mail.** Het is gebruikelijk om teste-mails naar uw testaccounts te sturen voordat u e-mails naar de werkelijke gebruikers stuurt. Als u Marketo voegt op lijst van gewenste personen, kunt u voorkomen dat deze teste-mails worden geblokkeerd of gemarkeerd als spam.
* **Stel SPF en DKIM in.** Deze technologieën verzekeren uw ontvangers dat uw e-mails van Marketo geen spam zijn. Als u wilt voorkomen dat spamfilters van ontvangers u e-mails van Marketo weigeren, voert u de volgende stappen uit om [Een SPF en DKIM instellen voor uw e-maillevering](/help/marketo/product-docs/email-marketing/deliverability/set-up-spf-and-dkim-for-your-email-deliverability.md).
* **Stel een MX-record in voor uw domein.** Met een MX-record kunt u e-mail ontvangen naar het domein waarvan u e-mail verzendt om reacties en auto-responders te verwerken. Als u van uw collectief domein verzendt, hebt u waarschijnlijk reeds gevormd dit. Als niet, kunt u opstelling gewoonlijk aan kaart aan het MX verslag van uw collectief domein.
* **Aanbevolen instellingen voor Van adres.** U moet een geldig, bestaand en werkend e-maildomein in Van Adres in alle e-mailcampagnes gebruiken. Het kan nuttig zijn om subdomain van uw collectief domein eerder dan het verzenden van uw collectief domein te vormen. Dit zorgt ervoor dat problemen van uw zakelijke mailstream geen invloed hebben op uw Marketo mailstream en vice versa. Bovendien verzendt het e-mailbericht van `something@nonexistentdomain.com` zorgt ervoor dat e-mail wordt gefilterd of geblokkeerd. Elk domein dat in het Van Adres van de afzender wordt gebruikt, moet een geldige en werkende postmaster@ en een misbruikaccount hebben.

Als u Google Apps gebruikt om uw bedrijfs e-mail te ontvangen, zult u geen misbruik@ of postmaster@ e-mails onder uw domein kunnen tot stand brengen. Om dit probleem te verhelpen, moet u groepen maken met de naam &quot;misbruik&quot; en &quot;postmeester&quot;. Gebruikers die lid zijn van deze groepen ontvangen e-mails die naar deze adressen worden verzonden (bijvoorbeeld postmaster@domain.com). Gedetailleerde instructies voor het maken van groepen zijn beschikbaar [hier](https://support.google.com/a/answer/33343#adminconsole){target="_blank"}.

Kies een CNAME voor koppelingen voor het bijhouden van e-mail (kies een CNAME die _verschillend_ van de landingspagina (CNAME u in Stap 3 koos). Enkele voorbeelden:

* go2.[CompanyDomain].com
* em.[CompanyDomain].com
* wow.[CompanyDomain].com

Het eerste deel is de e-mailtracking CNAME. `[EmailTrackingCNAME]`. U zult het aan IT in Stap 5 moeten geven.

>[!CAUTION]
>
>De NAAM van de e-mail- en bestemmingspagina moet anders zijn. Vermijd ook CNAME&#39;s zoals &#39;track&#39; of &#39;link&#39;. Het wordt vaak gemarkeerd als spam

Ga naar de **[!UICONTROL Admin]** gebied.

SCREENSHOT: setup-stappen-12.png

Klik op **[!UICONTROL Email]**.

SCREENSHOT: setup-stappen-13.png

De [!UICONTROL Tracking Link] uit uw e-mailinstellingen.

De [!UICONTROL Tracking Link] in de vorm: `mkto-[a-z][4 digits].com`.

SCREENSHOT: setup-stappen-14.png

Dit is uw `[MktoTrackingLink]`. Sla het bestand op. U moet het aan IT in Stap 5 geven.

Verzamel &#39;Van&#39; domeinen. Maak een lijst van alle &quot;Van&quot;domeinen (zoals in, `[Sender]@[FromDomain].com`) die je wilt gebruiken voor het verzenden van e-mails van Marketo. Voor de meesten is er slechts één.

Bijvoorbeeld &#39;marketo.com,&#39; &#39;info.marketo.com,&#39;. Dit zijn `[FromDomain1]`,`[FromDomain2]`, enz. Sla ze op. Je moet ze aan IT geven in stap 5.

U hebt nu alle informatie die u nodig hebt om uw aanvraag naar de IT-afdeling te verzenden.

## IT vragen om protocollen te configureren {#ask-it-to-configure-protocols}

>[!NOTE]
>
>Bent u een klant van het Pak van de Lancering? U kunt deze stap overslaan. Uw consultant zal u een document met instructies voor de IT-installatie geven tijdens uw gesprek.

Zodra u alle noodzakelijke informatie hebt verzameld, bent u bereid om een verzoek naar IT te verzenden. U kunt de onderstaande tekst als een sjabloon gebruiken en de vetgedrukte tekst vervangen door uw eigen gegevens.

[Een koppeling naar dit artikel opnemen](/help/marketo/getting-started/setup/configure-protocols-for-marketo.md).

Plak deze tekst in het e-mailbericht en vervang de gebrande plaatsaanduidingen:

>[!NOTE]
>
>Zie Stap 3 en 4 hierboven om de tekst te bepalen die de plaatsaanduidingen moet vervangen. Vergeet niet dat `[LandingPageCNAME]` en `[EmailTrackingCNAME]` moet anders zijn.

`----------------------------------------------`

Geachte Awesome IT Administrator,

Ons marketingteam gebruikt nu het Marketo-platform om met onze mensen te communiceren. Voor een goede e-mailleverbaarheid moeten we de volgende wijzigingen aanbrengen:

`1)` Voor onze landingspagina&#39;s, voeg een DNS Ingang (CNAME) voor toe **[LandingPageCNAME]**.**[CompanyDomain]**.com, aanwijzen naar **[Munchkin-id]**.mktoweb.com.

`2)` Voor onze het volgen verbindingen in e-mail, voeg een DNS Ingang (CNAME) voor toe **[EmailTrackingCNAME]**.**[CompanyDomain]**.com, aanwijzen naar **[MktoTrackingLink]**.

`3)` Lijst van gewenste personen Marketo.

    * Als wij IP adressen in onze E-mailLijst van gewenste personen gebruiken, voeg hieronder vermelde IPs toe:
    199.15.212.0/22
    
    192.28.144.0/20
    
    192.28.160.0/19
    
    185.28.196.0/22
    
    130.248.172.0/24
    
    130.248.173.0/24
    
    103.237.104.0/22
    
    94.236.119.0/26

>[!NOTE]
>
>Bereik uit naar de Steun van Marketo als u een afgekorte lijst van IPs zou willen om lijst van gewenste personen specifiek voor uw milieu te .

    * Als ons antispamsysteem van domeinen gebruikt, voeg deze toe:

**`[FromDomain1]`**
**`[FromDomain2]`**

`4)` We moeten SPF en DKIM instellen, zodat Marketo namens ons ondertekende e-mailberichten mag versturen.

`a.` Om SPF op te zetten, te voegen gelieve de volgende lijn aan onze DNS ingangen toe:

IN TXT **[Van domein]**: v=spf1 mx ip4:**[Bedrijfs-IP(&#39;s)]**
<br/>include: mktomail.com ~all

Als wij reeds een bestaand SPF- verslag in onze DNS ingang hebben, voeg eenvoudig het volgende aan het toe:

include:mktomail.com

`[`Vervangen **Van domein** met uw e-mail van Domein (bv. company.com) en **CorpIP** met het IP-adres van uw e-mailserver (bijvoorbeeld 255.255.255.255).  Als u e-mail van veelvoudige domeinen door Marketo gaat verzenden, zou u uw personeel van IT deze lijn voor elk domein (op één lijn) moeten hebben toevoegen.`]`

`b.` Voor DKIM, gelieve DNS de Verslagen van het Middel voor elk domein te creëren wij zouden willen opstelling. Hieronder zijn de Verslagen van de Gastheer en de Waarden TXT voor elk domein wij zullen ondertekenen voor:

**`[DKIMDomain1]`**: hostrecord is **`[HostRecord1]`** en de TXT-waarde is **[TXTValue1]**.

**`[DKIMDomain2]`**: hostrecord is **`[HostRecord2]`** en de TXT-waarde is **`[TXTValue2]`**.

`[`De **HostRecord** en **TXTValue** voor elke **DKIMDomain** u hebt opstelling na volgende [instructies hier](/help/marketo/product-docs/email-marketing/deliverability/set-up-a-custom-dkim-signature.md). Vergeet niet elk domein in te verifiëren **Beheer > E-mail > DKIM** nadat uw IT-personeel deze stap heeft voltooid.`]`

`5)` We moeten ervoor zorgen dat er een geldig MX-record is voor onze FROM-domeinen **[FromDomain1]**, **[FromDomain2]**, enz. Kunt u dat bevestigen? Als niet, gelieve te vormen om aan ons collectief domein MX verslag in kaart te brengen. Zo kunnen we antwoorden/autoresponders op onze Marketo-mailings verwerken.

Laat me weten wanneer u deze stappen hebt voltooid, zodat ik het installatieproces met Marketo kan voltooien.

Bedankt! Je bent de beste!

Liefde

**`[Your Name]`**

`----------------------------------------------`

Stuur de e-mail naar de IT-afdeling. We begrijpen dat het enige tijd kan duren voordat IT deze taken kan uitvoeren. U kunt doorgaan naar stap 7, maar vergeet niet dat u Stap 6 moet retourneren om de Marketo-instellingen te voltooien.

## Marketo-instellingen voltooien nadat de IT-afdeling is voltooid {#complete-your-marketo-setup-after-it-finishes}

Nadat de IT-afdeling hun taken heeft voltooid, voert u de volgende stappen uit om uw bestemmingspagina en e-mailCNAME&#39;s toe te voegen en om DKIM-ondertekening te activeren.

Ga naar de **[!UICONTROL Admin]** gebied voor het toevoegen van de NAAM van uw bestemmingspagina

SCREENSHOT: setup-stappen-15.png

Selecteer bestemmingspagina&#39;s en klik **[!UICONTROL Edit]** in de [!UICONTROL Settings] gebied.

SCREENSHOT: setup-stappen-16.png

Voer uw nieuwe domeinnaam in het veld in **[!UICONTROL Domain Name for Landing Pages]**. Dit moet de volgende vorm hebben:

`[LandingPageCNAME].[CompanyDomain].com`

SCREENSHOT: setup-stappen-17.png

In de **[!UICONTROL Fallback]** Voer de URL in waarnaar de mensen moeten gaan als er geen bestemmingspagina beschikbaar is. U kunt de homepage van uw bedrijf gebruiken als u geen reservepagina hebt. In de **[!UICONTROL Homepage]** in, voert u uw bedrijfswebsite in.

SCREENSHOT: setup-stappen-18.png

In de [!UICONTROL Admin] gebied, selecteren **[!UICONTROL Email]** om uw e-mailNAAM toe te voegen

SCREENSHOT: setup-stappen-19.png

Omlaag schuiven naar [!UICONTROL Branding Domains]. Selecteer uw domein en klik **[!UICONTROL Edit]**.

SCREENSHOT: setup-stappen-20.png

Voer in het veld Domein uw domein voor het bijhouden van e-mail in. Dit moet de volgende vorm hebben:

`[EmailTrackingCNAME].[CompanyDomain].com`. Klik op **[!UICONTROL Save]**.

SCREENSHOT: setup-stappen-21.png

## Uw CRM integreren {#integrate-your-crm}

Dit is waarschijnlijk de meest opwindende stap van uw opstelling - het is tijd om Marketo met al die lood en contacten te vullen u in uw CRM hebt opgeslagen!

Kies uit het volgende, afhankelijk van CRM uw bedrijf gebruikt.

    * [Marketo integreren met [!DNL Salesforce.com]](/help/marketo/product-docs/crm-sync/salesforce-sync/understanding-the-salesforce-sync.md)
    * [Marketo integreren met [!DNL Microsoft Dynamics]](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/understanding-the-microsoft-dynamics-sync.md)

>[!NOTE]
>
>U hebt de hulp van de beheerder van CRM van uw bedrijf nodig om deze stappen te voltooien.

## Trackingcode toevoegen aan uw website {#add-tracking-code-to-your-website}

>[!NOTE]
>
>Ben je [!DNL Launch Pack] klant? U kunt deze stap overslaan. Uw consultant zal u [!DNL Munchkin] code instructies in uw document van de de opstellingsinstructies van IT.

Marketo heeft JavaScript voor aangepaste reeksspatiëring (ook wel [!DNL Munchkin]) die u kunt gebruiken om persoonlijke activiteiten op elke webpagina bij te houden. [!DNL Munchkin] is vereist om uw website in Marketo te integreren. Ga als volgt te werk: [Toevoegen [!DNL Munchkin] Code volgen op uw website](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md){target="_blank"}.

>[!NOTE]
>
>Ervaring met HTML die nodig is om de trackingcode toe te voegen.

## Prestatieverwachtingen {#performance-expectations}

Wat kunt u van Marketo verwachten op het gebied van prestaties? Deze kan variëren, afhankelijk van de grootte en complexiteit van uw marketingcampagnes. Maar u kunt prestatieniveaus op gelijke voet met wat in de &quot;Standaard&quot;kolom in verscheidene lijsten verwachten die in worden gevonden in [Productbeschrijving Marketo Engage](https://helpx.adobe.com/legal/product-descriptions/adobe-marketo-engage---product-description.html){target="_blank"}. The "Performance" and "Performance Plus" columns refer to performance tier packages that provide [higher performance levels](https://nation.marketo.com/t5/product-documents/marketo-engage-performance-tiers/ta-p/328835){target="_blank"}.

Al uw opstellingsstappen zijn voorbij. Het enige wat er over is, is om in te duiken en Marketo te gebruiken.
