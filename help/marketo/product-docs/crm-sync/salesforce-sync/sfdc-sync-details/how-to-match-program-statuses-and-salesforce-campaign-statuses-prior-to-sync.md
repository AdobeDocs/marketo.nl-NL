---
unique-page-id: 2360370
description: Hoe kan ik programma-statussen en Salesforce-campagnestatussen afstemmen vóór synchronisatie - Marketo Docs - Productdocumentatie
title: Hoe te om de Statussen van het Programma en de Status van de Campagne van Salesforce voorafgaand aan Synchronisatie aan te passen
exl-id: 623676ff-ce63-484f-8467-71127fa40fe0
feature: Salesforce Integration
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '219'
ht-degree: 0%

---

# Uitleg over hoe te om de Statussen van het Programma en [!DNL Salesforce] Status van de Campagne voorafgaand aan Synchronisatie aan te passen {#how-to-match-program-statuses-and-salesforce-campaign-statuses-prior-to-sync}

In dit artikel wordt beschreven hoe u een incompatibele statusfout kunt oplossen en hoe u statussen kunt toewijzen vóór Marketo Program en [!DNL Salesforce] Campagne sync.

## Wat doet u als u een foutbericht hebt ontvangen {#what-do-you-do-if-you-received-an-error-message}

Als u probeert te synchroniseren met een bestaande [!DNL Salesforce] -campagne die leads bevat en de campagne een of meer incompatibele statussen bevat, wordt een foutbericht weergegeven. Een Programma van Marketo en a [!DNL Salesforce] Campagne *zullen niet* synchronisatie als de statussen geen nauwkeurige gelijke zijn.

![](assets/image2015-7-22-9-3a23-3a29.png)

Vanuit dit foutbericht kunt u kiezen voor:

1. Selecteer een andere campagne waarnaar u wilt synchroniseren in het keuzemenu, OF
1. U kunt de fout annuleren, de statusfouten herstellen en proberen te synchroniseren zodra de fouten zijn hersteld. Voer een van de volgende handelingen uit om de statusfouten te corrigeren:

   * Meld u aan bij Salesforce en verwijder of wijzig de naam van de incompatibele Campagnelidstaten om de status van het Marketo-programma toe te wijzen die wordt gebruikt voor het kanaaltype dat is gekoppeld aan uw Marketo-programma.
   * Wijzig de status van het Programma in Marketo om aan de lidstaten van de Campagne van Salesforce toe te wijzen u op zijn plaats hebt. Dit is een Marketo Admin-functie. Voor details, zie [ tot een Kanaal van het Programma ](/help/marketo/product-docs/administration/tags/create-a-program-channel.md){target="_blank"} leiden.
