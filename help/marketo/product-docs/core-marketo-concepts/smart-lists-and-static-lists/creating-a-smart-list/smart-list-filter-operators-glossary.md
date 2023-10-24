---
unique-page-id: 557312
description: Verklarende woordenlijst van slimme-lijstfilteroperatoren - Marketo Docs - Productdocumentatie
title: Verklarende woordenlijst voor slimme-lijstfilteroperatoren
exl-id: 5a370482-f214-4909-bb49-801c1a36b153
feature: Smart Lists
source-git-commit: 198d7d7fd4c1c312aeb30fa922fd89863ac87f81
workflow-type: tm+mt
source-wordcount: '592'
ht-degree: 0%

---

# Verklarende woordenlijst voor slimme-lijstfilteroperatoren {#smart-list-filter-operators-glossary}

Een exploitant is een deel van de Slimme Lijst die u helpt specifiek worden. Hiermee kunt u het filter of de trigger in een eenvoudige taal beschrijven. De beschikbare operatoren verschillen per veldtype.

Hier volgt een verklarende woordenlijst die elke reeks exploitanten beschrijft.

## Datumvelden {#date-fields}

![](assets/image2014-9-10-17-3a15-3a47.png)

Wanneer u een operator kiest, verandert de rechterzijde dynamisch.

| Operator | Rechterkant | Beschrijving |
|---|---|---|
| is | Enkele datum | Exacte datumovereenkomst |
| is niet | Enkele datum | Elke datum behalve de opgegeven datum |
| Tussen | Twee datumvelden | Elke datum met en tussen twee opgegeven data |
| in het verleden | Invoer natuurlijke taal&#42; | Zie onderstaande figuur |
| in het verleden | Invoer natuurlijke taal&#42; | Zie onderstaande figuur |
| in de toekomst | Invoer natuurlijke taal&#42; | Zie onderstaande figuur |
| later | Invoer natuurlijke taal&#42; | Zie onderstaande figuur |
| in tijdkader | Voorinstellingen (afgelopen kwartaal, gisteren, enz.) | Gedefinieerd in picklist |
| na | Enkele datum | Alle records na de opgegeven datum |
| voor | Enkele datum | Alle records voor de opgegeven record |
| op of na | Enkele datum | Gelijk aan &quot;after&quot; maar inclusief |
| op of voor | Enkele datum | Gelijk aan &quot;before&quot; maar inclusief |
| is leeg | Geen | Alle records zonder datum |
| is niet leeg | Geen | Alle records met een willekeurige datum |

&#42; Invoer in de natuurlijke taal is cool. Hier volgen enkele voorbeelden van patronen die u kunt invoeren:

* 1 uur
* 82 dagen
* 3 weken
* 14 maanden
* 1 jaar

Typ gewoon het nummer en de eenheid en het werkt!

>[!NOTE]
>
>&quot;In het verleden&quot; _doet_ neem de dag op (tot de tijd, niet daarna) u creeert uw Slimme Lijst.

>[!CAUTION]
>
>Wanneer u een slimme lijst maakt met een datumveldfilter (bijvoorbeeld Geboortedatum, Aanmaakdatum van SFDC) en de beperkingen gebruikt **[!UICONTROL before]**, **[!UICONTROL on or before]**, of **[!UICONTROL in past before]** bevat de slimme lijst ook personen die geen waarde hebben in het datumveld.

Gebruik het volgende diagram om het verschil tussen de datumoperatoren te begrijpen.

![](assets/image2014-9-10-17-3a15-3a58.png)

>[!NOTE]
>
>**Voorbeeld**
>
>Datumvelden kunnen lastig worden wanneer u met gebeurtenissen uit het verleden en de toekomst werkt. Hier zijn een paar voorbeelden.
>
>**[!UICONTROL In past before]**
>
>Gebruik deze operator voor je nieuwe aanbieding om alleen e-mails te verzenden aan mensen die zich niet binnen een jaar hebben geabonneerd op of verlengd van je service of die nog nooit een abonnement hebben genomen.
>
>**[!UICONTROL In future after]**
>
>Zeg u klanten wilt zien die voor vernieuwing in 90 dagen omhoog zijn. Er worden twee afzonderlijke filters gebruikt. Gebruik eerst &quot;In Future After 90 days&quot; en daarna &quot;In Future 91 Days&quot;. Dat zou datgene vastleggen wat over 90 dagen een datum heeft.

## Reeksvelden {#string-fields}

![](assets/image2014-9-10-17-3a16-3a6.png)

| Operator | Beschrijving |
|---|---|
| is | Exacte overeenkomst (niet hoofdlettergevoelig) |
| is niet | Alles behalve exact overeenkomen |
| begint met | Eerste tekenreeksletters |
| begint niet met | Eerste letters van tekenreeks KOMEN NIET overeen |
| contains | Alle letters in de tekenreeks komen overeen (bijvoorbeeld: california, fortune, daarvoor) |
| bevat niet | Geen letters in de tekenreeks komen overeen. (reverse van &quot;contains&quot;) |
| is leeg | Records die geen waarde hebben (NULL) |
| is niet leeg | Records met ANY-waarde |

>[!TIP]
>
>Gebruik positieve operatoren in plaats van negatieve operatoren. Filters &#39;Is niet&#39; moeten de gehele gegevensset in uw instantie doorzoeken, wat bijzonder tijdrovend kan zijn. Positieve &#39;is&#39;-filters kunnen effectievere zoekalgoritmen gebruiken.

## Gehele velden {#integer-fields}

![](assets/image2014-9-10-17-3a16-3a14.png)

<table> 
 <thead> 
  <tr> 
   <th colspan="1" rowspan="1">Operator</th> 
   <th colspan="1" rowspan="1">Beschrijving</th> 
  </tr> 
 </thead> 
 <tbody> 
  <tr> 
   <td colspan="1" rowspan="1">is</td> 
   <td colspan="1" rowspan="1">De nauwkeurige aantalgelijke ( = 0 zal beide lood met 0 terugkeren <em>en</em> NULL)</td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1">is niet</td> 
   <td colspan="1" rowspan="1">Alles behalve exact aantal komt overeen</td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1">Tussen</td> 
   <td colspan="1" rowspan="1">Definieer twee waarde om iedereen tussen (inclusief) te vinden</td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1">groter dan</td> 
   <td colspan="1" rowspan="1">Boven de opgegeven</td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1">minder dan</td> 
   <td colspan="1" rowspan="1">Minder dan opgegeven</td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1">ten minste</td> 
   <td colspan="1" rowspan="1">Boven het opgegeven (inclusief)</td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1">hoogstens</td> 
   <td colspan="1" rowspan="1">Kleiner dan opgegeven (inclusief)</td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1">is leeg</td> 
   <td colspan="1" rowspan="1">Records die geen waarde hebben (NULL) - nul is een getal, het is <em>niet</em> NULL</td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1">is niet leeg</td> 
   <td colspan="1" rowspan="1">Records met ANY-waarde (inclusief nul)</td> 
  </tr> 
 </tbody> 
</table>

Zoals u ziet, maken deze operatoren het gemakkelijk om Marketo-ese met soepelheid te spreken!
