---
unique-page-id: 2949158
description: Integratie van RTP met Google Analytics - Marketo Docs - Productdocumentatie
title: RTP integreren met Google Analytics
exl-id: a2bc0c17-dc23-435e-9480-857e97e6fd50
feature: Web Personalization
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '560'
ht-degree: 0%

---

# RTP integreren met Google Analytics {#integrate-rtp-with-google-analytics}

>[!NOTE]
>
>Universal Analytics is nu de standaard voor gebruik en alle eigenschappen in Google zijn bijgewerkt naar Universal Analytics.
>
>Dit artikel laat zien hoe u de oude Google Standard Analytics kunt gebruiken, maar we raden u aan over te schakelen op Universal Analytics.
>
>Als u nog niet [ analytics.js het volgen code ](https://developers.google.com/analytics/devguides/collection/analyticsjs/) gebruikt, adviseert Google sterk u een detailhandel van uw plaats om het te gebruiken. Google vervalt het volgende:
>
>* ga.js
>* urchin.js
>* WAP-/serverfragmenten
>* YT / MO
>* Aangepaste variabelen
>* Door de gebruiker gedefinieerde variabelen
>
>Zie hoe te om [ Personalization van het Web met Universele Analytics ](/help/marketo/product-docs/web-personalization/reporting-for-web-personalization/web-analytics-integrations/integrate-rtp-with-google-universal-analytics.md) te integreren

## Inleiding {#introduction}

Analyseer uw webanalyse vanuit een nieuwe hoek met behulp van directe gegevensstroom van Marketo Real-Time Personalization (RTP) naar uw Google Analytics-account (GA). Meet uw webbezoeken in GA volgens organisaties, industrieën en RTP-campagnes. Bekijk metriek zoals de types van industrieën of segmenten RTP in GA en hoe zij presteren en leiden volgens verschillende verkeersbronnen (sociaal, betaald, organisch) produceren, analyseert kliks door tarieven op campagnes, en het meten van de gevolgen personaliseringscampagnes op uw website hebben. Gebruikmaken van deze mogelijkheid om maximaal voordeel te halen uit uw RTP-account

**RTP Audience Analytics**

Dankzij de integratie hebt u een nieuwe dimensie in uw GA-account. RTP verbetert automatisch uw dashboards met:

1. Organisaties en industrieën
1. Aangepaste segmenten in RTP
1. Account-Based Marketing-lijsten

Focus op uw belangrijkste B2B-vooruitzichten. Kanalen door doelindustrieën en segmenten analyseren.

## Kanaalrapport {#channel-report}

![](assets/image2014-11-28-16-3a39-3a28.png)

Het dashboard van RTP B2B helpt u de uitsplitsing van uw bezoekers volgens verticals en segmentatie begrijpen RTP. Je kunt de prestaties van je bezoeker zien op basis van de financiële sector en volgens verschillende marketingcampagnes (betaald, biologisch, sociaal). Het dashboard verstrekt ook een overzicht op hoog niveau van hoe uw segmenten RTP presteren en oefeningen neer om de hoogste organisaties te tonen die uw plaats bezoeken.

## Gedragingen {#behavioral-flow}

![](assets/image2014-11-28-16-3a40-3a43.png)

In het rapport Gedragstroming (zie afbeelding) wordt weergegeven hoe bezoekers van het pad van de ene pagina of gebeurtenis naar de volgende gaan. Het voorbeeld toont het pad van alle bezoekers uit de financiële sector. Dit rapport kan u helpen ontdekken wat de inhoud houdt bezoekers betrokken bij uw site.

## RTP-prestaties {#rtp-performance}

Meet uw campagnes RTP en correleer hen met uw algemeen plaatsgemiddelde. Leer hoe deze campagnes de metriek van uw website beïnvloeden en deze gegevens gebruiken om uw verpersoonlijkingsinspanningen op de juiste doelstellingen te concentreren. Genereer aangepaste rapporten om beter te begrijpen hoe uw personalisatiecampagnes presteren.

![](assets/image2014-11-28-16-3a47-3a0.png)

## RTP instellen met Google Analytics {#setting-up-rtp-with-google-analytics}

1. Voeg het e-mailadres rtp.ga2@gmail.com als een gebruiker voor lezen en analyseren toe aan uw GA-account. Voor meer details, zie [ hier ](https://support.google.com/analytics/answer/2884495?hl=en).

1. In uw RTP-account. Ga naar **[!UICONTROL Account Settings]** .

   ![](assets/image2014-11-28-16-3a54-3a40.png)

1. Onder **[!UICONTROL Account Settings]** , **[!UICONTROL Domain]** en **[!UICONTROL Analytics]** .

1. Klik op **Google Analytics**.

1. Zet de relevante **Variabelen van de Douane** en **Gebeurtenissen** aan om deze gegevens van RTP aan Google Analytics toe te voegen.

1. Ga het **aantal van de Slot** in om de gegevens van de douanevariabele (gebrek is 1.2) te verzenden.

![](assets/image2014-11-28-17-3a0-3a17.png)

1. Klik op **[!UICONTROL Save]**.

>[!NOTE]
>
>Om segmentgegevens naar GA te verzenden, selecteert u onder de [[!UICONTROL Edit Segment] pagina ](/help/marketo/product-docs/web-personalization/using-web-segments/create-a-basic-web-segment.md) in het RTP-platform het selectievakje **[!UICONTROL Send Event to Google Analytics on Segment Match]** .

## Google Analytics-rapporten instellen met RTP-gegevens {#setting-up-google-analytics-reports-with-rtp-data}

In Google Analytics kunt u dashboards, de segmentatie van GA, en het melden gebruiken om uw gegevens RTP te bekijken:

* [ dashboards ](https://support.google.com/analytics/answer/1068216?hl=en) verstrekken een overzicht van de websiteprestaties.
* Een GA-segment is bedoeld om bezoekers in de GA-interface te filteren en het verkeer per segment weer te geven. Zie hoe te om een segment [ hier ](https://support.google.com/analytics/answer/3124493?hl=en) te bouwen.
* Creërend [ aangepaste rapporten ](https://support.google.com/analytics/answer/1033013?hl=en) aan mening en/of opstelling geplande e-mails. Zie onder **[!UICONTROL Customization]** > **[!UICONTROL New Custom Report]** .
