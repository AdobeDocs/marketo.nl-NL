---
unique-page-id: 14352482
description: Hoe Reageren het Volgen werkt - Marketo Docs - de Documentatie van het Product
title: Hoe Reageren bijhouden werkt
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '242'
ht-degree: 0%

---


# Hoe het Volgen van het Antwoord {#how-reply-tracking-works} werkt

Reageren bijhouden wordt uitgevoerd door te kijken naar een bericht-id in elke e-mail die u verzendt. Elk e-mailbericht bevat een unieke bericht-id waarmee we een aantal van de beste reacties kunnen bijhouden.

>[!PREREQUISITES]
>
>**Verbinding maken met e-mailserver:** Sales Connect moet zijn verbonden met uw Postvak IN, zodat we weten wanneer een nieuw antwoord is ontvangen. Uw Sales Connect-account [moet zijn aangesloten op Gmail](http://docs.marketo.com/x/kYMOAQ). Als u Vooruitzichten gebruikt, zullen wij met uw [ruilserver](http://toutapp.com/next#settings/exchange_settings) moeten integreren.

Als Sales Connect het antwoord van uw vooruitzicht op uw e-mail niet kan bijhouden, kan het geen campagne stoppen op basis van antwoorddetectie of logboek dat het antwoord op Salesforce bevat.  Wat betekent dat elk e-mailadres kan antwoorden?

Dit betekent dat als u [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#783217162b16170f3830170d0b1d2b0c190a13561b1715) en hij met [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#c08aafae93aeafb78094a8a58ea9a7a8b4b397a1b4a3a8eea3afad) antwoordt, wij het antwoord kunnen volgen. Bovendien, als u [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#450f2a2b162b2a32050d2a303620163124372e6b262a28) en CC [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#3e5f525f507e5b505d5153105d5153) verzendt, en Alan u terug schrijft, zal het ook het antwoord ontdekken en de campagne beëindigen.
