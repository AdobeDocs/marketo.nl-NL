---
unique-page-id: 14352476
description: Veld voor activiteitstypen op taken (SFDC) - Marketo Docs - Productdocumentatie
title: Veld voor activiteitstypen op taken (SFDC)
exl-id: b291e641-d3af-4667-a01c-cd491cd87add
feature: Marketo Sales Connect
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '245'
ht-degree: 1%

---

# Veld voor activiteitstypen op taken (SFDC) {#activity-type-field-on-tasks-sfdc}

Met behulp van [!DNL Sales Connect] kunt u uw e-mails en oproepen als een activiteit laten registreren in [!DNL Salesforce] . Een belangrijk onderdeel van het hebben van waardevolle gegevens in [!DNL Salesforce] is dat in het veld [!UICONTROL Type] de juiste waarde wordt ingevuld.

>[!NOTE]
>
>Het registreren van e-mails via BCC zal niet naar de lijst van het Type van Taak kijken, en zal in plaats daarvan automatisch het typegebied als &quot;e-mail&quot;vullen aangezien zij aan [!DNL Salesforce] door uw adres BCC worden geleverd.

## Vereisten {#requirements}

* Verbinding maken met [!DNL Salesforce]
* Geen standaardwaarde voor Type geselecteerd in keuzelijst Taaktype
* De vraag, het Antwoord, en E-mail moeten allen onder de picklist van het Type van Taak (kapitaliseert kwesties) bestaan
* Geen Workflows of Triggers die actie ondernemen op de waarde van het veld Type

## Instellen {#setup}

Controleer eerst of u de juiste waarden voor de keuzelijst hebt. U hebt de hulp van uw [!DNL Salesforce] Admin nodig om wijzigingen aan te brengen in uw keuzelijst.

1. Navigeer aan [&#x200B; Salesforce.com &#x200B;](https://salesforce.com) en klik op Opstelling in de hoogste juiste hoek.
1. Klik op **[!UICONTROL Customize]**.
1. Klik op **[!UICONTROL Activities]**.
1. Klik op **[!UICONTROL Task Fields]**.
1. Klik op **[!UICONTROL Type]**.
1. U bent nu bij de Picklist van het Type van Taak. Zorg ervoor dat er geen &#39;Standaard&#39; is geselecteerd.
1. Controleer of er een [!UICONTROL Type] -waarde wordt vermeld voor [!UICONTROL Email] , [!UICONTROL Call] en [!UICONTROL Reply] .

Nu dit op zijn plaats is, zult u beginnen te zien het gebied van het Type de overeenkomstige waarde voor geregistreerde E-mail, Vraag, en Reacties bevolken. Deze waarden zullen _niet_ op Verkoop Connect herinneringstaken worden bevolkt.

>[!NOTE]
>
>Als &#39;Reageren&#39; niet wordt weergegeven als een waarde, voegt u deze toe door op **[!UICONTROL New]** te klikken. Reageren is geen standaardwaarde in [!DNL Salesforce] .
