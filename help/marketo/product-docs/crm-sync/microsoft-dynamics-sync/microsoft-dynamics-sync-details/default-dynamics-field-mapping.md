---
description: Standaarddynamische veldtoewijzing - Marketo Docs - Productdocumentatie
title: Standaarddynamische veldtoewijzing
exl-id: 5f39bd0c-202e-4aa1-a0ac-49ac2554aa1e
feature: Microsoft Dynamics
source-git-commit: 09c70bb891f5cc93553c1f8dd0fb58dfd407fa81
workflow-type: tm+mt
source-wordcount: '829'
ht-degree: 12%

---

# Standaarddynamische veldtoewijzing {#default-dynamics-field-mapping}

Wanneer u uw Marketo-account aanvankelijk synchroniseert met Microsoft, maakt Marketo automatisch deze koppelingen tussen uw ingebouwde velden Dynamics en Marketo.  Marketo synchroniseert ook uw aangepaste velden op uw leads, accounts, opportunity en contactpersonen.

## Loodvelden {#lead-fields}

<table>
  <colgroup>
    <col>
    <col>
    <col>
  </colgroup>
  <tbody>
    <tr>
      <th>Marketo-veld</th>
      <th>MS Dynamics-veld</th>
      <th>API-naam MS Dynamics</th>
    </tr>
    <tr>
      <td>Aanmaakdatum van Microsoft</td>
      <td>Gemaakt op</td>
      <td>gemaakt</td>
    </tr>
    <tr>
      <td>Aanhef</td>
      <td>Aanhef</td>
      <td>aanhef</td>
    </tr>
    <tr>
      <td>Eerste</td>
      <td>Voornaam</td>
      <td>firstname</td>
    </tr>
    <tr>
      <td>Midden</td>
      <td>Tussenvoegsel</td>
      <td>middlename</td>
    </tr>
    <tr>
      <td>Laatste</td>
      <td>Achternaam</td>
      <td>lastname</td>
    </tr>
    <tr>
      <td>E-mail</td>
      <td>E-mail</td>
      <td>emailaddress1</td>
    </tr>
    <tr>
      <td>Beroep</td>
      <td>Functie</td>
      <td>jobtitle</td>
    </tr>
    <tr>
      <td>Telefoonnummer</td>
      <td>Zakelijke telefoon</td>
      <td>telephone1</td>
    </tr>
    <tr>
      <td>Mobiel</td>
      <td>Mobiele telefoon</td>
      <td>mobiele telefoon</td>
    </tr>
    <tr>
      <td>Fax</td>
      <td>Fax</td>
      <td>fax</td>
    </tr>
    <tr>
      <td>Adres</td>
      <td>Adres 1</td>
      <td>address1_line1</td>
    </tr>
    <tr>
      <td>Stad</td>
      <td>Stad</td>
      <td>address1_city</td>
    </tr>
    <tr>
      <td>Staat</td>
      <td>Staat/provincie</td>
      <td>address1_stateorProvince</td>
    </tr>
    <tr>
      <td>Land</td>
      <td>Land/regio</td>
      <td>address1_country</td>
    </tr>
    <tr>
      <td>Postcode</td>
      <td>Postcode</td>
      <td>address1_postalcode</td>
    </tr>
    <tr>
      <td>Bron persoon</td>
      <td>Leadbron</td>
      <td>leadsourcecode</td>
    </tr>
    <tr>
      <td>Status persoon</td>
      <td>Status</td>
      <td>statecode</td>
    </tr>
    <tr>
      <td>Reden voor status</td>
      <td>Reden voor status</td>
      <td>statuscode</td>
    </tr>
    <tr>
      <td>Personen</td>
      <td>Beschrijving</td>
      <td>beschrijving</td>
    </tr>
    <tr>
      <td>Niet bellen</td>
      <td>Telefoongesprekken niet toestaan</td>
      <td>donotphone</td>
    </tr>
    <tr>
      <td>Niet geabonneerd</td>
      <td>Geen e-mail bulksgewijs verzenden</td>
      <td>donotbulkemail</td>
    </tr>
    <tr>
      <td>Persoonsbeoordeling</td>
      <td>Classificatie</td>
      <td>leadquality code</td>
    </tr>
    <tr>
      <td>Microsoft-adres 2</td>
      <td>Adres 2</td>
      <td>address1_line2</td>
    </tr>
    <tr>
      <td>Microsoft-adres 3</td>
      <td>Adres 3</td>
      <td>address1_line3</td>
    </tr>
    <tr>
      <td>Microsoft verzendt geen e-mail</td>
      <td>E-mails niet toestaan</td>
      <td>donotemail</td>
    </tr>
    <tr>
      <td>Microsoft niet faxen</td>
      <td>Geen faxen toestaan</td>
      <td>donotfax</td>
    </tr>
    <tr>
      <td>Microsoft verzendt geen marketingmateriaal</td>
      <td>Marketingmateriaal</td>
      <td>donotsendmm</td>
    </tr>
    <tr>
      <td>Microsoft Home Phone</td>
      <td>Telefoon privé</td>
      <td>telephone2</td>
    </tr>
    <tr>
      <td>Voorkeursmethode van Microsoft</td>
      <td>Voorkeursmethode voor contact</td>
      <td>voorkeurscontactmethodiecode</td>
    </tr>
    <tr>
      <td>Microsoft-onderwerp</td>
      <td>Onderwerp</td>
      <td>onderwerp</td>
    </tr>
    <tr>
      <td>Laatste interessante momentdatum</td>
      <td>Laatste interessante momentdatum</td>
      <td>mkt_lastInterestingstweenDate</td>
    </tr>
    <tr>
      <td>Laatste interessante momentele beschrijving</td>
      <td>Laatste interessante momentele beschrijving</td>
      <td>mkt_lastInterestingmomentdesc</td>
    </tr>
    <tr>
      <td>Laatste interactieve tijdbron</td>
      <td>Laatste interactieve tijdbron</td>
      <td>mkt_leadinterestingimpulsource</td>
    </tr>
    <tr>
      <td>Laatste interessante momentype</td>
      <td>Laatste interessante momentype</td>
      <td>mkt_lastInterestingstentype</td>
    </tr>
    <tr>
      <td>Bedrijf</td>
      <td>Bedrijfsnaam</td>
      <td>bedrijfsnaam</td>
    </tr>
    <tr>
      <td>Relatieve score</td>
      <td>Relatieve score</td>
      <td>mkt_relativescore</td>
    </tr>
    <tr>
      <td>Prioriteit</td>
      <td>Prioriteit</td>
      <td>mkt_priority</td>
    </tr>
    <tr>
      <td>Relatieve urgentie</td>
      <td>urgentie</td>
      <td>mkt_priority</td>
    </tr>
    <tr>
      <td>Onderwerp</td>
      <td>Onderwerp</td>
      <td>onderwerp</td>
    </tr>
    <tr>
      <td>Jaaromzet</td>
      <td>Jaaromzet</td>
      <td>inkomsten</td>
    </tr>
  </tbody>
</table>

De onderstaande velden voor lead worden gesynchroniseerd voor intern gebruik.

<table>
  <colgroup>
    <col/>
    <col/>
  </colgroup>
  <tbody>
    <tr>
      <th>MS Dynamics-veld</th>
      <th>API-naam MS Dynamics</th>
    </tr>
    <tr>
      <td>Eigenaar </td>
      <td>eigenaar</td>
    </tr>
    <tr>
      <td>gemaakt op</td>
      <td>gemaakt</td>
    </tr>
  </tbody>
</table>

## Contactvelden {#contact-fields}

<table>
  <colgroup>
    <col/>
    <col/>
    <col/>
  </colgroup>
  <tbody>
    <tr>
      <th>Marketo-veld</th>
      <th>MS Dynamics-veld</th>
      <th>API-naam MS Dynamics</th>
    </tr>
    <tr>
      <td>Aanmaakdatum van Microsoft</td>
      <td>Gemaakt op</td>
      <td>gemaakt</td>
    </tr>
    <tr>
      <td>Aanhef</td>
      <td>Aanhef</td>
      <td>aanhef</td>
    </tr>
    <tr>
      <td>Eerste</td>
      <td>Voornaam</td>
      <td>firstname</td>
    </tr>
    <tr>
      <td>Midden</td>
      <td>Tussenvoegsel</td>
      <td>middlename</td>
    </tr>
    <tr>
      <td>Laatste</td>
      <td>Achternaam</td>
      <td>lastname</td>
    </tr>
    <tr>
      <td>E-mail</td>
      <td>E-mail</td>
      <td>emailaddress1</td>
    </tr>
    <tr>
      <td>Beroep</td>
      <td>Beroep</td>
      <td>jobtitle</td>
    </tr>
    <tr>
      <td>Telefoonnummer</td>
      <td>Zakelijke telefoon</td>
      <td>telephone1</td>
    </tr>
    <tr>
      <td>Mobiel</td>
      <td>Mobiele telefoon</td>
      <td>mobiele telefoon</td>
    </tr>
    <tr>
      <td>Adres</td>
      <td>Adres 1: Street 1</td>
      <td>address1_line1</td>
    </tr>
    <tr>
      <td>Stad</td>
      <td>Adres 1: Plaats</td>
      <td>address1_city</td>
    </tr>
    <tr>
      <td>Staat</td>
      <td>Adres 1: Staat/provincie</td>
      <td>address1_stateorProvince</td>
    </tr>
    <tr>
      <td>Land</td>
      <td>Adres 1: Land/regio</td>
      <td>address1_country</td>
    </tr>
    <tr>
      <td>Postcode</td>
      <td>Adres 1: Postcode</td>
      <td>address1_postalcode</td>
    </tr>
    <tr>
      <td>Status persoon</td>
      <td>Status</td>
      <td>statecode</td>
    </tr>
    <tr>
      <td>Reden voor status</td>
      <td>Reden voor status</td>
      <td>statuscode</td>
    </tr>
    <tr>
      <td>Niet bellen</td>
      <td>Telefoongesprekken niet toestaan</td>
      <td>donotphone</td>
    </tr>
    <tr>
      <td>Niet geabonneerd</td>
      <td>Geen e-mail bulksgewijs verzenden</td>
      <td>donotbulkemail</td>
    </tr>
    <tr>
      <td>Microsoft-adres 2</td>
      <td>Adres 1: Street 2</td>
      <td>address1_line2</td>
    </tr>
    <tr>
      <td>Microsoft-adres 3</td>
      <td>Adres 1: Street 3</td>
      <td>address1_line3</td>
    </tr>
    <tr>
      <td>Microsoft verzendt geen e-mail</td>
      <td>E-mails niet toestaan</td>
      <td>donotemail</td>
    </tr>
    <tr>
      <td>Microsoft Home Phone</td>
      <td>Telefoon privé</td>
      <td>telephone2</td>
    </tr>
    <tr>
      <td>Voorkeursmethode van Microsoft</td>
      <td>Voorkeursmethode voor contact</td>
      <td>voorkeurscontactmethodiecode</td>
    </tr>
    <tr>
      <td>Laatste interessante momentdatum</td>
      <td>Laatste interessante momentdatum</td>
      <td>mkt_lastInterestingstweenDate</td>
    </tr>
    <tr>
      <td>Laatste interessante momentype</td>
      <td>Laatste interessante momentype</td>
      <td>mkt_lastInterestingstentype</td>
    </tr>
    <tr>
      <td>Laatste interactieve tijdbron</td>
      <td>Laatste interactieve tijdbron</td>
      <td>mkt_leadinterestingimpulsource</td>
    </tr>
    <tr>
      <td>Laatste interessante momentele beschrijving</td>
      <td>Laatste interessante momentele beschrijving</td>
      <td>mkt_lastInterestingmomentdesc</td>
    </tr>
    <tr>
      <td>Microsoft verzendt geen marketingmateriaal</td>
      <td>Marketingmateriaal</td>
      <td>donotsendmm</td>
    </tr>
    <tr>
      <td>Microsoft niet faxen</td>
      <td>Microsoft niet faxen</td>
      <td>donotfax</td>
    </tr>
    <tr>
      <td>Prioriteit</td>
      <td>Prioriteit</td>
      <td>mkt_priority</td>
    </tr>
    <tr>
      <td>Relatieve urgentie</td>
      <td>urgentie</td>
      <td>mkt_priority</td>
    </tr>
    <tr>
      <td>Relatieve score</td>
      <td>Relatieve score</td>
      <td>mkt_relativescore</td>
    </tr>
    <tr>
      <td>Personen</td>
      <td>Beschrijving</td>
      <td>beschrijving </td>
    </tr>
    <tr>
      <td>Person score</td>
      <td>Leadscore</td>
      <td>mkt_leadscore</td>
    </tr>
    <tr>
      <td>Personen</td>
      <td>Beschrijving</td>
      <td>beschrijving </td>
    </tr>
  </tbody>
</table>

De onderstaande contactvelden worden gesynchroniseerd voor intern gebruik.

<table>
  <colgroup>
    <col/>
    <col/>
  </colgroup>
  <tbody>
    <tr>
      <th>MS Dynamics-veld</th>
      <th>API-naam MS Dynamics</th>
    </tr>
    <tr>
      <td>Eigenaar </td>
      <td>eigenaar</td>
    </tr>
    <tr>
      <td>gemaakt op</td>
      <td>gemaakt</td>
    </tr>
    <tr>
      <td>ouderdier</td>
      <td>Bedrijfsnaam</td>
    </tr>
  </tbody>
</table>

## Accountvelden {#account-fields}

<table>
  <colgroup>
    <col/>
    <col/>
    <col/>
  </colgroup>
  <tbody>
    <tr>
      <th>Marketo-veld</th>
      <th>MS Dynamics-veld</th>
      <th>API-naam MS Dynamics</th>
    </tr>
    <tr>
      <td>Rekening (a)</td>
      <td>Account</td>
      <td>verantwoording</td>
    </tr>
    <tr>
      <td>Factuuradres</td>
      <td>Adres 1: Street 1</td>
      <td>address1_line1</td>
    </tr>
    <tr>
      <td>Factuurstad</td>
      <td>Adres 1: Plaats</td>
      <td>address1_city</td>
    </tr>
    <tr>
      <td>Factuurland</td>
      <td>Adres 1: Land/regio</td>
      <td>address1_country</td>
    </tr>
    <tr>
      <td>Factuurpostcode</td>
      <td>Adres 1: Postcode</td>
      <td>address1_postalcode</td>
    </tr>
    <tr>
      <td>Microsoft-factuuradres 2</td>
      <td>Adres 1: Street 2</td>
      <td>address1_line2</td>
    </tr>
    <tr>
      <td>Microsoft-factureringsadres 3</td>
      <td>Adres 1: Street 3</td>
      <td>address1_line3</td>
    </tr>
    <tr>
      <td>Telefoon</td>
      <td>Telefoon</td>
      <td>telephone1</td>
    </tr>
    <tr>
      <td>Bedrijfstype</td>
      <td>Bedrijfstype</td>
      <td>businesstyecode</td>
    </tr>
    <tr>
      <td>Microsoft-accountnummer</td>
      <td>Rekeningnummer</td>
      <td>accountnummer</td>
    </tr>
    <tr>
      <td>Microsoft Company Status</td>
      <td>Status</td>
      <td>statecode</td>
    </tr>
    <tr>
      <td>Jaaromzet</td>
      <td>Jaaromzet</td>
      <td>inkomsten</td>
    </tr>
    <tr>
      <td>Bedrijfsnotities</td>
      <td>Beschrijving</td>
      <td>beschrijving</td>
    </tr>
    <tr>
      <td>Marktsegment</td>
      <td>Marktsegment</td>
      <td>industriële code</td>
    </tr>
    <tr>
      <td>SIC-code</td>
      <td>SIC-code</td>
      <td>sic</td>
    </tr>
    <tr>
      <td>Website</td>
      <td>Website</td>
      <td>website</td>
    </tr>
    <tr>
      <td>Aantal werknemers</td>
      <td>Aantal werknemers</td>
      <td>aantal werknemers</td>
    </tr>
    <tr>
      <td>SIC-code</td>
      <td>SIC-code</td>
      <td>sic</td>
    </tr>
    <tr>
      <td>Bedrijf</td>
      <td>Accountnaam</td>
      <td>name</td>
    </tr>
    <tr>
      <td>Aantal werknemers</td>
      <td>Aantal werknemers</td>
      <td>aantal werknemers</td>
    </tr>
  </tbody>
</table>

De onderstaande accountvelden worden gesynchroniseerd voor intern gebruik.

<table>
  <colgroup>
    <col/>
    <col/>
  </colgroup>
  <tbody>
    <tr>
      <th>MS Dynamics-veld</th>
      <th>API-naam MS Dynamics</th>
    </tr>
    <tr>
      <td>Eigenaar </td>
      <td>eigenaar</td>
    </tr>
    <tr>
      <td>gemaakt op</td>
      <td>gemaakt</td>
    </tr>
  </tbody>
</table>

## Opportunity-velden {#opportunity-fields}

<table>
  <colgroup>
    <col/>
    <col/>
    <col/>
  </colgroup>
  <tbody>
    <tr>
      <th>Marketo-veld</th>
      <th>MS Dynamics-veld</th>
      <th>API-naam MS Dynamics</th>
    </tr>
    <tr>
      <td>Probability sluiten</td>
      <td>waarschijnlijkheid</td>
      <td>waarschijnlijkheid</td>
    </tr>
    <tr>
      <td>Werkgebied</td>
      <td>status</td>
      <td>statecode</td>
    </tr>
    <tr>
      <td>Werkelijke sluitdatum</td>
      <td>Werkelijke sluitdatum</td>
      <td>actualclosed</td>
    </tr>
    <tr>
      <td>Naam</td>
      <td>Onderwerp</td>
      <td>name</td>
    </tr>
    <tr>
      <td>Geschatte waarde</td>
      <td>Oost. Ontvangsten</td>
      <td>estimatedValue</td>
    </tr>
    <tr>
      <td>Beschrijving</td>
      <td>Beschrijving</td>
      <td>beschrijving</td>
    </tr>
  </tbody>
</table>

De onderstaande accountvelden worden gesynchroniseerd voor intern gebruik.

<table>
  <colgroup>
    <col/>
    <col/>
  </colgroup>
  <tbody>
    <tr>
      <th>MS Dynamics-veld</th>
      <th>API-naam MS Dynamics</th>
    </tr>
    <tr>
      <td>Eigenaar </td>
      <td>eigenaar</td>
    </tr>
    <tr>
      <td>Opportunity</td>
      <td>opportunityId</td>
    </tr>
    <tr>
      <td>Potentiële klant</td>
      <td>customerId</td>
    </tr>
  </tbody>
</table>

## Microsoft-gerelateerde systeemvelden in Marketo (alleen-lezen) {#microsoft-related-system-fields}

De onderstaande velden worden gemaakt in Marketo, maar kunnen niet worden aangepast door gebruikers.

<table>
  <colgroup>
    <col/>
    <col/>
  </colgroup>
  <tbody>
    <tr>
      <th>Marketo-veld</th>
      <th>Beschrijving</th>
    </tr>
    <tr>
      <td>Microsoft-type</td>
      <td>Lood of contactpersoon. Indien leeg, bestaat de lead alleen als een persoon in Marketo</td>
    </tr>
    <tr>
      <td>Aanmaakdatum van Microsoft</td>
      <td>Datum gemaakt in MS Dynamics (kan verschillen van Gemaakt in Marketo)</td>
    </tr>
    <tr>
      <td>Microsoft is verwijderd</td>
      <td>Persoon was in Microsoft, maar werd verwijderd en woont nu alleen in Marketo</td>
    </tr>
  </tbody>
</table>
