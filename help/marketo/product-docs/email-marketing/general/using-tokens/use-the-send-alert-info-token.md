---
unique-page-id: 2952678
description: Het token voor waarschuwinggegevens verzenden gebruiken {SP_Send_Alert_Info} - Marketo Docs - Productdocumentatie
title: Het token voor waarschuwinggegevens verzenden gebruiken
translation-type: tm+mt
source-git-commit: d7d6aee63144c472e02fe0221c4a164183d04dd4
workflow-type: tm+mt
source-wordcount: '265'
ht-degree: 0%

---


# Het token {#use-the-send-alert-info-token-sp-send-alert-info} voor waarschuwinggegevens verzenden gebruiken

De token `{{SP_Send_Alert_Info}}` is een speciaal token dat moet worden gebruikt bij het maken van e-mailberichten voor uw verkoopteam.

>[!TIP]
>
>Dit token werkt alleen zoals bedoeld wanneer het e-mailbericht met het bericht [Send Alert](../../../../product-docs/core-marketo-concepts/smart-campaigns/flow-actions/send-alert.md) wordt verzonden. Het werkt niet als het wordt gebruikt in een stap E-mail verzenden.

Voorbeeld, waarschuwing:   ![](assets/image2014-9-25-15-3a17-3a58.png)

>[!NOTE]
>
>Koppen omhoog! URL&#39;s in waarschuwingen hebben vervaldatums, zodat ze beschikken over een interface die deze berichttypen ondersteunt. Vervaldatums worden [geconfigureerd door een beheerder](../../../../product-docs/administration/settings/edit-link-expiration-in-reports-and-alerts.md).

De volgende informatie maakt deel uit van `{{SP_Send_Alert_Info}}`:

* Voornaam en achternaam als koppeling naar de persoongegevens in Marketo
* Een koppeling naar de persoon in uw CRM
* De naam van de campagne in Marketo die de waarschuwing heeft verzonden
* Het tijdstip waarop de signalering is verzonden

>[!NOTE]
>
>De verbinding aan CRM zal slechts verschijnen als de persoon in het systeem van CRM (momenteel niet beschikbaar met Dynamica CRM) is. De koppeling is toegankelijk voor zowel gebruikers met als zonder markteconomie.

## Voeg het token SP_Send_Alert_Info toe aan een e-mail {#add-the-sp-send-alert-info-token-to-an-email}

1. Selecteer de e-mail en klik **Concept** bewerken.

   ![](assets/one-3.png)

1. Dubbelklik op het bewerkbare gebied waaraan u het token wilt toevoegen.

   ![](assets/two-3.png)

1. Plaats de curseur waar u het teken wilt zijn, dan klik **Symbolisch van het Tussenvoegsel** knoop.

   ![](assets/three-3.png)

1. Zoek en selecteer de token **`{{SP_Send_Alert_Info}}`** en klik op **Insert**.

   ![](assets/image2014-9-25-15-3a19-3a11.png)

1. Klik **Opslaan**.

   ![](assets/image2014-9-25-15-3a19-3a24.png)

>[!NOTE]
>
>**Herinnering**
>
>Vergeet niet uw e-mail goed te keuren.

Goed spul! Dit token is zeer nuttig en u moet het gebruiken in alle waarschuwingen die u voor uw verkoopteam maakt.