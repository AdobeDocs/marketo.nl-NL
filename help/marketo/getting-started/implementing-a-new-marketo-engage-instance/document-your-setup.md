---
description: Documenteer de opstelling van uw nieuwe instantie van het Marketo Engage.
title: Aanbevolen werkwijzen voor nieuwe instanties - Uw instellingen documenteren
feature: Getting Started
exl-id: c64d25e8-564b-487d-824e-7fcbfbf5d8bb
source-git-commit: 14583b7fa148aa2b03c8cf6316b9a106c11717b7
workflow-type: tm+mt
source-wordcount: '454'
ht-degree: 0%

---

# Aanbevolen werkwijzen voor nieuwe instanties: uw instellingen documenteren {#new-instance-best-practices-document-your-setup}

Nu u de belangrijkste productgebieden aan opstelling voor een nieuwe instantie van het Marketo Engage hebt geleerd, is de volgende stap documentatie voor uw instantieconfiguratie en technologiestapel te creëren. Of het creëren van het via spreadsheet of een toepassing van het projectbeheer, uw documentatie zal een groot middel zijn om vooruitgang te volgen en details te registreren, evenals uw instantie gestructureerd en houdbaar voor toekomstige marketers binnen uw organisatie te houden.

## Data {#data}

<table>
<thead>
  <tr>
    <th style="width:20%">Gebied</th>
    <th style="width:80%">Actiepunten</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Lijstimport</td>
    <td><li>Een lijst met gegevensbronnen verzamelen waarvan de records worden opgehaald van naar <a href="https://experienceleague.adobe.com/en/docs/marketo/using/getting-started/quick-wins/import-a-list-of-people" target="_blank">invoer in Marketo Engage</a>.</li>
    <li>Als u vanuit meerdere gegevensbronnen importeert, kunt u overwegen Hoofdlijsten te gebruiken of <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/field-management/create-a-custom-field-in-marketo" target="_blank">een aangepast veld maken</a> in het persoonsdossier om de gegevensbron te wijzen.</li></td>
  </tr>
  <tr>
    <td>Database-integratie</td>
    <td><li>Als u gebruikmaakt van de native synchronisatie tussen Marketo Engage en uw CRM, moet u zorgvuldig overwegen welke velden u wilt synchroniseren tussen systemen. Niet elk gebied moet worden gesynchroniseerd, dus ben strategisch over uw gegevensstromen.</li></td>
  </tr>
</tbody>
</table>

## Documentatie {#documentation}

<table>
<thead>
  <tr>
    <th style="width:20%">Gebied</th>
    <th style="width:80%">Actiepunten</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Gebruikers</td>
    <td><li>Documenteer de <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/add-or-remove-a-user#add-a-user" target="_blank">huidige gebruikers</a> om veiligheidsredenen. De volgende details moeten minimaal worden opgenomen (en zijn allemaal zichtbaar door naar Beheer &gt; Gebruikers &amp; rollen te gaan):</li>
    <ul>
    <li>Naam</li>
    <li>E-mail</li>
    <li>Aanmelden</li>
    <li>Functie</li>
    <li>Toegangsvervaldatum</li>
    <li>Door gebruiker aangemaakt op</li>
    <li>Meest recente aanmeldingsdatum</li></ul>
    <p><img src="assets/note-icon.png" alt="notitiepictogram"> NOTA: U kunt op dit ook uitbreiden om documentatie rond rollen/toestemmingen te omvatten.
    <p>
    <li>Als Admin van het Product van het Marketo Engage, ontwikkelt een intern proces om de gebruikerslijst van het Marketo Engage bij een regelmatige kring te controleren en bij te werken. Als u wijzigingen wilt aanbrengen in de lijst met gebruikers in Adobe Admin Console, kunt u <a href="https://helpx.adobe.com/enterprise/using/users.html" target="_blank">bulkacties</a>, zoals het uploaden van een .CSV-bestand met de REST-API voor gebruikersbeheer, enz.</li></td>
  </tr>
  <tr>
    <td>Organisatie</td>
    <td><li>Documenteer de overeengekomen omslagstructuur, standaard noemende overeenkomsten voor programma's, activa, etc., en de waarom de besluiten werden genomen. <a href="https://experienceleague.adobe.com/en/docs/marketo-learn/tutorials/fundamentals/best-practices-to-organize-a-new-instance" target="_blank">Klik hier voor meer informatie over de beste praktijken.</a></li></td>
  </tr>
  <tr>
    <td>Changelog</td>
    <td><li>Creeer een verandering waar u kunt documenteren wat in uw instantie en de waarom van de wijzigingen verandert. <a href="https://experienceleague.adobe.com/en/docs/marketo-learn/auditing-an-inherited-instance/develop-an-instance-governance-guide" target="_blank">Klik hier voor meer informatie over de beste praktijken.</a></li></td>
  </tr>
  <tr>
    <td>Afspeelboeken</td>
    <td><li>Maak een afspeelboek van de gebruiker of een beheerboek voor interne gebruikers die aan de instantie deelnemen.</li></td>
  </tr>
  <tr>
    <td>Gesprek met interne teams</td>
    <td><li>De verwachtingen van het interne marketingteam ten aanzien van Marketo Engage afstemmen op de mogelijkheden van het Marketo Engage.</li>
    <li>Identificeer de teams die uw belanghebbenden in de instantie van het Marketo Engage zullen zijn en documenteer hun doelstellingen om het gebruiken van Marketo Engage als technologie te bereiken.</li></td>
  </tr>
  <tr>
    <td>Werkruimten en partities (indien van toepassing)</td>
    <td><li>Documenteer hoe de werkruimten worden bepaald, en hoe dat op gegevensbestandverdelingen betrekking heeft (b.v., een Globale werkruimte die iedereen tegenover bedrijfssectoren toont).</li>
    <li>Importeer nieuwe records naar de juiste partitie.</li>
    <li>Bepaal de waarde in uw CRM die gebruikers in de aangewezen verdeling plaatst.</li></td>
  </tr>
</tbody>
</table>
