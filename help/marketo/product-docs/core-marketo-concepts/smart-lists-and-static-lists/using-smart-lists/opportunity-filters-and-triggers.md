---
unique-page-id: 8159286
description: Opportuniteitsfilters en -triggers - Marketo Docs - Productdocumentatie
title: Opportuniteitsfilters en -triggers
exl-id: 5b372c00-1553-4ac3-a495-53e208371d8d
feature: Smart Lists
source-git-commit: 8a5903fa5313e34f448f833f20ab8e3624cf23e6
workflow-type: tm+mt
source-wordcount: '471'
ht-degree: 0%

---

# Opportuniteitsfilters en -triggers {#opportunity-filters-and-triggers}

Met opportuniteitsfilters en -triggers kunt u opportuniteitsgebeurtenissen bijhouden vanuit Salesforce. Ze zijn iets anders dan andere filters en triggers.

## Opportuniteitsfilters {#opportunity-filters}

Met opportuniteitsfilters kunt u bogen in uw Salesforce-leads die mogelijkheden hebben. U kunt deze vinden in de map Opportunity van het palet wanneer u een slimme lijst bewerkt. Ze komen in een paar kleven.

* Aantal opties
* Totaal aantal opty&#39;s
* Totaal verwachte opty-inkomsten
* Heeft mogelijkheid
* Opportunity toegevoegd
* Opportunity is verwijderd
* Opportunity is bijgewerkt

Als u uw gebieden van de Kans (douane of norm) zoekt, gebruik **Heeft mogelijkheid** filter of **Opportunity was`[Added/Removed/Updated]`** filters of triggers.

**Aantal opties, Totaal bedrag van de Optie, Totaal van de Opty Verwachte Inkomsten**

Met deze filters, kunt u lood vinden die op het totale aantal, het bedrag, of de verwachte opbrengst van al hun kansen wordt gebaseerd.

![](assets/image2015-6-11-12-3a29-3a34.png)

**Heeft opportuniteit, is toegevoegd aan opportunity, is verwijderd uit opportunity**

Als u naar leads zoekt die mogelijkheden hebben gebaseerd op een combinatie van criteria, gebruikt u de opdracht **Heeft mogelijkheid**, **Is toegevoegd aan opportunity**, of **Is verwijderd uit opportunity** filter. Ze vertellen je:

* **Heeft mogelijkheid**: Als deze lead momenteel een overeenkomende mogelijkheid heeft
* **Is toegevoegd aan opportunity**: Als deze lead ooit aan een matching Opportunity is toegevoegd
* **Is verwijderd uit opportunity**: Als deze lead ooit uit een matching opportunity is verwijderd

De zoekcriteria toevoegen als **Restricties** op het filter. Tot de beperkingen behoren uw opportuniteitsnorm en aangepaste velden:

![](assets/image2015-6-11-12-3a31-3a0.png)

![](assets/image2015-6-11-12-3a31-3a46.png)

Stel bijvoorbeeld dat je naar leads wilt zoeken die open kansen hebben van minstens $5.000. Sleep in het dialoogvenster **Heeft mogelijkheid** filter en gebruik de **Is gesloten** en **Hoeveelheid** beperkingen:

![](assets/image2015-6-11-12-3a32-3a0.png)

>[!NOTE]
>
>Wanneer u meerdere Opportunity-filters gebruikt, krijgt u mogelijk onjuiste antwoorden. Als u het voorbeeld hierboven met twee filters van de Mogelijkheid bouwde, zou u een lijst van lood krijgen die om het even welke kans hebben die minstens $5.000 en om het even welke kans is die wordt gesloten, zelfs als die afzonderlijke kansen zijn.

**Opportunity is bijgewerkt**

De **Opportunity is bijgewerkt** filter zoekt naar om het even welke kans wanneer een specifiek opportuniteitsgebied werd bijgewerkt. Kies het veld dat u wilt controleren met de keuzelijst Trigger-kenmerk en gebruik vervolgens de beperkingen om de set wijzigingen te beperken.

Met dit filter ziet u bijvoorbeeld alle leads die de laatste 30 dagen een wijziging van de einddatum hebben ondergaan:

![](assets/image2015-6-11-12-3a33-3a7.png)

## Opportunity-triggers {#opportunity-triggers}

De volgende opportuniteitstranches zijn beschikbaar. Ze werken net zoals hun corresponderende filters (eerder beschreven), maar ze kunnen campagnes juist activeren wanneer de gebeurtenis plaatsvindt:

* Opportunity is bijgewerkt
* Toegevoegd aan opportunity
* Verwijderd uit opportunity

U kunt deze slimme lijst bijvoorbeeld gebruiken om te activeren wanneer een lead aan een opportuniteit wordt toegevoegd. In de stroom, zou u hen aan de Vergeschorte lijst van de Marketing kunnen toevoegen of hen een gerichte e-mail verzenden.

![](assets/image2015-6-11-12-3a33-3a48.png)

Als u aangepaste opportuniteitsvelden wilt uitschakelen, gebruikt u de optie **Opportunity is bijgewerkt** activeer en kies het veld in de keuzelijst:

![](assets/image2015-6-11-12-3a33-3a34.png)
