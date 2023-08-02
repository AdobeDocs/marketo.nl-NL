---
description: Overnemen Doc 1 - Marketo Docs - Productdocumentatie
title: Overnemen Doc 1
hide: true
hidefromtoc: true
source-git-commit: 93be928e540fd50d92bef4ead3ea23519de18cce
workflow-type: tm+mt
source-wordcount: '851'
ht-degree: 5%

---

# Overnemen Doc 1 {#inherit-doc-1}

Het controleren van een overgeërfde instantie kan als een

Hebt u een bestaande Marketo Engage-instantie van een andere beheerder overgenomen? Als dat het geval is, is dit artikel voor u bestemd.

>[!TIP]
>
>Als u een nieuwe (er) gebruiker van de Marketo Engage bent en niet vertrouwd met veel van de termijnen bent, gelieve te controleren [Marketo Verklarende woordenlijst](/help/marketo/getting-started/marketo-glossary.md){target="_blank"}.

## Gebruikers en rollen {#users-and-roles}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>Gebied</th> 
   <th>Focus controleren</th>
   <th>Kolom 3</th>
  </tr> 
  <tr> 
   <td>Gebruikers</td> 
   <td><li>Hoeveel gebruikers zijn er?</li>
<li>Zijn er gebruikers die verlopen zouden moeten zijn?</li>
<li>Heeft uw bedrijf beleid om gebruikers te schrappen?</li> 
<li>Hoeveel gebruikers hebben beheerdersmachtigingen?</li>
<li>Moet een van deze gebruikers worden gewijzigd in een andere rol?</li> 
<li>Wie zijn de API-gebruikers in deze instantie?</li></td>
   <td>3.1</td>
  </tr>
  <tr> 
   <td>Rollen</td> 
   <td><li>Hoeveel rollen zijn er?</li>  
<li>Welke toestemmingen/toegang heeft elke rol? Moet dit eventueel worden aangepast?</li>
<li>Hoeveel gebruikers zijn er per rol?</li>
<li>Hoe vaak aanmelden gebruikers?</li>
<li>Heeft elke gebruiker van API zijn eigen gebruikersrol? Als niet, overweeg het uitvoeren van dit om het oplossen van problemen gemakkelijker te maken.</li> 
<li>Zijn uw gebruikersrollen en toestemmingen op uw beleid van de bedrijfs gegevensprivacy gericht?</li></td>
   <td>3.2</td>
  </tr>
  <tr> 
   <td>Interne documentatie</td> 
   <td><li>Zijn de gebruikers en de rollen duidelijk bepaald in uw organisatie?</li>
<li>Wat is uw procedure voor het toevoegen van een nieuwe gebruiker/beheerder?</li></td>
   <td>3.3</td>
  </tr>
  <tr> 
   <td>Sandbox (indien van toepassing)</td> 
   <td><li>Hebt u een sandboxinstantie? Als dat het geval is, bekijkt u de bovenstaande categorieën voor uw sandbox.</li>
<li>Is de Invoer van het Programma verbonden met uw zandbak?</li></td>
   <td>3.4</td>
  </tr>
 </tbody> 
</table>

## Audittrail {#audit-trail}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>Gebied</th> 
   <th>Focus controleren</th>
   <th>Kolom 3</th>
  </tr> 
  <tr> 
   <td>Audittrail</td> 
   <td><li>Wie werkt in dit geval?</li></td>
   <td>3.1</td>
  </tr>
 </tbody> 
</table>

## Werkruimten en partities {#workspaces-and-partitions}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>Gebied</th> 
   <th>Focus controleren</th>
   <th>Kolom 3</th>
  </tr> 
  <tr> 
   <td>Werkruimten en partities</td> 
   <td><li>Hoeveel werkruimten en/of partities hebt u?</li>
<li>Wat is het primaire doel van elke werkruimte en verdeling?</li>
<li>Moeten ze gecontroleerd of gewijzigd worden?</li>
<li>Wat is het verband tussen uw werkruimten en verdelingen?</li>
<li>Hoeveel gebruikers hebben toegang tot elke werkruimte?</li></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>Interne documentatie</td> 
   <td><li>Hoe worden werkruimten en partities gedefinieerd?</li>
<li>Wat is uw proces om werkruimten aan uw instantie toe te voegen of gebruikers aan een werkruimte toe te voegen?</li></td>
   <td>3</td>
  </tr>
 </tbody> 
</table>

## Slimme campagnes {#smart-campaigns}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>Gebied</th> 
   <th>Focus controleren</th>
   <th>Kolom 3</th>
  </tr> 
  <tr> 
   <td>Instellingen voor slimme campagne</td> 
   <td><li>Hebt u een beperking op de grootte van slimme campagnes?</li>
<li>Als dat niet het geval is, kunt u er een toevoegen. We raden u aan om de limieten van slimme campagnes te beperken tot 25% van uw database om overcommunicatie te voorkomen of om uw gehele database in workflows te verwerken. Dit beschermt niet alleen uw merk maar helpt de prestaties van uw instantie te beschermen.</li></td>
   <td>3</td>
  </tr>
 </tbody> 
</table>

## Communicatielimieten {#communication-limits}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>Gebied</th> 
   <th>Focus controleren</th>
   <th>Kolom 3</th>
  </tr> 
  <tr> 
   <td>Communicatielimieten</td> 
   <td><li>Zijn er limieten? Heeft uw bedrijf beleid waar de communicatie grenzen noodzakelijk zouden kunnen zijn?</li>
<li>Adobe raadt u aan uw communicatie te beperken tot 1 per dag en 3 per 7 dagen, waarbij niet-operationele e-mailberichten worden geblokkeerd.</li></td>
   <td>3</td>
  </tr>
 </tbody> 
</table>

## Tags {#tags}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>Gebied</th> 
   <th>Focus controleren</th>
   <th>Kolom 3</th>
  </tr> 
  <tr> 
   <td>Tags</td> 
   <td><li>Hoeveel tags zijn er? Hoeveel tags zijn er in gebruik? Moet er iets worden toegevoegd?</li>
<li>Zijn er labels vereist binnen uw programma's?</li></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>Kanalen</td> 
   <td><li>Hoeveel kanalen zijn er? Hoeveel zijn er in gebruik?</li>
<li>Zijn alle statussen van het kanaalprogramma geschikt? Tonen zij vooruitgang binnen het programma?</li>
<li>Zijn uw kanalen verwant aan specifieke programmatypes?</li>
<li>Welke statussen worden beschouwd als een succes voor elk kanaal? Lijn die op uw marketingdoelstellingen?</li>
<li>Wordt het operationele kanaal correct gebruikt?</li>
<li>Voor Geavanceerde Report Builder (de Ontdekkingsreiziger van de Cyclus van de Opbrengst \ RCE), wordt uw gedrag van de kanaalanalyse geplaatst om zich aan uw programmapraktijken te richten die periodekosten opnemen?</li></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>Verkoopkalender (indien van toepassing)</td> 
   <td><li>Hoeveel types van kalenderingang zijn er? Zijn ze allemaal nog steeds relevant?</li></td>
   <td>3</td>
  </tr>
 </tbody> 
</table>

## Databasebeheer {#database-management}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>Gebied</th> 
   <th>Focus controleren</th>
   <th>Kolom 3</th>
  </tr> 
  <tr> 
   <td>Veldbeheer</td> 
   <td><li>Hoeveel velden zijn er? Klik op Veldnamen exporteren om een lijst met uw velden, aangepaste velden en hun API-namen weer te geven.</li>
<li>Hoeveel aangepaste velden zijn er?</li>
<li>Hoeveel velden worden gebruikt? Selecteer 'Exporteren gebruikt door' in de vervolgkeuzelijst Veldhandelingen om verwante elementen van een veld te bekijken.</li>
<li>Hoeveel worden er gesynchroniseerd tussen Marketo Engage en uw CRM?</li>
<li>Worden CRM-velden gesynchroniseerd met de desbetreffende objecten?</li>
<li>Is er een aangepaste weergave ingesteld voor de details van personen? Moet dat?</li>
<li>Hebt u een naamgevingsconventie voor uw velden op basis van de bron? Zo niet, dan kunt u overwegen dit te implementeren.</li>
<li>Zijn er velden geblokkeerd? Zorg ervoor dat je begrijpt waarom ze zijn.</li></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>Aangepaste activiteiten</td> 
   <td><li>Zijn er aangepaste activiteiten?</li>
<li>Als dat het geval is, klikt u erop om te begrijpen welke activiteiten niet gerelateerd zijn aan een Marketo-formulier, e-mail of landingspagina.</li></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>Aangepaste objecten</td> 
   <td><li>Hoeveel aangepaste objecten zijn er? Hoe worden ze gesynchroniseerd met uw CRM?</li>
<li>Hoe worden deze douanevoorwerpen gebruikt door uw programma's en lijstvragen?</li></td>
   <td>3</td>
  </tr>
 </tbody> 
</table>

## Integraties {#integrations}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>Gebied</th> 
   <th>Focus controleren</th>
   <th>Kolom 3</th>
  </tr> 
  <tr> 
   <td>CRM</td> 
   <td><li>Met welke CRM synchroniseert u? Salesforce? MS Dynamics? Veeva?</li>
<li>Is de aangepaste synchronisatie of bidirectionele synchronisatie? (KG: grammatica bevestigen en belang controleren)</li>
<li>[Alleen Salesforce] Heeft uw instantie aangepaste synchronisatiefilters geïmplementeerd? Neem contact op met Marketo Support om Aangepaste synchronisatiefilters te identificeren of om een aangepaste synchronisatieregel te vragen.</li></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>1</td> 
   <td>2</td>
   <td>3</td>
  </tr>
  <tr> 
   <td>1</td> 
   <td>2</td>
   <td>3</td>
  </tr>
  <tr> 
   <td>1</td> 
   <td>2</td>
   <td>3</td>
  </tr>
  <tr> 
   <td>Marketo Sales Insight (indien van toepassing)</td> 
   <td><li>heeft de <a href="/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md" target="_blank">MSI-pakket geïnstalleerd</a>?</li>
<li>Heb je <a href="/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/upgrading/upgrading-your-msi-package.md" target="_blank">bijgewerkt naar de nieuwste versie van Sales Insight</a>?</li>
<li>Hebt u de configuratie van het Inzicht van de Verkoop voltooid?</li>
<li>Heb je <a href="/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/add-sales-insight-permission-set.md" target="_blank">toegang krijgen tot uw gebruikers</a> op basis van het aantal licenties dat u hebt aangeschaft?</li></td>
   <td>3</td>
  </tr>
 </tbody> 
</table>

## Treasure Chest {#treasure-chest}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>Gebied</th> 
   <th>Focus controleren</th>
   <th>Kolom 3</th>
  </tr> 
  <tr> 
   <td>1</td> 
   <td>2</td>
   <td>3</td>
  </tr>
  <tr> 
   <td>1</td> 
   <td>2</td>
   <td>3</td>
  </tr>
  <tr> 
   <td>1</td> 
   <td>2</td>
   <td>3</td>
  </tr>
 </tbody> 
</table>

## Overige {#miscellaneous}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>Gebied</th> 
   <th>Focus controleren</th>
   <th>Kolom 3</th>
  </tr> 
  <tr> 
   <td>1</td> 
   <td>2</td>
   <td>3</td>
  </tr>
  <tr> 
   <td>1</td> 
   <td>2</td>
   <td>3</td>
  </tr>
  <tr> 
   <td>1</td> 
   <td>2</td>
   <td>3</td>
  </tr>
 </tbody> 
</table>
