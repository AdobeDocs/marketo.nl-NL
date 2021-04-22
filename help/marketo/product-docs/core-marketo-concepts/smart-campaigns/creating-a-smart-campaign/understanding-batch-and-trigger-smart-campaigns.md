---
unique-page-id: 2953132
description: Slimme campagnes in batch en trigger - Marketo Docs - Productdocumentatie
title: Slimme campagnes in batch en trigger
exl-id: 84a7b38c-b79c-4360-bd0b-3beb8ca35ac7
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '273'
ht-degree: 0%

---

# Slimme campagnes voor batchverwerking en triggers {#understanding-batch-and-trigger-smart-campaigns}

Er zijn twee soorten slimme campagnes: Batch en Trigger.

## Slimme batchcampagne {#batch-smart-campaign}

>[!NOTE]
>
>**Definitie**
>
>Een batchcampagne wordt op een bepaald moment gestart en heeft invloed op een specifieke groep mensen in één keer. Een voorbeeld zou een e-mail naar alle mensen in Californië verzenden.

Slimme batchcampagnes hebben alleen filters in de sectie van de slimme lijst (dus geen triggers).

![](assets/batch-filter.png)

Als u op het tabblad **Schema** klikt, wordt bevestigd dat de slimme campagne is ingesteld op &quot;Batch&quot;.

![](assets/batch-c4.png)

**Slimme batch-campagnes**

* Kan worden gepland voor terugkerende acties, zoals dagelijks, wekelijks, en maandelijks. Je kunt ze ook één keer laten draaien.
* Deze zijn zichtbaar op de [programmaweergave van het programma](/help/marketo/product-docs/core-marketo-concepts/programs/program-schedule-view/navigating-the-program-schedule-view.md). Alles na een stap &quot;Wacht&quot; in de slimme campagne wordt niet in de weergave opgenomen.

<br> 

## Slimme campagne activeren {#trigger-smart-campaign}

>[!NOTE]
>
>**Definitie**
>
>Een triggerslimme campagne beïnvloedt één persoon tegelijk op basis van een getriggerde gebeurtenis. Een voorbeeld van een trigger is het klikken op een koppeling in een e-mailbericht.

Als een slimme campagne minstens één trigger in de sectie van de slimme lijst gebruikt, wordt de modus automatisch ingesteld op geactiveerd.

![](assets/trigger.png)

Als u op het tabblad **Schema** klikt, wordt bevestigd dat de slimme campagne is ingesteld op &quot;Trigdered&quot;.

![](assets/trigger2.png)

**Slimme campagnes activeren**

* Kan niet worden gepland voor herhalingen. Deze kunnen alleen op actief of inactief worden ingesteld.
* U kunt meerdere trigger instellen. Als er echter een trigger wordt geactiveerd, worden de campagneacties uitgevoerd.

>[!TIP]
>
>Gebruik [activiteitenlogboek](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/locate-the-activity-log-for-a-person.md) om te zien wat stapsgewijs binnen uw slimme campagnes voorkwam. U kunt het activiteitenlogboek in het laatste lusje van de detailpagina van een persoon vinden.
