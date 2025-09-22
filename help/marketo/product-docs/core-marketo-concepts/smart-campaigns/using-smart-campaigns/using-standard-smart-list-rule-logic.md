---
unique-page-id: 1147001
description: Werken met Standard Smart List Rule Logic - Marketo Docs - Productdocumentatie
title: Werken met Standard Smart List Rule Logic
exl-id: 9befaa81-e50c-47d3-9edf-220cfadd00f6
feature: Smart Campaigns
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '129'
ht-degree: 0%

---

# Werken met Standard Smart List Rule Logic {#using-standard-smart-list-rule-logic}

Mogelijk hebt u de optie Filters gebruiken opgemerkt bij het maken van slimme lijsten voor campagnes. Met deze instelling kunt u bepalen of de filters moeten worden geëvalueerd met een operator AND of OR.

![](assets/using-standard-smart-list-rule-logic-1.png)

>[!NOTE]
>
>Het veranderen van de slimme logica van de lijstregel is slechts op filters van toepassing, _niet_ trekkers.

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

Zo, als een persoon de vorm _invult of_ de pagina bezoekt, zal de campagne dan die persoon evalueren die op _wordt gebaseerd allen_ of _om het even welke_ van de verdere filters, afhankelijk van het gebruikte plaatsen.

>[!MORELIKETHIS]
>
>[ Gebruikend Geavanceerde Slimme Logica van de Regel van de Lijst ](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/using-advanced-smart-list-rule-logic.md){target="_blank"}
