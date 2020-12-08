---
unique-page-id: 2949160
description: Integreren met Adobe Analytics - Marketo Docs - Productdocumentatie
title: Integreren met Adobe Analytics
translation-type: tm+mt
source-git-commit: 00887ea53e395bea3a11fd28e0ac98b085ef6ed8
workflow-type: tm+mt
source-wordcount: '1130'
ht-degree: 0%

---


# Integreren met Adobe Analytics {#integrate-with-adobe-analytics}

## Intro {#intro}

Analyseer uw webanalyses vanuit een B2B-perspectief door de gegevens van uw Adobe Analytics-account weer te geven voor uw organisatie, industrie en Marketo Real-Time Personalization (RTP).

Dit document laat de integratie tussen Marketo Real-Time Personalization (RTP) en Adobe Adobe Analytics toe. De gegevens van RTP zullen u toestaan om tendensen in alle industriesegmenten en organisaties te ontdekken en te analyseren die uw plaats bezoeken en de doeltreffendheid van uw campagnes te meten RTP, die de inzichten en de analyse verstrekken om optimale resultaten te bereiken.

U kunt dit bereiken door metriek zoals de aantallen nieuwe versus terugkerende bezoekers in elk segment te bekijken, kliktarieven op campagnes te analyseren, en te ontdekken welke industrieën en aangepaste segmenten en in real time campagnes de beste omzettende lood produceerden. Gebruik deze mogelijkheid om het maximale voordeel van uw RTP-account te behalen.

## RTP Audience Analytics {#rtp-audience-analytics}

Met de integratie RTP - AA, hebt u een nieuwe dimensie binnen uw interface van de Webanalyse. RTP verbetert automatisch uw Web analytics dashboards met:

1. Organisatie- en bedrijfsgegevens
1. Aangepaste RTP-segmenten
1. Lijsten met benoemde accounts (marketing op basis van account)

Hierdoor worden uw B2B-gegevens verbeterd en kunt u zich richten op relevante bezoekers door het optimaliseren van:

1. Uitgaande kanalen
1. Inhoud
1. Opnieuw rangschikken

## Kanaalrapport {#channel-report}

![](assets/image2014-11-29-12-3a0-3a26.png)

Het dashboard RTP helpt u de verdeling van uw bezoekers volgens verticals en segmenten begrijpen RTP. Je kunt de prestaties van je bezoeker bekijken op basis van de branche en verschillende marketingcampagnes (betaald, organisch, sociaal) in verband met die branche. Het dashboard biedt ook een overzicht op hoog niveau van de sitesecties die uw bezoekers bekijken op basis van hun branchetype.

## Gedragsrapport {#behavioral-report}

Verschillende gedragsrapporten kunnen in Adobe Analytics worden gecreeerd die op organisatie, industrie en RTP segmentgegevens wordt gebaseerd. Deze stroomrapporten visualiseren het pad dat bezoekers volgen van de ene pagina of gebeurtenis naar de volgende. Dit rapport kan u helpen ontdekken wat de inhoud houdt bezoekers betrokken bij uw site.

## RTP-prestaties {#rtp-performance}

De campagnebeelden van RTP van de mening en omzettingen onder de Verbindingen van de Douane in Adobe Analytics.

Dit rapport van de Verbinding van Douane zal beelden en omzettingen van campagnes onder het volgende noemende formaat tonen:

* Impressie ISegment: [Naam]RTP-segment, ICampaign: [Naam RTP-campagne]
* Conversie ISegment: [Naam]RTP-segment, ICampaign: [Naam RTP-campagne]

![](assets/custom-links-report.png)

## Instellen in Adobe Analytics {#set-up-in-adobe-analytics}

De integratie maakt gebruik van de JavaScript API die Adobe Analytics biedt. Aangepaste conversievariabelen (eVar), aangepaste gebeurtenissen (gebeurtenis) en verkeersvariabelen worden in de integratie gebruikt. Alles moet zijn ingeschakeld vanuit AA-beheer. U moet de conversievariabelen, aangepaste gebeurtenissen en verkeersvariabelen instellen in AA, anders kunt u de gegevens in de suite niet zien, zelfs niet als u deze in RTP hebt ingeschakeld.

Voer de volgende stappen uit om deze variabelen in te stellen in AA:

1. Ga naar **Admin Tools** in uw AA-account.
1. Selecteer de **rapportsuite** die bij de integratie moet worden gebruikt.
1. Ga onder Instellingen **bewerken naar** Conversie **en selecteer **** Variabelen [](http://microsite.omniture.com/t2/help/en_US/reference/#Edit_conversion_variables)conversie**.\
   Selecteer het aantal van de Variabele [van de](http://microsite.omniture.com/t2/help/en_US/reference/#Conversion_Variables_eVar) Omzetting (wij adviseren):

   1. 

      1. Evar # 20 for Industry Custom Conversions
      1. Evar # 21 for Organization Custom Conversions

         >[!NOTE]
         >
         >Als deze # worden genomen, selecteer een ander beschikbaar aantal. Lijn dit aantal met het groefaantal in de Montages van de Rekening RTP uit.

      1. Status wijzigen in* Ingeschakeld*

         1. Naam wijzigen in **Industrie** en **Organisatie**. (Zo wordt dit weergegeven in de rapportsuite.)

         1. Wijzig Verlopen na veld in **Bezoek.**

1. Onder **Instellingen bewerken **gaat u naar** Conversie **en selecteert u ** [Gebeurtenissen](http://microsite.omniture.com/t2/help/en_US/reference/#Configure_success_events)** met succes.

1. Selecteer het gebeurtenisnummer Aangepaste succesgebeurtenissen (aanbevolen):

   1. event20 voor campagnes RTP
   1. event21 voor RTP-segmenten

      >[!NOTE]
      >
      >Als deze # worden genomen, selecteer een ander beschikbaar aantal. Lijn dit aantal met het groefaantal in de Montages van de Rekening RTP uit.

   1. Verander de twee gebeurtenisnamen in Campagnes **RTP** en Segmenten **RTP**. Dit is de naam die wordt weergegeven in de rapportsuite.

1. Selecteer het veld Type* *dat **tellerveld moet zijn (geen subrelaties)**

1. Onder **Edit Montages** ga naar ** [Verkeer](http://microsite.omniture.com/t2/help/en_US/reference/#Traffic_Variable) **en selecteer ** de Variabelen [van het](http://microsite.omniture.com/t2/help/en_US/reference/#Enable_traffic_variable_reports)** Verkeer.

   1. Selecteer het bezit van de Variabele van het Verkeer # (wij adviseren):

      1. Eigenschap nr. 20 - Naam: RTP Segment Organisation
      1. Eigendomsnummer 21 - Naam: RTP Segment Industry
      1. Eigendomsnummer 25 - Naam: Campagneorganisatie
      1. Eigendomsnummer 26 - Naam: RTP-campagne

         >[!NOTE]
         >
         >Als deze # worden genomen, selecteer een ander beschikbaar aantal. Dit nummer uitlijnen met het sleufnummer in de instellingen voor RTP-account)

      1. Wijzig de 4 eigenschapnamen. Dit is de naam die wordt weergegeven in de rapportsuite.
   1. Veld voor Ingeschakeld selecteren om **in te schakelen**
   1. Veld voor padrapporten selecteren die moet worden **ingeschakeld**


## Opstelling in Marketo Real-Time Personalization (RTP) {#set-up-in-marketo-real-time-personalization-rtp}

1. Ga in het RTP-platform naar **Accountinstellingen**.

   ![](assets/image2014-11-29-11-3a27-3a7.png)

1. Klik onder **Accountinstellingen** op **Domein**.
1. Klik onder **Analytics op** **Adobe Analytics**.
1. Draai **On **de de veranderlijke knevels van de Omzetting, van de Douane en van het Verkeer.
1. Wijs de de **groefaantallen** van de Variabelen van de Omzetting, van de Gebeurtenis en van het Verkeer toe om de groefaantallen aan te passen die in AA worden gecreeerd
1. Klik op **OPSLAAN**.

![](assets/image2014-11-29-12-3a24-3a42.png)

>[!NOTE]
>
>Onze aanbevolen sleufinstellingen zijn
>
>**Conversievariabelen**
>
>* Aangepaste industriële conversies - sleuf 20
>* Aangepaste conversies van organisatie - sleuf 21

>
>
**Aangepaste gebeurtenissen**
>
>* Aangepaste gebeurtenis campagne - sleuf 20
>* Aangepaste gebeurtenis segment - sleuf 21

>
>
**Verkeersvariabelen**
>
>* Segment Organisation Traffic Variable - Slot 20
>* Segment Industry Traffic Variable - Slot 21
>* Verkeersvariabele Campagneorganisatie - Slot 22
>* Campagne Industrie Verkeersvariabele - Slot 23

>
>
**Zorg ervoor dat deze groefaantallen zich op de variabelen en de gebeurtenisaantallen richten die in aa worden gecreeerd.**

## Rapporten {#reports}

Maak verbeterde SiteAdobe Analytics-rapporten op basis van de namen van de organisatie, de industrieën en RTP-segmenten en realtime campagnegegevens.

Voorbeelden van aangepaste rapporten en dashboards in AA zijn:

* Prestaties per branche of bepaald segment (op rekening-Gebaseerde genoemde lijsten)
* Uitsplitsing naar bedrijfstak per KPI-prestatie
* Per organisatie bekeken pagina&#39;s
* Prestaties van marketingkanalen volgens organisatie, industrie, segmenten

**Voorbeelden van rapporten**

**Top Industries Report**

** ![](assets/top-industries-report.png)

**

**Organisatierapport**

![](assets/image2014-11-29-12-3a29-3a42.png)

**Het RTP-dashboard maken**

Creeer een [nieuw dashboard](http://microsite.omniture.com/t2/help/en_US/sc/user/t_dashboard_add.html), genoemd **Dashboard** RTP. Dit dashboard zal helpen de verdeling van uw bezoekers volgens verticals en segmenten begrijpen RTP.

1. Klik op **dashboard,** klik op** Dashboard toevoegen**

1. Geef het dashboard **RTP-dashboard een naam**
1. Selecteer de **dashboardgrootte** 3 x 2, 2 x 2
1. Maak het [rapport](http://microsite.omniture.com/t2/help/en_US/sc/user/t_dashboard_add_report.html#task_EC3AFBBAA51C45CEBAF632F841C305B3) en voeg [inhoud toe aan het dashboard](https://docs.marketo.com/Add%2520content%2520to%2520a%2520dashboard)

Het rapport Industrieën toevoegen aan het dashboard

1. Ga naar **Aangepaste conversies**, klik op **Industrie**

1. Grafiek configureren naar **schijfdiagram**
1. Klik op **dashboard**, voeg **Rapporlet toe**

1. Geef een naam aan het rapport **Top Industries**
1. Plaatsen in Dashboard **RTP-dashboard**
1. Maak **nieuw**.

De Segmentrapporten toevoegen aan het dashboard

1. Ga naar **Metriek van de Plaats, **Klik op **Aangepaste Gebeurtenissen, Segmenten**

1. Grafiek configureren naar **verticale balk**
1. Klik op **dashboard**, voeg **Rapporlet toe**

1. Geef de **bovenste segmenten van het rapport een naam**
1. Plaatsen in Dashboard **RTP-dashboard**
1. Maak **nieuw.**

Uw rapporten worden weergegeven op het dashboard.

## Afbeeldingen en klikken (conversies) weergeven in Adobe Analytics {#view-impressions-and-clicks-conversions-in-adobe-analytics}

1. Klik op Aangepaste koppelingen.

   ![](assets/sitecatalyst1-1.png)

1. Zoeken naar afbeeldingen om de namen van segmenten en campagnes weer te geven die het aantal indrukken voor de campagne aangeven.\
   ![](assets/sitecatalyst1.png)

1. Zoek naar Omzetting om de namen van Segmenten en van de Campagne te bekijken die het aantal klikken voor de campagne vertegenwoordigen.

   ![](assets/sitecatalyst2.png)

