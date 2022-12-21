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
>**Lood-aan-Account-overeenkomst** is een ingebouwde functie van Marketo Target Account Management. Het gebruikt vage logica om automatisch gelijke leidt tot de juiste genoemde rekeningen in bijna real time aan te passen. Deze benoemde accounts kunnen CRM-accounts zijn voor Marketo-bedrijven.

## Overzicht {#overview}

Marketo leidt-naar-account overeenkomst volgt een proces in vier stappen:

**Stap 1 -** Ons afstemmingsproces begint met het gebruik van de belangrijkste gegevens in de hoofdrecords, zoals:

* E-maildomein (bijvoorbeeld acme.com)
* De naam van het bedrijf van IP adres wordt afgeleid
* Bedrijfsnaam - Dit kan het kenmerk CRM-accountnaam of lead company name (afkomstig van het invullen van het formulier) zijn

**Stap 2 -** We normaliseren de bedrijfsnamen die we vinden op basis van verschillende hoofdkenmerken (zoals Acme Inc. en Acme Corp worden automatisch genormaliseerd naar Acme). Deze stap zorgt ervoor dat we één enkele representatie hebben van het account met een naam in Marketo en alle leads kunnen bekijken binnen één account met een naam.

**Stap 3 -** We verdelen overeenkomende leads in twee emmers: Sterke overeenkomst en zwakke overeenkomst.

* Zwak overeenkomende leads worden weergegeven op de benoemde accounts die vervolgens handmatig kunnen worden opgelost.

**Stap 4 -** We presenteren een lijst met voorgestelde bedrijven met sterke en zwakke overeenkomsten. Wanneer een benoemde account wordt gemaakt op basis van een van de voorgestelde bedrijven, maken we matchingsregels om automatisch nieuwe leads (bijvoorbeeld een ingevuld formulier) te koppelen die naar de juiste benoemde accounts gaan. Op deze manier kunt u zich minder zorgen maken over overeenkomende leads en meer over het verkrijgen van inkomsten.

Aangezien Marketo Lead-to-Account matching een ingebouwde functie is van Marketo Target Account Management, leidt matching tot het maken van accounts in bijna real-time (wanneer een lead bijvoorbeeld een Marketo-formulier invult, wordt gezegd dat lead overeenkomt met de rechteraccount). Deze gebeurtenis kan worden gebruikt om waarschuwingen te activeren en rekeninghouders op de hoogte te stellen van de nieuwe leads die vanuit hun benoemde accounts worden ontvangen.

>[!NOTE]
>
>Als u LeanData in Salesforce gebruikt om Lood-aan-Rekening aanpassing te doen, heeft Marketo een integratie die die gelijken aan uw instantie van Marketo zal synchroniseren. Neem contact op met [Marketo-ondersteuning](https://nation.marketo.com/t5/Support/ct-p/Support) Leer hoe u hieronder LeanData instelt.

## LeanData gebruiken voor Afleiden naar Account Matching {#using-leandata-for-lead-to-account-matching}

Na [Marketo-ondersteuning](https://nation.marketo.com/t5/Support/ct-p/Support) heeft LeanData voor uw account ingeschakeld. Volg de onderstaande stappen om deze in te stellen.

1. Klik in Salesforce op **Startpagina instellen** in de linkernav.

1. Nog in de linkernav, onder Beheer, klik **Gebruikers** dan **Profielen**.

1. Zoek en selecteer de **Marketo Sync** profiel.

1. Blader omlaag naar de sectie Beveiliging op veldniveau en zoek het object Lead. Selecteren **Weergave**.

1. Voor de veldnaam &quot;Aan elkaar gekoppelde account rapporteren&quot; schakelt u het selectievakje in het dialoogvenster **Leestoegang** is geselecteerd.

1. Ga in Marketo naar de **Beheer** sectie.

   ![](assets/lead-to-account-matching-1.png)

1. Selecteren **Veldbeheer**.

   ![](assets/lead-to-account-matching-2.png)

1. Bevestig dat het veld aanwezig is door op &quot;Overeenkomende account rapporteren&quot; te zoeken.

   ![](assets/lead-to-account-matching-3.png)

>[!MORELIKETHIS]
>
>[Accounts detecteren](/help/marketo/product-docs/target-account-management/target/named-accounts/discover-accounts.md)
