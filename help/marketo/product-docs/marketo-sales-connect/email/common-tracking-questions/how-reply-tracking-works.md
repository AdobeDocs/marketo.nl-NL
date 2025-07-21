---
unique-page-id: 14352482
description: Hoe Reageren bijhouden werkt - Marketo Docs - Productdocumentatie
title: Hoe Reageren bijhouden werkt
exl-id: 8d087014-99b7-47ba-9f08-95b13bc16438
feature: Marketo Sales Connect
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '167'
ht-degree: 0%

---

# Hoe Reageren bijhouden werkt {#how-reply-tracking-works}

Reageren bijhouden wordt uitgevoerd door te kijken naar een bericht-id in elke e-mail die u verzendt. Elk e-mailbericht bevat een unieke bericht-id waarmee we een aantal van de beste reacties kunnen bijhouden.

>[!PREREQUISITES]
>
>**Verbinding met de Server van de E-mail:** [!DNL Sales Connect] moet met uw inbox worden verbonden zodat weten wij wanneer een nieuw antwoord is aangekomen. U zult uw [!DNL Sales Connect] rekening [ moeten hebben die aan Gmail ](/help/marketo/product-docs/marketo-sales-connect/email-plugins/gmail/email-connection-for-gmail-users.md) wordt aangesloten. Als u [!DNL Outlook] gebruikt, zullen wij met uw [ uitwisselingsserver ](https://toutapp.com/next#settings/exchange_settings) moeten integreren.

Als [!DNL Sales Connect] het antwoord van uw vooruitzicht op uw e-mail niet kan volgen, zal het niet een campagne kunnen tegenhouden die op antwoordopsporing wordt gebaseerd of logboek dat dat antwoord op [!DNL Salesforce].  Wat betekent dat elk e-mailadres kan antwoorden?

Dit betekent dat als u een e-mail verzendt naar flynn@flynnsarcade.com en hij reageert op kevinf@flynnsarcade.com, we het antwoord kunnen volgen. Bovendien, als u flynn@flynnsarcade.com en CC alan@encom.com e-mailt, en Alan u terug schrijft, zal het ook het antwoord ontdekken en de campagne beëindigen.
