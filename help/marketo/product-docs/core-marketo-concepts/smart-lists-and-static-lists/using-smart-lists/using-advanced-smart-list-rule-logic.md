---
unique-page-id: 1146901
description: Geavanceerde logica voor slimme-lijstregels gebruiken - Marketo Docs - Productdocumentatie
title: Advanced Smart List Rule Logic gebruiken
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '288'
ht-degree: 0%

---


# Advanced Smart List Rule Logic {#using-advanced-smart-list-rule-logic} gebruiken

U kunt precies de mensen vinden u door slimme lijstregellogica op veelvoudige filters binnen een slimme lijst toe te passen nodig hebt. Zo gaat het.

>[!PREREQUISITES]
>
>* [Filters zoeken en toevoegen aan een slimme lijst](../../../../product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/find-and-add-filters-to-a-smart-list.md)
>* [Slimme lijstfilters definiëren](../../../../product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/define-smart-list-filters.md)

>



>[!NOTE]
>
>De geavanceerde filterlogica is alleen beschikbaar als uw slimme lijst drie of meer filters bevat.

## Logica toevoegen aan een slimme lijst {#add-logic-to-a-smart-list}

Standaard vindt uw slimme lijst de personen die overeenkomen met **ALL** filters (filters 1 *en* 2 *en* 3). U kunt de regellogica veranderen om mensen te vinden die **ANY** van de bepaalde filters (filters 1 *of* 2 *of* 3) aanpassen, of geavanceerde filters (filters 1 *en* 2 *of *3) gebruiken.

In dit voorbeeld, zeggen wij u mensen in Californië *en* met een score van minstens 50 punten *of* met een status van &quot;Verkoop Gekwalificeerd.&quot;

1. Selecteer **Gebruik** **Geavanceerd** **filters** in de keuzelijst.

   ![](assets/one.png)

   >[!NOTE]
   >
   >Door het gebruik van **Geavanceerde** filters vermindert u de noodzaak om slimme lijsten te maken met het lid van het filter Slimme lijst. Hierdoor worden de prestaties geoptimaliseerd.

1. In het tekstvak **Geavanceerd** **filters** wordt &quot;en&quot; weergegeven als standaardwaarde tussen al uw filters.

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

## Geneste haakjes gebruiken voor vier of meer filters indien nodig {#use-nested-parentheses-for-four-or-more-filters-if-needed}

Afhankelijk van uw bedoeling, kunt u genestelde haakjes moeten toevoegen wanneer het gebruiken van vier of meer filters.

![](assets/advancedfilters-nested.png)

>[!TIP]
>
>Als u een ongeldige regel ingaat, zult u een rode lijn zien onder de regel wordt getoond. Schuif over de tekst om het bijbehorende foutbericht weer te geven.

