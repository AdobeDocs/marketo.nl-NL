---
unique-page-id: 7514126
description: Attributievoorbeeld 1 - Marketo Docs - Productdocumentatie
title: Attributievoorbeeld 1
exl-id: 851cbad3-0f6d-4ea0-857f-8b15337c7540
feature: Reporting, Revenue Cycle Analytics
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '181'
ht-degree: 0%

---

# Attributievoorbeeld 1 {#attribution-example}

Lees het volgende scenario en probeer de aantallen te bepalen die in het net zouden moeten zijn.

* 11 april | Fred is overgenomen door (Tradeshow)
* 15 april | Margo bezoekt (Webinar) - succes
* 22 april | Fred is gekoppeld (rol) aan de opportunity
* 22 april | Opportunity is gemaakt voor $3.000

| Programmanaam | (Handelsversie) | (Webinar) |
|---|---|---|
| (FT) Opty Created | `<pre>1</pre>` | `<pre>0</pre>` |
| (FT) Pipet gemaakt | `<pre>$3,000</pre>` | `<pre>$0</pre>` |
| (FT) Opty Won | `<pre>0</pre>` | `<pre>0</pre>` |
| (FT) Opbrengst | `<pre>0</pre>` | `<pre>0</pre>` |

**toon Antwoorden**

>[!NOTE]
>
>**Verklaring**
>
>Ten eerste moet worden begrepen dat sommige soorten COUNTS zijn en andere VALUTA&#39;S. Opty Created is een telling, een geheel getal. Pipeline is een valuta. In Marketo voldoet de valuta aan de landinstellingen van uw beheerder.
>
>De handelsmaatschappij heeft alle kredieten ontvangen omdat Margo niet betrokken was bij een rol in de opportuniteit. Geen rol, geen krediet.

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
>* [&#x200B; Voorbeeld van de Attributie 2 &#x200B;](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/attribution-example-2.md)
>* [&#x200B; Voorbeeld van de Attributie 3 &#x200B;](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/attribution-example-3.md)
>* [&#x200B; Voorbeeld van de Attributie 4 &#x200B;](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/attribution-example-4.md)
