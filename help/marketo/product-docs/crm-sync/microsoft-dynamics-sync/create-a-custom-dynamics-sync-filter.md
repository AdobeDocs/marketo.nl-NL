---
unique-page-id: 9437903
description: Een aangepaste filter voor het synchroniseren van dynamiek maken - Marketo Docs - Productdocumentatie
title: Een filter voor aangepaste dynamicasynchronisatie maken
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '790'
ht-degree: 0%

---


# Een filter voor aangepaste dynamicasynchronisatie maken {#create-a-custom-dynamics-sync-filter}

Wilt u niet alles in uw Dynamische CRM in Marketo synchroniseren? Maak je geen zorgen! Met Marketo kunt u een synchronisatiefilter instellen en slechts een deel van uw records synchroniseren.

## Overzicht {#overview}

Een filter voor het synchroniseren van dynamiek instellen:

1. Creeer een douane twee van Opties (booleaanse) gebied genoemd new_synctomkto in uw Dynamica CRM voor om het even welk voorwerp (lood, contact, rekening, kans en andere douaneentiteiten).
1. Wijs in dit veld een waarde Ja/Nee toe of laat het veld leeg.

>[!NOTE]
>
>U moet deze veranderingen in Dynamica CRM, niet uw gegevensbestand of Marketo aanbrengen.

Marketo zoekt dit veld tijdens de automatische achtergrondsynchronisatie en bepaalt op basis van deze logica welke records moeten worden gesynchroniseerd:

| Veldwaarde | Synchroniseren met Marketo? |
|---|---|
| Veld bestaat niet | Ja |
| Veld is leeg | Ja |
| Veld heeft waarde Ja | Ja |
| Veld heeft waarde Nee | Nee |

>[!CAUTION]
>
>De enige manier om Marketo te vertellen een verslag over te slaan is de gebiedswaarde uitdrukkelijk te plaatsen om **nr** te zijn. Marketo synchroniseert nog steeds records, zelfs als de veldwaarden leeg zijn.

>[!NOTE]
>
>**Vereisten**
>
>Installeer de nieuwste versie van de plug-in Marketo (3.0.0.1 of hoger). Ga naar Marketo > Admin > Microsoft Dynamics > Download Marketo Solution.

## SyncToMkto-veld maken {#create-synctomkto-field}

1. Log in Dynamics CRM. Klik op **Instellingen** en vervolgens op **Aanpassingen**.

   ![](assets/image2015-8-10-21-3a40-3a9.png)

1. Klik op **Systeem** aanpassen.

   ![](assets/image2015-8-10-21-3a42-3a15.png)

1. Klik ![](assets/image2015-8-10-21-3a44-3a23.png) naast **Entiteiten**.

   ![](assets/image2015-8-10-21-3a43-3a39.png)

1. Klik ![](assets/image2015-8-10-21-3a44-3a23.png) naast **Lead **en selecteer **Gebieden**. Klik vervolgens op **Nieuw**.

   ![](assets/image2015-8-10-21-3a49-3a49.png)

1. Typ **SyncToMkto** in het veld **Weergavenaam** en selecteer **Twee opties** als **gegevenstype**. Klik vervolgens op **Opslaan en Sluiten**.

   ![](assets/image2015-9-8-10-3a25-3a33.png)

   >[!NOTE]
   >
   >Kies een willekeurige weergavenaam voor dit veld, maar het veld Naam moet exact **new_synctomkto** zijn. U moet **nieuw** als standaardprefix gebruiken. Als u de standaardinstelling hebt gewijzigd, gaat u hier om het standaardvoorvoegsel voor de aangepaste veldnamen [opnieuw in te](create-a-custom-dynamics-sync-filter/set-a-default-custom-field-prefix.md)stellen. U kunt deze instelling wijzigen nadat u de nieuwe velden hebt gemaakt.

   >[!NOTE]
   >
   >Als u een asynchrone workflow hebt ingesteld, krijgt de record de standaardwaarde voor SyncToMkto die u in het veld hebt ingesteld, en wordt de juiste waarde een paar seconden later opgehaald wanneer de workflow is voltooid. Als de standaardwaarde op Ja is ingesteld, worden deze records in Marketo gemaakt en vervolgens opgeschoond. Gebruik **Nee** als standaardwaarde om dit te voorkomen.

1. Herhaal dit proces en maak het **veld SyncToMkto** voor alle andere entiteiten waarvoor u de synchronisatie wilt beperken, zoals contact, account, opportuniteit en aangepaste entiteiten.

## Filter in markeerteken selecteren {#select-the-filter-in-marketo}

Zelfs als u uw eerste synchronisatie al hebt uitgevoerd, gaat u binnen en selecteert u de velden die u wilt synchroniseren met Marketo.

1. Ga naar Beheer en selecteer **Microsoft Dynamics**.

   ![](assets/image2015-10-9-9-3a50-3a9.png)

1. Klik op **Bewerken** op Veldsynchronisatiedetails.

   ![](assets/image2015-10-9-9-3a52-3a23.png)

1. Blader omlaag naar het veld en controleer het. De daadwerkelijke naam moet new_synctomkto zijn maar de Naam van de Vertoning kan om het even wat zijn. Klik op **Opslaan**.

   ![](assets/image2015-10-9-9-3a56-3a23.png)

Geweldig, nu hebt u het synchronisatiefilter ingeschakeld voor Marketo.

## Een dynamiekworkflow maken om automatisch waarden voor synchronisatiefilters toe te wijzen {#create-a-dynamics-workflow-to-assign-sync-filter-values-automatically}

U kunt altijd handmatig een waarde toewijzen aan de velden SyncToMkto voor uw records. Maar waarom voordeel niet uit de macht van een Workflow van de Dynamica en auto-wijs een waarde aan het gebied SyncToMkto toe wanneer een verslag wordt gecreeerd of bijgewerkt?

>[!NOTE]
>
>U kunt dit niet op het gegevensbestandniveau doen. Dit moet handmatig gebeuren in de CRM of met behulp van een workflow.
>
>Een workflow voor dynamiek werkt alleen voor nieuwe records die u maakt en niet voor historische gegevens. Gebruik een batchupdate om over bestaande records te navigeren.

1. Ga naar Dynamics CRM. Klik op **Instellingen** en vervolgens op **Processen**.

   ![](assets/image2015-8-11-8-3a42-3a10.png)

1. Klik op **Nieuw**.

   ![](assets/image2015-8-11-8-3a43-3a46.png)

1. Voer een naam voor de workflow in en selecteer **Workflow** als de categorie en **Lead** als de entiteit. Klik vervolgens op **OK**.

   ![](assets/image2015-8-11-8-3a45-3a46.png)

1. Maak regels om een waarde true of false toe te wijzen aan het veld **SyncToMkto** op basis van de voorkeur van uw organisatie. Klik op **Opslaan en Sluiten**.

   ![](assets/setsynctomkto-fix.png)

   >[!NOTE]
   >
   >Definieer een standaardhandeling nadat u op Stap **** toevoegen hebt geklikt om een voorwaarde voor controle toe te voegen. Hiermee stelt u de records die u niet wilt synchroniseren in op **Nee**. Anders worden ze gesynchroniseerd.

1. Selecteer de workflow en klik op **Activeren**.

   ![](assets/image2015-8-11-8-3a57-3a29.png)

   >[!TIP]
   >
   >Zie [Aangepaste filterregels voor synchronisatie voor een e-mailadres](create-a-custom-dynamics-sync-filter/custom-sync-filter-rules-for-an-email-address.md) om regels in te stellen voor het synchroniseren van alleen records voor mensen met e-mailadressen.

## Details van filter synchroniseren {#sync-filter-details}

Hier volgen enkele implementatiedetails die u volgens ons moet weten:

1. Synchronisatiebewerking starten

   Wanneer de **waarde SyncToMkto** van **Nr** in **ja** verandert, brengt de Dynamiek Marketo onmiddellijk op de hoogte om dit verslag te beginnen synchroniseren. Als de record al bestaat, wordt deze bijgewerkt door Marketo. Anders maakt Marketo de record.

   >[!TIP]
   >
   >Wanneer dit gebeurt, wordt een bewerking **Create [StartSync]** toegevoegd aan het Marketo Log.

1. Synchronisatiebewerking stoppen

   Wanneer een record de waarde SyncToMkto wijzigt van Ja in Nee, wordt Marketo een melding gestuurd om de synchronisatie van deze record te stoppen. De record wordt echter niet verwijderd, maar houdt op met het ophalen van updates en wordt &#39;stale&#39;.

>[!NOTE]
>
>**Verwante artikelen**
>
>* [Microsoft Dynamics Sync Filter: Kwalificeren](create-a-custom-dynamics-sync-filter/microsoft-dynamics-sync-filter-qualify.md)
>* [Microsoft Dynamics Sync Filter: Samenvoegen](create-a-custom-dynamics-sync-filter/microsoft-dynamics-sync-filter-merge.md)
>* [Aangepaste filterregels voor synchronisatie voor een e-mailadres](create-a-custom-dynamics-sync-filter/custom-sync-filter-rules-for-an-email-address.md)

>



