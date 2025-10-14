---
unique-page-id: 2951259
description: Verklarende woordenlijst Type aangepast veld - Marketo Docs - Productdocumentatie
title: Verklarende woordenlijst Type aangepast veld
exl-id: 495d4deb-28f1-4044-98d3-27c20756fe73
feature: Field Management
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '594'
ht-degree: 0%

---

# Verklarende woordenlijst Type aangepast veld {#custom-field-type-glossary}

Wanneer u een aangepast veld maakt in Marketo, hebt u een lijst met typen waaruit u kunt kiezen.

>[!PREREQUISITES]
>
>[&#x200B; creeer een Gebied van de Douane in Marketo &#x200B;](/help/marketo/product-docs/administration/field-management/create-a-custom-field-in-marketo.md)

>[!TIP]
>
>Afhankelijk van gebiedstype, filter/trekker [&#x200B; exploitanten &#x200B;](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/smart-list-filter-operators-glossary.md) zal verschillend zijn.

>[!NOTE]
>
>De meeste velden worden niet uitgelijnd op het aantal tekens, maar op het aantal bytes. Daarom kunnen we geen definitieve tekenlimiet opgeven voor elk veld. De uitzondering is **Koord**, dat bij 255 karakters maxes.

## Boolean {#boolean}

**Naam van het Voorbeeld:** is Klant - neem uw mensen als klanten in kaart

**Waarden van het Voorbeeld:** Waar (gecontroleerd)/Onwaar (ongecontroleerd)

**Operatoren**: niets

## Valuta {#currency}

**Naam van het Voorbeeld:** Begroting - sla een aantalwaarde voor het budget van een bedrijf op

**Waarden van het Voorbeeld:** 100

**Operatoren**: is, is niet, tussen, groter dan, minder dan, minstens, is leeg, is niet leeg

## Datum {#date}

**Naam van het Voorbeeld:** VerlengingsDatum - sla uw klanten vernieuwingsdata op

**Waarden van het Voorbeeld:** 8/19/14

**Operatoren**: is, is niet, tussen, in het verleden, in het verleden vóór, in de toekomst, na, in tijdkader, na, vóór, op of na, op of vóór, leeg is, is niet leeg

## Datumtijd {#datetime}

**Naam van het Voorbeeld:** Gemaakt Datum - sla de datum en de tijd op waarop een persoon wordt gecreeerd

**Waarden van het Voorbeeld:** 8/19/14 2 :00

**Operatoren**: is, is niet, tussen, in het verleden, in het verleden vóór, in de toekomst, na, in tijdkader, na, vóór, op of na, op of vóór, leeg is, is niet leeg

## E-mail {#email}

**Naam van het Voorbeeld:** Afwisselende E-mail - houd een afwisselend e-mailadres voor uw mensen (kan geen e-mails naar dit gebied zoals het standaard e-mailadresgebied eigenlijk verzenden, dat één speciaal is)

**Waarden van het Voorbeeld:** <name@company.com>

**Operatoren**: is, begint niet met, begint niet met, bevat, bevat, bevat niet, is leeg, is niet leeg

## Float {#float}

**Naam van het Voorbeeld:** het Gemiddelde van het Punt van de Grade - houd het gemiddelde van het de rangspunt van een persoon of een andere numerieke waarde die decimalen heeft

**Waarden van het Voorbeeld:** 2.47

**Operatoren**: tussen, groter dan, minder dan, minstens, is leeg, is niet leeg

## Formule {#formula}

**Naam van het Voorbeeld:** Aanpassingen - gebruik dit speciale gebied in a [&#x200B; oplossing om de juiste aanhef &#x200B;](/help/marketo/product-docs/administration/field-management/create-and-use-a-concatenated-string-formula-field.md) te krijgen die op gender wordt gebaseerd

**Waarden van het Voorbeeld:** controleer de verbonden oplossing

## Geheel {#integer}

**Naam van het Voorbeeld:** Aantal Werknemers - sla een aantalwaarde op die decimalen niet vereist

**Waarden van het Voorbeeld:** 600

**Operatoren**: is, is niet, tussen, groter dan, minder dan, minstens, is leeg, is niet leeg

## Percentage {#percent}

**Naam van het Voorbeeld:** Waarschijnlijk om te kopen - opslag een percentagewaarde (misschien berekend op de kant van CRM)

**Waarden van het Voorbeeld:** 85%

**Operatoren**: is, is niet, tussen, groter dan, minder dan, minstens, is leeg, is niet leeg

## Telefoonnummer {#phone}

**Naam van het Voorbeeld:** Alternatieve Telefoon - sla een extra telefoonaantal voor uw mensen op

**Waarde van het Voorbeeld:** 650-555-5555

**Operatoren**: is, begint niet met, begint niet met, bevat, bevat, bevat niet, is leeg, is niet leeg

## Score {#score}

**Naam van het Voorbeeld:** De Score van het Gedrag/de Demografische Score - creeer veelvoudige scorevelden om spoor van verschillende attributen te houden

**Waarde van het Voorbeeld:** 14

**Operatoren**: is, is niet, tussen, groter dan, minder dan, minstens, is leeg, is niet leeg

## String {#string}

**Naam van het Voorbeeld:** Middnaam - sla een extra tekstattribuut op

**Waarde van het Voorbeeld:** Roze

**Operatoren**: is, begint niet met, begint niet met, bevat, bevat, bevat niet, is leeg, is niet leeg

## Tekstgebied {#text-area}

**Naam van het Voorbeeld:** Commentaren - voeg een commentaargebied aan uw vormen toe om multi-line tekstingang toe te staan

**Waarde van het Voorbeeld:** Dit artikel is fantastisch!

**Operatoren**: is, begint niet met, begint niet met, bevat, bevat, bevat niet, is leeg, is niet leeg

## URL {#url}

**Naam van het Voorbeeld:** Blog - creeer een gebied om persoonblog URL&#39;s op te slaan

**Waarde van het Voorbeeld:** &lt;www.myblog.com>

**Operatoren**: is, begint niet met, begint niet met, bevat, bevat, bevat niet, is leeg, is niet leeg
