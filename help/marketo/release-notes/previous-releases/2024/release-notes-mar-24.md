---
description: Opmerkingen bij de release - maart 2024 - Marketo Docs - Productdocumentatie
title: Opmerkingen bij de release - maart 2024
feature: Release Information
source-git-commit: c7359cc95a3e90f228353dc3d21c92712f9d5684
workflow-type: tm+mt
source-wordcount: '297'
ht-degree: 0%

---

# Opmerkingen bij de release: maart 2024 {#release-notes-mar-24}

Hieronder vindt u alle functies die zijn opgenomen in de release van 24 maart. Raadpleeg de Adobe Marketo Engage-editie voor informatie over de beschikbaarheid van functies.

>[!AVAILABILITY]
>
>Kenmerken die door een ster worden aangeduid (![ster](assets/yellow-star.png)) worden betaald als extra&#39;s. Neem contact op met uw Marketo Engage voor meer informatie.

## Standaardfuncties van releasecyclus {#standard-release-cycle-features}

De volgende functies vallen onder de standaardreleasecyclus en worden vrijgegeven op **8 maart 2024**, met een gefaseerde uitrol van de resterende functies in de daaropvolgende weken. De functies en datums van de release kunnen worden gewijzigd. Controleer de status naast elke functie.

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:65%">Functie</th> 
   <th style="width:10%">Status</th>
   <th style="width:25%">Documentatie</th>
  </tr>
  <tr> 
   <td><strong>Advanced Conversated Flow Logic</strong>: Voeg aanvullende velden voor evaluatie toe in één keuze voor de opvolging van de controversiële stroom.</td> 
   <td>Verzonden</td>
   <td><a href="/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/conversational-flow-settings-for-marketo-engage-forms.md" target="_blank">Conversation Flow Settings for Marketo Engage Forms</a></td>
  </tr>
   <tr> 
   <td> </td> 
   <td> </td>
   <td> </td>
  </tr>
   </tr>
    <tr> 
   <td><strong>Conversie Flow Logic opnieuw ordenen</strong>: In Marketo Engage Forms kunt u nu de Conversational Flow-keuzes opnieuw ordenen in plaats van deze te verwijderen en weer toe te voegen.</td> 
   <td>Verzonden</td>
   <td><a href="/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/conversational-flow-settings-for-marketo-engage-forms.md" target="_blank">Conversation Flow Settings for Marketo Engage Forms</a></td>
   </tr>
  <tr> 
   <td> </td> 
   <td> </td>
   <td> </td>
  </tr>
    <tr> 
   <td><strong>Metagegevens API-activiteit</strong>: Metagegevens zoals Gebruikersagent, Platform en Apparaat zijn nu opgenomen in web- en e-mailactiviteiten en zorgen voor consistente inzichten in deze activiteiten via de Marketo REST API.</td> 
   <td><i>Binnenkort beschikbaar</i></td>
   <td><i>Binnenkort beschikbaar</i></td>
  </tr>
 </tbody> 
</table>
<br/>

## Aankondigingen {#announcements}

* **API-correctie voor programmalid ophalen**: Onlangs is een wijziging aangebracht om het gedrag van de [Programmaleden ophalen](https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Program_members/getProgramMemberUsingGET){target="_blank"} eindpunt. Eerder, bij het gebruiken van `updatedAt` filtertype om een datumwaaier te specificeren, was er een kans dat de verslagen van het programmalidmaatschap binnen die waaier werden bijgewerkt niet inbegrepen in de reactie waren. Bovendien was er een kans dat de verslagen van het programmalidmaatschap die buiten de gespecificeerde datumwaaier worden bijgewerkt die verkeerd in de reactie worden omvat. Beide kwesties zijn opgelost.

* **Insteekmodule-inversie accountgegevens browser**: Adobe verwijdert het beheer van doelaccounts [Insteekmodule voor de browser Account Insight](/help/marketo/product-docs/target-account-management/setup-tam/account-insight-plug-in-overview.md){target="_blank"} from the Chrome Web Store on March 18, 2024. Existing users: you can continue to use the plug-in until you migrate your Marketo Engage instance to Adobe Identity and Admin Console. This change **will not impact** any other TAM features/data within Marketo Engage or the Chrome and Outlook email plug-ins that work with Sales Insight. [Learn more](https://nation.marketo.com/t5/product-blogs/marketo-engage-account-insights-browser-plug-in-end-of-life/ba-p/344834){target="_blank"}.
