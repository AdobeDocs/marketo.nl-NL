---
unique-page-id: 37355758
description: Leden toevoegen aan een gebeurtenisprogramma - Marketo Docs - Productdocumentatie
title: Leden toevoegen aan een gebeurtenisprogramma
exl-id: 05bd4807-3ab8-452d-a389-b22477cf7445
feature: Events
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '165'
ht-degree: 0%

---

# Leden toevoegen aan een gebeurtenisprogramma {#adding-members-to-an-event-program}

Dit artikel is alleen van toepassing op gebruikers die gebruikmaken van Gebeurtenishoofdlettergebruik of Gebeurtenisdoelen.

>[!CAUTION]
>
>Als u een lijst met personen rechtstreeks in een gebeurtenisprogramma importeert, worden deze records niet meegeteld in werkelijke registraties in het rapport Goal Tracking en in het rapport Event Cap Progression. Volg de onderstaande instructies om ervoor te zorgen dat uw administratie wordt geteld.

1. Creeer en [ voeg mensen aan een statische lijst ](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/static-lists/create-a-static-list.md) toe.

1. [ creeer een slimme campagne ](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/create-a-new-smart-campaign.md).

1. Zoek in de slimme lijst van de slimme campagne die u in Stap twee hebt gemaakt het filter **[!UICONTROL Member of List]** en voeg dit toe.

   ![](assets/three.png)

1. Zoek en selecteer de lijst die u in Stap één hebt gemaakt.

   ![](assets/four.png)

1. Zoek in de stroom de **[!UICONTROL Change Program Status]** flowstap en voeg deze toe.

   ![](assets/five.png)

1. Zoek en selecteer uw gebeurtenisprogramma.

   ![](assets/six.png)

1. Kies de gewenste status.

   ![](assets/seven.png)

1. Klik op het tabblad [!UICONTROL Schedule] op **[!UICONTROL Run Once]** .

   ![](assets/eight.png)

1. Selecteer **[!UICONTROL Run Now]** en klik op **[!UICONTROL Run]** .

   ![](assets/nine.png)

1. Nadat de slimme campagnelooppas, worden de leden toegevoegd aan het programma en zullen in het Volgen van het Goal en de berekeningen van de Progressie van het Uiteinde van de Gebeurtenis tellen.
