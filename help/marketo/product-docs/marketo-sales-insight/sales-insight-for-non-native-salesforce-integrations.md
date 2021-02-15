---
unique-page-id: 45417125
description: Verkoopoverzicht voor niet-native Salesforce-integratie - Marketo Docs - Productdocumentatie
title: Verkoopoverzicht voor niet-native Salesforce-integratie
translation-type: tm+mt
source-git-commit: 6ae882dddda220f7067babbe5a057eec82601abf
workflow-type: tm+mt
source-wordcount: '1269'
ht-degree: 0%

---


# Verkoopoverzicht voor niet-native Salesforce-integratie {#sales-insight-for-non-native-salesforce-integrations}

Als uw Marketo-account via een aangepaste of niet-native integratie is verbonden met Salesforce, gebruikt u dit document om Sales Insight te configureren.

>[!PREREQUISITES]
>
>* Bereik uit aan uw Manager van het Succes van de Klant om de &quot;niet-inheemse eigenschap MSI&quot;voor uw instantie van het Marketo toe te laten.
>* Een Salesforce-account met MSI Package-up.
>* Marketo REST API [met succes opstelling](https://developers.marketo.com/rest-api/). De belichte CRUD-API&#39;s vormen de basis voor het uitvoeren van de niet-native synchronisatie.
>* Lees [dit blogbericht](https://developers.marketo.com/blog/create-and-associate-leads-companies-and-opportunities-with-the-marketo-rest-api/) om meer inzicht te krijgen in het object en de relaties.
>* Stel Salesforce-objecten in om de algemeen unieke id weer te geven voor 18 hoofdletters en kleine letters in plaats van voor 15 hoofdletters en kleine letters.

>



>[!NOTE]
>
>De configuratie van de REST API in het Admin Panel van Marketo MSI kan niet voor de niet-inheemse synchronisatie worden gebruikt.

## Voor geslaagde niet-native synchronisatie voor MSI is het volgende {#successful-non-native-sync-for-msi-requires-the-following} vereist

1. Synchroniseer de Salesforce-verkoopgebruiker naar Marketo.

   De verkoopgebruiker van Salesforce is een externe gebruiker die de Leads/Contacten in Salesforce bezit. Een verkoper van de Marketo moet voor de Gebruiker van de Verkoop van Salesforce worden bevestigd. Het veld *externalSalesPersonId* is verplicht voor de invoeging van de verkoper.

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td><strong>Veld verkoper markeren</strong></td> 
   <td><strong>Verkoopgebruikersveld Salesforce</strong></td> 
   <td><strong>Beschrijving</strong></td> 
  </tr> 
  <tr> 
   <td>externalSalesPersonId</td> 
   <td>Niet-gevoelige wereldwijde unieke identificatiecode voor verkoopgevallen van Salesforce</td> 
   <td><p>Identificeert het dossier van de Verkoper van de Marketo aan een extern voorwerp van de Gebruiker van de Verkoop van Salesforce.</p><p>Het is verplicht dat de persoon van de Verkoop eerst wordt gesynchroniseerd alvorens de andere voorwerpen te synchroniseren zodat de juiste verhoudingen zullen worden gecreeerd.</p></td> 
  </tr> 
 </tbody> 
</table>

API-documentatie voor Verkooppersoon: [https://developers.marketo.com/rest-api/lead-database/sales-persons/](https://developers.marketo.com/rest-api/lead-database/sales-persons/)\
API-documentatie voor het synchroniseren van de verkoper: [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Sales_Personen/syncSalesPersonenUsingPOST](https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Sales_Personen/syncSalesPersonenUsingPOST)

1. Synchroniseer de Salesforce-accounts met Marketo.

   Een Marketo Company zal voor de Rekening van Salesforce moeten worden opgenomen. De *externalCompanyId* en *externalSalesPersonId* gebieden worden verplicht voor de opnemer van het Bedrijf.

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td><strong>Veld Marketo Company</strong></td> 
   <td><strong>Salesforce-accountveld</strong></td> 
   <td><strong>Beschrijving</strong></td> 
  </tr> 
  <tr> 
   <td>externalCompanyId</td> 
   <td>Niet-gevoelige algemene unieke id voor Salesforce-account</td> 
   <td>Identificeert een verslag van het Bedrijf van de Marketo aan een extern voorwerp van de Rekening Salesforce.</td> 
  </tr> 
  <tr> 
   <td>externalSalesPersonId</td> 
   <td>Niet-gevoelige wereldwijde unieke identificatiecode voor verkoopgevallen van Salesforce</td> 
   <td>Identificeert een verslag van het Bedrijf van de Marketo aan een extern voorwerp van de Gebruiker van de Verkoop Salesforce dat de Rekeningeigenaar is.<br><br>Ook gebruikt binnen Marketo om het Bedrijf aan de Persoon van de Verkoop te associëren die het verslag van het Bedrijf bezit. De verkoper moet eerst worden gesynchroniseerd voordat dit veld wordt ingesteld.</td> 
  </tr> 
 </tbody> 
</table>

API-documentatie voor bedrijven: [https://developers.marketo.com/rest-api/lead-database/companies/](https://developers.marketo.com/rest-api/lead-database/companies/)\
`API documentation for syncing Companies:  [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Companies/syncCompaniesUsingPOST](https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Companies/syncCompaniesUsingPOST)`

1. Synchroniseer de Salesforce-contacten met Marketo.

   U moet een Marketo-lead bijwerken voor de Salesforce-lead/contactpersoon. De *externalPersonId*, *externalSalesPersonId*, en *externalCompanyId* gebieden zijn verplicht voor de bovenkant van de Lood.

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td><strong>Veld voor regelafstand markeren</strong></td> 
   <td><strong>Salesforce-lead/contactveld</strong></td> 
   <td><strong>Beschrijving</strong></td> 
  </tr> 
  <tr> 
   <td>externalPersonId</td> 
   <td>Salesforce lead/Contact case-insensitive global unique identifier</td> 
   <td>Identificeert de Marketo Lead-record naar een extern Salesforce Lead/Contact-object.<br><br>Dit is een nieuw gebied dat voor MSI niet-Native wordt geïntroduceerd.</td> 
  </tr> 
  <tr> 
   <td>externalSalesPersonId</td> 
   <td>Niet-gevoelige wereldwijde unieke identificatiecode voor verkoopgevallen van Salesforce</td> 
   <td>Identificeert het externe voorwerp van de Gebruiker van de Verkoop Salesforce die dit Lood/Contact bezit.<br><br>De lead heeft ook betrekking op de Sales Person in Marketo. De verkoper moet eerst correct worden gesynchroniseerd.</td> 
  </tr> 
  <tr> 
   <td>externalCompanyId</td> 
   <td>Niet-gevoelige algemene unieke id voor Salesforce-account</td> 
   <td>Hiermee wordt het externe Salesforce-accountobject aangegeven waartoe de lead/contactpersoon behoort.<br><br>Heeft ook betrekking op het loodrecord van een Bedrijf in Marketo. U moet de Salesforce-account eerst correct synchroniseren.</td> 
  </tr> 
 </tbody> 
</table>

API-documentatie voor leads: [`https://developers.marketo.com/rest-api/lead-database/leads/`](https://developers.marketo.com/rest-api/lead-database/leads/)\
API-documentatie voor het synchroniseren van leads:  [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Leads/syncLeadUsingPOST](https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Leads/syncLeadUsingPOST)

1. Synchroniseer Salesforce Opportunity op Marketo.

   U moet een Marketo Opportunity voor de Salesforce Opportunity handhaven. De *externalOpportunityId*, *externalCompanyId*, en *externalSalesPersonId* gebieden zijn verplicht voor de controle van de Opportunity.

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td><strong>Objectveld Marketo Opportunity</strong></td> 
   <td><strong>Salesforce Opportunity Object Field</strong></td> 
   <td><strong>Beschrijving</strong></td> 
  </tr> 
  <tr> 
   <td>externalOpportunityId</td> 
   <td>Salesforce lead/Contact case-insensitive global unique identifier</td> 
   <td>Hiermee wordt de Marketo Opportunity-record geïdentificeerd voor een extern Salesforce Opportunity-object.</td> 
  </tr> 
  <tr> 
   <td>externalCompanyId</td> 
   <td>Niet-gevoelige algemene unieke id voor Salesforce-account</td> 
   <td>Identificeert het externe Salesforce-accountobject waartoe deze Opportunity behoort. <br><br>U moet de Salesforce-account eerst correct synchroniseren.</td> 
  </tr> 
  <tr> 
   <td>externalSalesPersonId</td> 
   <td>Niet-gevoelige wereldwijde unieke identificatiecode voor verkoopgevallen van Salesforce</td> 
   <td>Identificeert het externe voorwerp van de Gebruiker van de Verkoop Salesforce die deze Kans bezit. </td> 
  </tr> 
 </tbody> 
</table>

API-documentatie voor Opportunity: [`https://developers.marketo.com/rest-api/lead-database/opportunities/`](https://developers.marketo.com/rest-api/lead-database/opportunities/)\
`API documentation for syncing Opportunities:  [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Opportunities/syncOpportunitiesUsingPOST](https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Opportunities/syncOpportunitiesUsingPOST)`

1. Synchroniseer Salesforce-contactrollen naar Marketo.

   De Rollen van het Contact van Salesforce voor een Kans van Salesforce kunnen dan via de Rol van de Kans van de Marketo worden gesynchroniseerd. In de opportunityrolrecord worden de velden *externalOpportunityId*, *rol* en *leadId* verplicht.

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td><strong>Rolveld Marketo Opportunity</strong></td> 
   <td><strong>Salesforce-veld Contactrol</strong></td> 
   <td><strong>Beschrijving</strong></td> 
  </tr> 
  <tr> 
   <td>externalOpportunityId</td> 
   <td>Niet-hoofdlettergevoelig algemeen unieke id voor Salesforce Opportunity</td> 
   <td>Hiermee wordt de rol Marketo Opportunity voor een extern Salesforce Opportunity-object geïdentificeerd.<br><br>De Salesforce Opportunity moet eerst correct worden gesynchroniseerd.</td> 
  </tr> 
  <tr> 
   <td>leadId</td> 
   <td>N.v.t. zou dit een Marketo Lead ID zijn</td> 
   <td>Dit zou de Marketo Lead-id van de gesynchroniseerde Salesforce-contactpersoon zijn.<br><br>Zodra het contact in Marketo wordt gesynchroniseerd, kunt u het geval-ongevoelige globaal unieke herkenningsteken van het Contact Salesforce gebruiken als externalPersonId en vraag voor de Lood van het Marketo gebruikend de REST API van de Marketo.</td> 
  </tr> 
  <tr> 
   <td>rol</td> 
   <td>Het veld Rol voor de Salesforce-contactpersoon</td> 
   <td>Beschrijft de rol van het contact voor deze kans.</td> 
  </tr> 
 </tbody> 
</table>

API-documentatie voor Opportunity: [`https://developers.marketo.com/rest-api/lead-database/opportunities/`](https://developers.marketo.com/rest-api/lead-database/opportunities/)\
`API documentation for syncing Opportunities:  [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Opportunities/syncOpportunitiesUsingPOST](https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Opportunities/syncOpportunitiesUsingPOST)`

1. Synchroniseer de velden Laatste interessant moment/MSI-score naar SFDC.

   Zodra uw voorwerpen Salesforce correct aan Marketo worden gesynchroniseerd, kunt u uit de eigenschappen MSI voordeel halen. De velden MSI Last Interesting Moment/Scoring worden weergegeven in de REST API voor leads. Deze velden worden berekend door MSI en zijn alleen-lezen.

   De velden Laatste interessante momenten/Scores van een Marketo Lead moeten regelmatig worden gesynchroniseerd met Salesforce met behulp van het REST API Lead-eindpunt. Vraag dit eindpunt voor een Lood van de Marketo gebruikend *externalPersonId* als filterType en het overgaan in Salesforce leiden GUID als filterValue.

   | GET /rest/v1/leads.json?filterType=externalPersonId&amp;filterValues=salesforceLeadId1,salesforceLeadId2 |
   |---|

   Vervolgens kunt u de waarden van deze velden gebruiken om te synchroniseren met het Salesforce-object Lead/Contact.

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td><strong>Veld voor regelafstand markeren</strong></td> 
   <td><strong>Salesforce-lead/contactveld</strong></td> 
   <td><strong>Beschrijving</strong></td> 
  </tr> 
  <tr> 
   <td>msiLastInterestingMomentType</td> 
   <td>Label: Laatste interessant momentype<br>Naam: Last_Interesting_Moment_Type__c</td> 
   <td>Type van het laatste interessante moment voor de lead</td> 
  </tr> 
  <tr> 
   <td>msiLastInterestingMomentDate</td> 
   <td><p>Label: Datum laatste interessant moment</p><p>Naam: Last_Interesting_Moment_Date__c</p></td> 
   <td>Datum van het laatste interessante moment voor de lead</td> 
  </tr> 
  <tr> 
   <td>msiLastInterestingMomentDesc</td> 
   <td><p>Label: Beschrijving van laatste interessant moment</p><p>Naam: Last_Interesting_Moment_Desc__c</p></td> 
   <td>Beschrijving van het laatste interessante moment voor de lead</td> 
  </tr> 
  <tr> 
   <td>msiLastInterestingMomentSource</td> 
   <td><p>Label: Laatste interessante mompbron</p><p>Naam: Last_Interesting_Moment_Source__c</p></td> 
   <td>Bron van het laatste interessante moment voor de lead</td> 
  </tr> 
  <tr> 
   <td>prioriteit</td> 
   <td><p>Label: Betrokkenheid</p><p>Naam: Priority_c</p></td> 
   <td>Prioriteit van de lead</td> 
  </tr> 
  <tr> 
   <td>relativeUrency</td> 
   <td><p>Label: Relatieve urgentiewaarde</p><p>Naam: Urence_Value_c</p></td> 
   <td>Relatieve urgentie van de leider</td> 
  </tr> 
  <tr> 
   <td>relativeScoring</td> 
   <td><p>Label: Relatieve score</p><p>Naam: Relative_Score_Value__c</p></td> 
   <td>Relatieve score van de lead</td> 
  </tr> 
 </tbody> 
</table>

Documentatie voor de LEIDREST API:  [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Leads/getLeadByIdUsingGET](https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Leads/getLeadByIdUsingGET).

Een correct gebruik van de externe velden is van wezenlijk belang voor een geslaagde niet-native synchronisatie. Als u gegevens in sommige weergaven niet ziet, is het waarschijnlijk dat een bepaald veld niet correct is gesynchroniseerd. Als de activiteiten en interessante momenten van een lead bijvoorbeeld niet worden weergegeven wanneer u de MSI-widget onder hun account bekijkt, is het waarschijnlijk dat het bedrijf van de lead of de account niet correct is gesynchroniseerd. Als u een GET-aanvraag voor deze lead uitvoert terwijl u de externe velden opgeeft, kunt u controleren of de lead correct is gesynchroniseerd. Bovendien moet de e-mail voor de externe verkoper in Marketo overeenkomen met de e-mail voor die gebruiker in Salesforce. Gegevens worden mogelijk niet weergegeven op het tabblad Marketo in Salesforce als de e-mails niet overeenkomen.

