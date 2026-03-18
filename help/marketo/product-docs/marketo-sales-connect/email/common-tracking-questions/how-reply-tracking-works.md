---
unique-page-id: 14352482
description: Begrijp hoe het volgen van antwoorden in Verkoop Connect werkt. Leer hoe antwoorden worden gedetecteerd en geregistreerd bij Salesforce of Marketo.
title: Hoe Reageren bijhouden werkt
exl-id: 8d087014-99b7-47ba-9f08-95b13bc16438
feature: Marketo Sales Connect
source-git-commit: 15427eacd2fc42a02f6a4c59d9102bacba02e57b
workflow-type: tm+mt
source-wordcount: '174'
ht-degree: 0%

---

# Hoe Reageren bijhouden werkt {#how-reply-tracking-works}

Reageren bijhouden wordt uitgevoerd door te kijken naar een bericht-id in elke e-mail die u verzendt. Elk e-mailbericht bevat een unieke bericht-id waarmee we een aantal van de beste reacties kunnen bijhouden.

>[!PREREQUISITES]
>
>**Verbinding met de Server van de E-mail:** [!DNL Sales Connect] moet met uw inbox worden verbonden zodat weten wij wanneer een nieuw antwoord is aangekomen. U zult uw [!DNL Sales Connect] rekening [&#x200B; moeten hebben die aan Gmail &#x200B;](/help/marketo/product-docs/marketo-sales-connect/email-plugins/gmail/email-connection-for-gmail-users.md) wordt aangesloten. Als u [!DNL Outlook] gebruikt, zullen wij met uw [&#x200B; uitwisselingsserver &#x200B;](https://toutapp.com/next#settings/exchange_settings) moeten integreren.

Als [!DNL Sales Connect] het antwoord van uw vooruitzicht op uw e-mail niet kan volgen, zal het niet een campagne kunnen tegenhouden die op antwoordopsporing wordt gebaseerd of logboek dat dat antwoord op [!DNL Salesforce].  Wat betekent dat elk e-mailadres kan antwoorden?

Dit betekent dat als u <flynn@flynnsarcade.com> per e-mail verzendt en hij met <kevinf@flynnsarcade.com> reageert, we het antwoord kunnen volgen. Als u bovendien een e-mail verzendt naar <flynn@flynnsarcade.com> en CC <alan@encom.com> en Alan terugschrijft, detecteert het ook het antwoord en beëindigt het de campagne.
