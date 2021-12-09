---
description: Marketo Unsubscribe Check - Marketo Docs - Productdocumentatie
title: Marketo Unsubscribe Check
hide: true
hidefromtoc: true
exl-id: 3c242d04-cf6c-466b-9bcd-e77c6d97d308
source-git-commit: fda1bf51d4016a61c41be9acba4771db1797a552
workflow-type: tm+mt
source-wordcount: '145'
ht-degree: 0%

---

# Marketo Unsubscribe Check {#marketo-unsubscribe-check}

Met de Marketo Unsubscribe Check wordt de verbinding van uw team met Marketo gebruikt om te voorkomen dat e-mails worden verzonden naar personen die zich niet hebben geabonneerd in het beheersysteem voor leads van Marketo. Wanneer een verkoopgebruiker een e-mail verzendt bij Marketo Sales, wordt een API-aanroep naar Marketo uitgevoerd om te controleren of het e-mailadres niet is geabonneerd. Als dit het geval is, blokkeren we het verzenden van de e-mail.

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

## Deze inschakelen {#turning-it-on}

1. Klik op het tandwielpictogram en selecteer **Instellingen**.

   ![](assets/marketo-unsubscribe-check-1.png)

1. Klik onder Beheerinstellingen op **Abonnementen opzeggen**.

   ![](assets/marketo-unsubscribe-check-2.png)

1. Klik op de knop **Integraties** tab. Klik in de sectie Marketo Unsubscribe Check op de schuifregelaar om de controle te activeren.

   ![](assets/marketo-unsubscribe-check-3.png)

## Informatie over {#things-to-know}

Afmeldingscontrole van Marketo...

* telt niet mee voor uw API-limieten
* Hiervoor moet een Marketo-verbinding tot stand worden gebracht
* Is een globale instelling
* Hiermee blokkeert u e-mailberichten die worden verzonden vanuit de webtoepassing, e-mailclients en Salesforce
