---
unique-page-id: 9437903
description: Een aangepast synchronisatiefilter voor dynamiek maken - Marketo Docs - Productdocumentatie
title: Een filter voor aangepaste dynamicasynchronisatie maken
exl-id: 6b0d878a-9c55-4e73-9923-11140e83bb37
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '785'
ht-degree: 0%

---

# Een filter voor aangepaste dynamicasynchronisatie maken {#create-a-custom-dynamics-sync-filter}

Wilt u niet alles in uw Dynamics CRM synchroniseren naar Marketo? Maak je geen zorgen! Met Marketo kunt u een synchronisatiefilter instellen en slechts een deel van uw records synchroniseren.

## Overzicht {#overview}

Een filter voor het synchroniseren van dynamiek instellen:

1. Creeer een douane twee van Opties (booleaanse) gebied genoemd new_synctomkto in uw Dynamica CRM voor om het even welk voorwerp (lood, contact, rekening, kans en andere douaneentiteiten).
1. Wijs in dit veld een waarde Ja/Nee toe of laat het veld leeg.

>[!NOTE]
>
>U moet deze veranderingen in Dynamica CRM, niet uw gegevensbestand of Marketo aanbrengen.

Marketo zoekt naar dit veld tijdens de automatische achtergrondsynchronisatie en bepaalt op basis van deze logica welke records moeten worden gesynchroniseerd:

| Veldwaarde | Synchroniseren met Marketo? |
|---|---|
| Veld bestaat niet | Ja |
| Veld is leeg | Ja |
| Veld heeft waarde Ja | Ja |
| Veld heeft waarde Nee | Nee |

>[!CAUTION]
>
>De enige manier om Marketo te vertellen een verslag over te slaan is de gebiedswaarde uitdrukkelijk te plaatsen om **nr** te zijn. Marketo synchroniseert nog steeds records, zelfs als de veldwaarden leeg zijn.

>[!PREREQUISITES]
>
>Installeer de nieuwste versie van de Marketo-plug-in (3.0.0.1 of hoger). Ga naar Marketo > Admin > Microsoft Dynamics > Download Marketo Solution.

## SyncToMkto-veld {#create-synctomkto-field} maken

1. Log in Dynamics CRM. Klik **Instellingen** en klik dan **Aanpassingen**.

   ![](assets/image2015-8-10-21-3a40-3a9.png)

1. Klik **Pas het Systeem** aan.

   ![](assets/image2015-8-10-21-3a42-3a15.png)

1. Klik ![](assets/image2015-8-10-21-3a44-3a23.png) naast **Entiteiten**.

   ![](assets/image2015-8-10-21-3a43-3a39.png)

1. Klik ![](assets/image2015-8-10-21-3a44-3a23.png) naast **Lead** en selecteer **Fields**. Klik vervolgens op **Nieuw**.

   ![](assets/image2015-8-10-21-3a49-3a49.png)

1. Typ **SyncToMkto** in het veld **Weergavenaam** en selecteer **Twee opties** als **Gegevenstype**. Klik vervolgens op **Opslaan en sluiten**.

   ![](assets/image2015-9-8-10-3a25-3a33.png)

   >[!NOTE]
   >
   >Kies een willekeurige weergavenaam voor dit veld, maar het veld Naam moet exact **new_synctomkto** zijn. U moet **new** als standaardprefix gebruiken. Als u het gebrek hebt veranderd, ga hier naar [stel het standaardvoorvoegsel voor de namen van douanegebieden ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter/set-a-default-custom-field-prefix.md) terug. U kunt deze instelling wijzigen nadat u de nieuwe velden hebt gemaakt.

   >[!NOTE]
   >
   >Als u een asynchrone workflow hebt ingesteld, krijgt de record de standaardwaarde voor SyncToMkto die u in het veld hebt ingesteld, en wordt de juiste waarde een paar seconden later opgehaald wanneer de workflow is voltooid. Als de standaardwaarde op Ja is ingesteld, worden deze records in Marketo gemaakt en vervolgens opgeschoond. Gebruik **No** als standaardwaarde om dit te voorkomen.

1. Herhaal dit proces en maak het veld **SyncToMkto** voor alle andere entiteiten waarvoor u de synchronisatie wilt beperken, zoals contact, account, opportuniteit en aangepaste entiteiten.

## Selecteer het filter in Marketo {#select-the-filter-in-marketo}

Zelfs als u uw eerste synchronisatie al hebt uitgevoerd, gaat u binnen en selecteert u de velden die met Marketo moeten worden gesynchroniseerd.

1. Ga naar Admin en selecteer **MIcrosoft Dynamics**.

   ![](assets/image2015-10-9-9-3a50-3a9.png)

1. Klik op **Bewerken** op Details van veldsynchronisatie.

   ![](assets/image2015-10-9-9-3a52-3a23.png)

1. Blader omlaag naar het veld en controleer het. De daadwerkelijke naam moet new_synctomkto zijn maar de Naam van de Vertoning kan om het even wat zijn. Klik **Opslaan**.

   ![](assets/image2015-10-9-9-3a56-3a23.png)

Geweldig, nu hebt u het synchronisatiefilter ingeschakeld voor Marketo.

## Creeer een Workflow van de Dynamiek om de Waarden van de Filter van de Synchronisatie automatisch {#create-a-dynamics-workflow-to-assign-sync-filter-values-automatically} toe te wijzen

U kunt altijd handmatig een waarde toewijzen aan de velden SyncToMkto voor uw records. Maar waarom voordeel niet uit de macht van een Workflow van de Dynamica en auto-wijs een waarde aan het gebied SyncToMkto toe wanneer een verslag wordt gecreeerd of bijgewerkt?

>[!NOTE]
>
>U kunt dit niet op het gegevensbestandniveau doen. Dit moet handmatig gebeuren in de CRM of met behulp van een workflow.
>
>Een workflow voor dynamiek werkt alleen voor nieuwe records die u maakt en niet voor historische gegevens. Gebruik een batchupdate om over bestaande records te navigeren.

1. Ga naar Dynamics CRM. Klik **Instellingen** en klik vervolgens op **Processen**.

   ![](assets/image2015-8-11-8-3a42-3a10.png)

1. Klik **Nieuw**.

   ![](assets/image2015-8-11-8-3a43-3a46.png)

1. Voer een naam voor de workflow in en selecteer **Workflow** als de categorie en **Lead** als de entiteit. Klik vervolgens op **OK**.

   ![](assets/image2015-8-11-8-3a45-3a46.png)

1. Maak regels om een waarde true of false toe te wijzen aan het veld **SyncToMkto** op basis van de voorkeur van uw organisatie. Klik **Opslaan en sluiten**.

   ![](assets/setsynctomkto-fix.png)

   >[!NOTE]
   >
   >Definieer een standaardactie nadat u **Stap toevoegen** hebt geklikt om een voorwaarde van de Controle toe te voegen. Hiermee stelt u de records in die u niet wilt synchroniseren met **No**. Anders worden ze gesynchroniseerd.

1. Selecteer de workflow en klik op **Activeren**.

   ![](assets/image2015-8-11-8-3a57-3a29.png)

   >[!TIP]
   >
   >Zie [Aangepaste filterregels voor synchronisatie voor een e-mailadres](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter/custom-sync-filter-rules-for-an-email-address.md) om regels in te stellen voor het synchroniseren van alleen records voor mensen met e-mailadressen.

## Details van filter synchroniseren {#sync-filter-details}

Hier volgen enkele implementatiedetails die u volgens ons moet weten:

1. Synchronisatiebewerking starten

   Wanneer de **SyncToMkto** waarde van **No** in **Yes** verandert, richt de Dynamiek Marketo onmiddellijk om met het synchroniseren van dit verslag te beginnen. Als de record al bestaat, wordt deze door Marketo bijgewerkt. Anders maakt Marketo de record.

   >[!TIP]
   >
   >Wanneer dit gebeurt, wordt een bewerking `Create [StartSync]` toegevoegd aan het Marketo-logboek.

1. Synchronisatiebewerking stoppen

   Wanneer een record de waarde SyncToMkto wijzigt van Ja in Nee, wordt Marketo een melding gestuurd dat de synchronisatie van deze record moet worden gestopt. De record wordt echter niet verwijderd, maar houdt op met het ophalen van updates en wordt &#39;stale&#39;.

>[!MORELIKETHIS]
>
>* [Microsoft Dynamics Sync Filter: Kwalificeren](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter/microsoft-dynamics-sync-filter-qualify.md)
>* [Microsoft Dynamics Sync Filter: Samenvoegen](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter/microsoft-dynamics-sync-filter-merge.md)
>* [Aangepaste filterregels voor synchronisatie voor een e-mailadres](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter/custom-sync-filter-rules-for-an-email-address.md)

