---
unique-page-id: 2360370
description: Hoe te om de Statussen van het Programma en de statussen van de Campagne van Salesforce voorafgaand aan synchronisatie - Marketo Docs - de Documentatie van het Product aan te passen
title: Hoe te om de Statussen van het Programma en de Status van de Campagne Salesforce voorafgaand aan Synchronisatie aan te passen
exl-id: 623676ff-ce63-484f-8467-71127fa40fe0
feature: Salesforce Integration
source-git-commit: 0087a5e88b8bd9601875f68a2e7cadeebdb5d682
workflow-type: tm+mt
source-wordcount: '223'
ht-degree: 0%

---

# Hoe te om de Statussen van het Programma en de Status van de Campagne Salesforce voorafgaand aan Synchronisatie aan te passen {#how-to-match-program-statuses-and-salesforce-campaign-statuses-prior-to-sync}

In dit artikel wordt beschreven hoe u een incompatibele statusfout kunt oplossen en hoe u statussen kunt toewijzen vóór de synchronisatie van Marketo Program en Salesforce Campaign.

## Wat doet u als u een foutbericht hebt ontvangen {#what-do-you-do-if-you-received-an-error-message}

Als u probeert te synchroniseren met een bestaande Salesforce-campagne die leads bevat en de campagne een of meer incompatibele statussen bevat, wordt een foutbericht weergegeven. Een Marketo-programma en een Salesforce-campagne *niet* synchroniseren als de statussen niet exact overeenkomen.

![](assets/image2015-7-22-9-3a23-3a29.png)

Vanuit dit foutbericht kunt u kiezen voor:

1. Selecteer een andere campagne waarnaar u wilt synchroniseren in het keuzemenu, OF
1. U kunt de fout annuleren, de statusfouten herstellen en proberen te synchroniseren zodra de fouten zijn hersteld. Voer een van de volgende handelingen uit om de statusfouten te corrigeren:

   * Meld u aan bij Salesforce en verwijder of wijzig de naam van de incompatibele campagnelidstaten om de status van het Marketo-programma toe te wijzen die wordt gebruikt voor het kanaaltype dat is gekoppeld aan uw Marketo-programma.
   * Wijzig de status van het Programma in Marketo om aan de lidstaten van de Campagne Salesforce in kaart te brengen u op zijn plaats hebt. Dit is een Marketo Admin-functie. Zie voor meer informatie [Een programmakanaal maken](/help/marketo/product-docs/administration/tags/create-a-program-channel.md){target="_blank"}.
