---
description: Adobe Identity Management FAQ - Marketo Docs - Productdocumentatie
title: Veelgestelde vragen over Adobe Identity Management
feature: Marketo with Adobe Identity
exl-id: 2401def7-1696-4d77-a8a3-96c490517121
source-git-commit: 95ed91736b7276dd7a5b9e09958c1f09832ae719
workflow-type: tm+mt
source-wordcount: '1579'
ht-degree: 0%

---

# Veelgestelde vragen over Adobe Identity Management {#adobe-identity-management-faq}

**wat is de Identiteit van Adobe?**

Adobe Identity Management System bestaat uit drie componenten.

* [!DNL Adobe Identity Service]: handelt verificatie en validatie van de eindgebruiker af, inclusief federatie en runtime Single-Sign-On (SSO).

* Adobe Admin Console: De Admin Console biedt een centrale locatie voor het beheer van Adobe-rechten in uw hele organisatie. Het behandelt gebruikersbeheer, de wolkendienst, de vergunning van de Desktop, federatieconfiguratie, en verstrekt de veiligheidseigenschappen van de verliespreventie.

* Adobe User Management API (UMAPI): staat organisaties toe om zakelijke gebruikers en rechten in de Adobe Admin Console op API-niveau te beheren.

**wanneer zullen de bestaande abonnementen van Marketo Engage met IMS worden geïntegreerd?**

Bestaande Marketo Engage-abonnementen worden momenteel gemigreerd naar de Adobe IMS tijdens elke verkoopgebeurtenis, waaronder verlengingen, heruitbestedingsgebeurtenissen en/of addendums. Migraties buiten een verkoopgebeurtenis worden vanaf oktober 2024 ondersteund.

**Na migratie, zal Marketo Engage URLs het zelfde blijven?**

Nee. URL&#39;s worden na migratie in de volgende indeling weergegeven: `https://experience.adobe.com/#/@tenantID/so:XXX-XXX-XXX/marketo-engage/classic/` (de XXX&#39;s geven de Munchkin-id aan en @huurderID komt van uw Adobe-org).

**is er om het even wat wij moeten doen voor de verandering voorbereidingen treffen URL?**

Ja. Na de migratie gaat Marketo Engage van experience.adobe.com naar Adobe Experience Cloud. U zult met uw team van IT moeten werken om alle vermelde domeinen van Adobe [&#x200B; bij de bovenkant van dit artikel &#x200B;](/help/marketo/getting-started/initial-setup/configure-protocols-for-marketo.md){target="_blank"} te lijsten van gewenste personen om verstoring aan de toegang van Marketo Engage te verhinderen.

De vorige verbindingen en de referenties aan de activa van Marketo Engage op het engage-xx.marketo.com domein _zullen_ blijven functioneren. U moet zich echter eerst aanmelden bij de Marketo Engage-instantie voor de URL waarnaar u navigeert. Als u bijvoorbeeld naar een bladwijzer voor een slimme campagne wilt navigeren, bijvoorbeeld met Munchkin ID 123-ABC-456, moet u zich eerst aanmelden bij de Marketo Engage-instantie met Munchkin ID 123-ABC-456.

Deze omleidingsfunctie kan door toekomstige ontwikkelingswerkzaamheden worden verbroken, maar niet gepland. Om onverwachte onderbrekingen te voorkomen, wordt aangeraden bladwijzers zo snel mogelijk bij te werken.

**werkt dit met SSO?**

Ja. De integratie met Adobe IMS ondersteunt gebruikers van Universal ID en SSO. De SSO wordt nu aangestuurd door Adobe IMS en is ingesteld op organisatieniveau in de Adobe Admin Console. Nochtans, zijn er verschillen in Marketo Engage IDP-Toegelaten steun in vergelijking met Adobe SP-In werking gestelde steun ([&#x200B; leren meer hier &#x200B;](https://helpx.adobe.com/nl/enterprise/using/set-up-identity.html){target="_blank"}). Als u hulp betreffende SSO verschillen na wordt gemigreerd aan Admin Console nodig hebt, gelieve [&#x200B; de Zorg van de Klant van Adobe &#x200B;](https://helpx.adobe.com/nl/contact.html){target="_blank"} te contacteren.

**wat is het verschil tussen een Admin van het Product van Adobe en een Admin van Marketo Engage?**

* Adobe Product Admin is een nieuwe rol in het Marketo-platform.
* Adobe-productbeheerrol wordt toegekend aan gebruikers die als productbeheerder in Adobe Admin Console zijn toegevoegd
* Adobe Product Admin is een alleen-lezen rol en kan niet uit Marketo Engage worden bewerkt of verwijderd.
* Adobe Product Admin heeft dezelfde rechten en rechten als een standaard Marketo Admin.
* De rol van Marketo Engage Admin is nog steeds Admin en wordt toegekend aan een gebruiker in Marketo Engage.
* Alleen gebruikers met de Marketo-standaardbeheerrol worden toegewezen als Marketo-productbeheerder in de Admin Console.

**is er om het even welke verandering in de cliëntsteun van het Beheer van de Gebruiker API?**

Ja. Degenen die aan Adobe IMS zijn aangemeld, kunnen niet alle bestaande Marketo-API&#39;s voor gebruikersbeheer gebruiken. Voor gebruiker nodig, update, en schrappingsacties, zou Adobe [&#x200B; IMS APIs &#x200B;](https://www.adobe.io/apis/experienceplatform/umapi-new.html){target="_blank"} moeten worden gebruikt. Voor rolbeheer zijn de Marketo-API&#39;s voor gebruikersbeheer nog steeds van toepassing. Daarnaast zijn er geen andere wijzigingen in de Marketo REST API-clientondersteuning.

**wie contacteren wij voor steun als wij met IMS geïntegreerd zijn?**

* Migratie vóór gebruiker: de gevallen van de dossiersteun in de [&#x200B; Gemeenschap van de Natie van de Marketing &#x200B;](https://nation.marketo.com/t5/support/ct-p/Support) of e-mail `customercare@marketo.com`.

* De Migratie van de post-gebruiker: de gevallen van de dossiersteun in de [&#x200B; Gemeenschap van de Natie van de Marketing &#x200B;](https://nation.marketo.com/t5/support/ct-p/Support) of e-mail `customercare@marketo.com`.

* Voltooiing van migratie na ondersteuning: beheerders van productondersteuning kunnen zaken indienen via de Experience League Support-portal.

Als u Ultimate Success hebt, hebt u toegang tot Admin Console Migration White Glove Service. Neem contact op met het Adobe-accountteam (uw accountmanager) voor hulp.

**als ik een Identiteit van Adobe gebruik om tot andere toepassingen van Adobe toegang te hebben, kan ik dat gebruiken om tot Marketo toegang te hebben?**

Zelfs als u andere Adobe-producten hebt, hebt u geen toegang tot Marketo met Adobe Identity totdat het abonnement is gemigreerd naar IMS.

**worden Marketo gebruikersrollen (binnen werkruimten) beheerd in Adobe Admin Console?**

Nee. Gebruikersrolbeheer (binnen werkruimten) wordt voltooid in Marketo Engage.

**ik ben Marketo Admin in een geïntegreerd abonnement IMS en heb geen toegang tot Admin Console. Hoe krijg ik toegang?**

Elke Adobe System of Product Admin die toegang heeft tot de Admin Console van uw organisatie kan u toegang geven. Als u niet zeker bent wie in uw organisatie admin voorrechten in de console heeft, contacteer [&#x200B; de Zorg van de Klant van Adobe &#x200B;](https://helpx.adobe.com/nl/contact.html){target="_blank"}.

**hoe Admin gebruikers aan Marketo [!DNL Sales Connect] zou toevoegen?**

Hoewel er een productkaart in Admin Console for [!DNL Sales Connect] wordt weergegeven, mag Admin Console niet worden gebruikt om gebruikers toe te voegen/te beheren. De volgende verbinding zal Admins toestaan om gebruikers via Marketo [!DNL Sales Connect] te beheren: [&#x200B; https://toutapp.com/next#settings/admin/user-management &#x200B;](https://toutapp.com/next#settings/admin/user-management){target="_blank"}.

**waar kan ik meer over Adobe Admin Console leren?**

[&#x200B; https://helpx.adobe.com/nl/enterprise/admin-guide.html &#x200B;](https://helpx.adobe.com/nl/enterprise/admin-guide.html){target="_blank"}.

**ga ik nog naar de Admin sectie in Marketo om gebruikersrekeningsveranderingen voor mijn rekening aan te brengen?**

Nr, zou u aan [&#x200B; account.adobe.com &#x200B;](https://account.adobe.com){target="_blank"} moeten navigeren.

**hoe werkt dit met universele identiteitskaart van Marketo?**

Degenen die aan de Adobe-identiteit zijn gekoppeld, hebben naadloos toegang tot alle abonnementen waarvoor IMS is ingeschakeld via de abonnementskiezer in het product.

**werkt dit met SSO?**

Ja. Marketo-integratie met Adobe IMS ondersteunt gebruikers van Universal ID en SSO. De SSO wordt nu aangestuurd door Adobe IMS en is ingesteld op organisatieniveau in de Adobe Admin Console. [&#x200B; leer hier meer &#x200B;](https://helpx.adobe.com/nl/enterprise/using/set-up-identity.html){target="_blank"}.

**ik ben reeds aan de Identiteit van Adobe ingetekend en nu wil ik SSO uitvoeren. Wat doe ik?**

Als u Single Sign On wilt uitvoeren en uw abonnement aan de Identiteit van Adobe zonder SSO die in Adobe Org wordt uitgevoerd, gelieve een kaartje aan [&#x200B; Steun van Marketo &#x200B;](https://nation.marketo.com/){target="_blank"} voor te leggen en het onderwerp te specificeren zoals &quot;Marketo op Admin Console, die SSO uitvoert.&quot;

**hoe werkt de apparatenvergunning?**

Adobe IMS biedt momenteel geen ondersteuning voor functies voor het autoriseren van Marketo-apparaten.

**is het nog mogelijk om &quot;Login te gebruiken nodigt de eigenschap van de Dialoog van de Gebruiker uit, om login van een gebruiker uniek van hun e-mail te maken?**

Nee. De uitnodigingsworkflow van de gebruiker is niet meer actief wanneer een abonnement op IMS is ingeschakeld, zodat de functie niet langer geldig is. Voor Adobe-identiteit moet de identiteit van een gebruiker door het e-mailadres worden gestuurd.

**voor Adobe IMS, hebben wij de optie om Adobe ID, Enterprise ID, of Federated ID te gebruiken?**

Ja, u bepaalt het type identiteit om uw organisatiesteun te hebben. Meer info kan hier worden gevonden: [&#x200B; Overzicht van de Identiteit &#x200B;](https://helpx.adobe.com/nl/enterprise/using/identity.html) en hier: [&#x200B; Opstelling Identiteit &#x200B;](https://helpx.adobe.com/nl/enterprise/using/set-up-identity.html){target="_blank"}.

**Welke productkaarten worden gesteund in Adobe Admin Console?**

De ondersteunde productkaarten zijn: Marketo Engage, Marketo Measure, Marketo Dynamic Chat, Marketo Sales Connect en Marketo Sales Insight Actions.

**wat als mijn gebruikerslogin niet mijn e-mail aanpast wanneer ik gemigreerd aan een Identiteit van Adobe?**

Huidige Marketo Engage-gebruikers met een andere aanmeldingsnaam dan hun e-mailadres kunnen zich niet meer aanmelden met die referentie als ze eenmaal naar een Adobe Identity zijn gemigreerd. Adobe-identiteiten worden altijd geverifieerd met het e-mailadres van een gebruiker. U kunt een adres van de identiteitskaart van Adobe op [&#x200B; account.adobe.com bijwerken &#x200B;](https://account.adobe.com){target="_blank"}.

**wat gebeurt na de migratie van de Identiteit van Adobe als mijn abonnement IP beperkingsmontages gebruikt?**

Uw huidige IP beperkingen zullen actief door Q1 2026 blijven (dit is op abonnementen van toepassing die hen vóór migratie hadden toegelaten). Deze beperkingen zijn ook van toepassing op Adobe ID-gebruikers. Uw toegangsbeheer blijft dus werken zoals u had verwacht.

Vanaf Q1 2026, zullen de erfenisIP beperkingen worden gepensioneerd. Vanaf dat punt vooruit, zal op IP-Gebaseerde toegang uitsluitend in Adobe Admin Console (AAC) worden beheerd. Om veilige toegang te handhaven, zult u IP beperkingen in AAC moeten vormen. Voor meer informatie, te zien gelieve dit [&#x200B; blogpost van de Blog van de Aantekening van de Marketing &#x200B;](https://nation.marketo.com/t5/product-blogs/updated-important-update-ip-restrictions-feature-transition/ba-p/358420){target="_blank"}.

**wat gebeurt na de migratie van de Identiteit van Adobe als ik gebruikers met een rol heb die de optie om &quot;het Enige Teken van de Bypass&quot;te mijden heeft?**

Adobe Admin Console wordt geleverd met een standaard Business ID-directory. Gebruikers buiten de domeinen die worden geclaimd in Federated ID-directory&#39;s in een Adobe Org, worden toegewezen aan deze map met een Adobe ID-identiteitstype. Deze gebruikers kunnen Marketo Engage openen zonder Single Sign On (SSO) en het eigendom van de licentie blijft bij het bedrijf, niet bij de personen.

**ik heb meer dan één abonnement, maar niet allen toegelaten Enig Teken hebben. Wat gebeurt er na de migratie naar Adobe Identity?**

Wanneer abonnementen op Adobe Identity worden geregistreerd, wordt Single Sign On (SSO) ingesteld op het niveau van de Adobe-organisatie. Dit betekent dat SSO op alle productinstanties in Adobe Org van toepassing is. Als SSO is ingesteld, geldt deze voor alle Marketo-instanties in die Adobe Org. Eerder ondersteunde Marketo deze instelling op instantieniveau. Dit wordt niet ondersteund door Adobe Identity Management System.

**zijn om het even welke veranderingen nodig aan CNAMEs, SPF, of DKIM wij momenteel voor Marketo Engage na de migratie van de Identiteit van Adobe gebruiken?**

Nee, er zijn geen gevolgen voor deze configuraties.

**Hoe kan ik zittingen verhinderen uit timing?**

In [&#x200B; Geavanceerde Montages &#x200B;](https://helpx.adobe.com/nl/enterprise/using/authentication-settings.html#advanced-settings){target="_blank"}, kunt u het gewenste maximumzittingsleven (de toestemmingen van Admin van het Systeem vereiste) aanpassen. Het wordt aanbevolen deze instelling in te stellen na de migratie van het product, maar vóór de migratie van de gebruiker.

**ik moet nu in Experience Cloud navigeren om tot Marketo Engage toegang te hebben. Is er een manier om deze stroom te stroomlijnen?**

Ja. U kunt browser referentie van de verbinding tot stand brengen die na het klikken van de **knoop van de** Lancering &lbrace;op de pagina van de de instantietoegang van Marketo Engage begint om die pagina vooruit te mijden.

![](assets/faq-1.png)
