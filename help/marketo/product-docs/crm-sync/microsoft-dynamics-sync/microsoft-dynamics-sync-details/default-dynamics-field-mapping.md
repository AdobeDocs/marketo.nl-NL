---
description: Standaarddynamische veldtoewijzing - Marketo Docs - Productdocumentatie
title: Standaarddynamische veldtoewijzing
exl-id: 5f39bd0c-202e-4aa1-a0ac-49ac2554aa1e
feature: Microsoft Dynamics
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '332'
ht-degree: 1%

---

# Standaarddynamische veldtoewijzing {#default-dynamics-field-mapping}

Wanneer u uw Marketo Engage-account aanvankelijk synchroniseert met Microsoft, maakt Marketo automatisch deze koppelingen tussen uw ingebouwde velden Dynamics en Marketo.  Marketo synchroniseert ook uw aangepaste velden op uw leads, accounts, opportunity en contactpersonen.

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
      <td>[!UICONTROL Microsoft Created Date]</td>
      <td>[!UICONTROL Created On]</td>
      <td>gemaakt</td>
    </tr>
    <tr>
      <td>[!UICONTROL Salutation]</td>
      <td>[!UICONTROL Salutation]</td>
      <td>aanhef</td>
    </tr>
    <tr>
      <td>[!UICONTROL First]</td>
      <td>[!UICONTROL First Name]</td>
      <td>firstname</td>
    </tr>
    <tr>
      <td>[!UICONTROL Middle]</td>
      <td>[!UICONTROL Middle Name]</td>
      <td>middlename</td>
    </tr>
    <tr>
      <td>[!UICONTROL Last]</td>
      <td>[!UICONTROL Last Name]</td>
      <td>lastname</td>
    </tr>
    <tr>
      <td>[!UICONTROL Email]</td>
      <td>[!UICONTROL Email]</td>
      <td>e-mailadres1</td>
    </tr>
    <tr>
      <td>[!UICONTROL Job Title]</td>
      <td>[!UICONTROL Job title]</td>
      <td>jobtitle</td>
    </tr>
    <tr>
      <td>[!UICONTROL Phone]</td>
      <td>[!UICONTROL Business Phone]</td>
      <td>phone1</td>
    </tr>
    <tr>
      <td>[!UICONTROL Mobile]</td>
      <td>[!UICONTROL Mobile Phone]</td>
      <td>mobiele telefoon</td>
    </tr>
    <tr>
      <td>[!UICONTROL Fax]</td>
      <td>[!UICONTROL Fax]</td>
      <td>fax</td>
    </tr>
    <tr>
      <td>[!UICONTROL Address]</td>
      <td>[!UICONTROL Street 1]</td>
      <td>address1_line1</td>
    </tr>
    <tr>
      <td>[!UICONTROL City]</td>
      <td>[!UICONTROL City]</td>
      <td>address1_city</td>
    </tr>
    <tr>
      <td>[!UICONTROL State]</td>
      <td>[!UICONTROL State/Province]</td>
      <td>address1_stateorProvince</td>
    </tr>
    <tr>
      <td>[!UICONTROL Country]</td>
      <td>[!UICONTROL Country/Region]</td>
      <td>address1_country</td>
    </tr>
    <tr>
      <td>[!UICONTROL Postal Code]</td>
      <td>[!UICONTROL Zip/Postal Code]</td>
      <td>address1_postalcode</td>
    </tr>
    <tr>
      <td>[!UICONTROL Person Source]</td>
      <td>[!UICONTROL Lead Source]</td>
      <td>leadsourcecode</td>
    </tr>
    <tr>
      <td>[!UICONTROL Person Status]</td>
      <td>[!UICONTROL Status]</td>
      <td>statecode</td>
    </tr>
    <tr>
      <td>[!UICONTROL Status Reason]</td>
      <td>[!UICONTROL Status Reason]</td>
      <td>statuscode</td>
    </tr>
    <tr>
      <td>[!UICONTROL Person Notes]</td>
      <td>[!UICONTROL Description]</td>
      <td>beschrijving</td>
    </tr>
    <tr>
      <td>[!UICONTROL Do Not Call]</td>
      <td>[!UICONTROL Do Not Allow Phone Calls]</td>
      <td>donotphone</td>
    </tr>
    <tr>
      <td>[!UICONTROL Unsubscribed]</td>
      <td>[!UICONTROL Do not bulk email]</td>
      <td>donotbulkemail</td>
    </tr>
    <tr>
      <td>[!UICONTROL Person Rating]</td>
      <td>[!UICONTROL Rating]</td>
      <td>leadquality code</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Address 2]</td>
      <td>[!UICONTROL Street 2]</td>
      <td>address1_line2</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Address 3]</td>
      <td>[!UICONTROL Street 3]</td>
      <td>address1_line3</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Do Not Email]</td>
      <td>[!UICONTROL Do Not Allow Emails]</td>
      <td>donotemail</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Do Not Fax]</td>
      <td>[!UICONTROL Do Not Allow Faxes]</td>
      <td>donotfax</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Do Not Send Marketing Material]</td>
      <td>[!UICONTROL Marketing Material]</td>
      <td>donotsendmm</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Home Phone]</td>
      <td>[!UICONTROL Home Phone]</td>
      <td>phone2</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Preferred Method Of Contact]</td>
      <td>[!UICONTROL Preferred Method of Contact]</td>
      <td>voorkeurscontactmethodiecode</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Topic]</td>
      <td>[!UICONTROL Topic]</td>
      <td>onderwerp</td>
    </tr>
    <tr>
      <td>[!UICONTROL Last interesting moment date]</td>
      <td>[!UICONTROL Last interesting moment date]</td>
      <td>mkt_lastInterestingstweenDate</td>
    </tr>
    <tr>
      <td>[!UICONTROL Last Interesting moment desc]</td>
      <td>[!UICONTROL Last Interesting moment desc]</td>
      <td>mkt_lastInterestingmomentdesc</td>
    </tr>
    <tr>
      <td>[!UICONTROL Last Interesting moment source]</td>
      <td>[!UICONTROL Last Interesting moment source]</td>
      <td>mkt_leadinterestingimpulsource</td>
    </tr>
    <tr>
      <td>[!UICONTROL Last interesting moment type]</td>
      <td>[!UICONTROL Last interesting moment type]</td>
      <td>mkt_lastInterestingstentype</td>
    </tr>
    <tr>
      <td>[!UICONTROL Company]</td>
      <td>[!UICONTROL Company Name]</td>
      <td>bedrijfsnaam</td>
    </tr>
    <tr>
      <td>[!UICONTROL Relative Score]</td>
      <td>[!UICONTROL Relative Score]</td>
      <td>mkt_relativescore</td>
    </tr>
    <tr>
      <td>[!UICONTROL Priority]</td>
      <td>[!UICONTROL Priority]</td>
      <td>mkt_priority</td>
    </tr>
    <tr>
      <td>[!UICONTROL Relative Urgency]</td>
      <td>[!UICONTROL Urgency]</td>
      <td>mkt_priority</td>
    </tr>
    <tr>
      <td>[!UICONTROL Subject]</td>
      <td>[!UICONTROL Topic]</td>
      <td>onderwerp</td>
    </tr>
    <tr>
      <td>[!UICONTROL Annual Revenue]</td>
      <td>[!UICONTROL Annual Revenue]</td>
      <td>omzet</td>
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
      <td>[!UICONTROL Owner] </td>
      <td>eigenaar</td>
    </tr>
    <tr>
      <td>[!UICONTROL Created On]</td>
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
      <td>[!UICONTROL Microsoft Created Date]</td>
      <td>[!UICONTROL Created On]</td>
      <td>gemaakt</td>
    </tr>
    <tr>
      <td>[!UICONTROL Salutation]</td>
      <td>[!UICONTROL Salutation]</td>
      <td>aanhef</td>
    </tr>
    <tr>
      <td>[!UICONTROL First]</td>
      <td>[!UICONTROL First Name]</td>
      <td>firstname</td>
    </tr>
    <tr>
      <td>[!UICONTROL Middle]</td>
      <td>[!UICONTROL Middle Name]</td>
      <td>middlename</td>
    </tr>
    <tr>
      <td>[!UICONTROL Last]</td>
      <td>[!UICONTROL Last Name]</td>
      <td>lastname</td>
    </tr>
    <tr>
      <td>[!UICONTROL Email]</td>
      <td>[!UICONTROL Email]</td>
      <td>e-mailadres1</td>
    </tr>
    <tr>
      <td>[!UICONTROL Job Title]</td>
      <td>[!UICONTROL Job Title]</td>
      <td>jobtitle</td>
    </tr>
    <tr>
      <td>[!UICONTROL Phone]</td>
      <td>[!UICONTROL Business Phone]</td>
      <td>phone1</td>
    </tr>
    <tr>
      <td>[!UICONTROL Mobile]</td>
      <td>[!UICONTROL Mobile Phone]</td>
      <td>mobiele telefoon</td>
    </tr>
    <tr>
      <td>[!UICONTROL Address]</td>
      <td>[!UICONTROL Address 1: Street 1]</td>
      <td>address1_line1</td>
    </tr>
    <tr>
      <td>[!UICONTROL City]</td>
      <td>[!UICONTROL Address 1: City]</td>
      <td>address1_city</td>
    </tr>
    <tr>
      <td>[!UICONTROL State]</td>
      <td>[!UICONTROL Address 1: State/Province]</td>
      <td>address1_stateorProvince</td>
    </tr>
    <tr>
      <td>[!UICONTROL Country]</td>
      <td>[!UICONTROL Address 1: Country/Region]</td>
      <td>address1_country</td>
    </tr>
    <tr>
      <td>[!UICONTROL Postal Code]</td>
      <td>[!UICONTROL Address 1: Zip/Postal Code]</td>
      <td>address1_postalcode</td>
    </tr>
    <tr>
      <td>[!UICONTROL Person Status]</td>
      <td>[!UICONTROL Status]</td>
      <td>statecode</td>
    </tr>
    <tr>
      <td>[!UICONTROL Status Reason]</td>
      <td>[!UICONTROL Status Reason]</td>
      <td>statuscode</td>
    </tr>
    <tr>
      <td>[!UICONTROL Do Not Call]</td>
      <td>[!UICONTROL Do Not Allow Phone Calls]</td>
      <td>donotphone</td>
    </tr>
    <tr>
      <td>[!UICONTROL Unsubscribed]</td>
      <td>[!UICONTROL Do not bulk email]</td>
      <td>donotbulkemail</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Address 2]</td>
      <td>[!UICONTROL Address 1: Street 2]</td>
      <td>address1_line2</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Address 3]</td>
      <td>[!UICONTROL Address 1: Street 3]</td>
      <td>address1_line3</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Do Not Email]</td>
      <td>[!UICONTROL Do Not Allow Emails]</td>
      <td>donotemail</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Home Phone]</td>
      <td>[!UICONTROL Home Phone]</td>
      <td>phone2</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Preferred Method Of Contact]</td>
      <td>[!UICONTROL Preferred Method Of Contact]</td>
      <td>voorkeurscontactmethodiecode</td>
    </tr>
    <tr>
      <td>[!UICONTROL Last interesting moment date]</td>
      <td>[!UICONTROL Last interesting moment date]</td>
      <td>mkt_lastInterestingstweenDate</td>
    </tr>
    <tr>
      <td>[!UICONTROL Last interesting moment type]</td>
      <td>[!UICONTROL Last interesting moment type]</td>
      <td>mkt_lastInterestingstentype</td>
    </tr>
    <tr>
      <td>[!UICONTROL Last Interesting moment source]</td>
      <td>[!UICONTROL Last Interesting moment source]</td>
      <td>mkt_leadinterestingimpulsource</td>
    </tr>
    <tr>
      <td>[!UICONTROL Last Interesting moment desc]</td>
      <td>[!UICONTROL Last Interesting moment desc]</td>
      <td>mkt_lastInterestingmomentdesc</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Do Not Send Marketing Material]</td>
      <td>[!UICONTROL Marketing Material]</td>
      <td>donotsendmm</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Do Not Fax]</td>
      <td>[!UICONTROL Microsoft Do Not Fax]</td>
      <td>donotfax</td>
    </tr>
    <tr>
      <td>[!UICONTROL Priority]</td>
      <td>[!UICONTROL Priority]</td>
      <td>mkt_priority</td>
    </tr>
    <tr>
      <td>[!UICONTROL Relative Urgency]</td>
      <td>[!UICONTROL Urgency]</td>
      <td>mkt_priority</td>
    </tr>
    <tr>
      <td>[!UICONTROL Relative Score]</td>
      <td>[!UICONTROL Relative Score]</td>
      <td>mkt_relativescore</td>
    </tr>
    <tr>
      <td>[!UICONTROL Person Notes]</td>
      <td>[!UICONTROL Description]</td>
      <td>beschrijving </td>
    </tr>
    <tr>
      <td>[!UICONTROL Person Score]</td>
      <td>[!UICONTROL Lead Score]</td>
      <td>mkt_leadscore</td>
    </tr>
    <tr>
      <td>[!UICONTROL Person Notes]</td>
      <td>[!UICONTROL Description]</td>
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
      <td>[!UICONTROL Owner] </td>
      <td>eigenaar</td>
    </tr>
    <tr>
      <td>[!UICONTROL Created On]</td>
      <td>gemaakt</td>
    </tr>
    <tr>
      <td>[!UICONTROL Company Name]</td>
      <td>ouderdier</td>
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
      <td>[!UICONTROL Account (a)]</td>
      <td>[!UICONTROL Account]</td>
      <td>verantwoording</td>
    </tr>
    <tr>
      <td>[!UICONTROL Billing Address]</td>
      <td>[!UICONTROL Address 1: Street 1]</td>
      <td>address1_line1</td>
    </tr>
    <tr>
      <td>[!UICONTROL Billing City]</td>
      <td>[!UICONTROL Address 1: City]</td>
      <td>address1_city</td>
    </tr>
    <tr>
      <td>[!UICONTROL Billing Country]</td>
      <td>[!UICONTROL Address 1: Country/Region]</td>
      <td>address1_country</td>
    </tr>
    <tr>
      <td>[!UICONTROL Billing Postal Code]</td>
      <td>[!UICONTROL Address 1: Zip/Postal Code]</td>
      <td>address1_postalcode</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Billing Address 2]</td>
      <td>[!UICONTROL Address 1: Street 2]</td>
      <td>address1_line2</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Billing Address 3]</td>
      <td>[!UICONTROL Address 1: Street 3]</td>
      <td>address1_line3</td>
    </tr>
    <tr>
      <td>[!UICONTROL Main Phone]</td>
      <td>[!UICONTROL Main Phone]</td>
      <td>phone1</td>
    </tr>
    <tr>
      <td>[!UICONTROL Business Type]</td>
      <td>[!UICONTROL Business Type]</td>
      <td>businesstyecode</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Account Number]</td>
      <td>[!UICONTROL Account Number]</td>
      <td>accountnummer</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Company Status]</td>
      <td>[!UICONTROL Status]</td>
      <td>statecode</td>
    </tr>
    <tr>
      <td>[!UICONTROL Annual Revenue]</td>
      <td>[!UICONTROL Annual Revenue]</td>
      <td>omzet</td>
    </tr>
    <tr>
      <td>[!UICONTROL Company Notes]</td>
      <td>[!UICONTROL Description]</td>
      <td>beschrijving</td>
    </tr>
    <tr>
      <td>[!UICONTROL Industry]</td>
      <td>[!UICONTROL Industry]</td>
      <td>industriële code</td>
    </tr>
    <tr>
      <td>[!UICONTROL SIC Code]</td>
      <td>[!UICONTROL SIC Code]</td>
      <td>sic</td>
    </tr>
    <tr>
      <td>[!UICONTROL Website]</td>
      <td>[!UICONTROL Website]</td>
      <td>website</td>
    </tr>
    <tr>
      <td>[!UICONTROL Num Employees]</td>
      <td>[!UICONTROL Number of Employees]</td>
      <td>aantal werknemers</td>
    </tr>
    <tr>
      <td>[!UICONTROL SIC Code]</td>
      <td>[!UICONTROL SIC Code]</td>
      <td>sic</td>
    </tr>
    <tr>
      <td>[!UICONTROL Company]</td>
      <td>[!UICONTROL Account Name]</td>
      <td>name</td>
    </tr>
    <tr>
      <td>[!UICONTROL Num Employees]</td>
      <td>[!UICONTROL Number of Employees]</td>
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
      <td>[!UICONTROL Owner] </td>
      <td>eigenaar</td>
    </tr>
    <tr>
      <td>[!UICONTROL Created On]</td>
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
      <td>[!UICONTROL Close Probability]</td>
      <td>[!UICONTROL Probabliity]</td>
      <td>waarschijnlijkheid</td>
    </tr>
    <tr>
      <td>[!UICONTROL Stage]</td>
      <td>[!UICONTROL Status]</td>
      <td>statecode</td>
    </tr>
    <tr>
      <td>[!UICONTROL Actual Close Date]</td>
      <td>[!UICONTROL Actual Close Date]</td>
      <td>actualclosed</td>
    </tr>
    <tr>
      <td>[!UICONTROL Name]</td>
      <td>[!UICONTROL Topic]</td>
      <td>name</td>
    </tr>
    <tr>
      <td>[!UICONTROL Estimated Value]</td>
      <td>[!UICONTROL Est. Revenue]</td>
      <td>estimatedValue</td>
    </tr>
    <tr>
      <td>[!UICONTROL Description]</td>
      <td>[!UICONTROL Description]</td>
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
      <td>[!UICONTROL Owner] </td>
      <td>eigenaar</td>
    </tr>
    <tr>
      <td>[!UICONTROL Opportunity]</td>
      <td>opportunityId</td>
    </tr>
    <tr>
      <td>[!UICONTROL Potential Customer]</td>
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
      <td>[!UICONTROL Microsoft Type]</td>
      <td>Lood of contactpersoon. Indien leeg, bestaat de lead alleen als een persoon in Marketo</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Created Date]</td>
      <td>Datum gemaakt in [!DNL MS Dynamics] (kan anders zijn dan Gemaakt in Marketo)</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft is Deleted]</td>
      <td>Persoon was in Microsoft, maar werd verwijderd en woont nu alleen in Marketo</td>
    </tr>
  </tbody>
</table>
