---
description: Marketo Unsubscribe Check - Marketo Docs - Productdocumentatie
title: Marketo Unsubscribe Check
exl-id: 3c242d04-cf6c-466b-9bcd-e77c6d97d308
feature: Sales Insight Actions
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '128'
ht-degree: 0%

---

# [!UICONTROL Marketo Unsubscribe Check] {#marketo-unsubscribe-check}

In [!UICONTROL Marketo Unsubscribe Check] wordt de verbinding van uw team met Marketo gebruikt om te voorkomen dat e-mailberichten worden verzonden naar personen die zich niet hebben geabonneerd in het beheersysteem voor leads van Marketo. Wanneer een verkoopgebruiker een e-mail verzendt met [!DNL Marketo Sales] , wordt een API-aanroep naar Marketo uitgevoerd om te controleren of het e-mailadres niet is geabonneerd. Als dit het geval is, blokkeren we het verzenden van de e-mail.

>[!NOTE]
>
>**Vereiste Bevoegdheden Admin**

## De functie inschakelen {#turning-it-on}

1. Klik op het tandwielpictogram en selecteer **[!UICONTROL Settings]** .

   ![](assets/marketo-unsubscribe-check-1.png)

1. Klik onder [!UICONTROL Admin Settings] op **[!UICONTROL Unsubscribes]** .

   ![](assets/marketo-unsubscribe-check-2.png)

1. Klik op de tab **[!UICONTROL Integrations]** . Klik in de sectie [!UICONTROL Marketo Unsubscribe Check] op de schuifregelaar om de controle te activeren.

   ![](assets/marketo-unsubscribe-check-3.png)

## Informatie over dingen {#things-to-know}

Afmeldingscontrole van Marketo...

* telt niet mee voor uw API-limieten
* Hiervoor moet een Marketo-verbinding tot stand worden gebracht
* Is een globale instelling
* Hiermee blokkeert u e-mailberichten die worden verzonden vanuit de webtoepassing, e-mailclients en [!DNL Salesforce]
