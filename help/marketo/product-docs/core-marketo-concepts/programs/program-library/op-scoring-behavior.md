---
description: OP-Scoring-Gedrag - Marketo Docs - Productdocumentatie
title: OP-Scoring-gedrag
hide: true
hidefromtoc: true
feature: Programs
source-git-commit: 0f71600b18315feb3ef32e95dfb108b09c4cb79f
workflow-type: tm+mt
source-wordcount: '357'
ht-degree: 4%

---

# OP-Scoring-gedrag {#op-scoring-behavior}

Dit voorbeeld is een geavanceerd (samengevoegd) Operationeel Programma voor Gedrag dat gebruikend een Programma van het Standaard van het Marketo Engage schrapt. U kunt de waarden voor scores weergeven en bewerken op het tabblad &quot;Mijn tokens&quot; van het programma. Vereist een aangepast score-veld met de naam &quot;Gedragscore&quot;.

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
   <td>Operationeel</td> 
   <td>01-Lid</td>
   <td>Operationeel</td>
   <td>Standaard</td>
  </tr>
 </tbody> 
</table>

## Vereiste velden {#prerequisite-fields}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>Type</th> 
   <th>Vriendelijke naam</th>
   <th>API-naam</th>
  </tr>
  <tr> 
   <td>Score</td> 
   <td>Gedragscore</td>
   <td>BehaviorScore</td>
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
   <td>Slimme campagne</td> 
   <td> </td>
   <td>E-mail - Klik op Koppeling in e-mail</td>
  </tr>
  <tr> 
   <td>Slimme campagne</td> 
   <td> </td>
   <td>Formulier - Contactformulier invullen</td>
  </tr>
  <tr> 
   <td>Slimme campagne</td> 
   <td> </td>
   <td>Formulier - Formulier voor inhoud wordt ingevuld</td>
  </tr>
  <tr> 
   <td>Slimme campagne</td> 
   <td> </td>
   <td>Formulier - Standaardformulier wordt ingevuld</td>
  </tr>
  <tr> 
   <td>Slimme campagne</td> 
   <td> </td>
   <td>Formulier - Vult gebeurtenisformulier uit</td>
  </tr>
  <tr> 
   <td>Slimme campagne</td> 
   <td> </td>
   <td>Web - downloadt om het even welke PDF</td>
  </tr>
  <tr> 
   <td>Slimme campagne</td> 
   <td> </td>
   <td>Web - het Scorebord PPC</td>
  </tr>
  <tr> 
   <td>Slimme campagne</td> 
   <td> </td>
   <td>Web - bezoeken Zeer belangrijke Web-pagina's</td>
  </tr>
  <tr> 
   <td>Slimme campagne</td> 
   <td> </td>
   <td>Web - bezoeken Meerdere Web-pagina's in 1 dag</td>
  </tr>
  <tr> 
   <td>Slimme campagne</td> 
   <td> </td>
   <td>Live-gebeurtenis - bijgewoond</td>
  </tr>
  <tr> 
   <td>Slimme campagne</td> 
   <td> </td>
   <td>Handelsvoorstelling - beïnvloed</td>
  </tr>
  <tr> 
   <td>Slimme campagne</td> 
   <td> </td>
   <td>Handelsversie - Bezochte cabine</td>
  </tr>
  <tr> 
   <td>Slimme campagne</td> 
   <td> </td>
   <td>Webinar - Bijgewoond</td>
  </tr>
  <tr> 
   <td>Slimme campagne</td> 
   <td> </td>
   <td>Score verlagen - Geen activiteit</td>
  </tr>
  <tr> 
   <td>Slimme campagne</td> 
   <td> </td>
   <td>Score verlagen - Bezoek ongewenste webpagina's</td>
  </tr>
  <tr> 
   <td>Map</td> 
   <td> </td>
   <td>Interacties</td>
  </tr>
  <tr> 
   <td>Map</td> 
   <td> </td>
   <td>Wijzigingen in status programma</td>
  </tr>
  <tr> 
   <td>Map</td> 
   <td> </td>
   <td>Score-verlies</td>
  </tr>
 </tbody> 
</table>

SCHERM VAN HET PROGRAMMA

## Mijn tokens inbegrepen {#my-tokens-included}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>Type token</th> 
   <th>Tokennaam</th>
   <th>Waarde</th>
  </tr>
  <tr> 
   <td>Score</td> 
   <td><code>{{my.Decrease Score - No Activity}}</code></td>
   <td>-10</td>
  </tr>
  <tr> 
   <td>Score</td> 
   <td><code>{{my.Decrease Score - Visits Undesirable Web Pages}}</code></td>
   <td>-5</td>
  </tr>
  <tr> 
   <td>Score</td> 
   <td><code>{{my.Email - Clicks Link}}</code></td>
   <td>+2</td>
  </tr>
   <tr> 
   <td>Score</td> 
   <td><code>{{my.Form - Fills Out Contact Form}}</code></td>
   <td>+30</td>
  </tr>
  <tr> 
   <td>Score</td> 
   <td><code>{{my.Form - Fills Out Content Form}}</code></td>
   <td>+15</td>
  </tr>
  <tr> 
   <td>Score</td> 
   <td><code>{{my.Form - Fills Out Default Form}}</code></td>
   <td>+10</td>
  </tr>
   <tr> 
   <td>Score</td> 
   <td><code>{{my.Form - Fills-out Event Form}}</code></td>
   <td>+15</td>
  </tr>
  <tr> 
   <td>Score</td> 
   <td><code>{{my.Live Event - Attended}}</code></td>
   <td>+30</td>
  </tr>
   <tr> 
   <td>Score</td> 
   <td><code>{{my.Tradeshow - Influenced}}</code></td>
   <td>+20</td>
  </tr>
  <tr> 
   <td>Score</td> 
   <td><code>{{my.Tradeshow - Visited Booth}}</code></td>
   <td>+5</td>
  </tr>
  <tr> 
   <td>Score</td> 
   <td><code>{{my.Web - Downloaded Any PDF}}</code></td>
   <td>+5</td>
  </tr>
  <tr> 
   <td>Score</td> 
   <td><code>{{my.Web - PPC Scoring}}</code></td>
   <td>+15</td>
  </tr>
   <tr> 
   <td>Score</td> 
   <td><code>{{my.Web - Visits Key Web Pages}}</code></td>
   <td>+5</td>
  </tr>
  <tr> 
   <td>Score</td> 
   <td><code>{{my.Web - Visits Multiple Web Pages in 1 Day}}</code></td>
   <td>+5</td>
  </tr>
  <tr> 
   <td>Score</td> 
   <td><code>{{my.Webinar - Attended}}</code></td>
   <td>+20</td>
  </tr>
 </tbody> 
</table>

## Conflictregels {#conflict-rules}

* **Programmatags**
   * Tags maken in dit abonnement - _Aanbevolen_
   * Negeren

* **Landingspagina-sjabloon met dezelfde naam**
   * Oorspronkelijke sjabloon kopiëren - _Aanbevolen_
   * Doelsjabloon gebruiken

* **Afbeeldingen met dezelfde naam**
   * Beide bestanden behouden - _Aanbevolen_
   * Item in dit abonnement vervangen

* **E-mailsjablonen met dezelfde naam**
   * Beide sjablonen behouden - _Aanbevolen_
   * Bestaande sjabloon vervangen

SCHERM VAN CONFLICTREGELS

## Aanbevolen procedures {#best-practices}

* Elke gebouwde campagne moet een voorbeeld zijn van de beste praktijk bouwt en niet specifiek voor uw gebruiksgevallen. Herinner me om de Slimme Campagnes bij te werken om uw specifieke pijnpunten en gegevensuitdagingen te richten.

* U kunt overwegen de naamgevingsconventie van dit programmavoorbeeld bij te werken en deze uit te lijnen met uw naamgevingsconventie.
