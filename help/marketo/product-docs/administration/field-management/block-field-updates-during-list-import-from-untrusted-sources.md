---
unique-page-id: 2360335
description: De Updates van het Gebied van het blok tijdens de Invoer van de Lijst van Onbetrouwbare Bronnen - Marketo Docs - de Documentatie van het Product
title: Veldupdates blokkeren tijdens het importeren van lijsten uit niet-vertrouwde bronnen
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '205'
ht-degree: 0%

---


# Veldupdates blokkeren tijdens het importeren van lijsten uit niet-vertrouwde bronnen {#block-field-updates-during-list-import-from-untrusted-sources}

U kunt de gegevens in sommige lijsten meer vertrouwen dan in andere. Soms hebt u twijfelachtige gegevens en wilt u deze gebruiken als het veld leeg is, maar niet als er een bestaande waarde is. U kunt dit bereiken door veldupdates op sleutelvelden te blokkeren.

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

## Veldupdates blokkeren vanuit niet-vertrouwde bronnen {#blocking-field-updates-from-untrusted-sources}

1. Ga naar **Admin** en klik op **Veldbeheer**.

   ![](assets/image2014-9-19-9-3a38-3a38.png)

1. Zoek het gewenste veld, selecteer het en klik onder **Veldhandelingen** op **Veldupdates** blokkeren.

   ![](assets/image2014-9-19-9-3a39-3a40.png)

1. Schakel **Lijst importeren van niet-vertrouwde bron** in en klik op **Toepassen**.

   ![](assets/blockupdates.png)

>[!TIP]
>
>U kunt velden veilig houden voor alle lijsten, vertrouwd en niet-vertrouwd, door ook de optie Vertrouwde **bron** importeren van lijst te controleren.

Herhaal bovenstaande stappen voor alle andere velden die u wilt beveiligen tegen niet-vertrouwde lijsten.

## Importeren van niet-vertrouwde lijsten uitvoeren {#running-an-untrusted-list-import}

1. Wanneer u de lijst wilt importeren, moet u **Niet-vertrouwde **selecteren als u wilt dat alle velden die u in de vorige stap hebt ingesteld, veilig zijn.

   ![](assets/importpersondetails.jpg)

Zie Een lijst met personen [](../../../getting-started/quick-wins/import-a-list-of-people.md)importeren voor gedetailleerde instructies over het importeren van lijsten.

Mooi werk! Nu weet u hoe u sleutelvelden veilig kunt houden voor niet-vertrouwde lijsten.
