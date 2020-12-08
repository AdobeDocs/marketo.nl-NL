---
unique-page-id: 18317340
description: Marketo Unsubscribe Check - Marketo Docs - Productdocumentatie
title: Marketo Unsubscribe-controle
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '147'
ht-degree: 0%

---


# Marketo Unsubscribe-controle {#marketo-unsubscribe-check}

Met de controle Afmelden bij Marketo wordt de verbinding van uw team met Marketo gebruikt om te voorkomen dat e-mails worden verzonden naar personen die niet zijn geabonneerd in het Lead Management-systeem van Marketo. Wanneer een verkoopgebruiker een e-mail verzendt met Sales Connect, wordt een API-aanroep naar Marketo uitgevoerd om te controleren of het e-mailadres niet is geabonneerd. Als dit het geval is, blokkeren we het verzenden van de e-mail.

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

## Deze inschakelen {#turning-it-on}

1. Klik in de webtoepassing op het tandwielpictogram en selecteer **Instellingen**.

   ![](assets/one-2.png)

1. Klik onder Beheerinstellingen op **Abonnementen** opzeggen.

   ![](assets/two-3.png)

1. Klik op **Integraties**.

   ![](assets/three-3.png)

1. Klik in de sectie Marketo Unsubscribe Check op de schuifregelaar om de controle te activeren.

   ![](assets/four-2.png)

## Informatie over {#things-to-know}

De controle Afmelden bij Marketo...

* telt niet mee voor uw API-limieten
* Vereist dat een verbinding Marketo wordt gevestigd
* Is een globale instelling
* Hiermee blokkeert u e-mailberichten die worden verzonden vanuit de webtoepassing, e-mailclients en Salesforce

