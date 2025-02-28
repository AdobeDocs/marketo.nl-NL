---
description: Adobe IMS-handleiding voor probleemoplossing - Marketo Docs - Productdocumentatie
title: Adobe IMS-gids voor probleemoplossing
hide: true
hidefromtoc: true
feature: Marketo with Adobe Identity
exl-id: 921d9d45-c5c2-405c-bd3b-be8aa6d11e2f
source-git-commit: 2a01045abbc23bce9531c64e3494fb12a9adf1bd
workflow-type: tm+mt
source-wordcount: '602'
ht-degree: 0%

---

# Adobe IMS-gids voor probleemoplossing {#adobe-ims-troubleshooting-guide}

Tijdens het IMS-gebruikersmigratieproces wordt een Adobe-gebruiker gemaakt voor elke Marketo Engage-gebruiker die wordt gemigreerd. Soms, wordt het niet gecreeerd (om diverse redenen, met betrekking tot het verslag van de gebruiker in de Actieve Folder of kwesties met het e-mailadres). Als dit gebeurt, ziet de Marketo Engage-beheerder de reden in het migratiestatus veld van de gebruiker op de zelfmigratieconsole.

## Foutberichten {#error-messages}

Gebruik de sectie &quot;Op deze pagina&quot; aan de rechterkant om rechtstreeks naar een specifieke fout te gaan en te leren hoe u deze kunt oplossen.

### Niet in directory {#not-in-directory}

_de oorzaak van de Wortel_: De gebruiker bestaat niet in Actieve Folder (AD). Voor organisaties met een SSO waarvoor de AD-synchronisatie is ingeschakeld, kan de gebruiker alleen worden gemaakt via Identiteitsprovider (IdP). De gebruiker kan daarom niet via Admin Console worden toegevoegd tijdens de migratie naar gebruikers.

_Resoluties_:

Pre-migratie - Marketo Enage-beheerder slaat de gebruiker in de migratieconsole over. De knop &quot;Migratie voltooid&quot; wordt weergegeven wanneer alle gebruikers voor de migratie of het overslaan verantwoordelijk zijn. Klik op de knop om het migratieproces van de gebruiker te voltooien.

Post-migratie - De gebruiker moet aan de Actieve Folder met juiste toestemmingen worden toegevoegd. Marketo Engage-beheerder om de gebruikersmigratie voor deze gebruiker opnieuw uit te voeren vanuit de migratieconsole.

### Ongeldig Gmail-teken {#gmail-invalid-character}

_Oorzaak van de wortel_: Per het veiligheidsbeleid van Adobe, worden de karakters `.` en `+` niet toegestaan in een Gmail- e-mailadres. Beide tekens zijn toegestaan in e-mailadressen die geen Gmail zijn.

_Resoluties_:

Pre-migratie - Marketo Enage-beheerder slaat de gebruiker in de migratieconsole over. De knop &quot;Migratie voltooid&quot; wordt weergegeven wanneer alle gebruikers voor de migratie of het overslaan verantwoordelijk zijn. Klik op de knop om het migratieproces van de gebruiker te voltooien.

Na de migratie - Het e-mailadres moet in Marketo Engage worden bijgewerkt om te voldoen aan het beveiligingsbeleid van Adobe. Marketo-beheerder kan de gebruikersmigratie voor deze gebruiker opnieuw uitvoeren vanuit de migratieconsole.

### Inactieve gebruiker {#inactive-user}

_de oorzaak van de wortel_: De Synchronisatie van de ADVERTENTIE wordt toegelaten, en de gefedereerde rekening van de gebruiker bestaat maar in inactief/gehandicapte status.

_Resoluties_:

Pre-migratie - Marketo Enage-beheerder slaat de gebruiker in de migratieconsole over. De knop &quot;Migratie voltooid&quot; wordt weergegeven wanneer alle gebruikers voor de migratie of het overslaan verantwoordelijk zijn. Klik op de knop om het migratieproces van de gebruiker te voltooien.

Na de migratie: de status van de gebruiker en de juiste machtigingen moeten worden hersteld. Marketo Engage-beheerder om de gebruikersmigratie voor deze gebruiker opnieuw uit te voeren vanuit de migratieconsole.

### Niet in domein {#not-in-domain}

_de oorzaak van de wortel_: De handhaving van het domein wordt toegelaten in Admin Console, maar het domein van het e-mailadres voor de gebruiker is geen één van de toegestane domeinen.

_Resoluties_:

Pre-migratie - Marketo Enage-beheerder slaat de gebruiker in de migratieconsole over. De knop &quot;Migratie voltooid&quot; wordt weergegeven wanneer alle gebruikers voor de migratie of het overslaan verantwoordelijk zijn. Klik op de knop om het migratieproces van de gebruiker te voltooien.

Na de migratie - Het e-mailadres moet in Marketo Engage worden bijgewerkt om te voldoen aan het beleid voor domeinhandhaving (DE). Alternatief, kan Admin van het Systeem of [ het domein ](https://helpx.adobe.com/enterprise/using/manage-domains-directories.html#move-domains-across-directories) bewegen {target="_blank"} aan een andere gehandicapte folder van de Handhaving van het Domein (DE), of [ tot een nieuwe folder ](https://helpx.adobe.com/enterprise/using/set-up-identity.html) {target="_blank"} leiden die niet onder het beleid van DE WIJZE is. Marketo Engage-beheerder om de gebruikersmigratie voor deze gebruiker opnieuw uit te voeren vanuit de migratieconsole.

### Fout bij maken {#create-failure}

_de oorzaak van de wortel_: Deze fout kan door diverse redenen in het achterste eind worden veroorzaakt.

_Resoluties_:

Pre-migratie - gelieve een steungeval voor die [ voor te leggen nog niet gemigreerd ](https://nation.marketo.com/t5/support/ct-p/Support) {target="_blank"}.

Na-migratie - gelieve een steungeval voor die [ reeds gemigreerd ](https://experienceleague.adobe.com/home?support-tab=home#support) voor te leggen {target="_blank"}.

### Type2e-gebruikersfout {#type2e-user-failure}

_de oorzaak van de wortel_: Deze fout kan door diverse redenen in het achterste eind worden veroorzaakt.

_Resoluties_:

Pre-migratie - gelieve een steungeval voor die [ voor te leggen nog niet gemigreerd ](https://nation.marketo.com/t5/support/ct-p/Support) {target="_blank"}.

Na-migratie - gelieve een steungeval voor die [ reeds gemigreerd ](https://experienceleague.adobe.com/home?support-tab=home#support) voor te leggen {target="_blank"}.
