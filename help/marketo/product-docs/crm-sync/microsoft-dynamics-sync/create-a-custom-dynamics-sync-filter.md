---
unique-page-id: 9437903
description: Creeer een Filter van de Douane  [!DNL Dynamics]  Synchronisatie - de Documenten van Marketo - de Documentatie van het Product
title: Creeer een Filter van de Douane  [!DNL Dynamics]  Synchronisatie
exl-id: 6b0d878a-9c55-4e73-9923-11140e83bb37
feature: Microsoft Dynamics
source-git-commit: 0c0dd3355f979577ec194f9e8f935615515905c0
workflow-type: tm+mt
source-wordcount: '746'
ht-degree: 1%

---

# Een aangepast [!DNL Dynamics] synchronisatiefilter maken {#create-a-custom-dynamics-sync-filter}

Met Marketo kunt u een synchronisatiefilter instellen en slechts een deel van uw records synchroniseren.

## Overzicht {#overview}

Een [!DNL Dynamics] -synchronisatiefilter instellen:

1. Maak een aangepast veld Twee opties (Boolean) met de naam `new_synctomkto` in de Dynamics CRM voor elk object (lead, contact, account, opportunity en andere aangepaste entiteiten).
1. Wijs aan dit veld een waarde Ja/Nee toe.

U moet deze veranderingen in Dynamica CRM, niet uw gegevensbestand of Marketo aanbrengen.

>[!CAUTION]
>
>Als u het veld niet toewijst en dit leeg laat/NULL, wordt het veld gesynchroniseerd, maar niet bijgewerkt. Records met een veldwaarde van blank/NULL in Dynamics CRM zullen deze veldwaarde in Marketo als &quot;false&quot; weergeven.

Marketo zoekt naar dit veld tijdens de automatische achtergrondsynchronisatie en bepaalt op basis van deze logica welke records moeten worden gesynchroniseerd:

| Veldwaarde | Synchroniseren met Marketo? |
|---|---|
| Veld bestaat niet | Ja |
| Veld is leeg | Ja |
| Veld heeft waarde Ja | Ja |
| Veld heeft waarde Nee | Nee |

>[!CAUTION]
>
>De enige manier om Marketo te vertellen om een verslag over te slaan is de gebiedswaarde uitdrukkelijk te plaatsen om **Nr** te zijn. Marketo synchroniseert nog steeds records, zelfs als de veldwaarden leeg zijn.

>[!PREREQUISITES]
>
>Installeer de nieuwste versie van de Marketo-plug-in (3.0.0.1 of hoger). Ga naar Marketo > [!UICONTROL Admin] > [!DNL Microsoft Dynamics] > [!UICONTROL Download Marketo Solution] .

## SyncToMkto-veld maken {#create-synctomkto-field}

1. Log in je Dynamics CRM. Klik **Montages**, dan klik **Aanpassingen**.

   ![](assets/image2015-8-10-21-3a40-3a9.png)

1. Klik op **[!UICONTROL Customize the System]**.

   ![](assets/image2015-8-10-21-3a42-3a15.png)

1. Klik op ![](assets/image2015-8-10-21-3a44-3a23.png) naast **[!UICONTROL Entities]** .

   ![](assets/image2015-8-10-21-3a43-3a39.png)

1. Klik op ![](assets/image2015-8-10-21-3a44-3a23.png) naast **[!UICONTROL Lead]** en selecteer **[!UICONTROL Fields]** . Klik vervolgens op **[!UICONTROL New]** .

   ![](assets/image2015-8-10-21-3a49-3a49.png)

1. Ga **SyncToMkto** op het **[!UICONTROL Display Name]** gebied in en selecteer **[!UICONTROL Two Options]** als **[!UICONTROL Data Type]**. Klik vervolgens op **[!UICONTROL Save and Close]** .

   ![](assets/image2015-9-8-10-3a25-3a33.png)

   >[!NOTE]
   >
   >Kies om het even welke vertoningsnaam voor dit gebied, maar het gebied van de Naam moet precies **new_synctomkto** zijn. U moet **nieuw** als standaardprefix gebruiken. Als u het gebrek hebt veranderd, ga hier [ de standaardprefix voor de namen van het douanegebied ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter/set-a-default-custom-field-prefix.md){target="_blank"} terugstellen. U kunt deze instelling wijzigen nadat u de nieuwe velden hebt gemaakt.

   >[!NOTE]
   >
   >Als u een asynchrone workflow hebt ingesteld, krijgt de record de standaardwaarde voor SyncToMkto die u in het veld hebt ingesteld, en wordt de juiste waarde een paar seconden later opgehaald wanneer de workflow is voltooid. Als de standaardwaarde op Ja is ingesteld, worden deze records in Marketo gemaakt en vervolgens opgeschoond. Gebruik **Nr** als standaardwaarde om dit te vermijden.

1. Herhaal dit proces en creeer het **SyncToMkto** gebied voor om het even welke andere entiteiten u wenst om de synchronisatie, zoals contact, rekening, kans en douaneentiteiten te beperken.

## Selecteer het filter in Marketo {#select-the-filter-in-marketo}

Zelfs als u uw eerste synchronisatie al hebt uitgevoerd, gaat u binnen en selecteert u de velden die met Marketo moeten worden gesynchroniseerd.

1. Ga naar Beheer en selecteer **[!UICONTROL Microsoft Dynamics]** .

   ![](assets/image2015-10-9-9-3a50-3a9.png)

1. Klik op **[!UICONTROL Edit]** Veldsynchronisatiedetails.

   ![](assets/image2015-10-9-9-3a52-3a23.png)

1. Blader omlaag naar het veld en controleer het. De daadwerkelijke naam moet new_synctomkto zijn maar de Naam van de Vertoning kan om het even wat zijn. Klik op **[!UICONTROL Save]**.

   ![](assets/image2015-10-9-9-3a56-3a23.png)

Geweldig, nu hebt u het synchronisatiefilter ingeschakeld voor Marketo.

## Een [!DNL Dynamics] workflow maken om automatisch waarden voor synchronisatiefilters toe te wijzen {#create-a-dynamics-workflow-to-assign-sync-filter-values-automatically}

U kunt altijd handmatig een waarde toewijzen aan de velden SyncToMkto voor uw records. Maar waarom zou u niet profiteren van de kracht van een [!DNL Dynamics] Workflow en automatisch een waarde toewijzen aan het veld SyncToMkto wanneer een record wordt gemaakt of bijgewerkt?

>[!NOTE]
>
>U kunt dit niet op het gegevensbestandniveau doen. Dit moet handmatig gebeuren in de CRM of met behulp van een workflow.
>
>Een [!DNL Dynamics] -werkstroom werkt alleen voor nieuwe records die u maakt, niet voor historische gegevens. Gebruik een batchupdate om over bestaande records te navigeren.

1. Ga naar je Dynamics CRM. Klik **Montages**, toen **Processen**.

   ![](assets/image2015-8-11-8-3a42-3a10.png)

1. Klik op **[!UICONTROL New]**.

   ![](assets/image2015-8-11-8-3a43-3a46.png)

1. Voer een naam voor de workflow in en selecteer **[!UICONTROL Workflow]** als de [!UICONTROL Category] en **[!UICONTROL Lead]** als de [!UICONTROL Entity] . Dan klik O.K. ****.

   ![](assets/image2015-8-11-8-3a45-3a46.png)

1. Creeer regels om een ware of valse waarde aan het **SyncToMkto** gebied toe te wijzen dat op de voorkeur van uw organisatie wordt gebaseerd. Klik op **[!UICONTROL Save and Close]**.

   ![](assets/setsynctomkto-fix.png)

   >[!NOTE]
   >
   >Definieer een standaardhandeling nadat u op **[!UICONTROL Add Step]** hebt geklikt om een voorwaarde voor controle toe te voegen. Dit plaatst de verslagen die u niet aan **Nr** wilt synchroniseren. Anders worden ze gesynchroniseerd.

1. Selecteer de workflow en klik op **[!UICONTROL Activate]** .

   ![](assets/image2015-8-11-8-3a57-3a29.png)

   >[!TIP]
   >
   >Zie [ de Regels van de Filter van de Synchronisatie van de Douane voor een E-mail- Adres ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter/custom-sync-filter-rules-for-an-email-address.md){target="_blank"} aan opstellingsregels om slechts verslagen voor mensen met e-mailadressen te synchroniseren.

## Details van filter synchroniseren {#sync-filter-details}

Hier volgen enkele implementatiedetails die u volgens ons moet weten:

* Synchronisatiebewerking starten

  Wanneer de **SyncToMkto** waarde van **Nr** aan **ja** verandert, [!DNL Dynamics] brengt Marketo onmiddellijk op om dit verslag te beginnen synchroniseren. Als de record al bestaat, wordt deze door Marketo bijgewerkt. Anders maakt Marketo de record.

* Synchronisatiebewerking stoppen

  Wanneer een record de waarde SyncToMkto wijzigt van Ja in Nee, wordt Marketo een melding gestuurd dat de synchronisatie van deze record moet worden gestopt. De record wordt echter niet verwijderd, maar houdt op met het ophalen van updates en wordt &#39;stale&#39;.

>[!MORELIKETHIS]
>
>* [ de Filter van de Synchronisatie van Microsoft Dynamics: Kwalificeer ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter/microsoft-dynamics-sync-filter-qualify.md){target="_blank"}
>* [ de Filter van de Synchronisatie van Microsoft Dynamics: Samenvoegen ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter/microsoft-dynamics-sync-filter-merge.md){target="_blank"}
>* [ de Regels van de Filter van de Synchronisatie van de Douane voor een E-mailAdres ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter/custom-sync-filter-rules-for-an-email-address.md){target="_blank"}
