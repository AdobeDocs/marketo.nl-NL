---
unique-page-id: 2360335
description: Veldupdates blokkeren tijdens het importeren van lijsten uit niet-vertrouwde bronnen - Marketo Docs - Productdocumentatie
title: Veldupdates blokkeren tijdens het importeren van lijsten uit niet-vertrouwde bronnen
exl-id: 0fd59f0c-6cb9-442c-937b-da18a4466873
feature: Field Management
source-git-commit: 02b2e39580c5eac63de4b4b7fdaf2a835fdd4ba5
workflow-type: tm+mt
source-wordcount: '188'
ht-degree: 0%

---

# Veldupdates blokkeren tijdens het importeren van lijsten uit niet-vertrouwde bronnen {#block-field-updates-during-list-import-from-untrusted-sources}

U kunt de gegevens in sommige lijsten meer vertrouwen dan in andere. Soms hebt u twijfelachtige gegevens en wilt u deze gebruiken als het veld leeg is, maar niet als er een bestaande waarde is. U kunt dit bereiken door veldupdates op sleutelvelden te blokkeren.

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

## Veldupdates blokkeren vanuit niet-vertrouwde bronnen {#blocking-field-updates-from-untrusted-sources}

1. Ga naar de **[!UICONTROL Admin]** gebied.

   ![](assets/blocking-field-updates-from-untrusted-sources-1.png)

1. Klik op **[!UICONTROL Field Management]**.

   ![](assets/blocking-field-updates-from-untrusted-sources-2.png)

1. Zoek het gewenste veld, selecteer het en onder **[!UICONTROL Field Actions]**, klikt u op **[!UICONTROL Block Field Updates]**.

   ![](assets/blocking-field-updates-from-untrusted-sources-3.png)

1. Controleren **[!UICONTROL List Import untrusted source]** en klik op **[!UICONTROL Apply]**.

   ![](assets/blocking-field-updates-from-untrusted-sources-4.png)

>[!TIP]
>
>U kunt velden veilig houden voor alle lijsten, vertrouwd en niet-vertrouwd, door ook **[!UICONTROL List Import trusted source]**.

Herhaal bovenstaande stappen voor alle andere velden die u wilt beveiligen tegen niet-vertrouwde lijsten.

## Importeren van niet-vertrouwde lijsten uitvoeren {#running-an-untrusted-list-import}

1. Zorg ervoor dat u **[!UICONTROL Untrusted]** als u wilt dat alle velden die u in de vorige stap hebt ingesteld, veilig zijn.

   ![](assets/blocking-field-updates-from-untrusted-sources-5.png)

Voor gedetailleerde instructies over het importeren van lijsten raadpleegt u [Een lijst met personen importeren](/help/marketo/getting-started/quick-wins/import-a-list-of-people.md).

Mooi werk! Nu weet u hoe u sleutelvelden veilig kunt houden voor niet-vertrouwde lijsten.
