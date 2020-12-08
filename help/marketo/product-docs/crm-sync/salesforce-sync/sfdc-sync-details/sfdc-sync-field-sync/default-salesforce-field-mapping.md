---
unique-page-id: 4719314
description: Standaard Salesforce-veldtoewijzing - Marketo Docs - Productdocumentatie
title: Standaardtoewijzing Salesforce-veld
translation-type: tm+mt
source-git-commit: 1a29614ec938074902af201b2ffc11cfaa625f7a
workflow-type: tm+mt
source-wordcount: '362'
ht-degree: 0%

---


# Standaardtoewijzing Salesforce-veld {#default-salesforce-field-mapping}

Wanneer u uw Marketo-account eerst synchroniseert met Salesforce, maakt Marketo automatisch deze koppelingen tussen uw ingebouwde Salesforce- en Marketo-velden. Marketo synchroniseert ook uw aangepaste velden op uw leads, accounts, opportunity en contactpersonen.

## Loodvelden {#lead-fields}

| SFDC-veld | Markeringsveld |
|---|---|
| Jaarlijkse inkomsten | Jaarlijkse inkomsten |
| Plaats | Plaats |
| Bedrijf | Bedrijfsnaam |
| Omgezette datum | Omgezette SFDC-datum |
| Land | Land |
| Aanmaakdatum | Aanmaakdatum SFDC |
| Beschrijving | Personen |
| E-mail | E-mailadres |
| Fax | Faxnummer |
| Voornaam | Voornaam |
| E-mail uitschakelen | Abonnement opgezegd |
| Industrie | Industrie |
| Omgezet | SFDC is geconverteerd |
| Verwijderd | SFDC wordt verwijderd |
| Achternaam | Achternaam |
| Bron lood | Bron |
| Loodscore | Score |
| Mobiele telefoon | Mobiel telefoonnummer |
| Werknemers | Aantal werknemers |
| Telefoon | Telefoonnummer |
| Postcode | Postcode |
| Classificatie | Classificatie |
| Aanhef | Aanhef |
| Staat/provincie | Staat |
| Status | Status |
| Straat | Adres |
| Titel | Functie |
| Website | Website |

## Contactvelden {#contact-fields}

| SFDC-veld | Markeringsveld |
|---|---|
| Geboortedatum | Geboortedatum |
| Aanmaakdatum | Aanmaakdatum SFDC |
| Beschrijving contactpersoon | Personen |
| E-mail | E-mailadres |
| Zakelijke fax | Faxnummer |
| Voornaam | Voornaam |
| E-mail uitschakelen | Abonnement opgezegd |
| Verwijderd | SFDC wordt verwijderd |
| Achternaam | Achternaam |
| Bron lood | Bron |
| Loodscore | Score |
| MailingCity | Plaats |
| MailingLand | Land |
| Postcode | Postcode |
| MailingState | Staat |
| MailingStreet | Adres |
| Mobiele telefoon | Mobiel telefoonnummer |
| Zakelijke telefoon | Telefoonnummer |
| Aanhef | Aanhef |
| Titel | Functie |

## Accountvelden {#account-fields}

| SFDC-veld | Markeringsveld |
|---|---|
| Jaarlijkse inkomsten | Jaarlijkse inkomsten |
| Factureringsplaats | Factureringsplaats |
| Factureringsland | Factureringsland |
| Postcode facturering | Postcode facturering |
| Factureringsstaat/provincie | Factureringsstatus |
| Factureringsstraat | Factuuradres |
| Accountbeschrijving | Bedrijfsnotities |
| Industrie | Industrie |
| Verwijderd | SFDC wordt verwijderd |
| Accountnaam | Bedrijfsnaam |
| Werknemers | Aantal werknemers |
| Account-telefoon | Hoofdtelefoon |
| SIC-code | SIC-code |
| Accountsite | Site |
| Accounttype | SFDC-type |
| Website | Website |

## Salesforce-Verwante Systeemvelden in Marketo (alleen-lezen) {#salesforce-related-system-fields-in-marketo-read-only}

Deze velden worden gemaakt in Marketo, maar kunnen niet worden aangepast door klanten.

| Veld | Beschrijving |
|---|---|
| SFDC-id | Salesforce-id van 18 tekens |
| SFDC-type | Lood of contactpersoon. Indien leeg, bestaat de lead alleen als een persoon in Marketo |
| Aanmaakdatum SFDC | Datum gemaakt in SFDC (kan verschillen van Gemaakt in Marketo) |
| SFDC is verwijderd | Persoon was in SFDC maar werd verwijderd en woont nu alleen in Marketo |
