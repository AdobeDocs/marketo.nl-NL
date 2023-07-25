---
unique-page-id: 5472615
description: Werken met systeembeheerde velden - Marketo Docs - Productdocumentatie
title: Werken met door het systeem beheerde velden
exl-id: 4a58d41f-c2f5-4bcc-93ef-10a31e5475fd
feature: Field Management
source-git-commit: 02b2e39580c5eac63de4b4b7fdaf2a835fdd4ba5
workflow-type: tm+mt
source-wordcount: '512'
ht-degree: 1%

---

# Werken met door het systeem beheerde velden {#understanding-system-managed-fields}

U zou kunnen opgemerkt hebben dat [detailpagina van persoon](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/using-the-person-detail-page.md){target="_blank"} heeft een reeks niet-bewerkbare velden die door Marketo zijn gemaakt. Deze gegevens zijn afkomstig uit verschillende bronnen en er zijn talloze waarden die kunnen worden weergegeven.

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
| Anoniem IP-adres | Geeft het IP-adres van een persoon aan |
| Afgeleid bedrijf | Marketo raadt het bedrijf van de persoon het beste raden (op basis van IP) |
| Overgenomen stad | De beste schatting van de stad van de persoon (op basis van IP) door Marketo |
| Gebied van de betrokken staat | Marketo kan het beste raden (op basis van IP) van de staat of regio van de persoon |
| Postcode | Marketo geeft de beste schatting (op basis van IP) van de postcode van de persoon |
| Afgeleid land | Marketo geeft de beste schatting (gebaseerd op IP) van het land van de persoon |
| Overgenomen metropolitaans gebied | Marketo geeft de beste schatting (gebaseerd op IP) van het metropolitane gebied van de persoon |
| Gebiedscode afgeleide telefoon | Marketo kan het beste raden (op basis van IP) van de gebiedscode van de persoon |

## Mogelijke waarden voor het brontype Origineel en Registratie {#possible-values-for-original-and-registration-source-type}

Hieronder staan enkele mogelijke waarden en wat ze betekenen.

| **Oorspronkelijk brontype** | **Definitie** |
|---|---|
| Salesforce.com | Persoon is ontdekt van een [!DNL Webhook] synchroniseren |
| Bezoekingen webpagina | Persoon is aangetroffen op een webpagina |
| Invullen webformulier | De persoon is ontdekt na het invullen van een formulier |
| Lijstimport | De persoon is gevonden uit een lijstimport |
| Nieuwe persoon | De persoon is handmatig in de database ingevoerd |
| Webkoppeling klikken | Persoon is gevonden nadat op een koppeling is geklikt |
| Verkoope-mail | De persoon is per e-mail verzonden via [!DNL Sales Insight] E-mailinvoegtoepassing |
| Persoon | Persoon is gesynchroniseerd van [!DNL Salesforce] als persoon |
| Contact | Persoon is gesynchroniseerd van [!DNL Webhook] als contactpersoon |
| [!DNL Munchkin] API | Persoon is ontdekt door de Marketo Engage [!DNL Munchkin] API |
| Sociale app | Persoon is ontdekt door een sociale widget |
| Webservice-API | Persoon is aangetroffen door een webservice-API |
| Gebeurtenispartner | Persoon is ontdekt via een gesynchroniseerde webinarservice |
| Associate Lead | Persoon die is samengevoegd via een koppelings-API-aanroep |

| **Brontype van registratie** | **Definitie** |
|---|---|
| Lijstimport | Een persoon worden via een lijstimport |
| Salesforce.com | Een persoon worden via een [!DNL Webhook] synchroniseren |
| Invullen webformulier | Een persoon worden na het invullen van een formulier |
| Verkoope-mail | De persoon is per e-mail verzonden via [!DNL Webhook] E-mailinvoegtoepassing |
| Webservice-API | De persoon is gemaakt via de API SOAP/REST |
| Nieuwe persoon | De persoon is handmatig in de database ingevoerd |
| [!DNL Munchkin] API | Word een persoon via Marketo [!DNL Munchkin] API |
| Sociale app | Een persoon worden via een sociale widget |
| Gebeurtenispartner | Een persoon worden via een gekoppelde webinar-service |
