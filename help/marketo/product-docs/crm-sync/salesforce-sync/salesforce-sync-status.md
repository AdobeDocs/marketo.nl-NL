---
description: Salesforce Sync Status - Marketo Docs - Productdocumentatie
title: Status Salesforce-synchronisatie
translation-type: tm+mt
source-git-commit: 98af67caaf485535ba2177aa661a503990e8698d
workflow-type: tm+mt
source-wordcount: '552'
ht-degree: 0%

---


# Salesforce-synchronisatiestatus {#salesforce-sync-status}

Gebruik het statusdashboard synchroniseren om synchronisatiestatussen weer te geven als onderdeel van de synchronisatiestappen en de successtatus.

De synchronisatiestappen weerspiegelen de bewerkingen van push of pull van elk objecttype voor het objectschema en de gegevens zelf. Statistische gegevens betreffen nieuwe records, updates, verwijderingen en mislukte aantallen tijdens het synchroniseren. Gebruikers kunnen filteren op datum, bewerkingstype of objecttype. Het statusdashboard voor synchronisatie toont de status van synchronisatiecycli in de afgelopen vijf dagen.

>[!NOTE]
>
>Beheerdersmachtigingen vereist

## Synchronisatiestatus {#view-sync-status} weergeven

1. Klik **Admin**.

   ![](assets/salesforce-sync-status-1.png)

1. Klik onder Integratie op Salesforce en vervolgens op het tabblad Synchronisatiestatus.

   ![](assets/salesforce-sync-status-2.png)

Standaard worden stats gesorteerd op basis van de status die het laatst is gestart. U kunt sorteren op Begonnen bij of Beëindigd bij-van meest recent aan oudst-door het soortpictogram te klikken.

![](assets/salesforce-sync-status-3.png)

## Synchronisatiestatus filter {#filter-sync-status}

1. Als u de gegevens wilt filteren, klikt u op het filterpictogram helemaal rechts van de pagina.

   ![](assets/salesforce-sync-status-4.png)

1. Selecteer uw datum- en tijdbereik en klik vervolgens op de vervolgkeuzelijst(en) om te filteren op Type object, Type bewerking en/of Statustype.

   ![](assets/salesforce-sync-status-5.png)

1. Klik **Toepassen**.

   ![](assets/salesforce-sync-status-6.png)

**Optionele stap**: Als u synchronisatiefouten wilt exporteren, klikt u op  **Exporteren**. De gegevens worden geëxporteerd als een CSV-bestand.

![](assets/salesforce-sync-status-7.png)

## Statusvelden synchroniseren {#sync-status-fields}

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Veld</th> 
   <th>Beschrijving</th> 
   <th>Enumwaarden</th> 
  </tr> 
  <tr> 
   <td colspan="1">Gestart om</td> 
   <td colspan="1">De begindatum/tijd van de synchronisatiecyclus (tijdzone van de gebruiker)</td> 
   <td colspan="1"></td> 
  </tr>  
  <tr> 
   <td colspan="1">Beëindigd bij</td> 
   <td colspan="1">De einddatum/tijd van de synchronisatiecyclus (tijdzone van de gebruiker)</td> 
   <td colspan="1"></td> 
  </tr> 
  <tr> 
   <td colspan="1">Object</td> 
   <td colspan="1">Objecttype</td> 
   <td colspan="1">Contact, Persoon, Taak, Opportunity, Lead, Overige zoals hieronder</td> 
  </tr>  
  <tr> 
   <td colspan="1">Bewerking</td> 
   <td colspan="1">Type bewerking</td> 
   <td colspan="1">Bewerkingstypen zoals hieronder</td> 
  </tr>  
  <tr> 
   <td colspan="1">Status</td> 
   <td colspan="1">Status van de partij</td> 
   <td colspan="1">Voltooid, Mislukt, Niet voltooid, In proces, Opgeschoond*</td> 
  </tr>
  <tr> 
   <td colspan="1">Nieuw</td> 
   <td colspan="1">Aantal nieuwe records</td> 
   <td colspan="1"></td> 
  </tr>  
  <tr> 
   <td colspan="1">Bijgewerkt</td> 
   <td colspan="1">Aantal bijgewerkte records</td> 
   <td colspan="1"></td> 
  </tr>  
  <tr> 
   <td colspan="1">Verwijderd</td> 
   <td colspan="1">Aantal verwijderde records</td> 
   <td colspan="1"></td> 
  </tr> 
  <tr> 
   <td colspan="1">Mislukt item</td> 
   <td colspan="1">Aantal records waarvan synchronisatie is mislukt</td> 
   <td colspan="1"><br></td> 
  </tr>  
  <tr> 
   <td colspan="1">Overgeslagen</td> 
   <td colspan="1">Aantal records overgeslagen omdat er geen wijzigingen zijn aangebracht in de relevante velden voor de synchronisatie</td> 
   <td colspan="1"></td> 
  </tr>  
 </tbody> 
</table>

*Gegevens werden teruggezet naar vorige status van integriteit na fout met synchronisatiestap.

## Objecttype {#object-type}

<table> 
 <colgroup> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td colspan="1">Account</td> 
  </tr>  
  <tr> 
   <td colspan="1">Accounttype</td> 
  </tr> 
  <tr> 
   <td colspan="1">Aangepaste objecten</td> 
  </tr>  
  <tr> 
   <td colspan="1">Campagne</td> 
  </tr>  
  <tr> 
   <td colspan="1">Campagne-lidstatus</td> 
  </tr>
  <tr> 
   <td colspan="1">Contact</td> 
  </tr>  
  <tr> 
   <td colspan="1">E-mailsjabloon</td> 
  </tr>  
  <tr> 
   <td colspan="1">Gebeurtenis</td> 
  </tr> 
  <tr> 
   <td colspan="1">Persoon (lead)</td> 
  </tr>  
  <tr> 
   <td colspan="1">Opportunity</td> 
  </tr>  
  <tr> 
   <td colspan="1">Functie contactpersoon opportunity</td> 
  </tr>  
  <tr> 
   <td colspan="1">Taak</td> 
  </tr>  
  <tr> 
   <td colspan="1">Gebruiker</td> 
  </tr>  
 </tbody> 
</table>

## Type bewerking {#operation-type}

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col>
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Type bewerking</th> 
   <th>Gevonden tegen deze objecten</th> 
   <th>Opmerkingen</th> 
   <th>Type bewerking</th>
  </tr> 
  <tr> 
   <td colspan="1">Init link to Program</td> 
   <td colspan="1">Campagne</td> 
   <td colspan="1">Campagnes koppelen aan programma's</td> 
   <td colspan="1">Bijwerken</td>
  </tr>  
  <tr> 
   <td colspan="1">Pull-omzettingen</td> 
   <td colspan="1">Persoon (lead)*</td> 
   <td colspan="1">Zet SFDC-handelingen om in Marketo. Eenheden (getallen) zijn leads die worden geconverteerd naar contactpersonen</td> 
   <td colspan="1">Bijwerken, Mislukt item of Overgeslagen</td>
  </tr> 
  <tr> 
   <td colspan="1">Verwijderen verwijderen</td> 
   <td colspan="1">Contact, Persoon (lead), Opportunity, Campagne, Campagne leden, opportunity Contact, Custom Objects, Campaigns, Campagne Member Status, Opportunity Contact Role</td> 
   <td colspan="1">Verwijderde records van SFDC die worden gesynchroniseerd met Marketo</td> 
   <td colspan="1">Verwijderd, mislukt item of overgeslagen</td>
  </tr>  
  <tr> 
   <td colspan="1">Updates uitvouwen</td> 
   <td colspan="1">Taak, Persoon (lead), Person (lead) Wachtrij, Contact, Gebeurtenis, Opportunity, Account, Accounttype, Campagne-leden, Aangepaste objecten, Campagnes, Campagne-lidstatus, Gebeurtenissen, Personstatus, Opportunity, Opportunity Contactrol</td> 
   <td colspan="1">Updates of nieuwe records in SFDC gesynchroniseerd met Marketo, Pull Events as Activity</td> 
   <td colspan="1">Nieuw, Bijgewerkt, Mislukt item of Overgeslagen</td>
  </tr>  
  <tr> 
   <td colspan="1">Nieuw</td> 
   <td colspan="1">Taken, e-mailsjablonen</td> 
   <td colspan="1">Pushtaken (activiteiten)</td> 
   <td colspan="1"></td>
  </tr>
  <tr> 
   <td colspan="1">Push-updates</td> 
   <td colspan="1">Taken, E-mailsjablonen, Person, Contact, Campagnes</td> 
   <td colspan="1">Updates naar SFDC en ook verwijderen</td> 
   <td colspan="1">Bijwerken, Mislukt item of Overgeslagen</td>
  </tr>  
  <tr> 
   <td colspan="1">Schema synchroniseren</td> 
   <td colspan="1">Campagneleden, aangepaste objecten, campagnes, status van campagnelid, taken, persoon, opportuniteit, rol van contactpersoon voor opportunity, gebruikers</td> 
   <td colspan="1">Hiermee synchroniseert u metagegevens voor verschillende objecten om te bepalen welke nieuwe velden in de volgende cyclus moeten worden gesynchroniseerd</td> 
   <td colspan="1"></td>
  </tr>  
  <tr> 
   <td colspan="1">Synchroniseren met programma</td> 
   <td colspan="1">Campagnes</td> 
   <td colspan="1">Syncs Marketo-programma met SFDC-campagnes</td> 
   <td colspan="1">Nieuw, Updates, Mislukt of Overgeslagen</td>
  </tr> 
  <tr> 
   <td colspan="1">Activiteiten bijwerken</td> 
   <td colspan="1">Taken</td> 
   <td colspan="1">Pull Activiteiten van Salesforce</td> 
   <td colspan="1"></td>
  </tr>  
  <tr> 
   <td colspan="1">FKS bijwerken</td> 
   <td colspan="1">Alles</td> 
   <td colspan="1">Externe sleutel van alle objecten bijwerken</td> 
   <td colspan="1">N.v.t.</td>
  </tr>  
 </tbody> 
</table>

*Branding configuratie op het abonnementsniveau beslist het etiket - &quot;Lood&quot;of &quot;Persoon&quot;in het rapport.
