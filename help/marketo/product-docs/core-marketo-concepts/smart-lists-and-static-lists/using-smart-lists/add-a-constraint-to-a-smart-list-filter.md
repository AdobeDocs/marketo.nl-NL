---
unique-page-id: 2949413
description: Een restrictie toevoegen aan een slim lijstfilter - Marketo Docs - Productdocumentatie
title: Een restrictie toevoegen aan een slim lijstfilter
exl-id: 5345019c-55e7-4afd-b583-90f1a687a71c
feature: Smart Lists
source-git-commit: aeefe7a5c265e3a7ddd50920820742a463ab178a
workflow-type: tm+mt
source-wordcount: '160'
ht-degree: 2%

---

# Een restrictie toevoegen aan een slim lijstfilter {#add-a-constraint-to-a-smart-list-filter}

Bij het maken van een slimme lijst hebben sommige filters geavanceerde opties die &#39;beperkingen&#39; worden genoemd. Dit zijn extra voorwaarden die u kunt toevoegen aan filters en triggers om uw zoekopdracht nog verder te beperken.

In dit voorbeeld, voegen sommige beperkingen aan a toe **[Gewijzigde gegevenswaarde](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/change-data-value.md){target="_blank"}** te zoeken naar mensen met een statuswijziging van MQL in SQL.

>[!PREREQUISITES]
>
>* [Een slimme lijst maken](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md){target="_blank"}
>* [Het filter &quot;Gewijzigde gegevenswaarde&quot; in een slimme lijst gebruiken](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/use-the-data-value-changed-filter-in-a-smart-list.md){target="_blank"}

1. Ga naar **[!UICONTROL Marketing Activities]**.

   ![](assets/ma-1.png)

1. Selecteer de slimme lijst met een filter waaraan u een beperking wilt toevoegen en klik op de knop **[!UICONTROL Smart List]** tab.

   ![](assets/two-3.png)

1. Selecteer onder **[!UICONTROL Add Constraint]** de optie **[!UICONTROL Previous Value]**.

   ![](assets/three-3.png)

1. Voer de **[!UICONTROL Previous Value]**. In dit voorbeeld gebruiken we MQL.

   ![](assets/four-2.png)

1. Selecteer onder **[!UICONTROL Add Constraint]** de optie **[!UICONTROL New Value]**.

   ![](assets/five.png)

1. Voer de nieuwe waarde in. In dit voorbeeld gebruiken we SQL.

   ![](assets/six.png)

1. Echt waar! Klik op de knop **[!UICONTROL People]** om alle personen te zien die de afgelopen 30 dagen een statuswijziging van &quot;MQL&quot; in &quot;SQL&quot; hadden.
