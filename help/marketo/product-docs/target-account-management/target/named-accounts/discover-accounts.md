---
unique-page-id: 11378812
description: Accounts ontdekken - Marketo Docs - Productdocumentatie
title: Accounts detecteren
exl-id: 90da4ae0-0a12-48bd-8bae-a7431d2cf4f4
feature: Target Account Management
source-git-commit: dd4c8472ec3f453462bd8046daf70c89c587724a
workflow-type: tm+mt
source-wordcount: '558'
ht-degree: 0%

---

# Accounts detecteren {#discover-accounts}

Gebruik de optie Ontdekken om potentiële doelaccounts te identificeren.

## CRM-accounts detecteren {#discover-crm-accounts}

Identificeer potentiële doelrekeningen van uw CRM.

>[!NOTE]
>
>Nadat u uw CRM met Marketo TAM verbindt, **ontdekt de Rekeningen van CRM** alle rekeningen van CRM en relevante informatie zal tonen om u te helpen de juiste genoemde rekeningen kiezen. Marketo voegt extra informatie toe bovenop wat van CRM wordt ontvangen.

**Mensen** (in ontdekt de Rekeningen van CRM &amp; ontdekt de Bedrijven van Marketo): Omvat zowel Contacten als Leads. De leiders kunnen worden ontdekt gebruikend Marketo [ lood-aan-rekening aanpassing ](/help/marketo/product-docs/target-account-management/target/named-accounts/lead-to-account-matching.md).

**Potentiële Mensen** (in ontdekt de Rekeningen van CRM &amp; ontdekt de Bedrijven van Marketo): Toont hoeveel lood Marketo vond die tot een rekening van CRM kon behoren.

**het gebied van CRM van de Douane** (In ontdekt de Rekeningen van CRM slechts): Dit zal u helpen uw verkoop en marketing organisatie voor selectie van correcte doelrekeningen richten. Zodra u [ het gebied van douaneCRM ](/help/marketo/product-docs/target-account-management/setup-tam/create-a-custom-field-for-crm-discovery.md) met Marketo TAM in kaart brengt, zullen wij u de in kaart gebrachte gegevens tonen om u te helpen uw doelrekeningen identificeren.

1. In Benoemde Rekeningen, klik **Nieuwe** drop-down en selecteer **ontdekt de Rekeningen van CRM**.

   ![](assets/disc-crm-one.png)

1. Er wordt een nieuw venster/tabblad geopend. Selecteer de rekening(en) van CRM u aan uw Benoemde Rekeningen wilt toevoegen en **daarna** klikken.

   ![](assets/disc-crm-two.png)

1. Het voorvertoningsscherm bevestigt de hoeveelheid selecties. Klik **creëren**.

   ![](assets/disc-three.png)

   Dat is alles wat er aan te pas komt!

   ![](assets/disc-four.png)

## Ontdek Marketo Companies {#discover-marketo-companies}

Identificeer de juiste bedrijven voor het richten.

>[!NOTE]
>
>In Discover Marketo Companies zie je Marketo-bedrijven die niet van je CRM afkomstig waren.

1. In Benoemde Rekeningen, klik **Nieuwe** drop-down en selecteer **ontdekken de Bedrijven van Marketo**.

   ![](assets/one-1.png)

1. Er wordt een nieuw venster/tabblad geopend. Selecteer de bedrijven u aan uw Benoemde Rekeningen wilt toevoegen en **daarna** klikken.

   ![](assets/disc-comp-two.png)

   >[!NOTE]
   >
   >In Discover Marketo Companies en Discover CRM, Marketo automatisch:
   >
   >* Zoekt mensen uit uw Marketo-database die dat bedrijf in hun record hebben opgenomen. Als u meerdere waarden ziet voor sommige kenmerken (bijvoorbeeld Industry), komt dit doordat Marketo verschillende waarden heeft gevonden die voor die individuele personen zijn vermeld. Het kenmerk met de meest treffers wint
   >
   >In **ontdekt CRM** slechts, Marketo automatisch:
   >
   >* Syncs and associates CRM Contact with the Named Account
   >
   >In **ontdekt de Bedrijven van Marketo** slechts, Marketo automatisch:
   >
   >* Hiermee worden de meeste internetserviceproviders en openbare domeinen (bijv. yahoo.com, gmail.com) als bedrijfsnamen gefilterd
   >
   >* Deupes CRM accounts. Als u &quot;Acme&quot;in één verslag en &quot;Acme Inc&quot; (of om het even welke volgende achtervoegsels hebt: Co, Corp, Corporation, Gmbh, Inc, Incorporated, LLC, LLP, LP, Ltd, PA, PC, PLC, PLLC), zullen wij hen in TAM als enkel &quot;Acme&quot; samenvoegen

1. Klik op de pijl-omlaag onder de kolom Benoemd account om de vervolgkeuzelijst weer te geven.

   ![](assets/disc-comp-three.png)

   >[!CAUTION]
   >
   >In de toekomst zullen nieuwe personen van deze geselecteerde bedrijven automatisch worden toegewezen aan hun respectievelijke benoemde accounts. Controleer deze bedrijven nogmaals en controleer of ze zijn toegewezen aan de juiste benoemde account.

1. Om een bestaande Rekening te selecteren, klik **Genoemde Rekening** drop-down, kies de gewenste rekening, dan klik **daarna**.

   ![](assets/disc-comp-four.png)

   U kunt ook een nieuwe benoemde account maken door de gewenste naam rechtstreeks in de keuzelijst te typen. Klik buiten het vak als u klaar bent...

   ![](assets/disc-comp-five.png)

   ...en u zult uw nieuw Benoemd Rekening zien. Op dat punt klik enkel **daarna** als in Stap 4.

   ![](assets/disc-comp-six.png)

1. Klik **creëren**.

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
>[ Lood aan de Vergelijking van de Rekening ](/help/marketo/product-docs/target-account-management/target/named-accounts/lead-to-account-matching.md)
