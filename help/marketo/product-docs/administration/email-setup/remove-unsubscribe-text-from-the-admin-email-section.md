---
unique-page-id: 2360245
description: Tekst voor abonnement verwijderen uit de sectie "Admin -> Email" - Marketo Docs - Productdocumentatie
title: Tekst voor abonnement verwijderen uit de sectie "Beheer -> E-mail"
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '164'
ht-degree: 0%

---


# Tekst voor abonnement verwijderen uit de sectie &quot;Beheer -> E-mail&quot; {#remove-unsubscribe-text-from-the-admin-email-section}

De enige reden waarom u het afmelden van inhoud uit het gebied &quot;Admin > E-mail&quot;zou moeten ooit volledig verwijderen is als u verkiest om de afmeldingsverbinding in de e-mailmalplaatjes zelf te bouwen. Het tekstvak heeft een validatie die het niet mogelijk maakt om zonder inhoud op te slaan. U kunt dit omzeilen door een kleine HTML-opmerking toe te voegen. De HTML-opmerking wordt niet weergegeven in de e-mailclient, omdat deze de e-mail in HTML weergeeft en de opmerkingen worden weggelaten. Zo doe je het.

1. Ga naar **Beheer** en klik op **E-mail**.

   ![](assets/image2016-8-26-13-3a57-3a9.png)

1. Selecteer alle tekst en druk op **Delete **toets.

   >[!CAUTION]
   >
   >Kopieer of plak deze vóór het verwijderen in een tekstdocument als een back-up.

1. Typ in **<!--This is a comment -->**.

   ![](assets/image2016-8-26-13-3a53-3a15.png)

1. Klik op Wijzigingen **opslaan**.

   ![](assets/image2016-8-26-13-3a59-3a40.png)

>[!NOTE]
>
>Voor **Unsubscribe Tekst **u moet één enkel karakter toevoegen. Gebruik een streepje of een punt.

