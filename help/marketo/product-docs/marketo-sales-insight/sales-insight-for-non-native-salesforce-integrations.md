---
unique-page-id: 45417125
description: Verkoopoverzicht voor niet-native Salesforce-integratie - Marketo Docs - Productdocumentatie
title: Verkoopoverzicht voor niet-native Salesforce-integratie
exl-id: a771ecdf-c610-44e4-9e93-7fdcc9d79f4b
source-git-commit: 73c5375c6e2ec3b2dce09595be1f61f302ff4c25
workflow-type: tm+mt
source-wordcount: '1300'
ht-degree: 0%

---

# Verkoopoverzicht voor niet-native Salesforce-integratie {#sales-insight-for-non-native-salesforce-integrations}

Als uw Marketo-account op Salesforce is aangesloten via een aangepaste of niet-native integratie, gebruikt u dit document om Sales Insight te configureren.

>[!PREREQUISITES]
>
>* De functie &quot;Niet-native MSI&quot; die voor uw Marketo-instantie is ingeschakeld voordat u MSI instelt (als dit niet het geval is en u de functie al hebt aangeschaft, neemt u contact op met [Marketo Support](https://nation.marketo.com/t5/support/ct-p/Support) - als u deze functie nog niet hebt aangeschaft, neemt u contact op met uw Customer Success Manager).
>* Een Salesforce-account met [MSI Package set up](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md).
>* Marketo REST API [is correct ingesteld](https://developers.marketo.com/rest-api/). De belichte CRUD-API&#39;s vormen de basis voor het uitvoeren van de niet-native synchronisatie.
>* Lees [dit blogbericht](https://developers.marketo.com/blog/create-and-associate-leads-companies-and-opportunities-with-the-marketo-rest-api/) om meer inzicht te krijgen in het object en de relaties.
>* Stel Salesforce-objecten in om de algemeen unieke id weer te geven voor 18 hoofdletters en kleine letters in plaats van voor 15 hoofdletters en kleine letters.


>[!NOTE]
>
>De configuratie van de REST API in het deelvenster Marketo MSI Admin kan niet worden gebruikt voor de niet-native synchronisatie.

## Voor een geslaagde externe synchronisatie van MSI is het volgende vereist {#successful-non-native-sync-for-msi-requires-the-following}

1. Synchroniseer de verkoopgebruiker van Salesforce naar Marketo.

   De verkoopgebruiker van Salesforce is een externe gebruiker die de Leads/Contacten in Salesforce bezit. Een Marketo-verkoper moet worden geüpserd voor de verkoper van Salesforce. Het veld *externalSalesPersonId* is verplicht voor de invoeging van de verkoper.

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td><strong>Veld Marketo-verkoper</strong></td> 
   <td><strong>Verkoopgebruikersveld Salesforce</strong></td> 
   <td><strong>Beschrijving</strong></td> 
  </tr> 
  <tr> 
   <td>externalSalesPersonId</td> 
   <td>Niet-gevoelige wereldwijde unieke identificatiecode voor verkoopgevallen van Salesforce</td> 
   <td><p>Hiermee wordt de Marketo Sales Person-record geïdentificeerd voor een extern Salesforce Sales-object.</p><p>Het is verplicht dat de persoon van de Verkoop eerst wordt gesynchroniseerd alvorens de andere voorwerpen te synchroniseren zodat de juiste verhoudingen zullen worden gecreeerd.</p></td> 
  </tr> 
 </tbody> 
</table>

API-documentatie voor Verkooppersoon: [https://developers.marketo.com/rest-api/lead-database/sales-persons/](https://developers.marketo.com/rest-api/lead-database/sales-persons/)\
API-documentatie voor het synchroniseren van de verkoper: [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Sales_Personen/syncSalesPersonenUsingPOST](https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Sales_Personen/syncSalesPersonenUsingPOST)

1. Synchroniseer de Salesforce-accounts met Marketo.

   Een Marketo Company moet worden geüpserd voor de Salesforce-account. De _externalCompanyId_ en _externalSalesPersonId_ gebieden worden verplicht voor de opnemer van het Bedrijf.

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td><strong>Marketo Company Field</strong></td> 
   <td><strong>Salesforce-accountveld</strong></td> 
   <td><strong>Beschrijving</strong></td> 
  </tr> 
  <tr> 
   <td>externalCompanyId</td> 
   <td>Niet-gevoelige algemene unieke id voor Salesforce-account</td> 
   <td>Hiermee wordt een Marketo Company-record geïdentificeerd voor een extern Salesforce-accountobject.</td> 
  </tr> 
  <tr> 
   <td>externalSalesPersonId</td> 
   <td>Niet-gevoelige wereldwijde unieke identificatiecode voor verkoopgevallen van Salesforce</td> 
   <td>Hiermee wordt een Marketo Company-record geïdentificeerd voor een extern Salesforce Sales-object dat de eigenaar van de account is.<br><br>Wordt ook binnen Marketo gebruikt om het bedrijf te koppelen aan de verkoper die eigenaar is van het bedrijfsrecord. De verkoper moet eerst worden gesynchroniseerd voordat dit veld wordt ingesteld.</td> 
  </tr> 
 </tbody> 
</table>

API-documentatie voor bedrijven: [https://developers.marketo.com/rest-api/lead-database/companies/](https://developers.marketo.com/rest-api/lead-database/companies/)\
`API documentation for syncing Companies:  [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Companies/syncCompaniesUsingPOST](https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Companies/syncCompaniesUsingPOST)`

1. Synchroniseer de Salesforce-leads/contactpersonen met Marketo.

   U dient een Marketo-lead bij te voegen voor de Salesforce-lead/contactpersoon. De _externalPersonId_, _externalSalesPersonId_, en _externalCompanyId_ gebieden zijn verplicht voor de bovenkant van de Lood.

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td><strong>Marketo Lead Field</strong></td> 
   <td><strong>Salesforce-lead/contactveld</strong></td> 
   <td><strong>Beschrijving</strong></td> 
  </tr> 
  <tr> 
   <td>externalPersonId</td> 
   <td>Salesforce lead/Contact case-insensitive global unique identifier</td> 
   <td>Hiermee wordt de Marketo Lead-record geïdentificeerd voor een extern Salesforce Lead/Contact-object.<br><br>Dit is een nieuw gebied dat voor MSI niet-Native wordt geïntroduceerd.</td> 
  </tr> 
  <tr> 
   <td>externalSalesPersonId</td> 
   <td>Niet-gevoelige wereldwijde unieke identificatiecode voor verkoopgevallen van Salesforce</td> 
   <td>Identificeert het externe voorwerp van de Gebruiker van de Verkoop Salesforce die dit Lood/Contact bezit.<br><br>De lead heeft ook betrekking op de Sales Person in Marketo. De verkoper moet eerst correct worden gesynchroniseerd.</td> 
  </tr> 
  <tr> 
   <td>externalCompanyId</td> 
   <td>Niet-gevoelige algemene unieke id voor Salesforce-account</td> 
   <td>Hiermee wordt het externe Salesforce-accountobject aangegeven waartoe de lead/contactpersoon behoort.<br><br>Heeft ook betrekking op de loodrecord van een bedrijf in Marketo. U moet de Salesforce-account eerst correct synchroniseren.</td> 
  </tr> 
 </tbody> 
</table>

API-documentatie voor leads: [`https://developers.marketo.com/rest-api/lead-database/leads/`](https://developers.marketo.com/rest-api/lead-database/leads/)\
API-documentatie voor het synchroniseren van leads:  [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Leads/syncLeadUsingPOST](https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Leads/syncLeadUsingPOST)

1. Synchroniseer Salesforce Opportunity op Marketo.

   U moet een Marketo Opportunity voor de Salesforce Opportunity handhaven. De _externalOpportunityId_, _externalCompanyId_, en _externalSalesPersonId_ gebieden zijn verplicht voor de controle van de Opportunity.

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td><strong>Veld Marketo Opportunity-object</strong></td> 
   <td><strong>Salesforce Opportunity Object Field</strong></td> 
   <td><strong>Beschrijving</strong></td> 
  </tr> 
  <tr> 
   <td>externalOpportunityId</td> 
   <td>Salesforce lead/Contact case-insensitive global unique identifier</td> 
   <td>Identificeert de opportunityrecord van Marketo naar een extern Salesforce Opportunity-object.</td> 
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

   De Rollen van het Contact van Salesforce voor een Kans van Salesforce kunnen dan via de Rol van de Kans van Marketo worden gesynchroniseerd. In de opportunityrolrecord worden de velden _externalOpportunityId_, _rol_ en _leadId_ verplicht.

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td><strong>Marketo Opportunity Role Field</strong></td> 
   <td><strong>Salesforce-veld Contactrol</strong></td> 
   <td><strong>Beschrijving</strong></td> 
  </tr> 
  <tr> 
   <td>externalOpportunityId</td> 
   <td>Niet-hoofdlettergevoelig algemeen unieke id voor Salesforce Opportunity</td> 
   <td>Identificeert de Rol van de Kans van Marketo aan een extern voorwerp van de Kans van Salesforce.<br><br>De Salesforce Opportunity moet eerst correct worden gesynchroniseerd.</td> 
  </tr> 
  <tr> 
   <td>leadId</td> 
   <td>N.v.t., dit zou een Marketo Lead ID zijn</td> 
   <td>Dit zou de Marketo Lead-id van de gesynchroniseerde Salesforce-contactpersoon zijn.<br><br>Zodra het contact in Marketo wordt gesynchroniseerd, kunt u het geval-ongevoelige globale uniek herkenningsteken van het Contact van Salesforce gebruiken als externalPersonId en vraag voor de Lood van Marketo gebruikend Marketo REST API.</td> 
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

   Zodra uw Salesforce-objecten correct zijn gesynchroniseerd met Marketo, kunt u de MSI-functies benutten. De velden MSI Last Interesting Moment/Scoring worden weergegeven in de REST API voor leads. Deze velden worden berekend door MSI en zijn alleen-lezen.

   De velden Laatste interessante momenten/scores van een Marketo-lead moeten regelmatig worden gesynchroniseerd met Salesforce met behulp van het REST API-eindpunt Lead. Vraag dit eindpunt voor een Lood van Marketo gebruikend _externalPersonId_ als filterType en het overgaan in Salesforce Lood GUID als filterValue.

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
   <td><strong>Marketo Lead Field</strong></td> 
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

Documentatie voor de LEIDREST API: [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Leads/getLeadByIdUsingGET](https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Leads/getLeadByIdUsingGET).

Een correct gebruik van de externe velden is van wezenlijk belang voor een geslaagde niet-native synchronisatie. Als u gegevens in sommige weergaven niet ziet, is het waarschijnlijk dat een bepaald veld niet correct is gesynchroniseerd. Als de activiteiten en interessante momenten van een lead bijvoorbeeld niet worden weergegeven wanneer u de MSI-widget onder hun account bekijkt, is het waarschijnlijk dat het bedrijf van de lead of de account niet correct is gesynchroniseerd. Als u een GET-aanvraag voor deze lead uitvoert terwijl u de externe velden opgeeft, kunt u controleren of de lead correct is gesynchroniseerd. Bovendien moet de e-mail voor de externe verkoper in Marketo overeenkomen met de e-mail voor die gebruiker in Salesforce. Gegevens worden mogelijk niet weergegeven op het tabblad Marketo in Salesforce als de e-mails niet overeenkomen.
