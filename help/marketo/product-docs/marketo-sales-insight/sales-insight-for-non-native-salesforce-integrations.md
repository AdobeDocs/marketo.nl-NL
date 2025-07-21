---
unique-page-id: 45417125
description: '[!DNL Sales Insight] voor Niet-inheemse  [!DNL Salesforce]  Integraties - de Documentatie van Marketo - de Documentatie van het Product'
title: '[!DNL Sales Insight] voor Niet-inheemse  [!DNL Salesforce]  Integraties'
exl-id: a771ecdf-c610-44e4-9e93-7fdcc9d79f4b
feature: Marketo Sales Insights
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '1200'
ht-degree: 0%

---

# [!DNL Sales Insight] voor niet-native [!DNL Salesforce] integratie {#sales-insight-for-non-native-salesforce-integrations}

Als uw Adobe Marketo Engage-account met [!DNL Salesforce] is verbonden via een aangepaste of niet-native integratie, gebruikt u dit artikel om [!DNL Sales Insight] te configureren.

>[!PREREQUISITES]
>
>* De functie &#39;Niet-native MSI&#39; die is ingeschakeld voor uw Marketo-instantie voordat u MSI instelt. Als het niet is en u reeds de eigenschap kocht, gelieve [ de Steun van Marketo ](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"} te contacteren. Neem contact op met het Adobe-accountteam (uw accountmanager) als u deze functie nog niet hebt aangeschaft.
>* Een rekening van Salesforce met [ MSI de opstelling van het Pakket ](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md){target="_blank"}.
>* Marketo REST API [ met succes opstelling ](https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/rest/rest-api){target="_blank"}. De belichte CRUD-API&#39;s vormen de basis voor het uitvoeren van de niet-native synchronisatie.
>* Lees [ dit blogbericht ](https://developers.marketo.com/blog/create-and-associate-leads-companies-and-opportunities-with-the-marketo-rest-api/){target="_blank"} om een begrip van het voorwerp en de verhoudingen te krijgen.
>* Stel [!DNL Salesforce] -objecten zo in dat de algemeen unieke id voor 18 hoofdletters/kleine letters wordt weergegeven in plaats van de algemeen unieke id voor 15 hoofdletters/kleine letters.

>[!NOTE]
>
>De configuratie van de REST API in het deelvenster Marketo MSI Admin kan niet worden gebruikt voor de niet-native synchronisatie.

## Voor een geslaagde externe synchronisatie van MSI is het volgende vereist {#successful-non-native-sync-for-msi-requires-the-following}

1. Synchroniseer de [!DNL Salesforce] Verkoopgebruiker naar Marketo.

   De [!DNL Salesforce] Verkoopgebruiker is een externe gebruiker die eigenaar is van de leads/contactpersonen in [!DNL Salesforce] . Een Marketo-verkoper moet worden geüpserd voor de [!DNL Salesforce] Verkoopgebruiker. Het *externalSalesPersonId* gebied wordt mandated voor het toezicht van de Persoon van de Verkoop.

   <table> 
    <colgroup> 
     <col> 
     <col> 
     <col> 
    </colgroup> 
    <tbody> 
     <tr> 
      <td><strong>Veld Marketo-verkoper</strong></td> 
        <td><strong><span class="dnl"> Salesforce </span> Veld van de Gebruiker van de Verkoop</strong></td> 
      <td><strong>Beschrijving</strong></td> 
     </tr> 
     <tr> 
      <td>externalSalesPersonId</td> 
        <td><span class="dnl"> Salesforce </span> de geval-ongevoelig van de Gebruiker van de Verkoop globaal uniek herkenningsteken</td> 
      <td><p>Identificeert het verslag van de Persoon van de Verkoop van Marketo aan een extern <span class="dnl"> Salesforce </span> voorwerp van de Gebruiker van de Verkoop.</p><p>Het is verplicht dat de persoon van de Verkoop eerst wordt gesynchroniseerd alvorens de andere voorwerpen te synchroniseren zodat de juiste verhoudingen zullen worden gecreeerd.</p></td> 
     </tr> 
    </tbody> 
   </table>

   * API documentatie voor Verkoper: [ https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/rest/lead-database/sales-persons](https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/rest/lead-database/sales-persons){target="_blank"}
   * API documentatie voor het synchroniseren van de Persoon van de Verkoop: [ https://developer.adobe.com/marketo-apis/api/mapi/#tag/Sales-Persons/operation/syncSalesPersonsUsingPOST](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Sales-Persons/operation/syncSalesPersonsUsingPOST){target="_blank"}

1. Synchroniseer de [!DNL Salesforce] -accounts met Marketo.

   Een Marketo Company moet worden bijgewerkt voor de account van [!DNL Salesforce] . De _externalCompanyId_ en _externalSalesPersonId_ gebieden worden mandated voor de invoeging van het Bedrijf.

   <table> 
    <colgroup> 
     <col> 
     <col> 
     <col> 
    </colgroup> 
    <tbody> 
     <tr> 
      <td><strong>Marketo Company Field</strong></td> 
        <td><strong><span class="dnl"> Salesforce </span> Gebied van de Rekening</strong></td> 
      <td><strong>Beschrijving</strong></td> 
     </tr> 
     <tr> 
      <td>externalCompanyId</td> 
        <td><span class="dnl"> Salesforce </span> de geval-ongevoelige globaal unieke herkenningsteken van de Rekening</td> 
        <td>Identificeert een verslag van het Bedrijf van Marketo aan een extern <span class="dnl"> Salesforce </span> voorwerp van de Rekening.</td> 
     </tr> 
     <tr> 
      <td>externalSalesPersonId</td> 
        <td><span class="dnl"> Salesforce </span> de geval-ongevoelig van de Gebruiker van de Verkoop globaal uniek herkenningsteken</td> 
        <td>Identificeert een verslag van het Bedrijf van Marketo aan een extern <span class="dnl"> Salesforce </span> voorwerp van de Gebruiker van de Verkoop die de eigenaar van de Rekening is.<br><br> ook gebruikt binnen Marketo om het Bedrijf aan de Persoon van de Verkoop te associëren die het verslag van het Bedrijf bezit. De verkoper moet eerst worden gesynchroniseerd voordat dit veld wordt ingesteld.</td> 
     </tr> 
    </tbody> 
   </table>

   * API documentatie voor Bedrijven: [ https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/rest/lead-database/companies](https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/rest/lead-database/companies){target="_blank"}
   * API documentatie voor het synchroniseren van Bedrijven: [ https://developer.adobe.com/marketo-apis/api/mapi/#tag/Companies/operation/syncCompaniesUsingPOST](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Companies/operation/syncCompaniesUsingPOST){target="_blank"}

1. Synchroniseer [!DNL Salesforce] Leads/Contacten met Marketo.

   U moet een Marketo-lead bijwerken voor de [!DNL Salesforce] lead/contactpersoon. De _externalPersonId_, _externalSalesPersonId_, en _externalCompanyId_ gebieden worden mandated voor de bovenkant van Lood.

   <table> 
    <colgroup> 
     <col> 
     <col> 
     <col> 
    </colgroup> 
    <tbody> 
     <tr> 
      <td><strong>Marketo Lead Field</strong></td> 
        <td><strong><span class="dnl"> Salesforce </span> lood/het Gebied van het Contact</strong></td> 
      <td><strong>Beschrijving</strong></td> 
     </tr> 
     <tr> 
      <td>externalPersonId</td> 
        <td><span class="dnl"> Salesforce </span> leiden/het geval-ongevoelig van het Contact - globaal uniek herkenningsteken</td> 
        <td>Identificeert het verslag van het Lood van Marketo aan een extern <span class="dnl"> Salesforce </span> Lood/voorwerp van het Contact.<br><br> dit is een nieuw gebied dat voor niet-Inheems MSI wordt geïntroduceerd.</td> 
     </tr> 
     <tr> 
      <td>externalSalesPersonId</td> 
        <td><span class="dnl"> Salesforce </span> de geval-ongevoelig van de Gebruiker van de Verkoop globaal uniek herkenningsteken</td> 
        <td>Identificeert het externe <span class="dnl"> voorwerp van de Gebruiker van de Verkoop van Salesforce </span> die dit Lood/Contact bezit.<br><br> verwant ook de Lood met de Persoon van de Verkoop in Marketo. De verkoper moet eerst correct worden gesynchroniseerd.</td> 
     </tr> 
     <tr> 
      <td>externalCompanyId</td> 
        <td><span class="dnl"> Salesforce </span> de geval-ongevoelige globaal unieke herkenningsteken van de Rekening</td> 
        <td>Identificeert het externe <span class="dnl"> voorwerp van de Rekening van Salesforce </span> dat Lood/Contact tot behoort.<br><br> verwant ook het loodverslag aan een Bedrijf in Marketo. Het is verplicht eerst de Salesforce-account correct te synchroniseren.</td> 
     </tr> 
    </tbody> 
   </table>

   * API documentatie voor Leads: [ https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/rest/lead-database/leads](https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/rest/lead-database/leads)
   * API documentatie voor het synchroniseren van Leads: [ https://developer.adobe.com/marketo-apis/api/mapi/#tag/Leads/operation/syncLeadUsingPOST](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Leads/operation/syncLeadUsingPOST)

1. Synchroniseer [!DNL Salesforce] Kansen met Marketo.

   U moet een Marketo Opportunity voor de [!DNL Salesforce] Opportunity invoegen. De _externalOpportunityId_, _externalCompanyId_, en _externalSalesPersonId_ gebieden worden mandated voor de controle van de Kans.

   <table> 
    <colgroup> 
     <col> 
     <col> 
     <col> 
    </colgroup> 
    <tbody> 
     <tr> 
      <td><strong>Veld Marketo Opportunity-object</strong></td> 
        <td><strong><span class="dnl"> Salesforce </span> Gebied van de Objecten van de Opportunity</strong></td> 
      <td><strong>Beschrijving</strong></td> 
     </tr> 
     <tr> 
      <td>externalOpportunityId</td> 
      <td>Salesforce Lead/Contact case-insensitive global unique identifier</td> 
      <td>Identificeert de opportunityrecord van Marketo naar een extern Salesforce Opportunity-object.</td> 
     </tr> 
     <tr> 
      <td>externalCompanyId</td> 
        <td><span class="dnl"> Salesforce </span> de geval-ongevoelige globaal unieke herkenningsteken van de Rekening</td> 
        <td>Identificeert het externe <span class="dnl"> voorwerp van de Rekening van Salesforce </span> waar deze Kans tot behoort. <br><br> het wordt mandated dat de <span class="dnl"> Salesforce </span> rekening correct eerst wordt gesynchroniseerd.</td> 
     </tr> 
     <tr> 
      <td>externalSalesPersonId</td> 
        <td><span class="dnl"> Salesforce </span> de geval-ongevoelig van de Gebruiker van de Verkoop globaal uniek herkenningsteken</td> 
        <td>Identificeert het externe <span class="dnl"> voorwerp van de Gebruiker van de Verkoop van Salesforce </span> die deze Kans bezit. </td> 
     </tr> 
    </tbody> 
   </table>

   * API documentatie voor Kans: [ https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/rest/lead-database/opportunities](https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/rest/lead-database/opportunities){target="_blank"}
   * API documentatie voor het synchroniseren van Kansen: [ https://developer.adobe.com/marketo-apis/api/mapi/#tag/Opportunities/operation/syncOpportunitiesUsingPOST](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Opportunities/operation/syncOpportunitiesUsingPOST){target="_blank"}

1. Synchroniseer [!DNL Salesforce] Contactrollen naar Marketo.

   [!DNL Salesforce] Contactrollen voor een [!DNL Salesforce] opportunity kan vervolgens worden gesynchroniseerd via de opportuniteitsrol van Marketo. Het verslag van de Rol van de Kans mandeert _externalOpportunityId_, _rol_, en _leadId_ gebieden.

   <table> 
    <colgroup> 
     <col> 
     <col> 
     <col> 
    </colgroup> 
    <tbody> 
     <tr> 
      <td><strong>Marketo Opportunity Role Field</strong></td> 
      <td><strong>Veld Salesforce-contactrol</strong></td> 
      <td><strong>Beschrijving</strong></td> 
     </tr> 
     <tr> 
      <td>externalOpportunityId</td> 
        <td><span class="dnl"> Salesforce </span> van de Kans case-insensitive globaal uniek herkenningsteken</td> 
        <td>Identificeert de Rol van de Kans van Marketo aan een extern <span class="dnl"> Salesforce </span> voorwerp van de Kans.<br><br> het wordt mandated dat de <span class="dnl"> 2&rbrace; Kans van Salesforce &lbrace;eerst correct wordt gesynchroniseerd.</span></td> 
     </tr> 
     <tr> 
      <td>leadId</td> 
      <td>N.v.t., dit zou een Marketo Lead ID zijn</td> 
        <td>Dit zou identiteitskaart van de Lood van Marketo van het gesynchroniseerde <span class="dnl"> 1&rbrace; Contact van Salesforce zijn.</span><br><br> Zodra het contact in Marketo wordt gesynchroniseerd, kunt u het <span class="dnl"> geval-ongevoelige van het contact van Salesforce </span> gebruiken globaal uniek herkenningsteken als externalPersonId en vraag voor het Lood van Marketo gebruikend Marketo REST API.</td> 
     </tr> 
     <tr> 
      <td>rol</td> 
        <td>Het gebied van de Rol voor het <span class="dnl"> Salesforce </span> Contact</td> 
      <td>Beschrijft de rol van het contact voor deze kans.</td> 
     </tr> 
    </tbody> 
   </table>

   * API documentatie voor Kans: [ https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/rest/lead-database/opportunities](https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/rest/lead-database/opportunities){target="_blank"}
   * API documentatie voor het synchroniseren van Kansen: [ https://developer.adobe.com/marketo-apis/api/mapi/#tag/Opportunities/operation/syncOpportunitiesUsingPOST](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Opportunities/operation/syncOpportunitiesUsingPOST){target="_blank"}

1. Synchroniseer de velden Laatste interessant moment/MSI-score naar SFDC.

   Zodra uw [!DNL Salesforce] -objecten correct zijn gesynchroniseerd met Marketo, kunt u de MSI-functies benutten. De velden MSI Last Interesting Moment/Scoring worden weergegeven in de REST API voor leads. Deze velden worden berekend door MSI en zijn alleen-lezen.

   De velden Laatste interessante momenten/scores van een Marketo-lead moeten regelmatig met [!DNL Salesforce] worden gesynchroniseerd met behulp van het eindpunt REST API Lead. Vraag dit eindpunt voor een Lood van Marketo gebruikend _externalPersonId_ als filterType en het overgaan in [!DNL Salesforce] Lood GUID als filterValue.

   | GET /rest/v1/leads.json?filterType=externalPersonId&amp;filterValues=salesforceLeadId1,salesforceLeadId2 |
   |---|

   Vervolgens kunt u de waarden van deze velden gebruiken om te synchroniseren met het object [!DNL Salesforce] Lead/Contact.

   <table> 
    <colgroup> 
     <col> 
     <col> 
     <col> 
    </colgroup> 
    <tbody> 
     <tr> 
      <td><strong>Marketo Lead Field</strong></td> 
        <td><strong><span class="dnl"> Salesforce </span> lood/het Gebied van het Contact</strong></td> 
      <td><strong>Beschrijving</strong></td> 
     </tr> 
     <tr> 
      <td>msiLastInterestingMomentType</td> 
      <td>Etiket: Laatste het Interesten Naam van het Type van Momentype <br>: Last_Interesting_Moment_Type__c</td> 
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
      <td><p>Label: Source voor laatste interessant moment</p><p>Naam: Last_Interesting_Moment_Source__c</p></td> 
      <td>Source van het laatste interessante moment voor de leider</td> 
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

   Documentatie voor het LoodREST API: [ https://developer.adobe.com/marketo-apis/api/mapi/#tag/Leads/operation/getLeadByIdUsingGET ](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Leads/operation/getLeadByIdUsingGET){target="_blank"}.

   Een correct gebruik van de externe velden is van wezenlijk belang voor een geslaagde, niet-native synchronisatie. Als u gegevens in sommige weergaven niet ziet, is het waarschijnlijk dat een bepaald veld niet correct is gesynchroniseerd. Bijvoorbeeld, als de activiteiten van een lood en de interessante momenten niet verschijnen wanneer het kijken in MSI widget onder hun Rekening, is het waarschijnlijk dat of het bedrijf van de lood of de Rekening correct werd gesynchroniseerd. Als u een GET-aanvraag voor deze lead uitvoert terwijl u de externe velden opgeeft, kunt u controleren of de lead correct is gesynchroniseerd. Bovendien moet het e-mailbericht voor de externe verkoper in Marketo overeenkomen met het e-mailbericht voor die gebruiker in Salesforce. Gegevens worden mogelijk niet weergegeven op het tabblad Marketo in Salesforce als de e-mails niet overeenkomen.
