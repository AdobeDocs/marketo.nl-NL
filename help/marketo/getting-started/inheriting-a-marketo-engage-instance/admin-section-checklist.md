---
description: Controlelijst voor overgenomen Instance Admin - Marketo Docs - Productdocumentatie
title: Controlelijst voor overgenomen Instance Admin
feature: Getting Started
exl-id: 088f3ce9-bf3d-4323-9cde-c39fec06c20e
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '1858'
ht-degree: 0%

---

# Overgenomen instantie: beheerderscontrolelijst voor sectie {#inherited-instance-admin-section-checklist}

De onderstaande checklists (hiernavolgende checklists die aan de onderkant van elk artikel zijn gekoppeld) zijn samengesteld door Adobe Professional Services met input van Marketo Champions om u te helpen snel aan de slag te gaan. U kunt ook [ de controlelijsten ](/help/marketo/getting-started/inheriting-a-marketo-engage-instance/assets/adobe-marketo-engage-inherited-instance-admin-checklist.xlsx) downloaden en uw vooruitgang volgen.

>[!TIP]
>
>Als u een nieuwe (er) gebruiker van Marketo Engage bent en niet vertrouwd met veel van de termijnen, gelieve de [ Verklarende woordenlijst van Marketo Engage ](/help/marketo/getting-started/things-to-know/marketo-engage-glossary.md){target="_blank"} te controleren.

## Adobe Identity Management {#adobe-identity-management}

>[!NOTE]
>
>Dit is slechts van toepassing op de abonnementen van Marketo Engage die aan [ het Systeem van Identity Management van Adobe (IMS) ](/help/marketo/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.md){target="_blank"} worden bezet. Als uw abonnement Adobe IMS nog niet heeft betreden, ga met de [ erfenisgebruikersrollen en toestemmingenervaring ](/help/marketo/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.md){target="_blank"} in Marketo Engage > Admin > Gebruikers &amp; Roles te werk.

<table>
 <tbody>
  <tr>
   <th style="width:20%">Gebied</th>
   <th>Focus controleren</th>
  </tr>
  <tr>
   <td>Abonnement en Marketo Engage-productbeheerder</td>
   <td><li>Is uw Marketo Engage abonnement gemigreerd aan <a href="/help/marketo/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.md" target="_blank"> IMS van Adobe </a> nog?
<br/>     Zo ja, hebt u een "Adobe Admin Console Product Admin" rol gekregen van uw "Adobe Admin Console System Admin"? Als u niet zeker bent wie in uw organisatie admin voorrechten in de console heeft, contacteer <a href="https://helpx.adobe.com/nl/contact.html" target="_blank"> de Zorg van de Klant van Adobe </a>.</li>
<li>Heb je de uitnodiging voor 'Marketo Engage Product Admin' geaccepteerd? De e-mail wordt verzonden wanneer de rol in de Adobe Admin Console wordt toegewezen.
<br/>     Als niet, zoek <a href="/help/marketo/product-docs/administration/marketo-with-adobe-identity/admin-setup.md#initial-setup" target="_blank"> welkome e-mail </a> in uw inbox en keur de uitnodiging goed om uw Adobe ID te activeren.</li></td>
  </tr>
  <tr>
   <td>Productprofiel</td>
   <td><li>Worden alle geschikte gebruikers toegewezen aan het Marketo Engage-productprofiel in Adobe Admin Console?
<br/>     Als niet, zorg ervoor om <a href="/help/marketo/product-docs/administration/marketo-with-adobe-identity/add-or-remove-a-user.md" target="_blank"> gebruikers </a> van de productprofielen van Marketo Engage in Adobe Admin Console toe te voegen en/of te verwijderen. U kunt geen gebruikersrollen toewijzen in Marketo Engage &gt; Beheer &gt; Gebruikers en rollen als deze worden toegevoegd aan een productprofiel.</li>
<p><img src="assets/note-icon.png" alt="notitiepictogram"> OPMERKING: als een ongewenste gebruiker aan meerdere productprofielen wordt toegevoegd, moet u de gebruiker uit alle productprofielen verwijderen. Anders hebben ze nog steeds toegang tot Marketo Engage.</td>
  </tr>
  <tr>
   <td>Gebruikersbeheer-API</td>
   <td><li>Gebruikt uw abonnement Marketo-gebruikersbeheer-API's?
<br/>     Als zo, zult u <a href="https://www.adobe.io/apis/experienceplatform/umapi-new.html" target="_blank"> Adobe IMS APIs </a> moeten gebruiken om, gebruikers uit te nodigen bij te werken en te schrappen die zich vooruit bewegen.</li>
<p><img src="assets/note-icon.png" alt="notitiepictogram"> OPMERKING: 'Role Management' blijft in Marketo Engage en Marketo-API's voor gebruikersbeheer kunnen nog steeds worden gebruikt voor rolbeheer.</td>
  </tr>
 </tbody>
</table>

## Gebruikers en rollen {#users-and-roles}

<table>
 <tbody>
  <tr>
   <th style="width:20%">Gebied</th>
   <th>Focus controleren</th>
  </tr>
  <tr>
   <td>Gebruikers</td>
   <td><img src="assets/note-icon.png" alt="notitiepictogram"> OPMERKING: als uw abonnement al op Adobe IMS is, gaat u naar de volgende gebruikersbeheercontrole in Adobe Admin Console. Anders gaat u naar Beheer &gt; Gebruikers en rollen &gt; Gebruikers in Marketo Engage.
   <p>
   <li><a href="/help/marketo/product-docs/administration/users-and-roles/managing-marketo-users.md" target="_blank"> hoeveel gebruikers </a> zijn er?</li>
<li>Zijn er om het even welke gebruikers die <a href="/help/marketo/product-docs/administration/marketo-with-adobe-identity/add-or-remove-a-user.md#remove-a-user" target="_blank"> zouden moeten worden verwijderd </a>?</li>
<li>Heeft uw bedrijf beleid om gebruikers te schrappen?</li>
<li>Hoeveel gebruikers hebben <a href="/help/marketo/product-docs/administration/users-and-roles/descriptions-of-role-permissions.md" target="_blank"> toestemmingen Admin </a>?</li>
<li>Zou om het even welk van die gebruikers in <a href="/help/marketo/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.md" target="_blank"> andere rollen moeten worden veranderd?</a></li>
<li>Wie zijn de <a href="/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user.md" target="_blank"> API gebruikers </a> in deze instantie?</li></td>
  </tr>
  <tr>
   <td>Rollen</td>
   <td><img src="assets/note-icon.png" alt="notitiepictogram"> OPMERKING: Of u nu Marketo gebruikt met Adobe Identity of niet, ga door met het controleren van de rolinachtigingen in Marketo Engage onder Beheer &gt; Gebruikers &amp; rollen &gt; Rollen.
   <p><li>Hoeveel rollen zijn er?</li>
<li>Welke <a href="/help/marketo/product-docs/administration/users-and-roles/descriptions-of-role-permissions.md" target="_blank"> toestemmingen/toegang </a> heeft elke rol? Moet dit eventueel worden aangepast?</li>
<li>Hoeveel gebruikers zijn er per rol?</li>
<li>Hoe vaak zijn de gebruikers <a href="/help/marketo/product-docs/administration/audit-trail/user-login-history.md" target="_blank"> het programma openen </a>?</li>
<li>Heeft elke gebruiker API hun <a href="/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user-role.md" target="_blank"> eigen gebruikersrol </a>? Als niet, overweeg het uitvoeren van dit om het oplossen van problemen gemakkelijker te maken.</li>
<li>Zijn uw gebruikersrollen en toestemmingen gericht op uw collectief beleid van de gegevensprivacy voor regelgevende naleving (b.v., <a href="https://gdpr-info.eu/" target="_blank"> GDPR </a>)? Staat het collectieve gegevens <a href="/help/marketo/product-docs/core-marketo-concepts/miscellaneous/privacy-management.md" target="_blank"> privacybeleid </a> gebruikers toe om Marketo Engage gebruikersgegevens te downloaden en te delen? Is de toestemmingszaken noodzakelijk?</li></td>
  </tr>
  <tr>
   <td>Ondersteuningsgebruikers</td>
   <td><li>Hebt u opstelling de aangewezen <a href="/help/marketo/getting-started/initial-setup/setup-steps.md#set-up-your-authorized-support-contacts" target="_blank"> gemachtigde contacten </a> in het Portaal van de Steun?</li></td>
  </tr>
  <tr>
   <td>Interne documentatie</td>
   <td><li>Zijn de gebruikers en de rollen duidelijk bepaald in uw organisatie?</li>
<li>Wat is uw procedure voor het toevoegen van een nieuwe gebruiker/beheerder?</li></td>
  </tr>
  <tr>
   <td>Sandbox (indien van toepassing)</td>
   <td><li>Hebt u a <a href="/help/marketo/product-docs/core-marketo-concepts/miscellaneous/marketo-sandbox.md" target="_blank"> zandbakinstantie </a>?
   <br/>     Als dat het geval is, bekijkt u de bovenstaande categorieën voor uw sandbox.</li>
<li>Is de Invoer van het Programma <a href="/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/import-a-program.md" target="_blank"> verbonden met uw zandbak?</a></li></td>
  </tr>
 </tbody>
</table>

## Audittrail {#audit-trail}

<table style="table-layout:auto">
 <tbody>
  <tr>
   <th style="width:20%">Gebied</th>
   <th>Focus controleren</th>
  </tr>
  <tr>
   <td>Audittrail</td>
   <td><li><a href="/help/marketo/product-docs/administration/audit-trail/audit-trail-overview.md" target="_blank"> Who werkt </a> in de instantie?</li></td>
  </tr>
 </tbody>
</table>

## Werkruimten en partities {#workspaces-and-partitions}

<table style="table-layout:auto">
 <tbody>
  <tr>
   <th style="width:20%">Gebied</th>
   <th>Focus controleren</th>
  </tr>
  <tr>
   <td>Werkruimten en partities</td>
   <td><li>Hoeveel <a href="/help/marketo/product-docs/administration/workspaces-and-person-partitions/understanding-workspaces-and-person-partitions.md" target="_blank"> Werkruimten en/of Verdelingen </a> hebt u?</li>
<li>Wat is het belangrijkste doel van elke Workspace en Partitie?</li>
<li>Zijn of uw <a href="/help/marketo/product-docs/administration/workspaces-and-person-partitions/edit-a-workspace.md" target="_blank"> Werkruimten </a> of <a href="/help/marketo/product-docs/administration/workspaces-and-person-partitions/edit-an-existing-person-partition.md" target="_blank"> Verdelingen </a> moet worden gecontroleerd/worden veranderd?</li>
<li>Wat is het verband tussen uw Werkruimten en Verdelingen?</li>
<li>Hoeveel gebruikers <a href="/help/marketo/product-docs/administration/workspaces-and-person-partitions/allow-user-access-to-a-workspace.md" target="_blank"> hebben toegang </a> tot elke Workspace?</li></td>
  </tr>
  <tr>
   <td>Interne documentatie</td>
   <td><li>Hoe worden Werkruimten en Partities gedefinieerd?</li>
<li>Wat is uw proces om Werkruimten aan uw instantie toe te voegen of gebruikers aan een Workspace toe te voegen?</li></td>
  </tr>
 </tbody>
</table>

## Slimme campagnes {#smart-campaigns}

<table style="table-layout:auto">
 <tbody>
  <tr>
   <th style="width:20%">Gebied</th>
   <th>Focus controleren</th>
  </tr>
  <tr>
   <td>Slimme campagnes</td>
   <td><li><a href="/help/marketo/product-docs/administration/email-setup/enable-person-restrictions-for-smart-campaigns.md" target="_blank"> hebt u een beperking </a> op de Slimme grootte van de Campagne?
   <br/>     Als dat niet het geval is, kunt u er een toevoegen. We raden u aan de limiet voor slimme campagnes te beperken tot 25% van uw database om overcommunicatie te voorkomen of om uw gehele database in workflows te verwerken. Hierdoor wordt niet alleen uw merk beschermd, maar wordt ook de prestaties van uw instantie beter beveiligd.</li></td>
  </tr>
 </tbody>
</table>

## Communicatielimieten {#communication-limits}

<table style="table-layout:auto">
 <tbody>
  <tr>
   <th style="width:20%">Gebied</th>
   <th>Focus controleren</th>
  </tr>
  <tr>
   <td>Communicatielimieten</td>
   <td><li>Zijn er <a href="/help/marketo/product-docs/administration/email-setup/enable-communication-limits.md" target="_blank"> communicatie limieten </a> op zijn plaats? Heeft uw bedrijf beleid waar de communicatie grenzen noodzakelijk zouden kunnen zijn?</li>
<p><img src="assets/note-icon.png" alt="notitiepictogram"> NOTA: Wij adviseren beperkend uw mededeling aan 1 per dag en 3 per 7 dagen, met <b> niet </b> - <a href="/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/make-an-email-operational.md" target="_blank"> operationele </a> geblokkeerde e-mails.</td>
  </tr>
 </tbody>
</table>

## Tags {#tags}

<table style="table-layout:auto">
 <tbody>
  <tr>
   <th style="width:20%">Gebied</th>
   <th>Focus controleren</th>
  </tr>
  <tr>
   <td>Tags</td>
   <td><li><a href="/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/understanding-tags.md" target="_blank"> Hoeveel markeringen </a> zijn er? Hoeveel tags zijn er in gebruik? Moet er iets worden toegevoegd?</li>
<li>Zijn er labels vereist binnen uw programma's?</li></td>
  </tr>
  <tr>
   <td>Kanalen</td>
   <td><li><a href="/help/marketo/product-docs/administration/tags/create-a-program-channel.md" target="_blank"> hoeveel kanalen </a> zijn er? Hoeveel zijn er in gebruik?</li>
<li>Zijn alle <a href="/help/marketo/product-docs/administration/tags/hide-unhide-a-program-channel.md" target="_blank"> status van het kanaalprogramma aangewezen </a>? Tonen zij vooruitgang binnen het programma?</li>
<li>Zijn uw kanalen verwant aan specifieke programmatypes?</li>
<li>Welke statussen worden beschouwd als een succes voor elk kanaal? Lijn die op uw marketingdoelstellingen?</li>
<li>Wordt het operationele kanaal correct gebruikt?</li>
<li>Is voor Advanced Report Builder (Revenue Cycle Explorer/RCE) het gedrag van de kanaalanalyse zodanig ingesteld dat het overeenkomt met de praktijk van uw programma waarbij de kosten van de periode worden opgenomen?</li></td>
  </tr>
  <tr>
   <td>Verkoopkalender (indien van toepassing)</td>
   <td><li>Hoeveel <a href="/help/marketo/product-docs/core-marketo-concepts/marketing-calendar/understanding-the-calendar/navigating-the-marketing-calendar.md" target="_blank"> types van kalenderingang </a> zijn er? Zijn ze allemaal nog steeds relevant?</li></td>
  </tr>
 </tbody>
</table>

## Databasebeheer {#database-management}

<table style="table-layout:auto">
 <tbody>
  <tr>
   <th style="width:20%">Gebied</th>
   <th>Focus controleren</th>
  </tr>
  <tr>
   <td>Veldbeheer</td>
   <td><li>Hoeveel velden zijn er?
   <br/>     Klik <a href="/help/marketo/product-docs/administration/field-management/export-a-list-of-all-marketo-api-field-names.md" target="_blank"> Namen van het Gebied van de Uitvoer </a> om een lijst van uw gebieden, douanegebieden, en hun API namen te herzien.</li>
<li>Hoeveel <a href="/help/marketo/product-docs/administration/field-management/create-a-custom-field-in-marketo.md" target="_blank"> douanegebieden </a> zijn er?</li>
<li>Hoeveel velden worden gebruikt?
<br/>     Selecteer <a href="/help/marketo/product-docs/administration/field-management/export-used-by-data-for-a-field.md" target="_blank"> Uitvoer die door </a> in de drop-down de Acties van het Gebied wordt gebruikt om verwante activa van een gebied te herzien.</li>
<li>Hoeveel velden worden gesynchroniseerd tussen Marketo Engage en uw CRM?</li>
<li>Worden CRM-velden gesynchroniseerd met de desbetreffende objecten?</li>
<li>Is er a <a href="/help/marketo/product-docs/administration/settings/creating-a-custom-tab-for-the-person-detail-page.md" target="_blank"> geplaatste douanemening </a> voor persoondetail? Moet dat?</li>
<li>Hebt u een naamgevingsconventie voor uw velden op basis van de bron?
<br/>     Zo niet, dan kunt u overwegen dit te implementeren.</li>
<li>Zijn er om het even welke gebieden <a href="/help/marketo/product-docs/administration/field-management/block-updates-to-a-field.md" target="_blank"> geblokkeerd </a>?
<br/>     Als dat het geval is, moet u er zeker van zijn dat u begrijpt waarom dat zo is.</li></td>
  </tr>
  <tr>
   <td>Aangepaste activiteiten</td>
   <td><li>Zijn er om het even welke <a href="/help/marketo/product-docs/administration/marketo-custom-activities/understanding-custom-activities.md" target="_blank"> douaneactiviteiten </a>?
<br/>     Als dat het geval is, klikt u erop om te begrijpen welke activiteiten niet gerelateerd zijn aan een Marketo-formulier, e-mail of landingspagina.</li></td>
  </tr>
  <tr>
   <td>Aangepaste objecten</td>
   <td><li>Hoeveel <a href="/help/marketo/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md" target="_blank"> douanevoorwerpen </a> zijn er? Hoe worden ze gesynchroniseerd met uw CRM?</li>
<li>Hoe worden deze douanevoorwerpen gebruikt door uw programma's en lijstvragen?</li></td>
  </tr>
 </tbody>
</table>

## E-mail {#email}

<table style="table-layout:auto">
 <tbody>
  <tr>
   <th style="width:20%">Gebied</th>
   <th>Focus controleren</th>
  </tr>
  <tr>
   <td>Standaardinstellingen voor e-mail</td>
   <td><li>In Admin &gt; E-mail, zijn elk van uw standaardmontages bijgewerkt (b.v., <a href="/help/marketo/product-docs/administration/email-setup/change-the-default-from-email-and-from-label.md" target="_blank"> "van"e-mail/etiket </a>, <a href="/help/marketo/product-docs/administration/email-setup/add-multiple-branding-domains/edit-your-default-branding-domain.md" target="_blank"> brandend domein </a>, <a href="/help/marketo/product-docs/administration/email-setup/edit-the-unsubscribe-message.md" target="_blank"> unsubscribe bericht </a>, enz.)?</li></td>
  </tr>
 </tbody>
</table>

## Integraties {#integrations}

<table style="table-layout:auto">
 <tbody>
  <tr>
   <th style="width:20%">Gebied</th>
   <th>Focus controleren</th>
  </tr>
  <tr>
   <td>CRM</td>
   <td><li>Met welke CRM synchroniseert u? Salesforce? MS Dynamics? Veeva?</li>
<li>Gebruikt u a <a href="https://nation.marketo.com/t5/product-blogs/instructions-for-creating-a-custom-sync-rule/ba-p/242758" target="_blank"> douanesync </a>?</li>
<li>[Alleen Salesforce] Zijn er aangepaste synchronisatiefilters voor uw instantie geïmplementeerd?
<p><img src="assets/note-icon.png" alt="notitiepictogram"> OPMERKING: neem contact op met de ondersteuning van Marketo om Aangepaste synchronisatiefilters te identificeren of om een aangepaste synchronisatieregel te vragen.</li></td>
  </tr>
  <tr>
   <td>Landingspagina's</td>
   <td><li>Wat is het <a href="/help/marketo/product-docs/administration/settings/edit-landing-page-settings.md" target="_blank"> domein dat als </a> wordt geplaatst?</li>
   <li>Hoe wordt de homepage ingesteld?</li>
<li>Wat is de <a href="/help/marketo/product-docs/administration/settings/set-a-fallback-page.md" target="_blank"> fallback die als </a> wordt geplaatst?</li>
<li>Is het vooraf invullen van het formulier ingeschakeld?</li>
<li>Zijn <a href="/help/marketo/product-docs/demand-generation/landing-pages/personalizing-landing-pages/enable-personalized-urls-for-your-account.md" target="_blank"> gepersonaliseerde URLs </a> toegelaten?</li>
<li>Zijn er regels opstelling voor <a href="/help/marketo/product-docs/demand-generation/landing-pages/landing-page-actions/redirect-a-marketo-landing-page-to-another-page.md" target="_blank"> omleiding </a>?</li>
<li>Hebt u domeinaliassen op zijn plaats? Houdt u bij hoe u uw domeinaliassen gebruikt?</li>
<li>Is <a href="https://nation.marketo.com/t5/knowledgebase/setting-up-secured-domains-for-marketo-landing-pages-first-time/ta-p/250370" target="_blank"> Beveiligde Domeinen voor het Bestaan van Pagina's </a> toegelaten?
<br/>     Bevestig of uw landingspagina-elementen een 'http'-URL bevatten.</li></td>
  </tr>
  <tr>
   <td>Munchkin</td>
   <td><li>Is uw <a href="/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md" target="_blank"> het volgen van Munchkin code </a> op uw website (niet een Marketo Engage het Bestaan Pagina)?</li>
<li>Is a <a href="/help/marketo/product-docs/administration/settings/edit-do-not-track-browser-support-settings.md" target="_blank"> </a> toegelaten Browser van het Spoor niet Verzoek?</li>
<li>Is uw <a href="https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/javascriptapi/leadtracking/lead-tracking" target="_blank"> Munchkin API </a> gevormd?
<p><img src="assets/tip-icon.png" alt="pictogram tip">TIP: Als u documentatie mist waar de munchkin code op uw website is, kunt u alle URLs bekijken door het Rapport van de Activiteit van de Pagina van het a <a href="/help/marketo/product-docs/reporting/basic-reporting/report-types/web-page-activity-report.md" target="_blank"> te creëren </a>.</li></td>
  </tr>
  <tr>
   <td>Webservices</td>
   <td><li>Zijn <a href="/help/marketo/product-docs/administration/additional-integrations/create-an-allowlist-for-ip-based-api-access.md" target="_blank"> IP de Beperkingen </a> toegelaten? Moeten ze dat zijn?</li>
<li>Welke gebruikers/apps maken API-aanroepen in uw exemplaar?</li>
<li>Raakt u of bijna aan het bereiken van uw API grens?
<br/>     Als dat het geval is, kunt u overwegen het te verhogen of uw instantie te controleren om die API-aanroepen omlaag te brengen.</li></td>
  </tr>
  <tr>
   <td>Adobe Dynamic Chat (indien van toepassing)</td>
<td>Na de stappen hieronder zullen toegang tot <a href="https://adminconsole.adobe.com/" target="_blank"> Adobe Admin Console </a> vereisen. Als u opstelling nog geen Adobe ID hebt, <a href="https://helpx.adobe.com/nl/manage-account/using/create-update-adobe-id.html" target="_blank"> leren hoe te om dat hier </a> te doen.
<br/>
<li>Hebt u <a href="/help/marketo/product-docs/demand-generation/dynamic-chat/setup-and-configuration/initial-setup.md" target="_blank"> Admin van het Product van Dynamic Chat </a> Uitnodiging goedgekeurd? Het e-mailbericht wordt verzonden wanneer Dynamic Chat in uw Marketo Engage-exemplaar is ingeschakeld en u bent aangewezen als System Admin.
<br/>     Als dat niet het geval is, zoekt u de welkomste-mail in uw Postvak IN en accepteert u de uitnodiging om uw Adobe ID in te stellen.</li>
<li>Hebt u de <a href="/help/marketo/product-docs/demand-generation/dynamic-chat/setup-and-configuration/add-or-remove-chat-users.md#add-a-chat-user" target="_blank"> gewenste gebruikers </a> aan het het productprofiel van Dynamic Chat in Adobe Admin Console toegevoegd?
<li>Zorg ervoor dat het Dynamic Chat-productprofiel aan de Adobe-identiteit is toegevoegd en dat gebruikers die hiervoor in aanmerking komen dit profiel hebben. U kunt 'Access Dynamic Chat'-rollen niet toewijzen in Marketo Engage &gt; Beheer &gt; Gebruikers en rollen als deze worden toegevoegd aan een productprofiel.</li>
<li>Zijn de standaardprofielmachtigingen op het tabblad 'Productprofielen' afgestemd op de behoeften van uw organisatie?<br/>
Als dat niet het geval is, bewerkt u de machtigingen voor het specifieke profiel. </li>
<li>Als u meerdere abonnementen hebt, worden uw gebruikers dan toegevoegd aan de juiste abonnementen?</li>
<br>
Nadat u de instellingen Gebruikers en rollen hebt gecontroleerd, meldt u zich aan bij Dynamic Chat om door te gaan met de controle.
<li>Hebt u <a href="/help/marketo/product-docs/demand-generation/dynamic-chat/integrations/adobe-marketo-engage.md" target="_blank"> uw instantie van Marketo Engage </a> met Dynamic Chat verbonden?</li>
<li>Zijn de vijf standaardprofielen met vooraf bepaalde toestemmingen van toepassing op uw organisatie?<br/>
     Als niet, kunt u hen <a href="/help/marketo/product-docs/demand-generation/dynamic-chat/setup-and-configuration/permissions.md#edit-existing-permissions" target="_blank"> uitgeven in Dynamic Chat </a>. U kunt <a href="/help/marketo/product-docs/demand-generation/dynamic-chat/setup-and-configuration/permissions.md#create-a-profile" target="_blank"> een Profiel van de Douane </a> met een douanereeks toestemmingen ook tot stand brengen.</li>
<li>Als u uw gebruikers toegang wilt geven tot Dynamic Chat, hebt u "Access Dynamic Chat" (Toegang tot) ingeschakeld voor de toepasselijke Marketo Engage-rol onder Beheer &gt; Gebruikers en rollen &gt; Rollen?
<br/><img src="assets/note-icon.png" alt="notitiepictogram"> OPMERKING: de rollen 'Admin' en 'Marketing User' moeten toegang hebben tot Dynamic Chat.</li>
</td>
  </tr>
  <td>Marketo Sales Insight (indien van toepassing)</td>
   <td><li>Is het <a href="/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md" target="_blank"> pakket MSI geïnstalleerd </a>?</li>
<li>Hebt u <a href="/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/upgrading/upgrading-your-msi-package.md" target="_blank"> bevorderd aan de recentste versie van Verkoop Insight </a>?</li>
<li>Hebt u de configuratie van Verkoopmanager Insight voltooid? <br/>     De onderneming/Onbeperkte gebruikers <a href="/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-enterprise-unlimited.md" target="_blank"> klikt hier </a>, Professionele gebruikers <a href="/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-professional-edition.md" target="_blank"> klikt hier </a>.</li>
<li>Hebt u <a href="/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/add-sales-insight-permission-set.md" target="_blank"> toegang tot uw gebruikers </a> gegeven die op het aantal plaatsen wordt gebaseerd u hebt gekocht?</li>
<li>Zijn <a href="/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/stars-and-flames/customize-stars-and-flames.md" target="_blank"> Sterren en Flames </a> aangepast?</li></td>
  </tr>
  <tr>
   <td>Launchpoint (indien van toepassing)</td>
   <td><li>Welke diensten hebben u gevormd (bijvoorbeeld, <a href="/help/marketo/product-docs/administration/additional-integrations/add-webex-as-a-launchpoint-service.md" target="_blank"> BrightTALK </a>, <a href="/help/marketo/product-docs/administration/additional-integrations/connect-brighttalk-to-marketo.md" target="_blank"> Gezoem </a>, enz.)? Zijn ze bijna verlopen?</li>
<li><a href="https://nation.marketo.com/t5/knowledgebase/viewing-your-number-of-api-calls-to-marketo/ta-p/254256" target="_blank"> Hoeveel API vraag </a> zijn uw integraties gebruiken?</li>
<li>Hebt u de juiste integraties voor uw gebruiksgevallen?</li></td>
  </tr>
  <tr>
   <td>Webhaken (indien van toepassing)</td>
   <td><li><a href="/help/marketo/product-docs/administration/additional-integrations/create-a-webhook.md" target="_blank"> Welke verbindingen </a> hebt u opstelling?</li>
<li>Zijn er geen personen meer in gebruik?</li></td>
  </tr>
  <tr>
   <td>Mobiele apps (indien van toepassing)</td>
   <td><li>Welke <a href="/help/marketo/product-docs/mobile-marketing/admin/add-a-mobile-app.md" target="_blank"> mobiele apps </a> hebt u?</li>
<li>Zijn om het even welke <a href="/help/marketo/product-docs/mobile-marketing/push-notifications/adding-a-new-test-device.md" target="_blank"> testapparaten </a> toegevoegd?</li></td>
  </tr>
 </tbody>
</table>

## Treasure Chest {#treasure-chest}

<table style="table-layout:auto">
 <tbody>
  <tr>
   <th style="width:20%">Gebied</th>
   <th>Focus controleren</th>
  </tr>
  <tr>
   <td>Treasure Chest</td>
   <td><li>Wat in de <a href="/help/marketo/product-docs/administration/settings/enable-or-disable-treasure-chest-features.md" target="_blank"> Uitrusting van de Schatting </a> wordt aangezet?</li>
<li>Zijn er functies die moeten worden in- of uitgeschakeld?</li></td>
  </tr>
  <tr>
   <td>Campagne-controle</td>
   <td><li>Is <a href="/help/marketo/product-docs/administration/settings/campaign-inspector.md" target="_blank"> de Inspecteur van de Campagne </a> aangezet?
<br/> als niet, denk na het aanzetten om gemakkelijk te identificeren welke campagnes: actief zijn, synchroniserend met uw CRM, en/of het schrappen verslagen.</li></td>
  </tr>
 </tbody>
</table>

## Waarschuwingen en updates {#alerts-and-updates}

<table style="table-layout:auto">
 <tbody>
  <tr>
   <th style="width:20%">Gebied</th>
   <th>Focus controleren</th>
  </tr>
  <tr>
   <td>Marketo Engage-statusupdates</td>
   <td><li>Is uw instantie geabonneerd aan <a href="https://nation.marketo.com/t5/knowledgebase/how-to-subscribe-to-status-page-notifications/ta-p/296749" target="_blank"> Updates van de Status van Marketo Engage </a>?</li></td>
  </tr>
  <tr>
   <td>Waarschuwingen</td>
   <td><li>Zijn er om het even welk <a href="/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/send-alert.md" target="_blank"> actieve alarm </a> die naar interne teams van Marketo Engage worden verzonden?</li>
<li>Zo ja, functioneren deze waarschuwingen naar behoren?</li></td>
  </tr>
  <tr>
   <td>Meldingen</td>
   <td><li>Bent u geabonneerd aan aangewezen admin <a href="/help/marketo/product-docs/core-marketo-concepts/miscellaneous/understanding-notifications.md" target="_blank"> berichten </a>?</li></td>
  </tr>
 </tbody>
</table>
