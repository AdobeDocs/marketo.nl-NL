---
unique-page-id: 14352581
description: Throtatiefouten - Marketo Docs - Productdocumentatie
title: Rotatiefouten
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '163'
ht-degree: 0%

---


# Omdraaiingsfouten {#throttling-errors}

## Bestandslimiet bereikt {#file-limit-reached}

Als u door uw eigen Server verzendt, zal het beperkingen voor het aantal e-mails hebben u gelijktijdig kunt verzenden. Wanneer u via Sales Connect verzendt, kunt u veel e-mails verzenden, maar proberen we ze allemaal tegelijk te verzenden. Als u zich dus bewust bent dat uw server u om 100 e-mails per minuut zal schrappen, zult u slechts tot 100 e-mails door [Webtoepassing](http://toutapp.com/login) moeten verzenden. Anders kunnen de e-mails hier landen omdat de e-mails op de server worden vertraagd.

## Verificatiefout {#authentication-error}

Dit betekent dat we de verbinding met uw SMTP-server niet konden verifiëren. Het is zeer waarschijnlijk dat uw wachtwoord onlangs is gewijzigd en dat u alleen uw nieuwe gegevens moet verifiëren.

Om dit te doen, ga naar uw [SMTP Montages](http://docs.marketo.com/display/docs/assets/external-link-1.jspa) `where you should see the same error message. Update your credentials and hit **Authenticate and Save** to see a confirmation message.`

Ga naar de mislukte leveringen om te proberen deze e-mails opnieuw te verzenden.
