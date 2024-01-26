---
description: Activiteiten op het gebied van Dynamic Chat - Marketo Docs - Productdocumentatie
title: Dynamic Chat
feature: Dynamic Chat
exl-id: ef3bb1a3-6758-4798-92eb-fef28a5ff9c7
source-git-commit: b1101617ec670d42aed8c35044b656ba5fa0f9f5
workflow-type: tm+mt
source-wordcount: '254'
ht-degree: 0%

---

# Dynamic Chat {#dynamic-chat-activities}

Dynamic Chat biedt verschillende filters en triggers voor gebruik in uw slimme lijsten.

![](assets/dynamic-chat-activities-1.png)

## Definities {#definitions}

<table>
<thead>
<tbody>
  <tr>
    <td><b>Trigger</b></td>
    <td>Een triggergebeurtenis treedt op wanneer een bezoeker voldoet aan de criteria voor het opgeven van doelen voor een dialoog of omgekeerde stroom en het dialoogvenster wordt weergegeven.
    <br>Eén triggergebeurtenis per bezoeker, per sessie.</td>
  </tr>
  <tr>
    <td><b>Gegenereerd met een Stroom/Dialoog van de Gesprek</b></td>
    <td>Een betrokkenheid vindt plaats wanneer een webbezoeker voor het eerst op een vraag in een Dialoog of Conversationele Stroom klikt (door op een meerkeuzeoptie te klikken, informatie te verzenden, een vergadering te boeken, een document te openen, enz.). Als een bezoeker een dialoogvenster of een omgekeerde stroom opent, maar niet op een vraag klikt, is een betrokkenheid <b>niet</b> geregistreerd. 
    <br>Eén betrokkenheidsgebeurtenis per bezoeker, per sessie.</td>
  </tr>
   <tr>
    <td><b>Betrokken bij een agent</b></td>
    <td>gebeurt wanneer een bezoeker met succes met een levende praatjeagent wordt verbonden.
    <br>Eén persoon werkt per bezoeker aan een agentgebeurtenis, per sessie.</td>
  </tr>
  <tr>
    <td><b>Interactie met document</b></td>
    <td>gebeurt wanneer een bezoeker op een document in een documentkaart klikt.
    <br>Per sessie kunnen er meerdere documentinteracties per bezoeker zijn.</td>
  </tr>
  <tr>
    <td><b>Doelstellingen bereikt</b></td>
    <td>Vindt plaats wanneer een bezoeker een doel bereikt. <br>Per sessie kunnen er meerdere doelgerichte gebeurtenissen per bezoeker zijn.</td>
  </tr>
  <tr>
    <td><b>Geplande vergadering</b></td>
    <td>Vindt plaats wanneer een bezoeker een vergadering met een agent van de Dynamic Chat boekt.
    <br>Per sessie kunnen er meerdere door een vergadering geboekte gebeurtenissen per bezoeker zijn.</td>
  </tr>
</tbody>
</table>

## Notities {#things-to-note}

* Voorwaarden worden ondersteund in Dynamic Chat-stroomstappen
* Dynamics Chat kunnen worden gesynchroniseerd met [Marketo Sales Insight](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/dynamic-chat-integration.md){target="_blank"}
* U kunt de afzonderlijke activiteiten van de Dynamic Chat bekijken in het activiteitenlogboek van een Personen-record
