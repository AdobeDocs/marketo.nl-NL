---
description: E-mailverificatie - Marketo Docs - Productdocumentatie
title: E-mailverificatie
exl-id: 976e46a7-8c85-45ed-86c1-0c5cdb2d5c3e
source-git-commit: 44cca5ebad831cc39babac87ac9ebbf53df6c795
workflow-type: tm+mt
source-wordcount: '255'
ht-degree: 0%

---

# E-mailverificatie {#email-verification}

Adobe Marketo Engage-abonnementen vereisen dat alle gebruikers die geen API gebruiken, inclusief Marketo Engage-beheerders, hun e-mailadres verifiëren. Aan gebruikers met een SSO (Single Sign-On) die geen beheerrol hebben toegewezen of die een rol met de machtiging SSO omzeilen hebben toegewezen, wordt hun e-mail automatisch geverifieerd wanneer hun abonnement is ingeschakeld met de functie E-mailverificatie.

## Uitnodiging gebruiker {#user-invite}

Wanneer een Admin een gebruiker uitnodigt, wordt die gebruiker automatisch geverifieerd zodra hij op de uitnodigingskoppeling klikt. SSO-gebruikers waaraan de beheerdersrol niet is toegewezen, worden automatisch geverifieerd.

## Een e-mailadres wijzigen {#changing-an-email-address}

Wanneer het e-mailadres van een gebruiker wordt gewijzigd, wordt het niet geverifieerd. Er wordt een e-mail naar hen verzonden, zodat ze opnieuw kunnen verifiëren. Gebruikers kunnen de e-mail handmatig opnieuw verzenden door op **Verificatie opnieuw verzenden**.

![](assets/email-verification-1.png)

![](assets/email-verification-2.png)

## Gebruikers en rollen {#users-and-roles}

In **Beheer** > **Gebruikers en rollen** In de kolom E-mailstatus wordt de verificatiestatus van elke gebruiker weergegeven.

![](assets/email-verification-3.png)

## Meerdere aanmeldings-id&#39;s voor gebruikers {#multiple-user-login-ids}

Er kan slechts één gebruikersaccount aan één e-mailadres worden gekoppeld. Als er meerdere gebruikersaccounts zijn gekoppeld aan één e-mailadres, vereist Marketo Engage dat het conflict wordt opgelost en dat alle gebruikersaanmeldingen worden weergegeven die aan het e-mailadres zijn gekoppeld, en drie oplossingsopties:<p>
`1` Huidige e-mail gebruiken voor de huidige gebruikersnaam<p>
`2` Nieuwe e-mail gebruiken voor de huidige gebruikersnaam<p>
`3` De beslissing vertragen tot volgende aanmelding

![](assets/email-verification-4.png)

## Verificatiebericht {#verification-email}

Uitgenodigde gebruikers ontvangen de volgende e-mail:

![](assets/email-verification-5.png)

>[!NOTE]
>
>Als u een verificatiebericht opnieuw wilt verzenden aan een niet-geverifieerde gebruiker, selecteert u gewoon de desbetreffende record en klikt u op de knop **E-mail verifiëren** knop.
