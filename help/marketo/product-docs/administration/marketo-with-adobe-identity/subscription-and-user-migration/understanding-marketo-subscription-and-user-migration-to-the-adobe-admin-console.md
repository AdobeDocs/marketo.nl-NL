---
description: Een goed begrip van Marketo-abonnement en gebruikersmigratie naar de Adobe Admin Console - Marketo Docs - Productdocumentatie
title: Marketo-abonnement en gebruikersmigratie naar de Adobe Admin Console begrijpen
exl-id: 91e7b56b-2563-4986-a55c-f9760ea88b05
feature: Marketo with Adobe Identity
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '1571'
ht-degree: 0%

---

# Marketo-abonnement en gebruikersmigratie naar de Adobe Admin Console begrijpen {#understanding-marketo-subscription-and-user-migration-to-the-adobe-admin-console}

Adobe verbetert de manier waarop u uw Adobe Marketo Engage-abonnementen en -gebruikers beheert, waardoor u en uw organisatie productiever worden. Als onderdeel van deze wijziging migreert Adobe uw Marketo Engage-abonnementen en -gebruikers naar de Adobe Admin Console. Dit is een noodzakelijke migratie en heeft geen invloed op een marketingworkflow, inhoud, integratie of middelen.

>[!TIP]
>
>Leer hoe u Adobe Admin Console kunt gebruiken om uw rechten van Adobe over uw volledige organisatie met de [ Gids van de Onderneming en van Admin van Teams te beheren ](https://helpx.adobe.com/nl/enterprise/admin-guide.html){target="_blank"}.

## Wat verandert er? {#what-is-changing}

Tijdens de migratie gaan uw abonnement en gebruikersbeheer van de Marketo-toepassing naar de Adobe Admin Console.

* **Admins van het Systeem zal abonnementen op Adobe Admin Console** beheren. Bekijk al je Adobe producten in één console.

* **Admins van het Product zal gebruikers en hun toegang op Adobe Admin Console** beheren. Voeg gebruikers voor al je Adobe-abonnementen toe en verwijder ze. De Adobe Admin Console biedt geen ondersteuning voor het verlopen van gebruikerstoegang. Gebruikers met Marketo Engage-toegang die volgens de planning na de migratie verloopt, worden nog steeds gemigreerd en krijgen niet-vervallende toegang. Na de migratie moeten ze handmatig worden verwijderd op (of voor) de gewenste vervaldatum.

* **de Gebruikers zullen binnen met de Identiteit van Adobe** ondertekenen. Adobe migreert bestaande gebruikers naar de Adobe Admin Console. Gebruikers zullen zich aanmelden bij hun Marketo-abonnementen met hun nieuwe Adobe Identity - een Adobe ID of Adobe Federated ID (SSO).

* **URLs zal verschillend na migratie** kijken. Marketo Engage gaat van experience.adobe.com naar Adobe Experience Cloud en de URL&#39;s hebben de volgende notatie: `https://experience.adobe.com/#/@tenantID/so:XXX-XXX-XXX/marketo-engage/classic/` (de XXX&#39;s geven de Munchkin-id aan en @huurderID is afkomstig van uw Adobe-org). U zult met uw team van IT moeten werken om alle vermelde domeinen van Adobe [ bij de bovenkant van dit artikel ](/help/marketo/getting-started/initial-setup/configure-protocols-for-marketo.md){target="_blank"} te lijsten van gewenste personen om verstoring aan de toegang van Marketo Engage te verhinderen.

De id-nummers van uw elementen blijven ongewijzigd. En vorige verbindingen en referenties aan de activa van Marketo Engage op het engage-xx.marketo.com domein __ zullen blijven functioneren. U moet zich echter eerst aanmelden bij de Marketo Engage-instantie voor de URL waarnaar u navigeert. Als u bijvoorbeeld naar een bladwijzer voor een slimme campagne wilt navigeren, bijvoorbeeld met Munchkin ID 123-ABC-456, moet u zich eerst aanmelden bij de Marketo Engage-instantie met Munchkin ID 123-ABC-456.

Deze omleidingsfunctie kan door toekomstige ontwikkelingswerkzaamheden worden verbroken, maar niet gepland. Om onverwachte onderbrekingen te voorkomen, wordt aangeraden bladwijzers zo snel mogelijk bij te werken.

## Wat verandert er niet? {#what-is-not-changing}

* **Er is geen verandering in hoe u alle andere functionaliteit** binnen de toepassing van Marketo Engage zelf, met inbegrip van beheer van eigenschappen, gebruikersrollen, werkruimten, functionaliteit, en gedrag beheert. Het lokale (API-slechts) gebruikersbeheer blijft op het _Gebruikers en Rollen_ lusje in het gebied van Admin van Marketo.

## Tijdlijn migratiepad {#migration-journey-timeline}

Adobe migreert eerst uw Marketo Engage-abonnement(en) naar de Adobe Admin Console en migreert vervolgens alle bestaande gebruikers met geverifieerde e-mailadressen. Als u een Systeembeheerder of Marketo-productbeheerder bent, ontvangt u e-mails met instructies voor de migratie. Hier volgt een tijdlijn van wat u kunt verwachten:

![](assets/understanding-marketo-subscription-and-user-migration-1.png){width="800" zoomable="yes"}

### Abonnementsmigratie voltooid {#subscription-migration-complete}

Systeembeheerders ontvangen een e-mail wanneer de migratie naar Adobe Admin Console is voltooid.

Systeembeheerders moeten mogelijk een aantal vereiste stappen uitvoeren voordat de migratie van gebruikers de gevolgen voor Marketo-gebruikers minimaliseert:

* Als uw Marketo-gebruikers zich momenteel aanmelden bij SSO, moet u SSO instellen op de Adobe Admin Console zodat uw gebruikers zich kunnen blijven aanmelden bij SSO. Als uw Marketo-gebruikers momenteel geen SSO gebruiken, maar u wilt deze instellen op Adobe Admin Console, kunt u dit op dit moment doen tijdens de migratiereis.

* Als u al andere Adobe-producten beheert in uw Adobe Admin Console, kan Adobe uw toestemming vragen om gebruikers automatisch te migreren naar uw bestaande console. Klik op de knop Aan de slag in het e-mailbericht om naar de toestemmingspagina te navigeren.

Er is momenteel geen wijziging in het gebruikersbeheer. Hoewel Marketo-producten in de Admin Console worden weergegeven, blijven Marketo Admins gebruikers beheren in het gebied Marketo Admin en blijven gebruikers zich aanmelden met hun Marketo Identity totdat hun gebruikersmigratie is voltooid. Gedurende deze periode kunnen Marketo producten niet in Admin Console worden toegediend totdat de migratie van gebruikers begint. Dit geldt ook voor het Dynamic Chat-exemplaar dat aan het abonnement is gekoppeld.

>[!NOTE]
>
>Als u momenteel geen SSO gebruikt maar aan het uitvoeren van het overweegt, adviseren wij dit te doen alvorens de gebruikersmigratie voorkomt. Als u Single Sign On wilt uitvoeren en uw abonnement aan de Identiteit van Adobe zonder SSO die in Adobe Org wordt uitgevoerd, gelieve een kaartje aan [ Steun van Marketo ](https://nation.marketo.com/){target="_blank"} voor te leggen en het onderwerp te specificeren zoals &quot;Marketo op Admin Console, die SSO uitvoert.&quot;

### Gebruikersmigratie plannen {#schedule-user-migration}

Nadat uw systeembeheerder de voorwaarden voltooit die in de vorige sectie zijn beschreven, zal Adobe automatisch de migratie van uw gebruiker 30 dagen vooraf plannen en met de Admins van het Product van Marketo communiceren om de gebruikersmigratie te beheren.

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

* Zoek in uw e-mailpostvak naar &#39;vergrendelde&#39; gebruikersmeldingen. Vraag gebruikers die zijn vergrendeld, het wachtwoord opnieuw in te stellen om de toegang tot Marketo Engage voor de migratiedag te herstellen.

* Alle gebruikers voorbereiden op de komende migratie naar Adobe Identity.

>[!IMPORTANT]
>
>Als een Marketo Engage-gebruiker zijn e-mailadres niet verifieert of op het moment van de migratie van de gebruiker is vergrendeld, wordt hij of zij niet naar een Adobe ID gemigreerd en verliest hij of zij de toegang tot het Marketo-abonnement nadat de migratie voor het abonnement is voltooid. Om toegang te krijgen, moet een Marketo-productbeheerder deze als nieuwe gebruiker toevoegen.

### Wat verwacht u op de migratiedag {#what-to-expect-on-migration-day}

Alle Marketo-abonnementen met een Amerikaanse tijdzone worden gemigreerd vanaf middernacht, Pacific Standard Time, van de startdatum van de migratie. De migratie van de gebruiker voor alle andere abonnementen zal om middernacht van gespecificeerde timezone van het abonnement beginnen.

**Adobe zal automatisch Marketo Admins (met een standaard rol Admin) eerst** migreren. Wanneer Marketo Admins naar Adobe Identity met een rol van de Beheerder van het Product van Admin Console wordt gemigreerd, zullen zij de rol van de Admin van het Product van Adobe binnen de toepassing van Marketo samen met om het even welke andere rollen worden toegewezen zij eerder hadden.

**als uw Marketo abonnement geen SSO in Marketo en/of uw Adobe Org** heeft, zal Adobe automatisch de rest van uw gebruikers migreren. Deze workflow is bedoeld om het hoogste niveau van automatisering te bieden om overhead voor Adobe Marketo-gebruikers tot een minimum te beperken. Er is geen actie van uw kant vereist om de migratie uit te voeren.

**als uw Marketo abonnement SSO in Marketo en/of uw Adobe Org** heeft, zullen de Admins van Marketo toegang tot het gebied van de Migratie van de Gebruiker van de Zelfbediening van de Console van de Migratie van Marketo krijgen, die in het Gebied van Admin van Marketo wordt gevestigd. Voor degenen die meer controle nodig hebben tijdens het migratieproces van gebruikers, kunnen Marketo Admins beginnen met het selecteren van gebruikers om in partijen of allen tegelijk te migreren. Als gebruikers zijn geselecteerd, hebben beheerders de optie &quot;Nu migreren&quot; of &quot;Migratie plannen&quot; voor een latere datum. Hierdoor hebben beheerders de ultieme flexibiliteit en controle over welke gebruikers worden gemigreerd wanneer.

>[!NOTE]
>
>Tijdens de migratie van gebruikers zal de toegang tot het product niet verloren gaan. Als een gebruiker is aangemeld tijdens het migreren van de gebruiker, wordt de gebruiker afgemeld en wordt hem gevraagd zich binnen enkele minuten opnieuw aan te melden met Adobe Identity nadat de migratie is voltooid. De gebruiker moet de uitnodiging accepteren door op de koppeling te klikken in de e-mail met bevoegdheden die wordt verzonden aan het einde van een geslaagde gebruikersmigratie.

Terwijl gebruikers worden gemigreerd, ontvangen ze een e-mail van Adobe waarin ze op de hoogte worden gesteld van de wijziging in de manier waarop ze zich aanmelden bij Marketo. De gebruikers **moeten** een uitnodiging goedkeuren om binnen het gebruiken van Identiteit van Adobe voor het eerst te ondertekenen, of door binnen met bestaande Adobe ID te ondertekenen of door vestiging een nieuwe Adobe ID gebruikend het zelfde e-mailadres.

De meer informatie kan in [ Migrerend aan de Identiteit van Adobe ](/help/marketo/product-docs/administration/marketo-with-adobe-identity/subscription-and-user-migration/migrating-to-adobe-identity.md){target="_blank"}, [ Teken-binnen van de Gebruiker met Adobe ](/help/marketo/product-docs/administration/marketo-with-adobe-identity/user-sign-in-with-adobe-id.md){target="_blank"}, en [ Veelgestelde vragen van Identity Management van Adobe ](/help/marketo/product-docs/administration/marketo-with-adobe-identity/faq.md){target="_blank"} worden gevonden.

## Migratie van gebruiker voltooid {#user-migration-complete}

Adobe stelt alle systeembeheerders en productbeheerders via e-mail op de hoogte zodra alle beheerders en gebruikers zijn gemigreerd. Op dit moment zullen alle Marketo-gebruikers voor dat abonnement zich aanmelden bij Marketo met Adobe Identity en zullen productbeheerders gebruikers alleen op Adobe Admin Console beheren.

## Ondersteuning {#get-support}

E-mail `marketocares@marketo.com` voor extra ondersteuning met betrekking tot uw abonnement of gebruikersmigratie.

>[!MORELIKETHIS]
>
>* [ migrerend aan het Overzicht van de Identiteit van Adobe ](/help/marketo/product-docs/administration/marketo-with-adobe-identity/subscription-and-user-migration/migrating-to-adobe-identity.md){target="_blank"}
>* [ het Teken van de Gebruiker met Adobe ](/help/marketo/product-docs/administration/marketo-with-adobe-identity/user-sign-in-with-adobe-id.md){target="_blank"}
>* [ Adobe Identity Management FAQ ](/help/marketo/product-docs/administration/marketo-with-adobe-identity/faq.md){target="_blank"}
>* [ migrerend aan Adobe Identity Management Leerprogramma ](https://experienceleague.adobe.com/nl/docs/marketo-learn/tutorials/fundamentals/migrating-to-adobe-identity-management){target="_blank"}
