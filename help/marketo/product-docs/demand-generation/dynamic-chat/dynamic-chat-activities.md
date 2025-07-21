---
description: '[!DNL Dynamic Chat] Activiteiten - Marketo Docs - Productdocumentatie'
title: '[!DNL Dynamic Chat] Activiteiten'
exl-id: ef3bb1a3-6758-4798-92eb-fef28a5ff9c7
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '237'
ht-degree: 0%

---

# [!DNL Dynamic Chat] Activiteiten {#dynamic-chat-activities}

[!DNL Dynamic Chat] biedt verschillende filters en triggers voor gebruik in uw slimme lijsten.

![](assets/dynamic-chat-activities-1.png)

## Definities {#definitions}

<table>
<thead>
<tbody>
  <tr>
    <td style="width:25%"><b>Trigger</b></td>
    <td>Een triggergebeurtenis treedt op wanneer een bezoeker voldoet aan de criteria voor het opgeven van doelen voor een dialoog of omgekeerde stroom en het dialoogvenster wordt weergegeven.
    <br> Één trekkergebeurtenis per bezoeker, per zitting.</td>
  </tr>
  <tr>
    <td style="width:25%"><b>Gegenereerd met een Stroom/Dialoog van de Gesprek</b></td>
    <td>Een betrokkenheid vindt plaats wanneer een webbezoeker voor het eerst op een vraag in een Dialoog of Conversationele Stroom klikt (door op een meerkeuzeoptie te klikken, informatie te verzenden, een vergadering te boeken, een document te openen, enz.). Als een bezoeker een Dialoog of een Conversationele Stroom opent, maar niet op een herinnering klikt, wordt een overeenkomst <b> niet </b> geregistreerd. 
    <br> Één betrokkenheidsgebeurtenis per bezoeker, per zitting.</td>
  </tr>
   <tr>
    <td style="width:25%"><b>Betrokken bij een agent</b></td>
    <td>gebeurt wanneer een bezoeker met succes met een levende praatjeagent wordt verbonden.
    <br> één betrokken met agentengebeurtenis per bezoeker, per zitting.</td>
  </tr>
  <tr>
    <td style="width:25%"><b>Interactie met document</b></td>
    <td>gebeurt wanneer een bezoeker op een document in een documentkaart klikt.
    <br> Er kunnen veelvoudige documentinteractie per bezoeker, per zitting zijn.</td>
  </tr>
  <tr>
    <td style="width:25%"><b>Doelstellingen bereikt</b></td>
    <td>Vindt plaats wanneer een bezoeker een doel bereikt. <br> Er kunnen veelvoudige doel-bereikte gebeurtenissen per bezoeker, per zitting zijn.</td>
  </tr>
  <tr>
    <td style="width:25%"><b>Geplande vergadering</b></td>
    <td>Vindt plaats wanneer een bezoeker een vergadering met een Dynamic Chat-agent boekt.
    <br> Er kunnen veelvoudige vergadering-geboekte gebeurtenissen per bezoeker, per zitting zijn.</td>
  </tr>
</tbody>
</table>

## Notities {#things-to-note}

* Voorwaarden worden ondersteund in [!DNL Dynamic Chat] flowstappen
* [!DNL Dynamic Chat] -activiteiten kunnen worden gesynchroniseerd met [[!DNL Marketo Sales Insight]](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/dynamic-chat-integration.md){target="_blank"}
* U kunt afzonderlijke [!DNL Dynamic Chat] -activiteiten weergeven in het activiteitenlog van een Personen-record
