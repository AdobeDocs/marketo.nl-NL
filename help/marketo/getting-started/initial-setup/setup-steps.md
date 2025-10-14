---
description: Installatiestappen - Marketo-documentatie - Productdocumentatie
short-description: Bent u net aan de slag gegaan met Adobe Marketo Engage? Leer welke stappen u moet voltooien voordat u aan de slag kunt.
title: Stappen voor instellingen
feature: Getting Started
exl-id: 5f37da48-b2ed-4e48-a5a2-429149745085
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '1663'
ht-degree: 1%

---

# Stappen voor instellingen {#setup-steps}

**Onthaal aan Adobe Marketo Engage!**

Voordat u gaat duiken, moet u een aantal stappen uitvoeren.

Deze stappen omvatten:

* URL&#39;s en e-mailkoppelingen van uw bestemmingspagina markeren om het vertrouwen en de leverbaarheid te verbeteren
* Protocollen configureren voor Marketo Engage
* Uw CRM synchroniseren
* Trackingcode toevoegen aan uw bedrijfswebsite

>[!NOTE]
>
>U moet slechts deze stappen doen als uw bedrijf **nieuw aan Marketo** is. Als dat niet het geval is, is de installatie mogelijk al uitgevoerd.

Sommige stappen vereisen hulp van uw team van IT.

## E-maillevering garanderen {#ensure-email-deliverability}

>[!NOTE]
>
>Bent u een klant van het Pak van de Lancering? U kunt deze stap overslaan. Uw consultant zal u een document met instructies voor de IT-installatie geven tijdens uw gesprek.

Er zijn verschillende maatregelen die u kunt nemen om ervoor te zorgen dat de e-mails zoveel mogelijk van uw mensen bereiken.

* **merk uw het volgen verbindingen**. U kunt een CNAME kiezen om uw eigen domein (in plaats van Marketo) te gebruiken in de koppelingen die u opneemt in e-mails van Marketo. Dit versterkt uw domeinbranding en verhoogt vertrouwen en leverbaarheid met uw ontvangers.
* **voeg Marketo aan uw collectieve e-maillijst van gewenste personen** toe. Het is gebruikelijk om teste-mails naar uw testaccounts te sturen voordat u e-mails naar de werkelijke gebruikers stuurt. Als u Marketo voegt op lijst van gewenste personen, kunt u voorkomen dat deze teste-mails worden geblokkeerd of gemarkeerd als spam.
* **Opstelling SPF en DKIM**. Deze technologieën verzekeren uw ontvangers dat uw e-mails van Marketo geen spam zijn. Om te helpen de spamfilters van ontvangers verhinderen u de e-mails van Marketo te verwerpen, volg deze stappen aan [&#x200B; Opstelling een SPF en DKIM voor Uw E-mailLeverbaarheid &#x200B;](/help/marketo/product-docs/email-marketing/deliverability/set-up-spf-and-dkim-for-your-email-deliverability.md).
* **opstelling een MX verslag voor uw domein.** Met een MX-record kunt u e-mail ontvangen naar het domein waarvan u e-mail verzendt om reacties en auto-responders te verwerken. Als u van uw collectief domein verzendt, hebt u waarschijnlijk reeds gevormd dit. Als niet, kunt u opstelling gewoonlijk aan kaart aan het MX verslag van uw collectief domein.
* **geadviseerde Montages voor Van Adres.** U moet een geldig, bestaand en werkend e-maildomein in Van Adres in alle e-mailcampagnes gebruiken. Het kan nuttig zijn om subdomain van uw collectief domein eerder dan het verzenden van uw collectief domein te vormen. Dit zorgt ervoor dat problemen van uw zakelijke mailstream geen invloed hebben op uw Marketo mailstream en vice versa. Bovendien zorgt het verzenden van post van `something@nonexistentdomain.com` ervoor dat e-mail wordt gefilterd of geblokkeerd. Elk domein dat in het Van Adres van de afzender wordt gebruikt, moet een geldige en werkende postmaster@ en een misbruikaccount hebben.

Als u Google Apps gebruikt om uw bedrijfs e-mail te ontvangen, zult u geen misbruik@ of postmaster@ e-mails onder uw domein kunnen tot stand brengen. Om dit probleem te verhelpen, moet u groepen maken met de naam &quot;misbruik&quot; en &quot;postmeester&quot;. Gebruikers die lid zijn van deze groepen ontvangen e-mails die naar deze adressen worden verzonden (bijvoorbeeld <postmaster@domain.com> ). De gedetailleerde instructies voor het creëren van groepen kunnen [&#x200B; hier &#x200B;](https://support.google.com/a/answer/33343#adminconsole){target="_blank"} worden gevonden.

Kies een NAAM voor e-mail volgende verbindingen (kies één die _verschillend_ van de het landen pagina CNAME u in Stap 3 koos) is. Enkele voorbeelden:

* go2.[ CompanyDomain ].com
* em.[ CompanyDomain ].com
* wow.[ CompanyDomain ].com

Het eerste deel is de e-mailtracking CNAME, `[EmailTrackingCNAME]` . Je moet het aan IT geven.

>[!CAUTION]
>
>De NAAM van de e-mail- en bestemmingspagina moet anders zijn. Vermijd ook CNAME&#39;s zoals &#39;track&#39; of &#39;link&#39;. Het wordt vaak gemarkeerd als spam

Ga naar het **[!UICONTROL Admin]** -gebied als u de koppeling voor het bijhouden van Marketo wilt zoeken.

![](assets/setup-steps-1.png)

Klik op **[!UICONTROL Email]**.

![](assets/setup-steps-2.png)

Kopieer de [!UICONTROL Tracking Link] uit uw e-mailinstellingen.

De [!UICONTROL Tracking Link] heeft de notatie: `mkto-[a-z][4 digits].com` .

![](assets/setup-steps-3.png)

Dit is uw `[MktoTrackingLink]` . Sla het bestand op. U moet het aan IT in Stap 5 geven.

Verzamel &#39;Van&#39; domeinen. Maak een lijst van alle &quot;Van&quot;domeinen (zoals in, `[Sender]@[FromDomain].com`) die u voor het verzenden van e-mails van Marketo van plan bent te gebruiken. Voor de meesten is er slechts één.

Bijvoorbeeld &#39;marketo.com,&#39; &#39;info.marketo.com,&#39;. Dit zijn `[FromDomain1]`, `[FromDomain2]`, etc. Sla ze op. Je moet ze aan IT geven in stap 5.

U hebt nu alle informatie die u nodig hebt om uw aanvraag naar de IT-afdeling te verzenden.

## De URL&#39;s van uw bestemmingspagina aanpassen met een CNAME {#customize-your-landing-page-urls-with-a-cname}

>[!NOTE]
>
>Bent u een klant van het Pak van de Lancering? U kunt deze stap overslaan. Uw consultant zal u een document met instructies voor de IT-installatie geven tijdens uw gesprek.

>[!NOTE]
>
>**Vereiste Bevoegdheden Admin**

Kies een NAAM voor de bestemmingspagina&#39;s. Enkele voorbeelden:

    * **go**.[CompanyDomain].com
    * **www2**.[CompanyDomain].com 
     * **lp**.[CompanyDomain].com 

>[!TIP]
>
>Houd het kort! Kortere URL&#39;s zijn gemakkelijker te onthouden. We stellen voor om &quot;te gaan&quot; als domein.

Het eerste deel (vet weergegeven) is de `[LandingPageCNAME]` . Je hebt het nodig in Stap 5.

Om identiteitskaart terug te winnen van Munchkin die u met uw het landen pagina CNAME zult vervangen, ga naar het **Admin** gebied.

![](assets/setup-steps-4.png)

Klik **Mijn Rekening**.

![](assets/setup-steps-5.png)

Kopieer de [!UICONTROL Account String] van de montages van de landingspagina.

![](assets/setup-steps-6.png)

Dit is de `[Munchkin ID]` . Sla het bestand op. U moet het aan IT in Stap 5 geven.

Configureer uw domeininstellingen zodat bestemmingspagina&#39;s het domein van uw bedrijf gebruiken in plaats van Marketo (waar ze worden gehost).

## IT vragen om protocollen te configureren {#ask-it-to-configure-protocols}

>[!NOTE]
>
>Bent u een klant van het Pak van de Lancering? U kunt deze stap overslaan. Uw consultant zal u een document met instructies voor de IT-installatie geven tijdens uw gesprek.

Zodra u alle noodzakelijke informatie hebt verzameld, bent u bereid om een verzoek naar IT te verzenden. U kunt de onderstaande tekst als een sjabloon gebruiken en de vetgedrukte tekst vervangen door uw eigen gegevens.

[&#x200B; omvat een verbinding aan dit artikel &#x200B;](/help/marketo/getting-started/initial-setup/configure-protocols-for-marketo.md).

Plak deze tekst in het e-mailbericht en vervang de gebrande plaatsaanduidingen:

>[!NOTE]
>
>Zie Stap 3 en 4 hierboven om de tekst te bepalen die de plaatsaanduidingen moet vervangen. Houd er rekening mee dat `[LandingPageCNAME]` en `[EmailTrackingCNAME]` verschillend moeten zijn.

`----------------------------------------------`

Beste IT-beheerder,

Ons marketingteam gebruikt nu het Marketo-platform om met onze mensen te communiceren. Voor een goede e-mailleverbaarheid moeten we de volgende wijzigingen aanbrengen:

`1)` voor onze het landen pagina&#39;s, voeg een DNS Ingang (CNAME) voor **[LandingPageCNAME]** toe.**[CompanyDomain]**.com, wijzend aan **[identiteitskaart van Munchkin]** .mktoweb.com.

`2)` voor onze het volgen verbindingen in e-mail, voeg een DNS Ingang (CNAME) voor **[EmailTrackingCNAME]** toe.**[CompanyDomain]**.com, wijzend aan **[MktoTrackingLink]**.

`3)` Lijst van gewenste personen Marketo.

    * Als wij IP adressen in onze Lijst van gewenste personen E-mail gebruiken, voeg hieronder vermelde IPs toe:
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

`4)` We moeten SPF en DKIM instellen, zodat Marketo gemachtigd is om ondertekende e-mailberichten namens ons te verzenden.

`a.` Als u SPF wilt instellen, voegt u de volgende regel toe aan uw DNS-vermeldingen:

IN TXT **[van Domein]**: v=spf1 mx ip4:**[Collectieve IP(s)]**
<br/> include: mktomail.com ~all

Als wij reeds een bestaand SPF- verslag in onze DNS ingang hebben, voeg eenvoudig het volgende aan het toe:

include:mktomail.com

`[` vervangt **van Domein** met uw E-mail van Domein (ex: company.com) en **CorpIP** met het IP adres van uw collectieve e-mailserver (ex: 255.255.255.255).  Als u e-mail van veelvoudige domeinen door Marketo gaat verzenden, zou u uw personeel van IT deze lijn voor elk domein (op één lijn) moeten hebben toevoegen.`]`

`b.` Voor DKIM moet u DNS-bronrecords maken voor elk domein dat u wilt instellen. Hieronder zijn de Verslagen van de Gastheer en de Waarden TXT voor elk domein wij zullen ondertekenen voor:

**`[DKIMDomain1]`**: Hostrecord is **`[HostRecord1]`** en de TXT-waarde is **`[TXTValue1]`** .

**`[DKIMDomain2]`**: Hostrecord is **`[HostRecord2]`** en de TXT-waarde is **`[TXTValue2]`** .

`[` Exemplaar **HostRecord** en **TXTValue** voor elk **DKIMDomain** u opstelling na het volgen van de [&#x200B; instructies hier &#x200B;](/help/marketo/product-docs/email-marketing/deliverability/set-up-a-custom-dkim-signature.md) hebt. Vergeet niet om elk domein in **Admin te verifiëren > E-mail > DKIM** nadat uw personeel van IT deze stap heeft voltooid.`]`

`5)` We moeten ervoor zorgen dat er een geldige MX-record is voor onze FROM-domeinen **`[FromDomain1]`** , **`[FromDomain2]`** , enzovoort. Kunt u dat bevestigen? Als niet, gelieve te vormen om aan ons collectief domein MX verslag in kaart te brengen. Zo kunnen we antwoorden/autoresponders op onze Marketo-mailings verwerken.

Laat me weten wanneer u deze stappen hebt voltooid, zodat ik het installatieproces met Marketo kan voltooien.

Bedankt! Je bent de beste!

met betrekking tot

**`[Your Name]`**

`----------------------------------------------`

Stuur de e-mail naar de IT-afdeling. We begrijpen dat het enige tijd kan duren voordat IT deze taken kan uitvoeren. U kunt doorgaan naar de volgende stap, maar vergeet niet dat u naar deze stap moet terugkeren om de Marketo Engage-instellingen te voltooien.

## Marketo-instellingen voltooien nadat de IT-afdeling is voltooid {#complete-your-marketo-setup-after-it-finishes}

Nadat de IT-afdeling hun taken heeft voltooid, voert u de volgende stappen uit om uw bestemmingspagina en e-mailCNAME&#39;s toe te voegen en om het ondertekenen van DKIM te activeren.

Ga naar het gebied **[!UICONTROL Admin]** om de NAAM van uw bestemmingspagina toe te voegen

![](assets/setup-steps-7.png)

Selecteer Landing Pages en klik **[!UICONTROL Edit]** in het [!UICONTROL Settings] -gebied.

![](assets/setup-steps-8.png)

Voer uw nieuwe domeinnaam in het veld **[!UICONTROL Domain Name for Landing Pages]** in. Dit moet de volgende vorm hebben:

`[LandingPageCNAME].[CompanyDomain].com`

![](assets/setup-steps-9.png)

Voer in het veld **[!UICONTROL Fallback]** pagina de URL in waarnaar de mensen moeten gaan als er geen bestemmingspagina beschikbaar is. U kunt de homepage van uw bedrijf gebruiken als u geen reservepagina hebt. Voer in het veld **[!UICONTROL Homepage]** uw bedrijfswebsite in.

![](assets/setup-steps-10.png)

Selecteer in het gebied [!UICONTROL Admin] de optie **[!UICONTROL Email]** om uw e-mailNAAM toe te voegen

![](assets/setup-steps-11.png)

Omlaag schuiven naar [!UICONTROL Branding Domains] . Selecteer het domein en klik op **[!UICONTROL Edit]** .

![](assets/setup-steps-12.png)

Voer in het veld Domein uw domein voor het bijhouden van e-mail in. Dit moet de volgende vorm hebben:

`[EmailTrackingCNAME].[CompanyDomain].com`. Klik op **[!UICONTROL Save]**.

![](assets/setup-steps-13.png)

## Uw CRM integreren {#integrate-your-crm}

Dit is waarschijnlijk het meest opwindende deel van uw opstelling. Het is tijd om Marketo op te vullen met al die leads en contactpersonen die u in uw CRM hebt opgeslagen!

Kies uit het volgende, afhankelijk van CRM uw bedrijf gebruikt.

* [Marketo Engage integreren met  [!DNL Salesforce.com]](/help/marketo/product-docs/crm-sync/salesforce-sync/understanding-the-salesforce-sync.md)
* [Marketo Engage integreren met  [!DNL Microsoft Dynamics]](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/understanding-the-microsoft-dynamics-sync.md)

  >[!NOTE]
  >
  >U hebt de hulp van de beheerder van CRM van uw bedrijf nodig om deze stappen te voltooien.

## Trackingcode toevoegen aan uw website {#add-tracking-code-to-your-website}

>[!NOTE]
>
>Bent u een [!DNL Launch Pack] klant? U kunt deze stap overslaan. Uw consultant zal u [!DNL Munchkin] codeinstructies in uw document met instructies voor de IT-installatie geven.

Marketo Engage heeft een JavaScript voor aangepaste reeksspatiëring (ook wel [!DNL Munchkin] genoemd) die u kunt gebruiken om activiteiten van personen op elke webpagina bij te houden. [!DNL Munchkin] is vereist om uw website te integreren in Marketo. Volg deze stappen om [&#x200B; toe te voegen  [!DNL Munchkin]  het Volgen Code aan Uw Website &#x200B;](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md){target="_blank"}.

>[!NOTE]
>
>U hebt ervaring met HTML nodig om de trackingcode toe te voegen.

## Prestatieverwachtingen {#performance-expectations}

Wat kunt u van Marketo verwachten op het gebied van prestaties? Deze kan variëren, afhankelijk van de grootte en complexiteit van uw marketingcampagnes. Maar u kunt prestatiesniveaus op gelijke met verwachten wat in de &quot;Standaard&quot;kolom in verscheidene van de lijsten wordt geschetst die in de [&#x200B; wordt gevonden beschrijving van het Product van Marketo Engage &#x200B;](https://helpx.adobe.com/nl/legal/product-descriptions/adobe-marketo-engage---product-description.html){target="_blank"}. De &quot;Prestaties&quot;en &quot;Prestaties plus&quot;kolommen verwijzen naar de pakketten van de prestatiesrij die [&#x200B; hogere prestatiesniveaus &#x200B;](https://nation.marketo.com/t5/product-documents/marketo-engage-performance-tiers/ta-p/328835){target="_blank"} verstrekken.

>[!MORELIKETHIS]
>
>* [&#x200B; vorm Protocollen voor Marketo Engage &#x200B;](/help/marketo/getting-started/initial-setup/configure-protocols-for-marketo.md)
>
>* [&#x200B; Opstelling van de Gebruiker &#x200B;](/help/marketo/getting-started/initial-setup/user-setup.md)
