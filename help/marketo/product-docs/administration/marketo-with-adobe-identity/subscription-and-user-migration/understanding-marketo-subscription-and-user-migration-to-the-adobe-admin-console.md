---
description: Een goed begrip van Marketo-abonnement en gebruikersmigratie naar de Adobe Admin Console - Marketo Docs - Productdocumentatie
title: Marketo-abonnement en gebruikersmigratie naar de Adobe Admin Console begrijpen
exl-id: 91e7b56b-2563-4986-a55c-f9760ea88b05
feature: Marketo with Adobe Identity
source-git-commit: df7b29f9b7bb31b2762dd6a6d48eb237f4ccb9f0
workflow-type: tm+mt
source-wordcount: '1573'
ht-degree: 0%

---

# Marketo-abonnement en gebruikersmigratie naar de Adobe Admin Console begrijpen {#understanding-marketo-subscription-and-user-migration-to-the-adobe-admin-console}

Adobe verbetert de manier waarop u uw Adobe Marketo Engage-abonnementen en -gebruikers beheert, waardoor u en uw organisatie productiever worden. Als onderdeel van deze wijziging migreert Adobe uw abonnementen op Marketo&#39;s Engage en gebruikers naar de Adobe Admin Console. Dit is een noodzakelijke migratie en heeft geen invloed op een marketingworkflow, inhoud, integratie of middelen.

>[!TIP]
>
>Leer hoe u Adobe Admin Console kunt gebruiken om uw rechten van de Adobe over uw volledige organisatie met de [ Gids van de Onderneming en van Admin van Teams ](https://helpx.adobe.com/nl/enterprise/admin-guide.html) te beheren {target="_blank"}.

## Wat verandert er? {#what-is-changing}

Tijdens de migratie gaan uw abonnement en gebruikersbeheer van de Marketo-toepassing naar de Adobe Admin Console.

* **Admins van het Systeem zal abonnementen op Adobe Admin Console** beheren. Bekijk al uw producten van de Adobe in één console.

* **Admins van het Product zal gebruikers en hun toegang op Adobe Admin Console** beheren. Voeg gebruikers toe en verwijder gebruikers voor al uw Adobe abonnementen. De Adobe Admin Console biedt geen ondersteuning voor het verlopen van gebruikerstoegang. Gebruikers die toegang tot Marketo&#39;s Engage hebben die volgens de planning na de migratie verlopen, zullen nog steeds worden gemigreerd en niet-vervallende toegang krijgen. Na de migratie moeten ze handmatig worden verwijderd op (of voor) de gewenste vervaldatum.

* **de Gebruikers zullen binnen met de Identiteit van de Adobe** ondertekenen. Adobe migreert bestaande gebruikers naar de Adobe Admin Console. Gebruikers zullen zich aanmelden bij hun Marketo-abonnementen met hun nieuwe Adobe Identity - een Adobe ID- of Adobe Federated ID (SSO).

* **URLs zal verschillend na migratie** kijken. Na de migratie gaat Marketo Engage van experience.adobe.com naar Adobe Experience Cloud. U zult met uw team van IT moeten werken om alle vermelde domeinen van de Adobe [ bij de bovenkant van dit artikel ](/help/marketo/getting-started/initial-setup/configure-protocols-for-marketo.md){target="_blank"} te lijsten van gewenste personen om verstoring aan de toegang van het Marketo Engage te verhinderen.

De id-nummers van uw elementen blijven ongewijzigd. En vorige verbindingen en referenties aan de activa van het Marketo Engage op het engage-xx.marketo.com domein _zullen_ blijven functioneren. U moet zich echter eerst aanmelden bij de instantie Marketo Engage voor de URL waarnaar u navigeert. Als u bijvoorbeeld naar een bladwijzer voor een slimme campagne wilt navigeren, bijvoorbeeld met Munchkin ID 123-ABC-456, moet u zich eerst aanmelden bij de instantie Marketo Engage met Munchkin ID 123-ABC-456.

## Wat verandert er niet? {#what-is-not-changing}

* **Er is geen verandering in hoe u alle andere functionaliteit** binnen de toepassing van het Marketo Engage zelf, met inbegrip van beheer van eigenschappen, gebruikersrollen, werkruimten, functionaliteit, en gedrag beheert.

## Tijdlijn migratiepad {#migration-journey-timeline}

Adobe migreert eerst uw abonnement(en) op het Marketo Engage naar de Adobe Admin Console en migreert vervolgens alle bestaande gebruikers met geverifieerde e-mailadressen. Als u een Systeembeheerder of Marketo-productbeheerder bent, ontvangt u e-mails met instructies voor de migratie. Hier volgt een tijdlijn van wat u kunt verwachten:

![](assets/understanding-marketo-subscription-and-user-migration-1.png)

### Abonnementsmigratie voltooid {#subscription-migration-complete}

Systeembeheerders ontvangen een e-mail wanneer de migratie naar Adobe Admin Console is voltooid.

Systeembeheerders moeten mogelijk een aantal vereiste stappen uitvoeren voordat de migratie van gebruikers de gevolgen voor Marketo-gebruikers minimaliseert:

* Als uw Marketo-gebruikers zich momenteel aanmelden bij SSO, moet u SSO instellen op de Adobe Admin Console zodat uw gebruikers zich kunnen blijven aanmelden bij SSO. Als uw Marketo-gebruikers momenteel geen SSO gebruiken, maar u wilt deze instellen op Adobe Admin Console, kunt u dit op dit moment doen tijdens de migratiereis.

* Als u al andere producten van de Adobe in uw Adobe Admin Console beheert, kan de Adobe uw toestemming vragen om gebruikers automatisch aan uw bestaande console te migreren. Klik op de knop Aan de slag in het e-mailbericht om naar de toestemmingspagina te navigeren.

Er is momenteel geen wijziging in het gebruikersbeheer. Hoewel Marketo-producten in de Admin Console worden weergegeven, blijven Marketo Admins gebruikers beheren in het gebied Marketo Admin en blijven gebruikers zich aanmelden met hun Marketo Identity totdat hun gebruikersmigratie is voltooid. Gedurende deze tijd kunnen Marketo producten niet in de Admin Console worden toegediend totdat de migratie van de gebruiker begint. Dit omvat de instantie van de Dynamic Chat verbonden aan het abonnement.

>[!NOTE]
>
>Als u momenteel geen SSO gebruikt maar aan het uitvoeren van het overweegt, adviseren wij dit te doen alvorens de gebruikersmigratie voorkomt. Als u Enig Sign wilt uitvoeren en uw abonnement aan de Identiteit van de Adobe zonder SSO is geregistreerd die in de Adobe wordt uitgevoerd die of wordt uitgevoerd, gelieve een kaartje voor te leggen aan [ Steun van Marketo ](https://nation.marketo.com/) {target="_blank"} en het onderwerp te specificeren zoals &quot;Marketo op Admin Console, die SSO uitvoert.&quot;

### Gebruikersmigratie plannen {#schedule-user-migration}

Nadat uw systeembeheerder de voorwaarden voltooit die in de vorige sectie worden beschreven, zal de Adobe automatisch uw gebruikersmigratie 30 dagen vooruit plannen en met de Admins van het Product van Marketo communiceren om de gebruikersmigratie te beheren.

Marketo-productbeheerders zullen:

* Ontvang een e-mail met de geplande begindatum van de migratie van gebruikers 30 dagen vooruit.

* Verkrijg toegang tot de Marketo Migration Console, die in het gebied van Admin van Marketo wordt gevestigd, waar zij de de migratiedatum van een abonnement kunnen veranderen.

>[!NOTE]
>
>Vanwege de complexiteit van de migratie zijn datumwijzigingen beperkt tot maximaal 30 dagen na de geplande datum. Stuur een e-mail naar `marketocares@marketo.com` als u een latere datum nodig hebt.

* Zie een banner in Mijn Marketo die een afrekening naar de Begindatum van de Migratie van de Gebruiker toont.

* Ontvang een herinnering per e-mail de dag vóór de Begindatum van de Migratie van de Gebruiker.

### Gebruikers voorbereiden voor migratiedag {#prepare-users-for-migration-day}

Als Marketo-productbeheerder wordt u aangeraden ervoor te zorgen dat alle gebruikers op de migratiedag zijn voorbereid.

* Controle [ e-mailverificatie ](/help/marketo/product-docs/administration/users-and-roles/email-verification.md){target="_blank"} status voor alle gebruikers in het gebied van Admin van Marketo. Moedig gebruikers die hun e-mailadres niet hebben geverifieerd aan om dit te doen en help gebruikers eventuele problemen op te lossen bij het voltooien van het verificatieproces.

* Zoek in uw e-mailpostvak naar &#39;vergrendelde&#39; gebruikersmeldingen. Vraag gebruikers die zijn vergrendeld, hun wachtwoord opnieuw in te stellen om de toegang tot het Marketo Engage voor de migratiedag te herstellen.

* Alle gebruikers voorbereiden op de volgende migratie naar Adobe-id.

>[!NOTE]
>
>Terwijl gebruikers migreren, ontvangen ze een e-mail van de Adobe waarin ze op de hoogte worden gesteld van de wijziging in de manier waarop ze zich aanmelden bij Marketo. Gebruikers worden uitgenodigd een uitnodiging om zich voor het eerst aan te melden met Adobe Identity te accepteren, door zich aan te melden met een bestaande Adobe ID of door een nieuwe uitnodiging in te stellen met hetzelfde e-mailadres.

>[!IMPORTANT]
>
>Als een gebruiker van het Marketo Engage zijn e-mailadres niet verifieert of op het moment van de gebruikersmigratie is vergrendeld, wordt hij of zij niet naar een Adobe ID gemigreerd en verliest hij of zij de toegang tot het Marketo-abonnement nadat de migratie voor het abonnement is voltooid. Om toegang te krijgen, moet een Marketo-productbeheerder deze als nieuwe gebruiker toevoegen.

### Wat verwacht u op de migratiedag {#what-to-expect-on-migration-day}

Alle Marketo-abonnementen met een Amerikaanse tijdzone worden gemigreerd vanaf middernacht, Pacific Standard Time, van de startdatum van de migratie. De migratie van de gebruiker voor alle andere abonnementen zal om middernacht van gespecificeerde timezone van het abonnement beginnen.

**de Adobe zal automatisch Marketo Admins eerst migreren**. Wanneer Marketo Admins naar Adobe Identity wordt gemigreerd, krijgen zij de rol van Admin van het Product van de Adobe binnen de toepassing van Marketo samen met om het even welke andere rollen toegewezen zij eerder hadden.

**als uw Marketo abonnement minder dan 75 gebruikers heeft en geen SSO in Marketo en/of uw Adobe Org** heeft, zal de Adobe automatisch de rest van uw gebruikers migreren. Deze workflow is bedoeld om het hoogste niveau van automatisering te bieden om overhead voor Adobe Marketo-gebruikers tot een minimum te beperken. Er is geen actie van uw kant vereist om de migratie uit te voeren.

**als uw Marketo abonnement meer dan 75 gebruikers heeft of SSO in Marketo en/of uw Adobe Org** heeft, zullen de Admins van het Product van Marketo toegang tot het gebied van de Migratie van de Gebruiker van de Zelfbediening van de Console van de Migratie van Marketo krijgen, die in het Gebied van Admin van Marketo wordt gevestigd. Voor degenen die meer controle nodig hebben tijdens het migratieproces van gebruikers, kunnen Marketo-productbeheerders beginnen met het selecteren van gebruikers voor migratie in batches of in één keer. Als gebruikers zijn geselecteerd, hebben beheerders de optie &quot;Nu migreren&quot; of &quot;Migratie plannen&quot; voor een latere datum. Hierdoor hebben beheerders de ultieme flexibiliteit en controle over welke gebruikers worden gemigreerd wanneer.

>[!NOTE]
>
>Tijdens de migratie van gebruikers zal de toegang tot het product niet verloren gaan. Als een gebruiker tijdens de tijd het programma wordt geopend hun gebruiker wordt gemigreerd, zal de gebruiker worden geregistreerd uit en ertoe aangezet om binnen notulen terug te verbinden gebruikend de Identiteit van de Adobe nadat de migratie volledig is. De gebruiker moet de uitnodiging accepteren door op de koppeling te klikken in de e-mail met bevoegdheden die wordt verzonden aan het einde van een geslaagde gebruikersmigratie.

Terwijl gebruikers worden gemigreerd, ontvangen ze een e-mail van de Adobe waarin ze op de hoogte worden gesteld van de wijziging in de manier waarop ze zich aanmelden bij Marketo. De gebruikers **moeten** een uitnodiging goedkeuren om binnen het gebruiken van de Identiteit van de Adobe voor het eerst te ondertekenen, of door binnen met bestaande Adobe ID te ondertekenen of door nieuwe Adobe ID te vestigen die het zelfde e-mailadres gebruikt

De meer informatie kan in [ Migrerend aan de Identiteit van de Adobe ](/help/marketo/product-docs/administration/marketo-with-adobe-identity/subscription-and-user-migration/migrating-to-adobe-identity.md){target="_blank"}, [ Teken-binnen van de Gebruiker met Adobe ](/help/marketo/product-docs/administration/marketo-with-adobe-identity/user-sign-in-with-adobe-id.md){target="_blank"}, en [ Veelgestelde vragen van Identity Management van de Adobe ](/help/marketo/product-docs/administration/marketo-with-adobe-identity/faq.md){target="_blank"} worden gevonden.

## Migratie van gebruiker voltooid {#user-migration-complete}

Adobe zal alle systeembeheerders en productbeheerders via e-mail op de hoogte stellen zodra alle beheerders en gebruikers zijn gemigreerd. Op dit moment zullen alle Marketo-gebruikers voor dat abonnement zich aanmelden bij Marketo met Adobe-id en zullen productbeheerders gebruikers alleen in Adobe Admin Console beheren.

## Ondersteuning {#get-support}

E-mail `marketocares@marketo.com` voor extra ondersteuning met betrekking tot uw abonnement of gebruikersmigratie.

>[!MORELIKETHIS]
>
>* [ migrerend aan het Overzicht van de Identiteit van de Adobe ](/help/marketo/product-docs/administration/marketo-with-adobe-identity/subscription-and-user-migration/migrating-to-adobe-identity.md){target="_blank"}
>* [ het Teken-binnen van de Gebruiker met Adobe ](/help/marketo/product-docs/administration/marketo-with-adobe-identity/user-sign-in-with-adobe-id.md){target="_blank"}
>* [ Adobe Identity Management Veelgestelde vragen ](/help/marketo/product-docs/administration/marketo-with-adobe-identity/faq.md){target="_blank"}
>* [ migrerend aan de Leerprogramma van Identity Management van de Adobe ](https://experienceleague.adobe.com/en/docs/marketo-learn/tutorials/fundamentals/migrating-to-adobe-identity-management) {target="_blank"}
