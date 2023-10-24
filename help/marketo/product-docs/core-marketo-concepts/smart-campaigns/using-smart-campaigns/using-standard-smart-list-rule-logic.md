---
unique-page-id: 1147001
description: Werken met Standard Smart List Rule Logic - Marketo Docs - Productdocumentatie
title: Werken met Standard Smart List Rule Logic
exl-id: 9befaa81-e50c-47d3-9edf-220cfadd00f6
feature: Smart Campaigns
source-git-commit: 47bc93665a7efa0d64cd4d5f34b868895d407527
workflow-type: tm+mt
source-wordcount: '129'
ht-degree: 0%

---

# Werken met Standard Smart List Rule Logic {#using-standard-smart-list-rule-logic}

Mogelijk hebt u de optie Filters gebruiken opgemerkt bij het maken van slimme lijsten voor campagnes. Met deze instelling kunt u bepalen of de filters moeten worden geëvalueerd met een operator AND of OR.

![](assets/using-standard-smart-list-rule-logic-1.png)

>[!NOTE]
>
>Het wijzigen van de logica van de regel voor slimme lijsten is alleen van toepassing op filters. _niet_ triggers.

Triggers worden altijd geëvalueerd als OR, zelfs als de bovenstaande instelling op ALL is ingesteld. Hier volgt een voorbeeld:

![](assets/using-standard-smart-list-rule-logic-2.png)

De bovenstaande slimme lijst in woorden:

```box
IF person fills out Great Form
OR
IF person visits Keith's Landing Page 
AND 
Industry is Energy 
AND 
Country is US 
THEN follow the campaign's flow step(s)
```

Dus als iemand het formulier invult _of_ bezoekt de pagina , dan zal de campagne die persoon evalueren op basis van _alles_ of _alle_ van de volgende filters, afhankelijk van de gebruikte instelling.

>[!MORELIKETHIS]
>
>[Advanced Smart List Rule Logic gebruiken](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/using-advanced-smart-list-rule-logic.md){target="_blank"}
