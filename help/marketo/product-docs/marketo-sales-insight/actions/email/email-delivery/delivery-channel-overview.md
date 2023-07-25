---
description: Leveringskanaaloverzicht - Marketo Docs - Productdocumentatie
title: Overzicht van leveringskanaal
exl-id: 8dd6fe3e-86ae-4361-bc0a-6488dc1df9fa
feature: Sales Insight Actions
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '668'
ht-degree: 0%

---

# Overzicht van leveringskanaal {#delivery-channel-overview}

Marketo Sales biedt je meerdere opties om e-mails te leveren. In dit artikel worden de leveringskanalen besproken die u kunt benutten, hoe u deze kunt selecteren en wanneer u elkaar kunt kiezen.

## Aanbevolen: Gmail of Exchange via e-mailverbinding {#recommended-gmail-or-exchange-via-email-connection}

Met Marketo Sales kunt u een gestroomlijnde installatie en de verbeterde leverbaarheid realiseren via onze E-mailverbindingsservice. Met de e-mailverbinding kan elke gebruiker verbinding maken met zijn [Gmail](/help/marketo/product-docs/marketo-sales-connect/email-plugins/gmail/email-connection-for-gmail-users.md) of [Exchange](/help/marketo/product-docs/marketo-sales-connect/email-plugins/msc-for-outlook/email-connection-for-outlook-users.md) account aan Marketo Sales voor gebruik als leveringskanaal voor alle e-mails over Marketo Sales.

Het gebruiken van Gmail of Uitwisseling komt met sommige duidelijke voordelen over andere opties van het leveringskanaal:

* Dit is een bewezen leveringskanaal met een gevestigde reputatie die helpt om leverbaarheid hoog te houden.
* De methodes van de authentificatie zoals SPF en DKIM worden reeds gevormd en beheerd door uw team van IT, zodat is er geen extra opstelling.
* Het verzenden van e-mailberichten binnen een bepaald e-mailnetwerk (dat wil zeggen, het verzenden van een e-mailbericht als Exchange-gebruiker naar een bedrijf dat e-mails ontvangt via Exchange) kan de leverbaarheid verder verbeteren.

Het is belangrijk om op te merken dat deze leveringskanalen hun eigen verzendingsgrenzen hebben die door Microsoft en Google worden afgedwongen. Om dit te bestrijden, gebruiken wij een vertragingsmechanisme om gebruikers te helpen binnen die grenzen blijven. Meer informatie over [e-mailvertraging hier](/help/marketo/product-docs/marketo-sales-connect/email/email-delivery/email-connection-throttling.md).

>[!NOTE]
>
>Standaard gebruikt de O365-plug-in altijd uw Exchange-leveringskanaal en gebruikt de Gmail-plug-in altijd uw Gmail-leveringskanaal om e-mails van de plug-ins te verzenden.

**Stuiteren bijhouden**: De Verkoop van Marketo kan grenzen voor de gebruikers van de Uitwisseling online of van Gmail ontdekken door het stuitbericht te ontdekken dat wordt verzonden naar inbox van de afzender. Deze stuiteringsberichten worden opgenomen in Sjabloonanalyses, Campagne-analyses en Live Feed-meldingen voor gebruikers. Stuitsporen wordt niet gesteund voor de klanten van de Uitwisseling op Prem.

## Aangepast leveringskanaal via SMTP {#custom-delivery-channel-via-smtp}

De Verkoop van Marketo biedt de extra optie om een server van derdeSMTP aan te sluiten die als voorkeursleveringskanaal van uw verkoopteam moet worden gebruikt.

Het gebruiken van een derde leverancier SMTP is een grote optie voor verkoopteams waarin het e-mailvolume de hoogste één prioriteit is. SMTP-providers zoals Sendgrid en Sparkpost zijn geoptimaliseerd om te voldoen aan de behoeften van bulkverzending van e-mails en kunnen worden geschaald om tegemoet te komen aan de behoeften van mensen die grote hoeveelheden e-mail willen implementeren.

Daarnaast bieden SMTP-providers van derden een groot aantal functies om de leveringsbehoeften van uw team te ondersteunen (zoals e-mailleveringsrapporten en toegewezen IP-adressen). Dit is een geweldige optie voor gebruikers die op zoek zijn naar meer gedetailleerde controles en zichtbaarheid rondom hun e-mailleveringskanaal.

## Marketo Sales Servers (verouderd) {#marketo-sales-servers-legacy}

Marketo Sales-servers zijn alleen beschikbaar voor sommige klanten van Legacy ToutApp. Deze klanten zien Marketo Sales-servers beschikbaar in hun e-mailinstellingen. Alle niet-verouderde klanten zien Marketo Sales niet als een optie en moeten hun Gmail- of Outlook-account verbinden met Marketo Sales om een leveringskanaal te ontgrendelen.

Marketo Sales-servers bieden geen ondersteuning voor DKIM- en SPF-verificatiemethoden, waardoor het leverbrengingspercentage kan worden verlaagd. Daarom raden we aan dat alle klanten verbinding maken met Gmail of Outlook voor de beste leverbaarheid.

## MSC-servers (verouderd) {#msc-servers-legacy}

MSC-servers zijn alleen beschikbaar voor sommige klanten van Legacy ToutApp. Die klanten zullen MSC servers beschikbaar in hun e-mailmontages zien. Alle niet-verouderde klanten zien MSC niet als een optie en moeten hun Gmail- of Outlook-account verbinden met Sales Connect om een leveringskanaal te ontgrendelen.

MSC-servers bieden geen ondersteuning voor DKIM- en SPF-verificatiemethoden, waardoor de snelheid van de te leveren items kan worden verlaagd. Daarom raden we aan dat alle klanten verbinding maken met Gmail of Outlook voor de beste leverbaarheid.

## Marketo-servers {#marketo-servers}

Marketo e-mailservers zijn niet geïntegreerd met Marketo Sales. Marketo-servers zijn geoptimaliseerd voor bulkbezorging zodat ze kunnen worden geschaald met de behoeften van marketeers. Nochtans, hebben Gmail en Uitwisseling een hogere succestarief voor 1:1 verkoopmededeling, die is waarom wij adviseren gebruikend deze servers voor uw verkoopmededeling.

>[!MORELIKETHIS]
>
>* [E-mailverbinding voor Gmail-gebruikers](/help/marketo/product-docs/marketo-sales-connect/email-plugins/gmail/email-connection-for-gmail-users.md)
>* [E-mailverbinding voor Outlook-gebruikers](/help/marketo/product-docs/marketo-sales-connect/email-plugins/msc-for-outlook/email-connection-for-outlook-users.md)
>* [Een aangepast leveringskanaal instellen](/help/marketo/product-docs/marketo-sales-connect/email/email-delivery/setting-up-a-custom-delivery-channel.md)
>* [Throtting van e-mailverbinding](/help/marketo/product-docs/marketo-sales-connect/email/email-delivery/email-connection-throttling.md)
