---
unique-page-id: 14352602
description: Mijn dynamische velden zijn niet vol - Marketo Docs - Productdocumentatie
title: Mijn dynamische velden worden niet ingevuld
translation-type: tm+mt
source-git-commit: 6ae882dddda220f7067babbe5a057eec82601abf
workflow-type: tm+mt
source-wordcount: '301'
ht-degree: 0%

---


# Mijn dynamische velden vullen niet {#my-dynamic-fields-arent-filling-out}

Dynamische velden werken alleen wanneer u een sjabloon gebruikt. Individuele eenmalige e-mails die u schrijft, vullen deze niet in.

## Wat moet u controleren {#what-to-check}

Er zijn drie typen dynamische velden in Sales Connect: Standaard, Aangepast en Salesforce. Zowel Standaard als Aangepast zoeken om informatie van [Webtoepassing](https://toutapp.com/login) te trekken. Als de informatie niet bestaat in de webtoepassing, zijn de velden leeg. Salesforce-velden ophalen informatie van [Salesforce.com](https://salesforce.com).

**Problemen met Salesforce-velden oplossen**

Salesforce-velden: bijv. `{{sfdc_account_name}}`

* Controleer of het bestand goed is gekoppeld aan Sales Connect. Ga naar [Settings](https://toutapp.com/login) pagina en klik **Manage** naast uw CRM.

**Problemen met basisvelden en aangepaste velden oplossen**

Basisvelden voor tinten: bijv. `{{company}}`

Aangepaste Tout-velden: bijv. `{{custom_field_favorite_movie}}`

* Het overeenkomstige gebied moet voor uw contact in [pagina van Mensen ](https://toutapp.com/next#relationships) voor ons dynamische gebied worden bewaard om te verwijzen. Bijvoorbeeld, als u een e-mail naar Mary verzendt en het `{{company}}` gebied gebruikt, maar haar contactverslag maakt geen lijst van een bedrijf, zullen wij niet dat kunnen invullen.

## Waarom is mijn e-mail verzonden zonder alle dynamische velden te vullen? {#why-did-my-email-send-without-populating-all-dynamic-fields}

Sales Connect voorkomt dat uw e-mailberichten worden verzonden als niet al uw dynamische velden in de e-mail kunnen worden ingevuld. **Er zijn echter** enkele uitzonderingen op deze regel. Sommige velden worden leeg verzonden of vullen automatisch een waarde in als we er een kunnen vinden. Deze velden en de manier waarop ze reageren als ze het veld niet kunnen vullen, worden hieronder weergegeven.

`{{first_name}}` = BLANK

`{{last_name}}` =BLANK

`{{title}}` = BLANK

`{{company}}` = &quot;uw bedrijf&quot;

`{{friendly_company}}` = &quot;uw bedrijf&quot;

>[!NOTE]
>
>In het veld `{{first_name}}` wordt zowel in Sales Connect als in Salesforce gezocht naar informatie. Alle andere velden in deze lijst worden alleen weergegeven in Sales Connect om het veld te vullen.
