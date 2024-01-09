---
description: Webinars op aanvraag - Marketo Docs - Productdocumentatie
title: Webinars op aanvraag
hide: true
hidefromtoc: true
feature: Interactive Webinars
source-git-commit: 49a75b6aef25787a68554dff3a847279ef8ba12a
workflow-type: tm+mt
source-wordcount: '464'
ht-degree: 0%

---

# Webinars op aanvraag {#on-demand-webinars}

On-Demand Webinars legt de leads vast die voor uw gebeurtenis zijn geregistreerd en die u niet hebt bijgewoond, en verfijnen deze. Ze willen echter wel informatie over de gebeurtenis opvragen door de opname te bekijken. Deze gegevens, zoals Naam, E-mail-id en Datum/duur controleren, kunnen in het Marketo Engage worden vastgelegd en worden gebruikt om deze &#39;no-show&#39;-leads te activeren.

De Webinar die met de registranten vóór de gebeurtenis werd gedeeld verbindt URL kan als verbinding worden gebruikt om de opname op bestelling te letten. Wanneer een registrant die de livegebeurtenis niet heeft bijgewoond, d.w.z. een lead met de status &quot;No-Show&quot; van het programma, op de Webinar Joining URL klikt, verandert de status van het programma van een dergelijke lead van &quot;No-Show&quot; in &quot;Attended On-Demand&quot;. De status van het programma van de leads die de gebeurtenis live hebben bekeken en de status &quot;Bijgewoond&quot; hebben, wordt niet beïnvloed, zelfs niet als ze de URL voor deelname bezoeken en de opname op aanvraag bekijken.

Adobe Connect, de technologie die interactieve webinars aandrijft, volgt het bezoek en de wachttijd van de leiders die de opname hebben bekeken en rapporteert dit dagelijks aan Marketo. De opname is 30 dagen na de gebeurtenis beschikbaar op de Joining-URL en de duur is vast.

Marketo biedt de statistieken van de bewaking van On-Demand Webinars op het tabblad Dashboard met behulp van de volgende twee widgets:
1. Samenvatting op aanvraag: Dit geeft een dagsgewijze samenvatting van het aantal bezoekers (No-Show) dat de opname heeft bekeken na de gebeurtenis.
2. Statistieken op aanvraag: Deze widgets bieden informatie over: a. Dagen dat de opname op aanvraag beschikbaar is voor weergave. Op deze manier kunnen marketers actie ondernemen, zoals het uitvoeren van e-mailcampagnes die zich dichter bij het einde van de beschikbaarheidsduur van de opname van 30 dagen bevinden.
b. Het totale aantal bezoekers voor webinars op aanvraag tot de datum. Dit is het aantal van alle No-Show-registranten die de opname op aanvraag tot datum hebben bekeken.
c. Gemiddelde wachttijd in minuten voor alle bezoekers. Hierdoor zou de markator een idee krijgen van hoeveel van de opname wordt bekeken en welke slimme campagnes kunnen worden gebruikt om lood boven een bepaalde horlogeduur te richten.

SCREENSHOT

De filters en triggers voor interactieve webinars zijn aangepast om rekening te houden met On-Demand Webinars. De trigger &quot;Gebeurtenis bijwonen&quot; en het filter &quot;Gebeurtenis heeft bijgewoond&quot; worden toegevoegd met een extra beperking &quot;Gebeurtenismodus&quot;, waarbij een markeerteken kan kiezen of het doel een live-publiek of een on-demand-publiek is. Als de beperking &quot;Gebeurtenismodus&quot; niet is geselecteerd, worden zowel het actieve als het on-demand publiek als doelgroep gekozen. Andere beperkingen zoals &quot;Datum van het Controle&quot;en &quot;het Duur van het Controle&quot;zouden met de &quot;op bestelling&quot;gebeurteniswijze kunnen worden gebruikt. Inactiviteitfilter &quot;Heeft geen gebeurtenis bijgewoond&quot; kan ook worden gebruikt voor webinars op aanvraag met de gebeurtenismodus &quot;Op aanvraag&quot;.
