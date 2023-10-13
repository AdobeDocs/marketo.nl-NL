---
unique-page-id: 1147114
description: Mijn tokens in een programma begrijpen - Marketo Docs - Productdocumentatie
title: Mijn tokens in een programma begrijpen
exl-id: 01b42272-c419-4cd5-ad30-87413ceb2032
feature: Tokens
source-git-commit: b21f955bf98063e11f8ed3fdc6f164134ee4f5aa
workflow-type: tm+mt
source-wordcount: '416'
ht-degree: 0%

---

# Mijn tokens in een programma begrijpen {#understanding-my-tokens-in-a-program}

Een token is een variabele die u kunt gebruiken in e-mails, bestemmingspagina&#39;s en slimme campagnes om uw leven gemakkelijker te maken.

Naast Mijn tokens kunt u ook alle ingebouwde tokens in uw programma&#39;s gebruiken. Kijk uit de [Overzicht van tokens](/help/marketo/product-docs/demand-generation/landing-pages/personalizing-landing-pages/tokens-overview.md){target="_blank"}.

## Mijn tokens  {#my-tokens}

Mijn tokens zijn aangepaste variabelen die iedereen kan maken. Ze zijn [gemaakt](/help/marketo/product-docs/core-marketo-concepts/programs/tokens/managing-my-tokens.md){target="_blank"} in campagnemappen of -programma&#39;s.

Mijn tokens worden als volgt weergegeven: `{{my.Name Of Token}}`

Voorbeelden:

* `{{my.Event Date}}`
* `{{my.Webinar Speaker}}`

<table> 
 <thead> 
  <tr> 
   <th>Type token</th> 
   <th>Beschrijving</th> 
  </tr> 
 </thead> 
 <tbody> 
  <tr> 
   <td>Kalenderbestand <img alt="—" src="assets/image2014-9-25-16-3a44-3a19.png" data-linked-resource-id="3083230" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="1147114"></td> 
   <td>Gebruik deze token om <a href="/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/create-a-calendar-event-ics-file.md">een agenda-gebeurtenisbestand toevoegen (.i</a><a href="/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/create-a-calendar-event-ics-file.md">cs)</a> op uw e-mails en landingspagina's.</td> 
  </tr> 
  <tr> 
   <td><p>Datum <img alt="--" src="assets/image2014-9-25-16-3a44-3a47.png" data-linked-resource-id="3083231" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="1147114"></p></td> 
   <td>Dit token bevat een datumwaarde. De datum wordt weergegeven als dag van de maand (bijvoorbeeld 2016-05-23).</td> 
  </tr> 
  <tr> 
   <td>E-mailscript <img alt="--" src="assets/image2014-9-25-16-3a45-3a4.png" data-linked-resource-id="3083232" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="1147114"></td> 
   <td>Gebruik deze token om een snelheidsscript in uw e-mails uit te voeren. Meer informatie <a href="https://developers.marketo.com/documentation/email-scripting/" title="Koppeling volgen" rel="nofollow">hier</a>. </td> 
  </tr> 
  <tr> 
   <td>Getal<span> <img alt="--" src="assets/image2014-9-25-16-3a45-3a25.png" data-linked-resource-id="3083233" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="1147114"></span></td> 
   <td>Een geheel getal. Het kan zelfs negatief zijn.</td> 
  </tr> 
  <tr> 
   <td>RTF <img alt="--" src="assets/image2014-9-25-16-3a46-3a22.png" data-linked-resource-id="3083234" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="1147114"></td> 
   <td>Dit is HTML. Gebruik dit in e-mails en landingspagina's.</td> 
  </tr> 
  <tr> 
   <td>Score <img alt="--" src="assets/image2014-9-25-16-3a46-3a39.png" data-linked-resource-id="3083235" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="1147114"></td> 
   <td>Deze token gebruiken in het dialoogvenster <a href="/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/use-tokens-in-flow-steps.md">stap voor statusdoorloop wijzigen</a>. </td> 
  </tr> 
  <tr> 
   <td colspan="1">SFDC-campagne <img alt="--" src="assets/sfdc-campaign-icon.jpg" data-linked-resource-id="11379761" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="1147114" title="--"></td> 
   <td colspan="1">Gebruik dit token om toe te staan dat leads die onderdeel worden van een Marketo-programma ook worden toegevoegd aan SFDC-campagnes.</td> 
  </tr> 
  <tr> 
   <td>Tekst <img alt="--" src="assets/image2014-9-25-16-3a46-3a54.png" data-linked-resource-id="3083236" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="1147114"></td> 
   <td>Gewoon wat tekst. Gebruik het als HTML overmatig is. De formaatlimiet voor Text-tokens is 524.288 tekens (UTF-8) of 2 MB.</td> 
  </tr> 
 </tbody> 
</table>

>[!CAUTION]
>
>Mijn tokens zullen niet oplossen wanneer het verzenden van een e-mail van het Inzicht van de Verkoop op of de Dynamiek van Microsoft of Salesforce; slechts standaardtokens zullen bevolken (Lood, Bedrijf, enz.). Standaardwaarden voor tokens _zal_ werk echter .

## Nesten van tokens {#nesting-tokens}

Wanneer u een nieuw token maakt, kan hiernaar worden verwezen door andere objecten in de structuur. Er is een naamgevingsstructuur voor de plaats waar het token is gemaakt voor eenvoudig beheer.

* **Lokaal token:** Het token is direct in dat programma of die map gemaakt.
* **Overgenomen token:** Het token is ergens in een programma of map op een hoger niveau in de structuur gemaakt.
* **Overschreven token:** Het token werd overgeërfd en vervolgens maakte iemand een uitzondering in dit programma of deze map.

U kunt globale variabelen maken en dan hen met voeten treden op lagere niveaus in de boom.

Het verplaatsen van programma&#39;s en omslagen beïnvloedt ook tokens. Controleer altijd of verwijzingen niet worden verbroken tijdens het verplaatsen.

>[!NOTE]
>
>Als de e-mail die u verzendt vanuit een betrokkenheidsprogramma een onderliggende e-mail is van een standaardprogramma (niet lokaal naar uw betrokkenheidsprogramma), worden alle My Tokens die in de e-mail worden gebruikt, opgelost vanuit het standaardprogramma waarin de onderliggende e-mail zich bevindt.

>[!MORELIKETHIS]
>
>* [Overzicht van tokens](/help/marketo/product-docs/demand-generation/landing-pages/personalizing-landing-pages/tokens-overview.md){target="_blank"}
>* [Mijn tokens beheren](/help/marketo/product-docs/core-marketo-concepts/programs/tokens/managing-my-tokens.md){target="_blank"}
