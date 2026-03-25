---
description: Opmerkingen bij de release - februari 2026 - Marketo Docs - Productdocumentatie
title: Opmerkingen bij de release - februari 2026
feature: Release Information
exl-id: 679d2fca-99ba-4321-ad0d-a297b7f193fc
source-git-commit: 70939d387dcfe6064e179e4e7e91b16c6baa7b8b
workflow-type: tm+mt
source-wordcount: '372'
ht-degree: 1%

---

# Opmerkingen bij de release: februari 2026 {#release-notes-feb-26}

Hieronder vindt u alle functies die zijn inbegrepen in de release van 26 februari. Raadpleeg de Adobe Marketo Engage-editie voor informatie over de beschikbaarheid van functies.

De Nota&#39;s van de Versie specifiek voor Adobe Dynamic Chat [&#x200B; kunnen hier &#x200B;](/help/marketo/release-notes/dynamic-chat.md){target="_blank"} worden gevonden.

## Standaardfuncties van releasecyclus {#standard-release-cycle-features}

De volgende eigenschappen vallen onder de standaardversiecyclus en zullen beginnen om op **worden vrijgegeven 20 februari, 2026**, met een gefaseerde implementatie van resterende eigenschappen in de verdere weken. De functies en datums van de release kunnen worden gewijzigd. Controleer de status naast elke functie.

<table style="table-layout:auto">
 <tbody>
 <tr>
   <th style="width:65%">Functie</th>
   <th style="width:10%">Status</th>
   <th style="width:25%">Documentatie</th>
  </tr>
  <tr>
   <td><strong> E-mail Designer - de Acties van de Omslag </strong>: Pariteit met de oude e-mailredacteur.
   <ul>
   <li>Maphandelingen delen en archiveren voor e-mailmiddelen van Designer.</li>
   <li>Mappen delen over werkruimten, met de rechtermuisknop op een map klikken om een nieuw element te maken, elementen verplaatsen via slepen en neerzetten.</li>
   </ul>
   </td>
   <td>Vrijgegeven</td>
   <td>nvt</td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong> E-mail Designer - API </strong>: U kunt nu API vraag voor E-mail Designer gebruiken.</td>
   <td>Vrijgegeven</td>
   <td><a href="https://developer.adobe.com/marketo-apis/api/asset#">Marketo Asset API</a></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong> E-mail Designer - AI HulpGeneratie van het Beeld </strong>: Nu, naast Firefly, kunt u modellen van de Banaan van de Nano gebruiken om beelden met de Medewerker van AI voor e-mailinhoud te produceren.</td>
   <td>Vrijgegeven</td>
   <td><a href="https://experienceleague.adobe.com/nl/docs/marketo/using/product-docs/email-marketing/email-designer/ai-assistant#create-content-for-a-specific-section">Inhoud maken voor een specifieke sectie van uw e-mail</a></td>
  </tr>
  </tbody>
</table>
<br/>

## Aankondigingen {#announcements}

* **de Vermindering van de Eigenschap van SEO**: Op Dinsdag, 31 Maart, 2026, zal Marketo Engage de eigenschap van de Optimalisering van de Motor van het Onderzoek (SEO) verwerpen. Als je SEO niet actief gebruikt, hoef je niets te doen. Als u onlangs SEO hebt gebruikt, kunt u uw gegevens uitvoeren. [Meer info](https://experienceleaguecommunities.adobe.com/adobe-marketo-engage-27/seo-feature-deprecation-248617?profile.language=nl){target="_blank"}.

* **REST API de grens van de Leads van de Fusie**: Beginnend 31 Maart, 2026, vraag die meer dan 25 IDs in de leadIds parameter van een Samenvoegen leidt API vraag in een 1080 foutencode zal resulteren, en de vraag zal worden overgeslagen. Banen waarvoor meer dan 25 records in één record moeten worden samengevoegd, moeten in meerdere banen worden opgesplitst om het welslagen van deze oproepen te waarborgen.

* **Rest API &quot;access_token&quot;de Verdringing van de Parameter**: De `access_token` vraagparameter die wordt gebruikt om de vraag van Marketo REST API voor authentiek te verklaren wordt afgekeurd en zal niet beschikbaar na 31 Juli, 2026 zijn. Alle nieuwe en bestaande integratie zouden vraag REST API gebruikend de kopbal van de &quot;Vergunning&quot;voor authentiek moeten verklaren, [&#x200B; zoals hier beschreven &#x200B;](https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/rest/authentication){target="_blank"}.

* **SOAP API Verdringing**: De steun voor Marketo SOAP API zal op 31 Juli, 2026 beëindigen. De diensten die SOAP API mogelijkheden gebruiken zouden aan [&#x200B; REST API &#x200B;](https://experienceleague.adobe.com/nl/docs/marketo-developer/marketo/rest/rest-api){target="_blank"} moeten worden gemigreerd.
