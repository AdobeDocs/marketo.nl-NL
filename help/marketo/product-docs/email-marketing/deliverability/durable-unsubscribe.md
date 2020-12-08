---
unique-page-id: 10094576
description: Duurzaam abonnement - Marketo Docs - Productdocumentatie
title: Duurzaam abonnement opzeggen
translation-type: tm+mt
source-git-commit: 728066ab05de82f6123bfaa1f0b05af8632e32b2
workflow-type: tm+mt
source-wordcount: '321'
ht-degree: 0%

---


# Duurzaam abonnement opzeggen {#durable-unsubscribe}

Marketo heeft het gedrag van de functie voor het afmelden van abonnementen verbeterd om deze &#39;duurzaam&#39; te maken. We hebben een master e-mailstatus toegevoegd, die los staat van de markering voor afmelden die zichtbaar is in de persoonlijke detailrecord.

Als de markering voor afmelden is ingesteld op false (waar), wordt de master e-mailstatus bijgewerkt en wordt de wijziging doorgegeven aan andere personen met hetzelfde e-mailadres. Als een persoon wordt verwijderd en opnieuw gemaakt, of als een nieuwe record met hetzelfde e-mailadres wordt gemaakt, wordt de markering voor het afmelden **niet** overschreven.

>[!NOTE]
>
>De duurzame Unsubscribe werken over alle verdelingen in uw volledige gegevensbestand van de Marketo.

## De vlag voor het opzeggen van een abonnement bijwerken van Waar naar Onwaar (bijv. Een persoon opnieuw abonneren) {#update-the-unsubscribe-flag-from-true-to-false-e-g-re-subscribe-a-person}

Er zijn verschillende manieren waarop iemand opnieuw kan worden geabonneerd.

In Salesforce, **ontruim** het E-mailOpt uit gebied op het lood/contactpersoonverslag. Dit wordt gesynchroniseerd met Marketo.

![](assets/one.png)

Wis in Marketo het **vak voor opzeggen** op het tabblad Info van de record van de persoon.

![](assets/two.png)

Voer een **stap Gegevenswaarde** wijzigen uit zoals hieronder op een of meerdere personen wordt weergegeven.

![](assets/three.png)

Een bestaande persoon bijwerken via de SOAP API.

## Een nieuwe persoon maken {#creating-a-new-person}

Wanneer een nieuwe persoon wordt gecreeerd, controleert Marketo het tegen de master lijst van de e-mailstatus. Als de persoon eerder niet-geabonneerd was, zullen wij het verslag bijwerken om worden geabonneerd.

## Een e-mailadres wijzigen {#changing-an-email-address}

Als u het e-mailadres van een persoon wijzigt in een niet-geabonneerd e-mailadres, wordt het abonnement op die persoon opgezegd. Deze wijziging kan optreden in Marketo of Salesforce.

Als u een niet-geabonneerd e-mailadres wijzigt in een e-mailadres waarop wordt geabonneerd, wordt deze persoon geabonneerd.

## Opnieuw abonneren {#re-subscribing}

Net zoals een abonnement ertoe zou leiden dat alle mensen met hetzelfde e-mailadres niet meer worden geabonneerd, zou een abonnement elke persoon met hetzelfde e-mailadres opnieuw intekenen.

## Activiteitenlogboek {#activity-log}

De definities van de Verandering van de Waarde van gegevens voor *updateLeadEmailStatus* en *resetLeadEmailStatus* kunnen in [dit Communautair artikel](http://nation.marketo.com/t5/Knowledgebase/Durable-Unsubscribe-Activity-Log/ta-p/252688)worden gevonden.

>[!NOTE]
>
>**Verwante artikelen**
>
>[Abonnement begrijpen](understanding-unsubscribe.md)

