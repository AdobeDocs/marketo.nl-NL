---
description: Verkoopoverzicht voor niet-native integratie van MS Dynamics - Marketo Docs - Productdocumentatie
title: Verkoopoverzicht voor niet-native integratie van MS Dynamics
exl-id: 07613ff8-b197-4a3d-88e9-720b68a6b8da
feature: Marketo Sales Insights
source-git-commit: 2b610cc3486b745212b0b1f36018a83214d7ecd7
workflow-type: tm+mt
source-wordcount: '1258'
ht-degree: 0%

---

# Verkoopoverzicht voor niet-native integratie van MS Dynamics {#sales-insight-for-non-native-ms-dynamics-integrations}

Als uw Adobe Marketo Engage-account via een aangepaste of niet-native integratie verbinding heeft met MS Dynamics, gebruikt u dit artikel om Sales Insight te configureren.

>[!PREREQUISITES]
>
>* De functie &#39;Niet-native MSI&#39; die is ingeschakeld voor uw Marketo-instantie voordat u MSI instelt. Als dit niet het geval is en u de functie al hebt aangeschaft, neemt u contact op met [Marketo-ondersteuning](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"}. Neem contact op met het accountteam van de Adobe (uw accountmanager) als u deze functie nog niet hebt aangeschaft.
>* Downloaden [MSI-pakket voor aangepaste synchronisatie](https://mktg-cdn.marketo.com/community/MarketoSalesInsight_NonNative.zip){target="_blank"}.
>* Een abonnement van de Dynamiek van MS met Opstelling MSI (wij steunen slechts [Dynamics Online](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/install-and-configure-marketo-sales-insight-in-microsoft-dynamics-online.md){target="_blank"} op dat moment).
>* MARKETO REST API [met succes ingesteld](https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/rest/rest-api){target="_blank"}. De belichte CRUD-API&#39;s vormen de basis voor het uitvoeren van de niet-native synchronisatie.
>* Lezen [dit blogbericht](https://developers.marketo.com/blog/create-and-associate-leads-companies-and-opportunities-with-the-marketo-rest-api/){target="_blank"} om inzicht te krijgen in het object en de relaties.

## Voor een geslaagde externe synchronisatie van MSI is het volgende vereist {#successful-non-native-sync-for-msi-requires-the-following}

1. Synchroniseer de gebruiker van de Verkoop van de Dynamica van MS aan Marketo.

   De gebruiker van de Verkoop van de Verkoop van de Dynamica van MS is een externe gebruiker die de Leads/Contacten in de Dynamiek van MS bezit. Een Marketo-verkoper moet worden geüpserd voor de gebruiker van de Verkoop van de Dynamica van MS. Het veld externalSalesPersonId is verplicht voor het upsert van de verkoper.

   <table> 
    <colgroup> 
     <col> 
     <col> 
     <col> 
    </colgroup> 
    <tbody> 
     <tr> 
      <td><strong>Veld Marketo-verkoper</strong></td> 
      <td><strong>Gebruikersveld MS Dynamics</strong></td> 
      <td><strong>Beschrijving</strong></td> 
     </tr> 
     <tr> 
      <td>externalSalesPersonId</td> 
      <td>MS Dynamics User case-insensitive global unique identifier</td> 
      <td><p>Hiermee wordt de Marketo Sales Person-record geïdentificeerd voor een extern MS Dynamics User-object.</p><p>Het is verplicht dat de persoon van de Verkoop eerst wordt gesynchroniseerd alvorens de andere voorwerpen te synchroniseren zodat de juiste verhoudingen zullen worden gecreeerd.</p></td> 
     </tr> 
    </tbody> 
   </table>

   * [API-documentatie voor Verkooppersoon](https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/rest/lead-database/sales-persons){target="_blank"}
   * [API-documentatie voor het synchroniseren van de verkoper](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Sales-Persons/operation/syncSalesPersonsUsingPOST){target="_blank"}

1. Synchroniseer MS Dynamics Accounts naar Marketo.

   Een Marketo Company zal voor de Rekening van de Dynamiek van MS moeten worden geüpserd. De _externalCompanyId_ en _externalSalesPersonId_ de gebieden worden verplicht voor de opnemer van het Bedrijf.

   <table> 
    <colgroup> 
     <col> 
     <col> 
     <col> 
    </colgroup> 
    <tbody> 
     <tr> 
      <td><strong>Marketo Company Field</strong></td> 
      <td><strong>Veld MS Dynamics-account</strong></td> 
      <td><strong>Beschrijving</strong></td> 
     </tr> 
     <tr> 
      <td>externalCompanyId</td> 
      <td>MS Dynamics Account is niet hoofdlettergevoelig wereldwijd unieke id</td> 
      <td>Hiermee wordt een Marketo Company-record geïdentificeerd voor een extern MS Dynamics Account-object.</td> 
     </tr> 
     <tr> 
      <td>externalSalesPersonId</td> 
      <td>MS Dynamics Sales User case-insensitive global unique identifier</td> 
      <td>Hiermee wordt een Marketo Company-record geïdentificeerd voor een extern MS Dynamics Sales-object dat de eigenaar van de account is.<br><br>Wordt ook binnen Marketo gebruikt om het bedrijf te koppelen aan de verkoper die eigenaar is van het bedrijfsrecord. De verkoper moet eerst worden gesynchroniseerd voordat dit veld wordt ingesteld.</td> 
     </tr> 
    </tbody> 
   </table>

   * API-documentatie voor bedrijven: [https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/rest/lead-database/companies](https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/rest/lead-database/companies){target="_blank"}
   * API-documentatie voor synchroniserende bedrijven: [https://developer.adobe.com/marketo-apis/api/mapi/#tag/Sales-Persons/operation/syncSalesPersonsUsingPOST](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Sales-Persons/operation/syncSalesPersonsUsingPOST){target="_blank"}

1. Synchroniseer de leads/contactpersonen voor MS Dynamics met Marketo.

   U dient een Marketo-lead bij te voegen voor MS Dynamics Lead/Contact. De _externalPersonId_, _externalSalesPersonId_, en _externalCompanyId_ velden zijn verplicht voor de opname van de lead.

   <table> 
    <colgroup> 
     <col> 
     <col> 
     <col> 
    </colgroup> 
    <tbody> 
     <tr> 
      <td><strong>Marketo Lead Field</strong></td> 
      <td><strong>MS Dynamics Lead/Contact Field</strong></td> 
      <td><strong>Beschrijving</strong></td> 
     </tr> 
     <tr> 
      <td>externalPersonId</td> 
      <td>MS Dynamics Lead/Contact case-insensitive global unique identifier</td> 
      <td>Hiermee wordt de Marketo Lead-record geïdentificeerd voor een extern MS Dynamics Lead/Contact-object.<br><br>Dit is een nieuw gebied dat voor MSI niet-Native wordt geïntroduceerd.</td> 
     </tr> 
     <tr> 
      <td>externalSalesPersonId</td> 
      <td>MS Dynamics Sales User case-insensitive global unique identifier</td> 
      <td>Identificeert het externe voorwerp van de Gebruiker van de Verkoop van de Dynamiek van MS die dit Lood/Contact bezit.<br><br>De lead heeft ook betrekking op de Sales Person in Marketo. De verkoper moet eerst correct worden gesynchroniseerd.</td> 
     </tr> 
     <tr> 
      <td>externalCompanyId</td> 
      <td>MS Dynamics Account is niet hoofdlettergevoelig wereldwijd unieke id</td> 
      <td>Hiermee wordt het externe MS Dynamics Account-object aangegeven waartoe de lead/contactpersoon behoort.<br><br>Heeft ook betrekking op de loodrecord van een bedrijf in Marketo. U moet de MS Dynamics Account eerst correct synchroniseren.</td> 
     </tr> 
    </tbody> 
   </table>

   * API-documentatie voor leads: [https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/rest/lead-database/lead-database](https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/rest/lead-database/lead-database){target="_blank"}
   * API-documentatie voor het synchroniseren van leads: [https://developer.adobe.com/marketo-apis/api/mapi/#tag/Leads/operation/syncLeadUsingPOST](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Leads/operation/syncLeadUsingPOST){target="_blank"}

1. Synchroniseer MS Dynamics Opportunity naar Marketo.

   U moet een Marketo Opportunity voor MS Dynamics Opportunity handhaven. De _externalOpportunityId_, _externalCompanyId_, en _externalSalesPersonId_ velden zijn verplicht voor de opname van de Opportunity.

   <table> 
    <colgroup> 
     <col> 
     <col> 
     <col> 
    </colgroup> 
    <tbody> 
     <tr> 
      <td><strong>Veld Marketo Opportunity-object</strong></td> 
      <td><strong>Objectveld MS Dynamics Opportunity</strong></td> 
      <td><strong>Beschrijving</strong></td> 
     </tr> 
     <tr> 
      <td>externalOpportunityId</td> 
      <td>MS Dynamics Lead/Contact case-insensitive global unique identifier</td> 
      <td>Hiermee wordt de opportunityrecord van Marketo geïdentificeerd voor een extern MS Dynamics Opportunity-object.</td> 
     </tr> 
     <tr> 
      <td>externalCompanyId</td> 
      <td>MS Dynamics Account is niet hoofdlettergevoelig wereldwijd unieke id</td> 
      <td>Hiermee wordt het externe MS Dynamics Account-object aangegeven waartoe deze opportunity behoort. <br><br>U moet de MS Dynamics Account eerst correct synchroniseren.</td> 
     </tr> 
     <tr> 
      <td>externalSalesPersonId</td> 
      <td>MS Dynamics Sales User case-insensitive global unique identifier</td> 
      <td>Identificeert het externe voorwerp van de Gebruiker van de Verkoop van de Dynamiek van MS dat deze Kans bezit. </td> 
     </tr> 
    </tbody> 
   </table>

   * API-documentatie voor Opportunity: [https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/rest/lead-database/opportunities](https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/rest/lead-database/opportunities){target="_blank"}
   * API-documentatie voor synchronisatiemogelijkheden: [https://developer.adobe.com/marketo-apis/api/mapi/#tag/Opportunities/operation/syncOpportunitiesUsingPOST](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Opportunities/operation/syncOpportunitiesUsingPOST){target="_blank"}

1. Contactrollen voor MS Dynamics synchroniseren naar Marketo.

   De Rollen van het Contact van de Dynamica van MS voor een Kans van de Dynamiek van MS kunnen dan via de Rol van de Kans van Marketo worden gesynchroniseerd. In de opportunityrolrecord wordt de opdracht gegeven aan _externalOpportunityId_, _rol_, en _leadId_ velden.

   <table> 
    <colgroup> 
     <col> 
     <col> 
     <col> 
    </colgroup> 
    <tbody> 
     <tr> 
      <td><strong>Marketo Opportunity Role Field</strong></td> 
      <td><strong>Contactrolveld MS Dynamics</strong></td> 
      <td><strong>Beschrijving</strong></td> 
     </tr> 
     <tr> 
      <td>externalOpportunityId</td> 
      <td>MS Dynamics Opportunity niet-hoofdlettergevoelig globaal unieke id</td> 
      <td>Identificeert de Rol van de Kans van Marketo aan een extern voorwerp van de Opportunity van de Dynamiek van MS.<br><br>Er is een mandaat om de MS Dynamics Opportunity eerst correct te synchroniseren.</td> 
     </tr> 
     <tr> 
      <td>leadId</td> 
      <td>N.v.t., dit zou een Marketo Lead ID zijn</td> 
      <td>Dit zou de Marketo Lead-id van de gesynchroniseerde MS Dynamics Contact zijn.<br><br>Zodra het contact in Marketo wordt gesynchroniseerd, kunt u het geval-ongevoelige globaal unieke herkenningsteken van het Contact van de Dynamica van MS als externalPersonId en vraag voor de Lood van Marketo gebruiken gebruikend Marketo REST API.</td> 
     </tr> 
     <tr> 
      <td>rol</td> 
      <td>Het veld Rol voor de contactpersoon voor de LS-dynamiek</td> 
      <td>Beschrijft de rol van het contact voor deze kans.</td> 
     </tr> 
    </tbody> 
   </table>

   * API-documentatie voor Opportunity: [https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/rest/lead-database/opportunities](https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/rest/lead-database/opportunities){target="_blank"}
   * API-documentatie voor synchronisatiemogelijkheden: [https://developer.adobe.com/marketo-apis/api/mapi/#tag/Opportunities/operation/syncOpportunitiesUsingPOST](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Opportunities/operation/syncOpportunitiesUsingPOST){target="_blank"}

1. Synchroniseer de velden Laatste interessant moment/MSI-score naar MS Dynamics.

   Zodra uw voorwerpen van de Dynamiek van MS correct aan Marketo worden gesynchroniseerd, kunt u uit de eigenschappen MSI voordeel halen. De velden MSI Last Interesting Moment/Scoring worden weergegeven in de REST API voor leads. Deze velden worden berekend door MSI en zijn alleen-lezen.

   De velden Laatste interessante momenten/scores van een Marketo-lead moeten regelmatig worden gesynchroniseerd met MS Dynamics met behulp van het eindpunt REST API Lead. Vraag dit eindpunt voor een Lood van Marketo gebruikend _externalPersonId_ als filterType en het overgaan in Lood GUID van de Dynamiek van MS als filterValue.

   | GET /rest/v1/leads.json?filterType=externalPersonId&amp;filterValues=MS DynamicsLeadId1,MS DynamicsLeadId2 |
   |---|

   Vervolgens kunt u de waarden van deze velden gebruiken om te synchroniseren met het object LS Dynamics Lead/Contact.

   <table> 
    <colgroup> 
     <col> 
     <col> 
     <col> 
    </colgroup> 
    <tbody> 
     <tr> 
      <td><strong>Marketo Lead Field</strong></td> 
      <td><strong>MS Dynamics Lead/Contact Field</strong></td> 
      <td><strong>Beschrijving</strong></td> 
     </tr> 
     <tr> 
      <td>msiLastInterestingMomentType</td> 
      <td>Label: type laatste interessant moment<br>Naam: Last_Interesting_Moment_Type__c</td> 
      <td>Type van het laatste interessante moment voor de lead</td> 
     </tr> 
     <tr> 
      <td>msiLastInterestingMomentDate</td> 
      <td><p>Label: Datum laatste interessant moment</p><p>Naam: Last_Interesting_Moment_Date__c</p></td> 
      <td>Datum van het laatste interessante moment voor de lead</td> 
     </tr> 
     <tr> 
      <td>msiLastInterestingMomentDesc</td> 
      <td><p>Label: beschrijving laatste interessant moment</p><p>Naam: Last_Interesting_Moment_Desc__c</p></td> 
      <td>Beschrijving van het laatste interessante moment voor de lead</td> 
     </tr> 
     <tr> 
      <td>msiLastInterestingMomentSource</td> 
      <td><p>Label: bron van laatste interessant moment</p><p>Naam: Last_Interesting_Moment_Source__c</p></td> 
      <td>Bron van het laatste interessante moment voor de lead</td> 
     </tr> 
     <tr> 
      <td>prioriteit</td> 
      <td><p>Label: betrokkenheid</p><p>Naam: Prioriteit__c</p></td> 
      <td>Prioriteit van de lead</td> 
     </tr> 
     <tr> 
      <td>relativeUrency</td> 
      <td><p>Label: relatieve urgentiewaarde</p><p>Naam: Urence_Value__c</p></td> 
      <td>Relatieve urgentie van de leider</td> 
     </tr> 
     <tr> 
      <td>relativeScoring</td> 
      <td><p>Label: relatieve score</p><p>Naam: Relative_Score_Value__c</p></td> 
      <td>Relatieve score van de lead</td> 
     </tr> 
    </tbody> 
   </table>

   * Documentatie voor de LEIDREST API: [https://developer.adobe.com/marketo-apis/api/mapi/#tag/Leads/operation/getLeadByIdUsingGET](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Leads/operation/getLeadByIdUsingGET){target="_blank"}.

   Een correct gebruik van de externe velden is van wezenlijk belang voor een geslaagde, niet-native synchronisatie. Als u gegevens in sommige weergaven niet ziet, is het waarschijnlijk dat een bepaald veld niet correct is gesynchroniseerd. Bijvoorbeeld, als de activiteiten van een lood en de interessante momenten niet verschijnen wanneer het kijken in MSI widget onder hun Rekening, is het waarschijnlijk dat of het bedrijf van de lood of de Rekening correct werd gesynchroniseerd. Als u een GET-aanvraag voor deze lead uitvoert terwijl u de externe velden opgeeft, kunt u controleren of de lead correct is gesynchroniseerd. Bovendien moet de e-mail voor de externe verkoper in Marketo overeenkomen met de e-mail voor die gebruiker in MS Dynamics. Gegevens worden mogelijk niet weergegeven op het tabblad Marketo in MS Dynamics als de e-mails niet overeenkomen.
