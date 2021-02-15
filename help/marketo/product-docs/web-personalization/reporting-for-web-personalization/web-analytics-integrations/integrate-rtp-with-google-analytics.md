---
unique-page-id: 2949158
description: Integreer RTP met Google Analytics - Marketo Docs - de Documentatie van het Product
title: Integreer RTP met Google Analytics
translation-type: tm+mt
source-git-commit: 6ae882dddda220f7067babbe5a057eec82601abf
workflow-type: tm+mt
source-wordcount: '614'
ht-degree: 0%

---


# Integreer RTP met Google Analytics {#integrate-rtp-with-google-analytics}

>[!NOTE]
>
>Universal Analytics is nu de standaard voor het gebruik en alle eigenschappen in Google zijn bijgewerkt naar Universal Analytics.
>
>Dit artikel laat zien hoe u de oude Google Standard Analytics kunt gebruiken, maar we raden u aan over te schakelen op Universal Analytics.
>
>Als u de [analytics.js tracking-code](https://developers.google.com/analytics/devguides/collection/analyticsjs/) nog niet gebruikt, raadt Google u ten zeerste aan uw site opnieuw te labelen om deze te gebruiken. Google heeft het volgende verouderd:
>
>* ga.js
>* urchin.js
>* WAP-/serverfragmenten
>* YT / MO
>* Aangepaste variabelen
>* Door de gebruiker gedefinieerde variabelen

>
>
Zie hoe u [Web Personalization kunt integreren met Universal Analytics](integrate-rtp-with-google-universal-analytics.md)

## Inleiding {#introduction}

Analyseer uw webanalyse vanuit een nieuwe hoek met behulp van directe gegevensstroom van Marketo Real-Time Personalization (RTP) naar uw Google Analytics-account (GA). Meet uw webbezoeken in GA volgens organisaties, industrieën en RTP-campagnes. Bekijk metriek zoals de types van industrieën of segmenten RTP in GA en hoe zij presteren en leiden volgens verschillende verkeersbronnen (sociaal, betaald, organisch) produceren, analyseert kliks door tarieven op campagnes, en het meten van de gevolgen personaliseringscampagnes op uw website hebben. Gebruikmaken van deze mogelijkheid om maximaal voordeel te halen uit uw RTP-account

**RTP Audience Analytics**

Dankzij de integratie hebt u een nieuwe dimensie in uw GA-account. RTP verbetert automatisch uw dashboards met:

1. Organisaties en industrieën
1. Aangepaste segmenten in RTP
1. Marketinglijsten op basis van account

Focus op uw belangrijkste B2B-vooruitzichten. Kanalen door doelindustrieën en segmenten analyseren.

## Kanaalrapport {#channel-report}

![](assets/image2014-11-28-16-3a39-3a28.png)

Het dashboard van RTP B2B helpt u de uitsplitsing van uw bezoekers volgens verticals en segmentatie begrijpen RTP. Je kunt de prestaties van je bezoeker zien op basis van de financiële sector en volgens verschillende marketingcampagnes (betaald, biologisch, sociaal). Het dashboard verstrekt ook een overzicht op hoog niveau van hoe uw segmenten RTP presteren en oefeningen neer om de hoogste organisaties te tonen die uw plaats bezoeken.

## Gedragsstroom {#behavioral-flow}

![](assets/image2014-11-28-16-3a40-3a43.png)

In het rapport Gedragstroming (zie afbeelding) wordt weergegeven hoe bezoekers van het pad van de ene pagina of gebeurtenis naar de volgende gaan. Het voorbeeld toont het pad van alle bezoekers uit de financiële sector. Dit rapport kan u helpen ontdekken wat de inhoud houdt bezoekers betrokken bij uw site.

## RTP-prestaties {#rtp-performance}

Meet uw campagnes RTP en correleer hen met uw algemeen plaatsgemiddelde. Leer hoe deze campagnes de metriek van uw website beïnvloeden en deze gegevens gebruiken om uw verpersoonlijkingsinspanningen op de juiste doelstellingen te concentreren. Genereer aangepaste rapporten om beter te begrijpen hoe uw personalisatiecampagnes presteren.

![](assets/image2014-11-28-16-3a47-3a0.png)

## RTP instellen met Google Analytics {#setting-up-rtp-with-google-analytics}

1. Voeg het e-mailbericht [`[email protected]`](https://docs.marketo.com/cdn-cgi/l/email-protection#0674727628616734466b67746d6372692865696b) toe als een gebruiker voor lezen en analyseren aan uw GA-account. Zie [hier](https://support.google.com/analytics/answer/2884495?hl=en) voor meer informatie.
1. In uw RTP-account. Ga naar **Accountinstellingen**.

   ![](assets/image2014-11-28-16-3a54-3a40.png)

1. Onder **Accountinstellingen**, **Domein** en **Analytics**
1. Klik op** Google Analytics.**
1. Schakel de relevante **Aangepaste variabelen** en **Gebeurtenissen** in om deze gegevens van RTP aan Google Analytics toe te voegen.
1. Voer het getal **Slot** in om aangepaste variabele gegevens te verzenden (de standaardwaarde is 1,2).

![](assets/image2014-11-28-17-3a0-3a17.png)

Klik **OPSLAAN**.

>[!NOTE]
>
>Als u segmentgegevens naar GA wilt verzenden, schakelt u onder [Segmentpagina bewerken](/help/marketo/product-docs/web-personalization/using-web-segments/create-a-basic-web-segment.md) in het RTP-platform het selectievakje **Gebeurtenis verzenden naar Google Analytics op segmentovereenkomst** in.

## De Rapporten van Google Analytics van de vestiging met Gegevens RTP {#setting-up-google-analytics-reports-with-rtp-data}

In Google Analytics kunt u dashboards, de segmentatie van GA, en het melden gebruiken om uw gegevens te bekijken RTP:

* [De ](https://support.google.com/analytics/answer/1068216?hl=en) dashboardslijst verstrekt een overzicht van de websiteprestaties.
* Een GA-segment is bedoeld om bezoekers in de GA-interface te filteren en het verkeer per segment weer te geven. Zie hoe u een segment [hier](https://support.google.com/analytics/answer/3124493?hl=en) bouwt.
* Het creëren van [aangepaste rapporten](https://support.google.com/analytics/answer/1033013?hl=en) aan mening en/of opstelling geplande e-mails. Zie onder Aanpassing > Nieuw aangepast rapport.
