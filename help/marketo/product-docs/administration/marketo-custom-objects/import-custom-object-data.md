---
unique-page-id: 10099680
description: Aangepaste objectgegevens importeren - Marketo Docs - Productdocumentatie
title: Aangepaste objectgegevens importeren
exl-id: ee11199a-57ca-47ec-8f59-8384a93ea05e
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '233'
ht-degree: 0%

---

# Aangepaste objectgegevens importeren {#import-custom-object-data}

Het is gemakkelijk om douaneobjecten gegevens in uw gegevensbestand in te voeren. Als u douanevoorwerpen met bedrijven gebruikt, zie [Aangepaste objecten gebruiken met bedrijven](/help/marketo/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md#using-custom-objects-with-companies) voor meer informatie .

1. Ga in Mijn Marketo naar **Database**.

   ![](assets/db-1.png)

1. Klikken **Nieuw** en selecteert u **Aangepaste objectgegevens importeren**.

   ![](assets/image2016-4-7-10-6-54.png)

1. Klikken **Bladeren** om het gegevensbestand te zoeken. Selecteer de bestandsindeling (door komma&#39;s gescheiden waarden in dit voorbeeld).

   ![](assets/image2016-4-13-14-3a21-3a53.png)

1. Selecteer het aangepaste object.

   ![](assets/image2016-4-13-14-3a24-3a54.png)

1. Selecteer de deduplicatiemodus in het keuzemenu. Klikken **Volgende**.

   ![](assets/image2016-4-13-14-3a28-3a7.png)

   >[!NOTE]
   >
   >Gebruik het (de) Dedupeveld(en) als unieke herkenningstekens wanneer u douaneobjecten verslagen creeert of bijwerkt. In dit voorbeeld wordt het veld Dedupe van het dialoogvenster **auto** aangepast object - vin (ID voertuig). Als u alleen aangepaste objectrecords bijwerkt, kunt u de Marketo-hulplijn selecteren als de deduplicatiemodus.

1. Wijs elke kolom aan een gebied van Marketo toe, dat het van drop-down selecteert.

   ![](assets/image2016-4-13-14-3a36-3a57.png)

   >[!NOTE]
   >
   >Zorg ervoor dat de waarden in het bestand overeenkomen met het veldtype waarop u deze aansluit (bijvoorbeeld tekst, geheel getal, enzovoort). Anders wordt het bestand geweigerd.

1. Klikken **Volgende**.

   ![](assets/image2016-4-13-14-3a38-3a41.png)

1. Klikken **Importeren**.

   ![](assets/image2016-4-7-13-3a15-3a9.png)

   >[!NOTE]
   >
   >De formaatgrens voor douanevoorwerpen is 100MB.

   >[!TIP]
   >
   >Voer uw e-mailadres in het dialoogvenster **Waarschuwing verzenden naar:** -veld en Marketo sturen je een e-mail wanneer het importeren is voltooid.

1. In de rechterbovenhoek van het scherm ziet u een melding als het importeren wordt uitgevoerd en ziet u de uiteindelijke resultaten als het is voltooid.

   ![](assets/image2016-4-13-14-3a41-3a1.png)

   Yay!

>[!MORELIKETHIS]
>
>[Aangepaste Marketo-objecten begrijpen](/help/marketo/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md)
