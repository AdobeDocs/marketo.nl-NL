---
unique-page-id: 2951259
description: Verklarende woordenlijst Type aangepast veld - Marketo Docs - Productdocumentatie
title: Verklarende woordenlijst Type aangepast veld
exl-id: 495d4deb-28f1-4044-98d3-27c20756fe73
feature: Field Management
source-git-commit: 02b2e39580c5eac63de4b4b7fdaf2a835fdd4ba5
workflow-type: tm+mt
source-wordcount: '583'
ht-degree: 0%

---

# Verklarende woordenlijst Type aangepast veld {#custom-field-type-glossary}

Wanneer u een aangepast veld maakt in Marketo, hebt u een lijst met typen waaruit u kunt kiezen.

>[!PREREQUISITES]
>
>[Een aangepast veld maken in Marketo](/help/marketo/product-docs/administration/field-management/create-a-custom-field-in-marketo.md)

>[!TIP]
>
>Afhankelijk van het veldtype, filter/trigger [operatoren](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/smart-list-filter-operators-glossary.md) zal anders zijn.

>[!NOTE]
>
>De meeste velden worden niet uitgelijnd op het aantal tekens, maar op het aantal bytes. Daarom kunnen we geen definitieve tekenlimiet opgeven voor elk veld. De uitzondering is **String**, die maximaal 255 tekens bevat.

## Boolean {#boolean}

**Voorbeeldnaam:** Is Klant - Tags toewijzen aan uw mensen als klanten

**Voorbeelden:** Waar (ingeschakeld) / Onwaar (uitgeschakeld)

**Operatoren**: Geen

## Valuta {#currency}

**Voorbeeldnaam:** Begroting - Bewaar een getalwaarde voor de begroting van een bedrijf

**Voorbeelden:** 100

**Operatoren**: is, is niet, tussen, groter dan, minstens, is leeg, is niet leeg

## Datum {#date}

**Voorbeeldnaam:** Verlengingsdatum - Verlengingsdatums voor uw klanten opslaan

**Voorbeelden:** 19-08-14

**Operatoren**: is, is niet, tussen, in het verleden, vóór, in de toekomst, na, in tijdkader, nadat, vóór, op of na, op of vóór, leeg is, is niet leeg

## Datumtijd {#datetime}

**Voorbeeldnaam:** Aanmaakdatum - Sla de datum en het tijdstip op waarop een persoon wordt gemaakt

**Voorbeelden:** 19-08-14 2:00

**Operatoren**: is, is niet, tussen, in het verleden, vóór, in de toekomst, na, in tijdkader, nadat, vóór, op of na, op of vóór, leeg is, is niet leeg

## E-mail {#email}

**Voorbeeldnaam:** Alternatieve e-mail - Houd een alternatief e-mailadres voor uw mensen (kan geen e-mails naar dit veld verzenden, zoals het standaard e-mailadresveld, dat een speciaal adres is)

**Voorbeelden:** name@company.com

**Operatoren**: is, is niet, begint met, begint niet met, bevat, bevat, is leeg, is niet leeg

## Float {#float}

**Voorbeeldnaam:** Gemiddelde scorepunt - Behoud het gemiddelde van het scorepunt van een persoon of een andere numerieke waarde met decimalen

**Voorbeelden:** 2,47

**Operatoren**: tussen, groter dan, kleiner dan, minstens, is leeg, is niet leeg

## Formule {#formula}

**Voorbeeldnaam:** Aanhef - gebruik dit speciale veld in een [Oplossing voor de juiste aanhef](/help/marketo/product-docs/administration/field-management/create-and-use-a-concatenated-string-formula-field.md) op basis van geslacht

**Voorbeelden:** controleer de verbonden oplossing

## Geheel {#integer}

**Voorbeeldnaam:** Aantal Werknemers - sla een aantalwaarde op die decimalen niet vereist

**Voorbeelden:** 600

**Operatoren**: is, is niet, tussen, groter dan, minstens, is leeg, is niet leeg

## Percentage {#percent}

**Voorbeeldnaam:** Waarschuwing: koop een percentage op (misschien berekend aan de CRM-zijde)

**Voorbeelden:** 85%

**Operatoren**: is, is niet, tussen, groter dan, minstens, is leeg, is niet leeg

## Telefoonnummer {#phone}

**Voorbeeldnaam:** Alternatieve Telefoon - sla een extra telefoonaantal voor uw mensen op

**Voorbeeld:** 650-555-5555

**Operatoren**: is, is niet, begint met, begint niet met, bevat, bevat, is leeg, is niet leeg

## Score {#score}

**Voorbeeldnaam:** Gedragsscore / Demografische score - meerdere muziekvelden maken om verschillende kenmerken bij te houden

**Voorbeeld:** 14

**Operatoren**: is, is niet, tussen, groter dan, minstens, is leeg, is niet leeg

## String {#string}

**Voorbeeldnaam:** Tweede voornaam - een extra tekstkenmerk opslaan

**Voorbeeld:** Roze

**Operatoren**: is, is niet, begint met, begint niet met, bevat, bevat, is leeg, is niet leeg

## Tekstgebied {#text-area}

**Voorbeeldnaam:** Opmerkingen - voeg een opmerkingenveld toe aan uw formulieren zodat tekst op meerdere regels kan worden ingevoerd

**Voorbeeld:** Dit artikel is fantastisch!

**Operatoren**: is, is niet, begint met, begint niet met, bevat, bevat, is leeg, is niet leeg

## URL {#url}

**Voorbeeldnaam:** Blog - een veld maken voor het opslaan van persoonlijke blogURL&#39;s

**Voorbeeld:** www.myblog.com

**Operatoren**: is, is niet, begint met, begint niet met, bevat, bevat, is leeg, is niet leeg
