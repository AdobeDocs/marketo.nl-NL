---
unique-page-id: 7514918
description: Abonnement op opzeggen - Marketo Docs - Productdocumentatie
title: Abonnement begrijpen
exl-id: 30866dc0-cdac-4e73-8dbf-d4b509012269
feature: Deliverability
source-git-commit: 4bae0126d6b36720e170bea7b6b973508c855633
workflow-type: tm+mt
source-wordcount: '217'
ht-degree: 0%

---

# Abonnement begrijpen {#understanding-unsubscribe}

In Marketo zijn er verschillende soorten ingebouwde afmeldingsprogramma&#39;s. Ze worden allemaal vertegenwoordigd door velden op het object person, net als Voornaam.

Al deze velden zijn ingebouwd in uw Marketo-abonnement. Ze zijn allemaal van het type Boolean (selectievakje). Ze kunnen in Forms of [Gegevenswaarde wijzigen](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/change-data-value.md) stroomstappen.

## Niet geabonneerd {#unsubscribed}

Deze wordt gebruikt op de standaard pagina voor afmelden. Als iemand dit selectievakje inschakelt of op de koppeling Abonnement opzeggen klikt in een e-mail, ontvangen hij of zij geen e-mails over marketing meer. Zij zullen echter [operationele e-mails](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/make-an-email-operational.md).

## Marketing opgeschort {#marketing-suspended}

Dit veld wordt ingesteld door de gebruiker voor het plaatsen van personen op een tijdelijk abonnement. De mensen kunnen dit statuut slechts bereiken als zij manueel worden veranderd of een stap van de de waardestroom van veranderingsgegevens wordt gebruikt.

## E-mail opgeschort {#email-suspended}

Deze status verhindert een persoon 24 uur na een harde stuit te zenden. Na 24 uur wordt de persoon weer mailbaar.

>[!NOTE]
>
>E-mail geschorst blijft gecontroleerd zelfs nadat de periode van 24 uur voorbij is, zodat kunt u naar mensen verwijzen die historisch als zodanig zijn gemerkt. Als u wilt zien of de persoon mailbaar is, berekent u gewoon 24 uur na het tijdstip van de e-mailschorsing.

## Gevoegd op lijst van gewenste personen {#blocklisted}

[Gebruik dit voor mensen als concurrenten](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/add-person-to-blocklist.md). Iedereen die u wilt ontvangen **nee** e-mails—operationeel, op de markt brengen, enz. Ze krijgen niets!

![](assets/image2015-5-18-12-3a6-3a40.png)
