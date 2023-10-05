---
unique-page-id: 14352509
description: Dynamische woordenlijst velden - Marketo Docs - Productdocumentatie
title: Woordenlijst Dynamische velden
exl-id: 28351ba9-53da-4408-9526-918200d9bd29
feature: Marketo Sales Connect
source-git-commit: 7c8703059d7d28afbf57f4f285ac972fb9d8fbef
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# Woordenlijst Dynamische velden {#dynamic-fields-glossary}

Wanneer we een sjabloon maken in Sales Connect, raden we altijd aan dynamische velden te integreren met de opdracht **Dynamische velden MSE** knop.

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
* Wanneer u `{{company_friendly}}`, moet u Inc. of Co. scheiden met een komma in de contactgegevens. Zo weet Sales Connect wat er moet worden verwijderd wanneer u de waarde opgeeft.
* Als u het `{{my_signature}}` dynamisch veld, voegt het systeem niet automatisch de handtekening van de gebruiker toe om duplicaten te voorkomen.

>[!TIP]
>
>U kunt uw eigen [aangepast dynamisch veld](/help/marketo/product-docs/marketo-sales-connect/templates/dynamic-fields/create-custom-dynamic-fields.md) voor alles wat je automatisch in je e-mails had willen opnemen
