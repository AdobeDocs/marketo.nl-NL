---
unique-page-id: 1146901
description: Advanced Smart List Rule Logic - Marketo Docs - Productdocumentatie gebruiken
title: Advanced Smart List Rule Logic gebruiken
exl-id: fc41b6fd-c65e-4c44-b0ee-7bb5c77c51fb
feature: Smart Lists
source-git-commit: 8a5903fa5313e34f448f833f20ab8e3624cf23e6
workflow-type: tm+mt
source-wordcount: '280'
ht-degree: 0%

---

# Advanced Smart List Rule Logic gebruiken {#using-advanced-smart-list-rule-logic}

U kunt de nauwkeurige mensen vinden u door Slimme de regellogica van de Lijst op veelvoudige filters binnen een Slimme Lijst toe te passen wenst. Zo gaat het.

>[!PREREQUISITES]
>
>* [Filters zoeken en toevoegen aan een slimme lijst](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/find-and-add-filters-to-a-smart-list.md){target="_blank"}
>* [Slimme lijstfilters definiëren](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/define-smart-list-filters.md){target="_blank"}

>[!NOTE]
>
>De geavanceerde filterlogica is alleen beschikbaar als uw slimme lijst drie of meer filters bevat.

## Logica toevoegen aan een slimme lijst {#add-logic-to-a-smart-list}

Standaard vindt uw slimme lijst de overeenkomende personen **[!UICONTROL ALL]** filters (filters 1 _en_ 2 _en_ 3). U kunt de regellogica wijzigen en zoeken naar personen die overeenkomen **[!UICONTROL ANY]** van de gedefinieerde filters (filters 1 _of_ 2 _of_ 3), of gebruik geavanceerde filters (filters 1 _en_ 2 _of_ 3).

In dit voorbeeld wil je mensen zoeken in Californië _en_ met een score van ten minste 50 punten _of_ met de status &quot;Gekwalificeerde verkoop&quot;.

1. Selecteren **[!UICONTROL Use Advanced filters]** in de vervolgkeuzelijst.

   ![](assets/one.png)

   >[!NOTE]
   >
   >Gebruiken **[!UICONTROL Advanced]** de filters verminderen de behoefte om Slimme Lijsten met het Lid van Slimme filter van de Lijst tot stand te brengen. Hierdoor worden de prestaties geoptimaliseerd.

1. De **[!UICONTROL Advanced filters]** in het tekstvak wordt &#39;&#39;en&#39;&#39; weergegeven als de standaardwaarde tussen al uw filters.

   ![](assets/two-2.png)

1. Typ een paar haakjes rond &quot;2 en 3.&quot;

   ![](assets/three-2.png)

   >[!CAUTION]
   >
   >U moet &quot;en&quot;vóór &quot;of&quot;gebruiken wanneer het ingaan van regellogica.

1. Wijzig de &quot;and&quot; tussen &quot;2 en 3&quot; in &quot;of.&quot;

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
