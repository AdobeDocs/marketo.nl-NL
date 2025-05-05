---
description: Waarom vullen mijn dynamische velden niet uit? - Marketo Docs - Productdocumentatie
title: Waarom vullen mijn dynamische velden niet uit?
exl-id: 4e1d133f-8314-4e64-b50b-f3e824c3bef4
feature: Sales Insight Actions
source-git-commit: 02b2e39580c5eac63de4b4b7fdaf2a835fdd4ba5
workflow-type: tm+mt
source-wordcount: '294'
ht-degree: 0%

---

# Waarom vullen mijn dynamische velden niet uit? {#why-arent-my-dynamic-fields-filling-out}

Dynamische velden werken alleen wanneer u een sjabloon gebruikt. Individuele eenmalige e-mails die u schrijft, vullen deze niet in.

## Wat moet u controleren? {#what-to-check}

Er zijn drie soorten dynamische gebieden in de Acties van het Inzicht van de Verkoop: Standaard, Aangepast en Salesforce. Zowel standaard als Aangepast, zoeken informatie van de [webtoepassing](https://toutapp.com/login){target="_blank"}. If the information does not exist in the web application, the fields will be blank. Salesforce fields pull information from [Salesforce.com](https://salesforce.com){target="_blank"}.

**Problemen met Salesforce-velden oplossen**

Salesforce-velden: bijv. `{{sfdc_account_name}}`

* Zorg ervoor het behoorlijk met de Acties van het Inzicht van de Verkoop wordt verbonden. Ga naar de [Instellingen] (https://toutapp.com/login{target="_blank"} pagina en klik op **Beheren** naast uw CRM.

**Problemen met basisvelden en aangepaste velden oplossen**

Basisvelden van Marketo Sales Insight-acties: bijv. `{{company}}`

Marketo Sales Insight Actions Custom Fields: bijv. `{{custom_field_favorite_movie}}`

* Het corresponderende veld moet worden opgeslagen voor uw contactpersoon in het dialoogvenster [Personen, pagina](https://toutapp.com/next#relationships){target="_blank"} voor ons dynamische veld. Als u bijvoorbeeld een e-mail naar Mary stuurt en de `{{company}}` veld, maar haar contactrecord vermeldt geen bedrijf, dat kunnen we niet invullen.

## Waarom is mijn e-mail verzonden zonder alle dynamische velden te vullen? {#why-did-my-email-send-without-populating-all-dynamic-fields}

Met Handelingen in het venster Verkoopoverzicht worden e-mails niet verzonden als niet alle dynamische velden in de e-mail kunnen worden ingevuld. **Niettemin** Er zijn echter enkele uitzonderingen op deze regel. Sommige velden worden leeg verzonden of vullen automatisch een waarde in als we er een kunnen vinden. Deze velden en de manier waarop ze reageren als ze het veld niet kunnen vullen, worden hieronder weergegeven.

`{{first_name}}` = BLANK

`{{last_name}}` =BLANK

`{{title}}` = BLANK

`{{company}}` = &quot;uw bedrijf&quot;

`{{friendly_company}}` = &quot;uw bedrijf&quot;

>[!NOTE]
>
>De `{{first_name}}` in zowel Handelingen van het Inzicht van de Verkoop als Salesforce kijken om te proberen om informatie te trekken. Alle andere gebieden in deze lijst kijken slechts in de Acties van het Inzicht van de Verkoop om het gebied te bevolken.
