---
unique-page-id: 1146997
description: Gebruik een Datumtoken in een Stapsgewijze wachtstand - Marketo Docs - Productdocumentatie
title: Een Date Token gebruiken in een Wachten Flow-stap
translation-type: tm+mt
source-git-commit: 5b9f48c98464c79bcdca2e335f6a4a2edce98ce4
workflow-type: tm+mt
source-wordcount: '216'
ht-degree: 0%

---


# Een Date Token gebruiken in een Wachten Flow Step {#use-a-date-token-in-a-wait-flow-step}

U kunt de stap van de Wachtstroom gebruiken om de reis van een persoon door een slimme campagne tot een bepaalde datum te pauzeren die een datumteken gebruikt. U kunt de einddatum ook met een aantal dagen wijzigen.

>[!NOTE]
>
>Dit geldt alleen voor triggercampagnes. U kunt deze functie niet gebruiken in batchcampagnes.

1. In uw slimme campagne **Stroom** tabel, sleep over **Wacht** debietstap.

   ![](assets/image2014-9-22-14-3a8-3a22.png)

1. Klik op het tandwielpictogram rechts.

   ![](assets/image2014-9-22-14-3a8-3a37.png)

1. Selecteer **Datumtoken** in de vervolgkeuzelijst **Type**.

   ![](assets/image2014-9-22-14-3a8-3a41.png)

1. Kies een teken van de Datum om te specificeren wanneer de wachtende stap zou moeten beëindigen:

   * `{{my._____}}`
   * `{{lead.______}}`
   * `{{company.______}}`
   * `{{system._______}}`

   ![](assets/image2014-9-22-14-3a9-3a33.png)

1. Als u wilt wachten tot de volgende verjaardag van de datum die in het huidige of volgende kalenderjaar voorkomt, schakelt u het selectievakje in.

   ![](assets/image2014-9-22-14-3a9-3a37.png)

   >[!TIP]
   >
   >Gebruik deze optie op datumtokens die naar datums in het verleden verwijzen, zoals een geboortedatum of begindatum van een contract.

1. U kunt desgewenst de einddatum met een opgegeven aantal dagen wijzigen.

   ![](assets/image2014-9-22-14-3a9-3a57.png)

   >[!NOTE]
   >
   >U kunt het aantal dagen ook specificeren gebruikend een `{{lead.` of `{{company.` teken die een geheelgebied, of een `{{my.` teken van aantaltype vertegenwoordigt.

1. Klik **Opslaan**.

   ![](assets/image2014-9-22-14-3a11-3a3.png)

   >[!MORELIKETHIS]
   >
   >* [Gebruik een Duur in een Stap van de Stroom van de Wacht](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/wait/use-a-duration-in-a-wait-flow-step.md)
   >* [Gebruik een specifieke Datum in een Stap van de Stroom van de Wacht](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/wait/use-a-specific-date-in-a-wait-flow-step.md)

