---
unique-page-id: 5472615
description: Begrijpend Systeem Beheerde Gebieden - Marketo Docs - de Documentatie van het Product
title: Werken met door het systeem beheerde velden
translation-type: tm+mt
source-git-commit: d7d6aee63144c472e02fe0221c4a164183d04dd4
workflow-type: tm+mt
source-wordcount: '522'
ht-degree: 0%

---


# Werken met systeembeheerde velden {#understanding-system-managed-fields}

U zou kunnen opgemerkt hebben dat [persoondetailpagina](../../../product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/using-the-person-detail-page.md) een reeks niet-editable gebieden heeft die door Marketo worden gecreeerd. Deze gegevens zijn afkomstig uit verschillende bronnen en er zijn talloze waarden die kunnen worden weergegeven.

## Veldtypen {#field-types}

| **Veldnaam** | **Definitie** |
|---|---|
| Oorspronkelijk brontype | De locatie waar een persoon of websitebezoeker voor het eerst is aangetroffen (bijvoorbeeld: Importeren van lijst, webpaginabezoek) |
| Originele broninformatie | Specificaties over die locatie (voorbeeld: Naam van de lijst, URL van de webpagina) |
| Originele zoekengine | Indien van toepassing, de zoekmachine die de persoon naar de oorspronkelijke bron van binnenkomst heeft verwezen |
| Oorspronkelijke zoekterm | Indien van toepassing, de gebruikte zoekterm die de persoon naar de oorspronkelijke bron van binnenkomst verwees |
| Oorspronkelijke verwijzing | URL die de oorspronkelijke invoerbron heeft gehost |
| Brontype van registratie | De locatie waar een activiteit voor het eerst een persoon werd (voorbeeld: Importeren van lijst, webpaginabezoek) |
| Informatie over registratiefron | Specificaties over die locatie (voorbeeld: Naam van de lijst, URL van de webpagina) |
| Anonieme IP | Geeft het IP-adres van een persoon aan |
| Overgenomen onderneming | De beste raad van de markt (gebaseerd op IP) van het bedrijf van de persoon |
| Overgenomen stad | Marketo&#39;s beste schatting (gebaseerd op IP) van de stad van de persoon |
| Gebied van de betrokken staat | De beste raad van de markt (gebaseerd op IP) van de staat of de regio van de persoon |
| Postcode | De beste schatting van de markt (gebaseerd op IP) van de postcode van de persoon |
| Overgenomen land | Marketo&#39;s beste schatting (gebaseerd op IP) van het land van de persoon |
| Overgenomen metropolitaans gebied | Marketo&#39;s beste schatting (gebaseerd op IP) van het metropolitane gebied van de persoon |
| Gebiedscode afgeleide telefoon | De beste raad van de markt (gebaseerd op IP) van het het gebiedscode van de persoon |

## Mogelijke waarden voor het brontype Origineel en Registratie {#possible-values-for-original-and-registration-source-type}

Hieronder staan enkele mogelijke waarden en wat ze betekenen.

| **Oorspronkelijk brontype** | **Definitie** |
|---|---|
| Salesforce.com | Persoon is gevonden bij Salesforce-synchronisatie |
| Bezoekingen webpagina | Persoon is aangetroffen op een webpagina |
| Invullen webformulier | De persoon is ontdekt na het invullen van een formulier |
| Lijstimport | De persoon is gevonden uit een lijstimport |
| Nieuwe persoon | De persoon is handmatig in de database ingevoerd |
| Webkoppeling klikken | Persoon is gevonden nadat op een koppeling is geklikt |
| Verkoope-mail | De persoon is per e-mail verzonden via de e-mailinvoegtoepassing voor het verkoopinzicht |
| Persoon | Persoon is als persoon gesynchroniseerd van Salesforce |
| Contact | De persoon is als contactpersoon via Salesforce gesynchroniseerd |
| Munchkin-API | Persoon is ontdekt door de Munchkin-API van Marketo |
| Sociale app | Persoon is ontdekt door een sociale widget |
| Webservice-API | Persoon is aangetroffen door een webservice-API |
| Gebeurtenispartner | Persoon is ontdekt via een gesynchroniseerde webinarservice |
| Associate Lead | Persoon die is samengevoegd via een koppelings-API-aanroep |

| **Brontype van registratie** | **Definitie** |
|---|---|
| Lijstimport | Een persoon worden via een lijstimport |
| Salesforce.com | Iemand worden via een Salesforce-synchronisatie |
| Invullen webformulier | Een persoon worden na het invullen van een formulier |
| Verkoope-mail | De persoon is per e-mail verzonden via de e-mailinvoegtoepassing voor het verkoopinzicht |
| Webservice-API | De persoon is gemaakt via de API SOAP/REST |
| Nieuwe persoon | De persoon is handmatig in de database ingevoerd |
| Munchkin-API | Iemand worden via de Munchkin-API van Marketo |
| Sociale app | Een persoon worden via een sociale widget |
| Gebeurtenispartner | Een persoon worden via een gekoppelde webinar-service |

