---
description: WR-YYYY-MM-Web Request Program - Marketo Docs - Productdocumentatie
title: WR-YYYY-MM-Web Request-programma
feature: Programs
exl-id: 4acaa2d0-3329-4027-acbd-ae2e0ec6f7c5
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '400'
ht-degree: 1%

---

# WR-YYYY-MM-Web Request-programma {#wr-yyyy-mm-web-request-program}

Dit is een voorbeeldprogramma ideaal voor contactverzoek, citaatverzoek, demoverzoek, of proefverzoekvormen die een StandaardProgramma van Marketo Engage gebruiken. Kan worden gebruikt met Marketo-bestemmingspagina&#39;s of als een ingesloten formulier op niet-Marketo bestemmingspagina&#39;s. Bij het verzenden van het formulier wordt een waarschuwingsbericht naar een opgegeven persoon verzonden.

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
   <td>Webverzoek</td>
   <td>01 - Betrokken - Succes</td>
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
   <td>FM-WebRequestForm</td>
  </tr>
  <tr>
   <td>E-mail</td>
   <td><a href="/help/marketo/product-docs/core-marketo-concepts/programs/program-library/quick-start-email-template.md" target="_blank">E-mailsjabloon snel starten</a></td>
   <td>Alert-WebRequest</td>
  </tr>
  <tr>
   <td>Openingspagina</td>
   <td><a href="/help/marketo/product-docs/core-marketo-concepts/programs/program-library/quick-start-landing-page-template.md" target="_blank">LP-sjabloon snel starten</a></td>
   <td>01 - LP - Verzoek</td>
  </tr>
  <tr>
   <td>Openingspagina</td>
   <td><a href="/help/marketo/product-docs/core-marketo-concepts/programs/program-library/quick-start-landing-page-template.md" target="_blank">LP-sjabloon snel starten</a></td>
   <td>02 - LP - Dank u</td>
  </tr>
  <tr>
   <td>Lokaal rapport</td>
   <td> </td>
   <td>Prestaties van bestemmingspagina</td>
  </tr>
   <tr>
   <td>Slimme campagne</td>
   <td> </td>
   <td>Nieuwe persoon van webverzoek</td>
  </tr>
   <tr>
   <td>Slimme campagne</td>
   <td> </td>
   <td>Nieuwe persoon van Webinar</td>
  </tr>
  <tr>
   <td>Map</td>
   <td> </td>
   <td>Assets - Houdt alle creatieve middelen in huis
<br/> (submappen voor waarschuwings- en bestemmingspagina's)</td>
  </tr>
  <tr>
   <td>Map</td>
   <td> </td>
   <td>Campagnes - Houdt alle Slimme Campagnes</td>
  </tr>
  <tr>
   <td>Map</td>
   <td> </td>
   <td>Rapporten</td>
  </tr>
 </tbody>
</table>

![](assets/wr-yyyy-mm-web-request-program-1.png)

## Mijn tokens inbegrepen {#my-tokens-included}

<table style="table-layout:auto">
 <tbody>
  <tr>
   <th>Type token</th>
   <th>Tokennaam</th>
   <th>Waarde</th>
  </tr>
  <tr>
   <td>Tekst</td>
   <td><code>{{my.Request-Type}}</code></td>
   <td>Contact opnemen</td>
  </tr>
  <tr>
   <td>Tekst</td>
   <td><code>{{my.ALERT-FromAddress}}</code></td>
   <td>PlaceholderFrom.email@mydomain.com</td>
  </tr>
  <tr>
   <td>Tekst</td>
   <td><code>{{my.ALERT-FromName}}</code></td>
   <td><code><--My From Name Here--></code></td>
  </tr>
  <tr>
   <td>Tekst</td>
   <td><code>{{my.ALERT-ReplyToAddress}}</code></td>
   <td>reply-to.email@mydomain.com</td>
  </tr>
  <tr>
   <td>Tekst</td>
   <td><code>{{my.PageURL-ThankYou}}</code></td>
   <td>My.BedanktYouPageURL?zonder de http://</td>
  </tr>
 </tbody>
</table>

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

## Aanbevolen procedures {#best-practices}

* Na de invoer van het webinar programma, verplaats de vorm van lokaal activa aan globale activa die in de Studio van het Ontwerp worden gevestigd.
   * Door het aantal formulieren te verminderen en meer algemene middelen van de Design Studio te gebruiken, kunt u het ontwerp van uw programma en het beheer ervan meer schaalbaar maken. Het biedt ook flexibiliteit voor regelmatige compatibiliteitsupdates voor velden, de taal van de opt-in, enz.

* U kunt overwegen de sjablonen in uw geïmporteerde programma bij te werken om de sjablonen met branding te gebruiken of de nieuw geïmporteerde sjabloon bij te werken naar uw merk door deze toe te voegen in een fragment of door de juiste logo-/voettekstinformatie.

* U kunt overwegen de naamgevingsconventie van dit programmavoorbeeld bij te werken en deze uit te lijnen met uw naamgevingsconventie.

>[!NOTE]
>
>Herinner me om de Mijn Symbolische Waarden op het programmamalplaatje bij te werken en telkens als u het programma gebruikt, zoals nodig.

>[!IMPORTANT]
>
>Mijn tokens die naar een URL verwijzen, kunnen niet de URL http:// of https:// bevatten anders werkt de koppeling niet correct binnen het element.
