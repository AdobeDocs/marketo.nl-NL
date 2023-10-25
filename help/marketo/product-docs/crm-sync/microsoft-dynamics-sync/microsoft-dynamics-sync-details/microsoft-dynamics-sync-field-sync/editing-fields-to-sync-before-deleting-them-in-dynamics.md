---
description: Te synchroniseren velden bewerken voordat deze in Dynamics worden verwijderd - Marketo Docs - Productdocumentatie
title: Te synchroniseren velden bewerken voordat deze worden verwijderd in Dynamiek
exl-id: 6fa9f6c0-c69d-478f-b333-13a5c910f577
feature: Microsoft Dynamics
source-git-commit: 2403ae0f1fdca3b8238f3f59e2a3b94129deb301
workflow-type: tm+mt
source-wordcount: '199'
ht-degree: 0%

---

# Te synchroniseren velden bewerken voordat deze worden verwijderd in Dynamiek {#editing-fields-to-sync-before-deleting-them-in-dynamics}

Soms wilt u wellicht velden verwijderen in Dynamiek. Marketo Engage houdt de veldlijst bij als een referentie waarop de synchronisatie wordt gebaseerd. Als een veld wordt verwijderd in Dynamiek terwijl de synchronisatie is ingeschakeld, kunnen er fouten optreden bij de synchronisatie. Volg de onderstaande stappen voordat u velden verwijdert.

1. Klik in Marketo op **[!UICONTROL Admin]**.

   ![](assets/sync-before-deleting-them-in-dynamics-1.png)

1. Klik onder Integratie op **[!UICONTROL Microsoft Dynamics]**.

   ![](assets/sync-before-deleting-them-in-dynamics-2.png)

1. Klik op **[!UICONTROL Disable Sync]**.

   ![](assets/sync-before-deleting-them-in-dynamics-3.png)

1. Meld u aan bij Dynamiek en verwijder de gewenste velden in een nieuw tabblad in uw browser.

1. Terug in Marketo, onder Microsoft Dynamics, klik **[!UICONTROL Edit]** naast &quot;Stap 2: Selecteer te synchroniseren velden.&quot;

   ![](assets/sync-before-deleting-them-in-dynamics-4.png)

1. Bekijk de velden en klik op **[!UICONTROL Save]**.

   ![](assets/sync-before-deleting-them-in-dynamics-5.png)

>[!CAUTION]
>
>Klikken **[!UICONTROL Save]** is vereist om het bijgewerkte schema voor de synchronisatie op te slaan, zelfs als er geen wijzigingen zijn aangebracht.

>[!NOTE]
>
>Als de synchronisatie niet wordt gestopt voordat een veld in Dynamiek wordt verwijderd, kan de synchronisatie fouten tegenkomen. Als dit het geval is, wordt de synchronisatie gestopt. Voordat u het programma kunt hervatten, moet de Marketo Admin eerst controleren of Velden voor synchronisatie zijn geselecteerd (zoals hierboven beschreven) en vervolgens op **[!UICONTROL Save]** voor de synchronisatie om de schemaveranderingen goed te keuren.

Vergeet niet de synchronisatie in te schakelen nadat de wijzigingen zijn opgeslagen.
