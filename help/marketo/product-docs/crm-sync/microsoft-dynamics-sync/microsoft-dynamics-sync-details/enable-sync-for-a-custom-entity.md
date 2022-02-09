---
unique-page-id: 2953384
description: Sync inschakelen voor een aangepaste entiteit - Marketo Docs - Productdocumentatie
title: Sync inschakelen voor een aangepaste entiteit
exl-id: 4b075bf3-f10b-4725-8c8e-a6ecee63d756
source-git-commit: dadaf5bd8e887309d0e9ee8fc25fc58d1c4fbe97
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# Sync inschakelen voor een aangepaste entiteit {#enable-sync-for-a-custom-entity}

Als u de gegevens van de douaneentiteit van Dynamica nodig hebt om in Marketo beschikbaar te zijn, is hier hoe te om de synchronisatie voor het toe te laten.

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

>[!NOTE]
>
>* Wanneer u de synchronisatie inschakelt voor een aangepaste entiteit, voert Marketo een eerste synchronisatie uit om alle gegevens voor het aangepaste object in te voeren.
>* Leden van de Marketing List en de Marketing List zijn **niet ondersteund** op dat moment.


1. Ga naar de **Beheer** sectie.

   ![](assets/enable-sync-for-a-custom-entity-1.png)

1. Selecteren **Microsoft Dynamics** en klik op **Sync uitschakelen**.

   ![](assets/enable-sync-for-a-custom-entity-2.png)

   >[!NOTE]
   >
   >U moet de algemene synchronisatie tijdelijk uitschakelen om een aangepaste entiteit in of uit te schakelen.

1. Klik onder Databasebeheer op de knop **Synchronisatie van dynamische entiteiten** koppeling.

   ![](assets/enable-sync-for-a-custom-entity-3.png)

1. Klik op de knop **Schema synchroniseren** koppeling.

   ![](assets/enable-sync-for-a-custom-entity-4.png)

1. Selecteer de entiteit die u wilt synchroniseren en klik op **Sync inschakelen**.

   ![](assets/enable-sync-for-a-custom-entity-5.png)

1. Selecteer de velden die u wilt synchroniseren of gebruiken als [beperkingen](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/add-a-constraint-to-a-smart-list-filter.md) en/of triggers in slimme lijsten. Klik wanneer gereed **Sync inschakelen**.

   ![](assets/enable-sync-for-a-custom-entity-6.png)

   >[!NOTE]
   >
   >Tijdens het synchronisatieproces kan het zijn dat het item &quot;Dynamic Entities Sync&quot; uit de boomstructuur verdwijnt. Dit wordt verwacht en verschijnt weer nadat het synchroniseren is voltooid.

1. De entiteit heeft nu een groen vinkje.

   ![](assets/enable-sync-for-a-custom-entity-7.png)

1. Vergeet niet de globale synchronisatie opnieuw in te schakelen!

   ![](assets/enable-sync-for-a-custom-entity-8.png)
