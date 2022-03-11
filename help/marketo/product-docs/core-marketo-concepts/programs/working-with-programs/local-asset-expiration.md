---
description: Verlopen lokale middelen - Marketo-documenten - productdocumentatie
title: Vervaldatum van lokale middelen
exl-id: 603e3eee-0531-4139-a8f5-279831ad011f
source-git-commit: 48a49faa6a1fde1e9ac391c2bf0800123f6a5bac
workflow-type: tm+mt
source-wordcount: '237'
ht-degree: 0%

---

# Vervaldatum van lokale middelen {#local-asset-expiration}

Stel een vervaldatum/-tijd in om de publicatie van bestemmingspagina&#39;s ongedaan te maken, triggercampagnes te deactiveren of herhalende batchcampagnes te stoppen.

## Vervalmachtiging voor het schema van subsidies {#grant-schedule-asset-expiration-permission}

Voordat u de vervaldatum van middelen kunt plannen, moet voor uw Marketo-rol de juiste machtiging zijn ingeschakeld.

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

1. In de [!UICONTROL Admin] gebied, klikken **[!UICONTROL Users & Roles]**.

   ![](assets/local-asset-expiration-1.png)

1. Klik op de knop **[!UICONTROL Roles]** selecteert u de gebruiker aan wie u toegang wilt verlenen en klikt u vervolgens op **[!UICONTROL Edit Role]**.

   ![](assets/local-asset-expiration-2.png)

1. Onder [!UICONTROL Access Marketing Activities], selecteert u **[!UICONTROL Schedule Local Asset Expiration]** en klik op **[!UICONTROL Save]**.

   ![](assets/local-asset-expiration-3.png)

## Een vervaldatum instellen {#set-an-expiration-date}

1. Klik met de rechtermuisknop op het gewenste programma en selecteer **[!UICONTROL Set Local Asset Expiration]**.

   ![](assets/local-asset-expiration-4.png)

1. Controleer de elementen waarvoor u een vervaldatum wilt instellen en klik vervolgens op **[!UICONTROL Set Expiration]**.

   ![](assets/local-asset-expiration-5.png)

1. Kies een vervaldatum.

   ![](assets/local-asset-expiration-6.png)

1. Stel een tijd in. U moet een tijd minstens 20 minuten in de toekomst plannen (vergeet niet om AM/PM in te gaan). Klikken **[!UICONTROL Confirm]** wanneer gereed.

   ![](assets/local-asset-expiration-7.png)

>[!NOTE]
>
>* Als u een bestaande vervaldatum wilt bewerken, controleert u gewoon het element of de elementen en klikt u op **[!UICONTROL Set Expiration]**.
>* Nadat een element is verlopen, wordt het niet meer weergegeven op het raster Verlopen. Het raster geeft alleen gepubliceerde landingspagina&#39;s, actieve triggercampagnes en terugkerende batchcampagnes weer.
>* Geplande vervaldatums worden verwijderd als het element naar een ander programma wordt verplaatst.


## Een vervaldatum verwijderen {#remove-an-expiration-date}

1. Als u een vervaldatum wilt verwijderen, controleert u de elementen en klikt u op **[!UICONTROL Remove Expiration]**.

   ![](assets/local-asset-expiration-8.png)

1. Controleer de elementen die worden beïnvloed en klik vervolgens op **[!UICONTROL Confirm]**.

   ![](assets/local-asset-expiration-9.png)

>[!NOTE]
>
>Vervaldatums die in de toekomst minder dan 15 minuten bedragen, kunnen niet worden verwijderd. Als u de vervaldatum wilt &quot;verwijderen&quot;, moet u wachten tot het element is verlopen en het vervolgens opnieuw goedkeuren of opnieuw activeren.
