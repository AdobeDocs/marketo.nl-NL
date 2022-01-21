---
unique-page-id: 42762322
description: Marketo Sales Insight Configuration Tab in Salesforce - Marketo Docs - Product Documentation
title: Marketo Sales Insight Configuration Tab in Salesforce
exl-id: 4e2abd48-b0a5-4b71-939b-e66c7e39bb6c
source-git-commit: 15263f9c23c958499aaa2e4e6491b4962c617358
workflow-type: tm+mt
source-wordcount: '585'
ht-degree: 0%

---

# Marketo Sales Insight Configuration Tab in Salesforce {#marketo-sales-insight-configuration-tab-in-salesforce}

## Operationele instellingen {#operational-settings}

U moet deze instelling hebben om Verkoopinzicht te kunnen gebruiken in SFDC.

![](assets/marketo-sales-insight-configuration-tab-in-salesforce-1.png)

* MSI gebruikt zowel Soap- als Rest-API
* De pagina Sales Insight in uw Marketo-account heeft twee corresponderende deelvensters met Soap- en Rest API-referenties die u hier kunt kopiëren en plakken
* De Soap and Rest API beschikt over afzonderlijke time-outs die u kunt instellen op basis van de behoeften van uw organisatie. De maximaal toegestane tijd is 120 seconden
* Disabling Insights Dashboard: You can remove Rest API credentials and only use Soap API. Als u dit doet, wordt het tabblad Inhoudsdashboard in al uw MSI-deelvensters voor visualkracht uitgeschakeld

## MSI Configuration {#msi-configuration}

Configuraties zijn van toepassing op alle MSI-gebruikers en zijn niet specifiek voor profielen.

**Pagina-instellingen visualiseren**

* Vervolgkeuzelijst Handeling inschakelen:
   * Ability to hide Send Marketo email from drop-down in Lead and Contact MSI Layout
   * Mogelijkheid om de opties voor Toevoegen aan Marketo-campagne te verbergen in de vervolgkeuzelijst Lood en Contact opnemen met MSI-indeling
* Komende gebeurtenissen: Mogelijkheid om uitgenodigde gebeurtenissen, alle gebeurtenissen aan gebruikers te tonen of dit tabblad volledig te verbergen
* Upcoming campaigns: Ability to show all email campaigns or completely hide this tab
* Laad volgende campagnes en gebeurtenissen: Capaciteit om het aantal vraag van de Rest API te verminderen die door gebruikers wordt gemaakt door gebeurtenissen en campagnes lusje achter een op bestelling &quot;Laad Opkomende Punten&quot;knoop te plaatsen
* Tabinstellingen: Alle vijf tabbladen zijn standaard beschikbaar. U kunt de tabvolgorde kiezen in het deelvenster Verkoopcontrole. Dezelfde volgorde geldt voor alle indelingen (Lead, Contact, Account, Opportunity)

![](assets/marketo-sales-insight-configuration-tab-in-salesforce-2.png)

**Marketo Global Tab**

* RSS-feed ingeschakeld: Als deze optie is ingeschakeld, kunnen MSI-gebruikers hun voer voor leads bekijken in een RSS-feed (in aanvulling op het voer voor leads in Salesforce). De RSS-feed kan alleen functioneren als de functie &quot;Symbolische vervaldatum&quot; is uitgeschakeld. This setting is controlled in your Marketo Sales Insight Admin page.
* Modus Foutopsporing voor beste Bets
* Standaard verbergen: De optie die u hier kiest, is het aantal dagen dat een beste weddenschap wordt verborgen op het tabblad Best Bets in Marketo wanneer u op het pictogram Verbergen klikt
* Contact Status Field: The option you choose here will be the value that’s populated in the Status Header column in the Best Bets tab in Marketo
* Live Feed Settings: The option to choose to show only Live Feed (in Lead, Contact, Account, and Opportunity panels, and the Global Marketo page), only Lead Feed (in the Marketo Global Page) or both Live and Lead Feed
* Tabinstellingen: Alle vijf tabbladen zijn standaard beschikbaar. U kunt de tabvolgorde op de algemene Marketo-pagina kiezen

![](assets/marketo-sales-insight-configuration-tab-in-salesforce-3.png)

**Limieten**

* Activity (Interesting Moment, Web Activity, Email) is set to 1000 by default. E-mailcampagnes en gebeurtenissen worden standaard ingesteld op 200
* In case you notice time out issues on your org, you can reduce the limit

**Instellingen voor handeling**

* Send Marketo Email: Enabling this will give all Sales Insight users access to send emails from the Lead, Contact, Account, Opportunity panels and the Best Bets tab (bulk actions and inline engagement)
* Toevoegen aan Marketo-campagne: Als u dit inschakelt, krijgen alle gebruikers van het Sales Insight toegang tot campagnes via de deelvensters Lead, Contact, Account, Opportunity en Best Bets (bulkacties en inline-betrokkenheid)

![](assets/marketo-sales-insight-configuration-tab-in-salesforce-4.png)

## Marketo Sales Insight opnieuw instellen {#reset-marketo-sales-insight}

Als u dit doet, worden al uw configuraties in SFDC gewist en kunnen deze niet worden hersteld. U zult alles opnieuw moeten vormen.

![](assets/marketo-sales-insight-configuration-tab-in-salesforce-5.png)

>[!MORELIKETHIS]
>
>[Setting up Sales Insight for your Team](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/setting-up-sales-insight-for-your-team.md)
