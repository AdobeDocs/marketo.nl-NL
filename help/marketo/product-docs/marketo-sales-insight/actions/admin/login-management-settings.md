---
description: Aanmeldingsbeheerinstellingen - Marketo-documenten - Productdocumentatie
title: Aanmeldingsbeheerinstellingen
hide: true
hidefromtoc: true
source-git-commit: e3d175d9f6131ec9798c4047ccf79858c254c745
workflow-type: tm+mt
source-wordcount: '471'
ht-degree: 0%

---

# Aanmeldingsbeheerinstellingen {#login-management-settings}

Met de instellingen voor Aanmeldingsbeheer kunnen beheerders de voorkeuren voor verificatie instellen voor gebruikers van Handelingen voor Verkoopcontrole op mondiaal niveau.

>[!NOTE]
>
>Standaard wordt de optie Alleen Salesforce geselecteerd voor instanties van Handelingen Handelingen in het verkoopinzicht. We raden deze instelling aan zodat gebruikers [automatisch aanmelden](/help/marketo/product-docs/marketo-sales-insight/actions/admin/auto-login-from-salesforce.md) uit Salesforce.

## Aanmeldingsbeheerinstellingen bijwerken {#update-login-management-settings}

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

Voer de volgende stappen uit om uw voorkeuren voor aanmeldingsbeheer bij te werken.

1. Klik op het tandwielpictogram en selecteer **Instellingen**.

   ![](assets/login-management-settings-1.png)

1. Klik onder Beheerinstellingen op **Algemeen**.

   ![](assets/login-management-settings-2.png)

1. Blader omlaag naar de aanmeldbeheerkaart en selecteer de gewenste instelling (in dit voorbeeld kiest u Alleen Salesforce). Klikken **Opslaan** wanneer gereed.

   ![](assets/login-management-settings-3.png)

## Veelgestelde vragen alleen Salesforce {#salesforce-only-faq}

Alleen Salesforce betekent dat gebruikers zich alleen kunnen verifiëren voor gebruik van Handelingen Verkoopcontrole met Salesforce. Het is de standaardselectie voor de instanties van Acties van het Inzicht van de Verkoop, en wordt geadviseerd wegens zijn capaciteit om gebruikers toe te staan om voor authentiek te verklaren zonder het moeten een gebruikersbenaming en een wachtwoord beheren.

### Hoe activeert een nieuwe gebruiker van mijn instantie zijn account wanneer Alleen Salesforce is geselecteerd? {#activate-when-salesforce-only-is-selected}

Als u op de knop **Aan de slag** in de e-mail met de uitnodiging worden nieuwe gebruikers naar een scherm voor accountactivering gestuurd, waar ze hun Salesforce-exemplaar moeten aansluiten om hun account voor Handelingen in het venster Handelingen in het verkoopinzicht te activeren.

![](assets/login-management-settings-4.png)

### Met welke verificatiemethoden mogen mijn gebruikers verifiëren wanneer &quot;Alleen Salesforce&quot; is geselecteerd? {#what-authentication-methods}

Wanneer gebruikers naar ons aanmeldingsscherm navigeren, voeren ze eerst hun e-mailadres in. Dan zullen zij Salesforce klikken één knoop van de Aanmelding van de Klik, waar zij voor authentiek kunnen verklaren gebruikend de rekening Salesforce zij worden het programma geopend aan.

>[!NOTE]
>
>Dit geldt alleen voor gebruikers die rechtstreeks naar het aanmeldingsscherm navigeren. Gebruikers die van Salesforce tot Acties toegang hebben, worden aangemeld met [Automatisch aanmelden](/help/marketo/product-docs/marketo-sales-insight/actions/admin/auto-login-from-salesforce.md).

![](assets/login-management-settings-5.png)

### Hoe wordt de gebruikersauthentificatie behandeld voor Acties wanneer een gebruiker tot een eigenschap van Acties van Salesforce en &quot;Salesforce slechts&quot;wordt geselecteerd? {#how-is-user-authentication-handled}

Wanneer een gebruiker op één van de acties (Vraag, E-mail, Campagne, Taken, de Lijst van de Campagne enz.) klikt gebruiken wij hun authentificatie SFDC om hen automatisch in hun rekening van de Acties van het Inzicht van de Verkoop te registreren. We noemen deze verificatie [Automatisch aanmelden](/help/marketo/product-docs/marketo-sales-insight/actions/admin/auto-login-from-salesforce.md).

## Veelgestelde vragen over alle aanmeldingsmethoden {#all-login-methods-faq}

### Hoe activeert een nieuwe gebruiker van mijn instantie zijn account wanneer &quot;Alle aanmeldingsmethoden&quot; is geselecteerd? {#activate-when-all-login-methods-is-selected}

Wanneer een nieuwe gebruiker wordt uitgenodigd voor een exemplaar, ontvangt hij een e-mail over activering van zijn account. Zij zullen op de knoop klikken die &quot;krijgen Begonnen&quot;zegt die dan hen aan een pagina zal brengen die hen vraagt om een wachtwoord tot stand te brengen en te bevestigen. Zodra dit wordt gecreeerd zal hun rekening worden geactiveerd en zij zullen door het onboarding werkschema worden genomen.

![](assets/login-management-settings-6.png)

### Waarmee mogen gebruikers van mijn instantie zich aanmelden wanneer &quot;Alle aanmeldingsmethoden&quot; is geselecteerd? {#what-are-users-allowed-to-log-in-with-all-login}

Als gebruikers onze aanmeldingspagina gebruiken, moeten ze eerst hun e-mailadres invoeren. Vervolgens worden ze naar een pagina verzonden die alle aanmeldingsopties (gebruikersnaam/wachtwoord, SFDC, Gmail, SSO) bevat waarmee ze kunnen worden geverifieerd.
