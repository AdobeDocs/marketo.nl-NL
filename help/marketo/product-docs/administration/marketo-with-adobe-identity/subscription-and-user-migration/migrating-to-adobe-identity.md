---
description: Migreren naar Adobe Identity - Marketo Docs - Productdocumentatie
title: Migreren naar Adobe-id
hide: true
hidefromtoc: true
feature: Marketo with Adobe Identity
exl-id: a7969204-0ec9-45aa-a206-eff2df8adcd0
source-git-commit: 368e857c276e4dc19599b5169e82f578ce9becb0
workflow-type: tm+mt
source-wordcount: '2270'
ht-degree: 0%

---

# Migreren naar Adobe-id {#migrating-to-adobe-identity}

Wanneer de Adobe de gebruikersmigratie van een abonnement plant, zullen de productbeheerders van het Marketo Engage toegang tot de Console van de Migratie krijgen, die in het navigatiemenu in het Admin gebied onder het onderwerp van de Integratie kan worden gevonden.

SCREENSHOT

## Pre-migratie {#pre-migration}

Voordat de migratie begint, kan een beheerder de begindatum voor de gebruikersmigratie voor zijn abonnement wijzigen door naar het scherm Pre-Migration in de migratieconsole te navigeren. Als u de datum wilt wijzigen, klikt de beheerder op de knop **Bewerken** knop.

SCREENSHOT

De beheerder kan een datum kiezen tussen 8 en 30 dagen in de toekomst. Wanneer een datum is geselecteerd, moet de beheerder op **Opslaan** om de wijziging aan te brengen.

SCREENSHOT

>[!NOTE]
>
>Als u een datum wilt aanvragen die valt vóór 8 dagen of na 30 dagen, of als u de datum na de vergrendeling van de pre-migratieconsole moet aanpassen, stuurt u een e-mail naar `marketocares@marketo.com`.

## Migratie naar identiteit Adobe {#migrations-to-adobe-identity}

Alle Marketo-abonnementen met een Amerikaanse tijdzone worden gemigreerd vanaf middernacht, Pacific Standard Time, de begindatum van de gebruikersmigratie. De migratie van de gebruiker voor alle andere abonnementen zal om middernacht van de gespecificeerde tijdzone van het abonnement beginnen. Wanneer de gebruikersmigratie van een abonnement begint, is gebruikersbeheer niet meer beschikbaar in het gebied Marketo Admin en wordt het alleen in de Adobe Admin Console uitgevoerd. Rolbeheer blijft aanwezig op het tabblad Gebruikers en rollen in het gebied Marketo Admin en op het lokale gebruikersbeheer (alleen API).

Adobe migreert automatisch alle Marketo-beheerders eerst met geverifieerde e-mails. Als Marketo Admins naar Adobe Identity wordt gemigreerd, worden ze als productbeheerder voor het Marketo-abonnement toegevoegd aan de Adobe Admin Console van het abonnement en krijgen ze de rol Productbeheerder voor Adobe toegewezen in de Marketo-toepassing (samen met eventuele andere rollen die ze eerder hadden) en hebben hun Adobe ID recht op het abonnement. De beheerders ontvangen twee e-mails. Eén die aangeeft dat hij als Adobe productbeheerder is toegewezen, en de andere die aangeeft dat zijn Adobe ID recht heeft op het Marketo-product.

**E-mail Marketo-productbeheerder**

SCREENSHOT

**Marketo Entitlement Email**

SCREENSHOT

**Als uw Marketo-abonnement minder dan 75 gebruikers heeft**, zal de Adobe automatisch de rest van uw gebruikers migreren. Deze workflow is bedoeld om het hoogste niveau van automatisering te bieden en er is geen actie vereist om de migratie uit te voeren. Na het voltooien van de migratie wordt de Marketo Migration Console niet meer weergegeven in het Marketo Admin-navigatiegebied en kunnen alle gebruikers Marketo openen via een Adobe ID.

**Als uw Marketo-abonnement 75 of meer gebruikers heeft**, Marketo-productbeheerders krijgen toegang tot het Self-Service User Migration-hulpprogramma van de migratieconsole wanneer de migratie naar gebruikers begint en worden via banner gewaarschuwd wanneer ze zich aanmelden op de pagina Mijn Marketo. De beheerder is verantwoordelijk voor het voltooien van de gebruikersmigratie met het Self-Service User Migration-hulpprogramma.

SCREENSHOT

## Marketo Self-Service-gebruikersmigratie {#marketo-self-service-user-migration}

Het Marketo Self-Service User Migration Console-hulpprogramma bestaat uit twee tabbladen.

* **Tabblad Migratiestatus**
* **Tabblad Gebruikersmigratie**

### Tabblad Migratiestatus {#migration-status-tab}

Het tabblad Migratiestatus bevat algemene maatstaven voor de voortgang van de e-mailverificatie van gebruikers, de migratie en activering van gebruikers en de voltooiing van de abonnementmigratie.

SCREENSHOT

Boven aan de Migratiestatus worden het verlopen van de abonnementmigratie en de knop voor het verlengen van de vervaldatum weergegeven. Meer informatie over het verlopen van de migratie vindt u in de [Sectie Verlopen gebruikersmigratie](#user-migration-expiration).

In het volgende gedeelte van het tabblad Migratiestatus zijn er twee voortgangsbalken. In de eerste voortgangsbalk ziet u de voortgang van het voltooien van de e-mailverificatie van de gebruiker. In de tweede voortgangsbalk ziet u de voortgang van de voltooiing van de gebruikersmigratie.

Daarna, zijn er drie secties van de Status die aan admin worden getoond.

* **E-mailverificatie van gebruiker**: verificatiestatus van gebruikers binnen het abonnement.
* **Migratie en activering van gebruikers**: migratie van gebruikers en activeringsstatus (migratie en recht op het product van de Marketo Engage) van de gebruikers in het abonnement.
* **Migratiebevestiging**: migratie voltooid status van het abonnement.

**E-mailverificatie van gebruiker**

In het gedeelte E-mailverificatie van gebruiker kan een beheerder de huidige status van e-mailverificatie voor de gebruikers in het abonnement vinden, voordat er wordt overgeschakeld naar Identiteit Adobe.

Een beheerder kan de verificatiestatus van het abonnement, het percentage gebruikers in het abonnement dat de e-mailverificatie heeft voltooid, en het aantal gebruikers die zijn gemarkeerd als overgeslagen, weergeven. De status wordt gerapporteerd over de status van de e-mailverificatiestatus van alle gebruikers in het abonnement. De beheerder kan op het aantal overgeslagen gebruikers klikken en zal aan het lusje van de Migratie van de Gebruiker worden genavigeerd om de overgeslagen gebruikers te bekijken.

De verificatie-e-mail kan opnieuw worden verzonden door een beheerder op het tabblad Gebruikersmigratie van de migratieconsole en het tabblad Gebruiker en rollen in het gebied Marketo Admin of door de gebruiker in de accountinstellingen. De koppeling in het verificatiebericht verloopt over 3 dagen, net als in e-mails met gebruikersuitnodigingen. Meer informatie over e-mailverificatie vindt u op de [Gemeenschap](https://nation.marketo.com/) en in de [e-mailverificatiedocumentatie](/help/marketo/product-docs/administration/users-and-roles/email-verification.md).

>[!IMPORTANT]
>
>Als een gebruiker van het Marketo Engage zijn e-mailadres niet verifieert, kan hij of zij niet naar een Adobe ID worden gemigreerd en verliest hij of zij de toegang tot het Marketo-abonnement nadat de migratie is voltooid. Om toegang te krijgen, moet een Marketo-productbeheerder deze als nieuwe gebruiker toevoegen.

**Migratie en activering van gebruikers**

In de sectie Gebruikersmigratie en -activering kan een beheerder de huidige status van de totale gebruikersmigratie en de machtiging voor de Adobe Identity Management System vinden.

Een beheerder kan het percentage gebruikers in hun abonnement bekijken dat naar een Adobe ID is gemigreerd of als Overgeslagen is gemarkeerd. De status wordt gerapporteerd over de status van de migratiestatus van alle gebruikers naar een Adobe ID in het abonnement, of wordt gemarkeerd als Overgeslagen en wordt niet gemigreerd. Wanneer gebruikers worden gemigreerd en recht hebben op Marketo Engage of worden overgeslagen, wordt deze status bijgewerkt.

**Migratiebevestiging**

In het gedeelte Migratiebevestiging moet een beheerder bevestigen dat de migratie van gebruikers is voltooid voor het abonnement.

Wanneer alle gebruikers in het abonnement zijn aangemeld (gemigreerd of overgeslagen), wordt de knop &#39;Volledige migratie&#39; weergegeven.

SCREENSHOT

De beheerder die migratie uitvoert, moet de migratiebevestiging voltooien door op de knop **Volledige migratie** knop.

SCREENSHOT

Nadat de voltooiing van de gebruikersmigratie is bevestigd, wordt de migratieconsole verwijderd uit het navigatiemenu Admin.

### Verlopen gebruikersmigratie {#user-migration-expiration}

Adobe vereist dat klanten binnen 30 dagen de migratie voor eigen gebruik voltooien. Beheerders worden niet geblokkeerd voor het migreren van gebruikers of het voltooien van de migratie als de vervaldatum verstreken is. Ze kunnen echter alleen op verzoek gebruikers migreren. Als een beheerder meer tijd nodig heeft, kan hij of zij de vervaldatum van het abonnement verlengen.

SCREENSHOT

Klik op de knop **Verlopen verlengen** de datum wordt bijgewerkt naar een week later. Een beheerder kan de looptijd tot drie keer verlengen.

SCREENSHOT

SCREENSHOT

De Adobe zal uitreiken als u de migratie niet voltooit tegen de vervaldatum.

### Tabblad Gebruikersmigratie {#user-migration-tab}

Op het tabblad Gebruikersmigratie kunnen beheerders de volledige controle over de migratie van gebruikers hebben.

Beheerders kunnen kiezen uit:

* E-mails met verificatie voor niet-geverifieerde gebruikers activeren via de knop E-mail verifiëren
* Overslaan van gebruikersmigratie voor gebruikers die weten of de beheerder hun e-mail kan/zal verifiëren of niet mag worden gemigreerd via de knop Migratie overslaan
* Geselecteerde gebruikers op aanvraag migreren via de knop Nu migreren
* De gebruikersmigratie voor een bepaalde datum plannen via de knop &#39;Migratie plannen&#39;
* Alle in aanmerking komende gebruikers naar behoefte migreren (geen gebruikersselectie nodig) via de knop Alle gebruikers migreren

SCREENSHOT

**E-mail verifiëren**

E-mailverificatie is vereist voor het migreren van een gebruiker naar een Adobe ID. Als er gebruikers zijn die hun e-mailadres niet hebben geverifieerd en die moeten worden gemigreerd, kan de beheerder de verificatie-e-mail activeren om opnieuw naar de gebruiker te worden verzonden. Als u een niet-geverifieerde gebruiker selecteert, wordt op de knop E-mail controleren geklikt.

SCREENSHOT

Wanneer de beheerder op de knop **E-mail verifiëren** ontvangen ze een melding dat het e-mailbericht is verzonden.

SCREENSHOT

**Gebruikersmigratie overslaan en ongedaan maken**

Tijdens gebruikersmigratie moeten alle gebruikers worden gemigreerd of overgeslagen. Voor Adobe moeten beheerders erkennen dat een gebruiker niet wordt gemigreerd en dat een beheerder de gebruiker moet markeren als overgeslagen. Als de beheerder dit niet doet, kunnen ze de voltooiing van de gebruikersmigratie niet bevestigen. Alle overgeslagen gebruikers verliezen de toegang tot Marketo zodra de gebruikersmigratie is voltooid.

>[!IMPORTANT]
>
>Een beheerder moet alle gebruikers met niet-geverifieerde e-mails overslaan. Als er gebruikers zijn die hun e-mails hebben geverifieerd, maar de beheerder ze om welke reden dan ook niet wil migreren, moeten ze ze als overgeslagen markeren.

Als u een gebruiker wilt overslaan, kan de beheerder de gewenste gebruiker(s) selecteren. Klik op de knop &#39;Migratie overslaan&#39;. Als u op de knop **Migratie overslaan** wordt de pagina vernieuwd en worden de verificatiestatus en migratiestatus van de geselecteerde gebruiker bijgewerkt naar &#39;Overgeslagen&#39;.

SCREENSHOT

Een beheerder kan een eerder overgeslagen gebruiker ongedaan maken, als het wordt bepaald dat de gebruiker moet worden gemigreerd.

Als u het overslaan van een gebruiker ongedaan wilt maken, kan de beheerder de gewenste gebruiker selecteren. Klik op de knop &#39;Migratie ongedaan maken&#39;. Als u op de knop **Migratie ongedaan maken** de pagina wordt vernieuwd.  De verificatiestatus van de geselecteerde gebruiker wordt bijgewerkt naar de huidige status &#39;Verified&#39; of &#39;Unverify&#39; en de migratiestatus van de gebruiker wordt bijgewerkt naar &#39;Not Started&#39;.

SCREENSHOT

>[!NOTE]
>
>De knop &#39;Migratie ongedaan maken&#39; is alleen actief als alle geselecteerde gebruikers de status &#39;Overgeslagen&#39; hebben bij Migratie.

### Marketo-gebruikers migreren naar Adobe-id&#39;s {#migrating-marketo-users-to-adobe-ids}

Voor wie meer controle tijdens het gebruikersmigratieproces wenst, steunt Marketo een Zelfbediening benadering voor abonnementen met 75 of meer gebruikers. Marketo-productbeheerders kunnen gebruikers selecteren voor migratie in batches of voor alle in aanmerking komende gebruikers tegelijk. Als gebruikers zijn geselecteerd, hebben beheerders de optie &quot;Nu migreren&quot; of &quot;Migratie plannen&quot; voor een latere datum, zodat beheerders flexibel zijn en zelf kunnen bepalen welke gebruikers worden gemigreerd en wanneer. Beheerders krijgen ook de optie &quot;Alle gebruikers migreren&quot; in een abonnement te zien.

Een beheerder kan bijvoorbeeld een groep &#39;machtsgebruikers&#39; selecteren die ze eerst willen migreren. Nadat deze gebruikersmigraties zijn voltooid, kunnen ze verschillende groepen selecteren op basis van variabele, zoals werkruimte/bedrijfsfunctie/rol, om de migratie van gebruikers verder in een batch uit te voeren. Of ze kunnen besluiten om de rest van de gebruikers in de abonnementen te migreren nadat de eerste batch is geslaagd. Het doel is de meeste flexibiliteit te bieden bij het implementeren van Adobe-id&#39;s voor gebruikers.

Alle gebruikersmigraties vinden gelijktijdig plaats en moeten binnen zestig seconden met succes worden voltooid. Terwijl de gebruikersmigratie voor een specifieke gebruiker plaatsvindt, zou de gebruiker toegang tot maximaal 1 minuut kunnen verliezen, en dat is slechts als de gebruiker in de toepassing wordt geregistreerd. Na voltooiing van de gebruikersmigratie ontvangt de gebruiker een e-mail over hoe hij zich bij Marketo Engage met een Adobe-id kan aanmelden. De gebruiker moet de uitnodiging accepteren via de knopkoppeling in de e-mail. Nadat de uitnodiging is geaccepteerd, moet de gebruiker zich aanmelden met een Adobe ID. Instructies voor het aanmelden bij Marketo Engage met een Adobe ID [hier te vinden](/help/marketo/product-docs/administration/marketo-with-adobe-identity/user-sign-in-with-adobe-id.md).

SCREENSHOT

De migratie van gebruikers wordt onafhankelijk verwerkt. Als de migratie van gebruikers mislukt, wordt de migratie van andere gebruikers voortgezet. Als er een fout optreedt bij de gebruikersmigratie, is er geen actie vereist door een beheerder. De beheerder zal een e-mailbericht over de fout worden verzonden en gealarmeerd dat de Adobe werkt om de kwestie onmiddellijk op te lossen. Als de migratie van een gebruiker mislukt en die gebruiker is aangemeld bij het Marketo Engage, kan de gebruiker de toegang tot de computer gedurende maximaal twee minuten verliezen terwijl er zich migratiepogingen voordoen. Als de migratie van een gebruiker mislukt, kan de gebruiker het Marketo Engage blijven benaderen met zijn Marketo-identiteit totdat hij of zij een e-mail ontvangt met de melding dat de migratie is voltooid en dat hij of zij is uitgenodigd om zich aan te melden bij een Adobe ID.

SCREENSHOT

**Nu migreren**

Een beheerder kan een of meer gebruikers selecteren om op verzoek te migreren. Dit zal de migratie van de gebruikers onmiddellijk teweegbrengen. Als u een of meer gebruikers wilt migreren, kan de beheerder de gewenste gebruiker(s) selecteren en wordt op de knop &#39;Nu migreren&#39; geklikt.

SCREENSHOT

>[!NOTE]
>
>De knop &#39;Nu migreren&#39; is alleen actief als alle geselecteerde gebruikers de verificatiestatus &#39;Verified&#39; hebben.

Als u op de knop **Nu migreren** wordt de beheerder gevraagd de migratie van de geselecteerde gebruiker(s) te bevestigen. Zodra de beheerder bevestigt, zullen de gebruikersmigraties beginnen verwerking zo spoedig mogelijk.

SCREENSHOT

**Migratie plannen**

Een beheerder kan een of meer gebruikers selecteren om de migratie op een latere datum te plannen. Om migratie voor één of meerdere gebruikers te plannen, selecteert de beheerder de gewenste gebruiker(s) en de knoop van de Migratie van het Programma zal klikbaar worden.

SCREENSHOT

>[!NOTE]
>
>De knop &#39;Migratie plannen&#39; is alleen actief als alle geselecteerde gebruikers de verificatiestatus &#39;Geverifieerd&#39; hebben.

Als u op de knop **Migratie plannen** wordt de beheerder gevraagd de gewenste migratiedatum van de geselecteerde gebruiker(s) te selecteren. De beheerder kan alleen datums selecteren vóór de migratiedatum van het abonnement. Wanneer de beheerder bevestigt, zal (zullen) de gebruikersmigratie(s) gepland zijn om met verwerking op de geselecteerde datum te beginnen.

SCREENSHOT

>[!NOTE]
>
>Alle Marketo-abonnementen met een Amerikaanse tijdzone worden gemigreerd vanaf middernacht, Pacific Standard Time, van de startdatum van de migratie. De migratie van de gebruiker voor alle andere abonnementen zal om middernacht van de gespecificeerde tijdzone van het abonnement beginnen.

**Alle gebruikers migreren**

Een beheerder kan alle in aanmerking komende gebruikers in een abonnement op elk gewenst moment migreren. Dit zal de migratie van de in aanmerking komende gebruikers onmiddellijk in gang zetten. In aanmerking komende gebruikers zijn gebruikers met geverifieerde e-mails die nog niet zijn gemigreerd.

SCREENSHOT

Als u op de knop **Alle gebruikers migreren** wordt de beheerder gevraagd de migratie van alle in aanmerking komende gebruikers te bevestigen. Wanneer de beheerder dit bevestigt, worden de gebruikersmigraties zo snel mogelijk verwerkt.

SCREENSHOT
