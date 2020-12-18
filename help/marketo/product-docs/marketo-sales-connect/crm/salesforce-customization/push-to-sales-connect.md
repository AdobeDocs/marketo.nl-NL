---
unique-page-id: 14352477
description: Overstappen op Sales Connect - Marketo Docs - Productdocumentatie
title: Push to Sales Connect
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '188'
ht-degree: 0%

---


# Druk op Sales Connect {#push-to-sales-connect}

Met onze knop Push to Tout maakt u een lijst met uw leads/contactpersonen in Salesforce en plaatst u deze in een groep in Sales Connect. Vervolgens kunt u snel een aanpasbare groep e-mailen met de functie Tout bijhouden.

## Vereisten {#requirements}

* Sales Connect [Salesforce-pakket](http://docs.marketo.com/x/C4PS) geïnstalleerd door `Salesforce Admin`

* `Push to Sales Connect`knop geïnstalleerd als lijstweergave op  `Salesforce Admin`

* Salesforce Connection gemaakt met Sales Connect voor gebruiker die Push uitvoert

## Procedure {#how-to}

1. Klik in Salesforce op het tabblad **Lead/Contact**.
1. Schakel over naar de lijstweergave die u wilt gebruiken bij Sales Connect naast de knop Go.
1. Klik **Go**.
1. Selecteer alle leads/contactpersonen die u wilt laten afdrukken.
1. Selecteer **Naar MSE** duwen.
1. Er wordt een nieuw venster weergegeven waarin het aantal leads/contactpersonen dat u wilt laten aanwijzen, wordt gecontroleerd. Selecteer **Ga aan Groep** te werk. Sales Connect `will not push over` alle contactpersonen die zijn gemarkeerd als `Email Opt Out` in Salesforce of `Unsubscribed` in Sales Connect.

   >[!NOTE]
   >
   >Sales Connect voegt deze groep met de naam &quot;SFDC-...&quot; toe op de pagina Relaties op de [webtoepassing](http://toutapp.com/login).

1. Selecteer **Gehele groep e-mailen** om deze groep e-mail te verzenden.

