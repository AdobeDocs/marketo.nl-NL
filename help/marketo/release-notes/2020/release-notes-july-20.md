---
unique-page-id: 45416698
description: Opmerkingen bij de release - juli 2010 - Marketo Docs - Productdocumentatie
title: Opmerkingen bij de release - juli '20
exl-id: 3c9b1f1d-961c-4bf8-8b99-37b483230506
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '653'
ht-degree: 0%

---

# Opmerkingen bij de release: 20 juli{#release-notes-july}

De volgende functies zijn opgenomen in de release van juli 2010. Raadpleeg de Marketo-editie voor informatie over de beschikbaarheid van functies.

>[!AVAILABILITY]
>
>Houd er rekening mee dat, afhankelijk van het huidige pakket, items met een ster ( ![(star)](assets/star-yellow.svg)) mogelijk de aanschaf van een toegevoegde waarde vereisen. Neem contact op met uw Marketo Engage-vertegenwoordiger voor meer informatie.

**_Driemaandelijkse_** releasesDe volgende functies worden op 31  **juli 2020** gepubliceerd.

## Beheer {#administration}

* **[&quot;Gebruikt door&quot;Uitvoer in het Beheer](/help/marketo/product-docs/administration/field-management/export-used-by-data-for-a-field.md)** van het Gebied: Beheerders kunnen nu alle koppelingen met de elementen &quot;Gebruikt door&quot; voor een geselecteerd veld exporteren naar een CSV-bestand. Deze verbetering kan zowel beheerders als niet-beheerders helpen ongebruikte velden op te ruimen. Bovendien kunnen elementen nu worden geopend in een nieuw browsertabblad of venster.

## Op account gebaseerde marketing {#account-based-marketing}

![(ster)](assets/star-yellow.svg)

* **Bijgewerkte gebruikersinterface voor accountprofilering**: Vereenvoudig het maken van uw doelaccountlijst in Accountprofilering met gestroomlijnde stappen in één scherm.

<br> 

**_Vrijgeven door het Kwartaal_**

De volgende functies bevinden zich op een niet-driemaandelijkse cyclus en worden de komende maanden vrijgegeven.

* **Forms-service**: We introduceren een sterkere validatie van formulierveldsyntaxis en de mogelijkheid om gemeenschappelijke botpatronen te blokkeren met nieuwe functies voor beveiligde domeinen voor het laden van pagina&#39;s. Door het blokkeren van botpatronen kunt u de verzending van spamformulieren verminderen en de databasekwaliteit verbeteren.

>[!NOTE]
>
>De volledige implementatie van de uitgebreide validatie van de formulierveldsyntaxis is uitgesteld tot na onze release van januari 2021.

* **Verhoogde URI-groottebeperking** voor element-API: De de formaatgrens van het uniforme middel herkenningsteken (URI) wordt verhoogd van 8KB aan 65KB alvorens &quot;_method&quot;parameter te schrappen. Bij het uitvoeren van lange vraagkoorden, zal deze groottebeperking de gegevens toestaan om gemakkelijker over te gaan. De verwijdering van de parameter &quot;_method&quot; maakt deel uit van een aanstaande veiligheidsverbetering.

## Verkoopinzicht {#sales-insight}

![(ster)](assets/star-yellow.svg)

* **[Het Inzicht van de verkoop dat voor Klanten met Niet-inheemse Integratie](/help/marketo/product-docs/marketo-sales-insight/sales-insight-for-non-native-salesforce-integrations.md)  van Salesforce CRM (bèta)** wordt toegelaten: De klanten van de Marketo Engage met niet-inheemse integratie van Salesforce CRM kunnen de Inzicht van de Verkoop nu gebruiken om hun verkoopteams te helpen begrijpen, voorrang geven, en met de meest betrokken lood en de kansen in wisselwerking staan om slimme verkoop en snellere overeenkomsten toe te laten.

## Sales Connect {#sales-connect}

![(ster)](assets/star-yellow.svg)

* **[Verbeterde Tweepartijgoedkeuring voor de Vraag van de Verkoop:](/help/marketo/product-docs/marketo-sales-connect/phone/two-party-consent-settings.md)** Admins heeft nu grotere controle over de configuraties van de vraagopname. [Laat vraag ](/help/marketo/product-docs/marketo-sales-connect/phone/enable-call-recording.md) opname toe met vertrouwen dat u de twee-partij toestemmingswet naleeft. Automatiseer het bericht van de vraag die wordt geregistreerd en activeer audioclips om vóór de vraag worden gespeeld.

<br> 

## Aankondigingen en afwaarderingen {#announcements-deprecations}

* **Parameter &#39;_method&#39;-parameter voor element-API verwijderen**: Na september 2020, zullen de eindpunten van activa API niet meer &quot;_method&quot;goedkeuren om de Parameters van de Vraag in het lichaam van een POST over te gaan om de lengtebeperkingen van URI te omzeilen. Om tegemoet te komen aan verzoeken die deze parameter vereisen, worden de URI-limieten voor de bron-API&#39;s verhoogd van 8 kB naar 65 kB.
* **[Munchkin Associate Lead](https://developers.marketo.com/blog/deprecation-of-munchkin-associate-lead-method/)**: Met deze versie van Munchkin JavaScript Client, versie 159, beginnen we met het vervangen van de Munchkin Associate Lead-methode. Als deze wordt aangeroepen, wordt er een waarschuwing weergegeven dat de methode in een toekomstige versie wordt verwijderd. Nadat de methode is verwijderd, is deze niet meer functioneel en wordt geprobeerd deze te gebruiken. Marketo Engage klanten die deze methode onlangs hebben gebruikt, zullen individueel van hun gebruik op de hoogte worden gesteld.
* **Ondersteuning voor Internet Explorer**: Zoals eerder aangekondigd, loopt de ondersteuning van Marketo Engage voor Internet Explorer 11 af op 31  **juli 2020**. We blijven Google Chrome, Mozilla Firefox, Apple Safari en Microsoft Edge ondersteunen.
* **Standaardervaring** voor lucht: De optie die beheerders of gebruikers kunnen instellen als de standaardeleving, wordt in deze release verwijderd ter voorbereiding op een update van de primaire gebruikerservaring. Meer informatie over de update van de primaire ervaring, die voor later dit jaar is gepland, zal in juli beschikbaar zijn. Gebruikers die Marketo Sky als hun standaardervaring hebben geplaatst, of toegang tot Marketo Sky hebben gekregen, kunnen tot Marketo Sky van een tegel op de Mijn homepage van Marketo blijven toegang hebben.
* **EdgeHTML (non-Chromium) Microsoft Edge-ondersteuning**: Marketo Engage biedt eind 2020 geen ondersteuning meer voor EdgeHTML-versies van Microsoft Edge. Vanaf 1 januari 2021 ondersteunen we alleen de nieuwste Chromium-versie van Microsoft Edge.
