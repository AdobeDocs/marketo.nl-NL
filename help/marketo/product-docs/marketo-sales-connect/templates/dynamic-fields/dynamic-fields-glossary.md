---
unique-page-id: 14352509
description: Dynamische woordenlijst velden - Marketo Docs - Productdocumentatie
title: Woordenlijst Dynamische velden
exl-id: 28351ba9-53da-4408-9526-918200d9bd29
feature: Marketo Sales Connect
source-git-commit: d6a3d95ed42d1c08d69014e1aa013e7436bd06c2
workflow-type: tm+mt
source-wordcount: '176'
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
| `{{friendly_unsubscribe}}` | Als je niet meer van mij wilt horen, laat het me hier weten |
| `{{my_name}}` | Keith Flynn |
| `{{personal_email}}` | keith@pickyouremail.com |
| `{{title}}` | Senior Technical Writer |
| `{{work_website}}` | https://www.adobe.com |

**Notities**:

* Als de contactgegevens onjuist zijn ingevoerd of ontbreken op de pagina Personen, worden deze niet correct in de sjabloon ingevoerd.
* Het verschil tussen `{{company}}` en `{{company_friendly}}` is `{{company_friendly}}` zal om het even welke formele titel, zoals Inc., LLC., enz., van de naam van het bedrijf van uw contact verwijderen.
* Wanneer u `{{company_friendly}}`, moet u Inc. of Co. scheiden met een komma in de contactgegevens. Zo weet Sales Connect wat er moet worden verwijderd wanneer u de waarde opgeeft.

>[!TIP]
>
>U kunt uw eigen [aangepast dynamisch veld](/help/marketo/product-docs/marketo-sales-connect/templates/dynamic-fields/create-custom-dynamic-fields.md) voor alles wat je automatisch in je e-mails had willen opnemen
