---
description: Overzicht - Marketo Docs - Productdocumentatie
title: Overzicht
hide: true
hidefromtoc: true
source-git-commit: 1161d193261af10aaa7658e747ff6500ad4179d0
workflow-type: tm+mt
source-wordcount: '809'
ht-degree: 0%

---

# Overzicht {#overview}

Als uw Adobe Marketo Engage op of na 21-04-21 uw-abonnement is ingericht, wordt deze geïntegreerd met het Adobe Identity Management System. Dankzij deze integratie kunnen gebruikers zich aanmelden bij Marketo Engage en andere Experience Cloud-toepassingen met een gemeenschappelijke Adobe-id.

## Profielniveaus

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
  <td><strong>Marketo Engage-productbeheerder</strong></td>
  <td>Een persoon die toegang heeft gekregen tot Marketo Engage met administratieve voorrechten. Toegewezen rol in Marketo Engage, niet in Adobe Admin Console.</td>
 </tr>
 <tr>
  <td><strong>Marketo Engage-gebruiker</strong></td>
  <td>Een persoon die toegang heeft gekregen tot Marketo Engage. Geen beheerdersrechten.</td>
 </tr>
</table>

## Veelgestelde vragen

**Wat is Adobe Identity?**

Adobe Identity Management System bestaat uit drie componenten.

* Adobe-identiteitsdienst: Verwerkt verificatie en validatie van de eindgebruiker, inclusief federatie en runtime Single-Sign-On (SSO).

* Adobe Admin Console: De Admin Console biedt een centrale locatie voor het beheer van de rechten van Adobe in uw gehele organisatie. Het behandelt gebruikersbeheer, de wolkendienst, Desktoplicentierechten, federatieconfiguratie, en verstrekt de veiligheidseigenschappen van de verliespreventie.

* Adobe-gebruikersbeheer-API (UMAPI): Hiermee kunnen organisaties gebruikers en rechten van ondernemingen in de Adobe Admin Console op API-niveau beheren.

**Wat is het verschil tussen een Adobe-productbeheerder en een Marketo Engage-beheerder?**

* Adobe Product Admin is een nieuwe rol in het Marketo-platform.
* Adobe Product Admin-rol wordt toegekend aan gebruikers die als productbeheerder in Adobe Admin Console zijn toegevoegd
* Adobe Product Admin is een alleen-lezen rol en kan niet worden bewerkt of verwijderd uit Marketo Engage.
* Adobe Product Admin heeft dezelfde rechten en rechten als standaard Marketo Admin.
* De rol van Marketo Engage Admin is nog steeds Admin en wordt toegekend aan een gebruiker in Marketo Engage.

**Is er een wijziging in de API-clientondersteuning?**

Ja. Degenen die aan Adobe IMS zijn aangemeld, kunnen niet alle bestaande Marketo-API&#39;s voor gebruikersbeheer gebruiken. Voor het uitnodigen, bijwerken en verwijderen van handelingen van gebruikers [IMS API&#39;s](https://www.adobe.io/apis/experienceplatform/umapi-new.html) te gebruiken. Voor rolbeheer zijn de Marketo-API&#39;s voor gebruikersbeheer nog steeds van toepassing.

**Met wie nemen we contact op voor ondersteuning?**

U zou de standaardprocedure voor het contacteren volgen [Marketo-ondersteuning](https://nation.marketo.com/t5/support/ct-p/Support).

**Zijn Marketo-gebruikersrollen (binnen werkruimten) beheerd in Adobe Admin Console?**

Nee. Het beheer van de Rol van de gebruiker (binnen werkruimten) wordt voltooid in Marketo Engage.

**Ik ben Marketo Admin en heb geen toegang tot de Admin Console. Hoe krijg ik toegang?**

Om het even welk Systeem van de Adobe of Admin van het Product dat toegang tot de Admin Console van uw organisatie heeft kan u toegang geven. Als u niet zeker bent wie in uw organisatie admin voorrechten in de console heeft, contacteer [Adobe Klantenservice](https://helpx.adobe.com/contact.html).

**Hoe kan een beheerder gebruikers toevoegen aan Marketo Sales Connect?**

Hoewel er een productkaart in Admin Console voor Sales Connect is, mag Admin Console niet worden gebruikt om gebruikers toe te voegen/te beheren. Met de volgende koppeling kunnen beheerders gebruikers beheren via Marketo Sales Connect: [https://toutapp.com/next#settings/admin/user-management](https://toutapp.com/next#settings/admin/user-management).

**Waar kan ik meer leren over de Adobe Admin Console?**

[https://helpx.adobe.com/enterprise/admin-guide.html](https://helpx.adobe.com/enterprise/admin-guide.html).

**Ga ik nog steeds naar het gedeelte Beheer in Marketo om wijzigingen aan te brengen in het account?**

Nee, u moet naar [account.adobe.com](https://account.adobe.com).

**Hoe werkt dit met Marketo Universal ID?**

De gebruikers aan boord van een Adobe-identiteit hebben naadloos toegang tot alle abonnementen voor IMS via de abonnementsschakelaar in het product.

**Werkt dit met SSO?**

Ja. Marketo-integratie met Adobe IMS ondersteunt gebruikers van Universal ID en SSO. De SSO wordt nu aangestuurd door Adobe IMS en is ingesteld op organisatieniveau in de Adobe Admin Console. [Meer informatie hier](https://helpx.adobe.com/enterprise/using/set-up-identity.html).

**Hoe werkt apparaatautorisatie?**

Adobe IMS biedt momenteel geen ondersteuning voor functies zoals Marketo voor apparaatautorisatie.

**Is het nog mogelijk om de functie &quot;Aanmelden bij gebruiker uitnodigen&quot; te gebruiken om de aanmelding uniek te maken via onze e-mail?**

Nee. De uitnodigingsworkflow van de gebruiker is niet meer actief wanneer een abonnement op IMS is ingeschakeld, zodat de functie niet langer geldig is. Voor een Adobe-identiteit moet de identiteit van de gebruiker door het e-mailbericht worden gestuurd.

**Voor Adobe IMS, hebben wij de optie om Adobe ID, Enterprise ID, of Federated ID te gebruiken?**

Ja, u bepaalt het type identiteit om uw organisatiesteun te hebben. Hier vindt u meer informatie: [Identiteitsoverzicht](https://helpx.adobe.com/enterprise/using/identity.html) en hier: [Identiteit instellen](https://helpx.adobe.com/enterprise/using/set-up-identity.html).

>[!MORELIKETHIS]
>
>* [Beheerdersinstellingen](/help/marketo/product-docs/administration/marketo-with-adobe-identity/admin-setup.md)
>* [Een productbeheerder toevoegen of verwijderen](/help/marketo/product-docs/administration/marketo-with-adobe-identity/add-or-remove-a-product-admin.md)
>* [Een gebruiker toevoegen of verwijderen](/help/marketo/product-docs/administration/marketo-with-adobe-identity/add-or-remove-a-user.md)

