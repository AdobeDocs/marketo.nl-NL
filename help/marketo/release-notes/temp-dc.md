---
description: Aanvullende informatie voor Dynamic Chat - Documentatie voor Marketo - Productdocumentatie
title: Aanvullende informatie over Dynamic Chat
feature: Release Information, Dynamic Chat
hide: true
hidefromtoc: true
source-git-commit: 236c99d8939f076d93dfcd7988fc89e4c617c113
workflow-type: tm+mt
source-wordcount: '446'
ht-degree: 2%

---

# Opmerkingen bij de release TEMP Dynamic Chat {#dynamic-chat-release}

## Release september/oktober 2024 {#august-release}

### Verbeterde live chatanalyse {#enhanced-live-chat-analytics}

Er zijn verschillende verbeteringen aangebracht in het dashboard Analytics, waaronder:

* Totaal aangevraagd aantal actieve chatberichten: aantal bezoekers dat is aangevraagd voor een &quot;Chat met agent&quot;

* Totaal verbonden livechat: aantal verbonden bezoekers vs. totaal aangevraagd voor een &quot;Chat met agent&quot;

* Totaal aantal gemiste livechatverzoeken: aantal onbeheerde bezoekers versus totaal aangevraagd voor een &quot;Chat met agent&quot;

* Gemiddelde chatlengte in minuten: analyseren &quot;gemiddelde chatlengte&quot; tussen bezoekers en uw agenten

* Gemiddelde responstijd van de agent in seconden: analyseer de &quot;gemiddelde tijd die door de agents wordt genomen&quot; om te reageren op hun livechat Q&amp;A

* Dagelijks dashboard: livechatverzoeken zijn met succes verbonden, livechatverzoeken zijn overgeslagen, sorteren en filteren recente live chatactiviteiten

SCREENSHOT

### Gesprek {#conversation-scoring}

Kwaneer uw lood op de kwaliteit van hun praatjeinteractie en gebruik die metrisch als Trekker/Filter in Marketo Engage Slimme Campagnes. Gebruik de nieuwe attribuut _gespreksscore_ op de volgende activiteiten:

* Bij een dialoogvenster
* Behoefte aan een gespreksstroom
* Betrokken bij een agent

**Dingen aan nota te nemen:**

* De muziekwaarde ligt tussen 0, 1, 2 en 3 (standaardwaarde is null)

* Als de conversatie eenmaal is voltooid of verbroken, slaat u in de activiteit de waarde van de scoring op en plaatst u deze niet???????????????????????????????????? (wat betekent dit)

* Een score instellen:

   * In de agent inbox - tijdens een levende praatje, kan de agent een score voor het gesprek bijwerken of plaatsen, dat in de gespreksactiviteit wordt opgeslagen

   * In de stroomontwerper - in de doelkaart, kan de gebruiker een score voor het gesprek bijwerken of plaatsen

SCREENSHOT

SCREENSHOT

SCREENSHOT

### Nieuwe logica voor het maken van leads {#new-lead-creation-logic}

Als een lead een formulier invult met de e-mail `abc@test.com` en als xyz wordt gekookt, wordt later hetzelfde formulier ingevuld met de e-mail `def@test.com` , wordt een nieuwe lead gemaakt, maar wordt cookie xyz gekoppeld aan de nieuwe lead en verwijderd uit lead `abc@test.com` .

Vanaf dat moment is `abc@test.com` een lead zonder cookie. ANON LEAD?

Dus wanneer een bezoeker met cookie abc op een pagina landt en een e-mailadres opgeeft als `abc@p.com` :

TABEL

### Geoptimaliseerde de ladingstijd van de gespreksstroom {#optimized-conversation-flow-load-time}

Om de gebruikerservaring te verbeteren, wordt een shimmer lader nu getoond in plaats van een lege ruimte terwijl de gespreksstroom laadt. OMZETTEN OF CONVERSATIONEREN??

**vóór**

GIF

**na**

GIF

### Optie om lettertype over te nemen {#option-to-inherit-font}

Als gebruiker wil ik mijn chatsessie inschakelen om het lettertype rechtstreeks over te nemen van de webpagina waar het wordt geladen in plaats van mijn merklettertype te beheren in de Dynamic Chat

Opmerking: als u deze optie eenmaal hebt ingeschakeld, neemt Chatbot het lettertype over dat is gedefinieerd op de body-tag van de pagina
