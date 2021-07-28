---
unique-page-id: 11381156
description: Lood tot afstemmen van account - Marketo Docs - Productdocumentatie
title: Lood naar overeenkomst met account
exl-id: 676ae500-7691-492d-abec-0cac708216b7
source-git-commit: 98388f1ed941b321449e6e8badac0153dc2245ba
workflow-type: tm+mt
source-wordcount: '474'
ht-degree: 0%

---

# Lood naar overeenkomst met account {#lead-to-account-matching}

Met een overeenkomst van rechts leidt u naar accounts met een rechternaam die overeenkomen met Marketo Lead-to-Account.

>[!NOTE]
>
>**Lood-to-Account** Matchingis een ingebouwde functie van Marketo Target Account Management. Het gebruikt vage logica om automatisch gelijke leidt tot de juiste genoemde rekeningen in bijna real time aan te passen. Deze benoemde accounts kunnen CRM-accounts zijn voor Marketo-bedrijven.

## Overzicht {#overview}

Marketo leidt-naar-account overeenkomsten volgt een proces van vier stappen:

**Stap 1 -** Ons passende proces begint door zeer belangrijke informatie over de loodverslagen te gebruiken, zoals:

* E-maildomein (bijvoorbeeld acme.com)
* De naam van het bedrijf van IP adres wordt afgeleid
* Bedrijfsnaam - Dit kan het kenmerk CRM-accountnaam of lead company name (afkomstig van het invullen van het formulier) zijn

**Stap 2 -** wij normaliseren de bedrijfsnamen die wij gebaseerd op diverse loodattributen (b.v., Acme Inc. en Acme Corp worden automatisch genormaliseerd aan Acme) vinden. Deze stap zorgt ervoor dat we één enkele representatie hebben van het account met een naam in Marketo en alle leads kunnen bekijken binnen één account met een naam.

**Stap 3 -** Wij verdelen gelijke lood in 2 emmers: Sterke overeenkomst en zwakke overeenkomst.

* Zwak overeenkomende leads worden weergegeven op de benoemde accounts die vervolgens handmatig kunnen worden opgelost.

**Stap 4 -** Wij presenteren een lijst van voorgestelde bedrijven met sterke en zwakke overeenkomsten. Wanneer een benoemde account wordt gemaakt op basis van een van de voorgestelde bedrijven, maken we matchingsregels om automatisch nieuwe leads (bijvoorbeeld een ingevuld formulier) te koppelen die naar de juiste benoemde accounts gaan. Op deze manier kunt u zich minder zorgen maken over overeenkomende leads en meer over het verkrijgen van inkomsten.

Aangezien Marketo Lead-to-Account matching een ingebouwde functie is van Marketo Target Account Management, leidt matching tot het maken van accounts in bijna real-time (wanneer een lead bijvoorbeeld een Marketo-formulier invult, wordt gezegd dat lead overeenkomt met de rechteraccount). Deze gebeurtenis kan worden gebruikt om waarschuwingen te activeren en rekeninghouders op de hoogte te stellen van de nieuwe leads die vanuit hun benoemde accounts worden ontvangen.

>[!NOTE]
>
>Als u LeanData in Salesforce gebruikt om Lood-aan-Rekening aanpassing te doen, heeft Marketo een integratie die die gelijken aan uw instantie van Marketo zal synchroniseren. Als u deze functie wilt inschakelen, neemt u contact op met [Marketo Support](https://nation.marketo.com/t5/Support/ct-p/Support) Leer hoe u LeanData hieronder instelt.

## LeanData gebruiken voor Afleiden naar Account Matching {#using-leandata-for-lead-to-account-matching}

Nadat [Marketo Support](https://nation.marketo.com/t5/Support/ct-p/Support) LeanData voor uw account heeft ingeschakeld, volgt u de onderstaande stappen om deze in te stellen.

1. Klik in Salesforce op **Startpagina instellen** in de linkernav.

1. Nog in de linkernav, onder Beleid, klik **Gebruikers** toen **Profielen**.

1. Zoek en selecteer het profiel **Marketo Sync**.

1. Blader omlaag naar de sectie Beveiliging op veldniveau en zoek het object Lead. Selecteer **Weergave**.

1. Voor de gebiedsnaam &quot;Meld Gelijke Rekening,&quot;zorg checkbox in **Read Access** wordt geselecteerd.

1. Ga in Marketo naar de sectie **Admin**.

   ![](assets/lead-to-account-matching-1.png)

1. Selecteer **Veldbeheer**.

   ![](assets/lead-to-account-matching-2.png)

1. Bevestig dat het veld aanwezig is door op &quot;Overeenkomende account rapporteren&quot; te zoeken.

   ![](assets/lead-to-account-matching-3.png)

>[!MORELIKETHIS]
[Accounts detecteren](/help/marketo/product-docs/target-account-management/target/named-accounts/discover-accounts.md)>
>
