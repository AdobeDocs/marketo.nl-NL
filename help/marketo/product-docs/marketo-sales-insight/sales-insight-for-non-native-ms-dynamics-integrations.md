---
description: '[!DNL Sales Insight] voor Niet-inheemse Integraties van MS  [!DNL Dynamics]  - de Documentatie van Marketo - van het Product'
title: '[!DNL Sales Insight] voor Niet-inheemse Integraties van MS  [!DNL Dynamics] '
exl-id: 07613ff8-b197-4a3d-88e9-720b68a6b8da
feature: Marketo Sales Insights
source-git-commit: 7a57e52b497b271beff95b203bddd0c911e2e6a3
workflow-type: tm+mt
source-wordcount: '1262'
ht-degree: 0%

---

# [!DNL Sales Insight] voor niet-native MS [!DNL Dynamics] -integratie {#sales-insight-for-non-native-ms-dynamics-integrations}

Als uw Adobe Marketo Engage-account via een aangepaste of niet-native integratie is verbonden met MS [!DNL Dynamics] , gebruikt u dit artikel om [!DNL Sales Insight] te configureren.

>[!PREREQUISITES]
>
>* De functie &#39;Niet-native MSI&#39; die is ingeschakeld voor uw Marketo-instantie voordat u MSI instelt. Als het niet is en u reeds de eigenschap kocht, gelieve [ de Steun van Marketo ](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"} te contacteren. Neem contact op met het Adobe-accountteam (uw accountmanager) als u deze functie nog niet hebt aangeschaft.
>* Het Pakket van de download [ MSI voor de Synchronisatie van de Douane ](https://mktg-cdn.marketo.com/community/MarketoSalesInsight_NonNative.zip){target="_blank"}.
>* Een abonnement van de Dynamiek van MS met Opstelling MSI (wij steunen online slechts [ Dynamiek ](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/install-and-configure-marketo-sales-insight-in-microsoft-dynamics-online.md){target="_blank"} op dit ogenblik).
>* Marketo REST API [ met succes opstelling ](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/rest-api){target="_blank"}. De belichte CRUD-API&#39;s vormen de basis voor het uitvoeren van de niet-native synchronisatie.
>* Lees [ dit blogbericht ](https://developers.marketo.com/blog/create-and-associate-leads-companies-and-opportunities-with-the-marketo-rest-api/){target="_blank"} om een begrip van het voorwerp en de verhoudingen te krijgen.

## Voor een geslaagde externe synchronisatie van MSI is het volgende vereist {#successful-non-native-sync-for-msi-requires-the-following}

1. Synchroniseer MS [!DNL Dynamics] Sales User to Marketo.

   De gebruiker van de Verkoop van MS [!DNL Dynamics] is een externe gebruiker die de Leads/Contacten in MS [!DNL Dynamics] bezit. Een Marketo-verkoper moet worden geüpserd voor de gebruiker van de Verkoop van MS [!DNL Dynamics]. Het veld externalSalesPersonId is verplicht voor het upsert van de verkoper.

   <table>
    <colgroup>
     <col>
     <col>
     <col>
    </colgroup>
    <tbody>
     <tr>
      <td><strong>Veld Marketo-verkoper</strong></td>
        <td><strong>Het Gebied van de Gebruiker van de Dynamica van MS <span class="dnl"> </span></strong></td>
      <td><strong>Beschrijving</strong></td>
     </tr>
     <tr>
      <td>externalSalesPersonId</td>
        <td>MS <span class="dnl"> Dynamiek </span> van de Gebruiker case-insensitive globaal uniek herkenningsteken</td>
      <td><p>Identificeert het verslag van de Persoon van de Verkoop van Marketo aan een extern MS <span class="dnl"> Dynamica </span> voorwerp van de Gebruiker.</p><p>Het is verplicht dat de persoon van de Verkoop eerst wordt gesynchroniseerd alvorens de andere voorwerpen te synchroniseren zodat de juiste verhoudingen zullen worden gecreeerd.</p></td>
     </tr>
    </tbody>
   </table>

   * [ API documentatie voor de Persoon van de Verkoop ](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/sales-persons){target="_blank"}
   * [ API documentatie voor het synchroniseren van de Persoon van de Verkoop ](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Sales-Persons/operation/syncSalesPersonsUsingPOST){target="_blank"}

1. Synchroniseer de MS [!DNL Dynamics] -accounts met Marketo.

   Een Marketo Company moet worden geüpserd voor de MS [!DNL Dynamics] -account. De _externalCompanyId_ en _externalSalesPersonId_ gebieden worden mandated voor de invoeging van het Bedrijf.

   <table>
    <colgroup>
     <col>
     <col>
     <col>
    </colgroup>
    <tbody>
     <tr>
      <td><strong>Marketo Company Field</strong></td>
        <td><strong>MS <span class="dnl"> het Veld van de Rekening van de Dynamica </span></strong></td>
      <td><strong>Beschrijving</strong></td>
     </tr>
     <tr>
      <td>externalCompanyId</td>
        <td>MS <span class="dnl"> Dynamica </span> de geval-ongevoelige globaal unieke herkenningsteken van de Rekening</td>
        <td>Identificeert een verslag van het Bedrijf van Marketo aan een extern MS <span class="dnl"> voorwerp van de Rekening van de Dynamiek </span>.</td>
     </tr>
     <tr>
      <td>externalSalesPersonId</td>
        <td>MS <span class="dnl"> Dynamiek </span> van de Verkoop - niet-gevoelig globaal uniek herkenningsteken</td>
        <td>Identificeert een verslag van het Bedrijf van Marketo aan een extern voorwerp van de Gebruiker van de Verkoop van MS <span class="dnl"> Dynamica </span> dat de eigenaar van de Rekening is.<br><br> ook gebruikt binnen Marketo om het Bedrijf aan de Persoon van de Verkoop te associëren die het verslag van het Bedrijf bezit. De verkoper moet eerst worden gesynchroniseerd voordat dit veld wordt ingesteld.</td>
     </tr>
    </tbody>
   </table>

   * API documentatie voor Bedrijven: [ https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/companies](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/companies){target="_blank"}
   * API documentatie voor het synchroniseren van Bedrijven: [ https://developer.adobe.com/marketo-apis/api/mapi/#tag/Sales-Persons/operation/syncSalesPersonsUsingPOST](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Sales-Persons/operation/syncSalesPersonsUsingPOST){target="_blank"}

1. Synchroniseer de MS [!DNL Dynamics] Leads/Contacts met Marketo.

   U moet een Marketo-lead bijwerken voor de MS [!DNL Dynamics] -lead/-contactpersoon. De _externalPersonId_, _externalSalesPersonId_, en _externalCompanyId_ gebieden worden mandated voor de bovenkant van Lood.

   <table>
    <colgroup>
     <col>
     <col>
     <col>
    </colgroup>
    <tbody>
     <tr>
      <td><strong>Marketo Lead Field</strong></td>
        <td><strong>MS <span class="dnl"> Dynamica </span> lood/het Gebied van het Contact</strong></td>
      <td><strong>Beschrijving</strong></td>
     </tr>
     <tr>
      <td>externalPersonId</td>
        <td>MS <span class="dnl"> Dynamica </span> Lood/het geval-ongevoelig van het Contact - globaal uniek herkenningsteken</td>
        <td>Identificeert het Lead van Marketo verslag aan een extern MS <span class="dnl"> Dynamica </span> Lood/voorwerp van het Contact.<br><br> dit is een nieuw gebied dat voor niet-Inheems MSI wordt geïntroduceerd.</td>
     </tr>
     <tr>
      <td>externalSalesPersonId</td>
        <td>MS <span class="dnl"> Dynamiek </span> van de Verkoop - niet-gevoelig globaal uniek herkenningsteken</td>
        <td>Identificeert het externe voorwerp van de Gebruiker van de Verkoop van MS <span class="dnl"> Dynamica &lbrace;die dit Lood/Contact bezit.</span><br><br> verwant ook de Lood met de Persoon van de Verkoop in Marketo. De verkoper moet eerst correct worden gesynchroniseerd.</td>
     </tr>
     <tr>
      <td>externalCompanyId</td>
        <td>MS <span class="dnl"> Dynamica </span> de geval-ongevoelige globaal unieke herkenningsteken van de Rekening</td>
        <td>Identificeert het externe voorwerp van de Rekening van de Dynamiek van MS <span class="dnl"> </span> dat Lood/Contact tot behoort.<br><br> verwant ook het loodverslag aan een Bedrijf in Marketo. Het wordt mandated dat de 2&rbrace; rekening van de Dynamica van MS <span class="dnl"> &lbrace;correct eerst wordt gesynchroniseerd.</span></td>
     </tr>
    </tbody>
   </table>

   * API documentatie voor Leads: [ https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/lead-database](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/lead-database){target="_blank"}
   * API documentatie voor het synchroniseren van Leads: [ https://developer.adobe.com/marketo-apis/api/mapi/#tag/Leads/operation/syncLeadUsingPOST](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Leads/operation/syncLeadUsingPOST){target="_blank"}

1. Synchroniseer MS [!DNL Dynamics]-mogelijkheden met Marketo.

   U moet een Marketo Opportunity voor de MS [!DNL Dynamics] Opportunity handhaven. De _externalOpportunityId_, _externalCompanyId_, en _externalSalesPersonId_ gebieden worden mandated voor de controle van de Kans.

   <table>
    <colgroup>
     <col>
     <col>
     <col>
    </colgroup>
    <tbody>
     <tr>
      <td><strong>Veld Marketo Opportunity-object</strong></td>
        <td><strong>MS <span class="dnl"> het Gebied van de Objecten van de Dynamiek </span> van de Opportunity</strong></td>
      <td><strong>Beschrijving</strong></td>
     </tr>
     <tr>
      <td>externalOpportunityId</td>
        <td>MS <span class="dnl"> Dynamica </span> Lood/het geval-ongevoelig van het Contact - globaal uniek herkenningsteken</td>
      <td>Identificeert het verslag van de Kans van Marketo aan een extern voorwerp van de Kans van de Dynamiek van MS <span class="dnl"> </span>.</td>
     </tr>
     <tr>
      <td>externalCompanyId</td>
        <td>MS <span class="dnl"> Dynamica </span> de geval-ongevoelige globaal unieke herkenningsteken van de Rekening</td>
        <td>Identificeert het externe voorwerp van de Rekening van de Dynamiek van MS <span class="dnl"> </span> waar deze Kans tot behoort. <br><br> het wordt mandated dat de 2&rbrace; Rekening van de Dynamica van MS <span class="dnl"> correct eerst wordt gesynchroniseerd.</span></td>
     </tr>
     <tr>
      <td>externalSalesPersonId</td>
        <td>MS <span class="dnl"> Dynamiek </span> van de Verkoop - niet-gevoelig globaal uniek herkenningsteken</td>
        <td>Identificeert het externe voorwerp van de Gebruiker van de Verkoop van de Dynamiek van MS <span class="dnl"> &lbrace;die deze Kans bezit.</span> </td>
     </tr>
    </tbody>
   </table>

   * API documentatie voor Kans: [ https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/opportunities](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/opportunities){target="_blank"}
   * API documentatie voor het synchroniseren van Kansen: [ https://developer.adobe.com/marketo-apis/api/mapi/#tag/Opportunities/operation/syncOpportunitiesUsingPOST](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Opportunities/operation/syncOpportunitiesUsingPOST){target="_blank"}

1. Synchroniseer MS [!DNL Dynamics] Contact Rollen naar Marketo.

   MS [!DNL Dynamics] Contact Roles for a MS [!DNL Dynamics] Opportunity kan vervolgens worden gesynchroniseerd via de opportuniteitsrol van Marketo. Het verslag van de Rol van de Kans mandeert _externalOpportunityId_, _rol_, en _leadId_ gebieden.

   <table>
    <colgroup>
     <col>
     <col>
     <col>
    </colgroup>
    <tbody>
     <tr>
      <td><strong>Marketo Opportunity Role Field</strong></td>
        <td><strong>Het Gebied van de Rol van het Contact van MS <span class="dnl"> Dynamica </span></strong></td>
      <td><strong>Beschrijving</strong></td>
     </tr>
     <tr>
      <td>externalOpportunityId</td>
        <td>MS <span class="dnl"> Dynamiek </span> Kans van de Kans - ongevoelig globaal uniek herkenningsteken</td>
      <td>Identificeert de Rol van de Kans van Marketo aan een extern voorwerp van de Kans van de Dynamiek van MS <span class="dnl"> </span>.<br><br> het wordt mandated dat de 2&rbrace; Kans van de Dynamiek van MS <span class="dnl"> &lbrace;correct eerst wordt gesynchroniseerd.</span></td>
     </tr>
     <tr>
      <td>leadId</td>
      <td>N.v.t., dit zou een Marketo Lead ID zijn</td>
        <td>Dit zou identiteitskaart van de Lood van Marketo van het gesynchroniseerde Contact van de Dynamica van MS <span class="dnl"> </span> zijn.<br><br> Zodra het contact in Marketo wordt gesynchroniseerd, kunt u de 2&rbrace; het geval-ongevoelige globaal unieke herkenningsteken van het Contact van de Dynamica van MS <span class="dnl"> gebruiken &lbrace;als externalPersonId en vraag voor het Lood van Marketo gebruikend Marketo REST API.</span></td>
     </tr>
     <tr>
      <td>rol</td>
        <td>Het gebied van de Rol voor het 10&rbrace; Contact van de Dynamica van MS &lbrace;<span class="dnl"></span></td>
      <td>Beschrijft de rol van het contact voor deze kans.</td>
     </tr>
    </tbody>
   </table>

   * API documentatie voor Kans: [ https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/opportunities](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/opportunities){target="_blank"}
   * API documentatie voor het synchroniseren van Kansen: [ https://developer.adobe.com/marketo-apis/api/mapi/#tag/Opportunities/operation/syncOpportunitiesUsingPOST](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Opportunities/operation/syncOpportunitiesUsingPOST){target="_blank"}

1. Synchroniseer de velden Laatste interessant moment/MSI-score naar MS [!DNL Dynamics] .

   Zodra uw MS [!DNL Dynamics] -objecten correct zijn gesynchroniseerd met Marketo, kunt u de MSI-functies benutten. De velden MSI Last Interesting Moment/Scoring worden weergegeven in de REST API voor leads. Deze velden worden berekend door MSI en zijn alleen-lezen.

   De velden Laatste interessante momenten/scores van een Marketo-lead moeten regelmatig worden gesynchroniseerd met MS [!DNL Dynamics] met behulp van het eindpunt REST API Lead. Vraag dit eindpunt voor een Lood van Marketo gebruikend _externalPersonId_ als filterType en het overgaan in MS [!DNL Dynamics] Lood GUID als filterValue.

   | GET /rest/v1/leads.json?filterType=externalPersonId&amp;filterValues=MS DynamicsLeadId1,MS DynamicsLeadId2 |
   |---|

   Vervolgens kunt u de waarden van deze velden gebruiken om te synchroniseren met het object Lood/Contact van de lidstaat. [!DNL Dynamics]

   <table>
    <colgroup>
     <col>
     <col>
     <col>
    </colgroup>
    <tbody>
     <tr>
      <td><strong>Marketo Lead Field</strong></td>
        <td><strong>MS <span class="dnl"> Dynamica </span> lood/het Gebied van het Contact</strong></td>
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

   * Documentatie voor het LoodREST API: [ https://developer.adobe.com/marketo-apis/api/mapi/#tag/Leads/operation/getLeadByIdUsingGET ](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Leads/operation/getLeadByIdUsingGET){target="_blank"}.

   >[!NOTE]
   >
   >Voor objecttypen Lead/Contacts en Accounts: Marketo biedt ondersteuning voor het gebruik van uw eigen aangepaste velden als externe id-velden bij het gebruik van Marketo Sales Insights. Als u hulp met deze aanpassing nodig hebt, contacteer [ de Steun van Marketo ](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"}.

   Een correct gebruik van de externe velden is van wezenlijk belang voor een geslaagde, niet-native synchronisatie. Als u gegevens in sommige weergaven niet ziet, is het waarschijnlijk dat een bepaald veld niet correct is gesynchroniseerd. Bijvoorbeeld, als de activiteiten van een lood en de interessante momenten niet verschijnen wanneer het kijken in MSI widget onder hun Rekening, is het waarschijnlijk dat of het bedrijf van de lood of de Rekening correct werd gesynchroniseerd. Als u een GET-aanvraag voor deze lead uitvoert terwijl u de externe velden opgeeft, kunt u controleren of de lead correct is gesynchroniseerd. Bovendien moet de e-mail voor de externe verkoper in Marketo overeenkomen met de e-mail voor die gebruiker in MS Dynamics. Gegevens worden mogelijk niet weergegeven op het tabblad Marketo in MS Dynamics als de e-mails niet overeenkomen.
