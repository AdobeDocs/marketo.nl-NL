---
description: Overzicht - Marketo Docs - Productdocumentatie
title: Overzicht
exl-id: 18ddeebc-bc89-411c-9d2c-23df6841cb3a
source-git-commit: 0d1762d9a5607d72af625aafbf7b9f412d6713c1
workflow-type: tm+mt
source-wordcount: '1016'
ht-degree: 0%

---

# Overzicht {#overview}

Als u vanaf 15 februari 2022 een nieuwe account bij Adobe Marketo Engage hebt (een nieuwe account, niet alleen een nieuw exemplaar voor een bestaande account), wordt deze mogelijk geïntegreerd met het Adobe Identity Management System, afhankelijk van het aangeschafte productpakket. Neem contact op met de Marketo Admin of met de Customer Success Manager van uw account als u dit doet.

Bestaande Marketo-abonnementen worden later dit jaar naar het Adobe Identity Management-systeem gemigreerd.

>[!NOTE]
>
>Marketo Support kan geen updates voor Adobe IMS-migratie leveren. Uw manager van het Succes van de Klant zal met de geschatte chronologie in de komende maanden bereiken.

## Profielniveaus {#profile-levels}

Adobe Marketo Engage-abonnementen die op het Adobe-systeem zijn aangesloten, ondersteunen verschillende profielen. Hier volgen de typen gebruikersprofielen die relevant zijn voor deze integratie.

<table>
 <tr>
  <td><strong>Adobe Admin Console System Admin</strong></td>
  <td>Verantwoordelijk voor het opzetten van identiteitsconcepten voor de Adobe org en het Marketo Engage product in de Adobe Admin Console. Toegewezen rol bij de opstelling van de organisatie van Adobe.</td>
 </tr>
 <tr>
  <td><strong>Adobe Admin Console-productbeheerder</strong></td>
  <td>Verantwoordelijk voor het recht van gebruikers op het product Marketo Engage in de Adobe Admin Console. Toegewezen rol in Adobe Admin Console.</td>
 </tr>
 <tr>
  <td><strong>Adobe Admin Console-productprofielbeheer</strong></td>
  <td>Hiermee beheert u de beschrijvingen van het productprofiel die aan die beheerder zijn toegewezen en alle bijbehorende beheerfuncties.</td>
 </tr>
 <tr>
  <td><strong>Marketo Engage-productbeheerder</strong></td>
  <td>Een persoon die toegang heeft gekregen tot Marketo Engage met administratieve voorrechten. Toegewezen rol in Marketo Engage, niet in Adobe Admin Console.</td>
 </tr>
 <tr>
  <td><strong>Marketo Engage-gebruiker</strong></td>
  <td>Een persoon die toegang heeft gekregen tot Marketo Engage. Geen beheerdersrechten.</td>
 </tr>
</table>

## Veelgestelde vragen {#faq}

**Wat is Adobe Identity?**

Adobe Identity Management System bestaat uit drie componenten.

* Adobe-identiteitsdienst: Verwerkt verificatie en validatie van de eindgebruiker, inclusief federatie en runtime Single-Sign-On (SSO).

* Adobe Admin Console: De Admin Console biedt een centrale locatie voor het beheer van de rechten van Adobe in uw gehele organisatie. Het behandelt gebruikersbeheer, de wolkendienst, Desktoplicentierechten, federatieconfiguratie, en verstrekt de veiligheidseigenschappen van de verliespreventie.

* Adobe-gebruikersbeheer-API (UMAPI): Hiermee kunnen organisaties gebruikers en rechten van ondernemingen in de Adobe Admin Console op API-niveau beheren.

**Wanneer worden bestaande Marketo Engage-abonnementen geïntegreerd met IMS?**

Bestaande Marketo-abonnementen zullen later dit jaar naar het Adobe Identity Management-systeem worden gemigreerd. Marketo Support kan geen updates voor Adobe IMS-migratie leveren. Uw manager van het Succes van de Klant zal met de geschatte chronologie in de komende maanden bereiken.

**Wat is het verschil tussen een Adobe-productbeheerder en een Marketo Engage-beheerder?**

* Adobe Product Admin is een nieuwe rol in het Marketo-platform.
* Adobe Product Admin-rol wordt toegekend aan gebruikers die als productbeheerder in Adobe Admin Console zijn toegevoegd
* Adobe Product Admin is een alleen-lezen rol en kan niet worden bewerkt of verwijderd uit Marketo Engage.
* Adobe Product Admin heeft dezelfde rechten en rechten als standaard Marketo Admin.
* De rol van Marketo Engage Admin is nog steeds Admin en wordt toegekend aan een gebruiker in Marketo Engage.

**Is er een wijziging in de ondersteuning van de gebruikersbeheer-API-client?**

Ja. Degenen die aan Adobe IMS zijn aangemeld, kunnen niet alle bestaande Marketo-API&#39;s voor gebruikersbeheer gebruiken. Voor het uitnodigen, bijwerken en verwijderen van handelingen van gebruikers, de Adobe [IMS API&#39;s](https://www.adobe.io/apis/experienceplatform/umapi-new.html) te gebruiken. Voor rolbeheer zijn de Marketo-API&#39;s voor gebruikersbeheer nog steeds van toepassing. Daarnaast zijn er geen andere wijzigingen in de Marketo REST API-clientondersteuning.

**Wie nemen we contact op voor ondersteuning als we geïntegreerd zijn met IMS?**

U zou de standaardprocedure voor het contacteren volgen [Marketo-ondersteuning](https://nation.marketo.com/t5/support/ct-p/Support).

**Als ik een Identiteit van de Adobe gebruik om tot andere toepassingen van de Adobe toegang te hebben, kan ik dat gebruiken om tot Marketo toegang te hebben?**

Zelfs als u andere Adobe-producten hebt, hebt u geen toegang tot Marketo met Adobe Identity totdat het abonnement is gemigreerd naar IMS.

**Zijn Marketo-gebruikersrollen (binnen werkruimten) beheerd in Adobe Admin Console?**

Nee. Het beheer van de Rol van de gebruiker (binnen werkruimten) wordt voltooid in Marketo Engage.

**Ik ben Marketo Admin in een geïntegreerd IMS-abonnement en heb geen toegang tot de Admin Console. Hoe krijg ik toegang?**

Om het even welk Systeem van de Adobe of Admin van het Product dat toegang tot de Admin Console van uw organisatie heeft kan u toegang geven. Als u niet zeker bent wie in uw organisatie admin voorrechten in de console heeft, contacteer [Adobe Klantenservice](https://helpx.adobe.com/contact.html).

**Hoe kan een beheerder gebruikers toevoegen aan Marketo Sales Connect?**

Hoewel er een productkaart in Admin Console voor Sales Connect is, mag Admin Console niet worden gebruikt om gebruikers toe te voegen/te beheren. Met de volgende koppeling kunnen beheerders gebruikers beheren via Marketo Sales Connect: [https://toutapp.com/next#settings/admin/user-management](https://toutapp.com/next#settings/admin/user-management).

**Waar kan ik meer leren over de Adobe Admin Console?**

[https://helpx.adobe.com/enterprise/admin-guide.html](https://helpx.adobe.com/enterprise/admin-guide.html).

**Ga ik nog steeds naar de sectie Admin in Marketo om wijzigingen aan te brengen in gebruikersaccounts voor mijn account?**

Nee, u moet naar [account.adobe.com](https://account.adobe.com).

**Hoe werkt dit met Marketo Universal ID?**

De gebruikers aan boord van een Adobe-identiteit hebben naadloos toegang tot alle abonnementen voor IMS via de abonnementsschakelaar in het product.

**Werkt dit met SSO?**

Ja. Marketo-integratie met Adobe IMS ondersteunt gebruikers van Universal ID en SSO. De SSO wordt nu aangestuurd door Adobe IMS en is ingesteld op organisatieniveau in de Adobe Admin Console. [Meer informatie hier](https://helpx.adobe.com/enterprise/using/set-up-identity.html).

**Hoe werkt apparaatautorisatie?**

Adobe IMS biedt momenteel geen ondersteuning voor functies zoals Marketo voor apparaatautorisatie.

**Is het nog mogelijk om de functie &quot;Aanmelden bij gebruiker uitnodigen&quot; te gebruiken om de aanmelding van een gebruiker uniek te maken via e-mail?**

Nee. De uitnodigingsworkflow van de gebruiker is niet meer actief wanneer een abonnement op IMS is ingeschakeld, zodat de functie niet langer geldig is. Voor een Adobe-identiteit moet de identiteit van de gebruiker door het e-mailbericht worden gestuurd.

**Voor Adobe IMS, hebben wij de optie om Adobe ID, Enterprise ID, of Federated ID te gebruiken?**

Ja, u bepaalt het type identiteit om uw organisatiesteun te hebben. Hier vindt u meer informatie: [Identiteitsoverzicht](https://helpx.adobe.com/enterprise/using/identity.html) en hier: [Identiteit instellen](https://helpx.adobe.com/enterprise/using/set-up-identity.html).

>[!MORELIKETHIS]
>
>* [Beheerdersinstellingen](/help/marketo/product-docs/administration/marketo-with-adobe-identity/admin-setup.md)
>* [Een productbeheerder toevoegen of verwijderen](/help/marketo/product-docs/administration/marketo-with-adobe-identity/add-or-remove-a-product-admin.md)
>* [Een gebruiker toevoegen of verwijderen](/help/marketo/product-docs/administration/marketo-with-adobe-identity/add-or-remove-a-user.md)

