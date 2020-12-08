---
unique-page-id: 2951877
description: Begrijpen van het Gebied van de Analyse van de Kans van het Programma - Marketo Docs - de Documentatie van het Product
title: Het gebied van de Analyse van de Kans van het Programma
translation-type: tm+mt
source-git-commit: 1c4c4c62215550a09125f76fb76017348aba2bdf
workflow-type: tm+mt
source-wordcount: '898'
ht-degree: 0%

---


# Het gebied van de Analyse van de Kans van het Programma {#understanding-the-program-opportunity-analysis-area}

## Overzicht {#overview}

Op het gebied van de Analyse van de Kans van het Programma kunt u de doeltreffendheid van individuele Programma&#39;s analyseren of samengevatte resultaten zien door het Kanaal van het Programma.

**Voorbeelden van zakelijke vragen die u kunt beantwoorden met behulp van dit analysegebied zijn:**

Hoeveel kansen zijn er verbonden aan een bepaald programma en hoeveel daarvan hebben we gewonnen?

![](assets/one-1.png)

Hoeveel inkomsten heeft een bepaald programma of kanaal helpen genereren?

![](assets/two-1.png)

Wat is mijn opbrengst aan Investeringen voor een bepaald Programma of Kanaal?

![](assets/three-1.png)

Welke Kansen beïnvloedden een bepaald Programma?

![](assets/four-1.png)

## Analyse van kenmerken van programmamogelijkheid (blauwe stippen) {#program-opportunity-analysis-attribution-measures-blue-dots}

De maatregelen die u in analyse kunt gebruiken zijn over het algemeen aantallen en worden vertegenwoordigd door blauwe punten. Dimension zijn kenmerken die verschillende weergaven van de meetwaarden geven en worden weergegeven door gele stippen.

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
   <td>Kosten van opportuniteit</td> 
   <td><p>Het deel van de kosten van het programma dat de kansen beïnvloedde. De kosten kunnen worden opgesplitst als het om meerdere leads gaat.</p></td> 
  </tr> 
  <tr> 
   <td>Gemaakte kansen</td> 
   <td><p>Het deel van de kredieten dat het programma heeft ontvangen voor het beïnvloeden van de schepping van de kans. Het kan een fractie zijn als er meerdere leads bij betrokken waren.</p></td> 
  </tr> 
  <tr> 
   <td>Opportunity Won</td> 
   <td>Het deel van de kredieten dat het programma heeft ontvangen om de eigen kans te beïnvloeden. Het kan een fractie zijn als er meerdere leads bij betrokken waren.</td> 
  </tr> 
  <tr> 
   <td>Pipet gemaakt</td> 
   <td><p>Het deel van de kredieten (in monetaire waarde) dat het programma ontving om de schepping van de kans te beïnvloeden. Het kan een fractie zijn als er meerdere leads bij betrokken waren.</p></td> 
  </tr> 
  <tr> 
   <td>Pipet gemaakt - nog geopend</td> 
   <td>Het deel van de kredieten (in monetaire waarde) dat het programma heeft ontvangen om de creatie van de momenteel open mogelijkheid te beïnvloeden. Het kan een fractie zijn als er meerdere leads bij betrokken waren.</td> 
  </tr> 
  <tr> 
   <td><p>Verwachte inkomsten</p></td> 
   <td>Het deel van de kredieten (in monetaire waarde) dat het programma ontving om de schepping van de kans te beïnvloeden. Verwachte opbrengsten zijn de opportuniteitswaarschijnlijkheid vermenigvuldigd met de opportuniteitswaarde. Het kan een fractie zijn als er meerdere leads bij betrokken waren.</td> 
  </tr> 
  <tr> 
   <td><p>Opbrengsten van beleggingen</p></td> 
   <td><p>Dit is de verhouding tussen het deel van het krediet (in monetaire waarde) dat het programma heeft ontvangen om de eigen kansen en de kosten van het programma te beïnvloeden.</p></td> 
  </tr> 
  <tr> 
   <td>Won-inkomsten</td> 
   <td><p>Het deel van de kredieten (in monetaire waarde) dat het programma heeft ontvangen om de eigen kans te beïnvloeden. Het kan een fractie zijn als er meerdere leads bij betrokken waren.</p></td> 
  </tr> 
 </tbody> 
</table>

** (FT) = First-Touch Attribution, gebruikt voor metingen van de verwerving van lood; (MT) = Multi-Touch Attribution, gebruikt voor het meten van het succes van lead*

Hieronder volgt een scenario dat beschrijft hoe de Eenheden van de Kans worden berekend wanneer er twee Programma&#39;s zijn die lood produceerden, maar die tot één Kans van de zelfde rekening leiden.

**Programma 1**

* Genereert één lead: Lood 1
* Lood 1 komt uit account 1

**Programma 2**

* Genereert nog een lead: Lood 2
* Lood 2 is ook afkomstig van account 1

**Account 1**

* Genereert één kans: Opportunity 1

Marketo geeft op de juiste wijze krediet zonder dubbeltellingsmogelijkheden voor alle programma&#39;s. In dit geval ontvangt elk programma 0,5 eenheden van de Opportunity. Dat wil zeggen dat elk programma de helft van het krediet ontvangt voor de gegenereerde opportuniteit. Ook, wordt de helft van opbrengst verbonden aan de Kans toegewezen aan elk Programma.

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
   <td>Gemiddeld aantal successen per gemaakte opportuniteit</td> 
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

## Dimension voor de analyse van programmamogelijkheden (gele stippen) {#program-opportunity-analysis-dimensions-yellow-dots}

Terwijl metingen (blauwe stippen) worden berekend en enige overweging en uitleg nodig is, zijn de afmetingen (gele stippen) beschrijvend. Hier zijn de beschikbare afmetingen.

<table> 
 <tbody> 
  <tr> 
   <th>Categorie</th> 
   <th><p>Weergavelabel</p></th> 
  </tr> 
  <tr> 
   <td>Opportuniteitskenmerken</td> 
   <td><p>Opportunity<br>ClosedOpportunity Name*<br>Opportunity-eigenaar<br>NameOpportunity<br>StageOpportunity-type</p></td> 
  </tr> 
  <tr> 
   <td>Tijdskader voor opportunity</td> 
   <td><p>Opportunity afgesloten jaar/kwartaal/<br>maandMogelijkheid gemaakt jaar/kwartaal/maand</p></td> 
  </tr> 
  <tr> 
   <td>Programmakenmerken</td> 
   <td><p>Naam<br>van programmaChannelProgram</p></td> 
  </tr> 
  <tr> 
   <td>Tijdslimiet voor programmakosten</td> 
   <td>Kostenjaar/kwartaal/maand</td> 
  </tr> 
 </tbody> 
</table>

**All van de Kansen die om het even welk type van attributie krediet aan een Programma gaven. De kansen kunnen door één of meerdere lood en door één of meerdere Programma&#39;s worden beïnvloed.*

>[!NOTE]
>
>**Verwante artikelen**
>
>[Een rapport van de inkomstenverkenner maken](../../../../product-docs/reporting/revenue-cycle-analytics/revenue-explorer/create-a-revenue-explorer-report.md)
