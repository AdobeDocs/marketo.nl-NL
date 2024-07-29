---
unique-page-id: 5472615
description: Werken met systeembeheerde velden - Marketo Docs - Productdocumentatie
title: Werken met door het systeem beheerde velden
exl-id: 4a58d41f-c2f5-4bcc-93ef-10a31e5475fd
feature: Field Management
source-git-commit: fc25a088005ee1d552f6e61e2fa7b953e2fde862
workflow-type: tm+mt
source-wordcount: '523'
ht-degree: 1%

---

# Werken met door het systeem beheerde velden {#understanding-system-managed-fields}

U zou kunnen opgemerkt hebben dat de [ pagina van het persoondetail ](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/using-the-person-detail-page.md){target="_blank"} een reeks niet-editable gebieden heeft die door Marketo worden gecreeerd. Deze gegevens zijn afkomstig uit verschillende bronnen en er zijn talloze waarden die kunnen worden weergegeven.

## Veldtypen {#field-types}

<table><thead>
  <tr>
    <th>Veldnaam</th>
    <th>Definitie</th>
  </tr></thead>
<tbody>
  <tr>
    <td>Oorspronkelijk Source-type</td>
    <td>De locatie waar een persoon of websitebezoeker voor het eerst is aangetroffen (bijvoorbeeld: Lijstimport, webpaginabezoek)</td>
  </tr>
  <tr>
    <td>Originele Source-informatie</td>
    <td>Specificaties over die locatie (bijvoorbeeld: naam van de lijst, URL van de webpagina)</td>
  </tr>
  <tr>
    <td>Originele zoekengine</td>
    <td>Indien van toepassing, de zoekmachine die de persoon naar de oorspronkelijke bron van binnenkomst heeft verwezen</td>
  </tr>
  <tr>
    <td>Oorspronkelijke zoekterm</td>
    <td>Indien van toepassing, de gebruikte zoekterm die de persoon naar de oorspronkelijke bron van binnenkomst verwees</td>
  </tr>
  <tr>
    <td>Oorspronkelijke verwijzing</td>
    <td>URL die de oorspronkelijke invoerbron heeft gehost</td>
  </tr>
  <tr>
    <td>Source-type registratie</td>
    <td>De locatie waar een activiteit voor het eerst een persoon werd (Voorbeeld: List Import, Web Page Visit)</td>
  </tr>
  <tr>
    <td>Source-informatie registreren</td>
    <td>Specificaties over die locatie (bijvoorbeeld: naam van de lijst, URL van de webpagina)</td>
  </tr>
  <tr>
    <td>Anoniem IP-adres</td>
    <td>Geeft het IP-adres van een persoon aan</td>
  </tr>
  <tr>
    <td>Afgeleid bedrijf</td>
    <td>Marketo raadt het bedrijf van de persoon het beste raden (op basis van IP)</td>
  </tr>
  <tr>
    <td>Overgenomen stad</td>
    <td>De beste schatting van de stad van de persoon (op basis van IP) door Marketo</td>
  </tr>
  <tr>
    <td>Gebied van de betrokken staat</td>
    <td>Marketo kan het beste raden (op basis van IP) van de staat of regio van de persoon</td>
  </tr>
  <tr>
    <td>Postcode</td>
    <td>Marketo geeft de beste schatting (op basis van IP) van de postcode van de persoon</td>
  </tr>
  <tr>
    <td>Afgeleid land</td>
    <td>Marketo geeft de beste schatting (gebaseerd op IP) van het land van de persoon</td>
  </tr>
  <tr>
    <td>Overgenomen metropolitaans gebied</td>
    <td>Marketo geeft de beste schatting (op basis van IP) van het metropolitane gebied van de persoon</td>
  </tr>
  <tr>
    <td>Gebiedscode afgeleide telefoon</td>
    <td>Marketo kan het beste raden (op basis van IP) van de gebiedscode van de persoon</td>
  </tr>
</tbody></table>

## Mogelijke waarden voor het Source-type Origineel en Registratie {#possible-values-for-original-and-registration-source-type}

Hieronder staan enkele mogelijke waarden en wat ze betekenen.

<table><thead>
  <tr>
    <th>Oorspronkelijk Source-type</th>
    <th>Definitie</th>
  </tr></thead>
<tbody>
  <tr>
    <td>Salesforce.com</td>
    <td>Persoon is gevonden bij Salesforce-synchronisatie</td>
  </tr>
  <tr>
    <td>Bezoekingen webpagina</td>
    <td>Persoon is aangetroffen op een webpagina</td>
  </tr>
  <tr>
    <td>Invullen webformulier</td>
    <td>De persoon is ontdekt na het invullen van een formulier</td>
  </tr>
  <tr>
    <td>Lijstimport</td>
    <td>De persoon is gevonden uit een lijstimport</td>
  </tr>
  <tr>
    <td>Nieuwe persoon</td>
    <td>De persoon is handmatig in de database ingevoerd</td>
  </tr>
  <tr>
    <td>Webkoppeling klikken</td>
    <td>Persoon is gevonden na klikken op een koppeling</td>
  </tr>
  <tr>
    <td>Verkoope-mail</td>
    <td>De persoon is per e-mail verzonden via de e-mailinvoegtoepassing voor het verkoopinzicht</td>
  </tr>
  <tr>
    <td>Persoon</td>
    <td>Persoon is als persoon gesynchroniseerd van Salesforce</td>
  </tr>
  <tr>
    <td>Contact</td>
    <td>De persoon is via Webhaak gesynchroniseerd als een contactpersoon</td>
  </tr>
  <tr>
    <td>Munchkin-API</td>
    <td>Persoon is aangetroffen door de Marketo Engage Munchkin-API</td>
  </tr>
  <tr>
    <td>Sociale app</td>
    <td>Persoon is ontdekt door een sociale widget</td>
  </tr>
  <tr>
    <td>Webservice-API</td>
    <td>Persoon is aangetroffen door een webservice-API</td>
  </tr>
  <tr>
    <td>Gebeurtenispartner</td>
    <td>Persoon is ontdekt via een gesynchroniseerde webinarservice</td>
  </tr>
  <tr>
    <td>Associate Lead</td>
    <td>Persoon die is samengevoegd via een koppelings-API-aanroep</td>
  </tr>
</tbody></table>

<table><thead>
  <tr>
    <th>Source-type registratie</th>
    <th>Definitie</th>
  </tr></thead>
<tbody>
  <tr>
    <td>Lijstimport</td>
    <td>Een persoon worden via een lijstimport</td>
  </tr>
  <tr>
    <td>Salesforce.com</td>
    <td>Iemand worden via Salesforce-synchronisatie</td>
  </tr>
  <tr>
    <td>Invullen webformulier</td>
    <td>Een persoon worden na het invullen van een formulier</td>
  </tr>
  <tr>
    <td>Verkoope-mail</td>
    <td>De persoon is per e-mail verzonden via de e-mailinvoegtoepassing voor het verkoopinzicht</td>
  </tr>
  <tr>
    <td>Webservice-API</td>
    <td>Persoon is gemaakt via SOAP/REST API</td>
  </tr>
  <tr>
    <td>Nieuwe persoon</td>
    <td>De persoon is handmatig in de database ingevoerd</td>
  </tr>
  <tr>
    <td>Munchkin-API</td>
    <td>Word een persoon via de Marketo Munchkin-API</td>
  </tr>
  <tr>
    <td>Sociale app</td>
    <td>Een persoon worden via een sociale widget</td>
  </tr>
  <tr>
    <td>Gebeurtenispartner</td>
    <td>Een persoon worden via een gekoppelde webinar-service</td>
  </tr>
</tbody>
</table>
