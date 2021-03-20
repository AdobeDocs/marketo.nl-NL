---
unique-page-id: 14352482
description: Hoe Reageren het Volgen werkt - Marketo Docs - de Documentatie van het Product
title: Hoe Reageren bijhouden werkt
translation-type: tm+mt
source-git-commit: 073b73255d49f859c32c8b4793e6798f02f7a5c4
workflow-type: tm+mt
source-wordcount: '180'
ht-degree: 0%

---


# Hoe het Volgen van het Antwoord {#how-reply-tracking-works} werkt

Reageren bijhouden wordt uitgevoerd door te kijken naar een bericht-id in elke e-mail die u verzendt. Elk e-mailbericht bevat een unieke bericht-id waarmee we een aantal van de beste reacties kunnen bijhouden.

>[!PREREQUISITES]
>
>**Verbinding maken met e-mailserver:** Sales Connect moet zijn verbonden met uw Postvak IN, zodat we weten wanneer een nieuw antwoord is ontvangen. Uw Sales Connect-account [moet zijn aangesloten op Gmail](/help/marketo/product-docs/marketo-sales-connect/email-plugins/gmail/email-connection-for-gmail-users.md). Als u Vooruitzichten gebruikt, zullen wij met uw [ruilserver](https://toutapp.com/next#settings/exchange_settings) moeten integreren.

Als Sales Connect het antwoord van uw vooruitzicht op uw e-mail niet kan bijhouden, kan het geen campagne stoppen op basis van antwoorddetectie of logboek dat het antwoord op Salesforce bevat.  Wat betekent dat elk e-mailadres kan antwoorden?

Dit betekent dat als u een e-mail verzendt flynn@flynnsarcade.com en hij reageert met kevinf@flynnsarcade.com, we het antwoord kunnen volgen. Bovendien, als u flynn@flynnsarcade.com en CC alan@encom.com e-mailt, en Alan u terug schrijft, zal het ook het antwoord ontdekken en de campagne beëindigen.
