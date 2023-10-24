---
unique-page-id: 557316
description: Slimme lijstfilters definiëren - Marketo Docs - Productdocumentatie
title: Slimme lijstfilters definiëren
exl-id: ab08c5be-0afa-46d5-9f29-99e1f6b99dea
feature: Smart Lists
source-git-commit: 198d7d7fd4c1c312aeb30fa922fd89863ac87f81
workflow-type: tm+mt
source-wordcount: '173'
ht-degree: 0%

---

# Slimme lijstfilters definiëren {#define-smart-list-filters}

>[!PREREQUISITES]
>
>* [Een slimme lijst maken](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md){target="_blank"}
>* [Filters zoeken en toevoegen aan slimme lijsten](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/find-and-add-filters-to-a-smart-list.md){target="_blank"}

Nu hebt u [Een slimme lijst maken](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md){target="_blank"} and [added filters](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/find-and-add-filters-to-a-smart-list.md){target="_blank"} Laten we de filters definiëren. Zo gaat het.

Als we ons voorbeeld voortzetten, definiëren we deze filters om alle mensen in Californië te vinden met een score van meer dan 50.

1. Ga naar **[!UICONTROL Marketing Activities]**.

   ![](assets/login-marketing-activities-1.png)

1. Selecteer de slimme lijst en klik op de knop **[!UICONTROL Smart List]** tab.

   ![](assets/smarlist-choosefilters.png)

1. Zoek en selecteer &quot;CA&quot; voor de **[!UICONTROL State]** filter.

   ![](assets/smartlistdefinefilters.png)

   >[!NOTE]
   >
   >U kunt zowel &quot;Californië&quot;als &quot;CA opslaan.&quot; Als u voor beide waarden wilt filteren, neemt u _alles_ mensen uit Californië leren hoe te  [meerdere waarden toevoegen aan een filter Slimme lijst](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/add-multiple-values-to-a-smart-list-filter.md){target="_blank"}.

1. Kies de optie **[!UICONTROL greater than]** -operator en &quot;50&quot; invullen.

   ![](assets/smartlistfilter-personscore.png)

>[!TIP]
>
>Als u denkt dat uw database enkele records bevat die onvolledige e-mailadressen bevatten (bijvoorbeeld alleen &quot;@adobe.com&quot;), gebruikt u twee filters voor e-mailadressen wanneer u de operator &quot;contains&quot; gebruikt. Eén filter met &quot;bevat @adobe.com&quot; en een afzonderlijk filter met &quot;bevat adobe.com&quot; (het @-symbool wordt weggelaten).

U weet nu hoe u een slimme lijst maakt en filters toevoegt/definieert.
