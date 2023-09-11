---
description: OP-Scoring-Demographic - Marketo Docs - Productdocumentatie
title: OP-Scoring-Demografisch
feature: Programs
source-git-commit: 720215ea958206931413f2d273a4a058bc051579
workflow-type: tm+mt
source-wordcount: '313'
ht-degree: 7%

---

# OP-Scoring-Demografisch {#op-scoring-demographic}

Dit is een voorbeeld van een geavanceerd (samengevoegd) operationeel programma, dat een Programma van de Standaard van de Marketo Engage voor demografische scoring gebruikt. U kunt de waarden voor scores weergeven en bewerken op het tabblad &quot;Mijn tokens&quot; van het programma. Vereist een aangepast score-veld met de naam &quot;Demografische score&quot;.

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
   <td>01 - Lid</td>
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
   <td>Demografische score</td>
   <td>DemographicScore</td>
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
   <td>Algemeen e-maildomein</td>
  </tr>
  <tr> 
   <td>Slimme campagne</td> 
   <td> </td>
   <td>Ongeldige voornaam</td>
  </tr>
  <tr> 
   <td>Slimme campagne</td> 
   <td> </td>
   <td>Ongeldige voornaam bijgewerkt</td>
  </tr>
  <tr> 
   <td>Slimme campagne</td> 
   <td> </td>
   <td>Ongeldige achternaam</td>
  </tr>
  <tr> 
   <td>Slimme campagne</td> 
   <td> </td>
   <td>Ongeldige achternaam bijgewerkt</td>
  </tr>
  <tr> 
   <td>Slimme campagne</td> 
   <td> </td>
   <td>Jaaromzet</td>
  </tr>
  <tr> 
   <td>Slimme campagne</td> 
   <td> </td>
   <td>Marktsegment</td>
  </tr>
  <tr> 
   <td>Slimme campagne</td> 
   <td> </td>
   <td>Beroep</td>
  </tr>
  <tr> 
   <td>Slimme campagne</td> 
   <td> </td>
   <td>Aantal werknemers</td>
  </tr>
  <tr> 
   <td>Slimme campagne</td> 
   <td> </td>
   <td>Bron</td>
  </tr>
  <tr> 
   <td>Map</td> 
   <td> </td>
   <td>Algemeen e-maildomein</td>
  </tr>
  <tr> 
   <td>Map</td> 
   <td> </td>
   <td>Ongeldige voornaam</td>
  </tr>
  <tr> 
   <td>Map</td> 
   <td> </td>
   <td>Ongeldige achternaam</td>
  </tr>
 </tbody> 
</table>

![](assets/op-scoring-demographic-1.png)

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
   <td><code>{{my.Annual Revenue - High}}</code></td>
   <td>+15</td>
  </tr>
  <tr> 
   <td>Score</td> 
   <td><code>{{my.Annual Revenue - Low}}</code></td>
   <td>+5</td>
  </tr>
  <tr> 
   <td>Score</td> 
   <td><code>{{my.Annual Revenue - Mid}}</code></td>
   <td>+10</td>
  </tr>
   <tr> 
   <td>Score</td> 
   <td><code>{{my.Generic Email Domain}}</code></td>
   <td>-2</td>
  </tr>
  <tr> 
   <td>Score</td> 
   <td><code>{{my.Industry - High}}</code></td>
   <td>+10</td>
  </tr>
  <tr> 
   <td>Score</td> 
   <td><code>{{my.Industry - Low}}</code></td>
   <td>+6</td>
  </tr>
   <tr> 
   <td>Score</td> 
   <td><code>{{my.Industry - Mid}}</code></td>
   <td>+8</td>
  </tr>
  <tr> 
   <td>Score</td> 
   <td><code>{{my.Invalid First Name}}</code></td>
   <td>-5</td>
  </tr>
   <tr> 
   <td>Score</td> 
   <td><code>{{my.Invalid First Name Updated}}</code></td>
   <td>+5</td>
  </tr>
  <tr> 
   <td>Score</td> 
   <td><code>{{my.Invalid Last Name}}</code></td>
   <td>-5</td>
  </tr>
  <tr> 
   <td>Score</td> 
   <td><code>{{my.Invalid Last Name Updated}}</code></td>
   <td>+5</td>
  </tr>
  <tr> 
   <td>Score</td> 
   <td><code>{{my.Job Title - High}}</code></td>
   <td>+15</td>
  </tr>
   <tr> 
   <td>Score</td> 
   <td><code>{{my.Job Title - Low}}</code></td>
   <td>+5</td>
  </tr>
  <tr> 
   <td>Score</td> 
   <td><code>{{my.Job Title - Mid}}</code></td>
   <td>+10</td>
  </tr>
  <tr> 
   <td>Score</td> 
   <td><code>{{my.Lead Source - High}}</code></td>
   <td>+20</td>
  </tr>
  <tr> 
   <td>Score</td> 
   <td><code>{{my.Lead Source - Low}}</code></td>
   <td>+8</td>
  </tr>
  <tr> 
   <td>Score</td> 
   <td><code>{{my.Lead Source - Mid}}</code></td>
   <td>+10</td>
  </tr>
  <tr> 
   <td>Score</td> 
   <td><code>{{my.Number of Employees}}</code></td>
   <td>+5</td>
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

## Aanbevolen procedures {#best-practices}

* Elke gebouwde campagne moet een voorbeeld zijn van de beste praktijk bouwt en niet specifiek voor uw gebruiksgevallen. Herinner me om de Slimme Campagnes bij te werken om uw specifieke pijnpunten en gegevensuitdagingen te richten.

* U kunt overwegen de naamgevingsconventie van dit programmavoorbeeld bij te werken en deze uit te lijnen met uw naamgevingsconventie.
