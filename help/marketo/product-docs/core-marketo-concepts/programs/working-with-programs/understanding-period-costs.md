---
unique-page-id: 7504676
description: Begrijpen van de kosten van de periode - Marketo Docs - de Documentatie van het Product
title: Kosten voor tijdrekening
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '278'
ht-degree: 0%

---


# Kosten voor tijdrekening {#understanding-period-costs}

## Overzicht {#overview}

Periode-kosten hebben betrekking op het geld dat u in een bepaalde maand aan een programma besteedt.

>[!NOTE]
>
>**Voorbeeld**
>
>Als je $1000 besteedt aan het huren van een illustrator voor een eBook dat in juli wordt gestart - dan kost het eBook-programma in juli $1000.
>
>Als je 200 dollar per maand aan Google Adwords besteedt, kost het Google Adwords-programma **elke maand**$200.

>[!NOTE]
>
>**Diep duiken**
>
>[Programma&#39;s begrijpen](../../../../product-docs/core-marketo-concepts/programs/creating-programs/understanding-programs.md)
>
>[Werken met het lidmaatschap van het programma](../../../../product-docs/core-marketo-concepts/programs/creating-programs/understanding-program-membership.md)

## Hoe de kosten van de periode worden berekend {#how-period-costs-are-calculated}

Stel je een gebeurtenis voor, zoals een webinar, die in maart plaatsvindt. Nieuwe mensen worden van tevoren aangeschaft uit reclame in januari en februari. Nieuwe contacten worden ook verworven na de gebeurtenis, wanneer de mensen webinar in de maanden April en Mei downloaden.

1. Met een aan maart toegerekende kostprijs voor één periode...

   ![](assets/graph1.png)

   ...contacten die in de maanden daarvoor en daarna zijn toegevoegd, zullen *slechts* tot maart tellen.

   ![](assets/graph2.png)

1. Met aan januari, februari en maart toegerekende tijdskosten...

   ![](assets/graph3.png)

   ...contacten die pas in de maanden na maart zijn toegevoegd, zullen tot maart worden gerekend.

   ![](assets/graph4.png)

1. Met aan januari en april toegerekende tijdskosten...

   ![](assets/graph5.png)

   ...de contacten die in de maanden januari tot en met maart worden toegevoegd, zullen naar januari tellen. Contacten die in de maanden april en mei zijn toegevoegd, zullen tot april tellen.

   ![](assets/graph6.png)

   >[!NOTE]
   >
   >**Herinnering**
   >
   >
   >Samengevat: maanden zonder bepaalde periode zullen de kosten teruglopen tot de laatste die is gedefinieerd. Als er geen kosten voor de voorgaande periode zijn, worden de maanden &quot;voorwaarts&quot; doorgestuurd naar de volgende periode die is gedefinieerd. Als de kosten voor een periode voor *geen* maanden zijn vastgesteld, is de rapportage in RCE niet beschikbaar voor het programma.

   >[!NOTE]
   >
   >**Verwante artikelen**
   >
   >    
   >    
   >    * [Periode-kosten in een programma gebruiken](using-period-costs-in-a-program.md)
   >    * [Een programmarapport filteren op kosten van periode](../../../../product-docs/core-marketo-concepts/programs/program-performance-report/filter-a-program-report-by-period-cost.md)


