---
unique-page-id: 14352405
description: SSO instellen via SAML 2.0 in Sales Connect - Marketo Docs - Productdocumentatie
title: SSO via SAML 2.0 instellen in Sales Connect
exl-id: aab80626-d6d1-4194-9733-09c90c0b49a6
feature: Marketo Sales Connect
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '259'
ht-degree: 0%

---

# SSO via SAML 2.0 instellen in Sales Connect {#setting-up-sso-through-saml-in-sales-connect}

Wij steunen SSO door de specificatie van SAML 2.0. We hebben momenteel echter geen directe integratie met een leverancier. Wij zullen wat informatie van uw leverancier SSO moeten verzamelen om deze opstelling te krijgen.

>[!NOTE]
>
>Dit geldt alleen voor **Marketo Sales Connect** gebruikers. Neem contact op met het Adobe-accountteam (uw accountmanager) als u geen Sales Connect hebt maar meer wilt weten.

## Vereisten {#requirements}

* SSO-account
* Abonnement op Marketo Sales Connect
* Metadata.xml van SSO-account (geef URL uit, het eindpunt voor validatie en een openbare sleutel)

## Instellen {#setup}

Metadata.xml van de instantie van SSO van uw team zou de uitgever URL, het eindpunt voor bevestiging, en een openbare sleutel moeten bevatten.

Wij zullen ook de Plaats SSO voor de rekening van SSO van uw bedrijf nodig hebben om een uniek domein te zijn. We hebben bijvoorbeeld een uniek subdomein nodig, zoals `toutapp.pingidentity.com` of een soortgelijke Zonder dit type unieke id kunnen we geen SAML instellen vanaf het dashboard.

Één Login en Okta verstrekken niet altijd unieke herkenningstekens wanneer het toewijzen van een URL. Als u Okta of Één Login gebruikt, betekent het dat wij niet één login van de dashboardknoop kunnen plaatsen. We kunnen deze nog steeds instellen met de knop Single Sign On op het tabblad [webtoepassing](https://toutapp.com/login).

Zodra wij die informatie hebben, zullen wij met ons technische team werken om dit voor uw abonnement op te stellen.
