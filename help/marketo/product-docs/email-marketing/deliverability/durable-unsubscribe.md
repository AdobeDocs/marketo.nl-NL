---
unique-page-id: 10094576
description: Duurzaam abonnement - Marketo Docs - Productdocumentatie
title: Duurzaam abonnement opzeggen
exl-id: e03a5a01-7395-45b3-8351-7931ec413236
feature: Deliverability
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '286'
ht-degree: 0%

---

# Duurzaam abonnement opzeggen {#durable-unsubscribe}

Marketo heeft het gedrag van de functie voor het afmelden van abonnementen verbeterd, zodat deze &#39;duurzaam&#39; is. We hebben een e-mailstatus van het stramien toegevoegd, die los staat van de markering voor afmelden die zichtbaar is in de record met persoonlijke gegevens.

Als de markering voor afmelden is ingesteld op false (waar), wordt de status van de e-mailhoofdtelefoon bijgewerkt en wordt de wijziging doorgegeven aan andere personen met hetzelfde e-mailadres. Als een persoon wordt verwijderd en ontspannen, of als een nieuw verslag met het zelfde e-mailadres wordt gecreeerd, zal de unsubscribe vlag **niet** worden beschreven.

>[!NOTE]
>
>Duurzaam Unsubscribe werkt over alle verdelingen in uw volledige Marketo-database.

## De vlag voor het opzeggen van een abonnement bijwerken van Waar naar Onwaar (bijvoorbeeld een persoon opnieuw abonneren) {#update-the-unsubscribe-flag-from-true-to-false-e-g-re-subscribe-a-person}

Er zijn verschillende manieren waarop iemand opnieuw kan worden geabonneerd.

Wis in Salesforce het veld E-mail uitschakelen in de record van de lead/contactpersoon. Dit wordt gesynchroniseerd met Marketo.

![ het scherm van Salesforce ](assets/durable-unsubscribe-1.png)

Wis in Marketo het vak voor afmelden op het tabblad Info van de record van de persoon.

![ ontruimend unsubscribe doos in een persoonverslag ](assets/durable-unsubscribe-2.png)

Stel a _de stroomstap van de Waarde van Gegevens van de Verandering_ zoals hieronder getoond op één of vele mensen in werking.

![ stap van de de gegevenswaarde van de Verandering ](assets/durable-unsubscribe-3.png)

## Een nieuwe persoon maken {#creating-a-new-person}

Wanneer een nieuwe persoon wordt gemaakt, controleert Marketo deze op de statustabel van de hoofd-e-mail. Als de persoon eerder niet-geabonneerd was, zullen wij het verslag bijwerken om worden geabonneerd.

## Een e-mailadres wijzigen {#changing-an-email-address}

Als u het e-mailadres van een persoon wijzigt in een niet-geabonneerd e-mailadres, wordt het abonnement op die persoon opgezegd. Deze wijziging kan optreden in Marketo of [!DNL Salesforce] .

## Opnieuw abonneren {#re-subscribing}

Net zoals een abonnement ertoe zou leiden dat alle mensen met hetzelfde e-mailadres niet meer worden geabonneerd, zou een abonnement elke persoon met hetzelfde e-mailadres opnieuw intekenen.

>[!MORELIKETHIS]
>
>[ Begrijpend Unsubscribe ](/help/marketo/product-docs/email-marketing/deliverability/understanding-unsubscribe.md)
