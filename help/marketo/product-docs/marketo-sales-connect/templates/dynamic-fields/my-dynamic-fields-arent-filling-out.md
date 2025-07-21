---
unique-page-id: 14352602
description: Mijn dynamische velden zijn niet vol - Marketo Docs - Productdocumentatie
title: Mijn dynamische velden worden niet ingevuld
exl-id: fb3e8b56-506a-41f8-a84f-41370381c058
feature: Marketo Sales Connect
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '277'
ht-degree: 0%

---

# Mijn dynamische velden worden niet ingevuld {#my-dynamic-fields-arent-filling-out}

Dynamische velden werken alleen wanneer u een sjabloon gebruikt. Individuele eenmalige e-mails die u schrijft, vullen deze niet in.

## Wat moet u controleren {#what-to-check}

[!DNL Sales Connect] bevat drie typen dynamische velden: Standaard, Aangepast en [!DNL Salesforce] . De basis en van de Douane allebei kijken om informatie van de [ Webtoepassing ](https://toutapp.com/login) te trekken. Als de informatie niet bestaat in de webtoepassing, zijn de velden leeg. [!DNL Salesforce] gebieden trekken informatie van [ Salesforce.com ](https://salesforce.com).

**het Oplossen van problemen [!DNL Salesforce] Gebieden**

[!DNL Salesforce] Velden: bijvoorbeeld `{{sfdc_account_name}}`

* Zorg ervoor dat deze correct is gekoppeld aan [!DNL Sales Connect] . Ga naar de [ pagina van Montages ](https://toutapp.com/login) en klik **[!UICONTROL Manage]** naast uw CRM.

**Basis van het oplossen van problemen en de Gebieden van de Douane**

Basisvelden voor tinten: bijv. `{{company}}`

Aangepaste Tout-velden: bijv. `{{custom_field_favorite_movie}}`

* Het overeenkomstige gebied moet voor uw contact in de [ pagina van Mensen ](https://toutapp.com/next#relationships) voor ons dynamische gebied worden bewaard om te verwijzen. Bijvoorbeeld, als u een e-mail naar Mary en gebruikend het `{{company}}` gebied verzendt, maar haar contactverslag maakt geen lijst van een bedrijf, zullen wij niet dat kunnen invullen.

## Waarom is mijn e-mail verzonden zonder alle dynamische velden te vullen? {#why-did-my-email-send-without-populating-all-dynamic-fields}

[!DNL Sales Connect] voorkomt dat e-mailberichten worden verzonden als niet alle dynamische velden in de e-mail kunnen worden ingevuld. **Nochtans**, zijn er een paar uitzonderingen op deze regel. Sommige velden worden leeg verzonden of vullen automatisch een waarde in als we er een kunnen vinden. Deze velden en de manier waarop ze reageren als ze het veld niet kunnen vullen, worden hieronder weergegeven.

`{{first_name}}` = LEEG

`{{last_name}}` =BLANK

`{{title}}` = LEEG

`{{company}}` = &quot;uw bedrijf&quot;

`{{friendly_company}}` = &quot;uw bedrijf&quot;

>[!NOTE]
>
>Het veld `{{first_name}}` zoekt zowel in [!DNL Sales Connect] als in [!DNL Salesforce] naar informatie. Alle andere velden in deze lijst zoeken alleen in [!DNL Sales Connect] om het veld te vullen.
