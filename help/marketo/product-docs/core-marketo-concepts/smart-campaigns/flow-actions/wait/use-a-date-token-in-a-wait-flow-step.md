---
unique-page-id: 1146997
description: Een Date Token gebruiken in een Wachten Flow-stap - Marketo Docs - Productdocumentatie
title: Een Date Token gebruiken in een Wachten Flow-stap
exl-id: d161922b-ce90-4e65-9282-d3bb866c1d94
feature: Smart Campaigns
source-git-commit: 2eeb7ea7fd43ba75a3c802a91ce07c90dc8abd91
workflow-type: tm+mt
source-wordcount: '207'
ht-degree: 0%

---

# Een Date Token gebruiken in een Wachten Flow-stap {#use-a-date-token-in-a-wait-flow-step}

U kunt de stap van de Wachtstroom gebruiken om de reis van een persoon door een Slimme Campagne tot een bepaalde datum te pauzeren die een datumteken gebruikt. U kunt de einddatum ook met een aantal dagen wijzigen.

>[!NOTE]
>
>Dit geldt alleen voor triggercampagnes. U kunt deze functie niet gebruiken in Batch-campagnes.

1. In uw slimme campagne **[!UICONTROL Flow]** tab, sleep over de **[!UICONTROL Wait]** stap Stroom.

   ![](assets/image2014-9-22-14-3a8-3a22.png)

1. Klik op het tandwielpictogram.

   ![](assets/image2014-9-22-14-3a8-3a37.png)

1. Van de **[!UICONTROL Type]** vervolgkeuzelijst, selecteert u **[!UICONTROL Date Token]**.

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
   >U kunt ook het aantal dagen opgeven met een `{{lead.` of `{{company.` token dat staat voor een veld met gehele getallen, of een `{{my.` token of number type.

1. Klik op **[!UICONTROL Save]**.

   ![](assets/image2014-9-22-14-3a11-3a3.png)

   >[!MORELIKETHIS]
   >
   >* [Gebruik een Duur in een Stap van de Stroom van de Wacht](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/wait/use-a-duration-in-a-wait-flow-step.md){target="_blank"}
   >* [Gebruik een specifieke Datum in een Stap van de Stroom van de Wacht](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/wait/use-a-specific-date-in-a-wait-flow-step.md){target="_blank"}
