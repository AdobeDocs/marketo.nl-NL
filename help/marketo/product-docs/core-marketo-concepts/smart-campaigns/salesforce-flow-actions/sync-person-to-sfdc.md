---
unique-page-id: 1147027
description: Persoon synchroniseren naar SFDC - Marketo Docs - Productdocumentatie
title: Persoon synchroniseren naar SFDC
translation-type: tm+mt
source-git-commit: 00887ea53e395bea3a11fd28e0ac98b085ef6ed8
workflow-type: tm+mt
source-wordcount: '184'
ht-degree: 0%

---


# Persoon synchroniseren naar SFDC {#sync-person-to-sfdc}

>[!NOTE]
>
>**FYI**
>
>Marketo is nu bezig met het standaardiseren van de taal voor alle abonnementen, dus u ziet mogelijk leads/leads in uw abonnement en personen/personen in docs.marketo.com. Deze termen betekenen hetzelfde. het heeft geen invloed op de instructies van het artikel . Er zijn nog enkele andere veranderingen. [Meer](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)informatie.

>[!NOTE]
>
>Alleen beschikbaar bij integratie met Salesforce.

## Overzicht {#overview}

Met deze stroomstap worden personen die door Marketo zijn gemaakt als leads in uw Salesforce CRM ingevoegd.

![](assets/sync-person-to-sfdc.png)

## Gebruik {#usage}

1. Door gebrek, zal deze die stroomstap aan loodeigenaars toewijzen op de Salesforce auto-toewijzingsregels wordt gebaseerd.

   ![](assets/sync-person-to-sfdc.png)

   >[!TIP]
   >
   >Voor Salesforce moeten de velden Bedrijf en Achternaam van de persoon zijn ingevuld. Anders wordt de lead record geweigerd.

1. U kunt een specifieke gebruiker van Salesforce of een lood rij als lood eigenaar plaatsen.

   ![](assets/sync-person-to-sfdc-2.png)

   Wanneer u deze flowstap gebruikt, wordt de persoon onmiddellijk gesynchroniseerd als een Salesforce-lead en hoeft deze niet te wachten op de normale synchronisatie.

   >[!CAUTION]
   >
   >Salesforce staat niet toe dat &quot;Contacten&quot;worden toegewezen aan loodrijen. In dit geval maakt Marketo een duplicaat van &quot;Lead&quot; in Salesforce.

