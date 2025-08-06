---
description: CT-YYYY-MM-Content Non-Marketo Landing Page - Marketo Docs - Productdocumentatie
title: CT-YYYY-MM-Content Non-Marketo Landing Page
feature: Programs
exl-id: b7cf8e52-4f3f-44d7-ab4c-ad10fa0badc9
source-git-commit: 21bcdc10fe1f3517612efe0f8e2adaf2f4411a70
workflow-type: tm+mt
source-wordcount: '395'
ht-degree: 0%

---

# CT-YYYY-MM-Content Non-Marketo Landing Page {#ct-yyyy-mm-content-non-marketo-landing-page}

Dit is een voorbeeld van een inhoudsprogramma met een Marketo Engage-formulier voor het downloaden van inhoud naar een niet-Marketo Engage Landing Page met behulp van een Marketo Engage-standaardprogramma. Dit programma is bedoeld om te werken met een Marketo Engage-formulier dat is ingesloten op uw website. De koppeling naar het aanbod/de inhoud kan via een e-mail worden verzonden.

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
   <td>Webinhoud</td>
   <td>01-Lid
<br/> 02-Beheerd-Succes</td>
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
   <td>E-mail</td>
   <td><a href="/help/marketo/product-docs/core-marketo-concepts/programs/program-library/quick-start-email-template.md" target="_blank">E-mailsjabloon snel starten</a></td>
   <td>01-E-mail-Dank u</td>
  </tr>
  <tr>
   <td>Formulier</td>
   <td> </td>
   <td>FM-Inhoudsregistratieformulier (algemeen middel in Design Studio)</td>
  </tr>
  <tr>
   <td>Lokaal rapport</td>
   <td> </td>
   <td>E-mailprestaties</td>
  </tr>
  <tr>
   <td>Slimme campagne</td>
   <td> </td>
   <td>Ophaalprogramma voor 00-vastlegging</td>
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

![](assets/ct-yyyy-mm-content-non-marketo-landing-page-1.png)

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

* Nadat het inhoudsprogramma is geïmporteerd, verplaatst u het formulier van een lokaal element naar een algemeen element in de Design Studio.
   * Door het aantal formulieren te verminderen en meer algemene middelen van de Design Studio te gebruiken, kunt u het ontwerp van uw programma en het beheer ervan meer schaalbaar maken. Het biedt ook flexibiliteit voor regelmatige compatibiliteitsupdates voor velden, de taal van de opt-in, enz.

* U kunt overwegen de sjablonen in uw geïmporteerde programma bij te werken om de sjablonen met branding te gebruiken of de nieuw geïmporteerde sjabloon bij te werken naar uw merk door deze toe te voegen in een fragment of door de juiste logo-/voettekstinformatie.

* U kunt overwegen de naamgevingsconventie van dit programmavoorbeeld bij te werken en deze uit te lijnen met uw naamgevingsconventie.

>[!NOTE]
>
>Herinner me om de Mijn Symbolische Waarden op het programmamalplaatje bij te werken en telkens als u het programma gebruikt, zoals nodig.

>[!TIP]
>
>Vergeet niet de ‘02-Betrokken&#39; campagne te activeren om succes te volgen! Doe dit _alvorens_ uw vorm levend is en e-mails worden verzonden.
