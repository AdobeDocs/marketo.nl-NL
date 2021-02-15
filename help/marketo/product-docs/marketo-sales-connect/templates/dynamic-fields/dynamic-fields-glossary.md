---
unique-page-id: 14352509
description: Dynamische woordenlijst velden - Marketo Docs - Productdocumentatie
title: Woordenlijst Dynamische velden
translation-type: tm+mt
source-git-commit: 6ae882dddda220f7067babbe5a057eec82601abf
workflow-type: tm+mt
source-wordcount: '176'
ht-degree: 0%

---


# Woordenlijst voor dynamische velden {#dynamic-fields-glossary}

Wanneer het creëren van een malplaatje in Verkoop verbindt, adviseren wij altijd het integreren van dynamische gebieden, gebruikend **MSE Dynamische Gebieden** knoop.

Dit hulpmiddel wordt gebruikt aan `auto-personalize your email` en sparen u tonnen tijd door `pulling information from the People page`.

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
* Het verschil tussen `{{company}}` en `{{company_friendly}}` is dat `{{company_friendly}}` om het even welke formele titel, zoals Inc., LLC., enz., uit de naam van het bedrijf van uw contact zal verwijderen.
* Wanneer het gebruiken van `{{company_friendly}}`, zorg ervoor u Inc. scheidt of met een komma in de contactdetails. Zo weet Sales Connect wat er moet worden verwijderd wanneer u de waarde opgeeft.

>[!TIP]
>
>U kunt uw eigen [aangepast dynamisch veld maken](/help/marketo/product-docs/marketo-sales-connect/templates/dynamic-fields/create-custom-dynamic-fields.md) voor alles wat u automatisch in uw e-mails wilt opnemen
