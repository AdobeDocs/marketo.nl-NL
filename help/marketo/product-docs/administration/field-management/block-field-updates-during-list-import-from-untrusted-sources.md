---
unique-page-id: 2360335
description: Veldupdates blokkeren tijdens het importeren van lijsten uit niet-vertrouwde bronnen - Marketo Docs - Productdocumentatie
title: Veldupdates blokkeren tijdens het importeren van lijsten uit niet-vertrouwde bronnen
exl-id: 0fd59f0c-6cb9-442c-937b-da18a4466873
source-git-commit: 2776969be44ba1a3d795e99986d10cf0470fb9e9
workflow-type: tm+mt
source-wordcount: '206'
ht-degree: 0%

---

# Veldupdates blokkeren tijdens het importeren van lijsten uit niet-vertrouwde bronnen {#block-field-updates-during-list-import-from-untrusted-sources}

U kunt de gegevens in sommige lijsten meer vertrouwen dan in andere. Soms hebt u twijfelachtige gegevens en wilt u deze gebruiken als het veld leeg is, maar niet als er een bestaande waarde is. U kunt dit bereiken door veldupdates op sleutelvelden te blokkeren.

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

## Veldupdates blokkeren vanuit niet-vertrouwde bronnen {#blocking-field-updates-from-untrusted-sources}

1. Ga naar de **Beheer** gebied.

   ![](assets/blocking-field-updates-from-untrusted-sources-1.png)

1. Klikken **Veldbeheer**.

   ![](assets/blocking-field-updates-from-untrusted-sources-2.png)

1. Zoek het gewenste veld, selecteer het en onder **Veldhandelingen**, klikt u op **Veldupdates blokkeren**.

   ![](assets/blocking-field-updates-from-untrusted-sources-3.png)

1. Controleren **Niet-vertrouwde bron importeren** en klik op **Toepassen**.

   ![](assets/blocking-field-updates-from-untrusted-sources-4.png)

>[!TIP]
>
>U kunt velden veilig houden voor alle lijsten, vertrouwd en niet-vertrouwd, door ook **Vertrouwde bron importeren**.

Herhaal bovenstaande stappen voor alle andere velden die u wilt beveiligen tegen niet-vertrouwde lijsten.

## Importeren van niet-vertrouwde lijsten uitvoeren {#running-an-untrusted-list-import}

1. Zorg ervoor dat u **Onvertrouwd** als u wilt dat alle velden die u in de vorige stap hebt ingesteld, veilig zijn.

   ![](assets/blocking-field-updates-from-untrusted-sources-5.png)

Voor gedetailleerde instructies over het importeren van lijsten raadpleegt u [Een lijst met personen importeren](/help/marketo/getting-started/quick-wins/import-a-list-of-people.md).

Mooi werk! Nu weet u hoe u sleutelvelden veilig kunt houden voor niet-vertrouwde lijsten.
