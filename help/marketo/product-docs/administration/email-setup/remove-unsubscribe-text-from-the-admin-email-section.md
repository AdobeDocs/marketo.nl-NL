---
unique-page-id: 2360245
description: Tekst voor abonnement verwijderen uit de e-mailsectie Admin - Marketo Docs - Productdocumentatie
title: Tekst voor abonnement verwijderen uit de e-mailsectie voor beheerders
exl-id: 2961a9b6-8b35-4227-bf8a-a07b2664a6c4
feature: Email Setup
source-git-commit: d635fbd4807890266429d4a257cf7d6588736bb5
workflow-type: tm+mt
source-wordcount: '158'
ht-degree: 1%

---

# Tekst voor abonnement verwijderen uit de sectie Beheer > E-mail {#remove-unsubscribe-text-from-the-admin-email-section}

De enige reden waarom u de niet-geabonneerde inhoud ooit volledig uit de **[!UICONTROL Admin]** > **[!UICONTROL Email]** in dit gebied is het geval als u ervoor kiest om de koppeling voor afmelden op te nemen in de e-mailsjablonen zelf. Het tekstvak heeft een validatie die het niet mogelijk maakt om zonder inhoud op te slaan. U kunt dit omzeilen door een kleine HTML-opmerking toe te voegen. De opmerking HTML wordt niet weergegeven in de e-mailclient, omdat deze de e-mail in HTML weergeeft en de opmerkingen worden weggelaten. Zo doe je het.

1. Ga naar de **[!UICONTROL Admin]** gebied.

   ![](assets/remove-unsubscribe-text-from-the-admin-email-section-1.png)

1. Klik op **[!UICONTROL Email]**.

   ![](assets/remove-unsubscribe-text-from-the-admin-email-section-2.png)

1. Selecteer alle tekst en druk op de knop **[!UICONTROL Delete]** toets.

   >[!CAUTION]
   >
   >Kopieer of plak deze vóór het verwijderen in een tekstdocument als een back-up.

1. Type in `<!--This is a comment -->`.

   ![](assets/remove-unsubscribe-text-from-the-admin-email-section-3.png)

1. Klik op **[!UICONTROL Save Changes]**.

   ![](assets/remove-unsubscribe-text-from-the-admin-email-section-4.png)

>[!NOTE]
>
>Voor de **Tekst afmelden** u moet één teken toevoegen. Gebruik een streepje of een punt.
