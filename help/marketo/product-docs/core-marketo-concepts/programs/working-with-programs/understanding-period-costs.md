---
unique-page-id: 7504676
description: Begrijpingsperiode kosten - Marketo-documenten - productdocumentatie
title: Kosten voor tijdrekening
exl-id: 99f50eaf-28cf-4a8b-8ebd-89a4beef986a
feature: Programs
source-git-commit: 9e51ece12742152040dbbcb6a1584fba28e863ff
workflow-type: tm+mt
source-wordcount: '269'
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
>Als je $200 per maand besteedt aan [!DNL Google Adwords] - de [!DNL Google Adwords] programma zou een periode kosten van $200 hebben _elke maand_.

>[!NOTE]
>
>[Programma&#39;s begrijpen](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-programs.md)
>
>[Werken met het lidmaatschap van het programma](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-program-membership.md)

## Hoe de kosten van de periode worden berekend {#how-period-costs-are-calculated}

Stel je een gebeurtenis voor, zoals een webinar, die in maart plaatsvindt. Nieuwe mensen worden van tevoren aangeschaft uit reclame in januari en februari. Nieuwe contacten worden ook verworven na de gebeurtenis, wanneer de mensen webinar in de maanden April en Mei downloaden.

1. Met een aan maart toegerekende kostprijs voor één periode...

   ![](assets/graph1.png)

   ...contactpersonen toegevoegd in de maanden ervoor en erna *alleen* tel naar maart.

   ![](assets/graph2.png)

1. Met aan januari, februari en maart toegerekende tijdskosten...

   ![](assets/graph3.png)

   ...contacten die pas in de maanden na maart zijn toegevoegd, zullen tot maart worden gerekend.

   ![](assets/graph4.png)

1. Met aan januari en april toegerekende tijdskosten...

   ![](assets/graph5.png)

   ...contacten die in de maanden januari tot en met maart zijn toegevoegd, zullen naar januari tellen. Contacten die in de maanden april en mei zijn toegevoegd, zullen tot april tellen.

   ![](assets/graph6.png)

   >[!NOTE]
   >
   >Samengevat: maanden zonder bepaalde periode zullen de kosten teruglopen tot de laatste die is gedefinieerd. Als er geen kosten voor de voorgaande periode zijn, worden de maanden &quot;voorwaarts&quot; doorgestuurd naar de volgende periode die is gedefinieerd. Indien geen periode is vastgesteld _alle_ maanden, zal de rapportering in RCE niet beschikbaar voor het programma zijn.

   >[!MORELIKETHIS]
   >
   >* [Periode-kosten in een programma gebruiken](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/using-period-costs-in-a-program.md)
   >* [Een programmarapport filteren op kosten van periode](/help/marketo/product-docs/core-marketo-concepts/programs/program-performance-report/filter-a-program-report-by-period-cost.md)
