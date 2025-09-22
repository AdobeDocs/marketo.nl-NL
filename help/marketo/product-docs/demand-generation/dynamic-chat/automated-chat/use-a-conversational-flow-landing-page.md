---
description: Een tegengestelde landingspagina voor stroom gebruiken - Marketo Docs - Productdocumentatie
title: Een tegengestelde landingspagina voor stroom gebruiken
hide: true
hidefromtoc: true
feature: Dynamic Chat
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '226'
ht-degree: 0%

---

# Een tegengestelde landingspagina voor stroom gebruiken{#use-a-conversational-flow-landing-page}

Door een Dynamic Chat Conversational Flow rechtstreeks in te sluiten in een Marketo Engage Landing Page kunnen bezoekers een vergadering plannen via Dynamic Chat zonder dat ze een formulier hoeven in te vullen of met een chatbot moeten communiceren.

>[!PREREQUISITES]
>
>Creeer een eenvoudige [ Conversationele Stroom ](/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/create-a-conversational-flow.md) die slechts a **het boeken van de Vergadering** kaart bevat.

## Aanvoerpagina&#39;s met instructies {#guided-landing-pages}

Sluit de volgende code in de sjabloon Openingspagina met instructies in: `<div class="mktoConversation" id="exampleConversation" mktoName= "Example Conversation"></div>` .

Open de sjabloon Openingspagina met instructies in de editor en selecteer de tijdelijke aanduiding Conversationele stroom.

Klik de Conversationele drop-down Stroom en selecteer CF u in Stap 1 creeerde.

Bewaar altijd het Type van Levering als **in-lijn**. Klik **Tussenvoegsel**.

De gespreksstroom u enkel inging zal als Element op het recht verschijnen.

SCREENSHOT

>[!NOTE]
>
>Op dit moment wordt de Conversational Flow niet weergegeven in het hoofdvenster van de voorvertoning.

## Landingspagina&#39;s in vrije vorm {#free-form-landing-pages}

Tekst

NOTITIES VAN STEVE-VERGADERING

geleide lp, nieuwe div id voor malplaatje, kies conv stroom

freeform lp, breng het pictogram over - caveat: voeg nota toe - wanneer u cf op de redacteur zet, toont het u geen voorproef (geen placeholder ook) - &quot;u zult geen voorproef zien&quot; - op sidebar zullen zij zien dat cf op de pagina is - geleid lp maakt het als element - gebruik &quot;op dit ogenblik&quot;wanneer het verklaren - de eigenschap gaat misschien week van 22nd
