---
description: Inhoud op Marketo LP - Marketo Docs - Productdocumentatie
title: Inhoud op Marketo LP
hide: true
hidefromtoc: true
feature: Programs
source-git-commit: 661a41eb0c5c43541a63a36c31837b35f516d827
workflow-type: tm+mt
source-wordcount: '533'
ht-degree: 0%

---

# Inhoud op Marketo LP {#content-on-marketo-lp}

Programmanaam: CT-YYYY-MM-Content op Marketo LP

Deze voorbeeldverwijzing is ontworpen als een inhoudsprogramma dat gebruikmaakt van een Marketo Landing Page met een Marketo-formulier dat gebruikmaakt van een Marketo Default Program. Het formulier moet toegang krijgen tot de inhoud/het aanbod. De koppeling naar het aanbod kan worden weergegeven op de pagina Hartelijk dank, in een e-mail met dank of in beide. Voor verdere strategische hulp of hulp die een programma aanpast, gelieve het Team van de Rekening van de Adobe te contacteren of te bezoeken [Adobe Professional Services](https://business.adobe.com/customers/consulting-services/main.html) pagina.

**Kanaaloverzicht**

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

**Het programma bevat de volgende elementen:**

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>Type</th> 
   <th>Sjabloonnaam</th>
   <th>Elementnaam</th>
  </tr> 
  <tr> 
   <td>E-mail</td> 
   <td>E-mailsjabloon snel starten</td>
   <td>01-E-mail-Dank u</td>
  </tr>
  <tr> 
   <td>Openingspagina</td> 
   <td>LP-sjabloon snel starten</td>
   <td>01 - LP - Registratie</td>
  </tr>
  <tr> 
   <td>Openingspagina</td> 
   <td>LP-sjabloon snel starten</td>
   <td>02 - LP - Dank u</td>
  </tr>
  <tr> 
   <td>Formulier</td> 
   <td> </td>
   <td>Inhoudsregistratieformulier</td>
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
   <td>01-formulier met vulling</td>
  </tr>
  <tr> 
   <td>Slimme campagne</td> 
   <td> </td>
   <td>02-Betrokken (succes van programma)</td>
  </tr>
  <tr> 
   <td>Map</td> 
   <td> </td>
   <td>Activa - Houdt alle creatieve activa in huis 
<br/>(submappen voor e-mail- en bestemmingspagina's)  </td>
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

SCREENSHOT - Beeld van programma

**Mijn tokens zijn onder andere:**

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
   <td><code>{{my. Email-ReplyToAddress}}</code></td>
   <td>reply-to.email@mydomain.com</td>
  </tr>
  <tr> 
   <td>Tekst</td> 
   <td><code>{{my.PageURL-ThankYou}}</code></td>
   <td>My.BedanktYouPageURL?zonder de http://</td>
  </tr>
 </tbody> 
</table>

>[!CAUTION]
>
>Zie Instructies voor het importeren van programma&#39;s voor de standaardregels voor conflicten.

**Aanbevolen standaard conflictregel voor importeren:**

* Programmatags
   * Tags maken in dit abonnement (standaard) - Aanbevolen
   * Negeren

* Landingspagina-sjabloon met dezelfde naam
   * Originele sjabloon kopiëren (standaard)
   * Doelsjabloon gebruiken - Aanbevolen

* Afbeeldingen met dezelfde naam
   * Beide bestanden behouden (standaard)
   * Item in dit abonnement vervangen - Aanbevolen

* E-mailsjablonen met dezelfde naam
   * Beide sjablonen behouden (standaard)
   * Bestaande sjabloon vervangen - Aanbevolen

SCREENSHOT - Foto van standaardcollisieregels

**Aanbevolen aanbevolen procedures:**

* In Marketo Consulting worden aanbevolen het inhoudsprogramma na het importeren te importeren en het formulier te verplaatsen van een lokaal middel naar een algemeen middel in de Design Studio of Marketo Engage.
   * Door het aantal formulieren te verminderen en meer algemene middelen van de Design Studio te gebruiken, kunt u het ontwerp van uw programma en het beheer ervan meer schaalbaar maken. Het biedt ook flexibiliteit bij regelmatige compatibiliteitsupdates voor velden, de taal van de opt-in, enz.

* U kunt overwegen de sjablonen in uw geïmporteerde programma bij te werken om sjablonen met branding te gebruiken of de nieuw geïmporteerde sjabloon bij te werken naar uw merk door deze toe te voegen in een fragment of door uw juiste logo- en voettekstgegevens.

* U kunt desgewenst de naamgevingsconventie van dit programmasjabloon bijwerken en uitlijnen op uw naamgevingsconventie.

* Vergeet niet de Mijn Symbolische Waarden op het programmamalplaatje bij te werken en telkens als u het programma gebruikt, zoals nodig.

* Voor verdere strategische hulp of hulp die een programma aanpast, gelieve uw Team van de Rekening van de Adobe te contacteren of te bezoeken [Adobe Professional Services](https://business.adobe.com/customers/consulting-services/main.html) pagina.

>[!TIP]
>
>Vergeet niet de ‘02-Betrokken&#39; campagne te activeren om succes te volgen! Doe dit VOORDAT uw formulier live is en e-mails worden verzonden.

>[!NOTE]
>
>Mijn tokens die naar een URL verwijzen, kunnen niet de URL http:// of https:// bevatten anders werkt de koppeling niet correct binnen het element.
