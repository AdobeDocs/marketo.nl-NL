---
unique-page-id: 14352407
description: Leveringskanaaloverzicht - Marketo Docs - Productdocumentatie
title: Overzicht van leveringskanaal
exl-id: 432bad1e-4eaf-4be8-b856-be364c44816e
feature: Marketo Sales Connect
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '552'
ht-degree: 0%

---

# Overzicht van leveringskanaal {#delivery-channel-overview}

Marketo [!DNL Sales Connect] biedt u meerdere opties voor het verzenden van e-mails. In dit artikel worden de leveringskanalen besproken die u kunt benutten, hoe u deze kunt selecteren en wanneer u elkaar kunt kiezen.

## Aanbevolen: Gmail of [!DNL Exchange] via e-mailverbinding {#recommended-gmail-or-exchange-via-email-connection}

Met [!DNL Sales Connect] kunt u een gestroomlijnde installatie en de verbeterde leveringsbaarheid tot stand brengen via onze E-mailverbindingsservice. [!UICONTROL Email Connection] staat elke gebruiker toe om met hun [ Gmail ](/help/marketo/product-docs/marketo-sales-connect/email-plugins/gmail/email-connection-for-gmail-users.md) of [ Uitwisseling ](/help/marketo/product-docs/marketo-sales-connect/email-plugins/msc-for-outlook/email-connection-for-outlook-users.md) rekening [!DNL Sales Connect] te verbinden om als leveringskanaal van keus voor alle [!DNL Sales Connect] e-mails worden gebruikt.

Het gebruik van Gmail of [!DNL Exchange] heeft enkele duidelijke voordelen ten opzichte van andere opties voor het leveringskanaal:

* Dit is een bewezen leveringskanaal met een gevestigde reputatie die helpt om leverbaarheid hoog te houden.
* Verificatiemethoden zoals SPF en DKIM worden al geconfigureerd en beheerd door uw IT-team, dus er is geen extra installatie.
* Het verzenden van e-mailberichten binnen een bepaald e-mailnetwerk (dat wil zeggen het verzenden van een e-mail als een [!DNL Exchange] -gebruiker naar een bedrijf dat e-mails ontvangt via [!DNL Exchange] ) kan de leesbaarheid verder verbeteren.

Het is belangrijk om op te merken dat deze leveringskanalen hun eigen verzendingsgrenzen hebben die door Microsoft en Google worden afgedwongen. Om dit te bestrijden, gebruiken wij een vertragingsmechanisme om gebruikers te helpen binnen die grenzen blijven. Leer meer over [ e-mailthrottling hier ](/help/marketo/product-docs/marketo-sales-connect/email/email-delivery/email-connection-throttling.md).

>[!NOTE]
>
>Standaard gebruikt de O365-plug-in altijd uw Exchange-leveringskanaal en gebruikt de Gmail-plug-in altijd uw Gmail-leveringskanaal om e-mails van de plug-ins te verzenden.

**Stuiteren het Volgen**: MSC kan grenzen voor [!DNL Exchange Online] of gebruikers ontdekken Gmail door het stuiterende bericht te ontdekken dat naar inbox van de afzender wordt verzonden. Deze stuiteringsberichten worden opgenomen in Sjabloonanalyses, Campagne-analyses en Live Feed-meldingen voor gebruikers. Stuitsporen wordt niet ondersteund voor klanten van [!DNL Exchange] On-Prem.

## Aangepast leveringskanaal via SMTP {#custom-delivery-channel-via-smtp}

[!DNL Sales Connect] biedt de extra optie aan om een server van derdeSMTP aan te sluiten die als voorkeursleveringskanaal van uw verkoopteam moet worden gebruikt.

Het gebruiken van een derde leverancier SMTP is een grote optie voor verkoopteams waarin het e-mailvolume de hoogste één prioriteit is. SMTP-providers zoals [!DNL Sendgrid] en [!DNL Sparkpost] zijn geoptimaliseerd om te voldoen aan de behoeften van bulkverzending van e-mails en kunnen worden geschaald om tegemoet te komen aan de behoeften van mensen die grote hoeveelheden e-mail willen implementeren.

Daarnaast bieden SMTP-providers van derden een groot aantal functies om de leveringsbehoeften van uw team te ondersteunen (zoals e-mailleveringsrapporten en toegewezen IP-adressen). Dit is een geweldige optie voor gebruikers die op zoek zijn naar meer gedetailleerde controles en zichtbaarheid rondom hun e-mailleveringskanaal.

## MSC-servers (verouderd) {#msc-servers-legacy}

MSC-servers zijn alleen beschikbaar voor sommige klanten van Legacy ToutApp. Die klanten zullen MSC servers beschikbaar in hun e-mailmontages zien. Alle niet-verouderde klanten zien MSC niet als een optie en moeten hun Gmail- of [!DNL Outlook] account verbinden met [!DNL Sales Connect] om een leveringskanaal te ontgrendelen.

MSC-servers bieden geen ondersteuning voor DKIM- en SPF-verificatiemethoden, waardoor de snelheid van de te leveren items kan worden verlaagd. Daarom raden we alle klanten aan verbinding te maken met Gmail of [!DNL Outlook] voor de beste leverbaarheid.

## Marketo-servers {#marketo-servers}

Marketo-e-mailservers integreren niet met [!DNL Sales Connect] . Marketo-servers zijn geoptimaliseerd voor bulkbezorging zodat ze kunnen worden geschaald met de behoeften van marketeers. Nochtans, hebben Gmail en [!DNL Exchange] een hogere succestarief voor 1 :1 verkoopmededeling, die is waarom wij adviseren gebruikend deze servers voor uw verkoopmededeling.

>[!MORELIKETHIS]
>
>* [ E-mailVerbinding voor de Gebruikers van Gmail ](/help/marketo/product-docs/marketo-sales-connect/email-plugins/gmail/email-connection-for-gmail-users.md)
>* [ E-mailVerbinding voor  [!DNL Outlook]  Gebruikers ](/help/marketo/product-docs/marketo-sales-connect/email-plugins/msc-for-outlook/email-connection-for-outlook-users.md)
>* [ Vestiging een Kanaal van de Levering van de Douane ](/help/marketo/product-docs/marketo-sales-connect/email/email-delivery/setting-up-a-custom-delivery-channel.md)
>* [ Het Throttling van de Verbinding E-mail ](/help/marketo/product-docs/marketo-sales-connect/email/email-delivery/email-connection-throttling.md)
