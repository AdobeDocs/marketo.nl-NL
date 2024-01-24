---
description: Adobe Identity Management FAQ - Marketo Docs - Productdocumentatie
title: Adobe Identity Management - Veelgestelde vragen
feature: Marketo with Adobe Identity
exl-id: 2401def7-1696-4d77-a8a3-96c490517121
source-git-commit: af5e6b567c074507e20a8b8d312f3abaa5ab60b0
workflow-type: tm+mt
source-wordcount: '1202'
ht-degree: 0%

---

# Adobe Identity Management - Veelgestelde vragen {#adobe-identity-management-faq}

**Wat is Adobe Identity?**

Adobe Identity Management System bestaat uit drie componenten.

* [!DNL Adobe Identity Service]: handelt verificatie en validatie van de eindgebruiker af, inclusief federatie en runtime Single-Sign-On (SSO).

* Adobe Admin Console: De Admin Console biedt een centrale locatie voor het beheer van rechten voor Adoben in uw hele organisatie. Het behandelt gebruikersbeheer, de wolkendienst, de vergunning van de Desktop, federatieconfiguratie, en verstrekt de veiligheidseigenschappen van de verliespreventie.

* Gebruikerbeheer-API (UMAPI) voor Adobe: hiermee kunnen organisaties gebruikers en rechten van bedrijven in de Adobe Admin Console beheren op API-niveau.

**Wanneer worden bestaande abonnementen op Marketo&#39;s Engage geïntegreerd met IMS?**

Bestaande Marketo-abonnementen zullen later dit jaar naar het Adobe Identity Management System worden gemigreerd. Marketo Support kan geen updates voor Adobe IMS-migratie leveren. Het accountteam van de Adobe zal de komende maanden het geschatte tijdpad bereiken.

**Wat is het verschil tussen een Adobe productbeheerder en een Marketo Engage beheerder?**

* Adobe Product Admin is een nieuwe rol in het Marketo-platform.
* Adobe van productbeheerdersrol wordt toegekend aan gebruikers die als productbeheerder in Adobe Admin Console zijn toegevoegd
* De Admin van het Product van de Adobe is een read-only rol en kan niet uit Marketo Engage worden uitgegeven of worden geschrapt.
* Adobe productbeheerder heeft dezelfde rechten en rechten als standaard Marketo Admin.
* De rol van Admin van het Marketo Engage is nog Admin en aan een gebruiker in Marketo Engage verleend.

**Is er een wijziging in de ondersteuning van de gebruikersbeheer-API-client?**

Ja. Degenen die aan Adobe IMS zijn aangemeld, kunnen niet alle bestaande Marketo-API&#39;s voor gebruikersbeheer gebruiken. Voor het uitnodigen, bijwerken en verwijderen van handelingen van gebruikers, de Adobe [IMS API&#39;s](https://www.adobe.io/apis/experienceplatform/umapi-new.html){target="_blank"} te gebruiken. Voor rolbeheer zijn de Marketo-API&#39;s voor gebruikersbeheer nog steeds van toepassing. Daarnaast zijn er geen andere wijzigingen in de Marketo REST API-clientondersteuning.

**Wie nemen we contact op voor ondersteuning als we geïntegreerd zijn met IMS?**

U zou de standaardprocedure voor het contacteren volgen [Marketo-ondersteuning](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"}.

**Als ik een Identiteit van de Adobe aan toegang tot andere toepassingen van de Adobe gebruik, kan ik dat gebruiken om tot Marketo toegang te hebben?**

Zelfs als u andere producten van de Adobe hebt, kunt u geen toegang tot Marketo met de Identiteit van de Adobe tot het abonnement aan IMS wordt gemigreerd.

**Zijn Marketo-gebruikersrollen (binnen werkruimten) beheerd in Adobe Admin Console?**

Nee. Het beheer van de Rol van de gebruiker (binnen werkruimten) wordt voltooid in Marketo Engage.

**Ik ben Marketo Admin in een geïntegreerd IMS-abonnement en heb geen toegang tot de Admin Console. Hoe krijg ik toegang?**

Om het even welk Systeem van de Adobe of Admin van het Product dat toegang tot de Admin Console van uw organisatie heeft kan u toegang geven. Als u niet zeker bent wie in uw organisatie admin voorrechten in de console heeft, contacteer [Klantenservice Adoben](https://helpx.adobe.com/contact.html){target="_blank"}.

**Hoe kan een beheerder gebruikers toevoegen aan Marketo [!DNL Sales Connect]?**

Terwijl er een productkaart in Admin Console is voor [!DNL Sales Connect], mag Admin Console niet worden gebruikt om gebruikers toe te voegen/te beheren. Met de volgende koppeling kunnen beheerders gebruikers beheren via Marketo [!DNL Sales Connect]: [https://toutapp.com/next#settings/admin/user-management](https://toutapp.com/next#settings/admin/user-management){target="_blank"}.

**Waar kan ik meer leren over de Adobe Admin Console?**

[https://helpx.adobe.com/enterprise/admin-guide.html](https://helpx.adobe.com/enterprise/admin-guide.html){target="_blank"}.

**Ga ik nog steeds naar de sectie Admin in Marketo om wijzigingen aan te brengen in gebruikersaccounts voor mijn account?**

Nee, u moet naar [account.adobe.com](https://account.adobe.com){target="_blank"}.

**Hoe werkt dit met Marketo Universal ID?**

Degenen die zich aan de Adobe-identiteit houden, hebben naadloos toegang tot alle abonnementen voor IMS via de abonnementsschakelaar in het product.

**Werkt dit met SSO?**

Ja. Marketo-integratie met Adobe IMS ondersteunt gebruikers van Universal ID en SSO. De SSO wordt nu aangestuurd door Adobe IMS en is ingesteld op organisatieniveau in de Adobe Admin Console. [Meer informatie hier](https://helpx.adobe.com/enterprise/using/set-up-identity.html){target="_blank"}.

**Ik ben al geregistreerd voor Adobe Identity en nu wil ik SSO implementeren. Wat doe ik?**

Als u Single Sign On wilt implementeren en uw abonnement is aangemeld bij Adobe Identity zonder SSO geïmplementeerd in de Adobe Org, dient u een ticket in bij [Marketo-ondersteuning](https://nation.marketo.com/){target="_blank"} en specificeer het onderwerp als &quot;Marketo op Admin Console, die SSO uitvoeren.&quot;

**Hoe werkt apparaatautorisatie?**

Adobe IMS biedt momenteel geen ondersteuning voor functies voor het autoriseren van Marketo-apparaten.

**Is het nog mogelijk om de functie &quot;Aanmelden bij gebruiker uitnodigen&quot; te gebruiken om de aanmelding van een gebruiker uniek te maken via e-mail?**

Nee. De uitnodigingsworkflow van de gebruiker is niet meer actief wanneer een abonnement op IMS is ingeschakeld, zodat de functie niet langer geldig is. Voor een Adobe-id moet de identiteit van de gebruiker door het e-mailbericht worden gestuurd.

**Voor Adobe IMS, hebben wij de optie om Adobe ID, Enterprise ID, of Federated ID te gebruiken?**

Ja, u bepaalt het type identiteit om uw organisatiesteun te hebben. Hier vindt u meer informatie: [Identiteitsoverzicht](https://helpx.adobe.com/enterprise/using/identity.html) en hier: [Identiteit instellen](https://helpx.adobe.com/enterprise/using/set-up-identity.html){target="_blank"}.

**Welke productkaarten worden ondersteund in de Adobe Admin Console?**

De ondersteunde productkaarten zijn: Marketo Engage, Marketo Measure, Marketo Dynamic Chat, Marketo Sales Connect en Marketo Sales Insight Actions.

**Wat gebeurt er als mijn gebruikersaanmelding niet overeenkomt met mijn e-mailadres wanneer ik naar een Adobe-id word gemigreerd?**

Huidige Marketo-gebruikers met andere aanmeldingsgegevens dan hun e-mailadres kunnen zich niet meer aanmelden met die referentie wanneer ze eenmaal naar een Adobe Identity zijn gemigreerd. Adobe-id&#39;s worden altijd geverifieerd met het e-mailadres van een gebruiker.

**Wat gebeurt na de migratie van de Identiteit van de Adobe als mijn abonnement IP beperkingsmontages gebruikt?**

Wanneer abonnementen aan de Identiteit van de Adobe worden ingezien, worden de IP beperkingsmontages niet gemigreerd naar Adobe Admin Console. De de beperkingsmontages van Marketo IP omvatten het toestaan van slechts toegang van specifieke IP adressen, en het blokkeren van specifieke IP adressen van toegang. Op dit ogenblik, steunt het Systeem van Identity Management van de Adobe geen IP beperkingseigenschappen.

Vanaf 2024 zal het Systeem van Identity Management van de Adobe een eigenschap vrijgeven om slechts specifieke IP adressen toe te staan, ondersteunend een overgang voor de gebruikers van Marketo die momenteel deze eigenschap gebruiken. Degenen die deze functie momenteel gebruiken, worden pas door de gebruiker gemigreerd als de functie wordt vrijgegeven. Zodra de functie is geleverd, zullen gebruikers op de hoogte worden gesteld van de geplande migratie. Meer informatie over de functie wordt weergegeven als deze beschikbaar is.

Gebruikers die momenteel de IP-beperking gebruiken en specifieke adressen blokkeren voor toegang, kunnen deze functie niet meer gebruiken nadat ze naar Adobe Identity zijn gemigreerd, omdat deze functie niet wordt ondersteund door Adobe Identity Management System.

**Wat gebeurt er na de migratie van de Identiteit van de Adobe als ik gebruikers met een rol heb die de optie &quot;om Enige Onderteken te mijden&quot;heeft?**

Wanneer abonnementen aan de Identiteit van de Adobe worden geregistreerd, wordt Single Sign On (SSO) opstelling op het niveau van de Organisatie van de Adobe voor alle gebruikers. Als SSO is ingesteld, wordt deze afgedwongen voor alle Marketo-gebruikers/alle Marketo-instanties in die Adobe-organisatie. Eerder ondersteunde Marketo het toestaan van een gebruikersrol om de optie &#39;Afzonderlijke aanmelding omzeilen&#39; in te stellen. Dit wordt niet ondersteund door Adobe Identity Management System.

**Ik heb meer dan één abonnement, maar ik heb niet allemaal Single Sign On ingeschakeld. Wat gebeurt er na Adobe identiteitsmigratie?**

Wanneer abonnementen aan de Identiteit van de Adobe worden geregistreerd, wordt Enige Sign On (SSO) opstelling op het niveau van de Organisatie van de Adobe. Dit betekent dat SSO van toepassing is op alle productinstanties in de Adobe Org. Als SSO is ingesteld, geldt deze voor alle Marketo-instanties in die Adobe Org. Eerder ondersteunde Marketo deze instelling op instantieniveau. Dit wordt niet ondersteund door Adobe Identity Management System.
