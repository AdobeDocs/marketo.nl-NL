---
unique-page-id: 11378812
description: Accounts ontdekken - Marketo Docs - Productdocumentatie
title: Accounts detecteren
exl-id: 90da4ae0-0a12-48bd-8bae-a7431d2cf4f4
feature: Target Account Management
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '491'
ht-degree: 0%

---

# Accounts detecteren {#discover-accounts}

Gebruik de optie Ontdekken om potentiële doelaccounts te identificeren.

## [!UICONTROL Discover CRM Accounts] {#discover-crm-accounts}

Identificeer potentiële doelrekeningen van uw CRM.

>[!NOTE]
>
>Nadat u uw CRM met Marketo TAM verbindt, **[!UICONTROL Discover CRM Accounts]** zal alle rekeningen van CRM en relevante informatie tonen om u te helpen de juiste genoemde rekeningen kiezen. Marketo voegt extra informatie toe bovenop wat van CRM wordt ontvangen.

**[!UICONTROL People]** (In [!UICONTROL Discover CRM Accounts] &amp; [!UICONTROL Discover Marketo Companies]): bevat zowel contactpersonen als regelafstand. De leiders kunnen worden ontdekt gebruikend Marketo [ lood-aan-rekening aanpassing ](/help/marketo/product-docs/target-account-management/target/named-accounts/lead-to-account-matching.md).

**[!UICONTROL Potential People]** (In [!UICONTROL Discover CRM Accounts] &amp; [!UICONTROL Discover Marketo Companies] ): geeft aan hoeveel leads Marketo heeft gevonden die mogelijk tot een CRM-account behoren.

**het gebied van CRM van de Douane** (In ontdekt de Rekeningen van CRM slechts): Dit zal u helpen uw verkoop en marketing organisatie voor selectie van correcte doelrekeningen richten. Zodra u [ het gebied van douaneCRM ](/help/marketo/product-docs/target-account-management/setup-tam/create-a-custom-field-for-crm-discovery.md) met Marketo TAM in kaart brengt, zullen wij u de in kaart gebrachte gegevens tonen om u te helpen uw doelrekeningen identificeren.

1. Klik in [!UICONTROL Named Accounts] op de vervolgkeuzelijst **[!UICONTROL New]** en selecteer **[!UICONTROL Discover CRM Accounts]** .

   ![](assets/disc-crm-one.png)

1. Er wordt een nieuw venster/tabblad geopend. Selecteer de CRM-account(s) die u aan uw [!UICONTROL Named Accounts] wilt toevoegen en klik op **[!UICONTROL Next]** .

   ![](assets/disc-crm-two.png)

1. Het voorvertoningsscherm bevestigt de hoeveelheid selecties. Klik op **[!UICONTROL Create]**.

   ![](assets/disc-three.png)

   Dat is alles wat er aan te pas komt!

   ![](assets/disc-four.png)

## [!UICONTROL Discover Marketo Companies] {#discover-marketo-companies}

Identificeer de juiste bedrijven voor het richten.

>[!NOTE]
>
>In [!UICONTROL Discover Marketo Companies] zie je Marketo-bedrijven die niet van je CRM kwamen.

1. Klik in [!UICONTROL Named Accounts] op de vervolgkeuzelijst **[!UICONTROL New]** en selecteer **[!UICONTROL Discover Marketo Companies]** .

   ![](assets/one-1.png)

1. Er wordt een nieuw venster/tabblad geopend. Selecteer de bedrijven die u aan uw [!UICONTROL Named Accounts] wilt toevoegen en klik op **[!UICONTROL Next]** .

   ![](assets/disc-comp-two.png)

   >[!NOTE]
   >
   >In [!UICONTROL Discover Marketo Companies] en Discover CRM, Marketo automatisch:
   >
   >* Zoekt mensen uit uw Marketo-database die dat bedrijf in hun record hebben opgenomen. Als u meerdere waarden ziet voor sommige kenmerken (bijvoorbeeld Industry), komt dit doordat Marketo verschillende waarden heeft gevonden die voor die individuele personen zijn vermeld. Het kenmerk met de meest treffers wint
   >
   >In **ontdekt CRM** slechts, Marketo automatisch:
   >
   >* Hiermee synchroniseert en koppelt u CRM-contacten met de [!UICONTROL Named Account]
   >
   >Alleen in **[!UICONTROL Discover Marketo Companies]** wordt Marketo automatisch:
   >
   >* Hiermee worden de meeste internetserviceproviders en openbare domeinen (bijv. yahoo.com, gmail.com) als bedrijfsnamen gefilterd
   >
   >* Deupes CRM accounts. Als u &quot;Acme&quot;in één verslag en &quot;Acme Inc&quot; (of om het even welke volgende achtervoegsels hebt: Co, Corp, Corporation, Gmbh, Inc, Incorporated, LLC, LLP, LP, Ltd, PA, PC, PLC, PLLC), zullen wij hen in TAM als enkel &quot;Acme&quot; samenvoegen

1. Klik op de pijl-omlaag onder de kolom [!UICONTROL Named Account] om de vervolgkeuzelijst weer te geven.

   ![](assets/disc-comp-three.png)

   >[!CAUTION]
   >
   >In de toekomst zullen nieuwe personen van deze geselecteerde bedrijven automatisch worden toegewezen aan hun respectievelijke benoemde accounts. Controleer deze bedrijven nogmaals en zorg ervoor dat ze aan de juiste [!UICONTROL Named Account] zijn toegewezen.

1. Als u een bestaande account wilt selecteren, klikt u op de vervolgkeuzelijst **[!UICONTROL Named Account]** , kiest u de gewenste account en klikt u op **[!UICONTROL Next]** .

   ![](assets/disc-comp-four.png)

   U kunt ook een nieuwe [!UICONTROL Named Account] maken door de gewenste naam rechtstreeks in de vervolgkeuzelijst te typen. Klik buiten het vak als u klaar bent...

   ![](assets/disc-comp-five.png)

   ...en u zult uw nieuwe [!UICONTROL Named Account] zien. Klik op dat punt op **[!UICONTROL Next]** zoals in stap 4.

   ![](assets/disc-comp-six.png)

1. Klik op **[!UICONTROL Create]**.

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
