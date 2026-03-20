---
unique-page-id: 7514149
description: Leer meer over attributie voorbeeld 3 in Marketo Engage, met inbegrip van attributie voorbeeld 3 attributie-voorbeeld. Gebruik deze handleiding om de volgende stap te voltooien.
title: Attributievoorbeeld 3
exl-id: d8ca63a2-58de-4cde-b915-ff7f2e6468d9
feature: Reporting, Revenue Cycle Analytics
source-git-commit: 50befbf7339cd7a8b25b0942515497f6acc8f9ab
workflow-type: tm+mt
source-wordcount: '188'
ht-degree: 0%

---

# Attributievoorbeeld 3 {#attribution-example}

Lees het volgende scenario en probeer de aantallen te bepalen die in het net zouden moeten zijn.

* 11 april | Steve Downloads (Inhoud) - succes
* 22 april | Opportunity wordt gemaakt voor $3.000 (zowel Steve als Jason hebben rollen)
* 25 april | Jason Atends (Webinar) - succes
* 30 april | Opportunity is &#39;Closed Won&#39;

| Attributiemetrisch | (Inhoud) | (Webinar) |
|---|---|---|
| (MT) Opty Created | `<pre>1</pre>` | `<pre>0</pre>` |
| (MT) Pipet gemaakt | `<pre>$3,000</pre>` | `<pre>$0</pre>` |
| (MT) Opty Won | `<pre>0.5</pre>` | `<pre>0.5</pre>` |
| (MT) Woningopbrengsten | `<pre>$1,500</pre>` | `<pre>$1,500</pre>` |

**toon Antwoorden**

>[!NOTE]
>
>**Verklaring**
>
>Onthoud toewijzingsregel #3. Jason had succes met het programma NADAT de armoede was opgericht. Daarom kan het webinar geen krediet krijgen voor het creëren van de kans. Alleen krediet voor de Opty won.
>
>(Inhoud) heeft daarom 100% van de kredieten voor de oprichting en de pijpleiding van de Opty, maar slechts 50% van de kredieten voor de opty won.

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
>* [&#x200B; Voorbeeld van de Attributie 1 &#x200B;](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/attribution-example-1.md)
>* [&#x200B; Voorbeeld van de Attributie 2 &#x200B;](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/attribution-example-2.md)
>* [&#x200B; Voorbeeld van de Attributie 4 &#x200B;](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/attribution-example-4.md)
