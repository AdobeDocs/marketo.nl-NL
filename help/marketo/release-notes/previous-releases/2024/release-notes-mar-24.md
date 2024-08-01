---
description: Opmerkingen bij de release - maart 2024 - Marketo Docs - Productdocumentatie
title: Opmerkingen bij de release - maart 2024
feature: Release Information
exl-id: d8bc7f88-a77b-4b49-aed5-aceab9e639f0
source-git-commit: 1839ccb646e775b67efa8de7d2d2bf3dbbbefa72
workflow-type: tm+mt
source-wordcount: '350'
ht-degree: 0%

---

# Opmerkingen bij de release: maart 2024 {#release-notes-mar-24}

Hieronder vindt u alle functies die zijn opgenomen in de release van 24 maart. Raadpleeg de Adobe Marketo Engage-editie voor informatie over de beschikbaarheid van functies.

>[!AVAILABILITY]
>
>De eigenschappen die door een ster (![ worden aangegeven ster ](assets/yellow-star.png)) worden betaald toe:voegen-ons. Neem contact op met uw Marketo Engage voor meer informatie.

## Standaardfuncties van releasecyclus {#standard-release-cycle-features}

De volgende eigenschappen vallen onder de standaardversiecyclus en zullen beginnen om op **Maart 8, 2024**, met een gefaseerde uitrol van resterende eigenschappen in de verdere weken worden vrijgegeven. De functies en datums van de release kunnen worden gewijzigd. Controleer de status naast elke functie.

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:65%">Functie</th> 
   <th style="width:10%">Status</th>
   <th style="width:25%">Documentatie</th>
  </tr>
  <tr> 
   <td><strong> Geavanceerde Conversational Flow Logica </strong>: Voeg extra gebieden voor evaluatie in één enkele keus voor de Conversationele follow-up van de Stroom toe.</td> 
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
   <td><strong> opnieuw rangschikt Conversational Flow Logica </strong>: In Marketo Engage Forms, kunt u de Conversationele keuzen van de Stroom nu opnieuw in orde brengen, in plaats van het moeten schrappen en toevoegen terug.</td> 
   <td>Verzonden</td>
   <td><a href="/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/conversational-flow-settings-for-marketo-engage-forms.md" target="_blank">Conversation Flow Settings for Marketo Engage Forms</a></td>
   </tr>
  <tr> 
   <td> </td> 
   <td> </td>
   <td> </td>
  </tr>
    <tr> 
   <td><strong> Metagegevens van de Activiteit API </strong>: 
   Metagegevens zoals gebruikersagent, platform en apparaat worden nu opgenomen in web- en e-mailactiviteiten en helpen consistente inzichten in deze activiteiten te verkrijgen via de Marketo REST API.</td> 
   <td>Verzonden</td>
   <td>nvt</td>
  </tr>
 </tbody> 
</table>
<br/>

## Aankondigingen {#announcements}

* **krijgt het Repareren van het Lid API van het Programma**: Een verandering werd onlangs aangebracht om het gedrag van [ te verbeteren krijgt de Leden van het Programma ](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Program-Members/operation/getProgramMembersUsingGET) {target="_blank"} eindpunt. Eerder, toen het gebruiken van het `updatedAt` filtertype om een datumwaaier te specificeren, was er een kans dat de verslagen van het programmalidmaatschap die binnen dat waaier werden bijgewerkt niet inbegrepen in de reactie waren. Bovendien was er een kans dat de verslagen van het programmalidmaatschap die buiten de gespecificeerde datumwaaier worden bijgewerkt die verkeerd in de reactie worden omvat. Beide kwesties zijn opgelost.

* **Browser van het Inzicht van de Rekening Browser van het Inzicht van de Rekening Verdringing**: de Adobe verwijdert de browser van het Inzicht browser van het Inzicht van de Rekening van het Beheer van het Doel {](/help/marketo/product-docs/target-account-management/setup-tam/account-insight-plug-in-overview.md){target="_blank"} van de Opslag van het Web van Chrome op 8 april 2024. [ Bestaande gebruikers: u kunt de plug-in blijven gebruiken totdat u de Marketo Engage-instantie migreert naar Adobe Identity en Admin Console. Deze verandering **zal** geen andere eigenschappen/gegevens van TAM binnen Marketo Engage of de e-mailstop-ins van Chrome en van Vooruitzichten beïnvloeden die met het Inzicht van de Verkoop werken. [ leer meer ](https://nation.marketo.com/t5/product-blogs/marketo-engage-account-insights-browser-plug-in-end-of-life/ba-p/344834) {target="_blank"}.
