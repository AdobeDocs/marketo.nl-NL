---
description: CT-YYYY-MM-Content on Marketo Landing Page - Marketo Docs - Productdocumentatie
title: CT-YYYY-MM-Content op Marketo Landing Page
feature: Programs
exl-id: 11745023-a0c1-45ef-9547-6426f24e3fee
source-git-commit: 38274b4859ae38c018ee73d4f1715fdf6a78e815
workflow-type: tm+mt
source-wordcount: '472'
ht-degree: 0%

---

# CT-YYYY-MM-Content op Marketo Landing Page {#ct-yyyy-mm-content-on-marketo-landing-page}

Dit voorbeeld is ontworpen als een inhoudsprogramma dat gebruikmaakt van een Marketo Engage Landing Page met een Marketo Engage formulier dat gebruikmaakt van een standaardprogramma voor Marketo&#39;s Engage. Het formulier moet toegang krijgen tot de inhoud/het aanbod. De koppeling naar het aanbod kan worden weergegeven op de pagina Hartelijk dank, in een e-mail met dank of in beide.

Voor verdere strategische hulp of hulp die een programma aanpast, gelieve het Team van de Rekening van de Adobe te contacteren of te bezoeken [Adobe Professional Services](https://business.adobe.com/customers/consulting-services/main.html){target="_blank"} pagina.

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
   <td>Webinhoud</td> 
   <td>01-Lid 
<br/>02-Betrokken-Succes</td>
   <td>Inclusief</td>
   <td>Standaard</td>
  </tr>
 </tbody> 
</table>

## Het programma bevat de volgende elementen {#program-contains-the-following-assets}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>Type</th> 
   <th>Sjabloonnaam</th>
   <th>Elementnaam</th>
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
   <td>Formulier</td> 
   <td> </td>
   <td>FM - Inhoudsregistratieformulier</td>
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
   <td>Middelen - alle creatieve middelen onderbrengen 
<br/>(submappen voor e-mails, bestemmingspagina's en Forms)  </td>
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

![](assets/ct-yyyy-mm-content-on-marketo-landing-page-1.png)

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
<br/>Bewerk deze inhoudsbeschrijving op programmaniveau onder het tabblad Mijn tokens. 
<br/>U leert: 
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

## Conflictregels {#conflict-rules}

* **Programmatags**
   * Tags maken in dit abonnement - _Aanbevolen_
   * Negeren

* **Landingspagina-sjabloon met dezelfde naam**
   * Originele sjabloon kopiëren
   * Doelsjabloon gebruiken - _Aanbevolen_

* **Afbeeldingen met dezelfde naam**
   * Beide bestanden behouden
   * Item in dit abonnement vervangen - _Aanbevolen_

* **E-mailsjablonen met dezelfde naam**
   * Beide sjablonen behouden
   * Bestaande sjabloon vervangen - _Aanbevolen_

## Aanbevolen procedures {#best-practices}

* Nadat het inhoudsprogramma is geïmporteerd, verplaatst u het formulier van een lokaal element naar een algemeen element in de Design Studio.
   * Door het aantal formulieren te verminderen en meer algemene middelen van de Design Studio te gebruiken, kunt u het ontwerp van uw programma en het beheer ervan meer schaalbaar maken. Het biedt ook flexibiliteit bij regelmatige compatibiliteitsupdates voor velden, de taal van de opt-in, enz.

* U kunt overwegen de sjablonen in uw geïmporteerde programma bij te werken om de sjablonen met branding te gebruiken of de nieuw geïmporteerde sjabloon bij te werken naar uw merk door deze toe te voegen in een fragment of door de juiste logo-/voettekstinformatie.

* U kunt overwegen de naamgevingsconventie van dit programmavoorbeeld bij te werken en deze uit te lijnen met uw naamgevingsconventie.

>[!NOTE]
>
>Herinner me om de Mijn Symbolische Waarden op het programmamalplaatje bij te werken en telkens als u het programma gebruikt, zoals nodig.

>[!TIP]
>
>Vergeet niet de ‘02-Betrokken&#39; campagne te activeren om succes te volgen! Doe dit _voor_ uw formulier is live en e-mails worden verzonden.

>[!IMPORTANT]
>
>Mijn tokens die naar een URL verwijzen, kunnen niet de URL http:// of https:// bevatten anders werkt de koppeling niet correct binnen het element.
