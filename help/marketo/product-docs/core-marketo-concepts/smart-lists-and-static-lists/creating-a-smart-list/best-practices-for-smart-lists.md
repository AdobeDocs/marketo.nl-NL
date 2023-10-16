---
unique-page-id: 7512524
description: Aanbevolen procedures voor slimme lijsten - Marketo Docs - Productdocumentatie
title: Beste praktijken voor Slimme Lijsten
exl-id: 466de198-1012-4ac3-906c-d41943fe5bc0
feature: Smart Lists
source-git-commit: 0e68da238100f3816c2e64e1fbe4a5a2892bb3e1
workflow-type: tm+mt
source-wordcount: '573'
ht-degree: 0%

---

# Beste praktijken voor Slimme Lijsten {#best-practices-for-smart-lists}

Slimme lijsten zijn het krachtigste zoekprogramma in het marketinguniversum. Ze vinden de mensen die je zoekt met magische snelheid en gemak.

Om hen gemakkelijk te maken om met en prestaties te werken te optimaliseren, hebben wij een lijst van goede praktijken gecreeerd. Veel plezier!

>[!NOTE]
>
>**Elke gebruiker van het Marketo Engage is anders.** Hoe groter de database, hoe meer verwerking er plaatsvindt. Hoe meer activiteiten u hebt opgeslagen, hoe langer het duurt om er doorheen te zoeken.
>
>Probeer de onderstaande tips als u te maken hebt met een trage procedure. Neem contact op met [Marketo-ondersteuning](https://nation.marketo.com/t5/Support/ct-p/Support){target="_blank"}.

1. **Historie beperken -** Historiefilters (ook wel activiteitsfilters genoemd) behoren tot de meest hulpbronnenintensieve, tijdrovende bewerkingen. Als u ze moet gebruiken, probeert u het datumbereik zo kort mogelijk te houden. Hierdoor wordt de set doorzoekbare gegevens kleiner. Bovendien hebben datumbereiken geen voorrang op retentieperioden. Voorbeeld: Als de activiteit u vraagt een bewaartermijn van 90 dagen heeft en u &quot;afgelopen 100 dagen&quot;kiest, slechts zullen de resultaten van de afgelopen 90 dagen worden teruggegeven. Aanhoudingsperiodes activiteit [hier te vinden](https://nation.marketo.com/t5/knowledgebase/marketo-activities-data-retention-policy/ta-p/251480){target="_blank"}.
1. **Geneste slimme lijsten beperken -** Wanneer u een nieuwe slimme lijst maakt, moet u de hoeveelheid gebruikte filters Lid van slimme lijst beperken. Dit wordt genoemd het nesten Slimme Lijsten, en elke Slimme Lijst waarnaar wordt verwezen zal verwerkingstijd verhogen. Verwijs in plaats daarvan naar statische lijsten of gebruik [segmentatie](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/create-a-segmentation.md){target="_blank"}.
1. **Positief gebruiken over negatieve operatoren -** Hoewel filters &quot;niet&quot;beschikbaar zijn, moeten zij de volledige gegevensreeks in uw instantie zoeken, die uiterst tijdrovend kan zijn. Positieve &#39;is&#39;-filters kunnen effectievere zoekalgoritmen gebruiken.
1. **Vermijd &quot;contains&quot; -** Als u slechts gedeeltelijke gegevens hebt, &quot;begint met&quot;bepalende eigenschappen zullen veel sneller resultaten dan &quot;bevat.&quot; &quot;Is&quot; wordt nog sneller uitgevoerd. Vermijd het gebruik van &quot;contains&quot; met meerdere waarden. De twee tezamen kunnen een campagne nog verder vertragen.
1. **Willekeurig monster zelfstandig gebruiken -** Willekeurig monster is een speciaal filter. Gebruik het op zich om uw mensen in pre-made lijsten te zetten. Dan gebruik enkel &quot;Lid van Lijst&quot;om uw Slimme Lijst super snel te maken. Willekeurige sample **NOT** werken met geneste slimme lijsten. Het filter Willekeurige sample werkt niet als er naar de slimme lijst wordt verwezen voor het filter &quot;Lid van slimme lijst&quot;.
1. **Wees zacht met inactiviteitsfilters -** Filters als &quot;Formulier Niet ingevuld&quot; kunnen erg nuttig zijn, maar vereisen veel meer verwerkingskracht.
1. **Wees zachtaardig met plakken in meerdere waarden -** Multi-select is ontworpen voor het plakken in tientallen of mogelijk honderden waarden. Te veel inbrengen, en dat zal vertragen.
1. **Wees zachtaardig wanneer u beperkingen toevoegt -** Dit zijn de kleine details van een regel en gerelateerde waarden. Hoe meer beperkingen u toevoegt, hoe langzamer de verwerkingstijd.
1. **Vereenvoudig uw campagnes -** 100+ onafhankelijke regels (we hebben het gezien!) het is duidelijk dat het enige tijd zal duren voordat het proces is afgerond . Houd het eenvoudig en u zult de snelheidswinst merken - plus het zal voor u gemakkelijker zijn te begrijpen.
1. **@-symbool vóór domeinnaam opnemen wanneer het filter E-mailadres wordt gebruikt** **-** Hierdoor wordt er een snellere query gebruikt. Voorbeeld: in plaats van gebruiken _email bevat &#39;somedomain.com&#39;_, gebruik _E-mail bevat &#39;@somedomain.com_.&quot; Als u meerdere e-mailadressen gebruikt met &#39;contains&#39;, moeten ze allemaal beginnen met &#39;@.&#39;

>[!TIP]
>
>Marketo Engage kan op vele manieren worden gebruikt en bepaalde technieken zijn beter voor u en uw zaken. Neem contact op met je Adobe Professional Services-verkoper als je hulp nodig hebt om optimaal te investeren.
