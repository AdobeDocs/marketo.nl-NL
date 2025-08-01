---
unique-page-id: 1146987
description: Een stroomstap verwijderen - Marketo Docs - Productdocumentatie
title: Een stroomstap verwijderen
exl-id: 039a1e80-48cc-47f9-9e1a-459f89bf0730
feature: Smart Campaigns
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '367'
ht-degree: 0%

---

# Een stroomstap verwijderen {#delete-a-flow-step}

>[!CAUTION]
>
>Het verwijderen van stroomstappen, _wacht vooral stappen_ van actieve Slimme Campagnes, kan onverwachte resultaten hebben. Lees dit artikel zorgvuldig door.

Laten we eerst de basisbeginselen behandelen. Hier is hoe te om een ongewenste stroomstap uit een Slimme Campagne te verwijderen.

1. In de Slimme Campagne **[!UICONTROL Flow]**, klik het **X** pictogram om het even welke stroomstap te schrappen.

   ![](assets/delete-a-flow-step-1.png)

1. Klik op **[!UICONTROL Delete]**.

   ![](assets/delete-a-flow-step-2.png)

   >[!CAUTION]
   >
   >Het schrappen van, het toevoegen van, en het bewegen van stappen binnen een _actieve_ campagne kunnen zeker onverwachte resultaten hebben. Overweeg een nieuwe campagne te maken, deze te testen en vervolgens over te schakelen.

   Wijzigingen kunnen worden aangebracht in een actieve campagne, maar kunnen onvoorziene gevolgen hebben. Hier volgen de details:

   **Partij Slimme Campagnes**

   Als uw campagne:

   1. **liep nooit**. Breng alle gewenste wijzigingen aan. Het zal niemand beïnvloeden tot je die campagne voert.
   1. **is een terugkomende Slimme Campagne**. De wijzigingen zijn van invloed op mensen in de toekomst, niet op vorige versies.
   1. **reeds liep ZONDER stappen** te wachten.Geen mensen zullen worden beïnvloed omdat de campagne na het runnen slapend is.
   1. **loopt nu**. Wijzigingen kunnen onverwacht gedrag veroorzaken, afhankelijk van de timing en de details van het verwijderen. We raden u sterk aan GEEN batchcampagne te bewerken die actief wordt uitgevoerd. Voor noodgevallen, leer hoe te [ een lopende Slimme Campagne ](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/using-smart-campaigns/abort-a-smart-campaign.md){target="_blank"} afbreken.

   1. **reeds liep MET wachtende stappen.** Verschillende details over deze.
Wanneer een persoon een wachttijdstap ingaat, sluit de persoon zich aan bij de duur en welke STEP van het GETAL om aan terug te keren. Zie het onderstaande voorbeeld.

   **Trigger Slimme Campagnes**

   1. **Geen wachtstappen**. Als u een normale stap verwijdert, heeft dit alleen gevolgen voor mensen die de campagne in de toekomst doorlopen.
   1. **met wachtende stappen**. Zie het onderstaande voorbeeld voor batchcampagnes. Dezelfde logica is van toepassing.

   >[!NOTE]
   >
   >**Voorbeeld**
   >
   >1. Een slimme campagne bestaat uit drie stappen.
   >    * STAP 1. E-mailadres 1 verzenden
   >    * STAP 2. Wacht 1 week
   >    * STAP 3. E-mailadres 2 verzenden
   >
   >1. De mensen die **Stap 2** raken zullen 1 week wachten alvorens op **Stap 3** te bewegen.
   >1. U schrapt **Stap 2** tijdens de week.
   >1. Mensen blijven de 1 week wachten (ze komen niet automatisch terug in de flow).
   >1. Wanneer zij definitief terugkeren, zullen zij proberen om naar **Stap 3** te gaan. Ze zullen het niet vinden.
   >1. **BELANGRIJK:** Aangezien er nu slechts 2 stappen zijn, zullen de mensen _geen E-mail #2_ ontvangen.
