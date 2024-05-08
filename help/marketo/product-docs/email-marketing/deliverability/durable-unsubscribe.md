---
unique-page-id: 10094576
description: Duurzaam abonnement - Marketo Docs - Productdocumentatie
title: Duurzaam abonnement opzeggen
exl-id: e03a5a01-7395-45b3-8351-7931ec413236
feature: Deliverability
source-git-commit: 35f5b33b01462b1cd00e29360daee465c7f18cf0
workflow-type: tm+mt
source-wordcount: '296'
ht-degree: 0%

---

# Duurzaam abonnement opzeggen {#durable-unsubscribe}

Marketo heeft het gedrag van de functie voor het afmelden van abonnementen verbeterd, zodat deze &#39;duurzaam&#39; is. We hebben een e-mailstatus van het stramien toegevoegd, die los staat van de markering voor afmelden die zichtbaar is in de record met persoonlijke gegevens.

Als de markering voor afmelden is ingesteld op false (waar), wordt de status van de e-mailhoofdtelefoon bijgewerkt en wordt de wijziging doorgegeven aan andere personen met hetzelfde e-mailadres. Als een persoon wordt verwijderd en opnieuw gemaakt, of als een nieuw verslag met het zelfde e-mailadres wordt gecreeerd, zal de unsubscribe vlag **niet** worden overschreven.

>[!NOTE]
>
>Duurzaam Unsubscribe werkt over alle verdelingen in uw volledige Marketo-database.

## De vlag voor het opzeggen van een abonnement bijwerken van Waar naar Onwaar (bijvoorbeeld een persoon opnieuw abonneren) {#update-the-unsubscribe-flag-from-true-to-false-e-g-re-subscribe-a-person}

Er zijn verschillende manieren waarop iemand opnieuw kan worden geabonneerd.

In Salesforce **duidelijk** het veld E-mail uitschakelen in de record van de lead/contactpersoon. Dit wordt gesynchroniseerd met Marketo.

![](assets/one.png)

In Marketo: **duidelijk** het niet-geabonneerde vak op het tabblad Info van de record van de persoon.

![](assets/two.png)

Een **Gegevenswaarde wijzigen** stroomstap zoals hieronder weergegeven bij een of meer personen.

![](assets/three.png)

Een bestaande persoon bijwerken via de SOAP API.

## Een nieuwe persoon maken {#creating-a-new-person}

Wanneer een nieuwe persoon wordt gemaakt, controleert Marketo deze op de statustabel van de hoofd-e-mail. Als de persoon eerder niet-geabonneerd was, zullen wij het verslag bijwerken om worden geabonneerd.

## Een e-mailadres wijzigen {#changing-an-email-address}

Als u het e-mailadres van een persoon wijzigt in een niet-geabonneerd e-mailadres, wordt het abonnement op die persoon opgezegd. Deze wijziging kan optreden in Marketo of Salesforce.

Als u een niet-geabonneerd e-mailadres wijzigt in een e-mailadres waarop wordt geabonneerd, wordt deze persoon geabonneerd.

## Opnieuw abonneren {#re-subscribing}

Net zoals een abonnement ertoe zou leiden dat alle mensen met hetzelfde e-mailadres niet meer worden geabonneerd, zou een abonnement elke persoon met hetzelfde e-mailadres opnieuw intekenen.

>[!MORELIKETHIS]
>
>[Abonnement begrijpen](/help/marketo/product-docs/email-marketing/deliverability/understanding-unsubscribe.md)
