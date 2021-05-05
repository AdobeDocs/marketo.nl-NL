---
unique-page-id: 1146999
description: Tokens voor interessante momenten activeren - Marketo Docs - Productdocumentatie
title: Tokens activeren voor interessante momenten
exl-id: 666a6eed-c432-4088-b4f1-54c996eca64c
translation-type: tm+mt
source-git-commit: 20a3bee9973340d7b772532d1be31fe745e5ffd7
workflow-type: tm+mt
source-wordcount: '437'
ht-degree: 0%

---

# Tokens voor interessante momenten {#trigger-tokens-for-interesting-moments} activeren

>[!PREREQUISITES]
>
>Leer om [Interesserende de stroomstap van het Moment te gebruiken](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/interesting-moment.md).

## Beschikbare tokens {#available-tokens}

Bekijk [Tokens Overzicht](/help/marketo/product-docs/demand-generation/landing-pages/personalizing-landing-pages/tokens-overview.md) om alle tokens te zien u in een interessant moment kunt zetten.

## Tokens {#trigger-tokens} activeren

Op basis van de trigger die in een slimme campagne wordt gebruikt, worden extra triggertokens beschikbaar gesteld.

* `{{trigger.Trigger Name}}` dat altijd de eigenlijke trigger zelf is. Bijvoorbeeld: Klik op Koppelen in e-mail.
* `{{trigger.Name}}` Dit is de naam van het element dat de campagne heeft gestart. Bijvoorbeeld: Klik op Koppeling op webpagina is de URL zelf, afhankelijk van Salesforce-triggers, enzovoort.
* Aanvullende triggers zijn beschikbaar op basis van beperkingen, die hieronder worden weergegeven.

**E-mailtriggers**

<table> 
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
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
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
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
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
   <td>Bounces zacht e-mailen</td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
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
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
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
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
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
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
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
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td>
  </tr> 
  <tr> 
   <td>Abonnement op e-mail opzeggen</td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
 </tbody> 
</table>

**Salesforce Triggers**

<table> 
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
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td>
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>Verzende-mail</td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td>
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>Verkoopbericht openen</td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td>
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>Bounces verkoope-mail</td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
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
   <td>Verkoop-e-mail is ontvangen</td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td> 
   <td><br></td>
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
    <tr> 
   <td>Opportunity is bijgewerkt</td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
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
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
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
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
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
   <td>Persoon wordt verwijderd uit SFDC</td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
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
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
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
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
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
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
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
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
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
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
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
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
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
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
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

**Verkoop Connect-triggers**

<table> 
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
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td>
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>Verzende-mail</td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td>
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>Verkoopbericht openen</td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td>
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>Bounces verkoope-mail</td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
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
   <td>Verkoop-e-mail is ontvangen</td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td>
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>Wordt toegevoegd aan verkoopcampagne</td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
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
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
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
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
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

**Diversen**

<table> 
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
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>Bezoek de webpagina</td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>Klik op Koppeling op webpagina</td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
 </tbody> 
</table>

>[!NOTE]
>
>Als er geen controle ![(tik)](assets/check.svg) is, wordt er op het interessante moment een lege tekenreeks (niets) geretourneerd.

*Trigger **Bezoekt Web-pagina** heeft een paar extra tokens:

* `{{trigger.Referrer}}`
* `{{trigger.Search Engine}}`
* `{{trigger.Search Query}}`

>[!TIP]
>
>Test altijd uw interessante momenten uit om ervoor te zorgen dat ze de gewenste manier weergeven.
>
>Zorg er ook voor dat het interessant is voor de verkoper, niet alleen voor jou. ![(wink)](assets/wink.svg)>
