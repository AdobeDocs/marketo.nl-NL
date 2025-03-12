---
description: Adobe IMS-handleiding voor het oplossen van problemen bij gebruikersmigratie - Marketo Docs - Productdocumentatie
title: Adobe IMS-handleiding voor het oplossen van problemen met gebruikersmigratie
hide: true
hidefromtoc: true
feature: Marketo with Adobe Identity
exl-id: 921d9d45-c5c2-405c-bd3b-be8aa6d11e2f
source-git-commit: e96bc8676a73694ec60f46bb045f2a6ea5d8069c
workflow-type: tm+mt
source-wordcount: '674'
ht-degree: 0%

---

# Adobe IMS-handleiding voor het oplossen van problemen met gebruikersmigratie {#adobe-ims-user-migration-troubleshooting-guide}

Tijdens het IMS-gebruikersmigratieproces wordt een Adobe-gebruiker gemaakt voor elke Marketo Engage-gebruiker die wordt gemigreerd (tenzij deze al met hetzelfde e-mailadres bestaat). Soms, wordt het niet gecreeerd, wat aan het verslag van de gebruiker in de Actieve Folder of kwesties met het e-mailadres kan worden toegeschreven. Als dit gebeurt, ziet de Marketo Engage-beheerder de reden in het migratiestatus van de gebruiker in de console voor zelfmigratie.

## Foutberichten {#error-messages}

Bepaal eerst of de gebruiker moet worden gemigreerd of niet. Dat heeft invloed op de stappen die moeten worden uitgevoerd.

Gebruik de sectie &quot;Op deze pagina&quot; aan de rechterkant om rechtstreeks naar een specifieke fout te gaan.

### Niet in directory {#not-in-directory}

**de oorzaak van de Wortel**: De gebruiker bestaat niet in Actieve Folder (AD). Voor organisaties met een SSO waarvoor de AD-synchronisatie is ingeschakeld, kan de gebruiker alleen worden gemaakt via Identiteitsprovider (IdP). De gebruiker kan daarom niet via Admin Console worden toegevoegd tijdens de migratie naar gebruikers.

**Resoluties**:

_als de gebruiker niet moet worden gemigreerd_ - Marketo Engage admin om de gebruiker in de Console van de Migratie over te slaan. De knop &quot;Migratie voltooid&quot; wordt weergegeven wanneer alle gebruikers voor de migratie of het overslaan verantwoordelijk zijn. Klik op de knop om het migratieproces van de gebruiker te voltooien.

_als de gebruiker moet worden gemigreerd_ - de gebruiker moet aan de Actieve Folder met juiste toestemmingen door een systeembeheerder worden toegevoegd. Marketo Engage-beheerder voert de gebruikersmigratie voor deze gebruiker opnieuw uit vanuit de migratieconsole.

### Ongeldig Gmail-teken {#gmail-invalid-character}

**Oorzaak van de wortel**: Per het veiligheidsbeleid van Adobe, worden de karakters `.` en `+` niet toegestaan in een Gmail- e-mailadres. Beide tekens zijn toegestaan in e-mailadressen die geen Gmail zijn.

**Resoluties**:

_als de gebruiker niet moet worden gemigreerd_ - Marketo Engage admin om de gebruiker in de Console van de Migratie over te slaan. De knop &quot;Migratie voltooid&quot; wordt weergegeven wanneer alle gebruikers voor de migratie of het overslaan verantwoordelijk zijn. Klik op de knop om het migratieproces van de gebruiker te voltooien.

_als de gebruiker_ moet worden gemigreerd - het e-mailadres moet in Marketo Engage worden bijgewerkt om aan het de veiligheidsbeleid van Adobe te voldoen en opnieuw te verifiëren. Marketo-beheerder voert de gebruikersmigratie voor deze gebruiker opnieuw uit vanuit de migratieconsole.

### Inactieve gebruiker {#inactive-user}

**de oorzaak van de wortel**: De Synchronisatie van de ADVERTENTIE wordt toegelaten, en de gefedereerde rekening van de gebruiker bestaat maar in inactief/gehandicapte status.

**Resoluties**:

_als de gebruiker niet moet worden gemigreerd_ - Marketo Engage admin om de gebruiker in de Console van de Migratie over te slaan. De knop &quot;Migratie voltooid&quot; wordt weergegeven wanneer alle gebruikers voor de migratie of het overslaan verantwoordelijk zijn. Klik op de knop om het migratieproces van de gebruiker te voltooien.

_als de gebruiker moet worden gemigreerd_ - de status van de gebruiker en de juiste toestemmingen moeten worden hersteld. Marketo Engage-beheerder voert de gebruikersmigratie voor deze gebruiker opnieuw uit vanuit de migratieconsole.

### Niet in domein {#not-in-domain}

**de oorzaak van de wortel**: De handhaving van het domein wordt toegelaten in Admin Console, maar het domein van het e-mailadres voor de gebruiker is geen één van de toegestane domeinen.

**Resoluties**:

_als de gebruiker niet moet worden gemigreerd_ - Marketo Engage admin om de gebruiker in de Console van de Migratie over te slaan. De knop &quot;Migratie voltooid&quot; wordt weergegeven wanneer alle gebruikers voor de migratie of het overslaan verantwoordelijk zijn. Klik op de knop om het migratieproces van de gebruiker te voltooien.

_als de gebruiker_ moet worden gemigreerd - het e-mailadres moet in Marketo Engage worden bijgewerkt om aan het beleid van de Handhaving van het Domein (DE) te voldoen. Alternatief, kan Admin van het Systeem of [ het domein ](https://helpx.adobe.com/enterprise/using/manage-domains-directories.html#move-domains-across-directories) bewegen {target="_blank"} aan een andere gehandicapte folder van de Handhaving van het Domein (DE), of [ tot een nieuwe folder ](https://helpx.adobe.com/enterprise/using/set-up-identity.html) {target="_blank"} leiden die niet onder het beleid van DE WIJZE is. Marketo Engage-beheerder voert de gebruikersmigratie voor deze gebruiker opnieuw uit vanuit de migratieconsole.

### Fout bij maken {#create-failure}

**de oorzaak van de wortel**: Deze fout kan door diverse redenen in het achterste eind worden veroorzaakt.

**Resoluties**:

Verzend een steungeval met relevante details voor [ de Steun van Marketo ](https://nation.marketo.com/t5/support/ct-p/Support) {target="_blank"}.

### Type2e-gebruikersfout {#type2e-user-failure}

**de oorzaak van de wortel**: Deze fout kan door diverse redenen in het achterste eind worden veroorzaakt.

**Resoluties**:

Verzend een steungeval met relevante details voor [ de Steun van Marketo ](https://nation.marketo.com/t5/support/ct-p/Support) {target="_blank"}.
