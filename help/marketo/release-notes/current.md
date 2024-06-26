---
description: Actuele aanvullende informatie - Marketo Docs - Productdocumentatie
title: Opmerkingen bij de huidige release
exl-id: a2eccad5-73ad-48f9-8091-51cee23824e1
feature: Release Information
source-git-commit: ea9bf2a002415936cdfb5bfb723ce80723003da5
workflow-type: tm+mt
source-wordcount: '341'
ht-degree: 2%

---

# Opmerkingen bij de release: juli 2024 {#release-notes-july-24}

Hieronder vindt u alle functies die zijn opgenomen in de release van 24 juni. Raadpleeg de Adobe Marketo Engage-editie voor informatie over de beschikbaarheid van functies.

De opmerkingen bij de release specifiek voor Adobe Dynamic Chat [hier te vinden](/help/marketo/release-notes/dynamic-chat.md){target="_blank"}.

>[!AVAILABILITY]
>
>Kenmerken die door een ster worden aangeduid (![ster](assets/yellow-star.png)) worden betaald als extra&#39;s. Neem contact op met uw Marketo Engage voor meer informatie.

## Standaardfuncties van releasecyclus {#standard-release-cycle-features}

De volgende functies vallen onder de standaardreleasecyclus en worden vrijgegeven op **26 juli 2024**, met een gefaseerde uitrol van de resterende functies in de daaropvolgende weken. De functies en datums van de release kunnen worden gewijzigd. Controleer de status naast elke functie.

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:65%">Functie</th> 
   <th style="width:10%">Status</th>
   <th style="width:25%">Documentatie</th>
  </tr>
     <tr> 
   <td><strong>Wijziging Marketo REST API</strong>: We brengen een kleine wijziging aan in de <a href="https://developers.marketo.com/rest-api/user-management/">Gebruikersbeheer-API</a>. Beide <a href="https://developers.marketo.com/rest-api/user-management/#browse_users">Gebruikers doorbladeren</a> en <a href="https://developers.marketo.com/rest-api/user-management/#delete_user">Gebruiker verwijderen</a> eindpunten nu ondersteuning <a href="/help/marketo/product-docs/target-account-management/setup-tam/target-account-management-overview.md">Doelaccountbeheer</a> gebruikers.</td> 
   <td><i>binnenkort beschikbaar</i></td>
   <td><i>binnenkort beschikbaar</i></td>
  </tr>
 </tbody> 
</table>
<br/>

## Aankondigingen {#announcements}

* **Nieuwe documentatiesite voor ontwikkelaars**: Als onderdeel van onze verdere inspanningen om de gebruikerservaring in de Marketo Engage te verbeteren, zullen we in juli 2024 alle documentatie voor ontwikkelaars migreren naar de Adobe Experience League en de website van Adobe Developer. [Meer informatie](https://nation.marketo.com/t5/employee-blogs/new-developer-documentation-website/ba-p/351055){target="_blank"}

* **Toegangstoken in de Veroudering van de Parameter van de Vraag**: Ondersteuning voor verificatie met behulp van toegangstokens in een queryparameter van een REST API-aanroep van een Marketo Engage wordt in een toekomstige versie verwijderd (specifieke datum-TBD). Bestaande integraties moeten worden gemigreerd naar gebruik van de machtigingheader [hier beschreven](https://developers.marketo.com/rest-api/authentication/){target="_blank"}. De nieuwe ontwikkeling zou de kopbal van de Vergunning voor authentificatie met Marketo Engage slechts moeten gebruiken.

* **Opnieuw verifiëren van linkedIn vereist**: LinkedIn werkt aan de upgrade van hun marketing-API&#39;s die worden gebruikt door de integratie van Marketo Engage LinkedIn. Deze wijzigingen vereisen opnieuw verificatie van alle LinkedIn LaunchPoint-services in uw **Beheerder** > **LaunchPoint** tussen 26 juli en 15 december 2024 om onderbreking van de service te voorkomen. U kunt instructies vinden over hoe te om dit te verwezenlijken [Hier voor generaal-leider Forms](/help/marketo/product-docs/demand-generation/social/social-functions/set-up-linkedin-lead-gen-forms.md){target="_blank"} en [hier voor passend publiek](/help/marketo/product-docs/demand-generation/ad-network-integrations/add-linkedin-matched-audiences-as-a-launchpoint-service.md){target="_blank"}. De lead Gen Form-service heeft het type &quot;LinkedIn Lead Gen&quot; en de Matched Audience-service heeft het type &quot;LinkedIn Matched Audiences&quot;. Zie voor meer informatie de [Veelgestelde vragen over migratie](https://nation.marketo.com/t5/employee-blogs/linkedin-re-authentication-required/ba-p/347794){target="_blank"}.
