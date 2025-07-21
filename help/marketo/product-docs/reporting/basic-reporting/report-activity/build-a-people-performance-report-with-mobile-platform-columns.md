---
unique-page-id: 2951220
description: Bouw een Rapport van de Prestaties van Mensen met Mobiele Kolommen van het Platform - Marketo Docs - de Documentatie van het Product
title: Bouw een Rapport van de Prestaties van Mensen met Mobiele Kolommen van het Platform
exl-id: 93fb6cb4-a6ca-4b35-b8bf-c6657eb9343b
feature: Reporting
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '255'
ht-degree: 1%

---

# Bouw een Rapport van de Prestaties van Mensen met Mobiele Kolommen van het Platform {#build-a-people-performance-report-with-mobile-platform-columns}

Ga als volgt te werk om een People Performance Report met kolommen voor mobiele platforms (iOS/Android) te maken.

## Mobiele slimme lijsten maken {#create-mobile-smart-lists}

1. Ga naar **[!UICONTROL Marketing Activities]** .

   ![](assets/ma.png)

1. Kies een programma.

   ![](assets/two-1.png)

1. Selecteer onder **[!UICONTROL New]** de optie **[!UICONTROL New Local Asset]** .

   ![](assets/three-1.png)

1. Klik op **[!UICONTROL Smart List]**.

   ![](assets/four-1.png)

1. Typ een naam en klik op **[!UICONTROL Create]** .

   ![](assets/five-1.png)

1. Zoek en sleep het filter [!UICONTROL Opened Email] naar het canvas.

   ![](assets/six-1.png)

1. E-mail instellen op **[!UICONTROL is any]** .

   ![](assets/seven.png)

1. Klik op **[!UICONTROL Add Constraint]** en selecteer **[!UICONTROL Platform]** .

   ![](assets/eight.png)

   >[!TIP]
   >
   >In dit voorbeeld hebben we het filter [!UICONTROL Opened Email] gebruikt. U kunt het filter [!UICONTROL Clicked Email] ook gebruiken aangezien het de beperking van het Platform heeft.

1. Stel [!UICONTROL Platform] in op **[!UICONTROL iOS]** .

   ![](assets/nine.png)

   >[!NOTE]
   >
   >Ten minste één persoon moet een e-mailbericht hebben geopend op een iOS-apparaat, anders kan Marketo dit niet vinden. Als dit niet het geval is, kunt u het handmatig invoeren en opslaan.

   Maak nu een tweede slimme lijst voor het Android-platform. Ga vervolgens naar de volgende sectie.

## Een prestatierapport voor mensen maken {#create-a-people-performance-report}

1. Selecteer onder Marketingactiviteiten het programma waarin uw **[!UICONTROL iOS]** - en **[!UICONTROL Android]** slimme lijsten zijn opgeslagen.

   ![](assets/ten.png)

1. Selecteer onder **[!UICONTROL New]** de optie **[!UICONTROL New Local Asset]** .

   ![](assets/eleven.png)

1. Klik op **[!UICONTROL Report]**.

   ![](assets/twelve.png)

1. Stel Type in op **[!UICONTROL People Performance]** .

   ![](assets/thirteen.png)

1. Klik op **[!UICONTROL Create]**.

   ![](assets/fourteen.png)

   Je doet het geweldig! Nu over naar de volgende sectie.

## Mobiele slimme lijsten toevoegen als kolommen {#add-mobile-smart-lists-as-columns}

1. Klik in het rapport dat u zojuist hebt gemaakt op **[!UICONTROL Setup]** en sleep **[!UICONTROL Custom Columns]** naar het canvas.

   ![](assets/fifteen.png)

   >[!NOTE]
   >
   >Standaard wordt in het People Performance Report gekeken naar de laatste 7 dagen. U kunt de tijdlijn wijzigen door erop te dubbelklikken.

1. Zoek en selecteer de slimme lijsten die u eerder hebt gemaakt en klik op **[!UICONTROL Apply]** .

   ![](assets/sixteen.png)

1. Klik op **[!UICONTROL Report]** om het rapport uit te voeren en de gegevens weer te geven.

   ![](assets/seventeen.png)

   Mooi cool, toch? Echt waar!
