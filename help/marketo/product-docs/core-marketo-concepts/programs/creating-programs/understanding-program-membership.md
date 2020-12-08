---
unique-page-id: 1147091
description: Het begrip van het Lidmaatschap van het Programma - Marketo Docs - de Documentatie van het Product
title: Werken met het lidmaatschap van het programma
translation-type: tm+mt
source-git-commit: d78ecbec87d69cde66b583d21d7e0c95539bb6ec
workflow-type: tm+mt
source-wordcount: '308'
ht-degree: 0%

---


# Werken met het lidmaatschap van het programma {#understanding-program-membership}

>[!NOTE]
>
>Marketo is nu bezig met het standaardiseren van de taal voor alle abonnementen, dus u ziet mogelijk leads/leads in uw abonnement en personen/personen in docs.marketo.com. Deze termen betekenen hetzelfde. het heeft geen invloed op de instructies van het artikel . Er zijn nog enkele andere veranderingen. [Meer](/help/marketo/product-docs/crm-sync/salesforce-sync/understanding-the-salesforce-sync.md)informatie.

>[!NOTE]
>
>**Definitie:** Een lid is een persoon die een status in een programma heeft.

## Hoe mensen lid worden van een programma {#how-people-become-members-of-a-program}

1. Een persoon vult een [formulier in op een landingspagina](/help/marketo/getting-started/quick-wins/landing-page-with-a-form.md) in het programma.

   1. De persoon krijgt automatisch de eerste status in de progressie.

1. U [importeert leden in het programma](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/import-members-from-a-spreadsheet-into-a-program.md) vanuit een CSV-bestand.

   1. De persoon krijgt automatisch de eerste status in de progressie.

1. U gebruikt de stap voor de [statusstroom](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/program-flow-actions/change-program-status.md) van het wijzigingsprogramma.
1. Een persoon registreert of woont een [webinar bij die met een gebeurtenisprogramma](/help/marketo/product-docs/demand-generation/events/understanding-events/launchpoint-event-partners.md)wordt gesynchroniseerd.
1. Er wordt een persoon [gemaakt met de inchecktoepassing](/help/marketo/product-docs/core-marketo-concepts/mobile-apps/event-check-in/check-people-into-your-event-from-your-tablet.md)Marketo iPad.
1. Er wordt een persoon toegevoegd aan een SFDC-campagne, die [wordt gesynchroniseerd met het programma](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-campaign-sync.md).

>[!NOTE]
>
>Voor een e-mailprogramma wordt alleen een persoon aan het lidmaatschap toegevoegd wanneer het e-mailbericht wordt verzonden.

## Programmastatussen {#program-statuses}

Programmastatus zijn de stappen die mensen doorlopen in een programma (bijv. Uitgenodigd, RSVP&#39;d, Bijgewoond, Geen show). Deze stappen worden gedefinieerd door het [kanaal](/help/marketo/product-docs/administration/tags/create-a-program-channel.md).

![](assets/image2015-2-5-15-3a14-3a48.png)

>[!NOTE]
>
>Een persoon kan zich niet achterwaarts naar een vroegere programmastatus verplaatsen. Voortgang van de status is slechts één manier.

## Geslaagde statussen {#success-statuses}

Het doel van een programma is een zinvolle interactie met de persoon of het vooruitzicht tot stand te brengen. Het succes wordt duidelijk wanneer een persoon de status bereikt die dat doel bereikt.

>[!NOTE]
>
>Voor een webinar is registratie geen zinvolle interactie als ze niet echt naar het webinar kijken. Bijwonen is in dit geval een succes.

## Overnameprogramma  {#acquisition-program}

Wanneer een nieuwe naam het systeem als programmalid ingaat, plaatst Marketo automatisch dat programma als &quot;verwerving.&quot; Hiermee wordt krediet voor [First Touch-attributie](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/understanding-attribution.md)vastgesteld.

>[!MORELIKETHIS]
>
>* [Tags gebruiken in een programma](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/understanding-tags/use-tags-in-a-program.md)
>* [Een voortgangsrapport voor het programma maken](/help/marketo/product-docs/core-marketo-concepts/programs/program-performance-report/create-a-program-performance-report.md)

