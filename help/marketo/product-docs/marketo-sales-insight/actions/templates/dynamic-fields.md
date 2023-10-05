---
description: Dynamische velden - Marketo Docs - Productdocumentatie
title: Dynamische velden
exl-id: d9e52eae-d5bb-462f-8b7b-c28a560f6ea4
feature: Sales Insight Actions
source-git-commit: 7c8703059d7d28afbf57f4f285ac972fb9d8fbef
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# Dynamische velden {#dynamic-fields}

U kunt uw e-mailsjablonen aanpassen met vooraf gedefinieerde kenmerken, zoals `{{first_name}}` of `{{company}}`. Met deze velden kunt u meerdere contactpersonen per e-mail verzenden en deze velden automatisch aanvullen zonder dat u ze voor elk contact afzonderlijk hoeft in te voeren.

>[!TIP]
>
>Het veld &quot;first_name&quot; en &quot;bedrijf&quot; zijn de enige velden die zowel naar Handelingen voor het toezicht op de verkoop als naar Salesforce kijken. Dat betekent dat er geen contact bestaat in het [webtoepassing](https://toutapp.com/login)En dan kijken we in Salesforce of we een contact/lead record kunnen vinden met een bijbehorend e-mailadres. Vervolgens gebruiken we informatie uit die record om het veld te vullen.

## Een dynamisch veld invoegen in een sjabloon {#insert-a-dynamic-field-into-a-template}

1. In **Sjablonen en campagnes**, zoek de sjabloon die u wilt bewerken en klik op **Sjabloon bewerken**.

1. Klikken **Dynamisch veld invoegen**.

   >[!NOTE]
   >
   >Wanneer het e-mailen van contacten die in de Acties van het Inzicht van de Verkoop bestaan, kunt u de fundamentele dynamische gebieden gebruiken. Deze zullen zich direct uit het contact trekken.

Als je contacten in Salesforce e-mailt, kun je profiteren van de dynamische velden van Salesforce. Deze beginnen allemaal met &quot;sfdc&quot;. Zolang u een verbinding aan Salesforce hebt, zullen deze gebieden direct aan lood/contact in Salesforce roepen om informatie in het malplaatje te bevolken.

## Dynamische velden invoegen in een onderwerpregel {#insert-dynamic-fields-in-a-subject-line}

Kopieer en plak ze gewoon handmatig in het onderwerpveld van een e-mail, waarbij u ervoor zorgt dat u de juiste opmaak hebt.

## Standaardwaarden dynamisch veld {#dynamic-field-default-values}

Wanneer u dynamische velden toevoegt aan uw e-mailsjablonen, kunt u een standaardwaarde toevoegen die in het dynamische veld wordt gebruikt als er geen andere waarde beschikbaar is.

Hiervoor voegt u &quot;|&quot; toe na het dynamische veldlabel en voegt u &quot;default:&quot; (beide zonder aanhalingstekens) toe. Voeg vervolgens de waarde toe waarnaar het veld moet verwijzen (tussen aanhalingstekens) als er geen andere waarde kan worden gevonden.

**Voorbeeld:**

`{{first name | default: "loyal customer"}}`

`{{sfdc_contact_account_name | default: "your company"}}`

## Woordenlijst Dynamische velden {#dynamic-fields-glossary}

Bij het creëren van een malplaatje in de Acties van het Inzicht van de Verkoop adviseren wij altijd het integreren van dynamische gebieden, gebruikend **Dynamisch veld invoegen** knop.

Dit gereedschap wordt gebruikt om `auto-personalize your email` en bespaar u veel tijd met `pulling information from the People page`.

| Dynamisch veld | Voorbeeld van wat er in uw e-mail wordt weergegeven |
|---|---|
| `{{company}}` | Adobe |
| `{{company_friendly}}` | Adobe |
| `{{first_name}}` | Keith |
| `{{team_unsubscribe}}` | Klik hier als je geen e-mails meer van ons wilt ontvangen |
| `{{friendly_unsubscribe}}` | Heb je genoeg van alle e-mails? Laat het me even weten |
| `{{my_name}}` | Keith Flynn |
| `{{my_signature}}` | Keith Flynn, Senior Technical Writer - Adobe |
| `{{personal_email}}` | keith@pickyouremail.com |
| `{{title}}` | Senior Technical Writer |
| `{{work_website}}` | https://www.adobe.com |

**Notities**:

* Als de contactgegevens onjuist zijn ingevoerd of ontbreken op de pagina Personen, worden deze niet correct in de sjabloon ingevoerd.
* Het verschil tussen `{{company}}` en `{{company_friendly}}` is `{{company_friendly}}` zal om het even welke formele titel, zoals Inc., LLC., enz., van de naam van het bedrijf van uw contact verwijderen.
* Wanneer u `{{company_friendly}}`, moet u Inc. of Co. scheiden met een komma in de contactgegevens. Dit is hoe de Acties van het Inzicht van de Verkoop weten wat te verwijderen wanneer het trekken in de waarde.
* U kunt uw e-mailsjablonen aanpassen met vooraf gedefinieerde kenmerken, zoals `{{my_name}}` of `{{my_title}}`. Met deze velden kunt u snel naar uzelf verwijzen in uw e-mailsjablonen.
* Als u het `{{my_signature}}` dynamisch veld, voegt het systeem niet automatisch de handtekening van de gebruiker toe om duplicaten te voorkomen.

>[!TIP]
>
>Als de dynamische velden niet worden gevuld, schakelt u deze uit [dit artikel](/help/marketo/product-docs/marketo-sales-insight/actions/faq/why-arent-my-dynamic-fields-filling-out.md).
