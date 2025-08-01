---
unique-page-id: 2951877
description: Het begrip van het gebied van de Analyse van de Kans van het Programma - de Documenten van Marketo - de Documentatie van het Product
title: Het gebied van de Analyse van de Kans van het Programma
exl-id: 6105df93-b3de-4929-85e3-fd328372bd24
feature: Reporting, Revenue Cycle Analytics
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '907'
ht-degree: 0%

---

# Het gebied van de Analyse van de Kans van het Programma {#understanding-the-program-opportunity-analysis-area}

## Overzicht {#overview}

Op het gebied van de Analyse van de Kans van het Programma kunt u de doeltreffendheid van individuele Programma&#39;s analyseren of samengevatte resultaten zien door het Kanaal van het Programma.

**Van het bedrijfs voorbeeld vragen u het gebruiken van dit analysegebied kunt antwoorden omvatten**:

Hoeveel kansen zijn er verbonden aan een bepaald programma en hoeveel daarvan hebben we gewonnen?

![](assets/one-1.png)

Hoeveel inkomsten heeft een bepaald programma of kanaal helpen genereren?

![](assets/two-1.png)

Wat is mijn opbrengst aan Investeringen voor een bepaald Programma of Kanaal?

![](assets/three-1.png)

Welke Kansen beïnvloedden een bepaald Programma?

![](assets/four-1.png)

## Analyse van kenmerken van programmamogelijkheid (blauwe stippen) {#program-opportunity-analysis-attribution-measures-blue-dots}

De maatregelen die u in analyse kunt gebruiken zijn over het algemeen aantallen en worden vertegenwoordigd door blauwe punten. Dimensies zijn kenmerken die verschillende weergaven van de metingen geven en worden weergegeven door gele stippen.

Alle maatregelen (blauwe stippen) hebben betrekking op de toerekening - het &quot;krediet&quot; voor de verwerving van lood of voor het verkoopsucces dat met een lood gepaard gaat.

![](assets/six.five.png) ![](assets/seven-1.png)

Er zijn drie soorten maatregelen:

* Acquisitiegerelateerde maatregelen, waarvoor first-touch attributie (FT) wordt verkregen.
* Succesgerelateerde maatregelen die multitouch-attributie (MT) ontvangen.
* Diverse maatregelen in verband met het programma, waaronder het gemiddelde aantal marketingcontacten voordat Opportunity wordt gecreëerd of gesloten.

## Acquisitie- en succesgerelateerde maatregelen {#acquisition-and-success-related-measures}

Acquisitiegerelateerde maatregelen verlenen krediet aan het programma waarmee de contactgegevens van een lead voor het eerst worden verkregen. Een leidende rol hoeft niet te worden vervuld in een programma voor de toekenning van overnamekrediet.

De waarde van het aanschaffen van een bepaalde lead verandert in de loop van de tijd. Het is nul totdat de lead een aankoop heeft gedaan. Het kan dan stijgen met extra aankopen.

Succesgerelateerde maatregelen geven krediet aan alle programma’s die bijdragen tot de vooruitgang van een leidende rol op weg naar een aankoop.

Net als bij de overname verandert de waarde van de bijdrage aan de verkoop van een lead in de loop van de tijd en is deze nul totdat de lead een aankoop doet.

<table>
 <tbody>
  <tr>
   <th>Attributiemaatregel - Opportunity-Related (FT of MT)*</th>
   <th>Beschrijving</th>
  </tr>
  <tr>
   <td>Kosten van opportunity</td>
   <td>Het deel van de kosten van het programma dat de kansen beïnvloedde. De kosten kunnen worden opgesplitst als het om meerdere leads gaat.</td>
  </tr>
  <tr>
   <td>Gemaakte kansen</td>
   <td>Het deel van de kredieten dat het programma heeft ontvangen voor het beïnvloeden van de schepping van de kans. Het kan een fractie zijn als er meerdere leads bij betrokken waren.</td>
  </tr>
  <tr>
   <td>Opportunity Won</td>
   <td>Het deel van de kredieten dat het programma heeft ontvangen om de eigen kans te beïnvloeden. Het kan een fractie zijn als er meerdere leads bij betrokken waren.</td>
  </tr>
  <tr>
   <td>Pipet gemaakt</td>
   <td>Het deel van de kredieten (in monetaire waarde) dat het programma ontving om de schepping van de kans te beïnvloeden. Het kan een fractie zijn als er meerdere leads bij betrokken waren.</td>
  </tr>
  <tr>
   <td>Pipet gemaakt - nog steeds geopend</td>
   <td>Het deel van de kredieten (in monetaire waarde) dat het programma heeft ontvangen om de creatie van de momenteel open mogelijkheid te beïnvloeden. Het kan een fractie zijn als er meerdere leads bij betrokken waren.</td>
  </tr>
  <tr>
   <td>Verwachte inkomsten</td>
   <td>Het deel van de kredieten (in monetaire waarde) dat het programma ontving om de schepping van de kans te beïnvloeden. Verwachte opbrengsten zijn de opportuniteitswaarschijnlijkheid vermenigvuldigd met de opportuniteitswaarde. Het kan een fractie zijn als er meerdere leads bij betrokken waren.</td>
  </tr>
  <tr>
   <td>Opbrengsten van beleggingen</td>
   <td>Dit is de verhouding tussen het deel van het krediet (in monetaire waarde) dat het programma heeft ontvangen om de eigen kansen en de kosten van het programma te beïnvloeden.</td>
  </tr>
  <tr>
   <td>Won-inkomsten</td>
   <td>Het deel van de kredieten (in monetaire waarde) dat het programma heeft ontvangen om invloed uit te oefenen op de eigen kansen. Het kan een fractie zijn als er meerdere leads bij betrokken waren.</td>
  </tr>
 </tbody>
</table>

_&#42;(FT) = First-Touch Attribution, used for measurement of lead acquisition; (MT) = Multi-Touch Attribution, used for measurement of lead success_

Hieronder volgt een scenario dat beschrijft hoe de Eenheden van de Kans worden berekend wanneer er twee Programma&#39;s zijn die lood produceerden, maar die tot één Kans van de zelfde rekening leiden.

**Programma 1**

* Genereert één lead: lead 1
* Lood 1 komt uit account 1

**Programma 2**

* Genereert nog een lead: lead 2
* Lood 2 is ook afkomstig van account 1

**Rekening 1**

* Genereert één kans: Opportunity 1

Marketo geeft op de juiste wijze krediet zonder dubbeltellingsmogelijkheden voor alle programma&#39;s. In dit geval ontvangt elk programma 0,5 eenheden van de Opportunity. Dat wil zeggen dat elk programma de helft van het krediet ontvangt voor de gegenereerde opportuniteit. Ook, wordt de helft van de opbrengst verbonden aan de Kans toegewezen aan elk Programma.

## Diverse programmagerelateerde maatregelen {#miscellaneous-program-related-measures}

De overige beschikbare maatregelen weerspiegelen de algemene prestaties van het programma.

<table>
 <tbody>
  <tr>
   <th>Attributiemaatregel - Programmagerelateerd</th>
   <th>Beschrijving</th>
  </tr>
  <tr>
   <td>Aantal kansen verbonden aan Programma</td>
   <td><p>The number of total Opportunity that had any sort of attribution credit to a program. De kansen kunnen door één of meerdere lood en door één of meerdere Programma's worden beïnvloed.</p></td>
  </tr>
  <tr>
   <td>Gemiddeld aantal succesmeldingen per gesloten opportunity</td>
   <td>Het gemiddelde aantal succes van het Programma alvorens de Kans werd gesloten. <br></td>
  </tr>
  <tr>
   <td>Gemiddeld aantal successen per gemaakte kans</td>
   <td>Het gemiddelde aantal programma's is gelukt voordat de Opportunity is gemaakt.</td>
  </tr>
  <tr>
   <td>Nieuwe namen</td>
   <td>Het totale aantal nieuwe namen, dat wil zeggen nieuwe leads, dat door het programma wordt verworven.</td>
  </tr>
  <tr>
   <td>Programmakosten</td>
   <td>Totale kosten van het programma.</td>
  </tr>
  <tr>
   <td>Geslaagd (totaal)</td>
   <td>Het totale aantal programmaleden dat succes heeft geboekt.</td>
  </tr>
 </tbody>
</table>

## Analyse van programmamogelijkheden (gele stippen) {#program-opportunity-analysis-dimensions-yellow-dots}

Terwijl metingen (blauwe stippen) worden berekend en enige overweging en uitleg nodig is, zijn de afmetingen (gele stippen) beschrijvend. Hier zijn de beschikbare afmetingen.

<table>
 <tbody>
  <tr>
   <th>Categorie</th>
   <th>Weergavelabel</th>
  </tr>
  <tr>
   <td>Opportuniteitskenmerken</td>
   <td>De Naam van de Eigenaar van de Kans van de Kans van de kans gesloten <br> {<br> Naam van de Kans van het Stadium van de Kans <br> Type<br></td>
  </tr>
  <tr>
   <td>Tijdskader voor opportunity</td>
   <td>De kansen van de Gesloten Jaar/Kwart/Maand <br> Gemaakte Kanaal Jaar/Kwart/Maand</td>
  </tr>
  <tr>
   <td>Programmakenmerken</td>
   <td>De Naam van het Programma van het Kanaal van het programma <br></td>
  </tr>
  <tr>
   <td>Tijdslimiet voor programmakosten</td>
   <td>Kostenjaar/kwartaal/maand</td>
  </tr>
 </tbody>
</table>

*&#42;Alle Kansen die om het even welk type van attributiecrediet aan een Programma gaven. De kansen kunnen door één of meerdere lood en door één of meerdere Programma&#39;s worden beïnvloed.*

>[!MORELIKETHIS]
>
>[ creeer een Rapport van de Ontdekkingsreiziger van de Opbrengst ](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-explorer/create-a-revenue-explorer-report.md)
