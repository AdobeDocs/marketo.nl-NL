---
unique-page-id: 557316
description: Slimme lijstfilters definiëren - Marketo Docs - Productdocumentatie
title: Slimme lijstfilters definiëren
exl-id: ab08c5be-0afa-46d5-9f29-99e1f6b99dea
feature: Smart Lists
source-git-commit: 4bf27f7eb534ec76983a898d020f0b8c336a36dc
workflow-type: tm+mt
source-wordcount: '178'
ht-degree: 0%

---

# Slimme lijstfilters definiëren {#define-smart-list-filters}

>[!PREREQUISITES]
>
>* [ creeer een Slimme Lijst ](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md){target="_blank"}
>* [ vind en voeg Filters aan Slimme Lijsten toe ](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/find-and-add-filters-to-a-smart-list.md){target="_blank"}

Nu u [ een Slimme Lijst ](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md){target="_blank"} en [ toegevoegde filters ](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/find-and-add-filters-to-a-smart-list.md){target="_blank"} aan het hebt gecreeerd, bepalen de filters. Zo gaat het.

Als we ons voorbeeld voortzetten, definiëren we deze filters om alle mensen in Californië te vinden met een score van meer dan 50.

1. Ga naar **[!UICONTROL Marketing Activities]** .

   ![](assets/define-smart-list-filters-1.png)

1. Selecteer de gewenste slimme lijst en klik op de tab **[!UICONTROL Smart List]** .

   ![](assets/define-smart-list-filters-2.png)

1. Zoek en selecteer &#39;CA&#39; voor het filter **[!UICONTROL State]** .

   ![](assets/define-smart-list-filters-3.png)

   >[!NOTE]
   >
   >U kunt zowel &quot;Californië&quot;als &quot;CA opslaan.&quot; Om voor beide waarden te filtreren en _alle_ mensen van Californië te omvatten, leer hoe te [ veelvoudige waarden aan een Slimme filter van de Lijst ](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/add-multiple-values-to-a-smart-list-filter.md){target="_blank"} toevoegen.

1. Kies de operator **[!UICONTROL greater than]** en voer &quot;50&quot; in.

   ![](assets/define-smart-list-filters-4.png)

>[!TIP]
>
>Als u denkt dat uw database enkele records bevat die onvolledige e-mailadressen bevatten (bijvoorbeeld alleen &quot;@adobe.com&quot;), gebruikt u twee filters voor e-mailadressen wanneer u de operator &quot;contains&quot; gebruikt. Eén filter met &quot;bevat @adobe.com&quot; en een afzonderlijk filter met &quot;bevat adobe.com&quot; (het @-symbool wordt weggelaten).

Nu weet u hoe u een slimme lijst maakt en filters toevoegt/definieert.
