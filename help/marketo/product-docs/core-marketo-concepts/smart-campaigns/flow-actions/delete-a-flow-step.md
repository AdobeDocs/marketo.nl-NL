---
unique-page-id: 1146987
description: Een stroomstap verwijderen - Marketo Docs - Productdocumentatie
title: Een stroomstap verwijderen
exl-id: 039a1e80-48cc-47f9-9e1a-459f89bf0730
feature: Smart Campaigns
source-git-commit: 9e51ece12742152040dbbcb6a1584fba28e863ff
workflow-type: tm+mt
source-wordcount: '361'
ht-degree: 0%

---

# Een stroomstap verwijderen {#delete-a-flow-step}

>[!CAUTION]
>
>Het verwijderen van stroomstappen, _vooral stappen wachten_ van actieve slimme campagnes, kan onverwachte resultaten hebben. Lees dit artikel zorgvuldig door.

Laten we eerst de basisbeginselen behandelen. Hier is hoe te om een ongewenste stroomstap uit een Slimme Campagne te verwijderen.

1. In de slimme campagne **[!UICONTROL Flow]** klikt u op de knop **X** pictogram om een stroomstap te verwijderen.

![](assets/image2014-9-22-13-3a52-3a20.png)

1. Klik op **[!UICONTROL Delete]**.

   ![](assets/image2014-9-22-13-3a55-3a25.png)

   Eenvoudig en eenvoudig, niet? Meestal...

   >[!CAUTION]
   >
   >Stappen verwijderen, toevoegen en verplaatsen binnen een _actief_ de campagne kan zeker onverwachte resultaten opleveren . Overweeg een nieuwe campagne te maken, deze te testen en vervolgens over te schakelen.

   Wijzigingen kunnen worden aangebracht in een actieve campagne, maar kunnen onvoorziene gevolgen hebben. Hier volgen de details:

   **Slimme batch-campagnes**

   Als uw campagne:

   1. **Nooit rennen**. Breng alle gewenste wijzigingen aan. Het zal niemand beïnvloeden tot je die campagne voert.
   1. **Is een terugkerende Slimme Campagne**. De wijzigingen zijn van invloed op mensen in de toekomst, niet op vorige versies.
   1. **Reeds gestart ZONDER stappen te wachten**. Er zullen geen mensen worden beïnvloed omdat de campagne na de uitvoering slapend is.
   1. **Wordt nu uitgevoerd**. Wijzigingen kunnen onverwacht gedrag veroorzaken, afhankelijk van de timing en de details van het verwijderen. We raden u sterk aan GEEN batchcampagne te bewerken die actief wordt uitgevoerd. Leer hoe u in noodgevallen [Een actieve slimme campagne afbreken](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/using-smart-campaigns/abort-a-smart-campaign.md){target="_blank"}.

   1. **Reeds gestart MET wachtstappen.** Hierover zijn verschillende details te vinden.\
      Wanneer een persoon een wachttijdstap ingaat, sluit de persoon zich aan bij de duur en welke STEP van het GETAL om aan terug te keren. Zie het onderstaande voorbeeld.

   **Slimme campagnes activeren**

   1. **Geen wachtstappen**. Als u een normale stap verwijdert, heeft dit alleen gevolgen voor mensen die de campagne in de toekomst doorlopen.
   1. **Met wachtende stappen**. Zie het onderstaande voorbeeld voor batchcampagnes. Dezelfde logica is van toepassing.

   >[!NOTE]
   >
   >**Voorbeeld**
   >
   >1. Een slimme campagne bestaat uit drie stappen.
   >    * STAP 1. E-mailadres 1 verzenden
   >    * STAP 2. Wacht 1 week
   >    * STAP 3. E-mailadres 2 verzenden
   >
   >1. Mensen die getroffen zijn **Stap 2** zal 1 week wachten alvorens op te gaan **Stap 3**.
   >1. U verwijdert **Stap 2** gedurende de week.
   >1. Mensen blijven de 1 week wachten (ze komen niet automatisch terug in de flow).
   >1. Als ze eindelijk terugkeren, zullen ze proberen om naar **Stap 3**. Ze zullen het niet vinden.
   >1. **BELANGRIJK:** Aangezien er nu slechts twee stappen zijn, zijn de mensen _ontvangt geen e-mail #2_.
