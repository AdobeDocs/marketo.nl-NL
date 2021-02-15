---
unique-page-id: 10094576
description: Duurzaam abonnement - Marketo Docs - Productdocumentatie
title: Duurzaam abonnement opzeggen
translation-type: tm+mt
source-git-commit: 6ae882dddda220f7067babbe5a057eec82601abf
workflow-type: tm+mt
source-wordcount: '319'
ht-degree: 0%

---


# Duurzaam abonnement {#durable-unsubscribe}

Marketo heeft het gedrag van de functie voor het afmelden van abonnementen verbeterd om deze &#39;duurzaam&#39; te maken. We hebben een master e-mailstatus toegevoegd, die los staat van de markering voor afmelden die zichtbaar is in de persoonlijke detailrecord.

Als de markering voor afmelden is ingesteld op false (waar), wordt de master e-mailstatus bijgewerkt en wordt de wijziging doorgegeven aan andere personen met hetzelfde e-mailadres. Als een persoon wordt verwijderd en opnieuw gemaakt, of als een nieuw verslag met het zelfde e-mailadres wordt gecreeerd, zal de unsubscribe vlag **not** worden beschreven.

>[!NOTE]
>
>De duurzame Unsubscribe werken over alle verdelingen in uw volledige gegevensbestand van de Marketo.

## Werk de vlag van Unsubscribe van Waar in Vals (b.v., re-subscribe een Persoon) {#update-the-unsubscribe-flag-from-true-to-false-e-g-re-subscribe-a-person} bij

Er zijn verschillende manieren waarop iemand opnieuw kan worden geabonneerd.

In Salesforce **clear** het veld E-mail uitschakelen in de record van de lead/contactpersoon. Dit wordt gesynchroniseerd met Marketo.

![](assets/one.png)

In Marketo, **clear** het unsubscribed vakje op het lusje van Info van het verslag van de persoon.

![](assets/two.png)

Voer een **Gegevenswaarde wijzigen**-stap uit zoals hieronder wordt weergegeven op een of meerdere personen.

![](assets/three.png)

Een bestaande persoon bijwerken via de SOAP API.

## Een nieuwe persoon maken {#creating-a-new-person}

Wanneer een nieuwe persoon wordt gecreeerd, controleert Marketo het tegen de master lijst van de e-mailstatus. Als de persoon eerder niet-geabonneerd was, zullen wij het verslag bijwerken om worden geabonneerd.

## Een e-mailadres wijzigen {#changing-an-email-address}

Als u het e-mailadres van een persoon wijzigt in een niet-geabonneerd e-mailadres, wordt het abonnement op die persoon opgezegd. Deze wijziging kan optreden in Marketo of Salesforce.

Als u een niet-geabonneerd e-mailadres wijzigt in een e-mailadres waarop wordt geabonneerd, wordt deze persoon geabonneerd.

## {#re-subscribing} opnieuw abonneren

Net zoals een abonnement ertoe zou leiden dat alle mensen met hetzelfde e-mailadres niet meer worden geabonneerd, zou een abonnement elke persoon met hetzelfde e-mailadres opnieuw intekenen.

## Activiteitenlogboek {#activity-log}

De definities van de Verandering van de Waarde van gegevens voor _updateLeadEmailStatus_ en _resetLeadEmailStatus_ kunnen in [dit Communautair artikel](https://nation.marketo.com/t5/Knowledgebase/Durable-Unsubscribe-Activity-Log/ta-p/252688) worden gevonden.

>[!MORELIKETHIS]
>
>[Abonnement begrijpen](/help/marketo/product-docs/email-marketing/deliverability/understanding-unsubscribe.md)
