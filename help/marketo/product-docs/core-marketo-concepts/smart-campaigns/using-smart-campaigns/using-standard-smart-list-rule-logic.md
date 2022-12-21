---
unique-page-id: 1147001
description: Werken met Standard Smart List Rule Logic - Marketo Docs - Productdocumentatie
title: Werken met Standard Smart List Rule Logic
exl-id: 9befaa81-e50c-47d3-9edf-220cfadd00f6
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '129'
ht-degree: 0%

---

# Werken met Standard Smart List Rule Logic {#using-standard-smart-list-rule-logic}

Mogelijk hebt u de optie Filters gebruiken opgemerkt bij het samenstellen van slimme lijsten voor de campagne. Met deze instelling kunt u bepalen of de filters moeten worden geëvalueerd met een operator AND of OR.

![](assets/image2014-9-22-14-3a12-3a42.png)

>[!NOTE]
>
>Het wijzigen van de logica van de regel voor slimme lijsten is alleen van toepassing op filters. **niet** triggers.

Triggers worden altijd geëvalueerd als OR, zelfs als de bovenstaande instelling op ALL is ingesteld.  Hier volgt een voorbeeld:

![](assets/image2014-9-22-14-3a12-3a57.png)

De bovenstaande slimme lijst in woorden:

```box
IF person fills out My Form
OR
IF person visits My Page 
AND 
Industry is Marketing 
AND 
Country is USA 
THEN follow the campaign's flow step(s)
```

Dus als iemand het formulier invult **of** bezoekt de pagina , dan zal de campagne die persoon evalueren op basis van **alles** of **alle** van de volgende filters, afhankelijk van de gebruikte instelling.

>[!MORELIKETHIS]
>
>[Advanced Smart List Rule Logic gebruiken](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/using-advanced-smart-list-rule-logic.md)
