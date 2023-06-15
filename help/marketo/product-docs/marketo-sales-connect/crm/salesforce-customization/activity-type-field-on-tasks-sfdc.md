---
unique-page-id: 14352476
description: Veld voor activiteitstypen op taken (SFDC) - Marketo Docs - Productdocumentatie
title: Veld voor activiteitstypen op taken (Activity Type Field on Tasks — SFDC)
exl-id: b291e641-d3af-4667-a01c-cd491cd87add
source-git-commit: 46c48172a58cf6bd2e9772ef57510fd7d808adc2
workflow-type: tm+mt
source-wordcount: '265'
ht-degree: 0%

---

# Veld voor activiteitstypen op taken (Activity Type Field on Tasks — SFDC) {#activity-type-field-on-tasks-sfdc}

Met de hulp van Sales Connect kunt u uw e-mails en gesprekken laten registreren als een activiteit in Salesforce. Een belangrijk onderdeel van het gebruik van waardevolle gegevens in Salesforce is dat in het veld Type de juiste waarde wordt ingevuld.

>[!NOTE]
>
>Het registreren van e-mails via BCC zal niet naar de lijst van het Type van Taak kijken, en zal in plaats daarvan automatisch het typegebied als &quot;e-mail&quot;vullen aangezien zij aan Salesforce door uw adres BCC worden geleverd.

## Vereisten {#requirements}

* Verbinding met Salesforce
* Er is geen standaardwaarde voor Standaardtype geselecteerd in de keuzelijst Taaktype
* De vraag, het Antwoord, en E-mail moeten allen onder de picklist van het Type van Taak (kapitalisatiekwesties) bestaan
* Geen Workflows of Triggers die actie ondernemen op de waarde van het veld Type

## Instellen {#setup}

Controleer eerst of u de juiste waarden voor de keuzelijst hebt. U hebt de hulp van uw Admin van Salesforce nodig om om het even welke veranderingen in uw picklist aan te brengen.

1. Navigeren naar [Salesforce.com](https://salesforce.com) en klik op Instellen in de rechterbovenhoek.
1. Klik op Aanpassen.
1. Klik op Activiteiten.
1. Klik op Taakvelden.
1. Klik op Tekst.
1. U bent nu bij de Picklist van het Type van Taak. Zorg ervoor dat er geen &#39;Standaard&#39; is geselecteerd.
1. Zorg ervoor dat er een waarde van het Type voor E-mail, Vraag, en Antwoord wordt vermeld.

Nu dit op zijn plaats is, zult u beginnen te zien het gebied van het Type de overeenkomstige waarde voor geregistreerde E-mail, Vraag, en Reacties bevolken. Deze waarden _niet_ worden ingevuld bij de taken voor verkoopConnect-herinneringen.

>[!NOTE]
>
>Als &#39;Reageren&#39; niet wordt weergegeven als een waarde, voegt u deze toe door op **Nieuw**. &#39;Reageren&#39; is geen standaardwaarde in Salesforce.
