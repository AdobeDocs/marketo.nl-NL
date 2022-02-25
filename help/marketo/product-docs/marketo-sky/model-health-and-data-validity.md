---
description: Modelgezondheid en gegevensgeldigheid - Marketo Docs - Productdocumentatie
title: Modelgezondheid en gegevensgeldigheid
hide: true
hidefromtoc: true
source-git-commit: ab20d9683aa5987778970fd32793dc0f3056c84b
workflow-type: tm+mt
source-wordcount: '192'
ht-degree: 0%

---

# Modelgezondheid en gegevensgeldigheid {#model-health-and-data-validity}

De prestaties van uw modellen zijn afhankelijk van de kwaliteit en volledigheid van de invoergegevens. Zie de bovenste bepalende factor voor elk van uw waarschijnlijke AI-modellen. Zie ook de belangrijkste factoren die resulteren in een hogere/lagere registratie van gebeurtenissen, deelname aan gebeurtenissen of het opzeggen van abonnementen.

>[!NOTE]
>
>Gedragingen die zijn gemarkeerd met (+) hebben een positieve invloed op voorspellingen (en andersom).

Hier is hoe je je modelgezondheid kunt beoordelen.

Ga naar de **[!UICONTROL Models and Data Health]** deel onder **[!UICONTROL Predictive Audiences]** in de **[!UICONTROL Admin]** gebied Marketo Classic. Hier zie je al je modellen en hun status.

![Afbeelding één](assets/model-health-and-data-validity-1.png)

* **Trainingsstatus**: Geeft aan of uw model actief training volgt (voorspellingen verbeteren). De training wordt automatisch elke twee weken gegeven. Alle modellen die _Verwerking_ kan tot 24 uur duren om af te maken. Voor alle _Mislukt_ modellen, neem contact op met [Marketo-ondersteuning](https://nation.marketo.com/t5/Support/ct-p/Support).
* **Scorestatus**: Geeft aan of uw model voorspellingen (waarschijnlijkheidspercentages) voor programmaleden actief berekent.
* **Prestaties**: Indeling van de modelgezondheid op basis van de volledigheid van de gegevens en de gegevenskwaliteit (zie hieronder).
* **Volledigheid van gegevens**: Percentage gegevenskenmerken dat aanwezig/voltooid is.
* **Gegevenskwaliteit**: Percentage kenmerken dat goede, bruikbare gegevens bevat.