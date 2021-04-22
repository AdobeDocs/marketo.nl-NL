---
unique-page-id: 2951259
description: Verklarende woordenlijst Type aangepast veld - Marketo Docs - Productdocumentatie
title: Verklarende woordenlijst Type aangepast veld
exl-id: 495d4deb-28f1-4044-98d3-27c20756fe73
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '583'
ht-degree: 0%

---

# Verklarende woordenlijst voor aangepaste veldtype {#custom-field-type-glossary}

Wanneer u een aangepast veld maakt in Marketo, hebt u een lijst met typen waaruit u kunt kiezen.

>[!PREREQUISITES]
>
>[Een aangepast veld maken in Marketo](/help/marketo/product-docs/administration/field-management/create-a-custom-field-in-marketo.md)

>[!TIP]
>
>Afhankelijk van het veldtype zullen filter/trigger [operators](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/smart-list-filter-operators-glossary.md) verschillend zijn.

>[!NOTE]
>
>De meeste velden hebben niet het maximale aantal tekens, maar het maximale aantal bytes. Daarom kunnen we geen definitieve tekenlimiet opgeven voor elk veld. De uitzondering is **String**, die bij 255 karakters uitkomt.

## Booleaans {#boolean}

**Voorbeeldnaam:** is klant - Tags toewijzen aan uw personen als klanten

**Voorbeelden:** Waar (ingeschakeld) / Onwaar (uitgeschakeld)

**Operatoren**: Geen

## Valuta {#currency}

**Voorbeeldnaam:** Begroting - Een getalwaarde opslaan voor het budget van een bedrijf

**Voorbeelden:** 100

**Operatoren**: is, is niet, tussen, groter dan, minstens, is leeg, is niet leeg

## Datum {#date}

**Voorbeeldnaam:** Verlengingsdatum - Verlengingsdatums voor uw klanten opslaan

**Voorbeelden:** 19-08-14

**Operatoren**: is, is niet, tussen, in het verleden, vóór, in de toekomst, na, in tijdkader, nadat, vóór, op of na, op of vóór, leeg is, is niet leeg

## Datumtijd {#datetime}

**Voorbeeldnaam:** Gemaakt op - Sla de datum en het tijdstip op waarop een persoon is gemaakt

**Voorbeelden:** 8/19/14 2:00

**Operatoren**: is, is niet, tussen, in het verleden, vóór, in de toekomst, na, in tijdkader, nadat, vóór, op of na, op of vóór, leeg is, is niet leeg

## E-mail {#email}

**Voorbeeld Naam:** Alternatieve e-mail - Houd een alternatief e-mailadres voor uw mensen (kan geen e-mails naar dit veld verzenden zoals het standaard e-mailadresveld, dat is speciaal)

**voorbeeldwaarden:** name@company.com

**Operatoren**: is, is niet, begint met, begint niet met, bevat, bevat, is leeg, is niet leeg

## Zweven {#float}

**Voorbeeldnaam:Gemiddelde** verlooppunt - Het gemiddelde van het scorepunt van een persoon of een andere numerieke waarde met decimalen behouden

**Voorbeelden:** 2.47

**Operatoren**: tussen, groter dan, kleiner dan, minstens, is leeg, is niet leeg

## Formule {#formula}

**Voorbeeldnaam:** Salutaties - gebruik dit speciale veld in een  [oplossing om de juiste ](/help/marketo/product-docs/administration/field-management/create-and-use-a-concatenated-string-formula-field.md) salutatie op basis van geslacht te krijgen

**Voorbeeldwaarden:gekoppelde oplossing** controleren

## Geheel getal {#integer}

**Voorbeeldnaam:** Aantal werknemers - sla een getalwaarde op die geen decimalen vereist

**Voorbeelden:** 600

**Operatoren**: is, is niet, tussen, groter dan, minstens, is leeg, is niet leeg

## Percentage {#percent}

**Voorbeeldnaam:** Waarschijnlijk een percentagewaarde kopen - opslaan (wellicht berekend aan de CRM-zijde)

**Voorbeelden:** 85%

**Operatoren**: is, is niet, tussen, groter dan, minstens, is leeg, is niet leeg

## Telefoonnummer {#phone}

**Voorbeeld Naam:** Alternatieve Telefoon - sla een extra telefoonaantal voor uw mensen op

**Voorbeeld:** 650-555-5555

**Operatoren**: is, is niet, begint met, begint niet met, bevat, bevat, is leeg, is niet leeg

## Score {#score}

**Voorbeeldnaam:** Gedragsscore / Demografische score - Maak meerdere score-velden om verschillende kenmerken bij te houden.

**Voorbeeld:** 14

**Operatoren**: is, is niet, tussen, groter dan, minstens, is leeg, is niet leeg

## Tekenreeks {#string}

**Voorbeeldnaam:** Tweede voornaam - een extra tekstkenmerk opslaan

**voorbeeldwaarde:** Rose

**Operatoren**: is, is niet, begint met, begint niet met, bevat, bevat, is leeg, is niet leeg

## Tekstgebied {#text-area}

**Voorbeeldnaam:** Opmerkingen - voeg een opmerkingenveld toe aan uw formulieren om meerregelige tekstinvoer toe te staan

**Voorbeeld:** dit artikel is fantastisch!

**Operatoren**: is, is niet, begint met, begint niet met, bevat, bevat, is leeg, is niet leeg

## URL {#url}

**Voorbeeldnaam:** Blog - een veld maken voor het opslaan van persoonlijke blogURL&#39;s

**Voorbeeld:** www.myblog.com

**Operatoren**: is, is niet, begint met, begint niet met, bevat, bevat, is leeg, is niet leeg
