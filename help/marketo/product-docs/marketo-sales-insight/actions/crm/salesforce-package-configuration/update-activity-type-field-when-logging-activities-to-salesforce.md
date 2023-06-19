---
description: Veld voor activiteitstypen bijwerken bij aanmelding bij Salesforce - Marketo Docs - Productdocumentatie
title: Veld voor activiteitstype bijwerken bij aanmelding van activiteiten bij Salesforce
exl-id: f65d7d97-ec65-4210-9381-02be788498f9
source-git-commit: 02354356949aef7aa8836d4753ec538b7819a65a
workflow-type: tm+mt
source-wordcount: '422'
ht-degree: 0%

---

# Veld voor activiteitstype bijwerken bij aanmelding van activiteiten bij Salesforce {#update-activity-type-field-when-logging-activities-to-salesforce}

Met handelingen kunt u uw e-mailactiviteiten automatisch synchroniseren en naar Salesforce bellen om deze te kunnen melden en de zichtbaarheid in de activiteitengeschiedenis te vergroten. Wanneer het registreren van activiteiten, zorg ervoor het gebied van het Type van Activiteit behoorlijk wordt bijgewerkt aan E-mail, Vraag, of Antwoord, afhankelijk van welk type van activiteit wordt geregistreerd.

>[!NOTE]
>
>Het registreren van e-mails via BCC zal niet naar de lijst van het Type van Taak kijken, en zal in plaats daarvan automatisch het typegebied als &quot;e-mail&quot;vullen aangezien zij aan Salesforce door uw adres BCC worden geleverd.

## Informatie over {#things-to-know}

* Voor het bijwerken van het taaktype is een verbinding met Salesforce vereist.
* Er zou geen standaardwaarde van het Type op de picklist van het Type van Taak moeten worden geselecteerd.
* De vraag, het Antwoord, en E-mail moeten allen in de picklist van het Type van Taak bestaan (kapitaliseert kwesties).
* Workflows of triggers in Salesforce die het veld Taaktype bijwerken, kunnen problemen opleveren met dit proces.

## Instellen {#setup}

Controleer eerst of u de juiste waarden voor de keuzelijst hebt. U hebt de hulp van uw Admin van Salesforce nodig om om het even welke veranderingen in uw picklist aan te brengen.

Controleer eerst welke waarden u in uw Picklist van het Type van Taak (uit E-mail, Vraag, en Antwoord) mist. Mogelijk hebt u de hulp van uw Salesforce Admin nodig om dit te controleren en wijzigingen aan te brengen in uw keuzelijst Type activiteit. Uw Salesforce-beheerder kan de onderstaande stappen volgen om deze wijzigingen aan te brengen.

### In Salesforce Lightning {#salesforce-lightning}

1. Navigeren naar [Salesforce.com](https://salesforce.com){target="_blank"}.
1. Klik op het tandwielpictogram in de rechterbovenhoek en selecteer **Instellen** > **Objectbeheer**.
1. Typ &quot;taak&quot; in het vak &#39;Snel zoeken&#39;.
1. Klik in het linkerdeelvenster op **Velden en relaties**.
1. Klikken op veldlabel **Type**.
1. Klik onder Picklist voor taaktype op **Nieuw**.
1. Typ de naam van de waarden van de Picklist van het Type van Taak die ontbreken (&quot;E-mail, &quot;Vraag&quot;, &quot;Antwoord&quot;).
1. Klikken **Opslaan**.

### In Salesforce Classic {#salesforce-classic}

1. Navigeren naar [Salesforce.com](https://salesforce.com){target="_blank"}.
1. Klikken **Instellen** > **Opbouwen** > **Aanpassen** > **Activiteiten** > **Taakvelden**.
1. Klikken **Type**.
1. Klik onder Picklist voor taaktype op **Nieuw**.
1. Typ de naam van de waarden van de Picklist van het Type van Taak die ontbreken (&quot;E-mail, &quot;Vraag&quot;, &quot;Antwoord&quot;).
1. Klikken **Opslaan**.

Nu dit op zijn plaats is, zult u beginnen te zien het gebied van het Type de overeenkomstige waarde voor geregistreerde E-mail, Vraag, en Reacties bevolken. Deze waarden _niet_ worden ingevuld bij Herinneringstaken voor Handelingen in het oog op verkoopgegevens.

>[!NOTE]
>
>Als &#39;Reageren&#39; niet wordt weergegeven als een waarde, voegt u deze toe door op **Nieuw**. &#39;Reageren&#39; is geen standaardwaarde in Salesforce.

>[!MORELIKETHIS]
>
>* [Kenmerken verkoopactiviteit registreren voor Salesforce](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-package-configuration/logging-sales-activity-attributes-to-salesforce.md){target="_blank"}
>* [Aanpassing Salesforce Activity Detail configureren](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-integration/configure-salesforce-activity-detail-customization.md){target="_blank"}
>* [Verkoopactiviteiten synchroniseren met Salesforce](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-integration/sync-sales-activities-to-salesforce.md){target="_blank"}
