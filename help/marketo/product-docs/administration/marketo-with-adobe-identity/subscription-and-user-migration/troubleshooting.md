---
description: Adobe IMS-handleiding voor probleemoplossing - Marketo Docs - Productdocumentatie
title: Adobe IMS-gids voor probleemoplossing
hide: true
hidefromtoc: true
feature: Marketo with Adobe Identity
source-git-commit: eccebb8352c56770dea5af9395c8bc83a08525dd
workflow-type: tm+mt
source-wordcount: '543'
ht-degree: 0%

---

# Adobe IMS-gids voor probleemoplossing {#adobe-ims-troubleshooting-guide}

Tijdens het IMS-gebruikersmigratieproces wordt een Adobe-gebruiker gemaakt voor elke Marketo Engage-gebruiker die wordt gemigreerd. Soms, wordt het niet gecreeerd (om diverse redenen, met betrekking tot het verslag van de gebruiker in de Actieve Folder of kwesties met het e-mailadres). Als dit gebeurt, ziet de Marketo Engage-beheerder de redenen in het migratiestatus van de gebruiker op de zelfmigratieconsole. Hieronder ziet u hoe u verschillende problemen met het maken van Adobe-gebruikers kunt oplossen.

## Foutberichten {#error-messages}

* <a href="#not-in-directory"> niet in Folder </a>
* <a href="#gmail-invalid-character"> Ongeldig Teken van Gmail </a>
* <a href="#inactive-user"> Inactieve Gebruiker </a>
* <a href="#not-in-domain"> niet in Domein </a>
* <a href="#create-failure"> creeer Mislukking </a>
* <a href="#type2e-user-failure"> Type2e de Mislukking van de Gebruiker </a>



<table>
<thead>
  <tr>
    <th style="width:20%">Foutbericht</th>
    <th style="width:40%">Hoofdoorzaak</th>
    <th style="width:40%">Resoluties</th>
  </tr>
  </thead>
<tbody>
  <tr>
    <td><i><a id="not-in-directory">Niet in directory</a></i></td>
    <td>De gebruiker bestaat niet in Actieve Folder (AD). Voor organisaties met SSO's waarvoor ADD-synchronisatie is ingeschakeld, kan de gebruiker alleen worden gemaakt via Identiteitsprovider (IdP). Daarom kon de gebruiker niet via Admin Console worden toegevoegd tijdens de gebruikersmigratie.</td>
    <td>Migrate - de gebruiker moet aan de Actieve Folder met juiste toestemmingen worden toegevoegd. Marketo-beheerder kan de gebruikersmigratie voor deze gebruiker opnieuw uitvoeren vanuit de migratieconsole. 
    <br> niet migreer - Marketo admin om de gebruiker in de Console van de Migratie over te slaan. De knop "Migratie voltooid" wordt weergegeven wanneer alle gebruikers voor de migratie of het overslaan verantwoordelijk zijn. Klik op de koppeling om het gebruikersmigratieproces te voltooien.</td>
  </tr>
  <tr>
    <td><i><a id="gmail-invalid-character">Ongeldig Gmail-teken</a></i></td>
    <td>Per Adobe-beveiligingsbeleid '.' en het plusteken (+) zijn niet toegestaan in een e-mailadres van alleen het Gmail-domein  
    <br> beide speciale karakters worden toegestaan in een niet-Gmail domein e-mailadres. </td>
    <td>Migreren - Het e-mailadres moet in Marketo Engage worden bijgewerkt om te voldoen aan het beveiligingsbeleid van Adobe. Marketo-beheerder om de gebruikersmigratie voor deze gebruiker vanuit de migratieconsole opnieuw uit te voeren.<br> niet migreer - Marketo admin om de gebruiker in de Console van de Migratie over te slaan. De knop "Migratie voltooid" wordt weergegeven wanneer alle gebruikers voor de migratie of het overslaan verantwoordelijk zijn. Klik op de koppeling om het gebruikersmigratieproces te voltooien.</td>
  </tr>
  <tr>
    <td><i><a id="inactive-user">Inactieve gebruiker</a></i></td>
    <td>AD Sync is ingeschakeld en het gefedereerde account van de gebruiker bestaat maar in de status inactief/uitgeschakeld.</td>
    <td>Migreren - De status van de gebruiker en de juiste machtigingen moeten worden hersteld. Marketo-beheerder kan de gebruikersmigratie voor deze gebruiker opnieuw uitvoeren vanuit de migratieconsole.
    <br> niet migreer - Marketo admin om de gebruiker in de Console van de Migratie over te slaan. De knop "Migratie voltooid" wordt weergegeven wanneer alle gebruikers voor de migratie of het overslaan verantwoordelijk zijn. Klik op de koppeling om het gebruikersmigratieproces te voltooien.</td>
  </tr>
  <tr>
    <td><i><a id="not-in-domain">Niet in domein</a></i></td>
    <td>Domeinhandhaving is ingeschakeld in Admin Console, maar het domein van het e-mailadres voor de gebruiker is geen van de toegestane domeinen. 
    <br> het handhavingsbeleid van het Domein wordt geplaatst op het folderniveau.</td>
    <td>Migreren - Het e-mailadres moet in Marketo Engage worden bijgewerkt om te voldoen aan het beleid voor domeinhandhaving, anders kan de systeembeheerder <a href="https://helpx.adobe.com/enterprise/using/manage-domains-directories.html#move-domains-across-directories"> 
    verplaats het domein naar een andere gehandicapte folder van de Handhaving van het Domein (DE) </a> of <a href="https://helpx.adobe.com/enterprise/using/set-up-identity.html"> creeer een nieuwe folder </a>, die niet onder HET beleid is. Marketo-beheerder om de gebruikersmigratie voor deze gebruiker vanuit de migratieconsole opnieuw uit te voeren. <br> niet migreer - Marketo admin om de gebruiker in de Console van de Migratie over te slaan. De knop "Migratie voltooid" wordt weergegeven wanneer alle gebruikers voor de migratie of het overslaan verantwoordelijk zijn. Klik op de koppeling om het gebruikersmigratieproces te voltooien.</td>
  </tr>
  <tr>
    <td><i><a id="create-failure">Fout bij maken</a></i></td>
    <td>Verschillende redenen op de achtergrond.</td>
    <td>Gelieve een steunzaak in te dienen.</td>
  </tr>
  <tr>
    <td><i><a id="type2e-user-failure">Type2e-gebruikersfout</a></i></td>
    <td>Verschillende redenen op de achtergrond.</td>
    <td>Gelieve een steunzaak in te dienen.</td>
  </tr>
</tbody>
</table>
