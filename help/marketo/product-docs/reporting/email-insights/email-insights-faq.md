---
unique-page-id: 10100257
description: Veelgestelde vragen over e-mail - Marketo Docs - Productdocumentatie
title: Veelgestelde vragen over e-mail
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '600'
ht-degree: 0%

---


# Veelgestelde vragen over e-mail {#email-insights-faq}

## Zijn er verschillen tussen de maatstaven voor ratio&#39;s met e-mailinzichten en andere rapportage via e-mail? {#are-there-any-differences-between-ratio-metrics-with-email-insights-and-other-marketo-email-reporting}

Ja. E-mailinzichten correleren de betrokkenheidsmetriek met de bijbehorende leveringscijfers voor dezelfde e-mail die wordt verzonden bij het berekenen van de metrische verhoudingen van de betrokkenheid (Open Rate, Click-to-Open Rate, Unsubscribe Rate). Bijvoorbeeld, in E-mailInzichten, wanneer het bekijken van een tijdreeksengrafiek over de afgelopen week met dagelijkse onderverdelingen van klik-aan-Open-Tarief, tonen wij nu de ware gecorreleerde verhouding van open/klik/unsubscribe gebeurtenissen die op de overeenkomstige leveringsmetriek worden gebaseerd. Dit is in tegenstelling tot het gedrag in de Ontdekkingsreiziger van de Ontvangsten, die eenvoudig alles samenvat. E-mailinzichten bieden een nauwkeuriger weergave van de betrokkenheidsverhoudingen.

## Waarom ondersteunt e-mailinzichten alleen 10 aangepaste Dimension? {#why-does-email-insights-only-support-custom-dimensions}

In veel gevallen is het uitbreiden van de standaardsysteemafmetingen met 10 extra aangepaste afmetingen meer dan toereikend en bevat dit aangepaste afmetingen die zijn gebaseerd op Segmentaties of Programmacodes. In de toekomst, zijn wij van plan om klanten toe te staan om het aantal toegestane Dimension van de Douane te verhogen.

## Waarom kan ik geen groeven van de Dimension van de Douane hergebruiken nadat zij zijn toegewezen? {#why-cant-i-re-use-custom-dimensions-slots-after-theyve-been-assigned}

Als een bepaalde Eigen Dimension groef is toegewezen, zou het opnieuw in kaart brengen vorige gegevens veroorzaken om een fout te veroorzaken wanneer het mengen met een nieuwe betekenis. Daarom kunnen aangepaste Dimension-sleuven niet opnieuw worden gebruikt. Dit gedrag is verenigbaar met dat van andere metrische analysehulpmiddelen, zoals Google Analytics.

## Ondersteunt e-mails van Marktto Sales Insight? {#does-email-insights-support-marketo-sales-insight-emails}

Ja. Alle e-mails die via Marketo Sales Insights worden verzonden, worden opgenomen in e-mailinzichten.

## Ondersteunt e-mailinzichten operationele e-mails? {#does-email-insights-support-operational-emails}

Ja. Operationele e-mails zijn standaard verborgen voor weergave en zoeken. U kunt deze instelling echter wijzigen in het deelvenster Persoonlijke instellingen.

## Wordt met e-mailinzichten terugkerende geplande of opnieuw uitgevoerde e-mailstroomstappen voor Smart Campagne vastgelegd? {#does-email-insights-capture-recurring-scheduled-or-re-run-smart-campaign-email-flow-steps}

Ja en Nee. Met de eerste release van Email Insights worden alle e-mailgebeurtenissen vastgelegd en toegankelijk voor elke terugkerende geplande of opnieuw uitgevoerde slimme campagne. Maar je zult geen onderscheid kunnen maken tussen verschillende onderdelen van die slimme campagne. Wij voegen steun in onze volgende versie toe om de Slimme looppasinformatie van de Campagne voor Open, Klik, en Unsubscribe gebeurtenissen te vangen om zich te onderscheiden.

## Waarom geven veel metriek nul weer wanneer ik filtreer op Apparaattype of Apparaatbesturingssysteem? {#why-do-many-metrics-show-zero-when-i-filter-by-device-type-or-device-os}

Met uitzondering van klik-aan-Open-Tarief, Opens, Kliks, en Unsubscribes, zijn alle andere gesteunde metriek of leveringsgebeurtenissen of verhoudingen die uit leveringsgebeurtenissen worden afgeleid. Omdat het Type van Apparaat en het OS van Apparaat slechts op de metriek van de Betrokkenheid van toepassing zijn, hebben wij eenvoudig niet de informatie aan vertoning. Bijvoorbeeld, is het een ongedefinieerde vraag om het Tarief van de Levering te vragen wanneer gefiltreerd door Type van Apparaat = mobiel, aangezien Marketo geen metriek van de Betrokkenheid voor of de onderliggende Levering en Verzonden gebeurtenissen zou ontvangen. We onderzoeken manieren om het apparaattype en het apparaatbesturingssysteem toe te passen op basis van betrokkenheidsmetriek voor verhoudingen die bestaan uit de metriek voor betrokkenheid en levering.

## Wat doet e-mailinzichten wanneer bepaalde e-mailclients afbeeldingen blokkeren? {#what-does-email-insights-do-when-certain-email-clients-block-images}

Een veelvoorkomend industrieprobleem is dat steeds meer e-mailclients afbeeldingen standaard uitschakelen. Afbeeldingen laden is de basis voor het opnemen van Openens. Het is volledig mogelijk dat een gebruiker een e-mail ontvangt met afbeeldingen geblokkeerd, maar met de tekst en koppelingen volledig leesbaar. Als een gebruiker dit had ervaren en op een verbinding in die e-mail klikte, zou u uitkomen met een scenario van een gebeurtenis van de Klik, maar geen overeenkomstige Open gebeurtenis voor bovengenoemde e-mail. Marketo Email Insights genereert automatisch alle ontbrekende gebeurtenissen. De logica is identiek aan hoe Marketo dit voor het E-mailprestatiesrapport, evenals het gebied van de Analyse E-mail in de Ontdekkingsreiziger van de Inkomsten doet.
