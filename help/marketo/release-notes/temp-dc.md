---
description: Aanvullende informatie voor Dynamic Chat - Documentatie voor Marketo - Productdocumentatie
title: Aanvullende informatie over Dynamic Chat
feature: Release Information, Dynamic Chat
hide: true
hidefromtoc: true
exl-id: 12130dee-2dbf-4e71-b542-30d4732b1067
source-git-commit: cc8de935451fe5d6dc9c8dad19962391d8ed3535
workflow-type: tm+mt
source-wordcount: '495'
ht-degree: 2%

---

# Opmerkingen bij de release TEMP Dynamic Chat {#dynamic-chat-release}

## Release september/oktober 2024 {#august-release}

### Verbeterde live chatanalyse {#enhanced-live-chat-analytics}

Er zijn verschillende verbeteringen aangebracht in het dashboard Analytics, waaronder:

* Totaal aangevraagd aantal actieve chatberichten: aantal bezoekers dat is aangevraagd voor een &quot;chat met agent&quot;

* Totaal verbonden livechat: aantal verbonden bezoekers vs. totaal aangevraagd voor een &quot;chat met agent&quot;

* Totaal aantal gemiste livechatverzoeken: aantal onbeheerde bezoekers versus totaal aangevraagd voor een &quot;chat met agent&quot;

* Gemiddelde chatlengte in minuten: analyseren &quot;gemiddelde chatlengte&quot; tussen bezoekers en uw agenten

* Gemiddelde Responstijd van de agent in seconden: analyseer de &quot;gemiddelde tijd die door agenten wordt genomen&quot;om op hun levende chat Q&amp;A te antwoorden

* Dagelijks dashboard: livechatverzoeken zijn met succes verbonden, livechatverzoeken zijn overgeslagen, sorteren en filteren recente live chatactiviteiten

SCREENSHOT

### Gesprek {#conversation-scoring}

Kwaneer uw lood op de kwaliteit van hun praatjeinteractie en gebruik die metrisch als Trekker/Filter in Marketo Engage Slimme Campagnes. Gebruik de nieuwe attribuut _gespreksscore_ op de volgende activiteiten:

* Bij een dialoogvenster
* Behoefte aan een gespreksstroom
* Betrokken bij een agent

**Dingen aan nota te nemen:**

* De muziekwaarde ligt tussen 0, 1, 2 en 3 (standaardwaarde is null)

* Zodra het gesprek wordt voltooid of gelaten vallen, in de activiteit sparen de het schrapen waarde en post dat het niet kan worden uitgegeven   ???? (wat betekent deze zin)

* Een score instellen:

   * In de agent inbox - tijdens een levende praatje, kan de agent een score voor het gesprek bijwerken of plaatsen, dat in de gespreksactiviteit wordt opgeslagen

   * In de stroomontwerper - in de doelkaart, kan de gebruiker een score voor het gesprek bijwerken of plaatsen

SCREENSHOT

SCREENSHOT

SCREENSHOT

### Nieuwe logica voor het maken van leads {#new-lead-creation-logic}

Als een lead een formulier invult met de e-mail `abc@test.com` en als xyz wordt gekookt, wordt later hetzelfde formulier ingevuld met de e-mail `def@test.com` , wordt een nieuwe lead gemaakt, maar wordt cookie xyz gekoppeld aan de nieuwe lead en verwijderd uit lead `abc@test.com` .

Vanaf dat moment is `abc@test.com` een lead zonder cookie. ANONIEME LEIDING?

Dus wanneer een bezoeker met cookie abc op een pagina landt en een e-mailadres opgeeft als `abc@test.com` :

TABEL

### Geoptimaliseerde de ladingstijd van de gespreksstroom {#optimized-conversation-flow-load-time}

Om de gebruikerservaring te verbeteren, wordt een shimmer lader nu getoond in plaats van een lege ruimte terwijl de gespreksstroom laadt. OMZETTEN OF CONVERSATIONEREN??

**vóór**

GIF

**na**

GIF

### Optie om lettertype over te nemen {#option-to-inherit-font}

U kunt de chatbot nu inschakelen om het lettertype rechtstreeks over te nemen van de webpagina waarop het wordt gehost, in plaats van het merklettertype in de Dynamic Chat te beheren. Wanneer u deze optie inschakelt, neemt de chatbot het lettertype dat is gedefinieerd op de `<body>` -tag van de pagina.

SCREENSHOT

### Integratie van de eisen met Dynamic Chat {#demandbase-integration-with-dynamic-chat}

De veeleisende gebruikers kunnen hun eigen vergunning van Demandbase brengen en de integratie activeren. De attributen van de de vraagbasis van het gebruik voor dialoog het richten, voorwaardelijke branding, en douane het verpletteren.

De resolutie van deze kenmerkwaarden ten opzichte van een lead wordt in realtime uitgevoerd en wordt opgeslagen in het desbetreffende hoofdprofiel.
