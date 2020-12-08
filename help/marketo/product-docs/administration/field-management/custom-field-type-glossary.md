---
unique-page-id: 2951259
description: Aangepaste woordenlijst veldtype - Marketo Docs - Productdocumentatie
title: Verklarende woordenlijst Type aangepast veld
translation-type: tm+mt
source-git-commit: 00887ea53e395bea3a11fd28e0ac98b085ef6ed8
workflow-type: tm+mt
source-wordcount: '658'
ht-degree: 0%

---


# Verklarende woordenlijst Type aangepast veld {#custom-field-type-glossary}

>[!NOTE]
>
>**FYI**
>
>Marketo is nu bezig met het standaardiseren van de taal voor alle abonnementen, dus u ziet mogelijk leads/leads in uw abonnement en personen/personen in docs.marketo.com. Deze termen betekenen hetzelfde. het heeft geen invloed op de instructies van het artikel . Er zijn nog enkele andere veranderingen. [Meer](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)informatie.

Wanneer u een aangepast veld maakt in Marketo, hebt u een lijst met typen waaruit u kunt kiezen.

>[!NOTE]
>
>**Vereisten**
>
>* [Een aangepast veld maken in Marketo](create-a-custom-field-in-marketo.md)

>



>[!TIP]
>
>Afhankelijk van het veldtype zijn de [operatoren](https://docs.marketo.com/display/public/DOCS/Smart+List+Filter+Operators+Glossary) voor filter/trigger anders.

>[!NOTE]
>
>De meeste velden hebben niet het maximale aantal tekens, maar het maximale aantal bytes. Daarom kunnen we geen definitieve tekenlimiet opgeven voor elk veld. De uitzondering is **String**, die maximaal 255 tekens lang is.

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

**Voorbeelden:** [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#335d525e5673505c5e43525d4a1d505c5e)

**Operatoren**: is, is niet, begint met, begint niet met, bevat, bevat, is leeg, is niet leeg

## Float {#float}

**Voorbeeldnaam:** Gemiddelde scorepunt - Behoud het gemiddelde van het scorepunt van een persoon of een andere numerieke waarde met decimalen

**Voorbeelden:** 2,47

**Operatoren**: tussen, groter dan, kleiner dan, minstens, is leeg, is niet leeg

## Formule {#formula}

**Voorbeeldnaam:** Salutaties - gebruik dit speciale veld in een [oplossing om de juiste salutatie](create-and-use-a-concatenated-string-formula-field.md) te krijgen op basis van geslacht

**Voorbeelden:** controleer de verbonden oplossing

## Geheel {#integer}

**Voorbeeldnaam:** Aantal Werknemers - sla een aantalwaarde op die decimalen niet vereist

**Voorbeelden:** 600

**Operatoren**: is, is niet, tussen, groter dan, minstens, is leeg, is niet leeg

## Percentage {#percent}

**Voorbeeldnaam:** Waarschuwing: een percentage opslaan (wellicht berekend aan de CRM-zijde)

**Voorbeelden:** 85%

**Operatoren**: is, is niet, tussen, groter dan, minstens, is leeg, is niet leeg

## Telefoon {#phone}

**Voorbeeldnaam:** Alternatieve Telefoon - sla een extra telefoonaantal voor uw mensen op

**Voorbeeld:** 650-555-5555

**Operatoren**: is, is niet, begint met, begint niet met, bevat, bevat, is leeg, is niet leeg

## Score {#score}

**Voorbeeldnaam:** Gedragsscore / Demografische score: maak meerdere muziekvelden om verschillende kenmerken bij te houden.

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
