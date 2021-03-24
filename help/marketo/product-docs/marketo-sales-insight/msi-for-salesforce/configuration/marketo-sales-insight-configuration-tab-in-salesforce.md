---
unique-page-id: 42762322
description: Het Lusje van de Configuratie van het Inzicht van de Verkoop van de Marketo in Salesforce - Marketo Docs - de Documentatie van het Product
title: Het lusje van de Configuratie van het Inzicht van de Verkoop van de Marketo in Salesforce
translation-type: tm+mt
source-git-commit: ed9399396c82a3b2fb93c83ffdaa1dc7b0827306
workflow-type: tm+mt
source-wordcount: '434'
ht-degree: 0%

---


# Het lusje van de Configuratie van het Toezicht van het Inzicht van de Verkoop van de Marketo in Salesforce {#marketo-sales-insight-configuration-tab-in-salesforce}

## Operationele instellingen {#operational-settings}

U moet deze instelling hebben om Verkoopinzicht te kunnen gebruiken in SFDC.

![](assets/one.png)

* MSI gebruikt zowel Soap- als Rest-API
* De pagina Verkoopinzicht in uw Marketo-account heeft twee corresponderende deelvensters met Soap- en Rest API-referenties die u hier kunt kopiëren en plakken
* De Soap and Rest API beschikt over afzonderlijke time-outs die u kunt instellen op basis van de behoeften van uw organisatie. De maximaal toegestane tijd is 120 seconden
* Het dashboard Inzichten uitschakelen: U kunt de referenties van de rest-API verwijderen en alleen de Soap API gebruiken. Als u dit doet, wordt het tabblad Inhoudsdashboard in al uw MSI-deelvensters voor visualkracht uitgeschakeld

## MSI-configuratie {#msi-configuration}

Configuraties zijn van toepassing op alle MSI-gebruikers en zijn niet specifiek voor profielen.

**Instellingen voor Tab markeren**

* Modus Foutopsporing voor beste Bets
* Standaard verbergen - De optie die u hier kiest, is het aantal dagen dat een beste weddenschap wordt verborgen op het tabblad Best Bets in Marketo wanneer u op het pictogram Verbergen klikt
* Veld contactstatus - de optie die u hier kiest, is de waarde die is ingevuld in de kolom Status-koptekst op het tabblad Beste ophalen in Marketo
* Tabinstellingen - Alle vijf tabbladen zijn standaard beschikbaar. U kunt de tabvolgorde kiezen op de algemene pagina Marketo

**Pagina-instellingen visualiseren**

* Vervolgkeuzelijst Handeling inschakelen:

   * Mogelijkheid om Verzendmarkeerteken te verbergen in vervolgkeuzelijst voor lead en contact met MSI-layout
   * Mogelijkheid om de opties Toevoegen aan Marketo-campagne te verbergen in de vervolgkeuzelijst Lood en contact met MSI-layout

* Komende gebeurtenissen: Mogelijkheid om uitgenodigde gebeurtenissen, alle gebeurtenissen aan gebruikers te tonen of dit tabblad volledig te verbergen
* Opkomende campagnes: Mogelijkheid om alle e-mailcampagnes weer te geven of dit tabblad volledig te verbergen
* Laad volgende campagnes en gebeurtenissen: Capaciteit om het aantal vraag van de Rest API te verminderen die door gebruikers wordt gemaakt door gebeurtenissen en campagnes lusje achter een op bestelling &quot;Laad Opkomende Punten&quot;knoop te plaatsen
* Tabinstellingen - Alle vijf tabbladen zijn standaard beschikbaar. Alle vijf tabbladen zijn standaard beschikbaar. U kunt de tabvolgorde kiezen in het deelvenster Verkoopcontrole. Dezelfde volgorde geldt voor alle lay-outs (lead, contact, account, opportunity)

![](assets/two.png)

**Limieten**

* De activiteit (Interessant Moment, de Activiteit van het Web, E-mail) wordt geplaatst aan 1000 door gebrek. E-mailcampagnes en gebeurtenissen worden standaard ingesteld op 200
* Voor het geval u time-out problemen op uw org opmerkt, kunt u de limiet verlagen

## Marktverkoop opnieuw instellen {#reset-marketo-sales-insight}

Als u dit doet, worden al uw configuraties in SFDC gewist en kunnen deze niet worden hersteld. U zult alles opnieuw moeten vormen.

![](assets/three.png)

>[!MORELIKETHIS]
>
>[Het Inzicht van de Verkoop van de Opstelling voor uw Team](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/setting-up-sales-insight-for-your-team.md)
