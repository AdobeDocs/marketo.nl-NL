---
description: Waarom vullen mijn dynamische velden niet uit? - Marketo Docs - Productdocumentatie
title: Waarom vullen mijn dynamische velden niet uit?
exl-id: 4e1d133f-8314-4e64-b50b-f3e824c3bef4
feature: Sales Insight Actions
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '294'
ht-degree: 0%

---

# Waarom vullen mijn dynamische velden niet uit? {#why-arent-my-dynamic-fields-filling-out}

Dynamische velden werken alleen wanneer u een sjabloon gebruikt. Individuele eenmalige e-mails die u schrijft, vullen deze niet in.

## Wat moet u controleren {#what-to-check}

Er zijn drie soorten dynamische gebieden in de Acties van Insight van de Verkoop: Basis, Douane, en Salesforce. De basis en van de Douane allebei kijken om informatie van de [&#x200B; Webtoepassing &#x200B;](https://toutapp.com/login){target="_blank"} te trekken. Als de informatie niet bestaat in de webtoepassing, zijn de velden leeg. De gebieden van Salesforce trekken informatie van [&#x200B; Salesforce.com &#x200B;](https://salesforce.com){target="_blank"}.

**het Oplossen van problemen [!DNL Salesforce] Gebieden**

[!DNL Salesforce] Velden: bijvoorbeeld `{{sfdc_account_name}}`

* Zorg ervoor dat deze correct is gekoppeld aan Sales Insight Acties. Ga naar [ Montages ] (<https://toutapp.com/login{target="_blank"}> pagina en klik **leiden** naast uw CRM.

**Basis van het oplossen van problemen en de Gebieden van de Douane**

Marketo Sales Insight Actions Basic Fields: bijv., `{{company}}`

Marketo Sales Insight Actions Custom Fields: bijv., `{{custom_field_favorite_movie}}`

* Het overeenkomstige gebied moet voor uw contact in de [&#x200B; pagina van Mensen &#x200B;](https://toutapp.com/next#relationships){target="_blank"} voor ons dynamische gebied worden bewaard om te verwijzen. Bijvoorbeeld, als u een e-mail naar Mary en gebruikend het `{{company}}` gebied verzendt, maar haar contactverslag maakt geen lijst van een bedrijf, zullen wij niet dat kunnen invullen.

## Waarom is mijn e-mail verzonden zonder alle dynamische velden te vullen? {#why-did-my-email-send-without-populating-all-dynamic-fields}

[!DNL Sales Insight Actions] voorkomt dat e-mailberichten worden verzonden als niet alle dynamische velden in de e-mail kunnen worden ingevuld. **Nochtans**, zijn er een paar uitzonderingen op deze regel. Sommige velden worden leeg verzonden of vullen automatisch een waarde in als we er een kunnen vinden. Deze velden en de manier waarop ze reageren als ze het veld niet kunnen vullen, worden hieronder weergegeven.

`{{first_name}}` = LEEG

`{{last_name}}` =BLANK

`{{title}}` = LEEG

`{{company}}` = &quot;uw bedrijf&quot;

`{{friendly_company}}` = &quot;uw bedrijf&quot;

>[!NOTE]
>
>Het veld `{{first_name}}` zoekt zowel in [!DNL Sales Insight Actions] als in [!DNL Salesforce] naar informatie. Alle andere velden in deze lijst zoeken alleen in [!DNL Sales Insight Actions] om het veld te vullen.
