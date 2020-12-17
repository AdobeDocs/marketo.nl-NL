---
unique-page-id: 7514918
description: Inzicht in afmelden - Marketo Docs - Productdocumentatie
title: Abonnement begrijpen
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '269'
ht-degree: 0%

---


# Abonnement {#understanding-unsubscribe} begrijpen

In Marketo zijn er eigenlijk verschillende soorten ingebouwd afmelden. Ze worden allemaal vertegenwoordigd door velden op het object person, net als Voornaam.

>[!NOTE]
>
>Marketo is bezig met het wijzigen van termen als Blacklist en Whitelist in de Lijst van afgewezen personen en Lijst van gewenste personen in ons product. Tijdens deze update ziet u mogelijk de oude termen in onze gebruikersinterface en documentatiescherm en de nieuwe termen in onze documentatietekst. Onze excuses voor de verwarring.

Al deze velden zijn ingebouwd in uw abonnement op Marketo. Ze zijn allemaal van het type Boolean (selectievakje). Ze kunnen worden gebruikt in Forms- of [Gegevenswaarde wijzigen](../../../product-docs/core-marketo-concepts/smart-campaigns/flow-actions/change-data-value.md)-stroomstappen.

## Afgemeld {#unsubscribed}

Deze wordt gebruikt op de standaard pagina voor afmelden. Als iemand dit selectievakje inschakelt of op de koppeling Abonnement opzeggen klikt in een e-mail, ontvangen hij of zij geen e-mails over marketing meer. Ze zullen echter [operationele e-mails](../../../product-docs/email-marketing/general/functions-in-the-editor/make-an-email-operational.md) ontvangen.

## Marketing opgeschort {#marketing-suspended}

Dit veld wordt ingesteld door de gebruiker voor het plaatsen van personen op een tijdelijk abonnement. De mensen kunnen dit statuut slechts bereiken als zij manueel worden veranderd of een stap van de de waardestroom van veranderingsgegevens wordt gebruikt.

## E-mail opgeschort {#email-suspended}

Deze status verhindert een persoon 24 uur na een harde stuit te zenden. Na 24 uur wordt de persoon weer mailbaar.

>[!NOTE]
>
>E-mail geschorst blijft gecontroleerd zelfs nadat de periode van 24 uur voorbij is, zodat kunt u naar mensen verwijzen die historisch als zodanig zijn gemerkt. Als u wilt zien of de persoon mailbaar is, berekent u gewoon 24 uur na het tijdstip van de e-mailschorsing.

## Toegevoegd op lijst van gewenste personen {#blocklisted}

[Gebruik dit voor mensen zoals concurrenten](http://docs.marketo.com/x/uwOQ). Iedereen u **no** e-mail-operationeel wilt ontvangen, marketing, etc. Ze krijgen niets!

![](assets/image2015-5-18-12-3a6-3a40.png)

