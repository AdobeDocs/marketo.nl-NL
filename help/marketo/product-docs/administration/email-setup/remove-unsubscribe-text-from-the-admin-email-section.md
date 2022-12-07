---
unique-page-id: 2360245
description: Tekst voor abonnement verwijderen uit de e-mailsectie Admin - Marketo Docs - Productdocumentatie
title: Tekst voor abonnement verwijderen uit de e-mailsectie voor beheerders
exl-id: 2961a9b6-8b35-4227-bf8a-a07b2664a6c4
source-git-commit: 2776969be44ba1a3d795e99986d10cf0470fb9e9
workflow-type: tm+mt
source-wordcount: '165'
ht-degree: 0%

---

# Tekst voor abonnement verwijderen uit de e-mailsectie voor beheerders {#remove-unsubscribe-text-from-the-admin-email-section}

De enige reden waarom u het afmelden van inhoud uit het gebied &quot;Admin > E-mail&quot;zou moeten ooit volledig verwijderen is als u verkiest om de afmeldingsverbinding in de e-mailmalplaatjes zelf te bouwen. Het tekstvak heeft een validatie die het niet mogelijk maakt om zonder inhoud op te slaan. U kunt dit omzeilen door een kleine HTML-opmerking toe te voegen. De opmerking HTML wordt niet weergegeven in de e-mailclient, omdat deze de e-mail in HTML weergeeft en de opmerkingen worden weggelaten. Zo doe je het.

1. Ga naar de **Beheer** gebied.

   ![](assets/remove-unsubscribe-text-from-the-admin-email-section-1.png)

1. Klikken **E-mail**.

   ![](assets/remove-unsubscribe-text-from-the-admin-email-section-2.png)

1. Selecteer alle tekst en druk op **Verwijderen** toets.

   >[!CAUTION]
   >
   >Kopieer of plak deze vóór het verwijderen in een tekstdocument als een back-up.

1. Type in `<!--This is a comment -->`.

   ![](assets/remove-unsubscribe-text-from-the-admin-email-section-3.png)

1. Klikken **Wijzigingen opslaan**.

   ![](assets/remove-unsubscribe-text-from-the-admin-email-section-4.png)

>[!NOTE]
>
>Voor de **Tekst afmelden** u moet één teken toevoegen. Gebruik een streepje of een punt.
