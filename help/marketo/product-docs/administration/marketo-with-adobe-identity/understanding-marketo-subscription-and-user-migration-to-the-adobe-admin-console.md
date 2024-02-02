---
description: Een goed begrip van Marketo-abonnement en gebruikersmigratie naar de Adobe Admin Console - Marketo Docs - Productdocumentatie
title: Marketo-abonnement en gebruikersmigratie naar de Adobe Admin Console begrijpen
exl-id: 91e7b56b-2563-4986-a55c-f9760ea88b05
feature: Marketo with Adobe Identity
source-git-commit: c5d5fd490fe2800dc7a34d02c73d728e115646a0
workflow-type: tm+mt
source-wordcount: '1301'
ht-degree: 0%

---

# Marketo-abonnement en gebruikersmigratie naar de Adobe Admin Console begrijpen {#understanding-marketo-subscription-and-user-migration-to-the-adobe-admin-console}

Adobe verbetert de manier waarop u uw Adobe Marketo Engage-abonnementen en -gebruikers beheert, waardoor u en uw organisatie productiever worden. Als onderdeel van deze wijziging migreert Adobe uw abonnementen op Marketo&#39;s Engage en gebruikers naar de Adobe Admin Console. Dit is een noodzakelijke migratie en heeft geen invloed op een marketingworkflow, inhoud, integratie of middelen.

Leer hoe u de Adobe Admin Console kunt gebruiken om uw rechten voor Adoben te beheren in uw hele organisatie met de [Beheerdershandleiding voor ondernemingen en teams](https://helpx.adobe.com/enterprise/admin-guide.html){target="_blank"}.

## Wat verandert er? {#what-is-changing}

Tijdens de migratie gaan uw abonnement en gebruikersbeheer van de Marketo-toepassing naar de Adobe Admin Console.

* **Systeembeheerders beheren abonnementen op Adobe Admin Console**. Bekijk al uw producten van de Adobe in één console.

* **Productbeheerders beheren gebruikers en hun toegang op Adobe Admin Console**. Voeg gebruikers toe en verwijder gebruikers voor al uw Adobe abonnementen.

* **Gebruikers zullen zich aanmelden met Adobe-id**. Adobe migreert bestaande gebruikers naar de Adobe Admin Console. Gebruikers zullen zich aanmelden bij hun Marketo-abonnementen met hun nieuwe Adobe Identity - een Adobe ID- of Adobe Federated ID (SSO).

* **Er is geen wijziging in de manier waarop u alle andere functies beheert** binnen de toepassing van het Marketo Engage zelf, met inbegrip van beheer van eigenschappen, gebruikersrollen, werkruimten, functionaliteit, en gedrag.

## Tijdlijn migratiepad {#migration-journey-timeline}

Adobe migreert eerst uw abonnement(en) op het Marketo Engage naar de Adobe Admin Console en migreert vervolgens alle bestaande gebruikers met geverifieerde e-mailadressen. Als u een Systeembeheerder of Marketo-productbeheerder bent, ontvangt u e-mails met instructies voor de migratie. Hier volgt een tijdlijn van wat u kunt verwachten:

### Abonnementsmigratie voltooid {#subscription-migration-complete}

Systeembeheerders ontvangen een e-mail wanneer de migratie naar Adobe Admin Console is voltooid.

Systeembeheerders moeten mogelijk een aantal vereiste stappen uitvoeren voordat de migratie van gebruikers de gevolgen voor Marketo-gebruikers minimaliseert:

* Als uw Marketo-gebruikers zich momenteel aanmelden bij SSO, moet u SSO instellen op de Adobe Admin Console zodat uw gebruikers zich kunnen blijven aanmelden bij SSO. Als uw Marketo-gebruikers momenteel geen SSO gebruiken, maar u wilt deze instellen op Adobe Admin Console, kunt u dit op dit moment doen tijdens de migratiereis.

* Als u al andere producten van de Adobe in uw Adobe Admin Console beheert, kan de Adobe uw toestemming vragen om gebruikers automatisch aan uw bestaande console te migreren. Klik op de knop Aan de slag in het e-mailbericht om naar de toestemmingspagina te navigeren.

Er is momenteel geen wijziging in het gebruikersbeheer. Hoewel Marketo-producten in de Admin Console worden weergegeven, blijven Marketo Admins gebruikers beheren in het gebied Marketo Admin en blijven gebruikers zich aanmelden met hun Marketo Identity totdat hun gebruikersmigratie is voltooid. Gedurende deze tijd kunnen Marketo producten niet in de Admin Console worden toegediend totdat de migratie van de gebruiker begint. Dit omvat de instantie van de Dynamic Chat verbonden aan het abonnement.

>[!NOTE]
>
>Als u momenteel geen SSO gebruikt maar aan het uitvoeren van het overweegt, adviseren wij dit te doen alvorens de gebruikersmigratie voorkomt. Als u Single Sign On wilt implementeren en uw abonnement is aangemeld bij Adobe Identity zonder SSO geïmplementeerd in de Adobe Org, dient u een ticket in bij [Marketo-ondersteuning](https://nation.marketo.com/){target="_blank"} en specificeer het onderwerp als &quot;Marketo op Admin Console, die SSO uitvoeren.&quot;

### Gebruikersmigratie plannen {#schedule-user-migration}

Nadat uw systeembeheerder de voorwaarden voltooit die in de vorige sectie worden beschreven, zal de Adobe automatisch uw gebruikersmigratie 30 dagen vooruit plannen en met de Admins van het Product van Marketo communiceren om de gebruikersmigratie te beheren.

Marketo-productbeheerders zullen:

* Ontvang een e-mail met de geplande begindatum van de migratie van gebruikers 30 dagen vooruit.

* Verkrijg toegang tot de Marketo Migration Console, die in het gebied van Admin van Marketo wordt gevestigd, waar zij de de migratiedatum van een abonnement kunnen veranderen.

>[!NOTE]
>
>Vanwege de complexiteit van de migratie zijn datumwijzigingen beperkt tot maximaal 30 dagen na de geplande datum. Een e-mail verzenden naar `marketocares@marketo.com` als u een latere datum nodig hebt.

* Zie een banner in Mijn Marketo die een afrekening naar de Begindatum van de Migratie van de Gebruiker toont.

* Ontvang een herinnering per e-mail de dag vóór de Begindatum van de Migratie van de Gebruiker.

### Gebruikers voorbereiden voor migratiedag {#prepare-users-for-migration-day}

Als Marketo-productbeheerder wordt u aangeraden ervoor te zorgen dat alle gebruikers op de migratiedag zijn voorbereid.

* Controleren [e-mailverificatie](/help/marketo/product-docs/administration/users-and-roles/email-verification.md){target="_blank"} status voor alle gebruikers in het gebied Marketo Admin. Moedig gebruikers die hun e-mailadres niet hebben geverifieerd aan om dit te doen en help gebruikers eventuele problemen op te lossen bij het voltooien van het verificatieproces.

* Alle gebruikers voorbereiden op de volgende migratie naar Adobe-id.

>[!NOTE]
>
>Terwijl gebruikers migreren, ontvangen ze een e-mail van de Adobe waarin ze op de hoogte worden gesteld van de wijziging in de manier waarop ze zich aanmelden bij Marketo. Gebruikers worden uitgenodigd een uitnodiging om zich voor het eerst aan te melden met Adobe Identity te accepteren, door zich aan te melden met een bestaande Adobe ID of door een nieuwe uitnodiging in te stellen met hetzelfde e-mailadres.

>[!IMPORTANT]
>
>Als een gebruiker van het Marketo Engage zijn e-mailadres niet verifieert, wordt hij of zij niet naar een Adobe ID gemigreerd en verliest hij of zij de toegang tot het Marketo-abonnement nadat de migratie voor het abonnement is voltooid. Om toegang te krijgen, moet een Marketo-productbeheerder deze als nieuwe gebruiker toevoegen.

### Wat verwacht u op de migratiedag {#what-to-expect-on-migration-day}

Alle Marketo-abonnementen met een Amerikaanse tijdzone worden gemigreerd vanaf middernacht, Pacific Standard Time, van de startdatum van de migratie. De migratie van de gebruiker voor alle andere abonnementen zal om middernacht van gespecificeerde timezone van het abonnement beginnen.

**Adobe migreert automatisch eerst Marketo Admins**. Wanneer Marketo Admins naar Adobe Identity wordt gemigreerd, krijgen zij de rol van Admin van het Product van de Adobe binnen de toepassing van Marketo samen met om het even welke andere rollen toegewezen zij eerder hadden.

**Als uw Marketo-abonnement minder dan 75 gebruikers heeft**, zal de Adobe automatisch de rest van uw gebruikers migreren. Deze workflow is bedoeld om het hoogste niveau van automatisering te bieden om overhead voor Adobe Marketo-gebruikers tot een minimum te beperken. Er is geen actie van uw kant vereist om de migratie uit te voeren.

**Als uw Marketo-abonnement meer dan 75 gebruikers heeft** Marketo Product Admins krijgt toegang tot het gebied Self-Service User Migration van de Marketo Migration Console in het Marketo Admin Area. Voor degenen die meer controle nodig hebben tijdens het migratieproces van gebruikers, kunnen Marketo-productbeheerders beginnen met het selecteren van gebruikers voor migratie in batches of in één keer. Als gebruikers zijn geselecteerd, hebben beheerders de optie &quot;Nu migreren&quot; of &quot;Migratie plannen&quot; voor een latere datum. Hierdoor hebben beheerders de ultieme flexibiliteit en controle over welke gebruikers worden gemigreerd wanneer.

>[!NOTE]
>
>Tijdens de migratie van gebruikers zal de toegang tot het product niet verloren gaan. Als een gebruiker tijdens de tijd het programma wordt geopend hun gebruiker wordt gemigreerd, zal de gebruiker worden geregistreerd uit en ertoe aangezet om binnen notulen terug te verbinden gebruikend de Identiteit van de Adobe nadat de migratie volledig is.

Terwijl gebruikers worden gemigreerd, ontvangen ze een e-mail van de Adobe waarin ze op de hoogte worden gesteld van de wijziging in de manier waarop ze zich aanmelden bij Marketo. Gebruikers worden uitgenodigd een uitnodiging om zich voor het eerst aan te melden met Adobe Identity te accepteren, door zich aan te melden met een bestaande Adobe ID of door een nieuwe Adobe ID in te stellen met hetzelfde e-mailadres.

Meer informatie vindt u in [Migreren naar Adobe-id](/help/marketo/product-docs/administration/marketo-with-adobe-identity/subscription-and-user-migration/migrating-to-adobe-identity.md){target="_blank"}, [User Sign-in with Adobe](/help/marketo/product-docs/administration/marketo-with-adobe-identity/user-sign-in-with-adobe-id.md){target="_blank"}, and [Adobe Identity Management FAQ](/help/marketo/product-docs/administration/marketo-with-adobe-identity/faq.md){target="_blank"}.

## Migratie van gebruiker voltooid {#user-migration-complete}

Adobe zal alle systeembeheerders en productbeheerders via e-mail op de hoogte stellen zodra alle beheerders en gebruikers zijn gemigreerd. Op dit moment zullen alle Marketo-gebruikers voor dat abonnement zich aanmelden bij Marketo met Adobe-id en zullen productbeheerders gebruikers alleen in Adobe Admin Console beheren.

## Ondersteuning {#get-support}

Voor extra ondersteuning met betrekking tot uw abonnement of gebruikersmigratie, kunt u een e-mail `marketocares@marketo.com`.

>[!MORELIKETHIS]
>
>* [Migreren naar Adobe-id](/help/marketo/product-docs/administration/marketo-with-adobe-identity/subscription-and-user-migration/migrating-to-adobe-identity.md){target="_blank"}
>* [Aanmelden door gebruiker met Adobe](/help/marketo/product-docs/administration/marketo-with-adobe-identity/user-sign-in-with-adobe-id.md){target="_blank"}
>* [Adobe Identity Management - Veelgestelde vragen](/help/marketo/product-docs/administration/marketo-with-adobe-identity/faq.md){target="_blank"}
