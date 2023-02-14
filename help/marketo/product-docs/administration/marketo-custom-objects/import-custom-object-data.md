---
unique-page-id: 10099680
description: Aangepaste objectgegevens importeren - Marketo Docs - Productdocumentatie
title: Aangepaste objectgegevens importeren
exl-id: ee11199a-57ca-47ec-8f59-8384a93ea05e
source-git-commit: 99b11e17e9c2255a19c658b166e7b38c45cf1001
workflow-type: tm+mt
source-wordcount: '233'
ht-degree: 0%

---

# Aangepaste objectgegevens importeren {#import-custom-object-data}

Het is gemakkelijk om douaneobjecten gegevens in uw gegevensbestand in te voeren. Als u douanevoorwerpen met bedrijven gebruikt, zie [Aangepaste objecten gebruiken met bedrijven](/help/marketo/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md#using-custom-objects-with-companies) voor meer informatie .

1. Ga in Mijn Marketo naar **Database**.

   ![](assets/import-custom-object-data-1.png)

1. Klikken **Nieuw** en selecteert u **Aangepaste objectgegevens importeren**.

   ![](assets/import-custom-object-data-2.png)

1. Klikken **Bladeren** om het gegevensbestand te zoeken. Selecteer de bestandsindeling (door komma&#39;s gescheiden waarden in dit voorbeeld).

   ![](assets/import-custom-object-data-3.png)

1. Selecteer het aangepaste object.

   ![](assets/import-custom-object-data-4.png)

1. Selecteer de deduplicatiemodus in het keuzemenu. Klikken **Volgende**.

   ![](assets/import-custom-object-data-5.png)

   >[!NOTE]
   >
   >Gebruik het (de) Dedupeveld(en) als unieke herkenningstekens wanneer u douaneobjecten verslagen creeert of bijwerkt. In dit voorbeeld wordt het veld Dedupe van het dialoogvenster **auto** aangepast object - vin (ID voertuig). Als u alleen aangepaste objectrecords bijwerkt, kunt u de Marketo-hulplijn selecteren als de deduplicatiemodus.

1. Wijs elke kolom aan een gebied van Marketo toe, dat het van drop-down selecteert.

   ![](assets/import-custom-object-data-6.png)

   >[!NOTE]
   >
   >Zorg ervoor dat de waarden in het bestand overeenkomen met het veldtype waarop u deze aansluit (bijvoorbeeld tekst, geheel getal, enzovoort). Anders wordt het bestand geweigerd.

1. Klikken **Volgende**.

   ![](assets/import-custom-object-data-7.png)

1. Klikken **Importeren**.

   ![](assets/import-custom-object-data-8.png)

   >[!NOTE]
   >
   >De formaatgrens voor douanevoorwerpen is 100MB.

   >[!TIP]
   >
   >Voer uw e-mailadres in het dialoogvenster **Waarschuwing verzenden naar:** -veld en Marketo sturen je een e-mail wanneer het importeren is voltooid.

1. In de rechterbovenhoek van het scherm ziet u een melding als het importeren wordt uitgevoerd en ziet u de uiteindelijke resultaten als het is voltooid.

   ![](assets/import-custom-object-data-9.png)

   Yay!

>[!MORELIKETHIS]
>
>[Aangepaste Marketo-objecten begrijpen](/help/marketo/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md)
