---
unique-page-id: 1146901
description: Advanced Smart List Rule Logic - Marketo Docs - Productdocumentatie gebruiken
title: Advanced Smart List Rule Logic gebruiken
exl-id: fc41b6fd-c65e-4c44-b0ee-7bb5c77c51fb
feature: Smart Lists
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '294'
ht-degree: 0%

---

# Advanced Smart List Rule Logic gebruiken {#using-advanced-smart-list-rule-logic}

U kunt de nauwkeurige mensen vinden u door Slimme de regellogica van de Lijst op veelvoudige filters binnen een Slimme Lijst toe te passen wenst. Zo gaat het.

>[!PREREQUISITES]
>
>* [&#x200B; vind en voeg Filters aan een Slimme Lijst &#x200B;](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/find-and-add-filters-to-a-smart-list.md){target="_blank"} toe
>* [&#x200B; bepaalt Slimme Filters van de Lijst &#x200B;](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/define-smart-list-filters.md){target="_blank"}

>[!NOTE]
>
>De geavanceerde filterlogica is alleen beschikbaar als uw slimme lijst drie of meer filters bevat.

## Logica toevoegen aan een slimme lijst {#add-logic-to-a-smart-list}

Door gebrek, zal uw Slimme Lijst de mensen vinden die **[!UICONTROL ALL]** filters (filters 1 _en_ 2 _en_ 3) aanpassen. U kunt de regellogica veranderen om mensen te vinden die **[!UICONTROL ANY]** van de bepaalde filters (filters 1 _of_ 2 _of_ 3) aanpassen, of geavanceerde filters (filters 1 _en_ 2 _of_ 3) gebruiken.

In dit voorbeeld, zeggen wij u mensen in Californië _en_ met een score van minstens 50 punten _of_ met een status van &quot;Verkoop Gekwalificeerd.&quot;

1. Selecteer **[!UICONTROL Use Advanced filters]** in de vervolgkeuzelijst.

   ![](assets/using-advanced-smart-list-rule-logic-1.png)

   >[!NOTE]
   >
   >Het gebruik van **[!UICONTROL Advanced]** -filters vermindert de noodzaak om slimme lijsten te maken met het lid van het filter Slimme lijst. Hierdoor worden de prestaties geoptimaliseerd.

1. In het tekstvak **[!UICONTROL Advanced filters]** wordt &quot;en&quot; weergegeven als de standaardwaarde tussen al uw filters.

   ![](assets/using-advanced-smart-list-rule-logic-2.png)

1. Typ een paar haakjes rond &quot;2 en 3.&quot;

   ![](assets/using-advanced-smart-list-rule-logic-3.png)

   >[!CAUTION]
   >
   >U moet &quot;en&quot;vóór &quot;of&quot;gebruiken wanneer het ingaan van regellogica.

1. Wijzig de &quot;and&quot; tussen &quot;2 en 3&quot; in &quot;of.&quot;

   ![](assets/using-advanced-smart-list-rule-logic-4.png)

## Haakjes gebruiken bij het mengen van &quot;en&quot; en &quot;of {#use-parentheses-when-mixing-and-and-or}

Voor het mixen van logica &#39;and&#39; en &#39;of&#39; moeten ronde haakjes worden gebruikt om uw intentie duidelijk te maken.

![](assets/using-advanced-smart-list-rule-logic-5.png)

## Geneste ronde haakjes gebruiken voor vier of meer filters, indien nodig {#use-nested-parentheses-for-four-or-more-filters-if-needed}

Afhankelijk van uw bedoeling, kunt u genestelde haakjes moeten toevoegen wanneer het gebruiken van vier of meer filters.

![](assets/using-advanced-smart-list-rule-logic-6.png)

>[!TIP]
>
>Als u een ongeldige regel ingaat, zult u een rode lijn zien onder de regel wordt getoond. Schuif over de tekst om het bijbehorende foutbericht weer te geven.
