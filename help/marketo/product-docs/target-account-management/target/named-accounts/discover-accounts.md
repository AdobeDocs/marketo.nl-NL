---
unique-page-id: 11378812
description: Accounts ontdekken - Marketo Docs - Productdocumentatie
title: Accounts detecteren
exl-id: 90da4ae0-0a12-48bd-8bae-a7431d2cf4f4
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '585'
ht-degree: 0%

---

# Accounts detecteren {#discover-accounts}

Gebruik de optie Ontdekken om potentiële doelaccounts te identificeren.

## CRM-accounts detecteren {#discover-crm-accounts}

Identificeer potentiële doelrekeningen van uw CRM.

>[!NOTE]
>
>Nadat u uw CRM met Marketo TAM verbindt, **CRM-accounts detecteren** Alle CRM-accounts en relevante informatie worden weergegeven, zodat u de juiste benoemde accounts kunt kiezen. Marketo voegt extra informatie toe bovenop wat van CRM wordt ontvangen.

**Mensen** (In Discover CRM Accounts &amp; Discover Marketo Companies): Omvat zowel Contacten als Leads. Leads kunnen worden gedetecteerd met Marketo [lead-to-account-matching](/help/marketo/product-docs/target-account-management/target/named-accounts/lead-to-account-matching.md).

**Potentiële mensen** (In Discover CRM Accounts &amp; Discover Marketo Companies): Toont hoeveel lood Marketo vond die tot een rekening van CRM kon behoren.

**Aangepast CRM-veld** (Alleen CRM-rekeningen detecteren): Op deze manier kunt u uw verkoop- en marketingorganisatie beter afstemmen op de juiste doelaccounts. Eenmaal [het aangepaste CRM-veld toewijzen](/help/marketo/product-docs/target-account-management/setup-tam/create-a-custom-field-for-crm-discovery.md) met Marketo TAM zullen we u de toegewezen gegevens tonen om u te helpen uw doelaccounts te identificeren.

1. Klik in Benoemde accounts op de knop **Nieuw** vervolgkeuzelijst en selecteer **CRM-accounts detecteren**.

   ![](assets/disc-crm-one.png)

1. Er wordt een nieuw venster/tabblad geopend. Selecteer de CRM-account(s) die u wilt toevoegen aan uw benoemde accounts en klik op **Volgende**.

   ![](assets/disc-crm-two.png)

1. Het voorvertoningsscherm bevestigt de hoeveelheid selecties. Klikken **Maken**.

   ![](assets/disc-three.png)

   Dat is alles wat er aan te pas komt!

   ![](assets/disc-four.png)

## Ontdek Marketo Companies {#discover-marketo-companies}

Identificeer de juiste bedrijven voor het richten.

>[!NOTE]
>
>In Discover Marketo Companies zie je Marketo-bedrijven die niet van je CRM kwamen.

1. Klik in Benoemde accounts op de knop **Nieuw** vervolgkeuzelijst en selecteer **Ontdek Marketo Companies**.

   ![](assets/one-1.png)

1. Er wordt een nieuw venster/tabblad geopend. Selecteer de bedrijven die u wilt toevoegen aan uw benoemde accounts en klik op **Volgende**.

   ![](assets/disc-comp-two.png)

   >[!NOTE]
   >
   >In Discover Marketo Companies en Discover CRM, Marketo automatisch:
   >
   >* Zoekt mensen uit uw Marketo-database die dat bedrijf in hun record hebben opgenomen. Als u meerdere waarden ziet voor sommige kenmerken (bijvoorbeeld Industry), komt dit doordat Marketo verschillende waarden heeft gevonden die voor die individuele personen zijn vermeld. Het kenmerk met de meest treffers wint
   >
   >In **CRM detecteren** alleen, Marketo automatisch:
   >
   >* Syncs and associates CRM Contact with the Named Account
   >
   >In **Ontdek Marketo Companies** alleen, Marketo automatisch:
   >
   >* Filters uit de meeste Dienstverleners van Internet en Openbare Domeinen (b.v., yahoo.com, gmail.com) als bedrijfnamen
   >
   >* Deupes CRM accounts. Als u Acme in één record hebt en Acme Inc (of een van de volgende achtervoegsels): Co, Corp, Corporation, Gmbh, Inc, Incorporated, LLC, LLP, LP, Ltd, PA, PC, PLC, PLLC), zullen wij hen in TAM als enkel &quot;Acme&quot; samenvoegen

   >
   >Als je wilt dat Marketo accounts dedupliceert door CRM ID of accounteigenaar in plaats van door Company Name, neem dan contact op met [Marketo-ondersteuning](https://nation.marketo.com/t5/Support/ct-p/Support).

1. Klik op de pijl-omlaag onder de kolom Benoemd account om de vervolgkeuzelijst weer te geven.

   ![](assets/disc-comp-three.png)

   >[!CAUTION]
   >
   >In de toekomst zullen nieuwe personen van deze geselecteerde bedrijven automatisch worden toegewezen aan hun respectievelijke benoemde accounts. Controleer deze bedrijven nogmaals en controleer of ze zijn toegewezen aan de juiste benoemde account.

1. Als u een bestaande account wilt selecteren, klikt u op de knop **Benoemd account** keuzelijst, kies het gewenste account en klik op **Volgende**.

   ![](assets/disc-comp-four.png)

   U kunt ook een nieuwe benoemde account maken door de gewenste naam rechtstreeks in de keuzelijst te typen. Klik buiten het vak als u klaar bent...

   ![](assets/disc-comp-five.png)

   ...en u ziet uw nieuwe Benoemde Account. Op dat punt klikt u op **Volgende** zoals in Stap 4.

   ![](assets/disc-comp-six.png)

1. Klikken **Maken**.

   ![](assets/disc-comp-seven.png)

   Mooi werk!

   ![](assets/disc-co-six.png)

>[!NOTE]
>
>Als u een wanverhouding tussen de rekeningen ziet CRM u hebt geselecteerd en wat in het Discover Net van CRM is, is het waarschijnlijk toe te schrijven aan één of meerdere van het volgende:
>
>* Verschillende CRM-accounts met vergelijkbare namen die zijn gededupeerd
>* De volgende geplande synchronisatie is nog niet opgetreden


>[!MORELIKETHIS]
>
>[Lood naar overeenkomst met account](/help/marketo/product-docs/target-account-management/target/named-accounts/lead-to-account-matching.md)
