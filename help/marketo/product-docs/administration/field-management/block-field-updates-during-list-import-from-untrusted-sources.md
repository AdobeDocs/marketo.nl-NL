---
unique-page-id: 2360335
description: Veldupdates blokkeren tijdens het importeren van lijsten uit niet-vertrouwde bronnen - Marketo Docs - Productdocumentatie
title: Veldupdates blokkeren tijdens het importeren van lijsten uit niet-vertrouwde bronnen
exl-id: 0fd59f0c-6cb9-442c-937b-da18a4466873
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '205'
ht-degree: 0%

---

# Veldupdates blokkeren tijdens het importeren van lijsten uit niet-vertrouwde bronnen {#block-field-updates-during-list-import-from-untrusted-sources}

U kunt de gegevens in sommige lijsten meer vertrouwen dan in andere. Soms hebt u twijfelachtige gegevens en wilt u deze gebruiken als het veld leeg is, maar niet als er een bestaande waarde is. U kunt dit bereiken door veldupdates op sleutelvelden te blokkeren.

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

## Veldupdates blokkeren uit niet-vertrouwde bronnen {#blocking-field-updates-from-untrusted-sources}

1. Ga naar **Admin** en klik **Veld Management**.

   ![](assets/image2014-9-19-9-3a38-3a38.png)

1. Zoek het gewenste veld, selecteer het en klik onder **Veldhandelingen** op **Veldupdates blokkeren**.

   ![](assets/image2014-9-19-9-3a39-3a40.png)

1. Schakel **Lijst van niet-vertrouwde bron importeren** in en klik **Toepassen**.

   ![](assets/blockupdates.png)

>[!TIP]
>
>U kunt velden veilig houden voor alle lijsten, vertrouwd en niet-vertrouwd, door **Vertrouwde bron bij importeren weergeven** ook te controleren.

Herhaal bovenstaande stappen voor alle andere velden die u wilt beveiligen tegen niet-vertrouwde lijsten.

## Importeren van niet-vertrouwde lijsten {#running-an-untrusted-list-import} uitvoeren

1. Wanneer u de lijst wilt importeren, moet u **Niet-vertrouwd** selecteren als u wilt dat alle velden die u in de vorige stap hebt ingesteld, veilig zijn.

   ![](assets/importpersondetails.jpg)

Zie [Een lijst met personen importeren](/help/marketo/getting-started/quick-wins/import-a-list-of-people.md) voor gedetailleerde instructies voor het importeren van lijsten.

Mooi werk! Nu weet u hoe u sleutelvelden veilig kunt houden voor niet-vertrouwde lijsten.
