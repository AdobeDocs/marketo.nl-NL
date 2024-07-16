---
unique-page-id: 1147324
description: Veldwaarden wissen - Marketo Docs - Productdocumentatie
title: Veldwaarden wissen
exl-id: cddc7697-4e8f-4a62-865c-efd451abea0c
feature: Smart Campaigns
source-git-commit: 7dd2e21969b71a50bfd4643ab15459150ca07c92
workflow-type: tm+mt
source-wordcount: '102'
ht-degree: 0%

---

# Veldwaarden wissen {#clear-field-values}

[ de Waarde van Gegevens van de Verandering ](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/change-data-value.md) is groot, maar hoe u _verwijdert_ de waarde volledig? Goede vraag!

1. In de stroomstap, kies het gebied u zou willen ontruimen en in **ONGELDIG** (alle kapitalen) als **Nieuwe Waarde** typen.

   ![](assets/clear-field-values-1.png)

1. Boom! Ik wed dat je dat niet wist! Nadat de flowstap is voltooid, wordt de waarde van het veld dat u hebt gekozen, gewist.

   ![](assets/clear-field-values-2.png)

   >[!CAUTION]
   >
   >Als u de nieuwe waarde leeg laat of gewoon een SPATIE invoert, wordt het veld niet echt leeg. U moet NULL typen. Stroom-stappen kunnen ook niet ongedaan worden gemaakt nadat deze zijn uitgevoerd.
