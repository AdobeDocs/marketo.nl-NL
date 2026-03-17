---
unique-page-id: 2953243
description: Leer meer over berichttypen in Marketo, zoals een mislukking van de campagne, CRM-synchronisatie en betrokkenheid. Begrijp wat elke alarm betekent.
title: Typen meldingen
exl-id: 384cea0a-6252-4600-9211-aa5d6a7e875c
source-git-commit: 3efcb529cd3e35027f35e51dfd91f95e94af9d61
workflow-type: tm+mt
source-wordcount: '247'
ht-degree: 1%

---

# Typen meldingen {#notification-types}

Er zijn verschillende meldingstypen.

## Campagne mislukt  {#campaign-failure}

Fouten tijdens de campagne geven u een melding van fouten in uw slimme campagnes.

## CRM-synchronisatie {#crm-sync}

CRM-synchronisatieberichten geven een waarschuwing voor kritieke problemen die zich voordoen bij de CRM-synchronisatie, zoals onjuiste machtigingen of het neerzetten van de synchronisatie.

**[!DNL Microsoft Dynamics]**

[!DNL Dynamics] -meldingen worden elke 24 uur verzonden en bevatten leads die in die periode niet konden worden gesynchroniseerd. Typische oorzaken van een fout zijn dubbele leads (zoals hierboven) of onjuiste afstemmingen in de veldlengte.

![](assets/image2016-1-20-11-3a19-3a58.png)

**[!DNL Salesforce]**

Als u [!DNL Salesforce] gebruikt, zien synchronisatiefoutenmeldingen er ongeveer zo uit als hieronder. Typische fouten zijn verlopen gegevens en overschrijden de API-limieten.

![](assets/salesforcesyncerror.png)

## Betrokkenheid {#engagement}

Wanneer mensen uitgeput raken in een stroom, sturen wij een bericht. De kennisgeving bevat het aantal personen dat is uitgeput en enige andere informatie.

![](assets/image2014-10-14-10-3a57-3a9.png)

## Facebook {#facebook}

Als u mensen naar Facebook probeert te sturen zonder de servicevoorwaarden te accepteren, of als u mensen naar Facebook probeert te sturen nadat u de Marketo-app hebt verwijderd.

## Opruimen van campagne voor inactieve Trigger {#idle-trigger-campaign-cleanup}

Deactivate teweeggebrachte Slimme Campagnes die geen activiteit meer krijgen. Leer meer over [&#x200B; automatische opruiming van de trekkercampagne &#x200B;](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/using-smart-campaigns/automatic-trigger-campaign-cleanup.md).

## LinkedIn {#linkedin}

Als Marketo na drie pogingen geen nieuw publiek kan maken, meldt u zich aan of drukt u op e-mails naar LinkedIn.

![](assets/linkedin.png)

## Webservices {#web-services}

U wordt op de hoogte gesteld wanneer u uw dagelijkse quotum bereikt. De quota worden elke nacht opnieuw ingesteld om middernacht, Centrale Tijd.

>[!NOTE]
>
>Sommige foutencodes u kunt ontvangen worden geschetst in onze [&#x200B; Documentatie van de Ontwikkelaar &#x200B;](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/error-codes).
