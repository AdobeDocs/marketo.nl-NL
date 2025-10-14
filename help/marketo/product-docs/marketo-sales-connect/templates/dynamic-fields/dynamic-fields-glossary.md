---
unique-page-id: 14352509
description: Dynamische woordenlijst velden - Marketo Docs - Productdocumentatie
title: Woordenlijst Dynamische velden
exl-id: 28351ba9-53da-4408-9526-918200d9bd29
feature: Marketo Sales Connect
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '240'
ht-degree: 0%

---

# Woordenlijst Dynamische velden {#dynamic-fields-glossary}

Wanneer u een sjabloon maakt in [!DNL Sales Connect] , raden we u altijd aan dynamische velden te integreren met de knop **[!UICONTROL MSE Dynamic Fields]** .

Met dit gereedschap kunt u `auto-personalize your email` gebruiken en tonnen tijd besparen op `pulling information from the [!UICONTROL People] page` .

| Dynamisch veld | Voorbeeld van wat er in uw e-mail wordt weergegeven |
|---|---|
| `{{company}}` | Adobe |
| `{{company_friendly}}` | Adobe |
| `{{first_name}}` | Keith |
| `{{team_unsubscribe}}` | Klik hier als je geen e-mails meer van ons wilt ontvangen |
| `{{friendly_unsubscribe}}` | Heb je genoeg van alle e-mails? Laat het me even weten |
| `{{my_name}}` | Keith Flynn |
| `{{my_signature}}` | Keith Flynn, Senior Technical Writer - Adobe |
| `{{personal_email}}` | <keith@pickyouremail.com> |
| `{{title}}` | Senior Technical Writer |
| `{{work_website}}` | <https://www.adobe.com> |

**Dingen aan nota te nemen**:

* Als de contactgegevens onjuist zijn ingevoerd of ontbreken op de pagina Personen, worden deze niet correct in de sjabloon ingevoerd.
* Het verschil tussen `{{company}}` en `{{company_friendly}}` is dat `{{company_friendly}}` alle formele titels, zoals Inc., LLC., enz., verwijdert uit de naam van het bedrijf van uw contactpersoon.
* Als u `{{company_friendly}}` gebruikt, moet u Inc. of Co. scheiden met een komma in de contactgegevens. Zo weet Sales Connect wat er moet worden verwijderd wanneer u de waarde opgeeft.
* Het systeem voegt automatisch de handtekening van de gebruiker toe aan elke verzonden e-mail. Als de gebruiker een sjabloon gebruikt met het dynamische veld `{{my_signature}}` , vult het systeem de handtekening waar het dynamische veld `{{my_signature}}` is geplaatst. Het is daar alleen toegevoegd om dubbel werk te voorkomen. Het systeem verwerkt `{{team_unsubscribe}}` op dezelfde manier als wanneer de instelling Globaal abonnement voor toevoegen is ingeschakeld.

>[!TIP]
>
>U kunt uw eigen [&#x200B; douane dynamisch gebied &#x200B;](/help/marketo/product-docs/marketo-sales-connect/templates/dynamic-fields/create-custom-dynamic-fields.md) voor om het even wat tot stand brengen u in uw e-mails automatisch zou willen hebben getrokken
