---
unique-page-id: 9437903
description: Een aangepast synchronisatiefilter voor dynamiek maken - Marketo Docs - Productdocumentatie
title: Een filter voor aangepaste dynamicasynchronisatie maken
exl-id: 6b0d878a-9c55-4e73-9923-11140e83bb37
feature: Microsoft Dynamics
source-git-commit: a9aa55184a7971d3c82d106481f1f83593a7dd99
workflow-type: tm+mt
source-wordcount: '795'
ht-degree: 0%

---

# Een filter voor aangepaste dynamicasynchronisatie maken {#create-a-custom-dynamics-sync-filter}

Wilt u niet alles in uw Dynamics CRM synchroniseren naar Marketo? Maak je geen zorgen! Met Marketo kunt u een synchronisatiefilter instellen en slechts een deel van uw records synchroniseren.

## Overzicht {#overview}

Een filter voor het synchroniseren van dynamiek instellen:

1. Creeer een douane twee van Opties (booleaanse) gebied genoemd new_synctomkto in uw Dynamica CRM voor om het even welk voorwerp (lood, contact, rekening, kans en andere douaneentiteiten).
1. Wijs aan dit veld een waarde Ja/Nee toe.

U moet deze veranderingen in Dynamica CRM, niet uw gegevensbestand of Marketo aanbrengen.

>[!CAUTION]
>
>Als u het veld niet toewijst en dit leeg laat/NULL, wordt het veld gesynchroniseerd, maar niet bijgewerkt.

Marketo zoekt naar dit veld tijdens de automatische achtergrondsynchronisatie en bepaalt op basis van deze logica welke records moeten worden gesynchroniseerd:

| Veldwaarde | Synchroniseren met Marketo? |
|---|---|
| Veld bestaat niet | Ja |
| Veld is leeg | Ja |
| Veld heeft waarde Ja | Ja |
| Veld heeft waarde Nee | Nee |

>[!CAUTION]
>
>De enige manier waarop Marketo een record kan overslaan, is door expliciet in te stellen dat de veldwaarde **Nee**. Marketo synchroniseert nog steeds records, zelfs als de veldwaarden leeg zijn.

>[!PREREQUISITES]
>
>Installeer de nieuwste versie van de Marketo-plug-in (3.0.0.1 of hoger). Ga naar Marketo > Admin > Microsoft Dynamics > Download Marketo Solution.

## SyncToMkto-veld maken {#create-synctomkto-field}

1. Log in je Dynamics CRM. Klikken **Instellingen** en klik vervolgens op **Aanpassingen**.

   ![](assets/image2015-8-10-21-3a40-3a9.png)

1. Klikken **Het systeem aanpassen**.

   ![](assets/image2015-8-10-21-3a42-3a15.png)

1. Klikken ![](assets/image2015-8-10-21-3a44-3a23.png) naast **Entiteiten**.

   ![](assets/image2015-8-10-21-3a43-3a39.png)

1. Klikken ![](assets/image2015-8-10-21-3a44-3a23.png) naast **Lood** en selecteert u **Velden**. Klik vervolgens op **Nieuw**.

   ![](assets/image2015-8-10-21-3a49-3a49.png)

1. Enter **SyncToMkto** in de **Weergavenaam** veld en selecteer **Twee opties** als de **Gegevenstype**. Klik vervolgens op **Opslaan en sluiten**.

   ![](assets/image2015-9-8-10-3a25-3a33.png)

   >[!NOTE]
   >
   >Kies een willekeurige weergavenaam voor dit veld, maar het veld Naam moet exact **new_synctomkto**. U moet **new** als het standaardvoorvoegsel. Als u de standaard hebt gewijzigd, gaat u hier naar [het standaardvoorvoegsel voor aangepaste veldnamen opnieuw instellen](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter/set-a-default-custom-field-prefix.md){target="_blank"}. U kunt deze instelling wijzigen nadat u de nieuwe velden hebt gemaakt.

   >[!NOTE]
   >
   >Als u een asynchrone workflow hebt ingesteld, krijgt de record de standaardwaarde voor SyncToMkto die u in het veld hebt ingesteld, en wordt de juiste waarde een paar seconden later opgehaald wanneer de workflow is voltooid. Als de standaardwaarde op Ja is ingesteld, worden deze records in Marketo gemaakt en vervolgens opgeschoond. Gebruiken **Nee** als standaardwaarde om dit te voorkomen.

1. Herhaal dit proces en maak de **SyncToMkto** veld voor andere entiteiten die u wilt synchroniseren, zoals contact, account, opportuniteit en aangepaste entiteiten.

## Selecteer het filter in Marketo {#select-the-filter-in-marketo}

Zelfs als u uw eerste synchronisatie al hebt uitgevoerd, gaat u binnen en selecteert u de velden die met Marketo moeten worden gesynchroniseerd.

1. Ga naar Beheerder en selecteer **[!UICONTROL Microsoft Dynamics]**.

   ![](assets/image2015-10-9-9-3a50-3a9.png)

1. Klikken **[!UICONTROL Edit]** op veld Sync details.

   ![](assets/image2015-10-9-9-3a52-3a23.png)

1. Blader omlaag naar het veld en controleer het. De daadwerkelijke naam moet new_synctomkto zijn maar de Naam van de Vertoning kan om het even wat zijn. Klik op **[!UICONTROL Save]**.

   ![](assets/image2015-10-9-9-3a56-3a23.png)

Geweldig, nu hebt u het synchronisatiefilter ingeschakeld voor Marketo.

## Een dynamiekworkflow maken om automatisch waarden voor synchronisatiefilters toe te wijzen {#create-a-dynamics-workflow-to-assign-sync-filter-values-automatically}

U kunt altijd handmatig een waarde toewijzen aan de velden SyncToMkto voor uw records. Maar waarom voordeel niet uit de macht van een Workflow van de Dynamica en auto-wijs een waarde aan het gebied SyncToMkto toe wanneer een verslag wordt gecreeerd of bijgewerkt?

>[!NOTE]
>
>U kunt dit niet op het gegevensbestandniveau doen. Dit moet handmatig gebeuren in de CRM of met behulp van een workflow.
>
>Een workflow voor dynamiek werkt alleen voor nieuwe records die u maakt en niet voor historische gegevens. Gebruik een batchupdate om over bestaande records te navigeren.

1. Ga naar je Dynamics CRM. Klikken **Instellingen** vervolgens **Processen**.

   ![](assets/image2015-8-11-8-3a42-3a10.png)

1. Klikken **Nieuw**.

   ![](assets/image2015-8-11-8-3a43-3a46.png)

1. Voer een naam in voor de workflow en selecteer **Workflow** als categorie en **Lood** als de Entiteit. Klik vervolgens op **OK**.

   ![](assets/image2015-8-11-8-3a45-3a46.png)

1. Maak regels om een waarde waar of onwaar aan de **SyncToMkto** op basis van de voorkeur van uw organisatie. Klikken **Opslaan en sluiten**.

   ![](assets/setsynctomkto-fix.png)

   >[!NOTE]
   >
   >Een standaardhandeling definiëren nadat u hebt geklikt **Stap toevoegen** om een voorwaarde van de Controle toe te voegen. Hiermee worden de records ingesteld die u niet wilt synchroniseren **Nee**. Anders worden ze gesynchroniseerd.

1. Selecteer de workflow en klik op **Activeren**.

   ![](assets/image2015-8-11-8-3a57-3a29.png)

   >[!TIP]
   >
   >Zie [Aangepaste filterregels voor synchronisatie voor een e-mailadres](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter/custom-sync-filter-rules-for-an-email-address.md){target="_blank"} om regels in te stellen voor het synchroniseren van alleen records voor mensen met e-mailadressen.

## Details van filter synchroniseren {#sync-filter-details}

Hier volgen enkele implementatiedetails die u volgens ons moet weten:

* Synchronisatiebewerking starten

  Wanneer de **SyncToMkto** waarde verandert van **Nee** tot **Ja** Dynamics waarschuwt Marketo onmiddellijk om deze record te synchroniseren. Als de record al bestaat, wordt deze door Marketo bijgewerkt. Anders maakt Marketo de record.

  >[!TIP]
  >
  >A `Create [StartSync]` bewerking wordt toegevoegd aan het Marketo-logboek wanneer dit gebeurt.

* Synchronisatiebewerking stoppen

  Wanneer een record de waarde SyncToMkto wijzigt van Ja in Nee, wordt Marketo een melding gestuurd dat de synchronisatie van deze record moet worden gestopt. De record wordt echter niet verwijderd, maar houdt op met het ophalen van updates en wordt &#39;stale&#39;.

>[!MORELIKETHIS]
>
>* [Filter voor synchronisatie met Microsoft-dynamiek: kwalificeren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter/microsoft-dynamics-sync-filter-qualify.md){target="_blank"}
>* [Filter voor synchronisatie bij Microsoft: samenvoegen](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter/microsoft-dynamics-sync-filter-merge.md){target="_blank"}
>* [Aangepaste filterregels voor synchronisatie voor een e-mailadres](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter/custom-sync-filter-rules-for-an-email-address.md){target="_blank"}
