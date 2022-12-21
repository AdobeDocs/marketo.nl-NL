---
unique-page-id: 7512524
description: Beste praktijken voor Slimme Lijsten - de Documenten van Marketo - de Documentatie van het Product
title: Beste praktijken voor Slimme Lijsten
exl-id: 466de198-1012-4ac3-906c-d41943fe5bc0
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '521'
ht-degree: 0%

---

# Beste praktijken voor Slimme Lijsten {#best-practices-for-smart-lists}

Slimme lijsten zijn het krachtigste zoekprogramma in het marketinguniversum. Ze vinden de mensen die je zoekt met magische snelheid en gemak.

Om hen gemakkelijk te maken om met en prestaties te werken te optimaliseren, hebben wij een lijst van goede praktijken gecreeerd. Veel plezier!

>[!NOTE]
>
>**Elke klant is anders.** Hoe groter de database, hoe meer verwerking er plaatsvindt. Hoe meer activiteiten u hebt opgeslagen, hoe langer het duurt om er doorheen te zoeken.
>
>Probeer de onderstaande tips als u te maken hebt met een trage procedure. Neem contact op met [Marketo-ondersteuning](https://nation.marketo.com/t5/Support/ct-p/Support).

1. **Historie beperken -** Historiefilters (ook bekend als Activiteitenfilters) behoren tot de meest hulpbronnenintensieve, tijdrovende bewerkingen. Als u ze moet gebruiken, probeert u het datumbereik zo kort mogelijk te houden. Hierdoor wordt de set doorzoekbare gegevens kleiner.
1. **Geneste slimme lijsten beperken -** Beperk bij het maken van een nieuwe slimme lijst de hoeveelheid gebruikte filters Lid van Slimme lijst. Dit wordt genoemd het nesten slimme lijsten, en elke slimme lijst waarnaar wordt verwezen zal verwerkingstijd verhogen. Verwijs in plaats daarvan naar statische lijsten of gebruik [segmentatie](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/create-a-segmentation.md).
1. **Positief gebruiken over negatieve operatoren -** Hoewel filters &quot;niet&quot;beschikbaar zijn, moeten zij de volledige gegevensreeks in uw instantie zoeken, die uiterst tijdrovend kan zijn. Positieve &#39;is&#39;-filters kunnen effectievere zoekalgoritmen gebruiken.
1. **Vermijd &quot;contains&quot; -** Als u slechts gedeeltelijke gegevens hebt, &quot;begint met&quot;bepalende eigenschappen zullen veel sneller resultaten dan &quot;bevat.&quot; &quot;Is&quot; wordt nog sneller uitgevoerd. Vermijd het gebruik van &quot;contains&quot; met meerdere waarden; de twee samen kunnen een campagne nog verder vertragen .
1. **Willekeurig monster zelfstandig gebruiken -** Willekeurig monster is een speciaal filter. Gebruik het op zich om uw mensen in pre-made lijsten te zetten. Gebruik vervolgens gewoon &#39;lid van lijst&#39; om uw slimme lijst supersnel te maken. Willekeurige sample **NOT** werken met geneste slimme lijsten. Het filter Willekeurige sample werkt niet als er naar de slimme lijst wordt verwezen voor het filter &quot;Lid van slimme lijst&quot;.
1. **Wees zacht met inactiviteitsfilters -** Filters als &quot;Formulier Niet ingevuld&quot; kunnen erg nuttig zijn, maar vereisen veel meer verwerkingskracht.
1. **Wees zachtaardig met plakken in meerdere waarden -** Multi-select is ontworpen voor het plakken in tientallen of mogelijk honderden waarden. Te veel inbrengen, en dat zal vertragen.
1. **Wees zachtaardig wanneer u beperkingen toevoegt -** Dit zijn de kleine details van een regel en gerelateerde waarden. Hoe meer beperkingen u toevoegt, hoe langzamer de verwerkingstijd.
1. **Vereenvoudig uw campagnes -** 100+ onafhankelijke regels (we hebben het gezien!) het is duidelijk dat het enige tijd zal duren voordat het proces is afgerond . Houd het eenvoudig en u zult de snelheidswinst merken - plus het zal voor u gemakkelijker zijn te begrijpen.
1. **@-symbool vóór domeinnaam opnemen wanneer het filter E-mailadres wordt gebruikt** **-** Hierdoor wordt er een snellere query gebruikt. Voorbeeld: In plaats van _email bevat &#39;somedomain.com&#39;_, gebruik _email bevat &#39;@somedomain.com_.&quot; Als u meerdere e-mailadressen gebruikt met &#39;contains&#39;, moeten ze allemaal beginnen met &#39;@.&#39;

>[!TIP]
>
>Marketo kan op vele manieren worden gebruikt en bepaalde technieken zijn beter voor u en uw bedrijf. Overweeg [Professionele dienstverlening in Marketo](https://pages2.marketo.com/72-hour-survival-guide.html) om uw investering te doen schijnen.
