---
description: Overzicht - Marketo Docs - Productdocumentatie
title: Overzicht
hide: true
hidefromtoc: true
source-git-commit: 306e08b08bf63fe51778dc51ccb9cb971fed2f4b
workflow-type: tm+mt
source-wordcount: '658'
ht-degree: 0%

---

# Overzicht {#overview}

Als uw Adobe Marketo Engage op of na 21-04-21 uw-abonnement is ingericht, wordt deze geïntegreerd met het Adobe Identity Management System. Met AIMS kunnen gebruikers zich aanmelden bij Marketo Engage- en andere Experience Cloud-toepassingen met een gemeenschappelijke Adobe-id.

## Profielniveaus

Er zijn drie profielniveaus.

<table>
 <tr>
  <td><strong>Systeembeheerder</strong></td>
  <td>Verantwoordelijk voor het opzetten van identiteitsconcepten voor de Adobe org en het Marketo Engage product in de Adobe Admin Console.</td>
 </tr>
 <tr>
  <td><strong>Productbeheerder</strong></td>
  <td>Verantwoordelijk voor het recht van gebruikers op het product Marketo Engage in de Adobe Admin Console.</td>
 </tr>
 <tr>
  <td><strong>Gebruiker</strong></td>
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
* Het is een alleen-lezen rol en kan niet worden bewerkt of verwijderd uit Marketo.
* Deze heeft dezelfde rechten en rechten als standaard Marketo Admin.

**Is er een wijziging in de API-clientondersteuning?**

Ja. Degenen die aan Adobe IMS zijn aangemeld, kunnen de bestaande Marketo-API&#39;s voor gebruikersbeheer niet gebruiken. Zij zouden [IMS APIs](https://www.adobe.io/apis/experienceplatform/umapi-new.html) gebruiken.

**Met wie nemen we contact op voor ondersteuning?**

U zou de standaardprocedure volgen om [Marketo Support](https://nation.marketo.com/t5/support/ct-p/Support) te contacteren.

**Zijn Marketo-gebruikersrollen (binnen werkruimten) beheerd in Adobe Admin Console?**

Nee. Gebruikersrolbeheer (binnen werkruimten) wordt voltooid in Marketo.

**Ik ben Marketo Admin en heb geen toegang tot de Admin Console. Hoe krijg ik toegang?**

Om het even welke systeem of productbeheerder die toegang tot de Admin Console van uw organisatie heeft kan u toegang geven. Als u niet zeker weet wie binnen uw organisatie beheerdersrechten heeft in de console, neemt u contact op met [Adobe klantenservice](https://helpx.adobe.com/contact.html).

**Hoe kan een beheerder gebruikers toevoegen aan Marketo Sales Connect?**

Hoewel voor Sales Connect een productkaart in AC wordt weergegeven, mag AC niet worden gebruikt om gebruikers toe te voegen/te beheren. Met de volgende koppeling kunnen beheerders gebruikers beheren via Marketo Sales Connect: [https://toutapp.com/next#settings/admin/user-management](https://toutapp.com/next#settings/admin/user-management).

**Waar kan ik meer leren over de Adobe Admin Console?**

[https://helpx.adobe.com/enterprise/admin-guide.html](https://helpx.adobe.com/enterprise/admin-guide.html).

**Ga ik nog steeds naar het gedeelte Beheer in Marketo om wijzigingen aan te brengen in het account?**

Nee, u moet naar [account.adobe.com](https://account.adobe.com) navigeren.

**Hoe werkt dit met Marketo Universal ID?**

De gebruikers aan boord van een Adobe-identiteit hebben naadloos toegang tot alle abonnementen voor IMS via de abonnementsschakelaar in het product.

**Werkt dit met SSO?**

Ja. Marketo-integratie met Adobe IMS ondersteunt gebruikers van Universal ID en SSO. De SSO wordt nu aangestuurd door Adobe IMS en is ingesteld op organisatieniveau in de Adobe Admin Console. [Klik hier](https://helpx.adobe.com/enterprise/using/set-up-identity.html) voor meer informatie.

**Hoe werkt apparaatautorisatie?**

Adobe IMS biedt momenteel geen ondersteuning voor functies zoals Marketo voor apparaatautorisatie.

**Is het nog mogelijk om de functie &quot;Aanmelden bij gebruiker uitnodigen&quot; te gebruiken om de aanmelding uniek te maken via onze e-mail?**

Nee. De uitnodigingsworkflow van de gebruiker is niet meer actief wanneer een abonnement op IMS is ingeschakeld, zodat de functie niet langer geldig is. Voor een Adobe-identiteit moet de identiteit van de gebruiker door het e-mailbericht worden gestuurd.

**Voor Adobe IMS, hebben wij de optie om Adobe ID, Enterprise ID, of Federated ID te gebruiken?**

Ja, u bepaalt het type identiteit om uw organisatiesteun te hebben. Meer informatie [hier](https://helpx.adobe.com/enterprise/using/identity.html) en [hier](https://helpx.adobe.com/enterprise/using/set-up-identity.html).