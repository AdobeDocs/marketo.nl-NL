---
description: Adobe Identity Management FAQ - Marketo Docs - Productdocumentatie
title: Adobe Identity Management - Veelgestelde vragen
feature: Marketo with Adobe Identity
exl-id: 2401def7-1696-4d77-a8a3-96c490517121
source-git-commit: 9e51ece12742152040dbbcb6a1584fba28e863ff
workflow-type: tm+mt
source-wordcount: '780'
ht-degree: 0%

---

# Veelgestelde vragen {#faq}

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

**Hoe werkt apparaatautorisatie?**

Adobe IMS biedt momenteel geen ondersteuning voor functies voor het autoriseren van Marketo-apparaten.

**Is het nog mogelijk om de functie &quot;Aanmelden bij gebruiker uitnodigen&quot; te gebruiken om de aanmelding van een gebruiker uniek te maken via e-mail?**

Nee. De uitnodigingsworkflow van de gebruiker is niet meer actief wanneer een abonnement op IMS is ingeschakeld, zodat de functie niet langer geldig is. Voor een Adobe-id moet de identiteit van de gebruiker door het e-mailbericht worden gestuurd.

**Voor Adobe IMS, hebben wij de optie om Adobe ID, Enterprise ID, of Federated ID te gebruiken?**

Ja, u bepaalt het type identiteit om uw organisatiesteun te hebben. Hier vindt u meer informatie: [Identiteitsoverzicht](https://helpx.adobe.com/enterprise/using/identity.html) en hier: [Identiteit instellen](https://helpx.adobe.com/enterprise/using/set-up-identity.html){target="_blank"}.

**Welke productkaarten worden ondersteund in de Adobe Admin Console?**

De ondersteunde productkaarten zijn: Marketo Engage, Marketo Measure, Marketo Dynamic Chat, Marketo Sales Connect en Marketo Sales Insight Actions.
