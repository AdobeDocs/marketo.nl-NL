---
unique-page-id: 2360245
description: Verwijder de standaard afgebroken inhoud uit de e-mail van Admin door een HTML-opmerking te gebruiken wanneer u de koppeling naar sjablonen maakt.
title: Tekst voor abonnement verwijderen
exl-id: 2961a9b6-8b35-4227-bf8a-a07b2664a6c4
feature: Email Setup
source-git-commit: 9c4f0d0a43d3ef06132d827b605b9e42de712e22
workflow-type: tm+mt
source-wordcount: '150'
ht-degree: 1%

---

# Tekst voor abonnement verwijderen {#remove-unsubscribe-text}

De enige reden dat u het abonnement op inhoud uit het gebied **[!UICONTROL Admin]** > **[!UICONTROL Email]** moet verwijderen, is dat u de koppeling voor het afmelden van abonnementen zelf wilt maken in de e-mailsjablonen. Het tekstvak heeft een validatie die het niet mogelijk maakt om zonder inhoud op te slaan. U kunt dit omzeilen door een kleine HTML-opmerking toe te voegen. De HTML-opmerking wordt niet weergegeven in de e-mailclient, omdat deze de e-mail in HTML rendert en de opmerkingen worden weggelaten.

1. Ga naar het **[!UICONTROL Admin]** -gebied.

   ![](assets/remove-unsubscribe-text-from-the-admin-email-section-1.png)

1. Klik op **[!UICONTROL Email]** .

   ![](assets/remove-unsubscribe-text-from-the-admin-email-section-2.png)

1. Selecteer alle tekst en druk op **[!UICONTROL Delete]** .

   >[!CAUTION]
   >
   >Kopieer of plak deze vóór het verwijderen in een tekstdocument als een back-up.

1. Typ in `<!--This is a comment -->` .

   ![](assets/remove-unsubscribe-text-from-the-admin-email-section-3.png)

1. Klik op **[!UICONTROL Save Changes]** .

   ![](assets/remove-unsubscribe-text-from-the-admin-email-section-4.png)

>[!NOTE]
>
>Voor **Unsubscribe Tekst** moet u één enkel karakter toevoegen. Gebruik een streepje of een punt.
