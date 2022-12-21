---
unique-page-id: 2949413
description: Een restrictie toevoegen aan een slim lijstfilter - Marketo Docs - Productdocumentatie
title: Een restrictie toevoegen aan een slim lijstfilter
exl-id: 5345019c-55e7-4afd-b583-90f1a687a71c
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '175'
ht-degree: 0%

---

# Een restrictie toevoegen aan een slim lijstfilter {#add-a-constraint-to-a-smart-list-filter}

Bij het maken van slimme lijsten hebben sommige filters geavanceerde opties die &#39;beperkingen&#39; worden genoemd. Dit zijn extra voorwaarden die u kunt toevoegen aan filters en triggers om uw zoekopdracht nog verder te beperken.

In dit voorbeeld, voegen sommige beperkingen aan a toe **[Gewijzigde gegevenswaarde](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/change-data-value.md)** te zoeken naar mensen met een statuswijziging van MQL in SQL.

>[!PREREQUISITES]
>
>* [Een slimme lijst maken](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md)
>* [Het filter &quot;Gewijzigde gegevenswaarde&quot; in een slimme lijst gebruiken](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/use-the-data-value-changed-filter-in-a-smart-list.md)
>


1. Ga naar **Marketingactiviteiten**.

   ![](assets/ma-1.png)

1. Selecteer de slimme lijst met een filter waaraan u een beperking wilt toevoegen en klik op de knop **Slimme lijst** tab.

   ![](assets/two-3.png)

1. Onder **Restrictie toevoegen**, selecteert u **Vorige waarde**.

   ![](assets/three-3.png)

1. Voer de **Vorige waarde**. In dit voorbeeld gebruiken we MQL.

   ![](assets/four-2.png)

1. Onder **Restrictie toevoegen**, selecteert u **Nieuwe waarde**.

   ![](assets/five.png)

1. Voer de **Nieuwe waarde**. In dit voorbeeld gebruiken we SQL.

   ![](assets/six.png)

1. Echt waar! Klik op de knop **Mensen** tabblad om alle personen te zien die een **Status** wijzigen van **MQL** tot **SQL** in de afgelopen 30 dagen.
