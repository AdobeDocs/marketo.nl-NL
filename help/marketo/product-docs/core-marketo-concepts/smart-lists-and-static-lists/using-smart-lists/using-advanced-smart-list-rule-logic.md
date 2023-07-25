---
unique-page-id: 1146901
description: Advanced Smart List Rule Logic - Marketo Docs - Productdocumentatie gebruiken
title: Advanced Smart List Rule Logic gebruiken
exl-id: fc41b6fd-c65e-4c44-b0ee-7bb5c77c51fb
feature: Smart Lists
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '288'
ht-degree: 0%

---

# Advanced Smart List Rule Logic gebruiken {#using-advanced-smart-list-rule-logic}

U kunt precies de mensen vinden u door slimme lijstregellogica op veelvoudige filters binnen een slimme lijst toe te passen nodig hebt. Zo gaat het.

>[!PREREQUISITES]
>
>* [Filters zoeken en toevoegen aan een slimme lijst](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/find-and-add-filters-to-a-smart-list.md)
>* [Slimme lijstfilters definiëren](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/define-smart-list-filters.md)

>[!NOTE]
>
>De geavanceerde filterlogica is alleen beschikbaar als uw slimme lijst drie of meer filters bevat.

## Logica toevoegen aan een slimme lijst {#add-logic-to-a-smart-list}

Standaard worden in uw slimme lijst de overeenkomende personen gevonden **ALLES** filters (filters 1 _en_ 2 _en_ 3). U kunt de regellogica wijzigen en zoeken naar personen die overeenkomen **ALLE** van de gedefinieerde filters (filters 1 _of_ 2 _of_ 3), of gebruik geavanceerde filters (filters 1 _en_ 2 _of_ 3).

In dit voorbeeld, zeggen u wilt mensen in Californië vinden _en_ met een score van ten minste 50 punten _of_ met de status &quot;Gekwalificeerde verkoop&quot;.

1. Selecteren **Geavanceerde filters gebruiken** in de vervolgkeuzelijst.

   ![](assets/one.png)

   >[!NOTE]
   >
   >Gebruiken **Geavanceerd** filters verminderen de behoefte om slimme lijsten met het Lid van Slimme filter van de Lijst tot stand te brengen. Hierdoor worden de prestaties geoptimaliseerd.

1. De **Geavanceerde filters** in het tekstvak wordt &#39;&#39;en&#39;&#39; weergegeven als de standaardwaarde tussen al uw filters.

   ![](assets/two-2.png)

1. Typ een paar haakjes rond &quot;2 en 3.&quot;

   ![](assets/three-2.png)

   >[!CAUTION]
   >
   >U moet &quot;en&quot;vóór &quot;of&quot;gebruiken wanneer het ingaan van regellogica.

1. Wijzig de &#39;&#39;and&#39;&#39; tussen &#39;&#39;2 en &#39;&#39;3&#39;&#39; in &#39;&#39;of&#39;&#39;.

   ![](assets/four-1.png)

## Haakjes gebruiken bij het mengen van &quot;en&quot; en &quot;of {#use-parentheses-when-mixing-and-and-or}

Voor het mixen van logica &#39;and&#39; en &#39;of&#39; moeten ronde haakjes worden gebruikt om uw intentie duidelijk te maken.

![](assets/advancedfilters-parent.png)

## Geneste ronde haakjes gebruiken voor vier of meer filters, indien nodig {#use-nested-parentheses-for-four-or-more-filters-if-needed}

Afhankelijk van uw bedoeling, kunt u genestelde haakjes moeten toevoegen wanneer het gebruiken van vier of meer filters.

![](assets/advancedfilters-nested.png)

>[!TIP]
>
>Als u een ongeldige regel ingaat, zult u een rode lijn zien onder de regel wordt getoond. Schuif over de tekst om het bijbehorende foutbericht weer te geven.
