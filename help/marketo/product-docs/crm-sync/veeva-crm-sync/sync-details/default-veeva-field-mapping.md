---
description: Standaardveldtoewijzing voor beeldschermen - Marketo Docs - Productdocumentatie
title: Standaardveldtoewijzing
exl-id: 3bf36d50-daea-431f-9537-b3007ad75945
feature: Veeva CRM
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '263'
ht-degree: 27%

---

# Standaardveldtoewijzing {#default-veeva-field-mapping}

Wanneer u uw Marketo Engage-account aanvankelijk synchroniseert met Veeva, maakt Marketo automatisch deze koppelingen tussen uw ingebouwde Veva- en Marketo-velden. Marketo synchroniseert ook uw aangepaste velden op uw accounts en contactpersonen.

## Contactvelden {#contact-fields}

<table>
  <colgroup>
    <col/>
    <col/>
  </colgroup>
  <thead>
    <tr>
      <th>SFDC-veld</th>
      <th>Marketo-veld</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Verjaardag</td>
      <td>Geboortedatum</td>
    </tr>
    <tr>
      <td>Aanmaakdatum</td>
      <td>Aanmaakdatum SFDC</td>
    </tr>
    <tr>
      <td>Beschrijving contactpersoon</td>
      <td>Personen</td>
    </tr>
    <tr>
      <td>E-mail</td>
      <td>E-mailadres</td>
    </tr>
    <tr>
      <td>Zakelijke fax</td>
      <td>Faxnummer</td>
    </tr>
    <tr>
      <td>Voornaam</td>
      <td>Voornaam</td>
    </tr>
    <tr>
      <td>E-mail uitschakelen</td>
      <td>Niet geabonneerd</td>
    </tr>
    <tr>
      <td>Verwijderd</td>
      <td>SFDC wordt verwijderd</td>
    </tr>
    <tr>
      <td>Achternaam</td>
      <td>Achternaam</td>
    </tr>
    <tr>
      <td>Leadbron</td>
      <td>Bron</td>
    </tr>
    <tr>
      <td>Leadscore</td>
      <td>Score</td>
    </tr>
    <tr>
      <td>MailingCity</td>
      <td>Stad</td>
    </tr>
    <tr>
      <td>MailingLand</td>
      <td>Land</td>
    </tr>
    <tr>
      <td>Postcode</td>
      <td>Postcode</td>
    </tr>
    <tr>
      <td>MailingState</td>
      <td>Staat</td>
    </tr>
    <tr>
      <td>MailingStreet</td>
      <td>Adres</td>
    </tr>
    <tr>
      <td>Mobiele telefoon</td>
      <td>Mobiel</td>
    </tr>
    <tr>
      <td>Zakelijke telefoon</td>
      <td>Telefoonnummer</td>
    </tr>
    <tr>
      <td>Aanhef</td>
      <td>Aanhef</td>
    </tr>
    <tr>
      <td>Titel</td>
      <td>Beroep</td>
    </tr>
  </tbody>
</table>

## Accountvelden {#account-fields}

<table>
  <colgroup>
    <col/>
    <col/>
  </colgroup>
  <thead>
    <tr>
      <th>SFDC-veld</th>
      <th>Marketo-veld</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Jaaromzet</td>
      <td>Jaaromzet</td>
    </tr>
    <tr>
      <td>Factuurstad</td>
      <td>Factuurstad</td>
    </tr>
    <tr>
      <td>Factuurland</td>
      <td>Factuurland</td>
    </tr>
    <tr>
      <td>Postcode facturering</td>
      <td>Factuurpostcode</td>
    </tr>
    <tr>
      <td>Factureringsstaat/provincie</td>
      <td>Factuurstaat</td>
    </tr>
    <tr>
      <td>Factureringsstraat</td>
      <td>Factuuradres</td>
    </tr>
    <tr>
      <td>Accountbeschrijving</td>
      <td>Bedrijfsnotities</td>
    </tr>
    <tr>
      <td>Marktsegment</td>
      <td>Marktsegment</td>
    </tr>
    <tr>
      <td>Verwijderd</td>
      <td>SFDC wordt verwijderd</td>
    </tr>
    <tr>
      <td>Accountnaam</td>
      <td>Bedrijfsnaam</td>
    </tr>
    <tr>
      <td>Werknemers</td>
      <td>Aantal werknemers</td>
    </tr>
    <tr>
      <td>Account-telefoon</td>
      <td>Telefoon</td>
    </tr>
    <tr>
      <td>SIC-code</td>
      <td>SIC-code</td>
    </tr>
    <tr>
      <td>Accountsite</td>
      <td>Vestiging</td>
    </tr>
    <tr>
      <td>Accounttype</td>
      <td>SFDC-type</td>
    </tr>
    <tr>
      <td>Website</td>
      <td>Website</td>
    </tr>
  </tbody>
</table>

## Veeva-gerelateerde systeemvelden in Marketo (alleen-lezen) {#veeva-related-system-fields-in-marketo}

Deze velden worden gemaakt in Marketo, maar kunnen niet worden aangepast door klanten.

<table>
  <colgroup>
    <col/>
    <col/>
  </colgroup>
  <thead>
    <tr>
      <th>Veld</th>
      <th>Beschrijving</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Veeva-id</td>
      <td>Salesforce-id van 18 tekens</td>
    </tr>
    <tr>
      <td>Veeva Type</td>
      <td>Contact opnemen. Als de lead leeg is, bestaat deze alleen als een persoon in Marketo</td>
    </tr>
    <tr>
      <td>Veeva Gemaakt op</td>
      <td>Datum gemaakt in SFDC (kan anders zijn dan Gemaakt in Marketo)</td>
    </tr>
    <tr>
      <td>Veeva wordt verwijderd</td>
      <td>Persoon was in SFDC maar werd verwijderd en woont nu alleen in Marketo</td>
    </tr>
  </tbody>
</table>
