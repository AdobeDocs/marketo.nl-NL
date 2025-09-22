---
unique-page-id: 7514151
description: Attributievoorbeeld 4 - Marketo Docs - Productdocumentatie
title: Attributievoorbeeld 4
exl-id: 98cd7401-3bc7-40a1-b88d-7174a3027d4e
feature: Reporting, Revenue Cycle Analytics
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '204'
ht-degree: 0%

---

# Attributievoorbeeld 4 {#attribution-example}

Lees het volgende scenario en probeer de aantallen te bepalen die in het net zouden moeten zijn.

* 11 april | Michelle downloadt e-Book (content) - Voltooid
* 15 april | John attends (Webinar) - Succes
* 22 april | (Opportunity 1) gemaakt voor $3.000
* 24 april | (Opportunity 2) gemaakt voor $5.000
* 25 april | John en Michelle worden geassocieerd aan **allebei** Optys
* 29 april | [ Opty 1 ] is gesloten-Won

| Programmanaam | (Inhoud) | (Webinar) |
|---|---|---|
|   | (Opty 1) | (Opty 2) | (Opty 1) | (Opty 2) |
| (MT) Opty Created | `<pre>0.5</pre>` | `<pre>0.5</pre>` | `<pre>0.5</pre>` | `<pre>0.5</pre>` |
| (MT) Pipet gemaakt | `<pre>$1,500</pre>` | `<pre>$2,500</pre>` | `<pre>$1,500</pre>` | `<pre>$2,500</pre>` |
| (MT) Opty Won | `<pre>0.5</pre>` | `<pre>0</pre>` | `<pre>0.5</pre>` | `<pre>0</pre>` |
| (MT) Woningopbrengsten | `<pre>$1,500</pre>` | `<pre>$0</pre>` | `<pre>$1,500</pre>` | `<pre>$0</pre>` |

**toon Antwoorden**

>[!NOTE]
>
>**Verklaring**
>
>Als je meerdere mogelijkheden hebt en meerdere mensen met succes van programma&#39;s, moet je de kredieten verdelen tussen mensen en programma&#39;s. Merk echter op dat het krediet voor opportuniteit 1 en 2 niet gecombineerd wordt. Elk is een afzonderlijke kredietbeoordeling.
>
>Als er veel mensen bij betrokken zijn, zal Marketo automatisch de fracties berekenen van een kans om krediet te geven voor.

>[!NOTE]
>
>**Regels van de Attributie**
>
>1. Krediet is gelijkmatig verdeeld
>1. Je kunt niet meer krediet geven dan je hebt verdiend
>1. Je kunt geen krediet geven voor iets dat in het verleden is gebeurd

Probeer alle voorbeelden en je bent een attribuut pro!

>[!MORELIKETHIS]
>
>* [ Voorbeeld van de Attributie 1 ](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/attribution-example-1.md)
>* [ Voorbeeld van de Attributie 2 ](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/attribution-example-2.md)
>* [ Voorbeeld van de Attributie 3 ](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/attribution-example-3.md)
