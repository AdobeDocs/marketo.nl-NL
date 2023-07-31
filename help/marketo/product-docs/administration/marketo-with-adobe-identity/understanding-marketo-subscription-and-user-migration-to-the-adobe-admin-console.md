---
description: Een goed begrip van Marketo-abonnement en gebruikersmigratie naar de Adobe Admin Console - Marketo Docs - Productdocumentatie
title: Marketo-abonnement en gebruikersmigratie naar de Adobe Admin Console begrijpen
exl-id: 91e7b56b-2563-4986-a55c-f9760ea88b05
feature: Marketo with Adobe Identity
source-git-commit: 3c7eb2fc2e64898e12f08743225c0b802bf97474
workflow-type: tm+mt
source-wordcount: '1121'
ht-degree: 0%

---

# Marketo-abonnement en gebruikersmigratie naar de Adobe Admin Console begrijpen {#understanding-marketo-subscription-and-user-migration-to-the-adobe-admin-console}

Adobe verbetert de manier waarop u uw Adobe Marketo Engage-abonnementen en -gebruikers beheert, waardoor u en uw organisatie productiever worden. Als onderdeel van deze wijziging migreert Adobe uw Marketo Engage-abonnementen en gebruikers naar de Adobe Admin Console. Dit is een noodzakelijke migratie en heeft geen invloed op een marketingworkflow, inhoud, integratie of middelen.

Leer hoe u de Adobe Admin Console kunt gebruiken om uw rechten voor Adobe te beheren in uw hele organisatie met de [Beheerdershandleiding voor ondernemingen en teams](https://helpx.adobe.com/enterprise/admin-guide.html){target="_blank"}.

## Wat verandert er? {#what-is-changing}

Tijdens de migratie gaan uw abonnement en gebruikersbeheer van de Marketo-toepassing naar de Adobe Admin Console.

* **Systeembeheerders beheren abonnementen op Adobe Admin Console**. Bekijk al uw Adobe producten in één console.

* **Productbeheerders beheren gebruikers en hun toegang op Adobe Admin Console**. Voeg gebruikers voor al uw Adobe-abonnementen toe en verwijder deze.

* **Gebruikers zullen zich aanmelden met Adobe-identiteit**. Adobe migreert bestaande gebruikers naar de Adobe Admin Console. Gebruikers zullen zich aanmelden bij hun Marketo-abonnementen met hun nieuwe Adobe Identity - een Adobe ID- of Adobe Federated ID (SSO).

* **Er is geen wijziging in de manier waarop u alle andere functies beheert** binnen de toepassing van de Marketo Engage zelf, met inbegrip van beheer van eigenschappen, gebruikersrollen, werkruimten, functionaliteit, en gedrag.


## Tijdlijn migratiepad {#migration-journey-timeline}

Adobe migreert eerst uw Marketo Engage-abonnement(en) naar de Adobe Admin Console en migreert vervolgens alle bestaande gebruikers met geverifieerde e-mailadressen. Als u een Systeembeheerder of Marketo-productbeheerder bent, ontvangt u e-mails met instructies voor de migratie. Hier volgt een tijdlijn van wat u kunt verwachten:

### Abonnementsmigratie voltooid {#subscription-migration-complete}

Systeembeheerders ontvangen een e-mail wanneer de migratie naar Adobe Admin Console is voltooid.

Systeembeheerders moeten mogelijk een aantal vereiste stappen uitvoeren voordat de migratie van gebruikers de gevolgen voor Marketo-gebruikers minimaliseert:

* Als uw Marketo-gebruikers zich momenteel aanmelden bij SSO, moet u SSO instellen op de Adobe Admin Console zodat uw gebruikers zich kunnen blijven aanmelden bij SSO. Als uw Marketo-gebruikers momenteel geen SSO gebruiken, maar u wilt deze instellen op Adobe Admin Console, kunt u dit op dit moment doen tijdens de migratiereis.

* Als u al andere Adobe-producten beheert in uw Adobe Admin Console, vraagt Adobe mogelijk om uw toestemming om gebruikers automatisch te migreren naar uw bestaande console. Klik op de knop Aan de slag in het e-mailbericht om naar de toestemmingspagina te navigeren.

Er is momenteel geen wijziging in het gebruikersbeheer. Marketo Admins blijft gebruikers beheren in het gebied Marketo Admin en gebruikers blijven zich aanmelden met hun Marketo Identity totdat hun gebruikersmigratie is voltooid.

### Gebruikersmigratie plannen {#schedule-user-migration}

Nadat uw systeembeheerder de voorwaarden voltooit die in de vorige sectie worden beschreven, zal Adobe automatisch uw gebruikersmigratie 30 dagen vooruit plannen en met de Admins van het Product van Marketo communiceren om de gebruikersmigratie te beheren.

Marketo-productbeheerders zullen:

* Ontvang een e-mail met de geplande begindatum van de migratie van gebruikers 30 dagen vooruit.

* Verkrijg toegang tot de Marketo Migration Console, die in het gebied van Admin van Marketo wordt gevestigd, waar zij de de migratiedatum van een abonnement kunnen veranderen.

>[!NOTE]
>
>Vanwege de complexiteit van de migratie zijn datumwijzigingen beperkt tot maximaal 30 dagen na de geplande datum. Stuur een e-mail naar marketocares@adobe.com als u een latere datum nodig hebt.

* Zie een banner in Mijn Marketo die een afrekening naar de Begindatum van de Migratie van de Gebruiker toont.

* Ontvang een herinnering per e-mail de dag vóór de Begindatum van de Migratie van de Gebruiker.

### Gebruikers voorbereiden voor migratiedag {#prepare-users-for-migration-day}

Als Marketo-productbeheerder wordt u aangeraden ervoor te zorgen dat alle gebruikers op de migratiedag zijn voorbereid.

* Controleer de status van e-mailverificatie voor alle gebruikers in het gebied Marketo Admin. Moedig gebruikers die hun e-mailadres niet hebben geverifieerd aan om dit te doen en help gebruikers eventuele problemen op te lossen bij het voltooien van het verificatieproces.

* Alle gebruikers voorbereiden op de volgende migratie naar Adobe-identiteit.

>[!NOTE]
>
>Terwijl gebruikers migreren, ontvangen ze een e-mail van Adobe waarin ze op de hoogte worden gesteld van de wijziging in de manier waarop ze zich aanmelden bij Marketo. Gebruikers worden uitgenodigd een uitnodiging voor aanmelding met Adobe Identity voor het eerst te accepteren door u aan te melden met een bestaande Adobe ID of door een nieuwe uitnodiging met hetzelfde e-mailadres in te stellen.

### Wat verwacht u op de migratiedag {#what-to-expect-on-migration-day}

De migratie van gebruikers begint om middernacht van de tijdzone die is ingesteld in het Marketo-abonnement.

**Adobe migreert automatisch eerst Marketo Admins**. Wanneer Marketo Admins naar Adobe Identity wordt gemigreerd, krijgen zij de rol van Admin van het Product van de Adobe binnen de toepassing van Marketo samen met om het even welke andere rollen toegewezen zij eerder hadden.

**Als uw Marketo-abonnement minder dan 75 gebruikers heeft**, migreert Adobe automatisch de rest van uw gebruikers. Deze workflow is bedoeld om het hoogste niveau van automatisering te bieden om overhead voor Adobe Marketo-gebruikers tot een minimum te beperken. Er is geen actie van uw kant vereist om de migratie uit te voeren.

**Als uw Marketo-abonnement meer dan 75 gebruikers heeft** Marketo Product Admins krijgt toegang tot het gebied Self-Service User Migration van de Marketo Migration Console in het Marketo Admin Area. Voor degenen die meer controle nodig hebben tijdens het migratieproces van gebruikers, kunnen Marketo-productbeheerders beginnen met het selecteren van gebruikers voor migratie in batches of in één keer. Als gebruikers zijn geselecteerd, hebben beheerders de optie &quot;Nu migreren&quot; of &quot;Migratie plannen&quot; voor een latere datum. Hierdoor hebben beheerders de ultieme flexibiliteit en controle over welke gebruikers worden gemigreerd wanneer.

>[!NOTE]
>
>Tijdens de migratie van gebruikers zal de toegang tot het product niet verloren gaan. Als een gebruiker tijdens de tijd het programma wordt geopend hun gebruiker wordt gemigreerd, zal de gebruiker worden geregistreerd uit en ertoe aangezet om binnen notulen terug te verbinden gebruikend Identiteit Adobe nadat de migratie volledig is.

Terwijl gebruikers worden gemigreerd, ontvangen ze een e-mail van Adobe waarin ze op de hoogte worden gesteld van de wijziging in de manier waarop ze zich aanmelden bij Marketo. Gebruikers worden uitgenodigd een uitnodiging voor aanmelding met Adobe Identity voor het eerst te accepteren, hetzij door u aan te melden met een bestaande Adobe ID, hetzij door een nieuwe Adobe ID in te stellen met hetzelfde e-mailadres. Meer informatie vindt u in onze [Aanmelden door gebruiker met Adobe](/help/marketo/product-docs/administration/marketo-with-adobe-identity/user-sign-in-with-adobe-id.md) artikel.

## Migratie van gebruiker voltooid {#user-migration-complete}

Adobe zal alle Systeembeheerders en productbeheerders via e-mail op de hoogte stellen zodra alle beheerders en gebruikers zijn gemigreerd. Op dit moment zullen alle Marketo-gebruikers voor dat abonnement zich aanmelden bij Marketo met Adobe Identity en zullen productbeheerders gebruikers alleen in Adobe Admin Console beheren.

## Ondersteuning {#get-support}

Voor extra ondersteuning met betrekking tot uw abonnement of gebruikersmigratie, stuurt u een e-mail naar marketocares@adobe.com.
