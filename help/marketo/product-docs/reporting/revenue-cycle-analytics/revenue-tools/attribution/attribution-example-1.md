---
unique-page-id: 7514126
description: Attributievoorbeeld 1 - Marketo Docs - Productdocumentatie
title: Attributievoorbeeld 1
translation-type: tm+mt
source-git-commit: 1a29614ec938074902af201b2ffc11cfaa625f7a
workflow-type: tm+mt
source-wordcount: '172'
ht-degree: 0%

---


# Attributievoorbeeld 1 {#attribution-example}

Lees het volgende scenario en probeer de aantallen te bepalen die in het net zouden moeten zijn.

* 11 april | Fred is verworven door (Tradeshow)
* 15 april | Margo-deelnemers (Webinar) - succes
* 22 april | Fred is gekoppeld (rol) aan de opportuniteit
* 22 april | Opportunity is gemaakt voor $3.000

| Programmanaam | (Handelsversie) | (Webinar) |
|---|---|---|
| (FT) Opty Created | `<pre>1</pre>` | `<pre>0</pre>` |
| (FT) Pipet gemaakt | `<pre>$3,000</pre>` | `<pre>$0</pre>` |
| (FT) Opty Won | `<pre>0</pre>` | `<pre>0</pre>` |
| (FT) Opbrengst | `<pre>0</pre>` | `<pre>0</pre>` |

**Antwoorden tonen**

>[!NOTE]
>
>**Toelichting**
>
>Ten eerste moet worden begrepen dat sommige soorten COUNTS zijn en andere VALUTA&#39;S. Opty Created is een telling, een geheel getal. Pipeline is een valuta. In Marketo voldoet de valuta aan de landinstellingen van uw beheerder.
>
>De handelsmaatschappij heeft alle kredieten ontvangen omdat Margo niet betrokken was bij een rol in de kans. Geen rol, geen krediet.

>[!NOTE]
>
>**Attributieregels**
>
>1. Krediet is gelijkmatig verdeeld
>1. Je kunt niet meer krediet geven dan je hebt verdiend
>1. Je kunt geen krediet geven voor iets dat in het verleden is gebeurd


Probeer alle voorbeelden en je bent een attribuut pro!

>[!NOTE]
>
>**Verwante artikelen**
>
>* [Attributievoorbeeld 2](attribution-example-2.md)
>* [Attributievoorbeeld 3](attribution-example-3.md)
>* [Attributievoorbeeld 4](attribution-example-4.md)

