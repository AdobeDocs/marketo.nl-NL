---
unique-page-id: 37355758
description: Leden toevoegen aan een gebeurtenisprogramma - Marketo Docs - Productdocumentatie
title: Leden toevoegen aan een gebeurtenisprogramma
translation-type: tm+mt
source-git-commit: ed83438ae5660d172e845f25c4d72d599574bd91
workflow-type: tm+mt
source-wordcount: '177'
ht-degree: 0%

---


# Leden toevoegen aan een gebeurtenisprogramma {#adding-members-to-an-event-program}

Dit artikel is alleen van toepassing op gebruikers die gebruikmaken van Gebeurtenishoofdlettergebruik of Gebeurtenisdoelen.

>[!CAUTION]
>
>Als u een lijst met personen rechtstreeks in een gebeurtenisprogramma importeert, worden deze records niet meegeteld in werkelijke registraties in het rapport Goal Tracking en in het rapport Event Cap Progression. Volg de onderstaande instructies om ervoor te zorgen dat uw administratie wordt geteld.

1. Creeer en [voeg mensen aan een statische lijst](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/static-lists/create-a-static-list.md) toe.

1. [Maak een slimme campagne](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/create-a-new-smart-campaign.md).

1. In de Slimme Lijst van de Slimme Campagne u in Stap Twee creeerde, vind en voeg **Lid van de filter van List** toe.

   ![](assets/three.png)

1. Zoek en selecteer de lijst die u in Stap één hebt gemaakt.

   ![](assets/four.png)

1. In de Stroom, vind en voeg **De Status van het Programma van de Verandering** debietstap toe.

   ![](assets/five.png)

1. Zoek en selecteer uw gebeurtenisprogramma.

   ![](assets/six.png)

1. Kies de gewenste status.

   ![](assets/seven.png)

1. Klik op het tabblad Schema op **Eenmaal uitvoeren**.

   ![](assets/eight.png)

1. Selecteer **Nu uitvoeren** en klik **Run**.

   ![](assets/nine.png)

1. Nadat de slimme campagnelooppas, worden de leden toegevoegd aan het programma en zullen in Goal Tracking en de berekeningen van de Progressie van het Uiteinde van de Gebeurtenis tellen.
