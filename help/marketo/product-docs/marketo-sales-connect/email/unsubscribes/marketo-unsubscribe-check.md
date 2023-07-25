---
unique-page-id: 18317340
description: Marketo Unsubscribe Check - Marketo Docs - Productdocumentatie
title: Marketo Unsubscribe Check
exl-id: b8bd5b38-a4f5-4ac7-a5ce-a155fce57998
feature: Marketo Sales Connect
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '192'
ht-degree: 0%

---

# Marketo Unsubscribe Check {#marketo-unsubscribe-check}

Met de Marketo Unsubscribe Check wordt de verbinding van uw team met Marketo gebruikt om te voorkomen dat e-mails worden verzonden naar personen die zich niet hebben geabonneerd in het beheersysteem voor leads van Marketo. Wanneer een verkoopgebruiker een e-mail verzendt met Sales Connect, wordt een API-aanroep naar Marketo uitgevoerd om te controleren of het e-mailadres niet is geabonneerd. Als dit het geval is, blokkeren we het verzenden van de e-mail.

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

## Deze inschakelen {#turning-it-on}

1. Klik in de webtoepassing op het tandwielpictogram en selecteer **Instellingen**.

   ![](assets/one-2.png)

1. Klik onder Beheerinstellingen op **Abonnementen opzeggen**.

   ![](assets/two-3.png)

1. Klikken **Integraties**.

   ![](assets/three-3.png)

1. Klik in de sectie Marketo Unsubscribe Check op de schuifregelaar om de controle te activeren.

   ![](assets/four-2.png)

## Informatie over {#things-to-know}

Afmeldingscontrole van Marketo...

* telt niet mee voor uw API-limieten
* Hiervoor moet een Marketo-verbinding tot stand worden gebracht
* Is een globale instelling
* Hiermee blokkeert u e-mailberichten die worden verzonden vanuit de webtoepassing, e-mailclients en Salesforce
* Wordt een mislukte e-mail geregistreerd of voorkomt dat een gebruiker een bericht verzendt wanneer deze voor alle workflows probeert te verzenden (e-mailplug-in verzenden, individueel verzenden, verkoopcampagne verzenden, meerdere selecteren en verzenden), behalve voor [groepse e-mails](/help/marketo/product-docs/marketo-sales-connect/email/using-the-compose-window/composing-bulk-emails-with-select-and-send.md), waarin we zullen voorkomen dat de e-mails stilzwijgend worden verzonden
