---
unique-page-id: 10099680
description: Aangepaste objectgegevens importeren - Marketo Docs - Productdocumentatie
title: Aangepaste objectgegevens importeren
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '242'
ht-degree: 0%

---


# Aangepaste objectgegevens importeren {#import-custom-object-data}

Het is gemakkelijk om douaneobjecten gegevens in uw gegevensbestand in te voeren. Als u douanevoorwerpen met bedrijven gebruikt, zie het [Gebruiken van de Voorwerpen van de Douane met Bedrijven](http://docs.marketo.com/display/DOCS/Understanding+Marketo+Custom+Objects#UnderstandingMarketoCustomObjects-customcompanyUsingCustomObjectswithCompanies) voor meer informatie.

1. Ga in Mijn Marketo naar **Database**.

   ![](assets/db-1.png)

1. Klik op **Nieuw** en selecteer Aangepaste objectgegevens **** importeren.

   ![](assets/image2016-4-7-10-6-54.png)

1. Klik op **Bladeren** om het gegevensbestand te zoeken. Selecteer de bestandsindeling (door komma&#39;s gescheiden waarden in dit voorbeeld).

   ![](assets/image2016-4-13-14-3a21-3a53.png)

1. Selecteer het aangepaste object.

   ![](assets/image2016-4-13-14-3a24-3a54.png)

1. Selecteer de deduplicatiemodus in het keuzemenu. Klik op **Volgende**.

   ![](assets/image2016-4-13-14-3a28-3a7.png)

   >[!NOTE]
   >
   >Gebruik het (de) Dedupeveld(en) als unieke herkenningstekens wanneer u douaneobjecten verslagen creeert of bijwerkt. In dit voorbeeld wordt het veld Dedupe van het aangepaste object **car** - vin (ID-nummer van voertuig) gebruikt. Als u alleen aangepaste objectrecords bijwerkt, kunt u de Marketo-hulplijn selecteren als de deduplicatiemodus.

1. Wijs elke kolom aan een Marketo gebied toe, die het van drop-down selecteren.

   ![](assets/image2016-4-13-14-3a36-3a57.png)

   >[!NOTE]
   >
   >Zorg ervoor dat de waarden in het bestand overeenkomen met het veldtype waarop u deze aansluit (bijvoorbeeld tekst, geheel getal, enz.). Als dit niet het geval is, wordt het bestand geweigerd.

1. Klik op **Volgende**.

   ![](assets/image2016-4-13-14-3a38-3a41.png)

1. Klik op **Importeren**.

   ![](assets/image2016-4-7-13-3a15-3a9.png)

   >[!NOTE]
   >
   >De formaatgrens voor douanevoorwerpen is 100MB.

   >[!TIP]
   >
   >Voer uw e-mailadres in het bericht Waarschuwing **verzenden naar:** en Marketo sturen u een e-mail wanneer het importeren is voltooid.

1. In de rechterbovenhoek van het scherm ziet u een melding als het importeren wordt uitgevoerd en ziet u de uiteindelijke resultaten als het is voltooid.

   ![](assets/image2016-4-13-14-3a41-3a1.png)

   Yay!

>[!MORELIKETHIS]
>
>* [Aangepaste objecten markeren](understanding-marketo-custom-objects.md)

>



