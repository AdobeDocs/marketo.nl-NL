---
unique-page-id: 2949469
description: Stappen instellen - Marketo Docs - Productdocumentatie
title: Stappen instellen
exl-id: ef6b7311-55ca-4384-a24c-714eae89a57d
source-git-commit: fed5fc3a511022fbac40b8ad369a1cdda5112167
workflow-type: tm+mt
source-wordcount: '2002'
ht-degree: 0%

---

# Stappen instellen {#setup-steps}

**Welkom bij Marketo Engage!**

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

>[!TIP]
>
>Als u [deze checklist afdrukken](/help/marketo/getting-started/setup/setup-checklist.md){target=&quot;_blank&quot;} kunt u items uitchecken wanneer u ze hebt voltooid.

## Aanmelden en extra Marketo-gebruikers maken {#log-in-and-create-additional-marketo-users}

1. Aanmelden bij Marketo [hier](https://app.marketo.com/){target=&quot;_blank&quot;} met de gegevens die u per e-mail hebt ontvangen.

   ![](assets/setup-steps-1.png)

Gefeliciteerd.  U bent nu in Marketo en kunt beginnen te verkennen. U zou uw collega&#39;s op het marketing team kunnen willen uitnodigen om zich bij u aan te sluiten. U kunt dit doen door nieuwe gebruikers toe te voegen.

Ga naar de **Beheer** gebied.

>[!TIP]
>
>Terwijl u hier bent, kunt u klikken **Mijn account** om uw account- en locatie-instellingen te wijzigen en een nieuwe abonnementsnaam in te stellen.

![](assets/setup-steps-2.png)

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

Klikken **Gebruikers en rollen**.

![](assets/setup-steps-3.png)

Klikken **Nieuwe gebruiker uitnodigen**.

![](assets/setup-steps-4.png)

Vul het e-mailadres, de voornaam en de achternaam van uw collega in. _Het instellen van een vervaldatum voor toegang is optioneel_. Klikken **Volgende**.

![](assets/setup-steps-5.png)

>[!TIP]
>
>Een vervaldatum is ideaal voor externe belanghebbenden of consultants op korte termijn die slechts gedurende een korte periode toegang tot Marketo nodig hebben.

>[!NOTE]
>
>Wanneer de vervaldatum aankomt, ontvangt de gebruiker een vervalmelding en is de account vergrendeld.

Selecteer een rol en klik op **Volgende**. Standaardgebruikers hebben toegang tot alle gebieden behalve Admin.

![](assets/setup-steps-6.png)

>[!NOTE]
>
>Naast de vijf ingebouwde rollen, kunt u douanerollen ook tot stand brengen. Meer informatie over [Gebruikersrollen en -machtigingen beheren](/help/marketo/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.md){target=&quot;_blank&quot;}.

Voel u vrij om de uitnodigingstekst aan te passen. Klikken **Verzenden**.

![](assets/setup-steps-7.png)

De nieuwe gebruiker wordt nu vermeld op het tabblad Gebruikers en ontvangt een e-mail met een koppeling om een wachtwoord en een aanmelding te maken. Volgende stap!

![](assets/setup-steps-8.png)

## Stel uw geautoriseerde ondersteuningscontactpersonen in {#set-up-your-authorized-support-contacts}

Mogelijk hebt u een e-mail van Marketo Support ontvangen waarin staat dat u de beheerder voor klantenondersteuning van Marketo voor uw bedrijf bent. Zo ja, dan kunt u instellen **geautoriseerde ondersteuningscontactpersonen** voor uw team. Alleen geautoriseerde supportcontactpersonen kunnen rechtstreeks via de [Marketo Support Portal](https://support.marketo.com){target=&quot;_blank&quot;}.

>[!NOTE]
>
>Het aantal ondersteuningscontacten dat u kunt maken, wordt bepaald door het pakket dat u hebt aangeschaft. Deze limiet is opgegeven in uw e-mail van Marketo Support.

Contactdocumenten voor geautoriseerde ondersteuning zijn verplaatst naar de Marketo Community. Zie [dit artikel](https://nation.marketo.com/t5/Knowledgebase/Managing-Authorized-Support-Contacts/ta-p/254341){target=&quot;_blank&quot;}.

>[!NOTE]
>
>Alleen personen die zich hebben aangemeld bij de Marketo-gemeenschap, worden in de lijst weergegeven. Als u de persoon niet kunt vinden, zorg ervoor zij login aan de Gemeenschap eerst.

## De URL&#39;s van uw bestemmingspagina aanpassen met een CNAME {#customize-your-landing-page-urls-with-a-cname}

>[!NOTE]
>
>Bent u een klant van het Pak van de Lancering? U kunt deze stap overslaan. Uw consultant zal u een document van de de opstellingsinstructies van IT tijdens uw kickoff vraag verstrekken.

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

Ga naar het beheergebied als u de accounttekenreeks wilt ophalen die u vervangt door de CNAME-landingspagina.

![](assets/setup-steps-9.png)

Klikken **Openingspagina&#39;s**.

![](assets/setup-steps-10.png)

Kopieer de tekenreeks Account uit de instellingen van de openingspagina.

![](assets/setup-steps-11.png)

Dit is het `[AccountString]`. Sla het bestand op. U moet het aan IT in Stap 5 geven.

Configureer uw domeininstellingen zodat bestemmingspagina&#39;s het domein van uw bedrijf gebruiken in plaats van Marketo (waar ze worden gehost).

## E-maillevering garanderen {#ensure-email-deliverability}

>[!NOTE]
>
>Bent u een klant van het Pak van de Lancering? U kunt deze stap overslaan. Uw consultant zal u een document van de de opstellingsinstructies van IT tijdens uw kickoff vraag verstrekken.

Er zijn verschillende maatregelen die u kunt nemen om ervoor te zorgen dat de e-mails zoveel mogelijk van uw mensen bereiken.

* **Koppelingen markeren**. U kunt een CNAME kiezen om uw eigen domein (in plaats van Marketo) te gebruiken in de koppelingen die u opneemt in e-mails van Marketo. Dit versterkt uw domeinbranding en verhoogt vertrouwen en leverbaarheid met uw ontvangers.
* **Voeg Marketo toe aan uw bedrijfs-e-maillijst van gewenste personen.** Het is gebruikelijk om teste-mails naar uw testaccounts te sturen voordat u e-mails naar de werkelijke gebruikers stuurt. Als u Marketo voegt op lijst van gewenste personen, kunt u voorkomen dat deze teste-mails worden geblokkeerd of gemarkeerd als spam.
* **Stel SPF en DKIM in.** Deze technologieën verzekeren uw ontvangers dat uw e-mails van Marketo geen spam zijn. Als u wilt voorkomen dat de spamfilters van de ontvangers uw e-mails van Marketo afwijzen, voert u de volgende stappen uit om [Een SPF en DKIM instellen voor uw e-maillevering](/help/marketo/product-docs/email-marketing/deliverability/set-up-spf-and-dkim-for-your-email-deliverability.md).
* **Stel een MX-record in voor uw domein.** Met een MX-record kunt u e-mail ontvangen naar het domein waarvan u e-mail verzendt om reacties en auto-responders te verwerken. Als u vanuit uw bedrijfsdomein verzendt, is dit waarschijnlijk al geconfigureerd. Als niet, kunt u opstelling gewoonlijk aan kaart aan het MX verslag van uw collectief domein.
* **Aanbevolen instellingen voor Van adres.** U moet een geldig, bestaand en werkend e-maildomein in Van Adres in alle e-mailcampagnes gebruiken. Het kan nuttig zijn om subdomain van uw collectief domein eerder dan het verzenden van uw collectief domein te vormen. Dit zorgt ervoor dat problemen van uw zakelijke mailstream geen invloed hebben op uw Marketo mailstream en vice versa. Bovendien sturen van post van `something@nonexistentdomain.com` zorgt ervoor dat e-mail wordt gefilterd of geblokkeerd. Elk domein dat in het Van Adres van de afzender wordt gebruikt, moet een geldige en werkende postmaster@ en een misbruikaccount hebben.

Als u Google Apps gebruikt om uw bedrijfs-e-mail te hosten, kunt u geen e-mails met misbruik@ of postmaster@ onder uw domein maken. Om dit probleem te verhelpen, moet u groepen maken met de naam &quot;misbruik&quot; en &quot;postmeester&quot;. Gebruikers die lid zijn van deze groepen ontvangen e-mails die naar deze adressen worden verzonden (bijvoorbeeld postmaster@domain.com). Gedetailleerde instructies voor het maken van groepen zijn te vinden [hier](https://support.google.com/a/answer/33343#adminconsole){target=&quot;_blank&quot;}.

Kies een CNAME voor koppelingen voor het bijhouden van e-mail (kies een CNAME die _verschillend_ van de landingspagina (CNAME u in Stap 3 koos). Enkele voorbeelden:

* go2.[CompanyDomain].com
* em.[CompanyDomain].com
* wow.[CompanyDomain].com

Het eerste deel is de e-mailtracking CNAME. `[EmailTrackingCNAME]`. U zult het aan IT in Stap 5 moeten geven.

>[!CAUTION]
>
>De NAAM van de e-mail- en bestemmingspagina moet anders zijn. Vermijd ook CNAME&#39;s zoals &#39;track&#39; of &#39;link&#39;. Het wordt vaak gemarkeerd als spam

Ga naar de **Beheer** gebied.

![](assets/setup-steps-12.png)

Klikken **E-mail**.

![](assets/setup-steps-13.png)

Kopieer de koppeling Tracking uit uw e-mailinstellingen.

De koppeling voor het bijhouden van gegevens heeft de volgende vorm: `mkto-[a-z][4 digits].com`.

![](assets/setup-steps-14.png)

Dit is uw `[MktoTrackingLink]`. Sla het bestand op. U moet het aan IT in Stap 5 geven.

Verzamel &#39;Van&#39; domeinen. Maak een lijst van alle &quot;Van&quot;domeinen (zoals in, `[Sender]@[FromDomain].com`) die je wilt gebruiken voor het verzenden van e-mails van Marketo. Voor de meesten is er slechts één.

Bijvoorbeeld &#39;marketo.com,&#39; &#39;info.marketo.com,&#39;. Dit zijn `[FromDomain1]`,`[FromDomain2]`, enz. Sla ze op. Je moet ze aan IT geven in stap 5.

U hebt nu alle informatie die u nodig hebt om uw verzoek naar IT te verzenden.

## IT vragen om protocollen te configureren {#ask-it-to-configure-protocols}

>[!NOTE]
>
>Bent u een klant van het Pak van de Lancering? U kunt deze stap overslaan. Uw consultant zal u een document van de de opstellingsinstructies van IT tijdens uw kickoff vraag verstrekken.

Zodra u alle benodigde informatie hebt verzameld, kunt u een aanvraag naar de IT-afdeling sturen. U kunt de onderstaande tekst als een sjabloon gebruiken en de vetgedrukte tekst vervangen door uw eigen gegevens.

[Een koppeling naar dit artikel opnemen](/help/marketo/getting-started/setup/configure-protocols-for-marketo.md).

Plak deze tekst in het e-mailbericht en vervang de gebrande plaatsaanduidingen:

>[!NOTE]
>
>Zie Stap 3 en 4 hierboven om de tekst te bepalen die de plaatsaanduidingen moet vervangen. Vergeet niet dat `[LandingPageCNAME]` en `[EmailTrackingCNAME]` moet anders zijn.

`---------------------------------------------`

Geachte Awesome IT Administrator,

Ons marketingteam gebruikt nu het Marketo-platform om met onze mensen te communiceren. Voor een goede e-mailleverbaarheid moeten we de volgende wijzigingen aanbrengen:

`1)` Voor onze landingspagina&#39;s, voeg een DNS Ingang (CNAME) voor toe **[LandingPageCNAME]**.**[CompanyDomain]**.com, aanwijzen naar **[AccountString]**.mktoweb.com.

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
>Raadpleeg Marketo Support als u een verkorte lijst met IP&#39;s wilt gebruiken om de lijst van gewenste personen te maken die specifiek is voor uw omgeving.

    * Als ons antispamsysteem van domeinen gebruikt, voeg deze toe:

**`[FromDomain1]`**
**`[FromDomain2]`**

`4)` We moeten SPF en DKIM instellen, zodat Marketo namens ons ondertekende e-mailberichten mag versturen.

`a.` Om SPF op te zetten, te voegen gelieve de volgende lijn aan onze DNS ingangen toe:

IN TXT **[Van domein]**: v=spf1 mx ip4:**[Bedrijfs-IP(&#39;s)]**
<br/>omvatten: mktomail.com ~all

Als wij reeds een bestaand SPF- verslag in onze DNS ingang hebben, voeg eenvoudig het volgende aan het toe:

include:mktomail.com

`[`Vervangen **Van domein** met uw e-mail van Domein (bijvoorbeeld: bedrijf.com) en **CorpIP** met het IP-adres van uw e-mailserver van uw bedrijf (bijvoorbeeld: 255.255.255.255).  Als u e-mail van veelvoudige domeinen door Marketo gaat verzenden, zou u uw personeel van IT deze lijn voor elk domein (op één lijn) moeten hebben toevoegen.`]`

`b.` Voor DKIM, gelieve DNS de Verslagen van het Middel voor elk domein te creëren wij zouden willen opstelling. Hieronder zijn de Verslagen van de Gastheer en de Waarden TXT voor elk domein wij zullen ondertekenen voor:

**`[DKIMDomain1]`**: Hostrecord is **`[HostRecord1]`** en de TXT-waarde is **[TXTValue1]**.

**`[DKIMDomain2]`**: Hostrecord is **`[HostRecord2]`** en de TXT-waarde is **`[TXTValue2]`**.

`[`Kopieer de **HostRecord** en **TXTValue** voor elke **DKIMDomain** u hebt opstelling na het volgen van [instructies hier](/help/marketo/product-docs/email-marketing/deliverability/set-up-a-custom-dkim-signature.md). Vergeet niet elk domein in te verifiëren **Beheer > E-mail > DKIM** nadat uw IT-personeel deze stap heeft voltooid.`]`

`5)` We moeten ervoor zorgen dat er een geldig MX-record is voor onze FROM-domeinen **[FromDomain1]**, **[FromDomain2]**, enz. Kunt u bevestigen? Als niet, gelieve te vormen om aan ons collectief domein MX verslag in kaart te brengen. Zo kunnen we antwoorden/autoresponders op onze Marketo-mailings verwerken.

Laat me weten wanneer u deze stappen hebt voltooid, zodat ik het installatieproces met Marketo kan voltooien.

Bedankt! Je bent de beste!

Liefde

**`[Your Name]`**

`---------------------------------------------`

Stuur de e-mail naar de IT-afdeling. We begrijpen dat het enige tijd kan duren voordat IT deze taken kan uitvoeren. U kunt doorgaan naar stap 7, maar vergeet niet dat u Stap 6 moet retourneren om de Marketo-instellingen te voltooien.

## Marketo-instellingen voltooien nadat de IT-afdeling is voltooid {#complete-your-marketo-setup-after-it-finishes}

Nadat de IT-afdeling hun taken heeft voltooid, voert u de volgende stappen uit om uw bestemmingspagina en e-mailCNAME&#39;s toe te voegen en om DKIM-ondertekening te activeren.

Ga naar de **Beheer** gebied voor het toevoegen van de NAAM van uw bestemmingspagina

![](assets/setup-steps-15.png)

Selecteer bestemmingspagina&#39;s en klik **Bewerken** in het gebied Instellingen.

![](assets/setup-steps-16.png)

Voer uw nieuwe domeinnaam in in het veld Domeinnaam voor bestemmingspagina&#39;s. Dit moet de volgende vorm hebben:

`[LandingPageCNAME].[CompanyDomain].com`

![](assets/setup-steps-17.png)

Voer in het veld Pagina voor alternatieven de URL in waarnaar mensen moeten gaan als er geen bestemmingspagina beschikbaar is. U kunt de homepage van uw bedrijf gebruiken als u geen reservepagina hebt. Voer in het veld Homepage de website van uw bedrijf in.

![](assets/setup-steps-18.png)

Selecteer in het gebied Beheer de optie E-mail om uw e-mailNAAM toe te voegen

![](assets/setup-steps-19.png)

Schuif omlaag naar brandingdomeinen. Selecteer uw domein en klik **Bewerken**.

![](assets/setup-steps-20.png)

Voer in het veld Domein uw domein voor het bijhouden van e-mail in. Dit moet de volgende vorm hebben:

`[EmailTrackingCNAME].[CompanyDomain].com`. Klikken **Opslaan**.

![](assets/setup-steps-21.png)

## Uw CRM integreren {#integrate-your-crm}

Dit is waarschijnlijk de meest opwindende stap in uw configuratie: het is tijd om Marketo op te vullen met al die leads en contactpersonen die u in uw CRM hebt opgeslagen!

Kies uit het volgende, afhankelijk van CRM uw bedrijf gebruikt.

    * [Marketo integreren met Salesforce.com](/help/marketo/product-docs/crm-sync/salesforce-sync/understanding-the-salesforce-sync.md)
    * [Marketo integreren met Microsoft Dynamics](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/understanding-the-microsoft-dynamics-sync.md)

>[!NOTE]
>
>U hebt de hulp van de beheerder van CRM van uw bedrijf nodig om deze stappen te voltooien.

## Trackingcode toevoegen aan uw website {#add-tracking-code-to-your-website}

>[!NOTE]
>
>Bent u een klant van het Pak van de Lancering? U kunt deze stap overslaan. Uw consultant zal u in het handboek met instructies voor de installatie van uw IT-afdeling codeinstructies geven.

Marketo beschikt over JavaScript voor het bijhouden van wijzigingen (Munchkin genoemd) waarmee u activiteiten van personen op elke webpagina kunt bijhouden. Munchkin is vereist om uw website in Marketo te integreren. Ga als volgt te werk: [Munchkin-trackingcode toevoegen aan uw website](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md){target=&quot;_blank&quot;}.

>[!NOTE]
>
>Ervaring met HTML die nodig is om de trackingcode toe te voegen.

Al uw opstellingsstappen zijn voorbij. Het enige wat er over is, is om in te duiken en Marketo te gebruiken.