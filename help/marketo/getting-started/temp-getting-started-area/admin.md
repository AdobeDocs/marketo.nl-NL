---
description: NIEUW GEBIED - Marketo-documenten - Productdocumentatie
title: NIEUW GEBIED
hide: true
hidefromtoc: true
feature: Getting Started
exl-id: c7b068fc-a038-4f9c-a037-72440a1a864e
source-git-commit: 14ccfe39059b9c900a5e5e00b082146bb500d79d
workflow-type: tm+mt
source-wordcount: '1113'
ht-degree: 0%

---

# NIEUW GEBIED: Controlelijst voor beheerders {#new-area-admin-checklist}

Starttekst.

## Rollen {#roles}

<table>
<thead>
  <tr>
    <th style="width:20%">Gebied</th>
    <th style="width:80%">Actiepunten</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Rollen</td>
    <td><li>Herzie de prebuilt rollen en bevestig welke toestemmingen/toegang elke rol heeft.<br><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.html#create-a-new-role" target="_blank">Een nieuwe rol maken</a> of <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.html#edit-a-role" target="_blank">de rollen bewerken</a> op basis van de behoeften van uw organisatie en hoe vaak gebruikers zich aanmelden.<br><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.html%22%20/l%20%22assign-roles-to-a-user" target="_blank">Gebruikers toewijzen aan de juiste rollen</a>. De gebruikers moeten aan het abonnement in Adobe Admin Console worden toegevoegd alvorens hun rollen in Roles toe te kennen. Raadpleeg de sectie "Gebruikers" in de checklist "Eerste installatie" [LINK]. <br>Nadat u de rollen voor gebruikers hebt toegewezen, controleert u het aantal gebruikers per rol.<br>Implementeer een unieke rol voor elke API-gebruiker voor eenvoudige probleemoplossing.</td>
  </tr>
  <tr>
    <td>Documentatie</td>
    <td>Definieer gebruikers en rollen voor uw organisatie.<br>Definieer het proces voor het toevoegen van een nieuwe gebruiker/beheerder.</td>
  </tr>
  <tr>
    <td>Sandbox (indien van toepassing)</td>
    <td>Controleer de bovenstaande categorieën voor uw sandbox als u er een hebt.</td>
  </tr>
</tbody>
</table>

## Werkruimten en partities {#workspaces-partitions}

<table>
<thead>
  <tr>
    <th style="width:20%">Gebied</th>
    <th style="width:80%">Actiepunten</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Werkruimten en partities (indien van toepassing)</td>
    <td>Bepaal het aantal van<a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/workspaces-and-person-partitions/understanding-workspaces-and-person-partitions.html" target="_blank"> werkruimten</a> en/of partities die uw organisatie nodig heeft en <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/workspaces-and-person-partitions/allow-user-access-to-a-workspace.html" target="_blank">hoeveel gebruikers toegang hebben tot elke werkruimte.</a><br>Bepaal het primaire doel van elke werkruimte en verdeling.<br>Bepaal de verhouding tussen uw werkruimten en verdelingen.</td>
  </tr>
  <tr>
    <td>Documentatie</td>
    <td>Documenteer hoe de werkruimten worden bepaald, en hoe dat met gegevensbestandverdelingen (d.w.z. een Globale werkruimte die iedereen, tegenover bedrijfssectoren ziet) verhoudt. <br>Importeer nieuwe records naar de juiste partitie.<br>Bepaal de waarde in CRM die gebruikers in de aangewezen verdeling plaatst.</td>
  </tr>
</tbody>
</table>

## Instellingen voor slimme campagne {#smart-campaign-settings}

<table>
<thead>
  <tr>
    <th style="width:20%">Gebied</th>
    <th style="width:80%">Actiepunten</th>
  </tr>
</thead>
  <tr>
    <th>Gebied</th>
    <th>Actiepunten</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Instellingen voor slimme campagne</td>
    <td>Voeg een <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/email-setup/enable-person-restrictions-for-smart-campaigns.html" target="_blank">beperking van de grootte van slimme campagnes</a>te voorkomen dat per ongeluk de gehele database wordt gemaild.</td>
  </tr>
  <tr>
    <td>Documentatie</td>
    <td>Documenteer hoe de werkruimten worden bepaald, en hoe dat met gegevensbestandverdelingen (d.w.z. een Globale werkruimte die iedereen, tegenover bedrijfssectoren ziet) verhoudt.  <br>Importeer nieuwe records naar de juiste partitie.<br>Bepaal de waarde in CRM die gebruikers in de aangewezen verdeling plaatst.</td>
  </tr>
</tbody>
</table>

## E-mailinstellingen {#email-settings}

<table>
<thead>
  <tr>
    <th style="width:20%">Gebied</th>
    <th style="width:80%">Actiepunten</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Standaardwaarden e-mail</td>
    <td>Selecteer onder Brandingdomein uw domein en voeg uw e-mailNAAM toe. Dit moet de volgende notatie hebben: [EmailTrackingCNAME].[CompanyDomain].com.  <br><a href="https://experienceleague.adobe.com/en/docs/customer-one/using/home#create-a-support-ticket-with-admin-console" target="_blank">Contact opnemen met Marketo-ondersteuning</a> om deze te beveiligen met een SSL-certificaatvoorziening. Dit proces kan maximaal 3 werkdagen duren.</td>
  </tr>
  <tr>
    <td>SPF/DKIM</td>
    <td><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/deliverability/set-up-spf-and-dkim-for-your-email-deliverability.html" target="_blank">SPF en DKIM instellen</a> voor e-mailleverbaarheid.</td>
  </tr>
  <tr>
  </tr>
  <tr>
  </tr>
</tbody>
</table>

## Communicatielimieten {#communication-limits}

<table>
<thead>
  <tr>
    <th style="width:20%">Gebied</th>
    <th style="width:80%">Actiepunten</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Communicatielimieten</td>
    <td>Plaatsen <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/email-setup/enable-communication-limits.html" target="_blank" rel="noopener noreferrer">Communicatielimieten</a>.<br>Bepaal als uw zaken een beleid inzake Communicatie Limieten vereist </td>
  </tr>
</tbody>
</table>

## Tags {#tags}

<table>
<thead>
  <tr>
    <th style="width:20%">Gebied</th>
    <th style="width:80%">Actiepunten</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Kanalen</td>
    <td>Bepalen hoe u wilt gebruiken <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/tags/create-a-program-channel.html" target="_blank" rel="noopener noreferrer">kanalen</a>.</td>
  </tr>
  <tr>
    <td>Tags</td>
    <td>Bepalen hoe u wilt gebruiken <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/tags/managing-tag-values.html" target="_blank" rel="noopener noreferrer">tags</a>.</td>
  </tr>
  <tr>
    <td>Kalender (indien van toepassing)</td>
    <td><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/marketing-calendar/understanding-the-calendar/issue-revoke-a-marketing-calendar-license.html" target="_blank" rel="noopener noreferrer">Licentieschema's voor marketingkalenders afgeven</a> aan degenen die toegang nodig hebben. <br>Instellen <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/marketing-calendar/understanding-the-calendar/navigating-the-marketing-calendar.html" target="_blank" rel="noopener noreferrer">Kalender.</a></td>
  </tr>
</tbody>
</table>

## Databasebeheer {#database-management}

<table>
<thead>
  <tr>
    <th style="width:20%">Gebied</th>
    <th style="width:80%">Actiepunten</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Veldbeheer</td>
    <td>Naamgevingsconventie implementeren voor <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/field-management/create-a-custom-field-in-marketo.html" target="_blank" rel="noopener noreferrer">aangepaste velden.</a> Begin bijvoorbeeld met "MKTO".<br>Selecteer de velden die u synchroniseert. Hoe meer velden u synchroniseert, hoe langzamer de synchronisatiecyclus wordt.<br><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/field-management/block-updates-to-a-field.html" target="_blank" rel="noopener noreferrer">Updates van velden blokkeren</a> waarnaar u wilt schrijven (bijvoorbeeld oorspronkelijke loden bron, oorspronkelijke brongegevens van de bron, UTM-velden van de eerste aanraking, enz.)</td>
  </tr>
  <tr>
  </tr>
  <tr>
    <td>Aangepaste activiteiten</td>
    <td>Definiëren <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-custom-activities/understanding-custom-activities.html">Aangepaste activiteiten</a> die specifiek zijn voor uw bedrijf.  </td>
  </tr>
  <tr>
    <td>Aangepaste objecten</td>
    <td>Aantal controleren <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.html">Aangepaste objecten</a> dat is nodig. <br><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-custom-object-sync.html">Deze aangepaste objecten synchroniseren met uw CRM</a>. </td>
  </tr>
</tbody>
</table>

## Integraties {#integrations}

<table>
<thead>
  <tr>
    <th style="width:20%">Gebied</th>
    <th style="width:80%">Actiepunten</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>CRM </td>
    <td>CRM-synchronisatie starten. Kies uit het volgende, afhankelijk van CRM uw bedrijf gebruikt: <a href="https://experienceleague.adobe.com/docs/marketo-learn/tutorials/integrations/salesforce-sync-setup.html">Salesforce</a> | <a href="https://experienceleague.adobe.com/docs/marketo-learn/tutorials/integrations/microsoft-dynamics-sync-setup.html">Microsoft Dynamics</a>. <br>Identificeer het type van toegang u tot uw CRM moet toegang hebben. <br>Identificeer uw beheerder van CRM voor het oplossen van problemen. </td>
  </tr>
  <tr>
    <td>Landingspagina's</td>
    <td>NOTA: Ben u een klant van het Pak van de Lancering? U kunt deze stap overslaan. Uw consultant zal u een document met instructies voor de IT-installatie geven tijdens uw gesprek. <br>Stel uw landingspagina in met een <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/settings/edit-landing-page-settings.html">CNAME</a> en <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/settings/edit-landing-page-settings.html">domein- en paginagegevens invoeren</a>. Dit moet de volgende notatie hebben: [LandingPageCNAME].[CompanyDomain].com <br>Kies een NAAM voor de bestemmingspagina's. Enkele voorbeelden: <br>* * **go**.[CompanyDomain].com <br>* ***www2**.[CompanyDomain].com <br>* * ** lp**.[CompanyDomain].com <br><a href="https://experienceleague.adobe.com/en/docs/customer-one/using/home#create-a-support-ticket-with-admin-console">Contact opnemen met Marketo-ondersteuning</a> om het proces van levering van een SSL Certificaat te beginnen. Dit proces kan maximaal 3 werkdagen duren. <br>TIP: Houd het kort! Kortere URL's zijn gemakkelijker te onthouden. We stellen voor om "te gaan" als domein. <br>Voeg analytische volgcode (bijvoorbeeld Googles Analytics of Adobe Analytics) toe aan uw sjablonen voor de bestemmingspagina. </td>
  </tr>
  <tr>
    <td>Munchkin</td>
    <td>NOTA: Als u een klant van het Pak van de Lancering bent, gelieve deze stap over te slaan. Uw consultant zal u in het handboek met instructies voor de installatie van uw IT-afdeling codeinstructies geven. <br><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.html">Munchkin-trackingcode toevoegen</a> naar uw website. Munchkin-code kan <a href="https://developers.marketo.com/javascript-api/lead-tracking/">hard-gecodeerd</a> of geïmplementeerd via Google Tag Manager.  </td>
  </tr>
  <tr>
    <td>Webservices</td>
    <td>Inschakelen <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/additional-integrations/create-an-allowlist-for-ip-based-api-access.html">de IP Beperkingen</a> indien van toepassing. <br>Bepaal de gebruikers/apps die kunnen maken <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/users-and-roles/create-an-api-only-user.html">API-aanroepen</a> in uw exemplaar. <br>Controleer alle apps die API-aanroepen maken en bepaal of een verhoging of cut nodig is voor de API-aanroepen.  </td>
  </tr>
  <tr>
    <td>LaunchPoint</td>
    <td>Instellen vereist <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/additional-integrations/add-adobe-connect-as-a-launchpoint-service.html">LaunchPoint</a> services voor uw bedrijf. Elk LaunchPoint zou met een unieke API gebruiker aan hulp met het oplossen van problemen moeten worden gecombineerd.  </td>
  </tr>
  <tr>
    <td>Interactieve webinars (indien van toepassing)</td>
    <td>NOTA: Interactieve Webinars is slechts provisioned aan de instanties van de Productie. <br>Voor het creëren van Interactieve Webinars, de ingebouwde webinar eigenschap, <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/events/interactive-webinars/user-and-license-management">gebruikers toevoegen aan de sectie Gebruiker</a> op het tabblad Interactief webinar. </td>
  </tr>
  <tr>
    <td>Adobe Dynamic Chat (indien van toepassing)</td>
    <td>Voor gebruik <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/dynamic-chat/dynamic-chat-overview.html">Dynamic Chat</a>, het inheemse kanaal van de gespreksautomatisering in Marketo Engage, zult u met de opstelling van de gebruikerstoestemming na de hieronder stappen te werk gaan <a href="https://adminconsole.adobe.com/">Adobe Admin Console</a>. <br>Bevestig of aan u een rol van Admin van het Product van de Adobe door uw Adobe Org Systeembeheerder is toegekend. Contact <a href="https://helpx.adobe.com/contact.html">Klantenservice Adoben</a> om te weten te komen wie bij uw organisatie admin voorrechten in de console heeft. <br>Accepteren <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/initial-setup.html">de uitnodiging voor 'Dynamic Chat Product Admin'</a>. De <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/initial-setup.html">welkome e-mail</a> wordt verzonden wanneer de Dynamic Chat in uw instantie van het Marketo Engage wordt toegelaten en u als Admin van het Systeem wordt aangewezen.  <br>Wijs alle relevante gebruikers toe aan het productprofiel van de Dynamic Chat in Adobe Admin Console. <br>Als een ongewenste gebruiker aan meerdere productprofielen wordt toegevoegd, moet u de gebruiker uit alle productprofielen verwijderen. Anders hebben ze nog steeds toegang tot Dynamic Chat. <br>U kunt <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/permissions#edit-existing-permissions">Productprofielen bewerken in Dynamic Chat</a> en maak een aangepast profiel met een aangepaste set van <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/permissions#list-of-permissions">rechten beschikbaar binnen uw abonnement</a>. <br>Gebruikers toewijzen aan <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/add-or-remove-chat-users#add-dynamic-chat-access-to-marketo-role">Rollen 'Access Dynamic Chat'</a> in Marketo Engage/Admin/Users &amp; Roles. </td>
  </tr>
  <tr>
    <td>Verkoopoverzicht (indien van toepassing)</td>
    <td><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/marketo-sales-insight/actions/getting-started/sales-insight-actions-admin-setup-guide#set-up-marketo-sales-account">Handeling Verkoopinzicht instellen</a> in Sales Insight&gt;Actions Config.  <br><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/marketo-sales-insight/actions/getting-started/sales-insight-actions-admin-setup-guide.html#invite-individual-users-to-msi-actions">Geef licenties door aan de juiste gebruikers.</a>  <br><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/marketo-sales-insight-configuration-tab-in-salesforce.html">De API configureren</a>. <br><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/marketo-sales-insight/msi-for-salesforce/features/stars-and-flames/priority-urgency-relative-score-and-best-bets.html">Pas de leadscores aan.</a> </td>
  </tr>
  <tr>
    <td>Verkoopverbinding (indien van toepassing)</td>
    <td><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/marketo-sales-connect/getting-started/accessing-your-new-sales-connect-instance">De juiste beheerders van Marketo's Engage uitnodigen voor de Sales Connect-instantie</a>. <br>Voltooi de <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/marketo-sales-connect/getting-started/getting-started-guide-for-sales-connect-admins">Extra installatie van Sales Connect-beheer</a> in Sales Connect en Salesforce. </td>
  </tr>
</tbody>
</table>

## Treasure Chest {#treasure-chest}

<table>
<thead>
  <tr>
    <th style="width:20%">Gebied</th>
    <th style="width:80%">Actiepunten</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Treasure Chest </td>
    <td><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/settings/enable-or-disable-treasure-chest-features.html">Schatkest inschakelen</a> om te experimenteren met proefuiteinden.  <br>Bepaal de functies die u wilt in- of uitschakelen. </td>
  </tr>
  <tr>
    <td>Campagne-controle </td>
    <td><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/settings/campaign-inspector.html">Campagnecontrole inschakelen</a> om al uw slimme campagnes tegelijk weer te geven. </td>
  </tr>
</tbody>
</table>
