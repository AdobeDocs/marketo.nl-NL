---
unique-page-id: 7514149
description: Attributievoorbeeld 3 - Marketo Docs - Productdocumentatie
title: Attributievoorbeeld 3
exl-id: d8ca63a2-58de-4cde-b915-ff7f2e6468d9
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '161'
ht-degree: 0%

---

# Attributievoorbeeld 3 {#attribution-example}

Lees het volgende scenario en probeer de aantallen te bepalen die in het net zouden moeten zijn.

* 11 april | Steve Downloads (Content) - succes
* 22 april | Opportunity wordt gecreëerd voor $3.000 (Steve en Jason hebben rollen)
* 25 april | Jason Atends (Webinar) - succes
* 30 april | Opportunity is &#39;Closed Won&#39;

| Attributiemetrisch | (Inhoud) | (Webinar) |
|---|---|---|
| (MT) Opty Created | `<pre>1</pre>` | `<pre>0</pre>` |
| (MT) Pipet gemaakt | `<pre>$3,000</pre>` | `<pre>$0</pre>` |
| (MT) Opty Won | `<pre>0.5</pre>` | `<pre>0.5</pre>` |
| (MT) Woningopbrengsten | `<pre>$1,500</pre>` | `<pre>$1,500</pre>` |

**Antwoorden tonen**

>[!NOTE]
>
>**Toelichting**
>
>Onthoud toewijzingsregel #3. Jason had succes met het programma NADAT de armoede was opgericht. Daarom kan het webinar geen krediet krijgen voor het creëren van de kans. Alleen krediet voor de Opty won.
>
>(Inhoud) heeft daarom 100% van de kredieten voor de oprichting en de pijpleiding van de Opty, maar slechts 50% van de kredieten voor de opty won.

>[!NOTE]
>
>**Attributieregels**
>
>1. Krediet is gelijkmatig verdeeld
>1. Je kunt niet meer krediet geven dan je hebt verdiend
>1. Je kunt geen krediet geven voor iets dat in het verleden is gebeurd


Probeer alle voorbeelden en je bent een attribuut pro!

>[!MORELIKETHIS]
>
>* [Attributievoorbeeld 1](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/attribution-example-1.md)
>* [Attributievoorbeeld 2](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/attribution-example-2.md)
>* [Attributievoorbeeld 4](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/attribution-example-4.md)

