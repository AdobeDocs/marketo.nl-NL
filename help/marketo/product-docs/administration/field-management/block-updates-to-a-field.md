---
unique-page-id: 2360291
description: Updates van een veld blokkeren - Marketo Docs - Productdocumentatie
title: Updates van een veld blokkeren
exl-id: 763097a3-cfa0-4df7-bfd1-40332b8dda1e
feature: Field Management
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '158'
ht-degree: 0%

---

# Updates van een veld blokkeren {#block-updates-to-a-field}

Door het blokkeren van updates van een veld kunt u één keer naar het veld schrijven en vervolgens de oorspronkelijke waarde gedurende de levensduur van het veld behouden. Dit kan handig zijn voor een veld als [!UICONTROL Person Source] .

>[!NOTE]
>
>**Vereiste Bevoegdheden Admin**

1. Ga naar het **[!UICONTROL Admin]** -gebied.

   ![](assets/block-updates-to-a-field-1.png)

1. Klik op **[!UICONTROL Field Management]**.

   ![](assets/block-updates-to-a-field-2.png)

1. Zoek het veld, selecteer het en klik onder **[!UICONTROL Field Actions]** op **[!UICONTROL Block Field Updates]** .

   ![](assets/block-updates-to-a-field-3.png)

   >[!NOTE]
   >
   >U kunt updates aan {de Gebieden van de Douane van het Lid van 0} blokkeren [ eveneens.](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/program-member-custom-fields.md)

1. Selecteer **[!UICONTROL Input Sources]** u wilt blokkeren en klik **[!UICONTROL Apply]**.

   ![](assets/block-updates-to-a-field-4.png)

   >[!CAUTION]
   >
   >Wanneer het uitvoeren van een lijstinvoer, zal de status van een gebied dat in de Voorproef van de Invoer wordt geblokkeerd slechts tonen als het gebied automatisch door Marketo wordt erkend die op de naam van het gebied _precies_ wordt gebaseerd (of als aliassen worden gevestigd). Als het veld handmatig wordt gekozen in de vervolgkeuzelijst Marketo-veld, wordt de status voor geblokkeerd niet weergegeven in Voorvertoning importeren, maar wordt het blokkeren van updates voor dat veld nog steeds geïmplementeerd.
