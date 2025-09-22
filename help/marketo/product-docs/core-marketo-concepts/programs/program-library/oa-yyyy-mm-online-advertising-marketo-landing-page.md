---
description: OA-YYYY-MM-Online Advertising Marketo Landing Page - Marketo Docs - Productdocumentatie
title: Openingspagina van Advertising Marketo OA-YYYY-MM-Online
feature: Programs
exl-id: f7f17792-cc16-4a99-8683-68796770e42c
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '485'
ht-degree: 0%

---

# Openingspagina van Advertising Marketo OA-YYYY-MM-Online {#oa-yyyy-mm-online-advertising-marketo-landing-page}

Dit is een voorbeeld van een online programma voor het bijhouden van advertenties, waaronder een Marketo Landing Page met registratieformulier en een Marketo Default Program. De koppeling naar het aanbod kan worden weergegeven op de pagina Hartelijk dank, in een e-mail met dank of in beide.

Voor verdere strategiehulp of hulp die een programma aanpassen, gelieve te contacteren het Team van de Rekening van Adobe of de [ Adobe Professional Services ](https://business.adobe.com/customers/consulting-services/main.html){target="_blank"} pagina te bezoeken.

## Kanaaloverzicht {#channel-summary}

<table style="table-layout:auto">
 <tbody>
  <tr>
   <th>Kanaal</th>
   <th>Lidmaatschapsstatus</th>
   <th>Analysegedrag</th>
   <th>Programmatype</th>
  </tr>
  <tr>
   <td>Online Advertising</td>
   <td>01 - Lid
<br/> 02 - Behoefte - Succes</td>
   <td>Inclusief</td>
   <td>Standaard</td>
  </tr>
 </tbody>
</table>

## Het programma bevat de volgende Assets {#program-contains-the-following-assets}

<table style="table-layout:auto">
 <tbody>
  <tr>
   <th>Type</th>
   <th>Sjabloonnaam</th>
   <th>Elementnaam</th>
  </tr>
  <tr>
   <td>Formulier</td>
   <td> </td>
   <td>Registratie van FM-inhoud</td>
  </tr>
  <tr>
   <td>E-mail</td>
   <td><a href="/help/marketo/product-docs/core-marketo-concepts/programs/program-library/quick-start-email-template.md" target="_blank">E-mailsjabloon snel starten</a></td>
   <td>01-E-mail-Dank u</td>
  </tr>
  <tr>
   <td>Openingspagina</td>
   <td><a href="/help/marketo/product-docs/core-marketo-concepts/programs/program-library/quick-start-landing-page-template.md" target="_blank">LP-sjabloon snel starten</a></td>
   <td>01 - LP - Registratie</td>
  </tr>
   <tr>
   <td>Openingspagina</td>
   <td><a href="/help/marketo/product-docs/core-marketo-concepts/programs/program-library/quick-start-landing-page-template.md" target="_blank">LP-sjabloon snel starten</a></td>
   <td>02 - LP - Dank u</td>
  </tr>
   <tr>
   <td>Lokaal rapport</td>
   <td> </td>
   <td>E-mailprestaties</td>
  </tr>
  <tr>
   <td>Lokaal rapport</td>
   <td> </td>
   <td>Prestaties van bestemmingspagina</td>
  </tr>
  <tr>
   <td>Slimme campagne</td>
   <td> </td>
   <td>00 - Programma voor overname van vastleggingen</td>
  </tr>
  <tr>
   <td>Slimme campagne</td>
   <td> </td>
   <td>01 - Formulier invullen</td>
  </tr>
  <tr>
   <td>Slimme campagne</td>
   <td> </td>
   <td>02 - Betrokken (succes van programma)</td>
  </tr>
  <tr>
   <td>Map</td>
   <td> </td>
   <td>Assets - alle creatieve middelen onderbrengen
<br/> (submappen voor e-mails en bestemmingspagina's)  </td>
  </tr>
  <tr>
   <td>Map</td>
   <td> </td>
   <td>Campagnes - alle slimme campagnes onderbrengen</td>
  </tr>
  <tr>
   <td>Map</td>
   <td> </td>
   <td>Rapporten</td>
  </tr>
 </tbody>
</table>

![](assets/oa-yyyy-mm-online-advertising-marketo-landing-page-1.png)

## Mijn tokens inbegrepen {#my-tokens-included}

<table style="table-layout:auto">
 <tbody>
  <tr>
   <th>Type token</th>
   <th>Tokennaam</th>
   <th>Waarde</th>
  </tr>
  <tr>
   <td>RTF</td>
   <td><code>{{my.Content-Description}}</code></td>
   <td>Dubbelklik voor details
<br/><code><--My Content Description Here--></code>
<br/> geef deze inhoudsbeschrijving op het programmaniveau, onder het Mijn Tokens lusje uit.
<br/> u zult leren:
<li>Opsommingsteken 1</li>
<li>Opsommingsteken 2</li>
<li>Opsommingsteken 3</li></td>
  </tr>
  <tr>
   <td>Tekst</td>
   <td><code>{{my.Content-Title}}</code></td>
   <td><code><--My Content Title Here--></code></td>
  </tr>
  <tr>
   <td>Tekst</td>
   <td><code>{{my.Content-Type}}</code></td>
   <td><code><--My Content Type Here--></code></td>
  </tr>
  <tr>
   <td>Tekst</td>
   <td><code>{{my.Content-URL}}</code></td>
   <td>my.ContentURL?without=http://</td>
  </tr>
  <tr>
   <td>Tekst</td>
   <td><code>{{my.Email-FromAddress}}</code></td>
   <td>PlaceholderFrom.email@mydomain.com</td>
  </tr>
  <tr>
   <td>Tekst</td>
   <td><code>{{my.Email-FromName}}</code></td>
   <td><code><--My From Name Here--></code></td>
  </tr>
  <tr>
   <td>Tekst</td>
   <td><code>{{my.Email-ReplyToAddress}}</code></td>
   <td>reply-to.email@mydomain.com</td>
  </tr>
  <tr>
   <td>Tekst</td>
   <td><code>{{my.PageURL-ThankYou}}</code></td>
   <td>My.BedanktYouPageURL?zonder de http://</td>
  </tr>
 </tbody>
</table>

SCHERM VAN HET PROGRAMMA

## Conflictregels {#conflict-rules}

* **de Markeringen van het Programma**
   * Creeer markeringen in dit abonnement - _Geadviseerde_
   * Negeren

* **het Bestaan malplaatje van de Pagina met de zelfde naam**
   * Originele sjabloon kopiëren
   * Het bestemmingsmalplaatje van het gebruik - _geadviseerde_

* **Beelden met de zelfde naam**
   * Beide bestanden behouden
   * Vervang punt in dit abonnement - _geadviseerde_

* **E-mailmalplaatjes met de zelfde naam**
   * Beide sjablonen behouden
   * Vervang bestaand malplaatje - _geadviseerde_

SCHERM VAN CONFLICTREGELS

## Aanbevolen procedures {#best-practices}

* Nadat het inhoudsprogramma is geïmporteerd, verplaatst u het formulier van een lokaal element naar een algemeen element in de Design Studio.
   * Door het aantal formulieren te verminderen en meer algemene middelen van de Design Studio te gebruiken, kunt u het ontwerp van uw programma en het beheer ervan meer schaalbaar maken. Het biedt ook flexibiliteit bij regelmatige compatibiliteitsupdates voor velden, de taal van de opt-in, enz.

* U kunt overwegen de sjablonen in uw geïmporteerde programma bij te werken om de sjablonen met branding te gebruiken of de nieuw geïmporteerde sjabloon bij te werken naar uw merk door deze toe te voegen in een fragment of door de juiste logo-/voettekstinformatie.

* Met Programmatags kunt u rapporten filteren op verschillende bronnen van Online Advertising.

* U kunt overwegen de naamgevingsconventie van dit programmavoorbeeld bij te werken en deze uit te lijnen met uw naamgevingsconventie.

>[!NOTE]
>
>Herinner me om de Mijn Symbolische Waarden op het programmamalplaatje bij te werken en telkens als u het programma gebruikt, zoals nodig.

>[!TIP]
>
>Vergeet niet de campagne &quot;02 - Betrokken (succes programma)&quot; te activeren om succes te volgen! Doe dit _alvorens_ uw vorm levend is en e-mails worden verzonden.

>[!IMPORTANT]
>
>Mijn tokens die naar een URL verwijzen, kunnen niet de URL http:// of https:// bevatten anders werkt de koppeling niet correct binnen het element.
