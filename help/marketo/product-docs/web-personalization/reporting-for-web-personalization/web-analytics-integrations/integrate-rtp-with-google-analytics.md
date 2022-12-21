---
unique-page-id: 2949158
description: Integreer RTP met Google Analytics - Marketo Docs - de Documentatie van het Product
title: Integreer RTP met Google Analytics
exl-id: a2bc0c17-dc23-435e-9480-857e97e6fd50
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '608'
ht-degree: 0%

---

# Integreer RTP met Google Analytics {#integrate-rtp-with-google-analytics}

>[!NOTE]
>
>Universal Analytics is nu de standaard voor gebruik en alle eigenschappen in Google zijn bijgewerkt naar Universal Analytics.
>
>Dit artikel laat zien hoe u de oude Google Standard Analytics kunt gebruiken, maar we raden u aan over te schakelen op Universal Analytics.
>
>Als u nog geen [analytics.js-trackingcode](https://developers.google.com/analytics/devguides/collection/analyticsjs/), Google raadt u ten zeerste aan uw site opnieuw op te slaan als u deze wilt gebruiken. Google vervalt het volgende:
>
>* ga.js
>* urchin.js
>* WAP-/serverfragmenten
>* YT / MO
>* Aangepaste variabelen
>* Door de gebruiker gedefinieerde variabelen
>
>Ontdek hoe u kunt integreren [Web Personalization with Universal Analytics](/help/marketo/product-docs/web-personalization/reporting-for-web-personalization/web-analytics-integrations/integrate-rtp-with-google-universal-analytics.md)

## Inleiding {#introduction}

Analyseer uw webanalyse vanuit een nieuwe hoek met behulp van directe gegevensstroom van Marketo Real-Time Personalization (RTP) naar uw Google Analytics (GA)-account. Meet uw webbezoeken in GA volgens organisaties, industrieën en RTP-campagnes. Bekijk metriek zoals de types van industrieën of segmenten RTP in GA en hoe zij presteren en leiden volgens verschillende verkeersbronnen (sociaal, betaald, organisch) produceren, analyseert kliks door tarieven op campagnes, en het meten van de gevolgen personaliseringscampagnes op uw website hebben. Gebruikmaken van deze mogelijkheid om maximaal voordeel te halen uit uw RTP-account

**RTP Audience Analytics**

Dankzij de integratie hebt u een nieuwe dimensie in uw GA-account. RTP verbetert automatisch uw dashboards met:

1. Organisaties en industrieën
1. Aangepaste segmenten in RTP
1. Account-Based Marketing-lijsten

Focus op uw belangrijkste B2B-vooruitzichten. Kanalen door doelindustrieën en segmenten analyseren.

## Kanaalrapport {#channel-report}

![](assets/image2014-11-28-16-3a39-3a28.png)

Het dashboard van RTP B2B helpt u de uitsplitsing van uw bezoekers volgens verticals en segmentatie begrijpen RTP. Je kunt de prestaties van je bezoeker zien op basis van de financiële sector en volgens verschillende marketingcampagnes (betaald, biologisch, sociaal). Het dashboard verstrekt ook een overzicht op hoog niveau van hoe uw segmenten RTP presteren en oefeningen neer om de hoogste organisaties te tonen die uw plaats bezoeken.

## Gedragstroming {#behavioral-flow}

![](assets/image2014-11-28-16-3a40-3a43.png)

In het rapport Gedragstroming (zie afbeelding) wordt weergegeven hoe bezoekers van het pad van de ene pagina of gebeurtenis naar de volgende gaan. Het voorbeeld toont het pad van alle bezoekers uit de financiële sector. Dit rapport kan u helpen ontdekken wat de inhoud houdt bezoekers betrokken bij uw site.

## RTP-prestaties {#rtp-performance}

Meet uw campagnes RTP en correleer hen met uw algemeen plaatsgemiddelde. Leer hoe deze campagnes de metriek van uw website beïnvloeden en deze gegevens gebruiken om uw verpersoonlijkingsinspanningen op de juiste doelstellingen te concentreren. Genereer aangepaste rapporten om beter te begrijpen hoe uw personalisatiecampagnes presteren.

![](assets/image2014-11-28-16-3a47-3a0.png)

## Het vestigen RTP met Google Analytics {#setting-up-rtp-with-google-analytics}

1. Voeg het e-mailadres rtp.ga2@gmail.com als een gebruiker voor lezen en analyseren toe aan uw GA-account. Zie voor meer informatie [hier](https://support.google.com/analytics/answer/2884495?hl=en).

1. In uw RTP-account. Ga naar **Accountinstellingen**.

   ![](assets/image2014-11-28-16-3a54-3a40.png)

1. Onder **Accountinstellingen**, **Domein** en **Analyse**.

1. Klikken op **Google Analytics**.

1. Schakel de relevante **Aangepaste variabelen** en **Gebeurtenissen** om deze gegevens van RTP aan Google Analytics toe te voegen.

1. Voer de **Slot** getal om aangepaste variabele-gegevens te verzenden (standaardwaarde is 1,2).

![](assets/image2014-11-28-17-3a0-3a17.png)

1. Klikken **Opslaan**.

>[!NOTE]
>
>Om segmentgegevens naar GA te verzenden, onder de [Segmentpagina bewerken](/help/marketo/product-docs/web-personalization/using-web-segments/create-a-basic-web-segment.md) in het platform RTP, selecteer checkbox **Gebeurtenis verzenden naar Google Analytics op segmentovereenkomst**.

## De Rapporten van Google Analytics van de vestiging met Gegevens RTP {#setting-up-google-analytics-reports-with-rtp-data}

In Google Analytics kunt u dashboards, de segmentatie van GA, en het melden gebruiken om uw gegevens te bekijken RTP:

* [Dashboards](https://support.google.com/analytics/answer/1068216?hl=en) Geef een overzicht van de prestaties van de website.
* Een GA-segment is bedoeld om bezoekers in de GA-interface te filteren en het verkeer per segment weer te geven. Zie hoe u een segment kunt maken [hier](https://support.google.com/analytics/answer/3124493?hl=en).
* Maken [aangepaste rapporten](https://support.google.com/analytics/answer/1033013?hl=en) om geplande e-mailberichten te bekijken en/of in te stellen. Zie onder Aanpassing > Nieuw aangepast rapport.
