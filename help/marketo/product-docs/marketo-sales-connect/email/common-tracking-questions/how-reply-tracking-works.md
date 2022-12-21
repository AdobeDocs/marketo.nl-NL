---
unique-page-id: 14352482
description: Hoe Reageren bijhouden werkt - Marketo Docs - Productdocumentatie
title: Hoe Reageren bijhouden werkt
exl-id: 8d087014-99b7-47ba-9f08-95b13bc16438
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '180'
ht-degree: 0%

---

# Hoe Reageren bijhouden werkt {#how-reply-tracking-works}

Reageren bijhouden wordt uitgevoerd door te kijken naar een bericht-id in elke e-mail die u verzendt. Elk e-mailbericht bevat een unieke bericht-id waarmee we een aantal van de beste reacties kunnen bijhouden.

>[!PREREQUISITES]
>
>**Verbinding maken met e-mailserver:** Sales Connect moet verbonden zijn met uw Postvak IN, zodat we weten wanneer een nieuw antwoord is ontvangen. Je hebt je Sales Connect-account nodig [verbonden met Gmail](/help/marketo/product-docs/marketo-sales-connect/email-plugins/gmail/email-connection-for-gmail-users.md). Als u Vooruitzichten gebruikt, zullen wij met uw moeten integreren [ruilserver](https://toutapp.com/next#settings/exchange_settings).

Als Sales Connect het antwoord van uw vooruitzicht op uw e-mail niet kan bijhouden, kan het geen campagne stoppen op basis van antwoorddetectie of logboek dat het antwoord op Salesforce bevat.  Wat betekent dat elk e-mailadres kan antwoorden?

Dit betekent dat als u een e-mail verzendt naar flynn@flynnsarcade.com en hij reageert op kevinf@flynnsarcade.com, we het antwoord kunnen volgen. Bovendien, als u flynn@flynnsarcade.com en CC alan@encom.com e-mailt, en Alan u terug schrijft, zal het ook het antwoord ontdekken en de campagne beëindigen.
