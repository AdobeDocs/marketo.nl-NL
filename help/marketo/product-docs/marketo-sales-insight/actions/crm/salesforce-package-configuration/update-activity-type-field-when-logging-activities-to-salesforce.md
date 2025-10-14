---
description: Veld voor activiteitstypen bijwerken bij aanmelding bij Salesforce - Marketo Docs - Productdocumentatie
title: Veld voor activiteitstypen bijwerken bij aanmelding bij Salesforce
exl-id: 800323cb-2b99-42f1-ae30-0f87a9a1b4be
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '420'
ht-degree: 0%

---

# Veld voor activiteitstypen bijwerken bij aanmelding bij Salesforce {#update-activity-type-field-when-logging-activities-to-salesforce}

Met handelingen kunt u uw e-mailactiviteiten automatisch synchroniseren en Salesforce bellen voor rapportage en zichtbaarheid in de activiteitengeschiedenis verhogen. Wanneer het registreren van activiteiten, zorg ervoor het gebied van het Type van Activiteit behoorlijk wordt bijgewerkt aan E-mail, Vraag, of Antwoord, afhankelijk van welk type van activiteit wordt geregistreerd.

>[!NOTE]
>
>Het registreren van e-mails via BCC zal niet naar de lijst van het Type van Taak kijken, en zal in plaats daarvan automatisch het typegebied als &quot;e-mail&quot;vullen aangezien zij aan Salesforce door uw adres BCC worden geleverd.

## Informatie over dingen {#things-to-know}

* Voor het bijwerken van het taaktype is een verbinding met Salesforce vereist.
* Er zou geen standaardwaarde van het Type op de picklist van het Type van Taak moeten worden geselecteerd.
* De vraag, het Antwoord, en E-mail moeten allen in de picklist van het Type van Taak bestaan (kapitaliseert kwesties).
* Workflows of triggers in Salesforce die het veld Taaktype bijwerken, kunnen problemen opleveren met dit proces.

## Instellen {#setup}

Controleer eerst of u de juiste waarden voor de keuzelijst hebt. U hebt de hulp van uw Salesforce Admin nodig om wijzigingen aan te brengen in uw keuzelijst.

Controleer eerst welke waarden u in uw Picklist van het Type van Taak (uit E-mail, Vraag, en Antwoord) mist. Mogelijk hebt u de hulp van uw Salesforce Admin nodig om dit te controleren en wijzigingen aan te brengen in de keuzelijst Type activiteit. Om deze wijzigingen aan te brengen, kan uw Salesforce Admin de onderstaande stappen volgen.

### In Salesforce Lightning {#salesforce-lightning}

1. Navigeer aan [&#x200B; Salesforce.com &#x200B;](https://salesforce.com){target="_blank"}.
1. Klik het tandwielpictogram in de hoogste juiste hoek en selecteer **Opstelling** > **Manager van Objecten**.
1. Typ &quot;taak&quot; in het vak &#39;Snel zoeken&#39;.
1. In het linkerpaneel, klik **Gebieden &amp; Verhoudingen**.
1. Klik het etiket van het gebiedslabel **Type**.
1. Onder de Waarde van de Picklist van het Type van Taak, klik **Nieuw**.
1. Typ de naam van de waarden van de Picklist van het Type van Taak die ontbreken (&quot;E-mail, &quot;Vraag&quot;, &quot;Antwoord&quot;).
1. Klik **sparen**.

### In Salesforce Classic {#salesforce-classic}

1. Navigeer aan [&#x200B; Salesforce.com &#x200B;](https://salesforce.com){target="_blank"}.
1. Klik **>** Opstelling **>** aanpassen **>** Activiteiten **>** Gebieden van de Taak **.**
1. Klik **Type**.
1. Onder de Waarde van de Picklist van het Type van Taak, klik **Nieuw**.
1. Typ de naam van de waarden van de Picklist van het Type van Taak die ontbreken (&quot;E-mail, &quot;Vraag&quot;, &quot;Antwoord&quot;).
1. Klik **sparen**.

Nu dit op zijn plaats is, zult u beginnen te zien het gebied van het Type de overeenkomstige waarde voor geregistreerde E-mail, Vraag, en Reacties bevolken. Deze waarden zullen _niet_ op de herinneringstaken van de Acties van Insight van de Verkoop worden bevolkt.

>[!NOTE]
>
>Als u &quot;Reageren&quot;niet ziet als waarde, voeg het toe door **Nieuw** te klikken. Reageren is geen standaardwaarde in Salesforce.

>[!MORELIKETHIS]
>
>* [&#x200B; het Registreren de Attributen van de Activiteit van de Verkoop aan Salesforce &#x200B;](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-package-configuration/logging-sales-activity-attributes-to-salesforce.md){target="_blank"}
>* [&#x200B; vorm de Aanpassing van het Detail van de Activiteit van Salesforce &#x200B;](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-integration/configure-salesforce-activity-detail-customization.md){target="_blank"}
>* [&#x200B; de Activiteiten van de Verkoop van de Synchronisatie aan Salesforce &#x200B;](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-integration/sync-sales-activities-to-salesforce.md){target="_blank"}
