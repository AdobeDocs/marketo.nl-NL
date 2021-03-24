---
description: Te synchroniseren velden bewerken voordat deze in Dynamics worden verwijderd - Marketo Docs - Productdocumentatie
title: Te synchroniseren velden bewerken voordat deze worden verwijderd in Dynamiek
translation-type: tm+mt
source-git-commit: ed9399396c82a3b2fb93c83ffdaa1dc7b0827306
workflow-type: tm+mt
source-wordcount: '207'
ht-degree: 0%

---


# Te synchroniseren velden bewerken voordat deze worden verwijderd in dynamiek {#editing-fields-to-sync-before-deleting-them-in-dynamics}

Soms wilt u wellicht velden verwijderen in Dynamiek. Marketo houdt de veldlijst als een referentie waarop de synchronisatie wordt gebaseerd. Als een veld wordt verwijderd in Dynamiek terwijl de synchronisatie is ingeschakeld, kunnen er fouten optreden bij de synchronisatie. Volg onderstaande stappen voordat u velden verwijdert.

1. Klik in Marketo op **Admin**.

   ![](assets/sync-before-deleting-them-in-dynamics-1.png)

1. Klik onder Integratie op **Microsoft Dynamics**.

   ![](assets/sync-before-deleting-them-in-dynamics-2.png)

1. Klik **Sync uitschakelen**.

   ![](assets/sync-before-deleting-them-in-dynamics-3.png)

1. Meld u aan bij Dynamiek en verwijder de gewenste velden in een nieuw tabblad in uw browser.

1. Terug in Marketo, onder de Dynamica van Microsoft, klik **geef** naast &quot;Stap 2 uit: Selecteer te synchroniseren velden.&quot;

   ![](assets/sync-before-deleting-them-in-dynamics-4.png)

1. Controleer de velden en klik op **Opslaan**.

   ![](assets/sync-before-deleting-them-in-dynamics-5.png)

>[!CAUTION]
>
>Als u op **Opslaan** klikt, moet u het bijgewerkte schema voor de synchronisatie opslaan, zelfs als er geen wijzigingen zijn aangebracht.

>[!NOTE]
>
>Als de synchronisatie niet wordt gestopt voordat een veld in Dynamiek wordt verwijderd, kan de synchronisatie fouten tegenkomen. Als dit het geval is, wordt de synchronisatie gestopt. Alvorens te hervatten, zou Admin van de Marketo &quot;Uitgezochte Te synchroniseren Gebieden moeten herzien (hierboven besproken) en **sparen** klikken om de schemaveranderingen goed te keuren.

Vergeet niet de synchronisatie in te schakelen nadat de wijzigingen zijn opgeslagen.
