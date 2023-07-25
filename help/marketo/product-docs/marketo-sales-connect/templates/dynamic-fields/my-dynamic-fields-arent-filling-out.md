---
unique-page-id: 14352602
description: Mijn dynamische velden zijn niet vol - Marketo Docs - Productdocumentatie
title: Mijn dynamische velden worden niet ingevuld
exl-id: fb3e8b56-506a-41f8-a84f-41370381c058
feature: Marketo Sales Connect
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '301'
ht-degree: 0%

---

# Mijn dynamische velden worden niet ingevuld {#my-dynamic-fields-arent-filling-out}

Dynamische velden werken alleen wanneer u een sjabloon gebruikt. Individuele eenmalige e-mails die u schrijft, vullen deze niet in.

## Wat moet u controleren? {#what-to-check}

Er zijn drie typen dynamische velden in Sales Connect: Standaard, Aangepast en Salesforce. Zowel standaard als Aangepast, zoeken informatie van de [webtoepassing](https://toutapp.com/login). Als de informatie niet bestaat in de webtoepassing, zijn de velden leeg. Salesforce-velden ophalen informatie van [Salesforce.com](https://salesforce.com).

**Problemen met Salesforce-velden oplossen**

Salesforce-velden: bijv. `{{sfdc_account_name}}`

* Controleer of het bestand correct is gekoppeld aan Sales Connect. Ga naar de [Instellingen](https://toutapp.com/login) pagina en klik op **Beheren** naast uw CRM.

**Problemen met basisvelden en aangepaste velden oplossen**

Basisvelden voor tinten: bijv. `{{company}}`

Aangepaste Tout-velden: bijv. `{{custom_field_favorite_movie}}`

* Het corresponderende veld moet worden opgeslagen voor uw contactpersoon in het dialoogvenster [Personen, pagina](https://toutapp.com/next#relationships) voor ons dynamische veld. Als u bijvoorbeeld een e-mail naar Mary stuurt en de `{{company}}` veld, maar haar contactrecord vermeldt geen bedrijf, dat kunnen we niet invullen.

## Waarom is mijn e-mail verzonden zonder alle dynamische velden te vullen? {#why-did-my-email-send-without-populating-all-dynamic-fields}

Sales Connect voorkomt dat uw e-mailberichten worden verzonden als niet al uw dynamische velden in de e-mail kunnen worden ingevuld. **Niettemin** Er zijn echter enkele uitzonderingen op deze regel. Sommige velden worden leeg verzonden of vullen automatisch een waarde in als we er een kunnen vinden. Deze velden en de manier waarop ze reageren als ze het veld niet kunnen vullen, worden hieronder weergegeven.

`{{first_name}}` = BLANK

`{{last_name}}` =BLANK

`{{title}}` = BLANK

`{{company}}` = &quot;uw bedrijf&quot;

`{{friendly_company}}` = &quot;uw bedrijf&quot;

>[!NOTE]
>
>De `{{first_name}}` in zowel Sales Connect als Salesforce wordt gezocht naar informatie. Alle andere velden in deze lijst worden alleen weergegeven in Sales Connect om het veld te vullen.
