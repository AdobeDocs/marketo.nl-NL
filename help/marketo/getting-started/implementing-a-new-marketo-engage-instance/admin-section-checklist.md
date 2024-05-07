---
description: Stel de sectie Admin in voor uw nieuwe Marketo Engage-instantie.
title: Aanbevolen werkwijzen voor nieuwe instanties - Controlelijst voor sectie Admin
feature: Getting Started
exl-id: 4fa90a32-7e97-404c-90b1-90d05c2561d0
source-git-commit: 14583b7fa148aa2b03c8cf6316b9a106c11717b7
workflow-type: tm+mt
source-wordcount: '634'
ht-degree: 0%

---

# Aanbevolen werkwijzen voor nieuwe instanties: Controlelijst voor sectie Admin {#new-instance-best-practices-admin-section-checklist}

Als nieuwe beheerder die een nieuwe instantie van het Marketo Engage navigeert, pas checklist hieronder toe helpen u door het implementatieproces begeleiden. Net als bij al deze hulplijnen kunt u ook [checklists downloaden](/help/marketo/getting-started/inheriting-a-marketo-engage-instance/assets/adobe-marketo-engage-new-instance-admin-checklist.xlsx) en de voortgang volgen.

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
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.html#create-a-new-role" target="_blank">Een nieuwe rol maken</a> of <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.html#edit-a-role" target="_blank">de rollen bewerken</a> op basis van de behoeften van uw organisatie.</li>
    <li><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/users-and-roles/managing-user-roles-and-permissions#assign-roles-to-a-user" target="_blank">Gebruikers toewijzen aan de juiste rollen</a>. De gebruikers moeten aan het abonnement in Adobe Admin Console worden toegevoegd alvorens hun rollen in "Roles toe te kennen." Raadpleeg de sectie Gebruikers in het dialoogvenster <a href="/help/marketo/getting-started/initial-setup/user-setup.md">Checklist voor eerste setup</a>.</li>
    <li>Nadat u de rollen voor gebruikers hebt toegewezen, controleert u het aantal gebruikers per rol.</li>
    <li>Implementeer een unieke rol voor elke API-gebruiker voor eenvoudige probleemoplossing.</li></td>
  </tr>
  <tr>
    <td>Sandbox (indien van toepassing)</td>
    <td><li>Bekijk bovenstaande rubrieken voor je <a href="/help/marketo/product-docs/core-marketo-concepts/miscellaneous/marketo-sandbox.md" target="_blank">sandbox</a>.</li></td>
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
    <td><li>Bepaal het aantal van<a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/workspaces-and-person-partitions/understanding-workspaces-and-person-partitions.html" target="_blank"> werkruimten</a> en/of partities die uw organisatie nodig heeft en <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/workspaces-and-person-partitions/allow-user-access-to-a-workspace.html" target="_blank">hoeveel gebruikers toegang hebben tot elke werkruimte.</a></li>
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
    <td><li>Voeg een <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/email-setup/enable-person-restrictions-for-smart-campaigns.html" target="_blank">beperking van de grootte van slimme campagnes</a>te voorkomen dat per ongeluk uw gehele database wordt gemaild.</li></td>
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
    <td><li>Implementeren <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/email-setup/enable-communication-limits.html" target="_blank">communicatielimieten</a>.</li>
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
    <td><li>Bepalen hoe u wilt gebruiken <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/tags/create-a-program-channel.html" target="_blank">kanalen</a>.</li></td>
  </tr>
  <tr>
    <td>Tags</td>
    <td><li>Bepalen hoe u wilt gebruiken <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/tags/managing-tag-values.html" target="_blank">tags</a>.</li></td>
  </tr>
  <tr>
    <td>Kalender (indien van toepassing)</td>
    <td><li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/marketing-calendar/understanding-the-calendar/issue-revoke-a-marketing-calendar-license.html" target="_blank">Licentieschema's voor marketingkalenders afgeven</a> aan degenen die toegang nodig hebben.</li>
    <li>Stel de <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/marketing-calendar/understanding-the-calendar/navigating-the-marketing-calendar.html" target="_blank">Kalender</a>.</li></td>
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
    <td><li>Een naamgevingsconventie implementeren voor <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/field-management/create-a-custom-field-in-marketo.html" target="_blank">aangepaste velden</a> (bijvoorbeeld, beginnend met "MKTO").</li>
    <li>Selecteer de velden die u synchroniseert. Hoe meer velden u synchroniseert, hoe langzamer de synchronisatiecyclus wordt.</li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/field-management/block-updates-to-a-field.html" target="_blank">Updates van velden blokkeren</a> u wilt naar één keer schrijven (bijvoorbeeld oorspronkelijke bron, oorspronkelijke brongegevens van de bron, UTM-velden van de eerste aanraking, enz.).</li></td>
  </tr>
  <tr>
    <td>Aangepaste activiteiten</td>
    <td><li>Definiëren <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-custom-activities/understanding-custom-activities.html" target="_blank">Aangepaste activiteiten</a> die specifiek zijn voor uw bedrijf.</li></td>
  </tr>
  <tr>
    <td>Aangepaste objecten</td>
    <td><li>Aantal controleren <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.html" target="_blank">Aangepaste objecten</a> dat is nodig.</li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-custom-object-sync.html" target="_blank">Deze aangepaste objecten synchroniseren</a> aan uw CRM.</li></td>
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
    <td><li>Bepaal de gebruikers/apps die kunnen maken <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/users-and-roles/create-an-api-only-user.html" target="_blank">API-aanroepen</a> in uw exemplaar.</li>
    <li>Controleer alle apps die API-aanroepen maken en bepaal of een toename of afname van API-aanroepen nodig is.</li></td>
  </tr>
  <tr>
    <td>LaunchPoint</td>
    <td><li>Instellen <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/additional-integrations/add-adobe-connect-as-a-launchpoint-service.html" target="_blank">LaunchPoint</a> services voor uw bedrijf. Elk LaunchPoint zou met een unieke API gebruiker aan hulp met het oplossen van problemen moeten worden gecombineerd.</li></td>
  </tr>
  <tr>
    <td>Interactieve webinars (indien van toepassing)</td>
    <td><li>Voor het creëren van Interactieve Webinars, de ingebouwde eigenschap van het Marketo Engage webinar, <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/events/interactive-webinars/user-and-license-management" target="_blank">gebruikers toevoegen aan de sectie Gebruiker</a> op het tabblad Interactief webinar.</li>
    <p><img src="assets/note-icon.png" alt="notitiepictogram"> NOTA: Interactieve Webinars is slechts provisioned aan de instanties van de Productie.</td>
  </tr>
  <tr>
    <td>Adobe Dynamic Chat (indien van toepassing)</td>
    <td><li>Gebruikers toewijzen aan <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/add-or-remove-chat-users#add-dynamic-chat-access-to-marketo-role" target="_blank">Rollen 'Access Dynamic Chat'</a> in Marketo Engage &gt; Beheer &gt; Gebruikers en rollen.</li></td>
  </tr>
  <tr>
    <td>Verkoopoverzicht (indien van toepassing)</td>
    <td><li><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/marketo-sales-insight/actions/getting-started/sales-insight-actions-admin-setup-guide#set-up-marketo-sales-account" target="_blank">Handeling Verkoopinzicht instellen</a> in Sales Insight &gt; Actions Config.</li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/marketo-sales-insight/actions/getting-started/sales-insight-actions-admin-setup-guide.html#invite-individual-users-to-msi-actions" target="_blank">Licenties uitgeven</a> aan passende gebruikers.</li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/marketo-sales-insight-configuration-tab-in-salesforce.html" target="_blank">De API configureren</a>.</li>
    <li>De <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/marketo-sales-insight/msi-for-salesforce/features/stars-and-flames/priority-urgency-relative-score-and-best-bets.html" target="_blank">loodscores</a>.</li></td>
  </tr>
  <tr>
    <td>Verkoopverbinding (indien van toepassing)</td>
    <td><li>Nodig de aangewezen beheerders van het Marketo Engage aan uit <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/marketo-sales-connect/getting-started/accessing-your-new-sales-connect-instance" target="_blank">Sales Connect-exemplaar</a>.</li>
    <li>Voltooi de <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/marketo-sales-connect/getting-started/getting-started-guide-for-sales-connect-admins" target="_blank">Extra installatie van Sales Connect-beheer</a> in Sales Connect en Salesforce.</li></td>
  </tr>
  <tr>
    <td>Webhaken (indien van toepassing)</td>
    <td><li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/additional-integrations/create-a-webhook.html" target="_blank">Vereiste webhaken maken</a> voor uw bedrijf.</li>
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
    <td><li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/settings/enable-or-disable-treasure-chest-features.html" target="_blank">Schatkest inschakelen</a> om te experimenteren met proefuiteinden.</li>
    <li>Bepaal de functies die u wilt in- of uitschakelen.</li></td>
  </tr>
  <tr>
    <td>Campagne-controle </td>
    <td><li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/settings/campaign-inspector.html" target="_blank">Campagnecontrole inschakelen</a> om al uw slimme campagnes op één plaats te bekijken.</li></td>
  </tr>
</tbody>
</table>
