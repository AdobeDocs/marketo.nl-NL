---
unique-page-id: 1146999
description: Tokens voor interessante momenten - Marketo Docs - Productdocumentatie
title: Tokens voor interessante momenten
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '265'
ht-degree: 0%

---


# Tokens voor interessante momenten {#tokens-for-interesting-moments}

>[!PREREQUISITES]
>
>* Leer hoe u de [interrustende stroomstap](../../../../../../product-docs/core-marketo-concepts/smart-campaigns/flow-actions/interesting-moment.md)voor momenten gebruikt.
>* Meer weten over [tokens](http://docs.marketo.com/display/docs/tokens)?

>



## Beschikbare tokens {#available-tokens}

Bekijk het [Tokens Overzicht](../../../../../../product-docs/demand-generation/landing-pages/personalizing-landing-pages/tokens-overview.md) om alle tokens te zien die u in een interessant moment kunt zetten.

## Tokens activeren {#trigger-tokens}

Op basis van de trigger die in een slimme campagne wordt gebruikt, worden extra triggertokens beschikbaar gesteld.

* `{{trigger.Trigger Name}}` dat altijd de eigenlijke trigger zelf is. Bijvoorbeeld: Klik op Koppelen in e-mail.
* `{{trigger.Name}}` Dit is de naam van het element dat de campagne heeft gestart. Bijvoorbeeld: Klik op Koppeling op webpagina is de URL zelf, afhankelijk van Salesforce-triggers, enzovoort.
* Aanvullende triggers zijn beschikbaar op basis van beperkingen, die hieronder worden weergegeven:

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
  </tr> 
  <tr> 
   <td>Abonnement op e-mail opzeggen</td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td> 
   <td><br></td> 
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
   <td><br></td> 
  </tr> 
  <tr> 
   <td>E-mail over verkoop verzonden</td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>Verkoopbericht openen</td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>Verkoop-e-mail ontvangen</td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tik)"></td> 
  </tr> 
  <tr> 
   <td colspan="1">Verkoop-e-mail teruggestuurd</td> 
   <td colspan="1"><img src="assets/check.svg" alt="(tik)"></td> 
   <td colspan="1"><img src="assets/check.svg" alt="(tik)"></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
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
   <td><p><br></p></td> 
  </tr> 
  <tr> 
   <td colspan="1">Bezoek de webpagina*</td> 
   <td colspan="1"><img src="assets/check.svg" alt="(tik)"></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><img src="assets/check.svg" alt="(tik)"></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
 </tbody> 
</table>

>[!NOTE]
>
>Als het geen controle heeft ![(tik)](assets/check.svg) dan zou het een lege koord (niets) op het interessante ogenblik terugkeren.

*De webpagina **van Trigger-** bezoeken bevat een aantal extra tokens:

* `{{trigger.Referrer}}`
* `{{trigger.Search Engine}}`
* `{{trigger.Search Query}}`

>[!TIP]
>
>Test altijd uw interessante momenten uit om ervoor te zorgen dat ze de gewenste manier weergeven.
>
>Zorg er ook voor dat het interessant is voor de verkoper, niet alleen voor jou. ![(wink)](assets/wink.svg)>

