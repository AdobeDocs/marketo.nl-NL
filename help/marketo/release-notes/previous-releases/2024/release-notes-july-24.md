---
description: Opmerkingen bij de release - juli 2024 - Marketo Docs - Productdocumentatie
title: Opmerkingen bij de release - juli 2024
feature: Release Information
exl-id: ff63af41-2d33-40f8-abca-3fd9493e7916
source-git-commit: 8e72b24e18ae108ec74e6d4fa6b04f10130439a4
workflow-type: tm+mt
source-wordcount: '521'
ht-degree: 2%

---

# Opmerkingen bij de release: juli 2024 {#release-notes-july-24}

Hieronder vindt u alle functies die zijn inbegrepen in de release van 24 juli. Raadpleeg de Adobe Marketo Engage-editie voor informatie over de beschikbaarheid van functies.

De Nota&#39;s van de Versie specifiek voor Adobe Dynamic Chat [&#x200B; kunnen hier &#x200B;](/help/marketo/release-notes/dynamic-chat.md){target="_blank"} worden gevonden.

>[!AVAILABILITY]
>
>De eigenschappen die door een ster (![&#x200B; worden aangegeven ster &#x200B;](assets/yellow-star.png)) worden betaald toe:voegen-ons. Neem contact op met je Marketo Engage-vertegenwoordiger voor meer informatie.

## Standaardfuncties van releasecyclus {#standard-release-cycle-features}

De volgende eigenschappen vallen onder de standaardversiecyclus en zullen beginnen om op **worden vrijgegeven 26 juli, 2024**, met een gefaseerde uitrol van resterende eigenschappen in de verdere weken. De functies en datums van de release kunnen worden gewijzigd. Controleer de status naast elke functie.

<table style="table-layout:auto">
 <tbody>
  <tr>
   <th style="width:65%">Functie</th>
   <th style="width:10%">Status</th>
   <th style="width:25%">Documentatie</th>
  </tr>
     <tr>
   <td><strong> Dashboard van de Betrokkenheid voor Interactieve Webinars </strong>: Verkrijg een gezamenlijke webinar prestatiesmening evenals een uitvoerige mening van betrokkenheid voor elke aanwezige tijdens webinar zodat kunt u beslissen wat tot doel door de organisatiehulpmiddelen van Marketo Engage leidt.</td>
    <td>Vrijgegeven</td>
   <td><a href="/help/marketo/product-docs/demand-generation/events/interactive-webinars/engagement-dashboard.md" target="_blank">Betrokkenheidsdashboard</a></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  </tr>
     <tr>
   <td><strong> Beheer van de Zaal voor Interactieve Webinars </strong>: De toegang individuele die ruimten (en maakt wijzigingen indien nodig) worden gecreeerd evenals toegang tot de inhoud en de opname (en ontruim hen indien nodig om opslag te optimaliseren).</td>
    <td>Vrijgegeven</td>
   <td><a href="/help/marketo/product-docs/demand-generation/events/interactive-webinars/room-management.md" target="_blank">Ruimtebeheer</a></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  </tr>
     <tr>
   <td><strong> Aanpassing Webinar voor Interactieve Webinars </strong>: Verstrek een eenvormige organisatie-goedgekeurde branded ervaring door het gebruik van een gemeenschappelijke ruimteinterface, intermediaire schermen (zoals het scherm van de deelnemersingang achtergronden), evenals douanevideoachtergronden, zodat de webinar strategie zich gemakkelijker op merkstrategie kan richten.</td>
    <td>Vrijgegeven</td>
   <td><a href="/help/marketo/product-docs/demand-generation/events/interactive-webinars/customization.md" target="_blank">Interactieve webinars aanpassen</a></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  </tr>
     <tr>
   <td><strong> Marketo REST API Verandering </strong>: Wij introduceren een minder belangrijke verandering in het <a href="https://developers.marketo.com/rest-api/user-management/"> Beheer API van de Gebruiker </a>. Zowel doorbladeren de <a href="https://developers.marketo.com/rest-api/user-management/#browse_users"> Gebruikers </a> en <a href="https://developers.marketo.com/rest-api/user-management/#delete_user"> schrapt eindpunten van de Gebruiker </a> steunen nu <a href="/help/marketo/product-docs/target-account-management/setup-tam/target-account-management-overview.md"> de gebruikers van het Beheer van de Rekening van het Doel </a>.</td>
   <td>Vrijgegeven</td>
   <td>nvt</td>
  </tr>
 </tbody>
</table>
<br/>

## Aankondigingen {#announcements}

* **Nieuwe Plaats van de Documentatie van de Ontwikkelaar**: Als deel van onze voortdurende inspanning om de gebruikerservaring van Marketo Engage te verbeteren, zullen wij alle ontwikkelaarsdocumentatie aan de Liga van de Ervaring van Adobe en de website van Adobe Developer in juli 2024 migreren. [Meer informatie](https://nation.marketo.com/t5/employee-blogs/new-developer-documentation-website/ba-p/351055){target="_blank"}

* **Sociale Veroudering van Eigenschappen**: Op Woensdag, 31 Juli, 2024, zal Marketo Engage met de veroudering van de volgende Sociale eigenschappen binnen het product beginnen:

   * Opiniepeiling
   * Sociale knop
   * Aanbieding via verwijzing
   * Video delen
   * Sweepstake

Gebruikers kunnen deze sociale functies niet meer maken, klonen of insluiten in Marketo Engage. Bestaande sociale voorzieningen blijven werken tot 31 januari 2025. [Meer informatie](https://nation.marketo.com/t5/employee-blogs/marketo-engage-social-features-deprecation/ba-p/351977){target="_blank"}

* **Token van de Toegang in de Afschrijving van de Parameter van de Vraag**: De steun voor authentificatie die toegangstokens in een vraagparameter van een Marketo Engage REST API vraag gebruikt zal in een toekomstige versie (specifieke datumTBD) worden verwijderd. De bestaande integratie zouden aan gebruik van de kopbal van de Vergunning moeten migreren [&#x200B; die hier &#x200B;](https://developers.marketo.com/rest-api/authentication/){target="_blank"} wordt beschreven. Bij nieuwe ontwikkeling mag de machtigingheader alleen worden gebruikt voor verificatie met Marketo Engage.

* **LinkedIn vereiste re-authentificatie**: LinkedIn bevordert hun marketing APIs die door de integratie van Marketo Engage LinkedIn worden gebruikt. Deze veranderingen zullen re-authentificatie van alle diensten LinkedIn LaunchPoint in uw **Admin** > **LaunchPoint** menu tussen 26 en 15 december 2024 vereisen, om de dienstonderbreking te vermijden. U kunt instructies op vinden hoe te om dit [&#x200B; hier voor Leider Gen Forms &#x200B;](/help/marketo/product-docs/demand-generation/social/social-functions/set-up-linkedin-lead-gen-forms.md){target="_blank"} en [&#x200B; hier voor Gelijke Soorten publiek &#x200B;](/help/marketo/product-docs/demand-generation/ad-network-integrations/add-linkedin-matched-audiences-as-a-launchpoint-service.md){target="_blank"} te verwezenlijken. De lead Gen Form-service heeft het type &quot;LinkedIn Lead Gen&quot; en de Matched Audience-service heeft het type &quot;LinkedIn Matched Audiences&quot;. Voor meer informatie, bezoek de [&#x200B; Veelgestelde vragen van de Migratie &#x200B;](https://nation.marketo.com/t5/employee-blogs/linkedin-re-authentication-required/ba-p/347794){target="_blank"}.
