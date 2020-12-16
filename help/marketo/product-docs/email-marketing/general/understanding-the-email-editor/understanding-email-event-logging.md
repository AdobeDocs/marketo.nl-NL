---
unique-page-id: 1147356
description: Inzicht in loggen van e-mailgebeurtenissen - Marketo Docs - Productdocumentatie
title: Logboekregistratie van e-mailgebeurtenissen
translation-type: tm+mt
source-git-commit: d7d6aee63144c472e02fe0221c4a164183d04dd4
workflow-type: tm+mt
source-wordcount: '300'
ht-degree: 0%

---


# Logboekregistratie van e-mailgebeurtenissen {#understanding-email-event-logging}

Bij het verzenden van e-mails registreert Marketo verschillende gegevenspunten naar de activiteitenlogboeken van de persoon. Hier zijn de basale.

| Gebeurtenis | Beschrijving |
|---|---|
| Verzonden | Wordt geregistreerd telkens als een e-mail van de servers van de Marketo wordt verzonden ongeacht of het eigenlijk wordt geleverd. Afgewezen e-mailberichten worden nog steeds geregistreerd als &#39;Verzonden&#39;. |
| Geleverd | Wordt geregistreerd telkens wanneer een e-mailbericht wordt geaccepteerd door de e-mailserver van de ontvanger. Dit betekent niet dat spamfilters vermeden zijn. Er kan slechts 1 levering zijn voor elke verzonden e-mail. |
| Hard geprononceerd | Sommige harde stormen zijn het resultaat van spamblokken, dus we zullen niet proberen die persoon 24 uur per campagne te e-mailen. Andere harde geluiden zoals niet-bestaande inboxes zijn permanent en we zullen de persoon nooit meer van een campagne e-mailen. |
| Zacht gebogen | Wordt geregistreerd wanneer een serverreactie onduidelijk is, brievenbus volledig of algemene serverkwesties. We zetten deze mensen wel 24 tot 36 uur door een retry-logica voor mogelijke toekomstige levering. Hierdoor wordt de persoon niet uitgesloten van andere mailings. |
| Geopend | Wordt geregistreerd als een ontvanger een e-mailbericht weergeeft met afbeeldingen NIET geblokkeerd. Er wordt slechts één open gebeurtenis per e-mail, per persoon, per slimme campagne geregistreerd. Als ze hetzelfde e-mailbericht twee keer openen vanuit hun Postvak IN, wordt het niet meer dan één keer geregistreerd. |
| Geklikt | Wordt geregistreerd wanneer een versierde URL uit de e-mail in de browser wordt geladen (het resultaat van het klikken op de koppeling). Doorgaans is dit de ontvanger die klikt, maar het kan ook een cut/paste zijn. |
| Abonnement opgezegd | Wordt geregistreerd als iemand op de koppeling voor het afmelden van een e-mail klikt en het afmeldingsformulier verzendt. |

>[!CAUTION]
>
>Als dezelfde e-mail twee keer vanuit dezelfde campagne naar dezelfde persoon wordt verzonden, wordt de gebeurtenis **Geopend** maximaal één keer geregistreerd.

