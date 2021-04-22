---
unique-page-id: 1146987
description: Een stroomstap verwijderen - Marketo Docs - Productdocumentatie
title: Een stroomstap verwijderen
exl-id: 039a1e80-48cc-47f9-9e1a-459f89bf0730
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '377'
ht-degree: 0%

---

# Een stroomstap {#delete-a-flow-step} verwijderen

>[!CAUTION]
>
>Het verwijderen van stroomstappen, _vooral wachtstappen_ van actieve slimme campagnes, kan onverwachte resultaten hebben. **Lees dit artikel zorgvuldig door.**

Laten we eerst de basisbeginselen doen. Hier is hoe te om een ongewenste stroomstap uit een slimme campagne te verwijderen. 1. Klik in de slimme-campagnestroom op het X-pictogram om een flowstap te verwijderen.

![](assets/image2014-9-22-13-3a52-3a20.png)

1. Klik **Delete**.

   ![](assets/image2014-9-22-13-3a55-3a25.png)

   Eenvoudig en eenvoudig, niet? Meestal...

   >[!CAUTION]
   >
   >Het verwijderen, toevoegen en verplaatsen van stappen binnen een **actieve** campagne kan zeker onverwachte resultaten hebben. Overweeg een nieuwe campagne te maken, deze te testen en vervolgens over te schakelen.

   Wijzigingen kunnen worden aangebracht in een actieve campagne, maar kunnen onvoorziene gevolgen hebben. Hier volgen de details:

   **Slimme batch-campagnes**

   Als uw campagne:

   1. **Nooit rennen.** Breng alle gewenste wijzigingen aan. Het zal niemand beïnvloeden tot je die campagne voert.
   1. **Dit is een terugkerende slimme campagne.** De wijzigingen zijn van invloed op mensen in de toekomst, niet op vorige versies.
   1. **Reeds gestart ZONDER stappen te wachten.** Er zullen geen mensen worden beïnvloed omdat de campagne na de uitvoering slapend is.
   1. **Wordt nu uitgevoerd.** Wijzigingen kunnen onverwacht gedrag veroorzaken, afhankelijk van de timing en de details van de verwijdering. We raden u sterk aan GEEN batchcampagne te bewerken die actief wordt uitgevoerd. Leer voor noodgevallen hoe u een actieve slimme campagne ](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/using-smart-campaigns/abort-a-smart-campaign.md) kunt afbreken.[

   1. **Reeds gestart MET wachtstappen.** Hierover zijn verschillende details te vinden.\
      Wanneer een persoon een wachttijdstap ingaat, sluit de persoon zich aan bij de duur en welke STEP van het GETAL om aan terug te keren. Zie het onderstaande voorbeeld.

   **Slimme campagnes activeren**

   1. **Geen wachtstappen.** Als u een normale stap verwijdert, heeft dit alleen gevolgen voor mensen die de campagne in de toekomst doorlopen.
   1. **Met wachtende stappen.** Zie het onderstaande voorbeeld voor batchcampagnes. Dezelfde logica is van toepassing.

   >[!NOTE]
   >
   >**Voorbeeld**
   >
   >1. Een slimme campagne bestaat uit drie stappen.
      >    * STAP 1. E-mailadres 1 verzenden
      >    * STAP 2. Wacht 1 week
      >    * STAP 3. E-mailadres 2 verzenden
   >
   >1. Personen die **Stap 2** raken, wachten één week voordat ze verdergaan naar **Stap 3**.
   >1. U schrapt **Stap 2** tijdens de week.
   >1. Mensen zullen de 1 week blijven wachten. (Ze komen niet automatisch terug in de flow.)
   >1. Wanneer zij uiteindelijk terugkeren, zullen zij proberen om naar **Stap 3** te gaan. Ze zullen het niet vinden.
   >1. **BELANGRIJK:** Aangezien er nu slechts twee stappen zijn, zullen de  *mensen geen e-mail #2 ontvangen.*


Wijzigingen aanbrengen in een actieve campagne

Begrijp deze functie en u zult slimme campagnes master.
