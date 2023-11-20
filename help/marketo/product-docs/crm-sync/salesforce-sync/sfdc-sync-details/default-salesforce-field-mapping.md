---
unique-page-id: 4719314
description: Standaardtoewijzing van Salesforce-velden - Marketo-documenten - Productdocumentatie
title: Standaardtoewijzing Salesforce-veld
exl-id: d6639733-f85d-4f4c-ac41-5d2a68a9c6b2
feature: Salesforce Integration
source-git-commit: 0087a5e88b8bd9601875f68a2e7cadeebdb5d682
workflow-type: tm+mt
source-wordcount: '363'
ht-degree: 33%

---

# Standaardtoewijzing Salesforce-veld {#default-salesforce-field-mapping}

Als u uw Marketo Engage-account eerst synchroniseert met Salesforce, maakt Marketo automatisch deze koppelingen tussen uw ingebouwde Salesforce- en Marketo-velden. Marketo synchroniseert ook uw aangepaste velden op uw leads, accounts, opportunity en contactpersonen.

## Loodvelden {#lead-fields}

| SFDC-veld | Marketo-veld |
|---|---|
| Jaaromzet | Jaaromzet |
| Stad | Stad |
| Bedrijf | Bedrijfsnaam |
| Omgezette datum | Omgezette SFDC-datum |
| Land | Land |
| Aanmaakdatum | Aanmaakdatum SFDC |
| Beschrijving | Personen |
| E-mail | E-mailadres |
| Fax | Faxnummer |
| Voornaam | Voornaam |
| E-mail uitschakelen | Niet geabonneerd |
| Marktsegment | Marktsegment |
| Omgezet | SFDC is geconverteerd |
| Verwijderd | SFDC wordt verwijderd |
| Achternaam | Achternaam |
| Leadbron | Bron |
| Leadscore | Score |
| Mobiele telefoon | Mobiel |
| Werknemers | Aantal werknemers |
| Telefoonnummer | Telefoonnummer |
| Postcode | Postcode |
| Classificatie | Classificatie |
| Aanhef | Aanhef |
| Staat/provincie | Staat |
| Status | Status |
| Straat | Adres |
| Titel | Beroep |
| Website | Website |

## Contactvelden {#contact-fields}

| SFDC-veld | Marketo-veld |
|---|---|
| Verjaardag | Geboortedatum |
| Aanmaakdatum | Aanmaakdatum SFDC |
| Beschrijving contactpersoon | Personen |
| E-mail | E-mailadres |
| Zakelijke fax | Faxnummer |
| Voornaam | Voornaam |
| E-mail uitschakelen | Niet geabonneerd |
| Verwijderd | SFDC wordt verwijderd |
| Achternaam | Achternaam |
| Leadbron | Bron |
| Leadscore | Score |
| MailingCity | Stad |
| MailingLand | Land |
| Postcode | Postcode |
| MailingState | Staat |
| MailingStreet | Adres |
| Mobiele telefoon | Mobiel |
| Zakelijke telefoon | Telefoonnummer |
| Aanhef | Aanhef |
| Titel | Beroep |

## Accountvelden {#account-fields}

| SFDC-veld | Marketo-veld |
|---|---|
| Jaaromzet | Jaaromzet |
| Factuurstad | Factuurstad |
| Factuurland | Factuurland |
| Postcode facturering | Factuurpostcode |
| Factureringsstaat/provincie | Factuurstaat |
| Factureringsstraat | Factuuradres |
| Accountbeschrijving | Bedrijfsnotities |
| Marktsegment | Marktsegment |
| Verwijderd | SFDC wordt verwijderd |
| Accountnaam | Bedrijfsnaam |
| Werknemers | Aantal werknemers |
| Account-telefoon | Telefoon |
| SIC-code | SIC-code |
| Accountsite | Vestiging |
| Accounttype | SFDC-type |
| Website | Website |

## Salesforce-gerelateerde systeemvelden in Marketo (alleen-lezen) {#salesforce-related-system-fields-in-marketo-read-only}

Deze velden worden gemaakt in Marketo, maar kunnen niet worden aangepast door klanten.

| Veld | Beschrijving |
|---|---|
| SFDC-id | Salesforce-id van 18 tekens |
| SFDC-type | Lood of contactpersoon. Indien leeg, bestaat de lead alleen als een persoon in Marketo |
| Aanmaakdatum SFDC | Datum gemaakt in SFDC (kan anders zijn dan Gemaakt in Marketo) |
| SFDC is verwijderd | Persoon was in SFDC maar werd verwijderd en woont nu alleen in Marketo |
