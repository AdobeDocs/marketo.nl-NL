---
unique-page-id: 557322
description: Eén stroomstap uitvoeren vanuit een slimme lijst - Marketo Docs - Productdocumentatie
title: Eén stroomstap uitvoeren vanuit een slimme lijst
exl-id: 1ac5795b-1906-4f94-bd0a-570d55c9357b
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '234'
ht-degree: 0%

---

# Eén stroomstap uitvoeren vanuit een slimme lijst {#run-a-single-flow-step-from-a-smart-list}

Als u een stap wilt uitvoeren die slechts eenmalig is, kunt u één stap voor de stroom in een slimme lijst gebruiken in plaats van een hele slimme campagne te maken.

>[!PREREQUISITES]
>
>[Een slimme lijst maken](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md)

1. Ga naar **Marketingactiviteiten**.

   ![](assets/login-marketing-activities-1.png)

1. Selecteer een lijst of een slimme lijst met personen in de lijst en ga vervolgens naar de **Mensen** tab.

   ![](assets/smartlistpeopletab-hands.png)

   >[!TIP]
   >
   >Zowel statische lijsten als slimme lijsten hebben deze functionaliteit.

1. Klikken **Alles selecteren**. U kunt ook **Ctrl/Cmd** en klik om een aantal records handmatig te selecteren.

   ![](assets/smartlist-selectallhand.png)

   >[!NOTE]
   >
   >Als de resultaten over meerdere pagina&#39;s worden verdeeld, klikt u op **Alles selecteren** Alle personen op alle pagina&#39;s selecteren.

1. Onder **Persoon** **Handelingen** selecteert u de gewenste stap voor de stroom. In dit voorbeeld gebruiken we [Gegevenswaarde wijzigen](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/change-data-value.md).

   ![](assets/personactions-hands.png)

1. Zoeken en selecteer een **Kenmerk**. In dit voorbeeld nemen we alle mensen met de status &#39;Californië&#39; en veranderen deze in &#39;CA&#39;.

   ![](assets/runaction-hands.png)

1. Voer een nieuwe waarde in. Klikken **Nu uitvoeren**.

   ![](assets/runactionnewvalue-hands.png)

1. Als u gegevenswaarden voor een groot aantal mensen verandert, kunt u de verandering moeten bevestigen door het aantal te typen. Klikken **Ga er naartoe**.

   ![](assets/changedatavalue.jpg)

Geweldig werk! U ziet de status van de enkele stap in de rechterbovenhoek.

![](assets/completesingleflowaction.jpg)

Wanneer het is gebeëindigd, vernieuw de lijst en u zult de bijgewerkte info zien.
