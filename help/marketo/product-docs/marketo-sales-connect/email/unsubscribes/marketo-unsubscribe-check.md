---
unique-page-id: 18317340
description: Marketo Unsubscribe Check - Marketo Docs - Productdocumentatie
title: Marketo Unsubscribe Check
exl-id: b8bd5b38-a4f5-4ac7-a5ce-a155fce57998
feature: Marketo Sales Connect
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '179'
ht-degree: 0%

---

# Marketo Unsubscribe Check {#marketo-unsubscribe-check}

In [!UICONTROL Marketo Unsubscribe Check] wordt de verbinding van uw team met Marketo gebruikt om te voorkomen dat e-mailberichten worden verzonden naar personen die zich niet hebben geabonneerd in het beheersysteem voor leads van Marketo. Wanneer een verkoopgebruiker een e-mail verzendt met [!DNL Sales Connect] , wordt een API-aanroep naar Marketo uitgevoerd om te controleren of het e-mailadres niet is geabonneerd. Als dit het geval is, blokkeren we het verzenden van de e-mail.

>[!NOTE]
>
>**Vereiste Bevoegdheden Admin**

## De functie inschakelen {#turning-it-on}

1. Klik in de webtoepassing op het tandwielpictogram en selecteer **[!UICONTROL Settings]** .

   ![](assets/one-2.png)

1. Klik onder [!UICONTROL Admin Settings] op **[!UICONTROL Unsubscribes]** .

   ![](assets/two-3.png)

1. Klik op **[!UICONTROL Integrations]**.

   ![](assets/three-3.png)

1. Klik in de sectie [!UICONTROL Marketo Unsubscribe Check] op de schuifregelaar om de controle te activeren.

   ![](assets/four-2.png)

## Informatie over dingen {#things-to-know}

Afmeldingscontrole van Marketo...

* telt niet mee voor uw API-limieten
* Hiervoor moet een Marketo-verbinding tot stand worden gebracht
* Is een globale instelling
* Hiermee blokkeert u e-mailberichten die worden verzonden vanuit de webtoepassing, e-mailclients en Salesforce
* Zal een ontbroken e-mail registreren of een gebruiker verhinderen te verzenden wanneer zij proberen om voor alle werkschema&#39;s (e-mailstop te verzenden, individueel verzenden, verkoopcampagne verzenden, veelvoudige selecteren en verzenden) behalve [ groep e-mails ](/help/marketo/product-docs/marketo-sales-connect/email/using-the-compose-window/composing-bulk-emails-with-select-and-send.md) te verzenden, waarin wij zullen verhinderen de e-mails stil te verzenden
