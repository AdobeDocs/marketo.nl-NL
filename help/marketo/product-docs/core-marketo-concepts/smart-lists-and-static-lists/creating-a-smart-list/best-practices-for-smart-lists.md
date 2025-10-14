---
unique-page-id: 7512524
description: Aanbevolen procedures voor slimme lijsten - Marketo Docs - Productdocumentatie
title: Beste praktijken voor Slimme Lijsten
exl-id: 466de198-1012-4ac3-906c-d41943fe5bc0
feature: Smart Lists
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '566'
ht-degree: 0%

---

# Beste praktijken voor Slimme Lijsten {#best-practices-for-smart-lists}

Slimme lijsten zijn het krachtigste zoekprogramma in het marketinguniversum. Ze vinden de mensen die je zoekt met magische snelheid en gemak.

Om hen gemakkelijk te maken om met en prestaties te werken te optimaliseren, hebben wij een lijst van beste praktijken gecreeerd. Veel plezier!

>[!NOTE]
>
>**Elke gebruiker van Marketo Engage is verschillend.** Hoe groter de database, hoe meer verwerking er plaatsvindt. Hoe meer activiteiten u hebt opgeslagen, hoe langer het duurt om er doorheen te zoeken.
>
>Probeer de onderstaande tips als u te maken hebt met een trage procedure. Als de kwestie voortduurt, contacteer [&#x200B; de Steun van Marketo &#x200B;](https://nation.marketo.com/t5/Support/ct-p/Support){target="_blank"}.

1. **geschiedenis van de Beperking -** de filters van de Geschiedenis (a.k.a. de filters van de Activiteit) zijn onder de meest middel intensieve, tijdrovende verrichtingen. Als u ze moet gebruiken, probeert u het datumbereik zo kort mogelijk te houden. Hierdoor wordt de set doorzoekbare gegevens kleiner. Bovendien hebben datumbereiken geen voorrang op retentieperioden. Voorbeeld: Als de activiteit u vraagt een bewaartermijn van 90 dagen heeft en u &quot;afgelopen 100 dagen&quot;kiest, slechts zullen de resultaten van de afgelopen 90 dagen worden teruggegeven. De periodes van het behoud van de activiteit [&#x200B; kunnen hier &#x200B;](https://nation.marketo.com/t5/knowledgebase/marketo-activities-data-retention-policy/ta-p/251480){target="_blank"} worden gevonden.
1. **grens genestelde Slimme Lijsten -** wanneer het creëren van een nieuwe Slimme Lijst, grens de hoeveelheid &quot;Lid van Slimme gebruikte filters van de Lijst&quot;. Dit wordt genoemd het nesten Slimme Lijsten, en elke Slimme Lijst waarnaar wordt verwezen zal verwerkingstijd verhogen. In plaats daarvan, of verwijzing statische lijsten of gebruik [&#x200B; segmentatie &#x200B;](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/create-a-segmentation.md){target="_blank"}.
1. **Gebruik positief over negatieve exploitanten -** terwijl de &quot;niet&quot;filters beschikbaar zijn, moeten zij de volledige gegevensreeks in uw instantie zoeken, die uiterst tijdrovend kan zijn. Positieve &#39;is&#39;-filters kunnen effectievere zoekalgoritmen gebruiken.
1. **vermijd &quot;bevat&quot; -** als u slechts gedeeltelijke gegevens hebt, &quot;begint met&quot;bepalende eigenschappen zal veel snellere resultaten opleveren dan &quot;bevat.&quot; &quot;Is&quot; wordt nog sneller uitgevoerd. Vermijd het gebruik van &quot;contains&quot; met meerdere waarden. De twee tezamen kunnen een campagne nog verder vertragen.
1. **Willekeurige Steekproef van het gebruik door zich -** Willekeurige Steekproef is een speciale filter. Gebruik het op zich om uw mensen in pre-made lijsten te zetten. Dan gebruik enkel &quot;Lid van Lijst&quot;om uw Slimme Lijst super snel te maken. De willekeurige Steekproef zal **&#x200B;**&#x200B;niet met genestelde Slimme Lijsten werken. Het filter Willekeurige sample werkt niet als er naar de slimme lijst wordt verwezen voor het filter &quot;Lid van slimme lijst&quot;.
1. **ben zacht met inactiviteitsfilters -** de Filters als &quot;niet Gevulde Vorm&quot;kunnen echt nuttig zijn, maar vereisen veel meer verwerkingscapaciteit.
1. **ben zacht met het kleven in veelvoudige waarden -** multi-uitgezocht wordt ontworpen voor het kleven in tientallen of misschien honderden waarden. Te veel inbrengen, en dat zal vertragen.
1. **ben zacht wanneer het toevoegen van beperkingen -** dit zijn de zeer kleine details van een regel en verwante waarden. Hoe meer beperkingen u toevoegt, hoe langzamer de verwerkingstijd.
1. **vereenvoudig uw campagnes -** 100+ onafhankelijke regels (wij hebben het gezien!) zullen duidelijk wat tijd aan proces vergen. Houd het eenvoudig en u zult de snelheidswinst merken - plus het zal voor u gemakkelijker zijn te begrijpen.
1. **omvat het @ symbool vóór de domeinnaam wanneer het gebruiken van de filter van het E-mailAdres** **-** dit maakt het een snellere vraag gebruiken. Voorbeeld: In plaats van het gebruiken van _e-mail bevat &quot;somedomain.com&quot;_, gebruik _e-mail bevat &quot;@somedomain.com_&quot;. Als u meerdere e-mailadressen gebruikt met &#39;contains&#39;, moeten ze allemaal beginnen met &#39;@.&#39;

>[!TIP]
>
>Marketo Engage kan op vele manieren worden gebruikt en bepaalde technieken zijn beter voor u en uw bedrijf. Neem contact op met je Adobe Professional Services-verkoper als je hulp nodig hebt om optimaal te investeren.
