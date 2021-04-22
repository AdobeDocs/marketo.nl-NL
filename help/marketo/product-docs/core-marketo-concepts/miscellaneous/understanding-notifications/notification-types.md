---
unique-page-id: 2953243
description: Meldingstypen - Marketo Docs - Productdocumentatie
title: Typen meldingen
exl-id: 384cea0a-6252-4600-9211-aa5d6a7e875c
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '246'
ht-degree: 0%

---

# Typen meldingen {#notification-types}

Er zijn verschillende meldingstypen.

## Campagne mislukt {#campaign-failure}

Fouten tijdens de campagne geven u een melding van fouten in uw slimme campagnes.

## CRM-synchronisatie {#crm-sync}

CRM-synchronisatieberichten geven een waarschuwing voor kritieke problemen die zich voordoen bij de CRM-synchronisatie, zoals onjuiste machtigingen of het neerzetten van de synchronisatie.

**Microsoft Dynamics**

Dynamische meldingen worden elke 24 uur verzonden en bevatten aanwijzingen die in die periode niet zijn gesynchroniseerd. Typische oorzaken van een fout zijn dubbele leads (zoals hierboven) of onjuiste overeenkomsten met veldlengte.

![](assets/image2016-1-20-11-3a19-3a58.png)

**Salesforce**

Als u Salesforce gebruikt, zien synchronisatiefoutenmeldingen er ongeveer zo uit als hieronder. Typische fouten zijn verlopen gegevens en overschrijden de API-limieten.

![](assets/salesforcesyncerror.png)

Betrokkenheid

Wanneer de leads uitgeput raken in een stream, sturen we een melding.  In de aanmelding zijn het aantal uitgedrukte leads en enige andere informatie opgenomen.

![](assets/image2014-10-14-10-3a57-3a9.png)

Facebook

Als u leads naar Facebook probeert te verzenden zonder de servicevoorwaarden te accepteren, of als u leads naar Facebook probeert te verzenden nadat u de Marketo-app hebt verwijderd.

Opruimen van campagne voor inactieve Trigger

Deactivate teweeggebrachte Slimme Campagnes die geen activiteit meer krijgen. Meer informatie over [opruimen van automatische triggercampagnes](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/using-smart-campaigns/automatic-trigger-campaign-cleanup.md).

LinkedIn

Als Marketo na drie pogingen geen nieuw publiek kan maken, meldt u zich aan of stuurt u per e-mail naar LinkedIn.

![](assets/linkedin.png)

Webservices

U wordt op de hoogte gesteld wanneer u uw dagelijkse quotum bereikt. De quota worden elke nacht opnieuw ingesteld om middernacht, Centrale Tijd.

>[!NOTE]
>
>Sommige foutcodes die u ontvangt, worden beschreven in onze [documentatie voor ontwikkelaars](https://developers.marketo.com/rest-api/error-codes/#response_level_error_codes).
