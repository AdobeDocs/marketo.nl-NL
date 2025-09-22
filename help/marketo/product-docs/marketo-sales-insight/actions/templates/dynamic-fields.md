---
description: Dynamische velden - Marketo Docs - Productdocumentatie
title: Dynamische velden
exl-id: d9e52eae-d5bb-462f-8b7b-c28a560f6ea4
feature: Sales Insight Actions
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '525'
ht-degree: 0%

---

# Dynamische velden {#dynamic-fields}

U kunt uw e-mailsjablonen aanpassen met vooraf gedefinieerde kenmerken, zoals `{{first_name}}` of `{{company}}` . Met deze velden kunt u meerdere contactpersonen per e-mail verzenden en deze velden automatisch aanvullen zonder dat u ze voor elk contact afzonderlijk hoeft in te voeren.

>[!TIP]
>
>Het veld &quot;first_name&quot; en &quot;bedrijf&quot; zijn de enige velden die zowel naar [!DNL Sales Insight Actions] als naar [!DNL Salesforce] kijken. Dat betekent als een contact niet in de [ Webtoepassing ](https://toutapp.com/login) bestaat, kijken wij binnen [!DNL Salesforce] om te zien of kunnen wij een contact/loodverslag met een passend e-mailadres vinden. Vervolgens gebruiken we informatie uit die record om het veld te vullen.

## Een dynamisch veld invoegen in een sjabloon {#insert-a-dynamic-field-into-a-template}

1. Zoek in **[!UICONTROL Templates & Campaigns]** de sjabloon die u wilt bewerken en klik op **[!UICONTROL Edit Template]** .

1. Klik op **[!UICONTROL Insert Dynamic Field]**.

   >[!NOTE]
   >
   >Bij het e-mailen van contactpersonen in [!DNL Sales Insight Actions] kunt u de standaard dynamische velden gebruiken. Deze zullen zich direct uit het contact trekken.

Als u contactpersonen per e-mail verzendt die in [!DNL Salesforce] voorkomen, kunt u gebruikmaken van de dynamische velden van [!DNL Salesforce] . Deze beginnen allemaal met &quot;sfdc&quot;. Zolang u verbinding hebt met [!DNL Salesforce] , worden deze velden rechtstreeks aangeroepen bij de lead/contactpersoon in [!DNL Salesforce] om informatie in de sjabloon te vullen.

## Dynamische velden invoegen in een onderwerpregel {#insert-dynamic-fields-in-a-subject-line}

Kopieer en plak ze gewoon handmatig in het onderwerpveld van een e-mail, waarbij u ervoor zorgt dat u de juiste opmaak hebt.

## Standaardwaarden dynamisch veld {#dynamic-field-default-values}

Wanneer u dynamische velden toevoegt aan uw e-mailsjablonen, kunt u een standaardwaarde toevoegen die in het dynamische veld wordt gebruikt als er geen andere waarde beschikbaar is.

Hiervoor voegt u &quot;|&quot; toe na het dynamische veldlabel en voegt u &quot;default:&quot; (beide zonder aanhalingstekens) toe. Voeg vervolgens de waarde toe waarnaar het veld moet verwijzen (tussen aanhalingstekens) als er geen andere waarde kan worden gevonden.

**Voorbeeld:**

`{{first name | default: "loyal customer"}}`

`{{sfdc_contact_account_name | default: "your company"}}`

## Woordenlijst Dynamische velden {#dynamic-fields-glossary}

Wanneer u een sjabloon maakt in [!DNL Sales Insight Actions] , raden we u altijd aan dynamische velden te integreren met de knop **[!UICONTROL Insert Dynamic Field]** .

Met dit gereedschap kunt u `auto-personalize your email` gebruiken en tonnen tijd besparen op `pulling information from the People page` .

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
* Als u `{{company_friendly}}` gebruikt, moet u Inc. of Co. scheiden met een komma in de contactgegevens. Zo weet [!DNL Sales Insight Actions] wat te verwijderen wanneer het trekken van in de waarde.
* U kunt uw e-mailsjablonen aanpassen met vooraf gedefinieerde kenmerken, zoals `{{my_name}}` of `{{my_title}}` . Met deze velden kunt u snel naar uzelf verwijzen in uw e-mailsjablonen.
* Het systeem voegt automatisch de handtekening van de gebruiker toe aan elke verzonden e-mail. Als de gebruiker een sjabloon gebruikt met het dynamische veld `{{my_signature}}` , vult het systeem de handtekening waar het dynamische veld `{{my_signature}}` is geplaatst. Het is daar alleen toegevoegd om dubbel werk te voorkomen. Het systeem verwerkt `{{team_unsubscribe}}` op dezelfde manier als wanneer de instelling Globaal abonnement voor toevoegen is ingeschakeld.

>[!TIP]
>
>Als uw dynamische gebieden niet bevolkt, controleer [ dit artikel ](/help/marketo/product-docs/marketo-sales-insight/actions/faq/why-arent-my-dynamic-fields-filling-out.md).
