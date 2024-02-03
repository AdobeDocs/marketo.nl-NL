---
description: Adobe Identity Management - Overzicht - Marketo Docs - de Documentatie van het Product
title: Overzicht van Adobe Identity Management
exl-id: 18ddeebc-bc89-411c-9d2c-23df6841cb3a
feature: Marketo with Adobe Identity
source-git-commit: 6f9790c2243407f2622970d228c9de6be7697df6
workflow-type: tm+mt
source-wordcount: '402'
ht-degree: 0%

---

# Overzicht van Adobe Identity Management {#adobe-identity-management-overview}

Alle nieuwe Adobe Marketo Engage-abonnementen (31 juli 2023 of hoger) worden geïntegreerd met het Adobe Identity Management System. Bestaande Marketo-abonnementen worden momenteel gemigreerd naar het Adobe Identity Management System bij vernieuwings- en/of uitbestedingsgebeurtenissen. Migraties buiten een gebeurtenis voor vernieuwing of uitbesteding worden momenteel niet ondersteund.

>[!NOTE]
>
>Marketo Support kan geen updates bieden voor de migratie naar Adobe IMS. Het accountteam van de Adobe zal de komende maanden het geschatte tijdpad bereiken. Zie voor meer informatie [dit artikel](/help/marketo/product-docs/administration/marketo-with-adobe-identity/subscription-and-user-migration/understanding-marketo-subscription-and-user-migration-to-the-adobe-admin-console.md){target="_blank"}, and the [Frequently Asked Questions](/help/marketo/product-docs/administration/marketo-with-adobe-identity/faq.md){target="_blank"}.

Voor abonnementen op Adobe-id wordt de Adobe Admin Console gebruikt voor gebruikersbeheer. Identiteitsgerelateerde concepten, zoals Single Sign On, worden ook beheerd in de Admin Console.

* Meer informatie over de [Adobe Admin Console](https://helpx.adobe.com/nl/enterprise/using/admin-console.html){target="_blank"}.
* Meer informatie over [uw organisatie voor Adoben instellen voor uw Marketo-abonnement](https://helpx.adobe.com/enterprise/using/set-up-identity.html){target="_blank"}.

>[!NOTE]
>
>Als u Single Sign On wilt implementeren en uw abonnement is aangemeld bij Adobe Identity zonder SSO geïmplementeerd in de Adobe Org, dient u een ticket in bij [Marketo-ondersteuning](https://nation.marketo.com/){target="_blank"} en specificeer het onderwerp als &quot;Marketo op Admin Console, die SSO uitvoeren.&quot;

## Profielniveaus {#profile-levels}

Adobe Marketo Engage-abonnementen op het Adobe Identity Management System ondersteunen verschillende profielen. Hier volgen de typen gebruikersprofielen die relevant zijn voor deze integratie.

<table>
 <tr>
  <td><strong>Adobe Admin Console System Admin</strong></td>
  <td>Verantwoordelijk voor het opzetten van identiteitsconcepten voor de Adobe org en het product van de Marketo Engage in Adobe Admin Console. Toegewezen rol bij de opstelling van de Adobe organisatie.</td>
 </tr>
 <tr>
  <td><strong>Adobe Admin Console-productbeheerder</strong></td>
  <td>Verantwoordelijk voor het recht van gebruikers op het product van de Marketo Engage in de Adobe Admin Console. Toegewezen rol in Adobe Admin Console.</td>
 </tr>
 <tr>
  <td><strong>Adobe Admin Console-productprofielbeheer</strong></td>
  <td>Verantwoordelijk voor het beheer van gebruikers binnen een productprofiel. Ze kunnen gebruikers buiten dat specifieke profiel niet beheren. Beheerders van productprofielen hebben alleen toegang tot de Marketo-toepassing als ze als gebruiker aan het productprofiel zijn toegevoegd. Hun rol zou nog een standaardgebruiker zijn (standaardwerkruimte als meer dan één werkruimte heeft).
</td>
 </tr>
 <tr>
  <td><strong>Admin voor Marketo Engage</strong></td>
  <td>Een persoon die toegang heeft gekregen tot een Marketo Engage met administratieve voorrechten. Toegewezen rol in Marketo Engage, niet in Adobe Admin Console.</td>
 </tr>
 <tr>
  <td><strong>Gebruiker van Marketo Engage</strong></td>
  <td>Een persoon die toegang heeft gekregen tot Marketo Engage. Geen beheerdersrechten.</td>
 </tr>
</table>

## Veelgestelde vragen {#faq}

Veelgestelde vragen [hier te vinden](/help/marketo/product-docs/administration/marketo-with-adobe-identity/faq.md){target="_blank"}.

>[!MORELIKETHIS]
>
>* [Beheerdersinstellingen](/help/marketo/product-docs/administration/marketo-with-adobe-identity/admin-setup.md){target="_blank"}
>* [Een productbeheerder toevoegen of verwijderen](/help/marketo/product-docs/administration/marketo-with-adobe-identity/add-or-remove-a-product-admin.md){target="_blank"}
>* [Een gebruiker toevoegen of verwijderen](/help/marketo/product-docs/administration/marketo-with-adobe-identity/add-or-remove-a-user.md){target="_blank"}
