---
unique-page-id: 2360370
description: Hoe te om de Statussen van het Programma en de statussen van de Campagne Salesforce voorafgaand aan synchronisatie - Marketo Docs - de Documentatie van het Product aan te passen
title: Hoe te om de Statussen van het Programma en de Status van de Campagne Salesforce voorafgaand aan Synchronisatie aan te passen
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '223'
ht-degree: 0%

---


# Hoe te om de Statussen van het Programma en de Status van de Campagne Salesforce voorafgaand aan Synchronisatie {#how-to-match-program-statuses-and-salesforce-campaign-statuses-prior-to-sync} aan te passen

In dit artikel wordt beschreven hoe u een incompatibele statusfout kunt oplossen en hoe u statussen kunt toewijzen vóór de synchronisatie van Marketo Program en Salesforce Campaign.

## Wat doet u als u een foutbericht {#what-do-you-do-if-you-received-an-error-message} hebt ontvangen

Als u probeert te synchroniseren met een bestaande Salesforce-campagne die leads bevat en de campagne een of meer incompatibele statussen bevat, wordt een foutbericht weergegeven. Een Marketo-programma en een Salesforce-campagne *synchroniseren niet* als de status niet exact overeenkomt.

![](assets/image2015-7-22-9-3a23-3a29.png)

Vanuit dit foutbericht kunt u kiezen voor:

1. Selecteer een andere campagne waarnaar u wilt synchroniseren in het keuzemenu, OF
1. U kunt de fout annuleren, de statusfouten herstellen en proberen te synchroniseren zodra de fouten zijn hersteld. Voer een van de volgende handelingen uit om de statusfouten te corrigeren:

   * Meld u aan bij Salesforce en verwijder of wijzig de naam van de incompatibele campagnelidstaten om de status van het Marketo-programma toe te wijzen die wordt gebruikt voor het kanaaltype dat is gekoppeld aan uw Marketo-programma.
   * Wijzig de Status van het Programma in Marketo om aan de lidstaten van de Campagne Salesforce in kaart te brengen u op zijn plaats hebt. Dit is een functie Marketo Admin. Zie [Programmakanaal maken](../../../../../product-docs/administration/tags/create-a-program-channel.md) voor meer informatie.

