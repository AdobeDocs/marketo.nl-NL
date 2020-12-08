---
unique-page-id: 1146997
description: Gebruik een Datumtoken in een Stapsgewijze wachtstand - Marketo Docs - Productdocumentatie
title: Een Date Token gebruiken in een Wachten Flow-stap
translation-type: tm+mt
source-git-commit: 728066ab05de82f6123bfaa1f0b05af8632e32b2
workflow-type: tm+mt
source-wordcount: '269'
ht-degree: 0%

---


# Een Date Token gebruiken in een Wachten Flow-stap {#use-a-date-token-in-a-wait-flow-step}

U kunt de stap van de Wachtstroom gebruiken om de reis van een persoon door een slimme campagne tot een bepaalde datum te pauzeren die een datumteken gebruikt. U kunt de einddatum ook met een aantal dagen wijzigen.

>[!NOTE]
>
>**FYI**
>
>Marketo is nu bezig met het standaardiseren van de taal voor alle abonnementen, dus u ziet mogelijk leads/leads in uw abonnement en personen/personen in docs.marketo.com. Deze termen betekenen hetzelfde. het heeft geen invloed op de instructies van het artikel . Er zijn nog enkele andere veranderingen. [Meer](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)informatie.

>[!NOTE]
>
>Dit geldt alleen voor triggercampagnes. U kunt deze functie niet gebruiken in batchcampagnes.

1. Sleep in het tabblad **Stroom** van slimme campagne over de stap **Wachten** .

   ![](assets/image2014-9-22-14-3a8-3a22.png)

1. Klik op het tandwielpictogram rechts.

   ![](assets/image2014-9-22-14-3a8-3a37.png)

1. Selecteer **Datumtoken** in de keuzelijst **Type**.

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
   >U kunt ook het aantal dagen opgeven met een `{{lead.` of een `{{company.` token dat een veld met gehele getallen of een `{{my.` token van het type getal vertegenwoordigt.

1. Klik op Opslaan.

   ![](assets/image2014-9-22-14-3a11-3a3.png)

   >[!NOTE]
   >
   >**Verwante artikelen**
   >
   >* [Gebruik een Duur in een Stap van de Stroom van de Wacht](use-a-duration-in-a-wait-flow-step.md)
   >* [Gebruik een specifieke Datum in een Stap van de Stroom van de Wacht](use-a-specific-date-in-a-wait-flow-step.md)


