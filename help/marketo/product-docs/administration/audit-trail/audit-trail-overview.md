---
unique-page-id: 11377945
description: Audit Trail&rbrack; Overzicht - Marketo Docs - Productdocumentatie
title: Overzicht van audittrail
exl-id: e8aff7b7-72ca-4d4e-9159-56ff65f6345c
feature: Audit Trail
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '332'
ht-degree: 0%

---

# Overzicht van audittrail {#audit-trail-overview}

Met Audittrail hebt u de mogelijkheid om een complete geschiedenis (van zes maanden) met wijzigingen te verkrijgen die in uw Marketo-exemplaar zijn aangebracht.

>[!NOTE]
>
>De geschiedenis van audittrail begon op 14 september 2016.

![](assets/audit-trail-overview-1.png)

## Wat is audittrail? {#what-is-audit-trail}

Met Audittrail wordt in real-time een uitgebreide lijst met acties en gebeurtenissen vastgelegd die plaatsvinden binnen een Marketo-abonnement. Het omvat een zelfredzame manier om tot een geschiedenis van zes maanden van gegevens toegang te hebben helpen vragen zoals beantwoorden:

Wat is er gebeurd met dit middel of deze instelling en wie heeft deze voor het laatst bijgewerkt?

Wat heeft gebruiker X bereikt?

Wie registreert zich op ons account?

## Wat wij controleren {#what-we-audit}

Marketo zal [&#128279;](/help/marketo/product-docs/administration/audit-trail/change-details-in-audit-trail.md) acties creëren uitgeven en schrappen voor:

* Ontwerpstudioactiva
* Alle Marketo-programma&#39;s
* Slimme campagnes
* Lijsten (slim/statisch)
* Gebruikers (beheerder)
* Rollen en machtigingen (admin)
* Workspace en partities (admin)
* Aanmeldingsgeschiedenis gebruiker

>[!NOTE]
>
>Marketo is _niet_ controleveranderingen die binnen Personalization van het Web, Voorspelende Inhoud, of Insight van de Verkoop op dit ogenblik worden aangebracht.

## Componenten van audittrail {#audit-trail-components}

Audittrail bestaat uit drie componenten.

**1) [ Trail van de Controle van Activa](/help/marketo/product-docs/administration/audit-trail/change-details-in-audit-trail.md#asset-audit-trail)**

Zie de activiteiten die zijn uitgevoerd voor specifieke elementen.

**[&#128279;](/help/marketo/product-docs/administration/audit-trail/change-details-in-audit-trail.md#admin-audit-trail)** het Spoor van de Controle Admin 

Op gebruikers gebaseerde gegevens controleren.

**[ Login Geschiedenis van de Gebruiker](/help/marketo/product-docs/administration/audit-trail/user-login-history.md)**

Zie wie zich heeft aangemeld bij uw abonnement en wanneer. Omvat ook ontbroken login pogingen.

>[!TIP]
>
>Er is zo veel u het gebruiken van het Spoor van de Controle kunt controleren, ben zeker om [ het Filtreren ](/help/marketo/product-docs/administration/audit-trail/filtering-in-audit-trail.md) te gebruiken!

## Gegevens exporteren {#exporting-data}

U kunt slechts gegevens van 30 dagen in uw exemplaar bekijken. Gebruik de exportoptie om een waarde van maximaal zes maanden te verkrijgen.

![](assets/two.png)

>[!NOTE]
>
>**Definitie**
>
>**Onbekend:** In [!DNL Webhook], kunt u de naam en e-mail van een gebruiker zien die als &quot;Onbekend wordt vermeld.&quot; Dit gebeurt wanneer u een verandering in uw picklist waarden in uw CRM aanbrengt. Deze waarden worden weergegeven in Marketo-formulieren en bestemmingspagina&#39;s. Als u deze update uitvoert aan de CRM-zijde, worden uw bestemmingspagina&#39;s die verwijzen naar het formulier automatisch geprogrammeerd. In [!DNL Webhook] wordt vastgelegd dat de bestemmingspagina is opgesteld, maar dat de naam en het e-mailadres van de gebruiker &#39;Onbekend&#39; zijn, omdat we de gebruikersgegevens niet kunnen vastleggen aan de CRM-zijde.

>[!MORELIKETHIS]
>
>[ laat het Spoor van de Controle ](/help/marketo/product-docs/administration/audit-trail/enable-audit-trail.md) toe
