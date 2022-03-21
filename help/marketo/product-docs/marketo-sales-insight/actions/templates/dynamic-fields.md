---
description: Dynamische velden - Marketo Docs - Productdocumentatie
title: Dynamische velden
hide: true
hidefromtoc: true
source-git-commit: 1db88a95777df43c3cef7ee5cabada2464329661
workflow-type: tm+mt
source-wordcount: '419'
ht-degree: 0%

---

# Dynamische velden {#dynamic-fields}

U kunt uw e-mailsjablonen aanpassen met vooraf gedefinieerde kenmerken, zoals `{{first_name}}` of `{{company}}`. Met deze velden kunt u meerdere contactpersonen per e-mail verzenden en deze velden automatisch aanvullen zonder dat u ze voor elk contact afzonderlijk hoeft in te voeren.

>[!TIP]
>
>Het veld &quot;first_name&quot; en &quot;bedrijf&quot; zijn de enige velden die zowel naar Handelingen voor het toezicht op de verkoop als naar Salesforce kijken. Dat betekent dat er geen contact bestaat in het [webtoepassing](https://toutapp.com/login)En dan kijken we in Salesforce of we een contact-/lead-record kunnen vinden met een bijbehorend e-mailadres. Vervolgens gebruiken we informatie uit die record om het veld te vullen.

## Een dynamisch veld invoegen in een sjabloon {#insert-a-dynamic-field-into-a-template}

1. In **Sjablonen en campagnes**, zoek de sjabloon die u wilt bewerken en klik op **Sjabloon bewerken**.

1. Klikken **Dynamisch veld invoegen**.

   >[!NOTE]
   >
   >Wanneer het e-mailen van contacten die in de Acties van het Inzicht van de Verkoop bestaan, kunt u de fundamentele dynamische gebieden gebruiken. Deze zullen zich direct uit het contact trekken.

Als je contacten in Salesforce e-mailt, kun je profiteren van de dynamische velden van Salesforce. Deze beginnen allemaal met &quot;sfdc&quot;. Zolang u een verbinding aan Salesforce hebt, zullen deze gebieden direct aan lood/contact in Salesforce roepen om informatie in het malplaatje te bevolken.

## Dynamische velden invoegen in een onderwerpregel {#insert-dynamic-fields-in-a-subject-line}

Kopieer en plak ze gewoon handmatig in het onderwerpveld van een e-mail, waarbij u ervoor zorgt dat u de juiste opmaak hebt.

## Woordenlijst Dynamische velden {#dynamic-fields-glossary}

Bij het creëren van een malplaatje in de Acties van het Inzicht van de Verkoop adviseren wij altijd het integreren van dynamische gebieden, gebruikend **Dynamisch veld invoegen** knop.

Dit gereedschap wordt gebruikt om `auto-personalize your email` en bespaar u veel tijd met `pulling information from the People page`.

| Dynamisch veld | Voorbeeld van wat er in uw e-mail wordt weergegeven |
|---|---|
| `{{company}}` | Marketo |
| `{{company_friendly}}` | Marketo |
| `{{first_name}}` | Keith |
| `{{friendly_unsubscribe}}` | Als je niet meer van mij wilt horen, laat het me hier weten |
| `{{my_name}}` | Alan Bradley |
| `{{personal_email}}` | keith@pickyouremail.com |
| `{{title}}` | Senior Technical Writer |
| `{{work_website}}` | https://www.marketo.com |

**Notities**:

* Als de contactgegevens onjuist zijn ingevoerd of ontbreken op de pagina Personen, worden deze niet correct in de sjabloon ingevoerd.
* Het verschil tussen `{{company}}` en `{{company_friendly}}` is `{{company_friendly}}` zal om het even welke formele titel, zoals Inc., LLC., enz., van de naam van het bedrijf van uw contact verwijderen.
* Wanneer u `{{company_friendly}}`, moet u Inc. of Co. scheiden met een komma in de contactgegevens. Dit is hoe de Acties van het Inzicht van de Verkoop weten wat te verwijderen wanneer het trekken in de waarde.
* U kunt uw e-mailsjablonen aanpassen met vooraf gedefinieerde kenmerken, zoals `{{my_name}}` of `{{my_title}}`. Met deze velden kunt u snel naar uzelf verwijzen in uw e-mailsjablonen.

>[!TIP]
>
>Als de dynamische velden niet worden gevuld, schakelt u deze uit [dit artikel](/help/marketo/product-docs/marketo-sales-insight/actions/faq/why-arent-my-dynamic-fields-filling-out).
