---
unique-page-id: 14352405
description: SSO instellen via SAML 2.0 in Sales Connect - Marketo Docs - Productdocumentatie
title: SSO via SAML 2.0 instellen in Sales Connect
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '254'
ht-degree: 0%

---


# SSO instellen via SAML 2.0 in Sales Connect {#setting-up-sso-through-saml-in-sales-connect}

Wij steunen SSO door de specificatie van SAML 2.0. We hebben momenteel echter geen directe integratie met een leverancier. Wij zullen wat informatie van uw leverancier SSO moeten verzamelen om deze opstelling te krijgen.

>[!NOTE]
>
>**Herinnering**
>
>Dit is alleen van toepassing op **Marketo Sales Connect**-klanten. Neem contact op met de succesmanager van de klant als u geen Verkoopverbinding hebt maar meer wilt weten.

## Vereisten {#requirements}

* SSO-account
* Abonnement op Marketo Sales Connect
* Metadata.xml van SSO-account (geef URL uit, het eindpunt voor validatie en een openbare sleutel)

## {#setup} instellen

Metadata.xml van de instantie van SSO van uw team zou de uitgever URL, het eindpunt voor bevestiging, en een openbare sleutel moeten bevatten.

Wij zullen ook de Plaats SSO voor de rekening van SSO van uw bedrijf nodig hebben om een uniek domein te zijn. We `require a unique subdomain` houden bijvoorbeeld van &#39;toutapp.pingidentity.com&#39; of iets dergelijks. Zonder dit type unieke id kunnen we geen SAML instellen vanaf het dashboard.

Één Login en Okta verstrekken niet altijd unieke herkenningstekens wanneer het toewijzen van een URL. Als u Okta of Één Login gebruikt, betekent het dat wij niet één login van de dashboardknoop kunnen plaatsen. We kunnen deze nog steeds instellen met de knop Single Sign On op de [webtoepassing](http://toutapp.com/login).

Zodra wij die informatie hebben, zullen wij met ons technische team werken om dit voor uw abonnement op te stellen.
