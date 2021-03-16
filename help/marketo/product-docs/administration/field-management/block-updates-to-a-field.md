---
unique-page-id: 2360291
description: Updates van een veld blokkeren - Marketo Docs - Productdocumentatie
title: Updates van een veld blokkeren
translation-type: tm+mt
source-git-commit: 9f88e7cebc5e9d0d4491d65d332ccfdd9a31c395
workflow-type: tm+mt
source-wordcount: '170'
ht-degree: 0%

---


# Updates van een veld blokkeren {#block-updates-to-a-field}

Door het blokkeren van updates van een veld kunt u één keer naar het veld schrijven en vervolgens de oorspronkelijke waarde gedurende de levensduur van het veld behouden. Dit kan handig zijn voor een veld zoals Personbron.

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

1. Ga naar **Admin** en klik **Veld Management**.

   ![](assets/image2014-9-24-13-3a54-3a40.png)

1. Zoek het veld, selecteer het en klik onder **Veldhandelingen** op **Veldupdates blokkeren**.

   ![](assets/two-1.png)

   >[!NOTE]
   >
   >U kunt updates aan [De Aangepaste Gebieden van het Lid van het Programma ook blokkeren](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/program-member-custom-fields.md).

1. Selecteer **Invoerbronnen** die u wilt blokkeren en klik op **Toepassen**.

   ![](assets/image2014-9-24-13-3a55-3a16.png)

   >[!CAUTION]
   >
   >Wanneer u een lijst importeert, wordt de status van een veld dat wordt geblokkeerd in Voorvertoning importeren alleen weergegeven als het veld automatisch wordt herkend door Marketo op basis van de naam van het veld dat overeenkomt met _exact_ (of als er aliassen zijn ingesteld). Als het veld handmatig wordt gekozen in de vervolgkeuzelijst Marketo-veld, wordt de status voor geblokkeerd niet weergegeven in Voorvertoning importeren, maar wordt het blokkeren van updates voor dat veld nog steeds geïmplementeerd.
