---
unique-page-id: 2360335
description: Veldupdates blokkeren tijdens het importeren van lijsten uit niet-vertrouwde bronnen - Marketo Docs - Productdocumentatie
title: Veldupdates blokkeren tijdens het importeren van lijsten uit niet-vertrouwde bronnen
exl-id: 0fd59f0c-6cb9-442c-937b-da18a4466873
feature: Field Management
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '188'
ht-degree: 0%

---

# Veldupdates blokkeren tijdens het importeren van lijsten uit niet-vertrouwde bronnen {#block-field-updates-during-list-import-from-untrusted-sources}

U kunt de gegevens in sommige lijsten meer vertrouwen dan in andere. Soms hebt u twijfelachtige gegevens en wilt u deze gebruiken als het veld leeg is, maar niet als er een bestaande waarde is. U kunt dit bereiken door veldupdates op sleutelvelden te blokkeren.

>[!NOTE]
>
>**Vereiste Bevoegdheden Admin**

## Veldupdates blokkeren vanuit niet-vertrouwde bronnen {#blocking-field-updates-from-untrusted-sources}

1. Ga naar het **[!UICONTROL Admin]** -gebied.

   ![](assets/blocking-field-updates-from-untrusted-sources-1.png)

1. Klik op **[!UICONTROL Field Management]**.

   ![](assets/blocking-field-updates-from-untrusted-sources-2.png)

1. Zoek het gewenste veld, selecteer het en klik onder **[!UICONTROL Field Actions]** op **[!UICONTROL Block Field Updates]** .

   ![](assets/blocking-field-updates-from-untrusted-sources-3.png)

1. Controleer **[!UICONTROL List Import untrusted source]** en klik op **[!UICONTROL Apply]** .

   ![](assets/blocking-field-updates-from-untrusted-sources-4.png)

>[!TIP]
>
>U kunt velden veilig houden voor alle lijsten, vertrouwd en niet-vertrouwd, door ook **[!UICONTROL List Import trusted source]** te controleren.

Herhaal bovenstaande stappen voor alle andere velden die u wilt beveiligen tegen niet-vertrouwde lijsten.

## Importeren van niet-vertrouwde lijsten uitvoeren {#running-an-untrusted-list-import}

1. Wanneer u de lijst importeert, moet u **[!UICONTROL Untrusted]** selecteren als u wilt dat alle velden die u in de vorige stap hebt ingesteld, veilig zijn.

   ![](assets/blocking-field-updates-from-untrusted-sources-5.png)

Voor gedetailleerde instructies bij het invoeren van lijsten, zie [ een Lijst van Mensen ](/help/marketo/getting-started/quick-wins/import-a-list-of-people.md) invoeren.

Mooi werk! Nu weet u hoe u sleutelvelden veilig kunt houden voor niet-vertrouwde lijsten.
