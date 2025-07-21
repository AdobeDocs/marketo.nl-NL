---
unique-page-id: 11381156
description: Lood tot afstemmen van account - Marketo Docs - Productdocumentatie
title: Lood naar overeenkomst met account
exl-id: 676ae500-7691-492d-abec-0cac708216b7
feature: Target Account Management
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '451'
ht-degree: 0%

---

# Lood naar overeenkomst met account {#lead-to-account-matching}

Met een overeenkomst van rechts leidt u naar accounts met een juiste naam die overeenkomen met Marketo.

>[!NOTE]
>
>**leiden-aan-Rekening het Aanpassen** is een ingebouwde eigenschap van Marketo [!UICONTROL Target Account Management]. Het gebruikt vage logica om automatisch gelijke leidt tot de juiste genoemde rekeningen in bijna real time aan te passen. Deze benoemde accounts kunnen CRM-accounts zijn voor Marketo-bedrijven.

## Overzicht {#overview}

Marketo leidt-naar-account overeenkomst volgt een proces in vier stappen:

**Stap 1 -** Ons passend proces begint door zeer belangrijke informatie over de loodverslagen, zoals te gebruiken:

* E-maildomein (bijvoorbeeld acme.com)
* De naam van het bedrijf van IP adres wordt afgeleid
* Bedrijfsnaam - Dit kan het kenmerk CRM-accountnaam of lead company name (afkomstig van het invullen van het formulier) zijn

**Stap 2 -** wij normaliseren de bedrijfnamen die wij gebaseerd op diverse loodattributen (b.v., Acme Inc. en Acme Corp worden automatisch genormaliseerd aan Acme) vinden. Deze stap zorgt ervoor dat we één enkele representatie hebben van het account met een naam in Marketo en alle leads kunnen bekijken binnen één account met een naam.

**Stap 3 -** de verdeling van wij overtroffen lood in 2 emmers: Sterke Gelijke en Zwakke Gelijke.

* Zwak overeenkomende leads worden weergegeven op de benoemde accounts die vervolgens handmatig kunnen worden opgelost.

**Stap 4 -** wij presenteren een lijst van voorgestelde bedrijven met sterke en zwakke gelijken. Wanneer een benoemde account wordt gemaakt op basis van een van de voorgestelde bedrijven, maken we matchingsregels om automatisch nieuwe leads (bijvoorbeeld een ingevuld formulier) te koppelen die naar de juiste benoemde accounts gaan. Op deze manier kunt u zich minder zorgen maken over overeenkomende leads en meer over het verkrijgen van inkomsten.

Aangezien Marketo Lead-to-Account matching een ingebouwde functie is van Marketo [!UICONTROL Target Account Management], leidt matching tot accounts in bijna realtime (zo wordt bijvoorbeeld het moment dat een lead een Marketo-formulier invult, gekoppeld aan de rechteraccount). Deze gebeurtenis kan worden gebruikt om waarschuwingen te activeren en rekeninghouders op de hoogte te stellen van de nieuwe leads die vanuit hun benoemde accounts worden ontvangen.

>[!NOTE]
>
>Als u LeanData in Salesforce gebruikt om Lood-aan-Rekening aanpassing te doen, heeft Marketo een integratie die die gelijken aan uw instantie van Marketo zal synchroniseren. Om die eigenschap te hebben toegelaten, gelieve te contacteren {de Steun van 0} Marketo [ leren hoe te opstelling hieronder LeanData.](https://nation.marketo.com/t5/Support/ct-p/Support)

## LeanData gebruiken voor Afleiden naar Account Matching {#using-leandata-for-lead-to-account-matching}

Nadat [ de Steun van Marketo ](https://nation.marketo.com/t5/Support/ct-p/Support) LeanData voor uw rekening heeft toegelaten, volg de stappen hieronder om het op te zetten.

1. Klik in Salesforce op **[!UICONTROL Setup Home]** in de linkernavigatiebalk.

1. Nog steeds in de linkernav, onder Beheer, klikt u op **[!UICONTROL Users]** en vervolgens op **[!UICONTROL Profiles]** .

1. Bepaal en selecteer het **profiel van de Synchronisatie van Marketo**.

1. Blader omlaag naar de sectie Beveiliging op veldniveau en zoek het object Lead. Selecteer **[!UICONTROL View]** .

1. Voor de veldnaam &quot;Meldend Gelijke Rekening,&quot;zorg checkbox in de **[!UICONTROL Read Access]** kolom ervoor wordt geselecteerd.

1. Ga in Marketo naar de sectie **[!UICONTROL Admin]** .

   ![](assets/lead-to-account-matching-1.png)

1. Selecteer **[!UICONTROL Field Management]** .

   ![](assets/lead-to-account-matching-2.png)

1. Bevestig het gebied daar is door &quot;[!UICONTROL Reporting Matched Account]&quot;te zoeken.

   ![](assets/lead-to-account-matching-3.png)

>[!MORELIKETHIS]
>
>[ ontdekt Rekeningen ](/help/marketo/product-docs/target-account-management/target/named-accounts/discover-accounts.md)
