---
unique-page-id: 11381156
description: Lood tot afstemmen van account - Marketo Docs - Productdocumentatie
title: Lood naar overeenkomst met account
translation-type: tm+mt
source-git-commit: 9f88e7cebc5e9d0d4491d65d332ccfdd9a31c395
workflow-type: tm+mt
source-wordcount: '356'
ht-degree: 0%

---


# Regelafstand tot overeenkomst van account {#lead-to-account-matching}

Met een overeenkomst van rechts leidt u naar accounts met een rechternaam die gebruikmaken van Afleiding naar account afstemmen.

>[!NOTE]
>
>**Lood-aan-Account** Matchingis een ingebouwde eigenschap van Marketo Target Account Management. Het gebruikt vage logica om automatisch gelijke leidt tot de juiste genoemde rekeningen in bijna real time aan te passen. Deze genoemde rekeningen kunnen CRM-rekeningen of Marketo-ondernemingen zijn.

Marketo-overeenkomst tussen leads en accounts volgt een proces van vier stappen:

**Stap 1 -** Ons passende proces begint door zeer belangrijke informatie over de loodverslagen te gebruiken, zoals:

* E-maildomein (bijvoorbeeld acme.com)
* De naam van het bedrijf van IP adres wordt afgeleid
* Bedrijfsnaam - Dit kan het kenmerk CRM-accountnaam of lead company name (afkomstig van het invullen van het formulier) zijn

**Stap 2 -** wij normaliseren de bedrijfsnamen die wij gebaseerd op diverse loodattributen (b.v., Acme Inc. en Acme Corp worden automatisch genormaliseerd aan Acme) vinden. Deze stap zorgt ervoor dat we één enkele representatie hebben van de benoemde account in Marketo en alle leads binnen één benoemde account kunnen zien.

**Stap 3 -** Wij verdelen gelijke lood in 2 emmers: Sterke overeenkomst en zwakke overeenkomst.

* Zwak overeenkomende leads worden weergegeven op de benoemde accounts die vervolgens handmatig kunnen worden opgelost.

**Stap 4 -** Wij presenteren een lijst van voorgestelde bedrijven met sterke en zwakke overeenkomsten. Wanneer een benoemde account wordt gemaakt op basis van een van de voorgestelde bedrijven, maken we matchingsregels om automatisch nieuwe leads (bijvoorbeeld een ingevuld formulier) te koppelen die naar de juiste benoemde accounts gaan. Op deze manier kunt u zich minder zorgen maken over overeenkomende leads en meer over het verkrijgen van inkomsten.

Aangezien Marketo Lead-to-Account matching een ingebouwde functie is van Marketo Target Account Management, leidt het afstemmen van accounts in bijna real-time (wanneer een lead bijvoorbeeld een Marketo-formulier invult, wordt gezegd dat lead is gekoppeld aan de rechteraccount). Deze gebeurtenis kan worden gebruikt om waarschuwingen te activeren en rekeninghouders op de hoogte te stellen van de nieuwe leads die vanuit hun benoemde accounts worden ontvangen.

>[!NOTE]
>
>Als u LeanData in Salesforce gebruikt om Lood-aan-Rekening aanpassing te doen, heeft Marketo een integratie die die gelijken aan uw instantie van Marketo zal synchroniseren. Neem contact op met [Marketo Support](https://nation.marketo.com/t5/Support/ct-p/Support) als u deze functie wilt inschakelen.

>[!MORELIKETHIS]
>
>[Accounts detecteren](/help/marketo/product-docs/target-account-management/target/named-accounts/discover-accounts.md)
