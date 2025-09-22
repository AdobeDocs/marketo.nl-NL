---
unique-page-id: 2360245
description: Tekst voor abonnement verwijderen uit de e-mailsectie Admin - Marketo Docs - Productdocumentatie
title: Tekst voor abonnement verwijderen uit de e-mailsectie voor beheerders
exl-id: 2961a9b6-8b35-4227-bf8a-a07b2664a6c4
feature: Email Setup
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '158'
ht-degree: 1%

---

# Tekst voor abonnement verwijderen uit de sectie Beheer > E-mail {#remove-unsubscribe-text-from-the-admin-email-section}

De enige reden waarom u het afmelden van inhoud ooit volledig zou moeten verwijderen uit **[!UICONTROL Admin]** > **[!UICONTROL Email]** gebied is als u verkiest om de unsubscribe verbinding in de e-mailmalplaatjes zelf te bouwen. Het tekstvak heeft een validatie die het niet mogelijk maakt om zonder inhoud op te slaan. U kunt dit omzeilen door een kleine HTML-opmerking toe te voegen. De HTML-opmerking wordt niet weergegeven in de e-mailclient, omdat deze de e-mail in HTML rendert en de opmerkingen worden weggelaten. Zo doe je het.

1. Ga naar het **[!UICONTROL Admin]** -gebied.

   ![](assets/remove-unsubscribe-text-from-the-admin-email-section-1.png)

1. Klik op **[!UICONTROL Email]**.

   ![](assets/remove-unsubscribe-text-from-the-admin-email-section-2.png)

1. Selecteer alle tekst en druk op **[!UICONTROL Delete]** .

   >[!CAUTION]
   >
   >Kopieer of plak deze vóór het verwijderen in een tekstdocument als een back-up.

1. Typ in `<!--This is a comment -->` .

   ![](assets/remove-unsubscribe-text-from-the-admin-email-section-3.png)

1. Klik op **[!UICONTROL Save Changes]**.

   ![](assets/remove-unsubscribe-text-from-the-admin-email-section-4.png)

>[!NOTE]
>
>Voor **Unsubscribe Tekst** moet u één enkel karakter toevoegen. Gebruik een streepje of een punt.
