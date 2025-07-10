---
description: Adobe IMS-handleiding voor het oplossen van problemen bij gebruikersmigratie - Marketo Docs - Productdocumentatie
title: Adobe IMS-handleiding voor het oplossen van problemen met gebruikersmigratie
feature: Marketo with Adobe Identity
exl-id: 921d9d45-c5c2-405c-bd3b-be8aa6d11e2f
source-git-commit: e95748ed9a26f5454c342c6f6a9c29ec687c7cad
workflow-type: tm+mt
source-wordcount: '877'
ht-degree: 0%

---

# Adobe IMS-handleiding voor het oplossen van problemen met gebruikersmigratie {#adobe-ims-user-migration-troubleshooting-guide}

Tijdens het IMS-gebruikersmigratieproces wordt een Adobe-gebruiker gemaakt voor elke Marketo Engage-gebruiker die wordt gemigreerd (tenzij deze al met hetzelfde e-mailadres bestaat). Soms, wordt het niet gecreeerd, wat aan het verslag van de gebruiker in de Actieve Folder of kwesties met het e-mailadres kan worden toegeschreven.

In dit artikel wordt voor gebruikers die zelfmigraties uitvoeren, elk foutbericht weergegeven dat u ziet in het statusveld van de zelfmigratieconsole.

>[!NOTE]
>
>De map-/domeingerelateerde fouten kunnen worden geactiveerd door een andere org/Admin Console waar een directory trust is ingesteld of het domein is geclaimd.

## Foutberichten {#error-messages}

Bepaal eerst of de gebruiker moet worden gemigreerd of niet. Dat heeft invloed op de stappen die moeten worden uitgevoerd.

Gebruik de sectie &quot;Op deze pagina&quot; aan de rechterkant om rechtstreeks naar een specifieke fout te gaan.

### Ongeldig Gmail-teken {#gmail-invalid-character}

**Oorzaak van de wortel**: Per het veiligheidsbeleid van Adobe, worden de karakters `.` en `+` niet toegestaan in een Gmail- e-mailadres. Beide tekens zijn toegestaan in e-mailadressen die geen Gmail zijn.

**Resoluties**:

_als de gebruiker moet worden gemigreerd_ - het e-mailadres moet in Marketo Engage worden bijgewerkt om aan het veiligheidsbeleid van Adobe te voldoen en opnieuw geverifieerd. Marketo-beheerder voert de gebruikersmigratie voor deze gebruiker opnieuw uit vanuit de migratieconsole.

_als de gebruiker ****niet_ moet worden gemigreerd - Marketo Engage admin om de gebruiker in de Console van de Migratie over te slaan. De knop &quot;Migratie voltooid&quot; wordt weergegeven wanneer alle gebruikers voor de migratie of het overslaan verantwoordelijk zijn. Klik op de knop om het migratieproces van de gebruiker te voltooien.

### Gebruiker niet in directory {#user-not-in-directory}

**de oorzaak van de Wortel**: De gebruiker bestaat niet in Actieve Folder (AD). Voor organisaties met een SSO waarvoor de AD-synchronisatie is ingeschakeld, kan de gebruiker alleen worden gemaakt via Identiteitsprovider (IdP). De gebruiker kan daarom niet via Admin Console worden toegevoegd tijdens de migratie naar gebruikers.

**Resoluties**:

_als de gebruiker moet worden gemigreerd_ - de gebruiker moet aan de Actieve Folder met juiste toestemmingen door een systeembeheerder worden toegevoegd. Marketo Engage-beheerder voert de gebruikersmigratie voor deze gebruiker opnieuw uit vanuit de migratieconsole.

_als de gebruiker ****niet_ moet worden gemigreerd - Marketo Engage admin om de gebruiker in de Console van de Migratie over te slaan. De knop &quot;Migratie voltooid&quot; wordt weergegeven wanneer alle gebruikers voor de migratie of het overslaan verantwoordelijk zijn. Klik op de knop om het migratieproces van de gebruiker te voltooien.

### Inactieve gebruiker {#inactive-user}

**de oorzaak van de wortel**: De Synchronisatie van de ADVERTENTIE wordt toegelaten, en de gefedereerde rekening van de gebruiker bestaat maar in inactief/gehandicapte status.

**Resoluties**:

_als de gebruiker moet worden gemigreerd_ - de status van de gebruiker en de juiste toestemmingen moeten door een systeembeheerder worden hersteld. Marketo Engage-beheerder voert de gebruikersmigratie voor deze gebruiker opnieuw uit vanuit de migratieconsole.

_als de gebruiker ****niet_ moet worden gemigreerd - Marketo Engage admin om de gebruiker in de Console van de Migratie over te slaan. De knop &quot;Migratie voltooid&quot; wordt weergegeven wanneer alle gebruikers voor de migratie of het overslaan verantwoordelijk zijn. Klik op de knop om het migratieproces van de gebruiker te voltooien.

### Ongeldig domein {#invalid-domain}

**de oorzaak van de wortel**: De handhaving van het domein wordt toegelaten in Admin Console. Het domein van het e-mailadres voor de gebruiker is echter geen van de toegestane domeinen of het domein is geclaimd in een andere org/Admin Console.

**Resoluties**:

_als de gebruiker moet worden gemigreerd_ (en de domeinhandhaving wordt toegelaten in migrerende org) - het e-mailadres moet in Marketo Engage worden bijgewerkt om aan het beleid van de Handhaving van het Domein (DE) te voldoen. Alternatief, kan Admin van het Systeem of [ het domein ](https://helpx.adobe.com/enterprise/using/manage-domains-directories.html#move-domains-across-directories){target="_blank"} aan een andere gehandicapte folder van de Handhaving van het Domein bewegen (DE), of [ een nieuwe folder ](https://helpx.adobe.com/enterprise/using/set-up-identity.html){target="_blank"} creëren die niet onder het beleid van DE is. Marketo Engage-beheerder voert de gebruikersmigratie voor deze gebruiker opnieuw uit vanuit de migratieconsole.

_als de gebruiker moet worden gemigreerd_ (en de domeinhandhaving wordt toegelaten in een andere org) - een systeembeheerder van org waar het domein is geclaimd moet het e-mailadres van de gebruiker aan de uitzonderingslijst toevoegen. Marketo Engage-beheerder voert de gebruikersmigratie voor deze gebruiker opnieuw uit vanuit de migratieconsole.

_als de gebruiker ****niet_ moet worden gemigreerd - Marketo Engage admin om de gebruiker in de Console van de Migratie over te slaan. De knop &quot;Migratie voltooid&quot; wordt weergegeven wanneer alle gebruikers voor de migratie of het overslaan verantwoordelijk zijn. Klik op de knop om het migratieproces van de gebruiker te voltooien.

### Type2E-fout {#type2e-failure}

**De oorzaak van de wortel**: De verwezenlijking van een gefedereerde gebruikersrekening (voor Enige Sign-On) ontbrak tijdens gebruikersmigratie omdat een Adobe ID reeds voor het zelfde e-mailadres zoals een individuele gebruiker bestaat.

**Resoluties**:

1. Verwijder de individuele gebruiker van Adobe org. Opmerking: de gebruiker verliest de toegang tot alle producten en moet later opnieuw worden gemachtigd.
1. Voer de gebruikersmigratie opnieuw uit, zodat er voor deze gebruiker een gefedereerde gebruikersaccount wordt gemaakt.
1. Voeg de gebruiker terug aan de producten zij eerder toegang tot hadden.

### Maken van gebruiker mislukt {#user-creation-failed}

[Zie hieronder](#failed)

### Marketo Entitlement Failed {#marketo-entitlement-failed}

[Zie hieronder](#failed)

### Pendo-migratie mislukt {#pendo-migration-failed}

[Zie hieronder](#failed)

### Migratie van gebruikersgegevens is mislukt {#user-data-migration-failed}

[Zie hieronder](#failed)

### Synchronisatie van productgegevens is mislukt {#product-data-sync-failed}

[Zie hieronder](#failed)

### Adobe Entitlement Failed {#adobe-entitlement-failed}

[Zie hieronder](#failed)

### Afmelden door gebruiker mislukt {#user-sign-out-failed}

[Zie hieronder](#failed)

### Maken van Adobe ID is mislukt {#adobe-id-creation-failed}

[Zie hieronder](#failed)

### Mislukt {#failed}

**de oorzaak van de wortel**: Deze fouten kunnen door diverse redenen in het achterste deel worden veroorzaakt.

**Resoluties**:

Verzend een steungeval met relevante details voor [ de Steun van Marketo ](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"}.
