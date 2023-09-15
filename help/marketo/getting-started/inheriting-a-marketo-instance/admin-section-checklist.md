---
description: Controlelijst voor overgenomen Instance Admin - Marketo Docs - Productdocumentatie
title: Controlelijst voor overgenomen Instance Admin
hide: true
hidefromtoc: true
source-git-commit: d3a35d669eb54d020228ffdbdd7606a86abd18af
workflow-type: tm+mt
source-wordcount: '1566'
ht-degree: 0%

---

# Overgenomen instantie: beheerderscontrolelijst voor sectie {#inherited-instance-admin-section-checklist}

De onderstaande checklists (hiernavolgende checklists die aan de onderkant van elk artikel zijn gekoppeld) zijn samengesteld door Adobe Professional Services met input van Marketo Champions om u te helpen snel aan de slag te gaan. U kunt ook de checklists downloaden en de voortgang volgen.

>[!TIP]
>
>Als u een nieuwe (er) gebruiker van het Marketo Engage bent en niet vertrouwd met veel van de termijnen bent, gelieve te controleren [Woordenlijst Marketo Engage](/help/marketo/getting-started/marketo-engage-glossary.md){target="_blank"}.

## Adobe Identity Management {#adobe-identity-management}

>[!NOTE]
>
>Dit geldt alleen voor abonnementen op [Adobe Identity Management System (IMS)](/help/marketo/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.md){target="_blank"}. If your Marketo Engage subscription has not onboarded Adobe IMS yet, proceed with the [legacy user roles and permissions experience](/help/marketo/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.md){target="_blank"} in Marketo Engage > Beheer > Gebruikers en rollen.

<table> 
 <tbody> 
  <tr> 
   <th style="width:20%">Gebied</th> 
   <th>Focus controleren</th>
  </tr> 
  <tr> 
   <td>Abonnement</td> 
   <td><li>Is uw abonnement op Marketo's Engage gemigreerd naar <a href="/help/marketo/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.md" target="_blank">Adobe IMS</a> toch ? 
<br/>     Zo ja, hebt u een "Adobe Admin Console Product Admin" rol gekregen van uw "Adobe Admin Console System Admin"? Als u niet zeker bent wie in uw organisatie admin voorrechten in de console heeft, contacteer <a href="https://helpx.adobe.com/contact.html" target="_blank">Klantenservice Adoben</a>.</li>
<li>Hebt u de uitnodiging voor 'Marketo Engage Product Admin' geaccepteerd? De e-mail wordt verzonden wanneer de rol in de Adobe Admin Console wordt toegewezen.
<br/>     Indien niet, zoek naar <a href="/help/marketo/product-docs/administration/marketo-with-adobe-identity/admin-setup.md#" target="_blank">welkome e-mail</a> in uw Postvak IN en accepteer de uitnodiging om uw Adobe ID te activeren.</li></td>
  </tr>
  <tr> 
   <td>Productprofiel</td> 
   <td><li>Worden alle geschikte gebruikers toegewezen aan het productprofiel van Marketo Engage in Adobe Admin Console?
<br/>     Indien niet, zorg ervoor dat <a href="/help/marketo/product-docs/administration/marketo-with-adobe-identity/add-or-remove-a-user.md" target="_blank">gebruikers toevoegen en/of verwijderen</a> van productprofielen van de Marketo Engage in de Adobe Admin Console. U kunt geen gebruikersrollen toewijzen in Marketo Engage &gt; Beheer &gt; Gebruikers en rollen als deze worden toegevoegd aan een productprofiel.</li>
<p><img src="assets/note-icon.png" alt="notitiepictogram"> OPMERKING: als een ongewenste gebruiker aan meerdere productprofielen wordt toegevoegd, moet u de gebruiker uit alle productprofielen verwijderen. Anders hebben ze nog steeds toegang tot Marketo Engage.</td>
  </tr>
  <tr> 
   <td>Gebruikersbeheer-API</td> 
   <td><li>Gebruikt uw abonnement Marketo-gebruikersbeheer-API's?
<br/>     Als dat het geval is, zult u moeten gebruiken <a href="https://www.adobe.io/apis/experienceplatform/umapi-new.html" target="_blank">Adobe IMS API's</a> om gebruikers die zich verder verplaatsen uit te nodigen, bij te werken en te verwijderen.</li>
<p><img src="assets/note-icon.png" alt="notitiepictogram"> OPMERKING: 'Rolbeheer' blijft in Marketo Engage en Marketo-API's voor gebruikersbeheer kunnen nog steeds worden gebruikt voor rolbeheer.</td>
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
   <li><a href="/help/marketo/product-docs/administration/users-and-roles/managing-marketo-users.md" target="_blank">Hoeveel gebruikers</a> is dat zo ?</li>
<li>Zijn er om het even welke gebruikers die <a href="/help/marketo/product-docs/administration/marketo-with-adobe-identity/add-or-remove-a-user.md#remove-a-user" target="_blank">verwijderd</a>?</li>
<li>Heeft uw bedrijf beleid om gebruikers te schrappen?</li> 
<li>Hoeveel gebruikers hebben <a href="/help/marketo/product-docs/administration/users-and-roles/descriptions-of-role-permissions.md" target="_blank">Beheerdersmachtigingen</a>?</li>
<li>Indien een van deze gebruikers wordt gewijzigd in <a href="/help/marketo/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.md" target="_blank">andere rollen ?</a></li> 
<li>Wie zijn de <a href="/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user.md" target="_blank">API-gebruikers</a> in dit geval?</li></td>
  </tr>
  <tr> 
   <td>Rollen</td> 
   <td><img src="assets/note-icon.png" alt="notitiepictogram"> NOTA: Of u Marketo met de Identiteit van de Adobe gebruikt of niet, ga met het herzien roltoestemmingen in Marketo Engage onder Admin &gt; Gebruikers &amp; Rollen &gt; Rollen.
   <p><li>Hoeveel rollen zijn er?</li>  
<li>Wat <a href="/help/marketo/product-docs/administration/users-and-roles/descriptions-of-role-permissions.md" target="_blank">machtigingen/toegang</a> heeft elke rol een rol ? Moet dit eventueel worden aangepast?</li>
<li>Hoeveel gebruikers zijn er per rol?</li>
<li>Hoe vaak gebruikers zijn <a href="/help/marketo/product-docs/administration/audit-trail/user-login-history.md" target="_blank">aanmelden</a>?</li>
<li>Heeft elke API-gebruiker een <a href="/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user-role.md" target="_blank">eigen gebruikersrol</a>? Als niet, overweeg het uitvoeren van dit om het oplossen van problemen gemakkelijker te maken.</li> 
<li>Zijn uw gebruikersrollen en toestemmingen in overeenstemming met uw beleid van de bedrijfs gegevensprivacy voor regelgevende naleving (b.v., <a href="https://gdpr-info.eu/" target="_blank">GDPR</a>)? Voer de bedrijfsgegevens uit <a href="/help/marketo/product-docs/core-marketo-concepts/miscellaneous/privacy-management.md" target="_blank">privacybeleid</a> gebruikers toestaan om Marketo Engage gebruikersgegevens te downloaden en te delen? Is de toestemmingszaken noodzakelijk?</li></td>
  </tr>
  <tr> 
   <td>Ondersteuningsgebruikers</td> 
   <td><li>Hebt u de juiste instellingen <a href="/help/marketo/getting-started/setup/setup-steps.md#set-up-your-authorized-support-contacts" target="_blank">bevoegde contactpersonen</a> in het ondersteuningsportaal?</li></td>
  </tr>
  <tr> 
   <td>Interne documentatie</td> 
   <td><li>Zijn de gebruikers en de rollen duidelijk bepaald in uw organisatie?</li>
<li>Wat is uw procedure voor het toevoegen van een nieuwe gebruiker/beheerder?</li></td>
  </tr>
  <tr> 
   <td>Sandbox (indien van toepassing)</td> 
   <td><li>Heeft u een <a href="/help/marketo/product-docs/core-marketo-concepts/miscellaneous/marketo-sandbox.md" target="_blank">sandbox-instantie</a>?
   <br/>     Als dat het geval is, bekijkt u de bovenstaande categorieën voor uw sandbox.</li>
<li>Is <a href="/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/import-a-program.md" target="_blank">Programma importeren</a> gekoppeld aan uw sandbox?</li></td>
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
   <td><li><a href="/help/marketo/product-docs/administration/audit-trail/audit-trail-overview.md" target="_blank">Wie werkt</a> in dit geval?</li></td>
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
   <td><li>Hoeveel <a href="/help/marketo/product-docs/administration/workspaces-and-person-partitions/understanding-workspaces-and-person-partitions.md" target="_blank">Werkruimten en/of partities</a> heb je dat?</li>
<li>Wat is het primaire doel van elke Werkruimte en Partitie?</li>
<li>Voer een van de <a href="/help/marketo/product-docs/administration/workspaces-and-person-partitions/edit-a-workspace.md" target="_blank">Werkruimten</a> of <a href="/help/marketo/product-docs/administration/workspaces-and-person-partitions/edit-an-existing-person-partition.md" target="_blank">Partities</a> moet worden gecontroleerd/gewijzigd?</li>
<li>Wat is het verband tussen uw Werkruimten en Verdelingen?</li>
<li>Hoeveel gebruikers <a href="/help/marketo/product-docs/administration/workspaces-and-person-partitions/allow-user-access-to-a-workspace.md" target="_blank">toegang hebben</a> naar elke werkruimte?</li></td>
  </tr>
  <tr> 
   <td>Interne documentatie</td> 
   <td><li>Hoe worden Werkruimten en Partities gedefinieerd?</li>
<li>Wat is uw proces om Werkruimten aan uw instantie toe te voegen of gebruikers aan een Werkruimte toe te voegen?</li></td>
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
   <td>Instellingen voor slimme campagne</td> 
   <td><li><a href="/help/marketo/product-docs/administration/email-setup/enable-person-restrictions-for-smart-campaigns.md" target="_blank">Hebt u een beperking?</a> op grootte van slimme campagne? 
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
   <td><li>Zijn er <a href="/help/marketo/product-docs/administration/email-setup/enable-communication-limits.md" target="_blank">communicatielimieten</a> op zijn plaats? Heeft uw bedrijf beleid waar de communicatie grenzen noodzakelijk zouden kunnen zijn?</li>
<p><img src="assets/note-icon.png" alt="notitiepictogram"> OPMERKING: We raden u aan uw communicatie te beperken tot 1 per dag en 3 per 7 dagen, met <b>non</b>-<a href="/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/make-an-email-operational.md" target="_blank">operationeel</a> e-mailberichten geblokkeerd.</td>
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
   <td><li><a href="/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/understanding-tags.md" target="_blank">Hoeveel tags</a> is dat zo ? Hoeveel tags zijn er in gebruik? Moet er iets worden toegevoegd?</li>
<li>Zijn er labels vereist binnen uw programma's?</li></td>
  </tr>
  <tr> 
   <td>Kanalen</td> 
   <td><li><a href="/help/marketo/product-docs/administration/tags/create-a-program-channel.md" target="_blank">Hoeveel kanalen</a> is dat zo ? Hoeveel zijn er in gebruik?</li>
<li>Alles <a href="/help/marketo/product-docs/administration/tags/hide-unhide-a-program-channel.md" target="_blank">kanaalprogrammstatussen</a>? Tonen zij vooruitgang binnen het programma?</li>
<li>Zijn uw kanalen verwant aan specifieke programmatypes?</li>
<li>Welke statussen worden beschouwd als een succes voor elk kanaal? Lijn die op uw marketingdoelstellingen?</li>
<li>Wordt het operationele kanaal correct gebruikt?</li>
<li>Voor Geavanceerde Report Builder (de Ontdekkingsreiziger van de Cyclus van de Opbrengst/RCE), wordt uw gedrag van de kanaalanalyse geplaatst om zich aan uw programmapraktijken te richten die periodekosten opnemen?</li></td>
  </tr>
  <tr> 
   <td>Verkoopkalender (indien van toepassing)</td> 
   <td><li>Hoeveel <a href="/help/marketo/product-docs/core-marketo-concepts/marketing-calendar/understanding-the-calendar/navigating-the-marketing-calendar.md" target="_blank">Type kalenderinvoer</a> is dat zo ? Zijn ze allemaal nog steeds relevant?</li></td>
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
   <br/>     Klikken <a href="/help/marketo/product-docs/administration/field-management/export-a-list-of-all-marketo-api-field-names.md" target="_blank">Veldnamen exporteren</a> om een lijst met uw velden, aangepaste velden en hun API-namen te bekijken.</li>
<li>Hoeveel <a href="/help/marketo/product-docs/administration/field-management/create-a-custom-field-in-marketo.md" target="_blank">aangepaste velden</a> is dat zo ?</li>
<li>Hoeveel velden worden gebruikt? 
<br/>     Selecteren <a href="/help/marketo/product-docs/administration/field-management/export-used-by-data-for-a-field.md" target="_blank">Exporteren gebruikt door</a> in de vervolgkeuzelijst Veldhandelingen om de gerelateerde elementen van een veld te controleren.</li>
<li>Hoeveel velden worden gesynchroniseerd tussen Marketo Engage en uw CRM?</li>
<li>Worden CRM-velden gesynchroniseerd met de desbetreffende objecten?</li>
<li>Is er een <a href="/help/marketo/product-docs/administration/settings/creating-a-custom-tab-for-the-person-detail-page.md" target="_blank">aangepaste weergaveset</a> voor details van de persoon? Moet dat?</li>
<li>Hebt u een naamgevingsconventie voor uw velden op basis van de bron? 
<br/>     Zo niet, dan kunt u overwegen dit te implementeren.</li>
<li>Zijn er velden? <a href="/help/marketo/product-docs/administration/field-management/block-updates-to-a-field.md" target="_blank">geblokkeerd</a>? 
<br/>     Als dat het geval is, moet u er zeker van zijn dat u begrijpt waarom dat zo is.</li></td>
  </tr>
  <tr> 
   <td>Aangepaste activiteiten</td> 
   <td><li>Zijn er <a href="/help/marketo/product-docs/administration/marketo-custom-activities/understanding-custom-activities.md" target="_blank">aangepaste activiteiten</a>?
<br/>     Als dat het geval is, klikt u erop om te begrijpen welke activiteiten niet gerelateerd zijn aan een Marketo-formulier, e-mail of landingspagina.</li></td>
  </tr>
  <tr> 
   <td>Aangepaste objecten</td> 
   <td><li>Hoeveel <a href="/help/marketo/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md" target="_blank">aangepaste objecten</a> is dat zo ? Hoe worden ze gesynchroniseerd met uw CRM?</li>
<li>Hoe worden deze douanevoorwerpen gebruikt door uw programma's en lijstvragen?</li></td>
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
<li>Gebruikt u een <a href="https://nation.marketo.com/t5/product-blogs/instructions-for-creating-a-custom-sync-rule/ba-p/242758" target="_blank">aangepaste synchronisatie</a>?</li>
<li>[Alleen Salesforce] Heeft uw instantie aangepaste synchronisatiefilters geïmplementeerd? 
<p><img src="assets/note-icon.png" alt="notitiepictogram"> OPMERKING: neem contact op met de ondersteuning van Marketo om Aangepaste synchronisatiefilters te identificeren of om een aangepaste synchronisatieregel te vragen.</li></td>
  </tr>
  <tr> 
   <td>Landingspagina's</td> 
   <td><li>Wat is de <a href="/help/marketo/product-docs/administration/settings/edit-landing-page-settings.md" target="_blank">domeinset als</a>?</li>
   <li>Hoe wordt de homepage ingesteld?</li>
<li>Wat is de <a href="/help/marketo/product-docs/administration/settings/set-a-fallback-page.md" target="_blank">fallback ingesteld als</a>?</li>
<li>Is het vooraf invullen van het formulier ingeschakeld?</li>
<li>zijn <a href="/help/marketo/product-docs/demand-generation/landing-pages/personalizing-landing-pages/enable-personalized-urls-for-your-account.md" target="_blank">gepersonaliseerde URL's</a> ingeschakeld?</li>
<li>Zijn er regels ingesteld voor <a href="/help/marketo/product-docs/demand-generation/landing-pages/landing-page-actions/redirect-a-marketo-landing-page-to-another-page.md" target="_blank">omleiding</a>?</li>
<li>Hebt u domeinaliassen op zijn plaats? Houdt u bij hoe u uw domeinaliassen gebruikt?</li>
<li>Is <a href="https://nation.marketo.com/t5/knowledgebase/setting-up-secured-domains-for-marketo-landing-pages-first-time/ta-p/250370" target="_blank">Beveiligde domeinen voor aanlandingspagina's</a> ingeschakeld? 
<br/>     Bevestig of uw landingspagina-elementen een 'http'-URL bevatten.</li></td>
  </tr>
  <tr> 
   <td>Munchkin</td> 
   <td><li>Is uw <a href="/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md" target="_blank">Munchkin-trackingcode</a> op uw website (Niet in Marketo)?</li>
<li>Is a <a href="/help/marketo/product-docs/administration/settings/edit-do-not-track-browser-support-settings.md" target="_blank">Niet bijhouden</a> Browserverzoek ingeschakeld?</li>
<li>Is uw <a href="https://developers.marketo.com/javascript-api/lead-tracking/" target="_blank">Munchkin-API</a> geconfigureerd? 
<p><img src="assets/tip-icon.png" alt="pictogram tip">TIP: Als u documentatie mist over de plaats waar de code van de munchkin zich op uw website bevindt, kunt u alle URL's bekijken door een <a href="/help/marketo/product-docs/reporting/basic-reporting/report-types/web-page-activity-report.md" target="_blank">Rapport over activiteiten op webpagina</a>.</li></td>
  </tr>
  <tr> 
   <td>Webservices</td> 
   <td><li>zijn <a href="/help/marketo/product-docs/administration/additional-integrations/create-an-allowlist-for-ip-based-api-access.md" target="_blank">IP-beperkingen</a> ingeschakeld? Moeten ze dat zijn?</li>
<li>Welke gebruikers/apps maken API-aanroepen in uw exemplaar?</li>
<li>Raakt u of bijna aan het bereiken van uw API grens? 
<br/>     Als dat het geval is, kunt u overwegen het te verhogen of uw instantie te controleren om die API-aanroepen omlaag te brengen.</li></td>
  </tr>
  <tr> 
   <td>Marketo Sales Insight (indien van toepassing)</td> 
   <td><li>heeft de <a href="/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md" target="_blank">MSI-pakket geïnstalleerd</a>?</li>
<li>Heb je <a href="/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/upgrading/upgrading-your-msi-package.md" target="_blank">bijgewerkt naar de nieuwste versie van Sales Insight</a>?</li>
<li>Hebt u de configuratie van het Inzicht van de Verkoop voltooid? <br/>     Enterprise/Onbeperkte gebruikers <a href="/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-enterprise-unlimited.md" target="_blank">klik hier</a>, professionele gebruikers <a href="/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-professional-edition.md" target="_blank">klik hier</a>.</li>
<li>Heb je <a href="/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/add-sales-insight-permission-set.md" target="_blank">toegang krijgen tot uw gebruikers</a> op basis van het aantal licenties dat u hebt aangeschaft?</li>
<li>zijn <a href="/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/stars-and-flames/customize-stars-and-flames.md" target="_blank">Sterren en lamellen</a> aangepast?</li></td>
  </tr>
  <tr> 
   <td>Launchpoint (indien van toepassing)</td> 
   <td><li>Welke diensten hebben u gevormd (bijvoorbeeld, <a href="/help/marketo/product-docs/administration/additional-integrations/add-webex-as-a-launchpoint-service.md" target="_blank">BrightStor</a>, <a href="/help/marketo/product-docs/administration/additional-integrations/connect-brighttalk-to-marketo.md" target="_blank">Zoomen</a>, enz.)? Zijn ze bijna verlopen?</li>
<li><a href="https://nation.marketo.com/t5/knowledgebase/viewing-your-number-of-api-calls-to-marketo/ta-p/254256" target="_blank">Hoeveel API vraag</a> gebruiken uw integraties?</li>
<li>Hebt u de juiste integraties voor uw gebruiksgevallen?</li></td>
  </tr>
  <tr> 
   <td>Webhaken (indien van toepassing)</td> 
   <td><li><a href="/help/marketo/product-docs/administration/additional-integrations/create-a-webhook.md" target="_blank">Welke verbindingen</a> Heb je je ingesteld?</li>
<li>Zijn er geen personen meer in gebruik?</li></td>
  </tr>
  <tr> 
   <td>Mobiele apps (indien van toepassing)</td> 
   <td><li>Welke <a href="/help/marketo/product-docs/mobile-marketing/admin/add-a-mobile-app.md" target="_blank">mobiele apps</a> heb je dat?</li>
<li>beschikken over <a href="/help/marketo/product-docs/mobile-marketing/push-notifications/adding-a-new-test-device.md" target="_blank">testapparaten</a>  toegevoegd?</li></td>
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
   <td><li>Wat is ingeschakeld in de <a href="/help/marketo/product-docs/administration/settings/enable-or-disable-treasure-chest-features.md" target="_blank">Treasure Chest</a>?</li>
<li>Zijn er functies die moeten worden in- of uitgeschakeld?</li></td>
  </tr>
  <tr> 
   <td>Campagne-controle</td> 
   <td><li>Is <a href="/help/marketo/product-docs/administration/settings/campaign-inspector.md" target="_blank">Campagne-controle</a> ingeschakeld?
<br/>Als dat niet het geval is, kunt u het inschakelen om gemakkelijk te kunnen zien welke campagnes actief zijn, synchroniseren met uw CRM en/of records verwijderen.</li></td>
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
   <td>Statusupdates Marketo Engage</td> 
   <td><li>Is uw instantie geabonneerd op <a href="https://nation.marketo.com/t5/knowledgebase/how-to-subscribe-to-status-page-notifications/ta-p/296749" target="_blank">Statusupdates Marketo Engage</a>?</li></td>
  </tr>
  <tr> 
   <td>Waarschuwingen</td> 
   <td><li>Zijn er <a href="/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/send-alert.md" target="_blank">actieve waarschuwingen</a> vanuit Marketo Engage naar interne teams worden gestuurd?</li>
<li>Zo ja, functioneren deze waarschuwingen naar behoren?</li></td>
  </tr>
  <tr> 
   <td>Meldingen</td> 
   <td><li>Bent u geabonneerd op de juiste beheerder? <a href="/help/marketo/product-docs/core-marketo-concepts/miscellaneous/understanding-notifications.md" target="_blank">meldingen</a>?</li></td>
  </tr>
 </tbody> 
</table>

<br> 

[Een overgeërfde instantie controleren: Database ►](/help/marketo/getting-started/inheriting-a-marketo-instance/database-checklist.md)
