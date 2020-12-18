---
unique-page-id: 14352509
description: Dynamische woordenlijst velden - Marketo Docs - Productdocumentatie
title: Woordenlijst Dynamische velden
translation-type: tm+mt
source-git-commit: 5c9683c6b00ccbf9e9d606fd4513432c9872ad00
workflow-type: tm+mt
source-wordcount: '173'
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
| `{{personal_email}}` | [[beveiligd via e-mail]](http://docs.marketo.com/cdn-cgi/l/email-protection) |
| `{{title}}` | Senior Technical Writer |
| `{{work_website}}` | https://www.marketo.com |

**Notities**:

* Als een contact `information is entered incorrectly` of van de pagina van Mensen mist, `will not pull over correctly` in uw malplaatje.

* Het verschil tussen `{{company}}` en `{{company_friendly}}` is dat `{{company_friendly}}` `remove any formal title`, zoals Inc., LLC., etc., van de naam van het bedrijf van uw contact zal.
* Wanneer het gebruiken van `{{company_friendly}}`, zorg ervoor u Inc. scheidt of met een komma in de contactdetails. Zo weet Sales Connect wat er moet worden verwijderd wanneer u de waarde opgeeft.

>[!TIP]
>
>U kunt uw eigen [aangepast dynamisch veld maken](http://docs.marketo.com/x/fADb) voor alles wat u automatisch in uw e-mails wilt opnemen

