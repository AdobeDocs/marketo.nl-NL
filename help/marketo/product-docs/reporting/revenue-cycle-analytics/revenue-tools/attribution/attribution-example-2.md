---
unique-page-id: 7514146
description: Attributievoorbeeld 2 - Marketo Docs - Productdocumentatie
title: Attributievoorbeeld 2
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '162'
ht-degree: 0%

---


# Attributievoorbeeld 2 {#attribution-example}

Lees het volgende scenario en probeer de aantallen te bepalen die in het net zouden moeten zijn.

* 11 april | Bill is overgenomen door (Tradeshow)
* 15 april | Joan is overgenomen door (Webinar)
* 22 april | (Opportunity 1) gemaakt voor $6.000
* 24 april | (Opportunity 2) gemaakt voor $10.000
* 25 april | Bill en Joan zijn geassocieerd met rollen aan **BEIDE **Optys
* 29 april | (Opportunity 1) is &#39;Closed Won&#39;

| Programmanaam | (Handelsversie) | (Webinar) |
|---|---|---|
| (FT) Opty Created | `<pre>1</pre>` | `<pre>1</pre>` |
| (FT) Pipet gemaakt | `<pre>$8,000</pre>` | `<pre>$8,000</pre>` |
| (FT) Opty Won | `<pre>0.5</pre>` | `<pre>0.5</pre>` |
| (FT) Opbrengst | `<pre>$3,000</pre>` | `<pre>$3,000</pre>` |

**Antwoorden tonen**

>[!NOTE]
>
>**Toelichting**
>
>Omdat Bill en Joan aan rollen aan **BEIDE **kansen werden geassocieerd, het systeem (volgens de regels) verdelen de kredieten gelijkelijk tussen hen.
>
>De pijpleiding die voor elk programma ($8.000) wordt gecreeerd is de helft van het totaal ($16.000) beschikbaar om als krediet te geven.

>[!NOTE]
>
>**Attributieregels**
>
>1. Krediet is gelijkmatig verdeeld
>1. Je kunt niet meer krediet geven dan je hebt verdiend
>1. Je kunt geen krediet geven voor iets dat in het verleden is gebeurd

>



<br> 

Probeer alle voorbeelden en je bent een attribuut pro!

>[!MORELIKETHIS]
>
>* [Attributievoorbeeld 1](attribution-example-1.md)
>* [Attributievoorbeeld 3](attribution-example-3.md)
>* [Attributievoorbeeld 4](attribution-example-4.md)

