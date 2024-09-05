---
unique-page-id: 10100311
description: Een universele id gebruiken voor aanmelding bij een abonnement - Marketo Docs - Productdocumentatie
title: Een universele id gebruiken voor aanmelding bij een abonnement
exl-id: 75cf1323-0468-49e9-83ca-e55aa30744ac
feature: Administration
source-git-commit: 5a8ea3c5356cb370b4e502b23eea8a457bfc97f1
workflow-type: tm+mt
source-wordcount: '569'
ht-degree: 0%

---

# Een universele id gebruiken voor aanmelding bij een abonnement {#using-a-universal-id-for-subscription-login}

Met een Universal ID hebt u toegang tot meerdere Marketo-abonnementen met één aanmelding en kunt u snel schakelen tussen abonnementen. U kunt echter desgewenst verschillende aanmeldingen voor uw abonnementen gebruiken.

Met Universal ID maakt u nog steeds ondersteuningstickets voor elk van uw individuele abonnementen.

De het niveaumontages van het abonnement worden gerespecteerd voor gebruikers die Universele identiteitskaart, bijvoorbeeld, rollen, toestemmingen, en wachtwoordbeleid gebruiken. Wijzigingen in het gebruikersprofielniveau worden weerspiegeld in alle abonnementen, bijvoorbeeld voornaam, achternaam en e-mailadres.

## Een universele id instellen {#setting-up-a-universal-id}

Alle Marketo-abonnementen worden geleverd met de optionele functie Universele id. Van elk afzonderlijk exemplaar, moet uw beheerder van Marketo u aan elk van uw verschillende abonnementen met de zelfde login uitnodigen. Marketo kan uw bestaande aanmeldingen niet automatisch samenvoegen.

>[!NOTE]
>
>Als u meerdere aanmeldings-id&#39;s voor abonnementen hebt, hebt u mogelijk ook meerdere gemeenschapsprofielen. Kies de id voor de Universal-id die is verbonden met het profiel dat u wilt gebruiken. Deze id is bestemd voor de productie-instantie, niet voor de sandbox.

## Aanmelden {#logging-in}

Wanneer u zich aanmeldt om een uitnodiging voor een tweede abonnement met een Universal-id te accepteren, wordt de aanmeldingspagina van Inschakelen weergegeven. Hier moet u een selectievakje inschakelen om de voorwaarden te accepteren. Nadat u hebt goedgekeurd, zult u de normale terugstellingspagina, niet deze, voor om het even welke verdere logins zien. Door de voorwaarden en bepalingen te accepteren, staat u Marketo toe om uw basisprofielgegevens (zoals voornaam, achternaam en e-mailadres) naar de datacenters te distribueren op verschillende locaties waar uw abonnement wordt gehost.

![](assets/using-a-universal-id-for-subscription-login-1.png)

>[!TIP]
>
>Id&#39;s die u niet meer gebruikt, blijven behouden, tenzij de abonnementsbeheerder ze verwijdert. Wij adviseren dat u hen houdt, voor het geval dat, bijvoorbeeld, u een privé rapport hebt, dat aan zich wordt toegewezen, dat slechts kan worden betreden gebruikend die identiteitskaart. In dit geval is het verstandig om deze privérapporten te verplaatsen naar uw nieuwe universele id en vervolgens uw bestaande id te verwijderen.

## Wachtwoorden {#passwords}

Met Universal ID voor meerdere abonnementen past Marketo automatisch het strengste wachtwoordbeleid toe. Bijvoorbeeld, als sommige abonnementen een minimumwachtwoordlengte vereisen en anderen niet, zal de minimumlengte voor alle abonnementen worden afgedwongen.

Met een universele id voor meerdere abonnementen kunt u alleen het wachtwoord wijzigen.

>[!NOTE]
>
>Marketo zal gebruikers die de Universal-id willen gebruiken, vragen hun wachtwoord opnieuw in te stellen als het wachtwoord van het huidige abonnement niet voldoet aan het wachtwoordbeleid van het tweede abonnement waarvoor ze worden uitgenodigd.

## Schakelen tussen abonnementen {#switching-between-subscriptions}

Met een Universal-id kunt u het abonnement zien waarin u bent aangemeld en andere abonnementen selecteren waartoe u aanmeldingstoegang hebt. In de meeste gevallen, kunt u tussen hen schakelen zonder het moeten logout en terug binnen.

Als zowel [ Enige Teken ](/help/marketo/product-docs/administration/additional-integrations/add-single-sign-on-to-a-portal.md) en Universele identiteitskaart worden toegelaten, moet u de &quot;Enige Ondertekende die&quot;toestemming hebben van de Bypass wordt geplaatst om tussen abonnementen van een knevel te voorzien.

![](assets/using-a-universal-id-for-subscription-login-2.png)

Wanneer u zich afmeldt en weer inlogt, meldt Marketo u automatisch aan bij het abonnement waar u het laatst bent aangemeld. U kunt desgewenst overschakelen naar een ander abonnement.

## Profielen van community {#community-profiles}

Als u meerdere abonnementen hebt, hebt u mogelijk meerdere gemeenschapsprofielen. Wij adviseren dat u login kiest die met uw actiefste gemeenschapsprofiel verbonden is.

>[!MORELIKETHIS]
>
>* [ voeg Enige Sign-On aan een Portaal ](/help/marketo/product-docs/administration/additional-integrations/add-single-sign-on-to-a-portal.md){target="_blank"} toe
>* [ Beperk het Login van de Gebruiker tot SSO slechts ](/help/marketo/product-docs/administration/additional-integrations/restrict-user-login-to-sso-only.md){target="_blank"}
>* [ het Uitnodigen van de Gebruikers van Marketo aan Twee Instanties met Universele identiteitskaart ](https://nation.marketo.com/t5/Knowledgebase/Inviting-Marketo-Users-to-Two-Instances-with-Universal-ID-UID/ta-p/251122) {target="_blank"}
