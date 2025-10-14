---
unique-page-id: 7514918
description: Abonnement op opzeggen - Marketo Docs - Productdocumentatie
title: Abonnement begrijpen
exl-id: 30866dc0-cdac-4e73-8dbf-d4b509012269
feature: Deliverability
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '221'
ht-degree: 0%

---

# Abonnement begrijpen {#understanding-unsubscribe}

In Marketo zijn er verschillende soorten ingebouwde afmeldingsprogramma&#39;s. Ze worden allemaal vertegenwoordigd door velden op het object person, net als Voornaam.

Al deze velden zijn ingebouwd in uw Marketo-abonnement. Ze zijn allemaal van het type Boolean (selectievakje). Zij kunnen in Forms worden gebruikt of [&#x200B; de stroomstappen van de Waarde van Gegevens van de Verandering &#x200B;](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/change-data-value.md).

## Niet geabonneerd {#unsubscribed}

Deze wordt gebruikt op de standaard pagina voor afmelden. Als iemand dit selectievakje inschakelt of op de koppeling Abonnement opzeggen klikt in een e-mail, ontvangen hij of zij geen e-mails over marketing meer. Zij zullen, echter, [&#x200B; operationele e-mails &#x200B;](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/make-an-email-operational.md) ontvangen.

## Marketing opgeschort {#marketing-suspended}

Dit veld wordt ingesteld door de gebruiker voor het plaatsen van personen op een tijdelijk abonnement. De mensen kunnen dit statuut slechts bereiken als zij manueel worden veranderd of een stap van de de waardestroom van veranderingsgegevens wordt gebruikt.

## E-mail opgeschort {#email-suspended}

Deze status verhindert een persoon 24 uur na een harde stuit te zenden. Na 24 uur wordt de persoon weer mailbaar.

>[!NOTE]
>
>E-mail geschorst blijft gecontroleerd zelfs nadat de periode van 24 uur voorbij is, zodat kunt u naar mensen verwijzen die historisch als zodanig zijn gemerkt. Als u wilt zien of de persoon mailbaar is, berekent u gewoon 24 uur na het tijdstip van de e-mailschorsing.

## Gevoegd op lijst van gewenste personen {#blocklisted}

[&#x200B; gebruik dit voor mensen als concurrenten &#x200B;](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/add-person-to-blocklist.md). Iedereen u wilt ontvangen **geen** e-mail-operationeel, marketing, etc. Ze krijgen niets!

![](assets/image2015-5-18-12-3a6-3a40.png)
