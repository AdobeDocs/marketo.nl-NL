---
unique-page-id: 557312
description: Verklarende woordenlijst van slimme-lijstfilteroperatoren - Marketo Docs - Productdocumentatie
title: Verklarende woordenlijst voor slimme-lijstfilteroperatoren
exl-id: 5a370482-f214-4909-bb49-801c1a36b153
feature: Smart Lists
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '603'
ht-degree: 1%

---

# Verklarende woordenlijst voor slimme-lijstfilteroperatoren {#smart-list-filter-operators-glossary}

Een exploitant is een deel van de Slimme Lijst die u helpt specifiek worden. Hiermee kunt u het filter of de trigger in een eenvoudige taal beschrijven. De beschikbare operatoren verschillen per veldtype.

Hier volgt een verklarende woordenlijst die elke reeks exploitanten beschrijft.

## Datumvelden {#date-fields}

![](assets/smart-list-filter-operators-glossary-1.png)

Wanneer u een operator kiest, verandert de rechterzijde dynamisch.

<table><thead>
  <tr>
    <th>Operator</th>
    <th>Rechterkant</th>
    <th>Beschrijving</th>
  </tr></thead>
<tbody>
  <tr>
    <td>is</td>
    <td>Enkele datum</td>
    <td>Exacte datumovereenkomst</td>
  </tr>
  <tr>
    <td>is niet</td>
    <td>Enkele datum</td>
    <td>Elke datum behalve de opgegeven datum</td>
  </tr>
  <tr>
    <td>Tussen</td>
    <td>Twee datumvelden</td>
    <td>Elke datum met en tussen twee opgegeven data</td>
  </tr>
  <tr>
    <td>in het verleden</td>
    <td>Invoer in natuurlijke taal*</td>
    <td>Zie onderstaande figuur</td>
  </tr>
  <tr>
    <td>in het verleden</td>
    <td>Invoer in natuurlijke taal*</td>
    <td>Zie onderstaande figuur</td>
  </tr>
  <tr>
    <td>in de toekomst</td>
    <td>Invoer in natuurlijke taal*</td>
    <td>Zie onderstaande figuur</td>
  </tr>
  <tr>
    <td>later</td>
    <td>Invoer in natuurlijke taal*</td>
    <td>Zie onderstaande figuur</td>
  </tr>
  <tr>
    <td>in tijdkader</td>
    <td>Voorinstellingen (afgelopen kwartaal, gisteren, enz.)</td>
    <td>Gedefinieerd in picklist</td>
  </tr>
  <tr>
    <td>na</td>
    <td>Enkele datum</td>
    <td>Alle records na de opgegeven datum</td>
  </tr>
  <tr>
    <td>voor</td>
    <td>Enkele datum</td>
    <td>Alle records voor de opgegeven record</td>
  </tr>
  <tr>
    <td>op of na</td>
    <td>Enkele datum</td>
    <td>Gelijk aan "after" maar inclusief</td>
  </tr>
  <tr>
    <td>op of voor</td>
    <td>Enkele datum</td>
    <td>Gelijk aan "before" maar inclusief</td>
  </tr>
  <tr>
    <td>is leeg</td>
    <td>Geen</td>
    <td>Alle records zonder datum</td>
  </tr>
  <tr>
    <td>is niet leeg</td>
    <td>Geen</td>
    <td>Alle records met een willekeurige datum</td>
  </tr>
</tbody></table>

**&#42;** Invoer in de natuurlijke taal is cool. Hier volgen enkele voorbeelden van patronen die u kunt invoeren:

* 1 uur
* 82 dagen
* 3 weken
* 14 maanden
* 1 jaar

Typ gewoon het nummer en de eenheid en het werkt!

>[!NOTE]
>
>&quot;In het verleden&quot; _omvat_ de dag (tot de tijd, niet na) u uw Slimme Lijst creeert.

>[!CAUTION]
>
>Wanneer u een slimme lijst maakt met een datumveldfilter (bijvoorbeeld Geboortedatum, Gemaakt op SFDC) en de beperkingen **[!UICONTROL before]**, **[!UICONTROL on or before]** of **[!UICONTROL in past before]** gebruikt, bevat de slimme lijst ook personen die geen waarde hebben in het datumveld.

Gebruik het volgende diagram om het verschil tussen de datumoperatoren te begrijpen.

![](assets/smart-list-filter-operators-glossary-2.png)

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

![](assets/smart-list-filter-operators-glossary-3.png)

<table><thead>
  <tr>
    <th>Operator</th>
    <th>Beschrijving</th>
  </tr></thead>
<tbody>
  <tr>
    <td>is</td>
    <td>Exacte overeenkomst (niet hoofdlettergevoelig)</td>
  </tr>
  <tr>
    <td>is niet</td>
    <td>Alles behalve exact overeenkomen</td>
  </tr>
  <tr>
    <td>begint met</td>
    <td>Eerste tekenreeksletters</td>
  </tr>
  <tr>
    <td>begint niet met</td>
    <td>Eerste letters van tekenreeks KOMEN NIET overeen</td>
  </tr>
  <tr>
    <td>contains</td>
    <td>Alle letters in de tekenreeks komen overeen (bijvoorbeeld: california, fortune, daarvoor)</td>
  </tr>
  <tr>
    <td>bevat niet</td>
    <td>Geen letters in de tekenreeks komen overeen. (reverse van "contains")</td>
  </tr>
  <tr>
    <td>is leeg</td>
    <td>Records die geen waarde hebben (NULL)</td>
  </tr>
  <tr>
    <td>is niet leeg</td>
    <td>Records met ANY-waarde</td>
  </tr>
</tbody>
</table>

>[!TIP]
>
>Gebruik positieve operatoren in plaats van negatieve operatoren. Filters &#39;Is niet&#39; moeten de gehele gegevensset in uw instantie doorzoeken, wat bijzonder tijdrovend kan zijn. Positieve &#39;is&#39;-filters kunnen effectievere zoekalgoritmen gebruiken.

## Gehele velden {#integer-fields}

![](assets/smart-list-filter-operators-glossary-4.png)

<table><thead>
  <tr>
    <th>Operator</th>
    <th>Beschrijving</th>
  </tr></thead>
<tbody>
  <tr>
    <td>is</td>
    <td>De nauwkeurige aantalgelijke ( = 0 zal zowel lood met 0 als ONGELDIG terugkeren)</td>
  </tr>
  <tr>
    <td>is niet</td>
    <td>Alles behalve exact aantal komt overeen</td>
  </tr>
  <tr>
    <td>Tussen</td>
    <td>Definieer twee waarde om iedereen tussen (inclusief) te vinden</td>
  </tr>
  <tr>
    <td>groter dan</td>
    <td>Boven de opgegeven</td>
  </tr>
  <tr>
    <td>minder dan</td>
    <td>Minder dan opgegeven</td>
  </tr>
  <tr>
    <td>ten minste</td>
    <td>Boven het opgegeven (inclusief)</td>
  </tr>
  <tr>
    <td>hoogstens</td>
    <td>Kleiner dan opgegeven (inclusief)</td>
  </tr>
  <tr>
    <td>is leeg</td>
    <td>Records die geen waarde hebben (NULL) - nul is een getal, het is niet NULL</td>
  </tr>
  <tr>
    <td>is niet leeg</td>
    <td>Records met ANY-waarde (inclusief nul)</td>
  </tr>
</tbody>
</table>

Zoals u ziet, maken deze operatoren het gemakkelijk om Marketo-ese met soepelheid te spreken!
