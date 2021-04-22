---
unique-page-id: 2360245
description: Tekst voor abonnement verwijderen uit de e-mailsectie Admin - Marketo Docs - Productdocumentatie
title: Tekst voor abonnement verwijderen uit de e-mailsectie voor beheerders
exl-id: 2961a9b6-8b35-4227-bf8a-a07b2664a6c4
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '164'
ht-degree: 0%

---

# Tekst voor afmelden verwijderen uit de sectie {#remove-unsubscribe-text-from-the-admin-email-section} voor e-mailadressen van beheerders

De enige reden waarom u het afmelden van inhoud uit het gebied &quot;Admin > E-mail&quot;zou moeten ooit volledig verwijderen is als u verkiest om de afmeldingsverbinding in de e-mailmalplaatjes zelf te bouwen. Het tekstvak heeft een validatie die het niet mogelijk maakt om zonder inhoud op te slaan. U kunt dit omzeilen door een kleine HTML-opmerking toe te voegen. De HTML-opmerking wordt niet weergegeven in de e-mailclient, omdat deze de e-mail in HTML weergeeft en de opmerkingen worden weggelaten. Zo doe je het.

1. Ga naar **Admin** en klik **E-mail**.

   ![](assets/image2016-8-26-13-3a57-3a9.png)

1. Selecteer alle tekst en druk op **Delete**.

   >[!CAUTION]
   >
   >Kopieer of plak deze vóór het verwijderen in een tekstdocument als een back-up.

1. Typ in `<!--This is a comment -->`.

   ![](assets/image2016-8-26-13-3a53-3a15.png)

1. Klik **Wijzigingen opslaan**.

   ![](assets/image2016-8-26-13-3a59-3a40.png)

>[!NOTE]
>
>Voor **Unsubscribe Text** moet u één enkel karakter toevoegen. Gebruik een streepje of een punt.
