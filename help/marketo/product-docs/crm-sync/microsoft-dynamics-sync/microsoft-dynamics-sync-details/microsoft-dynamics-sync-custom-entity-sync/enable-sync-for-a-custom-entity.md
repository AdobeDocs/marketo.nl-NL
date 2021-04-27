---
unique-page-id: 2953384
description: Sync inschakelen voor een aangepaste entiteit - Marketo Docs - Productdocumentatie
title: Sync inschakelen voor een aangepaste entiteit
exl-id: 4b075bf3-f10b-4725-8c8e-a6ecee63d756
translation-type: tm+mt
source-git-commit: d81a4a3caa12c5ec642afadf9328b3825bde6fed
workflow-type: tm+mt
source-wordcount: '196'
ht-degree: 0%

---

# Sync inschakelen voor een aangepaste entiteit {#enable-sync-for-a-custom-entity}

Als u de gegevens van de douaneentiteit van Dynamica nodig hebt om in Marketo beschikbaar te zijn, is hier hoe te om de synchronisatie voor het toe te laten:

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

>[!NOTE]
>
>Wanneer u de synchronisatie inschakelt voor een aangepaste entiteit, voert Marketo een eerste synchronisatie uit om alle gegevens voor het aangepaste object in te voeren.

1. Ga naar **Admin** sectie.

   ![](assets/image2014-10-20-14-3a32-3a16.png)

1. Selecteer **Microsoft Dynamics** en klik **Sync** uitschakelen.

   U moet de algemene synchronisatie tijdelijk uitschakelen om een aangepaste entiteit in of uit te schakelen.

   ![](assets/image2015-11-10-9-3a0-3a6.png)

1. Klik onder Databasebeheer op de koppeling **Dynamics Entities Sync**.

   ![](assets/image2015-11-10-9-3a6-3a55.png)

1. Klik op de koppeling **Schema synchroniseren**.

   ![](assets/image2015-11-10-9-3a41-3a37.png)

1. Selecteer de entiteit die u wilt synchroniseren en klik **Sync inschakelen**.

   ![](assets/image2015-11-10-9-3a44-3a35.png)

1. Selecteer de velden die u wilt synchroniseren of gebruiken als [beperkingen](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/add-a-constraint-to-a-smart-list-filter.md) en/of triggers in slimme lijsten. Wanneer gedaan, klik **toelaten Synchronisatie**.

   ![](assets/image2014-10-20-14-3a32-3a55.png)

   >[!NOTE]
   >
   >Tijdens het synchronisatieproces kan het zijn dat het item &quot;Dynamic Entities Sync&quot; uit de boomstructuur verdwijnt. Dit wordt verwacht en verschijnt weer nadat het synchroniseren is voltooid.

1. De entiteit heeft nu een groen vinkje.

   ![](assets/image2014-10-20-14-3a33-3a4.png)

1. Vergeet niet de globale synchronisatie opnieuw in te schakelen!

   ![](assets/image2015-11-10-9-3a48-3a35.png)

O ja! Krachtige dingen.
