---
unique-page-id: 2949413
description: Een restrictie toevoegen aan een slim lijstfilter - Marketo Docs - Productdocumentatie
title: Een restrictie toevoegen aan een slim lijstfilter
exl-id: 5345019c-55e7-4afd-b583-90f1a687a71c
feature: Smart Lists
source-git-commit: ac7d6b222ca561c88e0bf10aba7736c1b2eee3f7
workflow-type: tm+mt
source-wordcount: '162'
ht-degree: 0%

---

# Een restrictie toevoegen aan een slim lijstfilter {#add-a-constraint-to-a-smart-list-filter}

Bij het maken van een slimme lijst hebben sommige filters geavanceerde opties die &#39;beperkingen&#39; worden genoemd. Dit zijn extra voorwaarden die u kunt toevoegen aan filters en triggers om uw zoekopdracht nog verder te beperken.

In dit voorbeeld, voegen sommige beperkingen aan a **[Gewijzigde Waarde van Gegevens](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/change-data-value.md){target="_blank"}** filter toe om mensen te vinden die een verandering van de Status van MQL in SQL hadden.

>[!PREREQUISITES]
>
>* [ creeer een Slimme Lijst ](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md){target="_blank"}
>* [ gebruik de &quot;Gewijzigde&quot;Filter van de Waarde van Gegevens in een Slimme Lijst ](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/use-the-data-value-changed-filter-in-a-smart-list.md){target="_blank"}

1. Ga naar **[!UICONTROL Marketing Activities]** .

   ![](assets/add-a-constraint-to-a-smart-list-filter-1.png)

1. Selecteer de slimme lijst met een filter waaraan u een beperking wilt toevoegen en klik op de tab **[!UICONTROL Smart List]** .

   ![](assets/add-a-constraint-to-a-smart-list-filter-2.png)

1. Selecteer onder **[!UICONTROL Add Constraint]** de optie **[!UICONTROL Previous Value]** .

   ![](assets/add-a-constraint-to-a-smart-list-filter-3.png)

1. Voer de **[!UICONTROL Previous Value]** in. In dit voorbeeld gebruiken we MQL.

   ![](assets/add-a-constraint-to-a-smart-list-filter-4.png)

1. Selecteer onder **[!UICONTROL Add Constraint]** de optie **[!UICONTROL New Value]** .

   ![](assets/add-a-constraint-to-a-smart-list-filter-5.png)

1. Voer de nieuwe waarde in. In dit voorbeeld gebruiken we SQL.

   ![](assets/add-a-constraint-to-a-smart-list-filter-6.png)

1. Echt waar! Klik op de tab **[!UICONTROL People]** om alle personen te zien die de afgelopen 30 dagen een statuswijziging van &quot;MQL&quot; in &quot;SQL&quot; hebben ondergaan.
