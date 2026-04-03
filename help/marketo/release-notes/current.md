---
description: Huidige aanvullende informatie - Documentatie voor Marketo - Productdocumentatie
title: Opmerkingen bij de huidige release
exl-id: a2eccad5-73ad-48f9-8091-51cee23824e1
feature: Release Information
source-git-commit: 1850dd03baba259e99e8cc089b39f35735e63fdf
workflow-type: tm+mt
source-wordcount: '462'
ht-degree: 2%

---

# Opmerkingen bij de release: maart 2026 {#release-notes-mar-26}

Hieronder vindt u alle functies die zijn opgenomen in de release van 26 maart. Raadpleeg de Adobe Marketo Engage-editie voor informatie over de beschikbaarheid van functies.

De Nota&#39;s van de Versie specifiek voor Adobe Dynamic Chat [&#x200B; kunnen hier &#x200B;](/help/marketo/release-notes/dynamic-chat.md){target="_blank"} worden gevonden.

## Standaardfuncties van releasecyclus {#standard-release-cycle-features}

De volgende eigenschappen vallen onder de standaardversiecyclus en zullen beginnen om op **Maart 27, 2026**, met een gefaseerde uitrol van resterende eigenschappen in de verdere weken worden vrijgegeven. De functies en datums van de release kunnen worden gewijzigd. Controleer de status naast elke functie.

<table style="table-layout:auto">
 <tbody>
 <tr>
   <th style="width:65%">Functie</th>
   <th style="width:10%">Status</th>
   <th style="width:25%">Documentatie</th>
  </tr>
  <tr>
   <td><strong> E-mail Designer - beheert Merken (bèta) </strong>: produceer e-mailinhoud die op de specifieke auteursrichtlijnen van uw organisatie/merk wordt gebaseerd.</td>
   <td>Vrijgegeven</td>
   <td><a href="/help/marketo/product-docs/email-marketing/email-designer/brands/manage-brands.md" target="_blank">Merken maken en beheren</a></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong> E-mail Designer - Snelle Acties </strong>: <i> Pariteit met de oude e-mailredacteur </i>. Snelle acties zijn nu beschikbaar voor alle e-mailmiddelen van Designer (e-mails, e-mailsjablonen, fragmenten). Tot de ondersteunde snelle acties behoren: Dupliceren, Verwijderen, Verplaatsen, Concept maken/bewerken.
   </td>
   <td>Vrijgegeven</i></td>
   <td>nvt</td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong> E-mail Designer - de Controleur van de Kwaliteit van het Merk </strong>: Beoordeel algemene inhoudkwaliteit om potentiële kwesties met leesbaarheid, inhoud cohesie, en doeltreffendheid, onafhankelijk van uw merkrichtlijnen te identificeren.</td>
   <td><i>Binnenkort beschikbaar</i></td>
   <td><i>Binnenkort beschikbaar</i></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong> E-mail Designer - het Teruggeven van Vooruitzichten bevestigen </strong>: Deze update lost teruggevende kwesties, vooral in de Vooruitzichten van MS op. Met de modus Expert kunt u kleine HTML/CSS-bewerkingen uitvoeren of scripttags toevoegen aan uw e-mail (de beste manier is om geen andere wijzigingen aan te brengen in de HTML van de e-mail, zodat de visuele elementen ongewijzigd blijven).
   </td>
   <td><i>Binnenkort beschikbaar</i></td>
   <td><i>Binnenkort beschikbaar</i></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong> Beheer van de Bestellijst </strong>: U kunt de waarden nu specificeren die op gebieden in Marketo Engage kunnen worden gebruikt.
   </td>
   <td><i>Binnenkort beschikbaar</i></td>
   <td><i>Binnenkort beschikbaar</i></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong> Push Meldingen </strong>: Redirect URLs die in de Push- berichtberichten wordt gevormd steunt nu de tekenen van Marketo Engage (van toepassing op <i> Lounch App URLs </i> slechts).
   </td>
   <td><i>Binnenkort beschikbaar</i></td>
   <td><i>Binnenkort beschikbaar</i></td>
  </tr>
  </tbody>
</table>
<br/>

## Aankondigingen {#announcements}

* **de Vermindering van de Eigenschap van SEO**: Op Dinsdag, 31 Maart, 2026, zal Marketo Engage de eigenschap van de Optimalisering van de Motor van het Onderzoek (SEO) verwerpen. Als je SEO niet actief gebruikt, hoef je niets te doen. Als u onlangs SEO hebt gebruikt, kunt u uw gegevens uitvoeren. [Meer info](https://experienceleaguecommunities.adobe.com/adobe-marketo-engage-27/seo-feature-deprecation-248617){target="_blank"}.

* **REST API de grens van de Leads van de Fusie**: Beginnend 31 Maart, 2026, vraag die meer dan 25 IDs in de leadIds parameter van een Samenvoegen leidt API vraag in een 1080 foutencode zal resulteren, en de vraag zal worden overgeslagen. Banen waarvoor meer dan 25 records in één record moeten worden samengevoegd, moeten in meerdere banen worden opgesplitst om het welslagen van deze oproepen te waarborgen.

* **Rest API &quot;access_token&quot;de Verdringing van de Parameter**: De `access_token` vraagparameter die wordt gebruikt om de vraag van Marketo REST API voor authentiek te verklaren wordt afgekeurd en zal niet beschikbaar na 31 Juli, 2026 zijn. Alle nieuwe en bestaande integratie zouden vraag REST API gebruikend de kopbal van de &quot;Vergunning&quot;voor authentiek moeten verklaren, [&#x200B; zoals hier beschreven &#x200B;](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/authentication){target="_blank"}.

* **SOAP API Verdringing**: De steun voor Marketo SOAP API zal op 31 Juli, 2026 beëindigen. De diensten die SOAP API mogelijkheden gebruiken zouden aan [&#x200B; REST API &#x200B;](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/rest-api){target="_blank"} moeten worden gemigreerd.
