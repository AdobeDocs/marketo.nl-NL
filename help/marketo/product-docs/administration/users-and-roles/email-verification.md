---
description: E-mailverificatie - Marketo Docs - Productdocumentatie
title: E-mailverificatie
exl-id: 976e46a7-8c85-45ed-86c1-0c5cdb2d5c3e
feature: Users and Roles
source-git-commit: 02b2e39580c5eac63de4b4b7fdaf2a835fdd4ba5
workflow-type: tm+mt
source-wordcount: '403'
ht-degree: 0%

---

# E-mailverificatie {#email-verification}

Adobe Marketo Engage-abonnementen vereisen dat alle gebruikers die geen API gebruiken, inclusief Marketo Engage-beheerders, hun e-mailadres verifiëren. Aan gebruikers met een SSO (Single Sign-On) die geen beheerrol hebben toegewezen of die een rol met de machtiging SSO omzeilen hebben toegewezen, wordt hun e-mail automatisch geverifieerd wanneer hun abonnement is ingeschakeld met de functie E-mailverificatie.

## Waarom deze functie is geïntroduceerd {#why-this-feature-was-introduced}

Marketo Engage gaat door met de uitrol van e-mailverificatie ter voorbereiding op het migreren van klanten naar het Adobe Business Platform, inclusief de migratie van gebruikers naar Adobe-id&#39;s. Deze functie verbetert de beveiliging van bestaande Marketo Engage-gebruikersaccounts. Om ervoor te zorgen dat een Marketo Engage-gebruiker aan de juiste Adobe ID is gekoppeld, moeten bestaande Marketo Engage-gebruikers hun e-mailadres verifiëren. Een Marketo Engage-gebruiker moet een geverifieerd e-mailadres hebben om naar een Adobe ID te worden gemigreerd. Als een Marketo Engage-gebruiker zijn e-mailadres niet verifieert, kan hij of zij niet naar een Adobe ID migreren en verliest hij of zij toegang tot een Marketo-abonnement nadat de gebruikersmigratie voor het abonnement is voltooid.

## Uitnodiging gebruiker {#user-invite}

Wanneer een Admin een gebruiker uitnodigt, wordt die gebruiker automatisch geverifieerd zodra hij op de uitnodigingskoppeling klikt. SSO-gebruikers waaraan de beheerdersrol niet is toegewezen, worden automatisch geverifieerd.

## Verificatiebericht {#verification-email}

Gebruikers ontvangen de volgende e-mail wanneer e-mailverificatie wordt geactiveerd voor een abonnement of als deze wordt geactiveerd door een beheerder/gebruiker:

![](assets/email-verification-1.png)

>[!NOTE]
>
>Als u een verificatiebericht opnieuw wilt verzenden aan een niet-geverifieerde gebruiker, selecteert u gewoon de desbetreffende record en klikt u op de knop **[!UICONTROL Verify Email]** knop.

## Een e-mailadres wijzigen {#changing-an-email-address}

Wanneer het e-mailadres van een gebruiker wordt gewijzigd, wordt het niet geverifieerd. Er wordt een e-mail naar hen verzonden, zodat ze opnieuw kunnen verifiëren. Gebruikers kunnen de e-mail handmatig opnieuw verzenden door op **[!UICONTROL Resend Verification]**.

![](assets/email-verification-2.png)

![](assets/email-verification-3.png)

## Gebruikers en rollen {#users-and-roles}

In **[!UICONTROL Admin]** > **[!UICONTROL Users & Roles]** In de kolom E-mailstatus wordt de verificatiestatus van elke gebruiker weergegeven.

![](assets/email-verification-4.png)

## Meerdere aanmeldings-id&#39;s voor gebruikers {#multiple-user-login-ids}

Er kan slechts één gebruikersaccount aan één e-mailadres worden gekoppeld. Als er meerdere gebruikersaccounts zijn gekoppeld aan één e-mailadres, vereist Marketo Engage dat het conflict wordt opgelost en dat alle gebruikersaanmeldingen worden weergegeven die aan het e-mailadres zijn gekoppeld, en drie oplossingsopties:

* Huidige e-mail gebruiken voor de huidige gebruikersnaam
* Nieuwe e-mail gebruiken voor de huidige gebruikersnaam
* De beslissing vertragen tot volgende aanmelding

  ![](assets/email-verification-5.png)

>[!NOTE]
>
>Terwijl een gebruikersaccount aan één adres moet worden gekoppeld, kan een gebruikersaccount voor veel abonnementen worden gebruikt via Universal ID.
