---
unique-page-id: 2952678
description: Het token voor waarschuwinggegevens verzenden gebruiken {SP_Send_Alert_Info} - Marketo Docs - Productdocumentatie
title: Het token voor waarschuwinggegevens verzenden gebruiken
translation-type: tm+mt
source-git-commit: 1a29614ec938074902af201b2ffc11cfaa625f7a
workflow-type: tm+mt
source-wordcount: '316'
ht-degree: 0%

---


# Het token voor waarschuwinggegevens verzenden gebruiken {#use-the-send-alert-info-token-sp-send-alert-info}

Het `{{SP_Send_Alert_Info}}` token is een speciaal token dat moet worden gebruikt bij het maken van e-mailberichten voor uw verkoopteam.

>[!NOTE]
>
>**FYI**
>
>Marketo is nu bezig met het standaardiseren van de taal voor alle abonnementen, dus u ziet mogelijk leads/leads in uw abonnement en personen/personen in docs.marketo.com. Deze termen betekenen hetzelfde. het heeft geen invloed op de instructies van het artikel . Er zijn nog enkele andere veranderingen. [Meer](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)informatie.

>[!TIP]
>
>Dit token werkt alleen zoals bedoeld wanneer het e-mailbericht met het bericht [Verzenden van waarschuwing](../../../../product-docs/core-marketo-concepts/smart-campaigns/flow-actions/send-alert.md) wordt verzonden. Het werkt niet als het wordt gebruikt in een stap E-mail verzenden.

Voorbeeld, waarschuwing:   ![](assets/image2014-9-25-15-3a17-3a58.png)

>[!NOTE]
>
>Koppen omhoog! URL&#39;s in waarschuwingen hebben vervaldatums, zodat ze beschikken over een interface die deze berichttypen ondersteunt. Vervaldatums worden [geconfigureerd door een beheerder](../../../../product-docs/administration/settings/edit-link-expiration-in-reports-and-alerts.md).

De volgende informatie maakt deel uit van het `{{SP_Send_Alert_Info}}`programma:

* Voornaam en achternaam als koppeling naar de persoongegevens in Marketo
* Een koppeling naar de persoon in uw CRM
* De naam van de campagne in Marketo die de waarschuwing heeft verzonden
* Het tijdstip waarop de signalering is verzonden

>[!NOTE]
>
>De verbinding aan CRM zal slechts verschijnen als de persoon in het systeem van CRM (momenteel niet beschikbaar met Dynamica CRM) is. De koppeling is toegankelijk voor zowel gebruikers met als zonder markteconomie.

## Het token SP_Send_Alert_Info toevoegen aan een e-mail {#add-the-sp-send-alert-info-token-to-an-email}

1. Selecteer het e-mailbericht en klik op Concept **** bewerken.

   ![](assets/one-3.png)

1. Dubbelklik op het bewerkbare gebied waaraan u het token wilt toevoegen.

   ![](assets/two-3.png)

1. Plaats de curseur waar u het teken wilt zijn, dan klik de **Symbolische** knoop van het Tussenvoegsel.

   ![](assets/three-3.png)

1. Zoek en selecteer het **`{{SP_Send_Alert_Info}}`** token en klik op **Invoegen**.

   ![](assets/image2014-9-25-15-3a19-3a11.png)

1. Klik op **Opslaan**.

   ![](assets/image2014-9-25-15-3a19-3a24.png)

>[!NOTE]
>
>**Herinnering**
>
>Vergeet niet uw e-mail goed te keuren.

Goed spul! Dit token is zeer nuttig en u moet het gebruiken in alle waarschuwingen die u voor uw verkoopteam maakt.