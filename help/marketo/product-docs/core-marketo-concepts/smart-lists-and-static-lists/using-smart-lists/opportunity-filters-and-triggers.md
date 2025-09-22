---
unique-page-id: 8159286
description: Opportuniteitsfilters en -triggers - Marketo Docs - Productdocumentatie
title: Opportuniteitsfilters en -triggers
exl-id: 5b372c00-1553-4ac3-a495-53e208371d8d
feature: Smart Lists
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '473'
ht-degree: 0%

---

# Opportuniteitsfilters en -triggers {#opportunity-filters-and-triggers}

Met opportuniteitsfilters en -triggers kunt u opportuniteitsgebeurtenissen bijhouden vanuit [!DNL Salesforce] . Ze zijn iets anders dan andere filters en triggers.

## Opportuniteitsfilters {#opportunity-filters}

Met opportuniteitsfilters kun je naar Salesforce-leads gaan die mogelijkheden hebben. U kunt deze vinden in de map Opportunity van het palet wanneer u een slimme lijst bewerkt. Ze komen in een paar kleven.

* Aantal opties
* Totaal aantal opty&#39;s
* Totaal verwachte opty-inkomsten
* Heeft mogelijkheid
* Opportunity toegevoegd
* Opportunity is verwijderd
* Opportunity is bijgewerkt

Als u uw gebieden van de Kans (douane of norm) zoekt, gebruik **heeft de filter van de Kans** of **Kans`[Added/Removed/Updated]`** filters of trekkers was.

**Aantal Optys, Totale Bedrag van de Optie, Totale Verwachte Opty Inkomsten**

Met deze filters, kunt u lood vinden die op het totale aantal, het bedrag, of de verwachte opbrengst van al hun kansen wordt gebaseerd.

![](assets/opportunity-filters-and-triggers-1.png)

**heeft Kans, werd toegevoegd aan Kans, werd verwijderd uit Kans**

Als u naar lood zoekt die kansen hebben die op een combinatie van criteria worden gebaseerd, gebruik **heeft Kans**, **werd toegevoegd aan Kans**, of **werd verwijderd uit Kans** filter. Ze vertellen je:

* **heeft Kans**: Als dit lood momenteel om het even welke passende kans heeft
* **werd toegevoegd aan Kans**: Als dit lood ooit aan een passende kans werd toegevoegd
* **werd Verwijderd uit Kans**: Als dit lood ooit werd verwijderd uit een passende kans

Voeg de onderzoekscriteria als **Beperkingen** op de filter toe. Tot de beperkingen behoren uw opportuniteitsnorm en aangepaste velden:

![](assets/opportunity-filters-and-triggers-2.png)

![](assets/opportunity-filters-and-triggers-3.png)

Stel bijvoorbeeld dat je naar leads wilt zoeken die open kansen hebben van minstens $5.000. De belemmering in **heeft het filter van de Kans** en gebruikt **wordt gesloten** en **beperkingen van het Bedrag**:

![](assets/opportunity-filters-and-triggers-4.png)

>[!NOTE]
>
>Wanneer u meerdere Opportunity-filters gebruikt, krijgt u mogelijk onjuiste antwoorden. Als u het voorbeeld hierboven met twee filters van de Mogelijkheid bouwde, zou u een lijst van lood krijgen die om het even welke kans hebben die minstens $5.000 en om het even welke kans is die wordt gesloten, zelfs als die afzonderlijke kansen zijn.

**Opportunity werd bijgewerkt**

De **Kans werd Bijgewerkte** filter zoekt om het even welke kans toen een specifiek opportuniteitsgebied werd bijgewerkt. Kies het veld dat u wilt controleren met de keuzelijst Trigger-kenmerk en gebruik vervolgens de beperkingen om de set wijzigingen te beperken.

Met dit filter ziet u bijvoorbeeld alle leads die de laatste 30 dagen een wijziging van de einddatum hebben ondergaan:

![](assets/opportunity-filters-and-triggers-5.png)

## Opportunity-triggers {#opportunity-triggers}

De volgende opportuniteitstranches zijn beschikbaar. Ze werken net zoals hun corresponderende filters (eerder beschreven), maar ze kunnen campagnes juist activeren wanneer de gebeurtenis plaatsvindt:

* Opportunity is bijgewerkt
* Toegevoegd aan opportunity
* Verwijderd uit opportunity

U kunt deze slimme lijst bijvoorbeeld gebruiken om te activeren wanneer een lead aan een opportuniteit wordt toegevoegd. In de stroom, zou u hen aan de Vergeschorte lijst van de Marketing kunnen toevoegen of hen een gerichte e-mail verzenden.

![](assets/opportunity-filters-and-triggers-6.png)

Om van uw gebieden van de opportuniteitdouane teweeg te brengen, gebruik de **Kans wordt Bijgewerkte** trekker en kies het gebied in pulldown:

![](assets/opportunity-filters-and-triggers-7.png)
