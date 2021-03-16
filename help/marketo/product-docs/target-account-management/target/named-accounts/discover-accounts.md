---
unique-page-id: 11378812
description: Accounts ontdekken - Marketo Docs - Productdocumentatie
title: Accounts detecteren
translation-type: tm+mt
source-git-commit: 9f88e7cebc5e9d0d4491d65d332ccfdd9a31c395
workflow-type: tm+mt
source-wordcount: '585'
ht-degree: 0%

---


# Accounts {#discover-accounts} detecteren

Gebruik de optie Ontdekken om potentiële doelaccounts te identificeren.

## CRM-accounts detecteren {#discover-crm-accounts}

Identificeer potentiële doelrekeningen van uw CRM.

>[!NOTE]
>
>Nadat u uw CRM met Marketo TAM verbindt, **ontdekt de Rekeningen van CRM** zal alle rekeningen van CRM en relevante informatie tonen om u te helpen de juiste genoemde rekeningen kiezen. Marketo voegt extra informatie toe bovenop wat van CRM wordt ontvangen.

**Personen**  (in het geval van CRM-accounts en markttoegang ontdekken): Omvat zowel Contacten als Leads. Leads kunnen worden gedetecteerd met behulp van [lead-to-account matching](/help/marketo/product-docs/target-account-management/target/named-accounts/lead-to-account-matching.md) van Marketo.

**Potentiële personen**  (bij het ontdekken van CRM-accounts en het ontdekken van marktobedrijven): Toont hoeveel lood Marketo vond die tot een rekening van CRM kon behoren.

**Aangepast CRM-veld**  (alleen in CRM-rekeningen ontdekken): Op deze manier kunt u uw verkoop- en marketingorganisatie beter afstemmen op de juiste doelaccounts. Zodra u [het gebied van douaneCRM](/help/marketo/product-docs/target-account-management/setup-tam/create-a-custom-field-for-crm-discovery.md) met Marketo TAM in kaart brengt, zullen wij u de in kaart gebrachte gegevens tonen om u te helpen uw doelrekeningen identificeren.

1. Klik in Benoemde accounts op de vervolgkeuzelijst **Nieuw** en selecteer **CRM-accounts detecteren**.

   ![](assets/disc-crm-one.png)

1. Er wordt een nieuw venster/tabblad geopend. Selecteer de CRM-account(s) die u wilt toevoegen aan uw benoemde accounts en klik op **Volgende**.

   ![](assets/disc-crm-two.png)

1. Het voorvertoningsscherm bevestigt de hoeveelheid selecties. Klik **Maken**.

   ![](assets/disc-three.png)

   Dat is alles wat er aan te pas komt!

   ![](assets/disc-four.png)

## Marketo Companies {#discover-marketo-companies} detecteren

Identificeer de juiste bedrijven voor het richten.

>[!NOTE]
>
>In Discover Marketo Companies zie je Marketo-bedrijven die niet van je CRM afkomstig waren.

1. Klik in Benoemde accounts op de vervolgkeuzelijst **Nieuw** en selecteer **Marketo-bedrijven detecteren**.

   ![](assets/one-1.png)

1. Er wordt een nieuw venster/tabblad geopend. Selecteer de bedrijven u aan uw Benoemde Rekeningen wilt toevoegen en **daarna** klikken.

   ![](assets/disc-comp-two.png)

   >[!NOTE]
   >
   >In Discover Marketo Companies en Discover CRM, Marketo automatisch:
   >
   >* Vindt mensen van uw gegevensbestand van Marketo die dat bedrijf in hun verslag hebben vermeld. Als u meerdere waarden ziet voor sommige kenmerken (bijvoorbeeld in de industrie), komt dat doordat Marketo verschillende waarden heeft gevonden die voor die individuele personen zijn vermeld. Het kenmerk met de meest treffers wint
   >
   >Alleen in **CRM** detecteren, markeert automatisch:
   >
   >* Syncs and associates CRM Contact with the Named Account
   >
   >In **Alleen Marketo Companies** detecteren, markeert u automatisch:
   >
   >* Filters uit de meeste Dienstverleners van Internet en Openbare Domeinen (b.v., yahoo.com, gmail.com) als bedrijfnamen
      >
      >
   * Deupes CRM accounts. Als u Acme in één record hebt en Acme Inc (of een van de volgende achtervoegsels): Co, Corp, Corporation, Gmbh, Inc, Incorporated, LLC, LLP, LP, Ltd, PA, PC, PLC, PLLC), zullen wij hen in TAM als enkel &quot;Acme&quot; samenvoegen
   >
   >Als u Marketo-accounts wilt dedupliceren door CRM-id of rekeningeigenaar in plaats van door bedrijfsnaam, neemt u contact op met [Marketo-ondersteuning](https://nation.marketo.com/t5/Support/ct-p/Support).

1. Klik op de pijl-omlaag onder de kolom Benoemd account om de vervolgkeuzelijst weer te geven.

   ![](assets/disc-comp-three.png)

   >[!CAUTION]
   >
   >In de toekomst zullen nieuwe personen van deze geselecteerde bedrijven automatisch worden toegewezen aan hun respectievelijke benoemde accounts. Controleer deze bedrijven nogmaals en controleer of ze zijn toegewezen aan de juiste benoemde account.

1. Als u een bestaande account wilt selecteren, klikt u op de vervolgkeuzelijst **Benoemd account** en kiest u de gewenste account. Klik vervolgens op **Volgende**.

   ![](assets/disc-comp-four.png)

   U kunt ook een nieuwe benoemde account maken door de gewenste naam rechtstreeks in de keuzelijst te typen. Klik buiten het vak als u klaar bent...

   ![](assets/disc-comp-five.png)

   ...en u ziet uw nieuwe Benoemde Account. Op dat punt klik enkel **Volgende** als in Stap 4.

   ![](assets/disc-comp-six.png)

1. Klik **Maken**.

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
