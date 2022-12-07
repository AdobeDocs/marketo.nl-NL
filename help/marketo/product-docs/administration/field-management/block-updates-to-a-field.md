---
unique-page-id: 2360291
description: Updates van een veld blokkeren - Marketo Docs - Productdocumentatie
title: Updates van een veld blokkeren
exl-id: 763097a3-cfa0-4df7-bfd1-40332b8dda1e
source-git-commit: 2776969be44ba1a3d795e99986d10cf0470fb9e9
workflow-type: tm+mt
source-wordcount: '171'
ht-degree: 0%

---

# Updates van een veld blokkeren {#block-updates-to-a-field}

Door het blokkeren van updates van een veld kunt u één keer naar het veld schrijven en vervolgens de oorspronkelijke waarde gedurende de levensduur van het veld behouden. Dit kan handig zijn voor een veld zoals Personbron.

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

1. Ga naar de **Beheer** gebied.

   ![](assets/block-updates-to-a-field-1.png)

1. Klikken **Veldbeheer**.

   ![](assets/block-updates-to-a-field-2.png)

1. Zoek het veld, selecteer het vervolgens onder **Veldhandelingen**, klikt u op **Veldupdates blokkeren**.

   ![](assets/block-updates-to-a-field-3.png)

   >[!NOTE]
   >
   >U kunt updates blokkeren voor [Aangepaste velden voor programmalid](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/program-member-custom-fields.md) ook.

1. Selecteer **Invoerbronnen** u wilt blokkeren en klikken **Toepassen**.

   ![](assets/block-updates-to-a-field-4.png)

   >[!CAUTION]
   >
   >Wanneer u een lijst importeert, wordt de status van een veld dat wordt geblokkeerd in Voorvertoning importeren alleen weergegeven als het veld automatisch wordt herkend door Marketo op basis van de naam van het veld dat overeenkomt _exact_ (of als aliassen worden vastgesteld). Als het veld handmatig wordt gekozen in de vervolgkeuzelijst Marketo-veld, wordt de status voor geblokkeerd niet weergegeven in Voorvertoning importeren, maar wordt het blokkeren van updates voor dat veld nog steeds geïmplementeerd.
