---
unique-page-id: 10100311
description: Een universele id gebruiken voor aanmelding bij een abonnement - Marketo Docs - Productdocumentatie
title: Een universele id gebruiken voor aanmelding bij een abonnement
exl-id: 75cf1323-0468-49e9-83ca-e55aa30744ac
source-git-commit: 591279dfb573853eb8781d7984c65716804120b0
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# Een universele id gebruiken voor aanmelding bij een abonnement {#using-a-universal-id-for-subscription-login}

Met een Universal ID hebt u toegang tot meerdere Marketo-abonnementen met één aanmelding en kunt u snel schakelen tussen abonnementen. U kunt echter desgewenst verschillende aanmeldingen voor uw abonnementen gebruiken.

Met Universal ID maakt u nog steeds ondersteuningstickets voor elk van uw individuele abonnementen.

De het niveaumontages van het abonnement worden gerespecteerd voor gebruikers die Universele identiteitskaart, bijvoorbeeld, rollen, toestemmingen, en wachtwoordbeleid gebruiken. Wijzigingen in het gebruikersprofielniveau worden weerspiegeld in alle abonnementen, bijvoorbeeld voornaam, achternaam en e-mailadres.

## Een universele id instellen {#setting-up-a-universal-id}

Van elk afzonderlijk exemplaar, moet uw beheerder van Marketo u aan elk van uw verschillende abonnementen met de zelfde login uitnodigen. Marketo kan uw bestaande aanmeldingen niet automatisch samenvoegen. Als u de Universal ID hebt ingeschakeld, is **uw Marketo-instantie maximaal 30 minuten niet beschikbaar**. Als u een grotere gebruikersbasis hebt, zou het een beetje langer kunnen zijn.

>[!NOTE]
>
>Als u meerdere aanmeldings-id&#39;s voor abonnementen hebt, hebt u mogelijk ook meerdere gemeenschapsprofielen. Kies de id voor de Universal-id die is verbonden met het profiel dat u wilt gebruiken. Deze id is bestemd voor de productie-instantie, niet voor de sandbox.

## Aanmelden {#logging-in}

Wanneer u zich aanmeldt om een uitnodiging voor een tweede abonnement met een Universal-id te accepteren, wordt de aanmeldingspagina van Inschakelen weergegeven. Hier moet u een selectievakje inschakelen om de voorwaarden te accepteren. Nadat u hebt goedgekeurd, zult u de normale terugstellingspagina, niet deze, voor om het even welke verdere logins zien. Door de voorwaarden en bepalingen te accepteren, staat u Marketo toe om uw basisprofielgegevens (zoals voornaam, achternaam en e-mailadres) naar de datacenters te distribueren op verschillende locaties waar uw abonnement wordt gehost.

![](assets/new-login-reduced-hands-name.png)

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

Gebruikend een Universele identiteitskaart, kunt u het abonnement zien u wordt geregistreerd in, en andere abonnementen selecteren waartot u login toegang hebt. In de meeste gevallen, kunt u tussen hen schakelen zonder het moeten logout en terug binnen.

![](assets/image2016-11-3-15-3a10-3a16.png)

Wanneer u zich afmeldt en weer inlogt, meldt Marketo u automatisch aan bij het abonnement waar u het laatst bent aangemeld. U kunt desgewenst overschakelen naar een ander abonnement.

## Community-profielen {#community-profiles}

Als u meerdere abonnementen hebt, hebt u mogelijk meerdere gemeenschapsprofielen. Wij adviseren dat u login kiest die met uw actiefste gemeenschapsprofiel verbonden is.

## Mobiel Platform {#mobile-platform}

Gebruikers met een Universal ID kunnen hun gegevens op Marketo Moments en de toepassing voor het inchecken van iPad-gebeurtenissen bekijken via het abonnement waarin zij zich het laatst hebben aangemeld. U kunt geen abonnementen van het Mobiele platform zelf veranderen.

>[!MORELIKETHIS]
>
>* [Eén aanmelding toevoegen aan een portal](/help/marketo/product-docs/administration/additional-integrations/add-single-sign-on-to-a-portal.md)
>* [Alleen gebruikersaanmelding beperken tot SSO](/help/marketo/product-docs/administration/additional-integrations/restrict-user-login-to-sso-only.md)
>* [Marketo-gebruikers uitnodigen voor twee instanties met Universal ID](https://nation.marketo.com/t5/Knowledgebase/Inviting-Marketo-Users-to-Two-Instances-with-Universal-ID-UID/ta-p/251122)

