---
unique-page-id: 1146999
description: Tokens voor interessante momenten activeren - Marketo Docs - Productdocumentatie
title: Tokens activeren voor interessante momenten
exl-id: 666a6eed-c432-4088-b4f1-54c996eca64c
feature: Marketo Sales Insights
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '546'
ht-degree: 0%

---

# Tokens activeren voor interessante momenten {#trigger-tokens-for-interesting-moments}

>[!PREREQUISITES]
>
>Leer om de [ het Interesten de stroomstap van de Moment ](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/interesting-moment.md) te gebruiken.

## Beschikbare tokens {#available-tokens}

Controle uit [ het Overzicht van Tokens ](/help/marketo/product-docs/demand-generation/landing-pages/personalizing-landing-pages/tokens-overview.md) om alle tokens te zien u in een interessant moment kunt zetten.

## Triggertokens {#trigger-tokens}

Op basis van de trigger die in een slimme campagne wordt gebruikt, worden extra triggertokens beschikbaar gesteld.

* `{{trigger.Trigger Name}}` dat altijd de werkelijke trigger zelf is. Bijvoorbeeld: klik op Koppeling in e-mail.
* `{{trigger.Name}}` is de naam van het middel dat de campagne heeft gestart. Bijvoorbeeld: klik op Koppeling op webpagina is de URL zelf, afhankelijk van Salesforce-triggers, enzovoort.
* Aanvullende triggers zijn beschikbaar op basis van beperkingen, die hieronder worden weergegeven.

### E-mailtriggers {#email-triggers}

<table style="table-layout:auto">
 <colgroup>
  <col>
  <col>
  <col>
  <col>
  <col>
  <col>
  <col>
  <col>
  <col>
  <col>
  <col>
  <col>
  <col>
  <col>
 </colgroup>
 <tbody>
  <tr>
   <th><br></th>
   <th><code>{{trigger.Trigger Name}}</code></th>
   <th><code>{{trigger.Name}}</code></th>
   <th><code>{{trigger.Link}}</code></th>
   <th><code>{{trigger.Subject}}</code></th>
   <th><code>{{trigger.Category}}</code></th>
   <th><code>{{trigger.Details}}</code></th>
   <th><code>{{trigger.Web Page}}</code></th>
   <th><code>{{trigger.Client IP Address}}</code></th>
   <th><code>{{trigger.Sent By}}</code></th>
   <th><code>{{trigger.Received By}}</code></th>
   <th><code>{{trigger.Referrer}}</code></th>
   <th><code>{{trigger.Search Engine}}</code></th>
   <th><code>{{trigger.Search Query}}</code></th>
   <th><code>{{trigger.Browser}}</code></th>
  </tr>
  <tr>
   <td>Klik op Koppeling in e-mail</td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
  <tr>
   <td>Bounces per e-mail hard</td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
  <tr>
   <td>E-mailgrenzen zacht</td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
  <tr>
   <td>E-mail is bezorgd</td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
  <tr>
   <td>Hiermee opent u e-mail</td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
    <tr>
   <td>E-mail doorgestuurd naar vriend</td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
    <tr>
   <td>Verzonden naar e-mail voor vriend</td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="controleren"></td>
  </tr>
  <tr>
   <td>Abonnement op e-mail opzeggen</td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
 </tbody>
</table>

### Salesforce Triggers {#salesforce-triggers}

<table style="table-layout:auto">
 <colgroup>
  <col>
  <col>
  <col>
  <col>
  <col>
  <col>
  <col>
  <col>
  <col>
  <col>
  <col>
  <col>
  <col>
  <col>
 </colgroup>
 <tbody>
  <tr>
   <th><br></th>
   <th><code>{{trigger.Trigger Name}}</code></th>
   <th><code>{{trigger.Name}}</code></th>
   <th><code>{{trigger.Link}}</code></th>
   <th><code>{{trigger.Subject}}</code></th>
   <th><code>{{trigger.Category}}</code></th>
   <th><code>{{trigger.Details}}</code></th>
   <th><code>{{trigger.Web Page}}</code></th>
   <th><code>{{trigger.Client IP Address}}</code></th>
   <th><code>{{trigger.Sent By}}</code></th>
   <th><code>{{trigger.Received By}}</code></th>
   <th><code>{{trigger.Referrer}}</code></th>
   <th><code>{{trigger.Search Engine}}</code></th>
   <th><code>{{trigger.Search Query}}</code></th>
   <th><code>{{trigger.Browser}}</code></th>
  </tr>
  <tr>
   <td>Klik op Koppeling in e-mail Verkoop</td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
  <tr>
   <td>Verzende-mail</td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
  <tr>
   <td>Verkoopbericht openen</td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
  <tr>
   <td>Bounges e-mail verkoop</td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
  <tr>
   <td>Verkoop-e-mail ontvangen</td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
    <tr>
   <td>Opportunity is bijgewerkt</td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
    <tr>
   <td>Wijzigingen eigenaar</td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
  <tr>
   <td>Persoon is omgezet</td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
  <tr>
   <td>Persoon wordt uit SFDC verwijderd</td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
  <tr>
   <td>Persoon is gesynchroniseerd met SFDC</td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
  <tr>
   <td>Verwijderd uit opportunity</td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
  <tr>
   <td>Verwijderd uit SFDC-campagne</td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
  <tr>
   <td>De activiteit is geregistreerd</td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
  <tr>
   <td>Activiteit is bijgewerkt</td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
  <tr>
   <td>Toegevoegd aan opportunity</td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
  <tr>
   <td>Toegevoegd aan SFDC-campagne</td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
  <tr>
   <td>Status is gewijzigd in SFDC-campagne</td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
 </tbody>
</table>

### Verkoop Connect-triggers {#sales-connect-triggers}

<table style="table-layout:auto">
 <colgroup>
  <col>
  <col>
  <col>
  <col>
  <col>
  <col>
  <col>
  <col>
  <col>
  <col>
  <col>
  <col>
  <col>
  <col>
 </colgroup>
 <tbody>
  <tr>
   <th><br></th>
   <th><code>{{trigger.Trigger Name}}</code></th>
   <th><code>{{trigger.Name}}</code></th>
   <th><code>{{trigger.Link}}</code></th>
   <th><code>{{trigger.Subject}}</code></th>
   <th><code>{{trigger.Category}}</code></th>
   <th><code>{{trigger.Details}}</code></th>
   <th><code>{{trigger.Web Page}}</code></th>
   <th><code>{{trigger.Client IP Address}}</code></th>
   <th><code>{{trigger.Sent By}}</code></th>
   <th><code>{{trigger.Received By}}</code></th>
   <th><code>{{trigger.Referrer}}</code></th>
   <th><code>{{trigger.Search Engine}}</code></th>
   <th><code>{{trigger.Search Query}}</code></th>
   <th><code>{{trigger.Browser}}</code></th>
  </tr>
  <tr>
   <td>Klik op Koppeling in e-mail Verkoop</td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
  <tr>
   <td>Verzende-mail</td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
  <tr>
   <td>Verkoopbericht openen</td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
  <tr>
   <td>Bounges e-mail verkoop</td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
  <tr>
   <td>Verkoop-e-mail ontvangen</td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
  <tr>
   <td>Wordt toegevoegd aan verkoopcampagne</td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
  <tr>
   <td>Wijzigingen eigenaar</td>
   <td>Is verwijderd uit verkoopcampagne</td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
  <tr>
   <td>Ontvangen verkoopoproep</td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
 </tbody>
</table>

### Dynamic Chat Trigger Tokens {#dynamic-chat-trigger-tokens}

<table>
<thead>
  <tr>
    <th> </th>
    <th><code>{{trigger.Agent Email}}</code></th>
    <th><code>{{trigger.Agent Name}}</code></th>
    <th><code>{{trigger.Conversation Status}}</code></th>
    <th><code>{{trigger.Conversation Summary}}</code></th>
    <th><code>{{trigger.Conversation Transcript}}</code></th>
    <th><code>{{trigger.Document Downloaded}}</code></th>
    <th><code>{{trigger.Document Name}}</code></th>
    <th><code>{{trigger.Document Opened}}</code></th>
    <th><code>{{trigger.Document URL}}</code></th>
    <th><code>{{trigger.Goal name}}</code></th>
    <th><code>{{trigger.meeting status}}</code></th>
    <th><code>{{trigger.Name}}</code></th>
    <th><code>{{trigger.Page URL}}</code></th>
    <th><code>{{trigger.routing queue name}}</code></th>
    <th><code>{{trigger.Scheduled For}}</code></th>
    <th><code>{{trigger.source name}}</code></th>
    <th><code>{{trigger.source type}}</code></th>
    <th><code>{{trigger.Trigger Name}}</code></th>
    <th><code>{{trigger.ui type}}</code></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Bij een dialoogvenster</td>
    <td></td>
    <td></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Gegroepeerd met een gespreksformulier</td>
    <td></td>
    <td></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td></td>
    <td></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td></td>
    <td><img src="assets/check.png" alt="controleren"></td>
  </tr>
  <tr>
    <td>Betrokken met een Agent in Dialoog</td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Betrokken bij een Agent in Gesprek Vorm</td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Geplande vergadering in dialoogvenster</td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Geplande vergadering in gespreksvorm</td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Dialoogvenster bereikt</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Gesprek doel van het Vorm</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Interactie met document in dialoogvenster</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td></td>
    <td></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Werkt met document in gespreksvorm</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td></td>
    <td></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td><img src="assets/check.png" alt="controleren"></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</tbody>
</table>

### Overige {#miscellaneous}

<table style="table-layout:auto">
 <colgroup>
  <col>
  <col>
  <col>
  <col>
  <col>
  <col>
  <col>
  <col>
  <col>
  <col>
  <col>
  <col>
  <col>
  <col>
 </colgroup>
 <tbody>
  <tr>
   <th><br></th>
   <th><code>{{trigger.Trigger Name}}</code></th>
   <th><code>{{trigger.Name}}</code></th>
   <th><code>{{trigger.Link}}</code></th>
   <th><code>{{trigger.Subject}}</code></th>
   <th><code>{{trigger.Category}}</code></th>
   <th><code>{{trigger.Details}}</code></th>
   <th><code>{{trigger.Web Page}}</code></th>
   <th><code>{{trigger.Client IP Address}}</code></th>
   <th><code>{{trigger.Sent By}}</code></th>
   <th><code>{{trigger.Received By}}</code></th>
   <th><code>{{trigger.Referrer}}</code></th>
   <th><code>{{trigger.Search Engine}}</code></th>
   <th><code>{{trigger.Search Query}}</code></th>
   <th><code>{{trigger.Browser}}</code></th>
  </tr>
  <tr>
   <td>Formulier wordt ingevuld</td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
  <tr>
   <td>Bezoek de webpagina</td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
  </tr>
  <tr>
   <td>Klik op Koppeling op webpagina</td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="controleren"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
 </tbody>
</table>

>[!NOTE]
>
>Als het geen controle ![ (tikken) ](assets/check.png) heeft dan zou het een leeg koord (niets) in het interessante ogenblik terugkeren.

&#42; Trigger **bezoekt Web-pagina** een paar extra tokens:

* `{{trigger.Referrer}}`
* `{{trigger.Search Engine}}`
* `{{trigger.Search Query}}`

>[!TIP]
>
>Test altijd uw interessante momenten uit om ervoor te zorgen dat ze de gewenste manier weergeven.
>
>Zorg er ook voor dat het interessant is voor de verkoper, niet alleen voor jou!
