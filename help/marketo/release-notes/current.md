---
description: Huidige aanvullende informatie - Documentatie voor Marketo - Productdocumentatie
title: Opmerkingen bij de huidige release
exl-id: a2eccad5-73ad-48f9-8091-51cee23824e1
feature: Release Information
source-git-commit: fddc2f24d9a66146f567c762305ab2825c2f29ae
workflow-type: tm+mt
source-wordcount: '473'
ht-degree: 2%

---

# Opmerkingen bij de release: mei 2025 {#release-notes-may-25}

Hieronder vindt u alle functies die zijn inbegrepen in de release van 25 mei. Raadpleeg de Adobe Marketo Engage-editie voor informatie over de beschikbaarheid van functies.

De Nota&#39;s van de Versie specifiek voor Adobe Dynamic Chat [ kunnen hier ](/help/marketo/release-notes/dynamic-chat.md){target="_blank"} worden gevonden.

>[!AVAILABILITY]
>
>De eigenschappen die door een ster (![ worden aangegeven ster ](assets/yellow-star.png)) worden betaald toe:voegen-ons. Neem contact op met je Marketo Engage-vertegenwoordiger voor meer informatie.

## Standaardfuncties van releasecyclus {#standard-release-cycle-features}

De volgende eigenschappen vallen onder de standaardversiecyclus en zullen beginnen om op **23 mei, 2025**, met een gefaseerde uitrol van resterende eigenschappen in de verdere weken worden vrijgegeven. De functies en datums van de release kunnen worden gewijzigd. Controleer de status naast elke functie.

<table style="table-layout:auto"> 
 <tbody>
 <tr> 
   <th style="width:65%">Functie</th> 
   <th style="width:10%">Status</th>
   <th style="width:25%">Documentatie</th>
  </tr>
  <tr> 
   <td><strong> de Verenigbaarheid van het Malplaatje voor E-mail Designer </strong>: E-mailmalplaatjes van de klassieke e-mailredacteur zijn nu compatibel met nieuwe <a href="/help/marketo/product-docs/email-marketing/email-designer/overview.md"> E-mailDesigner </a>.</td>
   <td><i>Binnenkort beschikbaar</i></td>
   <td><i>Binnenkort beschikbaar</i></td>
  </tr>
  <tr> 
   <td> </td> 
   <td> </td>
   <td> </td>
  </tr>
  <tr> 
   <td><strong> de Tokens van de Trekker voor Om het even welk Attribuut </strong>: Uitgebreide lijst van trekkertokens om het gebruiken van gegevens van om het even welk activiteitenattribuut in de Slimme gebieden van de Campagne te steunen.</td> 
   <td><i>Binnenkort beschikbaar</i></td>
   <td><i>Binnenkort beschikbaar</i></td>
  </tr>
  <tr> 
   <td> </td> 
   <td> </td>
   <td> </td>
  </tr>
  <tr> 
   <td><strong> E-mailInhoud Personalization </strong>: Marketo Engage volgt nu de zelfde camel gevalsyntaxis zoals de andere de toepassingstekenen van AEP zodat wordt een verenigbare ervaring verstrekt over de producten van Adobe DX. Alle standaardtokens en Marketo Engage-specifieke tokens zoals Lid, Programma en Mijn tokens zijn beschikbaar in de nieuwe e-mail-Designer.</td> 
   <td><i>Binnenkort beschikbaar</i></td>
   <td><i>Binnenkort beschikbaar</i></td>
  </tr>
  <tr> 
   <td> </td> 
   <td> </td>
   <td> </td>
  </tr>
  <tr> 
   <td><strong> Op rol-gebaseerde Controle van de Toegang voor E-mail Designer Assets </strong>: Een nieuwe verbetering aan het op rol-gebaseerde toegangsbeheersysteem (RBAC) verstrekt meer korrelige toestemmingen en beter gebruikersbeheer voor activa aangedreven door nieuwe E-mail Designer.</td> 
   <td><i>Binnenkort beschikbaar</i></td>
   <td><i>Binnenkort beschikbaar</i></td>
  </tr>
  <tr> 
   <td> </td> 
   <td> </td>
   <td> </td>
  </tr>
  <tr> 
   <td><strong> het Klonen E-mails die in E-mail Designer </strong> worden gecreeerd: U hebt nu de capaciteit om een bestaande e-mail te klonen die gebruikend nieuwe E-mail Designer wordt gecreeerd.</td> 
   <td><i>Binnenkort beschikbaar</i></td>
   <td><i>Binnenkort beschikbaar</i></td>
  </tr>
  <tr> 
   <td> </td> 
   <td> </td>
   <td> </td>
  </tr>
  <tr> 
   <td><strong> de Integratie van GenStudio </strong>: Integreer GenStudio voor prestaties marketing van binnen e-mail om marketing efficiency te verbeteren en merkconsistentie te handhaven.</td> 
   <td><i>Binnenkort beschikbaar</i></td>
   <td><i>Binnenkort beschikbaar</i></td>
  </tr>
 </tbody> 
</table>
<br/>

## Aankondigingen {#announcements}

* **Nieuwe Eigenschap van de Analyse - Openbare Beta**: [ Geavanceerde Analytics van BI ](/help/marketo/product-docs/reporting/advanced-bi-analytics/overview.md){target="_blank"} (vroeger genoemd als Ontdekkingsreiziger van de Opbrengst en Geavanceerde Report Builder) begon uit te rollen aan alle huidige gebruikers van de Ontdekkingsreiziger van de Ontdekkingsreiziger van de Opbrengst midden-April. Dit nieuwe hulpmiddel biedt een flexibele rapportage- en visualisatieinterface voor Marketo Engage-gegevens, die gedetailleerde informatie biedt over progressie, prestaties en meer. Deze server biedt een rijkere interactiviteit en visualisatie, snellere prestaties en een naadloze en intuïtievere gebruikerservaring.

Voor toegang tot deze functie moet u de add-on Advanced BI Analytics hebben aangeschaft. Neem contact op met het Adobe-accountteam (uw accountmanager) voor meer informatie.

* **Rest API &quot;access_token&quot;de Afschrijving van de Parameter**: De `access_token` vraagparameter die wordt gebruikt om de vraag van Marketo REST API voor authentiek te verklaren wordt afgekeurd en zal niet beschikbaar na 31 oktober 2025 zijn. Alle nieuwe en bestaande integratie zouden vraag REST API gebruikend de kopbal van de &quot;Vergunning&quot;voor authentiek moeten verklaren, [ zoals hier beschreven ](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/authentication){target="_blank"}.

* **SOAP API Verdringing**: Steun voor Marketo SOAP API zal op 31 Oktober, 2025 eindigen. De diensten die SOAP API mogelijkheden gebruiken zouden aan [ REST API ](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/rest-api){target="_blank"} moeten worden gemigreerd.
