---
description: Een tegengestelde landingspagina voor stroom gebruiken - Marketo Docs - Productdocumentatie
title: Een tegengestelde landingspagina voor stroom gebruiken
hide: true
hidefromtoc: true
feature: Dynamic Chat
source-git-commit: 5ef17e8c3988706a4d95332312ffb035f35bb269
workflow-type: tm+mt
source-wordcount: '226'
ht-degree: 0%

---

# Een tegengestelde landingspagina voor stroom gebruiken{#use-a-conversational-flow-landing-page}

Door een Dynamic Chat-conversie rechtstreeks in te sluiten in een Marketo Engage-landingspagina kunnen bezoekers een vergadering plannen via een Dynamic Chat zonder dat ze een formulier hoeven in te vullen of met een chatbot moeten communiceren.

>[!PREREQUISITES]
>
>Eenvoudig maken [Conversatievloeistroom](/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/create-a-conversational-flow.md) die alleen een **Boeking van vergadering** kaart.

## Aanvoerpagina&#39;s met instructies {#guided-landing-pages}

Sluit de volgende code in uw sjabloon voor de beweerde landingspagina in: `<div class="mktoConversation" id="exampleConversation" mktoName= "Example Conversation"></div>`.

Open de sjabloon Openingspagina met instructies in de editor en selecteer de tijdelijke aanduiding Conversationele stroom.

Klik de Conversationele drop-down Stroom en selecteer CF u in Stap 1 creeerde.

Leveringstype altijd behouden als **In line**. Klikken **Invoegen**.

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

