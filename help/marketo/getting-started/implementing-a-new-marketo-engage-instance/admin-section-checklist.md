---
description: Stel de sectie Admin in voor uw nieuwe Marketo Engage-exemplaar.
title: Aanbevolen werkwijzen voor nieuwe instanties - Controlelijst voor sectie Admin
feature: Getting Started
exl-id: 4fa90a32-7e97-404c-90b1-90d05c2561d0
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '634'
ht-degree: 0%

---

# Aanbevolen werkwijzen voor nieuwe instanties: Controlelijst voor sectie Admin {#new-instance-best-practices-admin-section-checklist}

Als nieuwe beheerder die door een nieuwe instantie van Marketo Engage navigeert, pas checklist hieronder toe om u door het implementatieproces te begeleiden. Zoals met elk van deze gidsen, kunt u ook [&#x200B; de controlelijsten &#x200B;](/help/marketo/getting-started/implementing-a-new-marketo-engage-instance/assets/adobe-marketo-engage-new-instance-admin-checklist.xlsx) downloaden en uw vooruitgang volgen.

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
    <td><li>Herzie de prebuilt rollen en bevestig welke toestemmingen/toegang elke rol heeft.</li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.html?lang=nl-NL#create-a-new-role" target="_blank"> creeer een nieuwe rol </a> of <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.html?lang=nl-NL#edit-a-role" target="_blank"> geef de rollen </a> uit die op de behoeften van uw organisatie worden gebaseerd.</li>
    <li><a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/administration/users-and-roles/managing-user-roles-and-permissions#assign-roles-to-a-user" target="_blank"> wijs gebruikers aan de aangewezen rollen </a> toe. De gebruikers moeten aan het abonnement in Adobe Admin Console worden toegevoegd alvorens hun rollen in "Roles toe te kennen." Verwijs naar de sectie van Gebruikers in de <a href="/help/marketo/getting-started/initial-setup/user-setup.md"> Aanvankelijke checklist van de Opstelling </a>.</li>
    <li>Nadat u de rollen voor gebruikers hebt toegewezen, controleert u het aantal gebruikers per rol.</li>
    <li>Implementeer een unieke rol voor elke API-gebruiker voor eenvoudige probleemoplossing.</li></td>
  </tr>
  <tr>
    <td>Sandbox (indien van toepassing)</td>
    <td><li>Herzie de categorieën hierboven voor uw <a href="/help/marketo/product-docs/core-marketo-concepts/miscellaneous/marketo-sandbox.md" target="_blank"> zandbak </a>.</li></td>
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
    <td><li>Bepaal het aantal <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/workspaces-and-person-partitions/understanding-workspaces-and-person-partitions.html?lang=nl-NL" target="_blank"> werkruimten </a> en/of verdelingen dat uw organisatie moet hebben en <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/workspaces-and-person-partitions/allow-user-access-to-a-workspace.html?lang=nl-NL" target="_blank"> hoeveel gebruikers toegang tot elke werkruimte hebben.</a></li>
    <li>Bepaal het primaire doel van elke werkruimte en verdeling.</li>
    <li>Bepaal de verhouding tussen uw werkruimten en verdelingen.</li></td>
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
<tbody>
  <tr>
    <td>Instellingen voor slimme campagne</td>
    <td><li>Voeg a <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/email-setup/enable-person-restrictions-for-smart-campaigns.html?lang=nl-NL" target="_blank"> beperking op Slimme grootte van de Campagne </a> toe, die toevallig uw volledig gegevensbestand e-mail verhindert.</li></td>
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
    <td><li>Voer <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/email-setup/enable-communication-limits.html?lang=nl-NL" target="_blank"> communicatie grenzen </a> uit.</li>
    <li>Bepaal als uw zaken een beleid op communicatie grenzen vereisen.</li></td>
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
    <td><li>Bepaal hoe te om <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/tags/create-a-program-channel.html?lang=nl-NL" target="_blank"> kanalen </a> te gebruiken.</li></td>
  </tr>
  <tr>
    <td>Tags</td>
    <td><li>Bepaal hoe te om <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/tags/managing-tag-values.html?lang=nl-NL" target="_blank"> markeringen </a> te gebruiken.</li></td>
  </tr>
  <tr>
    <td>Kalender <br>
    (indien van toepassing)</td>
    <td><li>{de plaatsen van de Kalender van de Verkoop van 0} kwestie <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/marketing-calendar/understanding-the-calendar/issue-revoke-a-marketing-calendar-license.html?lang=nl-NL" target="_blank"> aan hen die toegang nodig hebben.</a></li>
    <li>Opstelling de <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/marketing-calendar/understanding-the-calendar/navigating-the-marketing-calendar.html?lang=nl-NL" target="_blank"> Kalender </a>.</li></td>
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
    <td><li>Voer een noemende overeenkomst voor <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/field-management/create-a-custom-field-in-marketo.html?lang=nl-NL" target="_blank"> douanegebieden </a> uit (bijvoorbeeld, die met "MKTO"beginnen).</li>
    <li>Selecteer de velden die u synchroniseert. Hoe meer velden u synchroniseert, hoe langzamer de synchronisatiecyclus wordt.</li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/field-management/block-updates-to-a-field.html?lang=nl-NL" target="_blank"> de updates van het Blok aan gebieden </a> u aan één keer (b.v., originele loodbron, oorspronkelijk lood brondetail, eerste aanrakingUTM gebieden, enz.) wilt schrijven.</li></td>
  </tr>
  <tr>
    <td>Aangepaste activiteiten</td>
    <td><li>Bepaal <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-custom-activities/understanding-custom-activities.html?lang=nl-NL" target="_blank"> Activiteiten van de Douane </a> die voor uw zaken specifiek zijn.</li></td>
  </tr>
  <tr>
    <td>Aangepaste objecten</td>
    <td><li>Herzie hoeveel <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.html?lang=nl-NL" target="_blank"> Douane Voorwerpen </a> u nodig hebt.</li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-custom-object-sync.html?lang=nl-NL" target="_blank"> synchroniseer die Voorwerpen van de Douane </a> aan uw CRM.</li></td>
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
    <td><li>Identificeer de toestemmingen u tot uw CRM moet toegang hebben.</li>
    <li>Identificeer uw beheerder van CRM voor het oplossen van problemen.</li></td>
  </tr>
  <tr>
    <td>Webservices</td>
    <td><li>Bepaal de gebruikers/apps die <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/users-and-roles/create-an-api-only-user.html?lang=nl-NL" target="_blank"> API vraag </a> in uw instantie kunnen maken.</li>
    <li>Controleer alle apps die API-aanroepen maken en bepaal of een toename of afname van API-aanroepen nodig is.</li></td>
  </tr>
  <tr>
    <td>LaunchPoint</td>
    <td><li>De diensten van de Opstelling <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/additional-integrations/add-adobe-connect-as-a-launchpoint-service.html?lang=nl-NL" target="_blank"> LaunchPoint </a> voor uw zaken. Elk LaunchPoint zou met een unieke API gebruiker aan hulp met het oplossen van problemen moeten worden gecombineerd.</li></td>
  </tr>
  <tr>
    <td>Interactieve webinars (indien van toepassing)</td>
    <td><li>Voor het creëren van Interactieve Webinars, voegt de ingebouwde eigenschap van Marketo Engage webinar, <a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/demand-generation/events/interactive-webinars/user-and-license-management" target="_blank"> gebruikers aan de sectie van de "Gebruiker"</a> op het Interactieve Webinar lusje toe.</li>
    <p><img src="assets/note-icon.png" alt="notitiepictogram"> NOTA: Interactieve Webinars is slechts provisioned aan de instanties van de Productie.</td>
  </tr>
  <tr>
    <td>Adobe Dynamic Chat (indien van toepassing)</td>
    <td><li>Wijs gebruikers toe aan <a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/add-or-remove-chat-users#add-dynamic-chat-access-to-marketo-role" target="_blank"> 'Access Dynamic Chat'-rollen </a> in Marketo Engage &gt; Admin &gt; Users &amp; Roles.</li></td>
  </tr>
  <tr>
    <td>Verkoopmanager (indien van toepassing)</td>
    <td><li><a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/marketo-sales-insight/actions/getting-started/sales-insight-actions-admin-setup-guide#set-up-marketo-sales-account" target="_blank"> de Actie van Insight van de Verkoop van de Opstelling </a> in de Verkoop Insight &gt; Config van Acties.</li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/marketo-sales-insight/actions/getting-started/sales-insight-actions-admin-setup-guide.html?lang=nl-NL#invite-individual-users-to-msi-actions" target="_blank"> de plaatsen van de Kwestie </a> aan aangewezen gebruikers.</li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/marketo-sales-insight-configuration-tab-in-salesforce.html?lang=nl-NL" target="_blank"> vorm API </a>.</li>
    <li>Pas de <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/marketo-sales-insight/msi-for-salesforce/features/stars-and-flames/priority-urgency-relative-score-and-best-bets.html?lang=nl-NL" target="_blank"> loodscores </a> aan.</li></td>
  </tr>
  <tr>
    <td>Verkoopverbinding (indien van toepassing)</td>
    <td><li>Nodig de aangewezen beheerders van Marketo Engage aan de <a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/marketo-sales-connect/getting-started/accessing-your-new-sales-connect-instance" target="_blank"> instantie van Verkoop Connect </a> uit.</li>
    <li>Voltooi de <a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/marketo-sales-connect/getting-started/getting-started-guide-for-sales-connect-admins" target="_blank"> extra Opstelling van Connect van de Verkoop </a> in Verkoop Connect en Salesforce.</li></td>
  </tr>
  <tr>
    <td>Webhaken (indien van toepassing)</td>
    <td><li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/additional-integrations/create-a-webhook.html?lang=nl-NL" target="_blank"> creeer om het even welke vereiste Webhooks </a> voor uw zaken.</li>
    </td>
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
    <td><li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/settings/enable-or-disable-treasure-chest-features.html?lang=nl-NL" target="_blank"> laat de Borst van de Schat </a> toe om met het uitrekken eigenschappen te experimenteren.</li>
    <li>Bepaal de functies die u wilt in- of uitschakelen.</li></td>
  </tr>
  <tr>
    <td>Campagne-controle </td>
    <td><li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/settings/campaign-inspector.html?lang=nl-NL" target="_blank"> draai de Inspecteur van de Campagne </a> aan om al uw Slimme Campagnes in één plaats te bekijken.</li></td>
  </tr>
</tbody>
</table>
