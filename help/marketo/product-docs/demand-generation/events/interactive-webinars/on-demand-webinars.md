---
description: Webinars op aanvraag - Marketo Docs - Productdocumentatie
title: Webinars op aanvraag
feature: Interactive Webinars
exl-id: 65bfc1d2-6382-4cfa-9560-69cbb0c37c42
source-git-commit: 0bbe8110b7912cfbe04fdfc9b73c90fa9606a6b8
workflow-type: tm+mt
source-wordcount: '438'
ht-degree: 0%

---

# Webinars op aanvraag {#on-demand-webinars}

On-Demand Webinars legt de leads vast die voor uw gebeurtenis zijn geregistreerd en die u niet hebt bijgewoond, en verfijnen deze. Ze willen echter wel informatie over de gebeurtenis opvragen door de opname te bekijken. Informatie zoals Naam, E-mail-id en Datum/duur van controle kunnen in het Marketo Engage worden vastgelegd en worden gebruikt om deze leads zonder weergave te activeren.

Met de Webinar Joining URL die vóór de gebeurtenis met de geregistreerde personen is gedeeld, kunt u de opname op aanvraag bekijken. Wanneer een registrant die de livegebeurtenis niet heeft bijgewoond (bijvoorbeeld een lead met de status &quot;No-Show&quot; van het programma), op de Webinar Joining URL klikt, verandert de status van dat lead van &quot;No-Show&quot; in &quot;Attended On-Demand&quot;. De status van het programma van de leads die de gebeurtenis live hebben bekeken en de status &quot;Bijgewoond&quot; hebben, wordt niet gewijzigd als ze besluiten de URL voor deelname te bezoeken en de opname op aanvraag te bekijken.

Adobe Connect, de technologie die interactieve webinars aandrijft, volgt het bezoek en de wachttijd met betrekking tot de leads die de opname bekijken, en rapporteert de informatie dagelijks aan het Marketo Engage. 30 dagen na de gebeurtenis wordt het bijhouden van webinars op aanvraag stopgezet. De duur kan niet worden gewijzigd.

Marketo Engage verstrekt de horloge statistieken voor Webinars op bestelling op het lusje van het Dashboard met behulp van de volgende widgets:

* Samenvatting op aanvraag: Dit biedt een overzicht van het aantal bezoekers (geen presentaties) dat de opname na de gebeurtenis op een bepaalde dag of dagen bekijkt

* Statistieken op aanvraag: Deze widget biedt informatie over:
   * Dagen is de opname op aanvraag beschikbaar voor weergave. Hiermee kunnen marketers handelingen uitvoeren, zoals het uitvoeren van e-mailcampagnes vlak bij het einde van de beschikbaarheidsduur van de opname van 30 dagen.
   * Het totale aantal bezoekers voor webinars op aanvraag tot op heden: het aantal van alle registranten zonder weergave die de opname op aanvraag tot op heden hebben bekeken.
   * Gemiddelde controleduur in minuten voor alle bezoekers: geeft de marketers een idee hoeveel van de opname wordt bekeken en welke slimme campagnes kunnen worden gebruikt om leads boven een bepaalde controleduur te richten.

![](assets/on-demand-webinars-1.png)

De filters en triggers voor interactieve webinars zijn aangepast om rekening te houden met On-Demand Webinars. De trigger &quot;Gebeurtenis bijwonen&quot; en het filter &quot;Gebeurtenis heeft bijgewoond&quot; worden toegevoegd met een extra beperking (&quot;Gebeurtenismodus&quot;), waarbij een markeerteken kan kiezen of het doel een live-publiek of een on-demand-publiek is. Als de beperking Gebeurtenismodus niet is geselecteerd, wordt zowel het actieve als het on-demand-publiek als doelgroep gekozen. Andere beperkingen, zoals &quot;Datum van het Controle&quot;en &quot;Duur van het Controle,&quot;zouden met de &quot;op bestelling&quot;gebeurteniswijze kunnen worden gebruikt. Het inactiviteitsfilter &quot;Heeft geen gebeurtenis bijgewoond&quot; kan ook worden gebruikt voor webinars op aanvraag met de gebeurtenismodus &quot;Op aanvraag&quot;.
