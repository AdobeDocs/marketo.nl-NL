---
unique-page-id: 45416698
description: Opmerkingen bij de release - juli 2010 - Marketo Docs - Productdocumentatie
title: Opmerkingen bij de release - juli '20
exl-id: 3c9b1f1d-961c-4bf8-8b99-37b483230506
feature: Release Information
source-git-commit: ecd225af3ecfd7cb9159faf5a9d384d47ee6312c
workflow-type: tm+mt
source-wordcount: '629'
ht-degree: 0%

---

# Opmerkingen bij de release: juli &#39;20 {#release-notes-july}

De volgende functies zijn opgenomen in de release van juli 2010. Raadpleeg de Marketo-editie voor informatie over de beschikbaarheid van functies.

>[!AVAILABILITY]
>
>Houd er rekening mee dat, afhankelijk van het huidige pakket, items met een ster ( ![ (ster) ](assets/yellow-star.png) ) mogelijk een toegevoegde waarde moeten aanschaffen. Neem contact op met je Marketo Engage-vertegenwoordiger voor meer informatie.

**_Kwartaalversies_** De volgende eigenschappen zullen op **31 Juli, 2020** worden vrijgegeven.

## Beheer {#administration}

* **[&quot;Gebruikt door&quot;Uitvoer in het Beheer van het Gebied](/help/marketo/product-docs/administration/field-management/export-used-by-data-for-a-field.md)**: De beheerders kunnen alle &quot;Gebruikt door&quot;activa nu uitvoeren verbindingen voor een geselecteerd gebied in een Csv- dossier. Deze verbetering kan zowel beheerders als niet-beheerders helpen ongebruikte velden op te ruimen. Bovendien kunnen elementen nu worden geopend in een nieuw browsertabblad of venster.

## Account-Based Marketing {#account-based-marketing}

![ (star) ](assets/yellow-star.png)

* **bijgewerkte UI voor het Profileren van de Rekening**: vereenvoudig de verwezenlijking van uw lijst van de doelrekening in het Profileren van de Rekening met gestroomlijnde stappen allen in één enkel scherm.

<br> 

**_vrijstellend door het Kwartaal_**

De volgende functies bevinden zich op een niet-driemaandelijkse cyclus en worden de komende maanden vrijgegeven.

* **Dienst van Forms**: Wij introduceren sterkere bevestiging van de de syntaxis van het vormgebied en de capaciteit om gemeenschappelijke bot patronen met nieuwe Beveiligde Domeinen voor het Bestaan van Pagina&#39;s mogelijkheden te blokkeren. Door het blokkeren van botpatronen kunt u de verzending van spamformulieren verminderen en de databasekwaliteit verbeteren.

>[!NOTE]
>
>De volledige implementatie van de uitgebreide validatie van de formulierveldsyntaxis is uitgesteld tot na onze release van januari 2021.

* **Verhoogde Limiet van de Grootte van activa API URI**: De eenvormige grens van de middelherkenningsteken (URI) wordt verhoogd van 8KB aan 65KB voorafgaand aan de verwijdering van &quot;_method&quot;parameter. Bij het uitvoeren van lange vraagkoorden, zal deze groottebeperking de gegevens toestaan om gemakkelijker over te gaan. De verwijdering van de parameter &quot;_method&quot; maakt deel uit van een aanstaande veiligheidsverbetering.

## [!DNL Sales Insight] {#sales-insight}

![ (star) ](assets/yellow-star.png)

* **[[!DNL Sales Insight] Toegelaten voor Klanten met de Integratie van niet-inheemse  [!DNL Salesforce]  CRM ](/help/marketo/product-docs/marketo-sales-insight/sales-insight-for-non-native-salesforce-integrations.md) (Beta)**: De klanten van Marketo Engage met de integratie van niet-inheemse [!DNL Salesforce] CRM kunnen [!DNL Sales Insight] nu gebruiken om hun verkoopteams te helpen begrijpen, voorrang geven, en met de meest betrokken lood en kansen in wisselwerking staan om slimme het verkopen en snellere overeenkomsten toe te laten.

## [!DNL Sales Connect] {#sales-connect}

![ (star) ](assets/yellow-star.png)

* **[Verbeterde Toestemming van twee partijen voor de Vraag van de Verkoop:](/help/marketo/product-docs/marketo-sales-connect/phone/two-party-consent-settings.md)** Admins heeft nu grotere controle over de configuraties van de vraagopname. [ laat vraagopnamen ](/help/marketo/product-docs/marketo-sales-connect/phone/enable-call-recording.md) met vertrouwen toe dat u de wet van de twee-partijtoestemming in acht neemt. Automatiseer het bericht van de vraag die wordt geregistreerd en activeer audioclips om vóór de vraag worden gespeeld.

<br> 

## Aankondigingen en afwaarderingen {#announcements-deprecations}

* **Activum API &quot;_method&quot;de Verwijdering van de Parameter**: Na September 2020, zullen de eindpunten van activa API niet meer &quot;_method&quot;goedkeuren om de Parameters van de Vraag in een POST lichaam over te gaan om de lengtebeperkingen van URI te mijden. Om tegemoet te komen aan verzoeken die deze parameter vereisen, worden de URI-limieten voor de bron-API&#39;s verhoogd van 8 KB naar 65 KB.
* **[[!DNL Munchkin] associate Lood ](https://developers.marketo.com/blog/deprecation-of-munchkin-associate-lead-method/)**: Met deze versie van de Cliënt van Munchkin JavaScript, versie 159, zullen wij met afschrijving van de [!DNL Munchkin] Associate methode van de Lood beginnen. Als deze wordt aangeroepen, wordt er een waarschuwing weergegeven dat de methode in een toekomstige versie wordt verwijderd. Nadat de methode is verwijderd, is deze niet meer functioneel en wordt geprobeerd deze te gebruiken. Marketo Engage-klanten die deze methode onlangs hebben gebruikt, zullen individueel op de hoogte worden gesteld van hun gebruik.
* **Steun voor Internet Explorer**: Zoals eerder aangekondigd, beëindigt de steun van Marketo Engage voor Internet Explorer 11 op **31 Juli, 2020**. We blijven [!DNL Google Chrome], [!DNL Mozilla Firefox], [!DNL &#x200B; Apple Safari] en [!DNL Microsoft Edge] ondersteunen.
* **Van het Standaard luchtruim Ervaring**: De optie voor beheerders of gebruikers om [!DNL Marketo Sky] als standaardervaring te plaatsen zal in deze versie in voorbereiding op een update aan de primaire gebruikerservaring worden verwijderd. Meer informatie over de update van de primaire ervaring, die voor later dit jaar is gepland, zal in juli beschikbaar zijn. Gebruikers die [!DNL Marketo Sky] als hun standaardervaring hebben ingesteld of toegang hebben gekregen tot [!DNL Marketo Sky] , kunnen [!DNL Marketo Sky] blijven gebruiken via een tegel op de startpagina van Mijn Marketo.
* **EdgeHTML (niet-Chromium) [!DNL Microsoft Edge] steun**: Marketo Engage zal geen versies EdgeHTML van Microsoft Edge aan het eind van 2020 meer steunen. Vanaf 1 januari 2021 ondersteunen we alleen de nieuwste Chromium-versie van Microsoft Edge.
