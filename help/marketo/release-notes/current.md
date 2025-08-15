---
description: Huidige aanvullende informatie - Documentatie voor Marketo - Productdocumentatie
title: Opmerkingen bij de huidige release
exl-id: a2eccad5-73ad-48f9-8091-51cee23824e1
feature: Release Information
source-git-commit: 8101d9c73571948847d00dfc21f21c39bcd1d975
workflow-type: tm+mt
source-wordcount: '514'
ht-degree: 2%

---

# Opmerkingen bij de release: augustus 2025 {#release-notes-aug-25}

Hieronder vindt u alle functies die zijn inbegrepen in de release van 25 augustus. Raadpleeg de Adobe Marketo Engage-editie voor informatie over de beschikbaarheid van functies.

De Nota&#39;s van de Versie specifiek voor Adobe Dynamic Chat [ kunnen hier ](/help/marketo/release-notes/dynamic-chat.md){target="_blank"} worden gevonden.

>[!AVAILABILITY]
>
>De eigenschappen die door een ster (![ worden aangegeven ster ](assets/yellow-star.png)) worden betaald toe:voegen-ons. Neem contact op met je Marketo Engage-vertegenwoordiger voor meer informatie.

## Standaardfuncties van releasecyclus {#standard-release-cycle-features}

De volgende eigenschappen vallen onder de standaardversiecyclus en zullen beginnen om op **22 augustus, 2025**, met een gefaseerde uitrol van resterende eigenschappen in de verdere weken worden vrijgegeven. De functies en datums van de release kunnen worden gewijzigd. Controleer de status naast elke functie.

<table style="table-layout:auto">
 <tbody>
 <tr>
   <th style="width:65%">Functie</th>
   <th style="width:10%">Status</th>
   <th style="width:25%">Documentatie</th>
  </tr>
  <tr>
   <td><strong> E-mail Designer - het Melden van </strong>: De rapporten van de Prestaties van de Verbinding van e-mail en E-mail van de Verbinding tonen nu gegevens van e-mail die gebruikend nieuwe e-mail Designer worden gecreeerd.</td>
   <td><i>Binnenkort beschikbaar</i></td>
   <td><i>Binnenkort beschikbaar</i></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong> E-mail Designer - de Optimalisering van de Voorproef van de E-mail </strong>: Sommige gebruikers ervoeren langzamere ladingstijden toen het proberen om hun e-mail in de e-mail/e-mailmalplaatje/fragment detailspagina voor te vertonen. Deze ervaring is geoptimaliseerd voor 60% snellere laadtijden.</td>
   <td><i>Binnenkort beschikbaar</i></td>
   <td>nvt</td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong> E-mail Designer - de Correcties van het Malplaatje </strong>: Sommige uit-van-de-doos malplaatjes hadden teruggevende kwesties (b.v., die niet correct op bepaalde browsers/donkere wijze teruggeven, verkeerd gerichte beelden, verkeerd geplaatste de knopen van CTA, en een paar meer). Deze zijn allemaal opgelost met deze release.</td>
   <td><i>Binnenkort beschikbaar</i></td>
   <td>nvt</td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong> E-mail Designer - het Vergrendelen van de Inhoud </strong>: Eerder, als een e-mailmalplaatje met inhoudsafsluiting werd gecreeerd en het malplaatje werd gebruikt om een e-mail tot stand te brengen, zou inhoudsafscherping blijven zelfs wanneer e-mail werd teruggesteld of "veranderingsontwerp"werd geselecteerd. Dit probleem is opgelost met deze release.</td>
   <td><i>Binnenkort beschikbaar</i></td>
   <td>nvt</td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong> E-mail Designer - AutoComplete Verwijdering </strong>: De optie Autocomplete in de symbolische verpersoonlijkingsredacteur wees aan verkeerde voorwerpen en is verwijderd. Op dit moment zijn er geen plannen om het programma opnieuw uit te voeren.</td>
   <td>Verzonden</td>
   <td>nvt</td>
  </tr>
 </tbody>
</table>
<br/>

## Aankondigingen {#announcements}

* **Eind van het Leven van de Identiteit van Marketo Engage**: In Augustus 2025, begon Adobe fasing-out steun voor de Identiteit van Marketo Engage (het programma openen via `login.marketo.com`). Om onderbroken toegang tot Marketo Engage te verhinderen, moet u overgang aan [ Identiteit van Adobe ](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview){target="_blank"} uiterlijk 30 September, 2025.

   * _IP de Afschrijving van Beperkingen_: Steun voor [ Beperkende Marketo Logins die op IP ](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/settings/restrict-marketo-logins-based-on-ip){target="_blank"} worden gebaseerd eindigde op 30 juli, 2025. De functie blijft actief totdat de overgang naar Adobe Identity is voltooid. Binnenkort wordt er een nieuwe functie voor toegangsbeheer op basis van locatie beschikbaar voor Adobe Identity in de Adobe Admin Console.

   * _Enige Sign-On (SSO) Verdringing_: Steun voor [ Identiteit SSO van Marketo ](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/additional-integrations/add-single-sign-on-to-a-portal){target="_blank"} geëindigd op 30 Juli, 2025. De functie blijft actief totdat de overgang naar Adobe Identity is voltooid. Single Sign-On voor Adobe Identity in de Adobe Admin Console moet afzonderlijk worden geconfigureerd. Voor opstellingsstappen, zie [ de identiteit van de Opstelling en Enige Sign-On ](https://helpx.adobe.com/enterprise/using/set-up-identity.html){target="_blank"}.

* **Rest API &quot;access_token&quot;de Afschrijving van de Parameter**: De `access_token` vraagparameter die wordt gebruikt om de vraag van Marketo REST API voor authentiek te verklaren wordt afgekeurd en zal niet beschikbaar na 31 oktober 2025 zijn. Alle nieuwe en bestaande integratie zouden vraag REST API gebruikend de kopbal van de &quot;Vergunning&quot;voor authentiek moeten verklaren, [ zoals hier beschreven ](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/authentication){target="_blank"}.

* **SOAP API Verdringing**: Steun voor Marketo SOAP API zal op 31 Oktober, 2025 eindigen. De diensten die SOAP API mogelijkheden gebruiken zouden aan [ REST API ](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/rest-api){target="_blank"} moeten worden gemigreerd.
