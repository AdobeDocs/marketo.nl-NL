---
unique-page-id: 11377945
description: Overzicht audittrail - Marketo Docs - Productdocumentatie
title: Overzicht van audittrail
exl-id: e8aff7b7-72ca-4d4e-9159-56ff65f6345c
source-git-commit: 81ee349dbbe48c70b040751cae750c3684b71c78
workflow-type: tm+mt
source-wordcount: '328'
ht-degree: 0%

---

# Overzicht van audittrail {#audit-trail-overview}

Met Audittrail hebt u de mogelijkheid om een complete geschiedenis (van zes maanden) met wijzigingen te verkrijgen die in uw Marketo-exemplaar zijn aangebracht.

>[!NOTE]
>
>De geschiedenis van de gegevens van het audittrail begon op 14 september 2016.

![](assets/audit-trail-overview-1.png)

## Wat is audittrail? {#what-is-audit-trail}

Met Audittrail wordt in real-time een uitgebreide lijst met acties en gebeurtenissen vastgelegd die plaatsvinden binnen een Marketo-abonnement. Het omvat een zelfredzame manier om tot een geschiedenis van zes maanden van gegevens toegang te hebben helpen vragen zoals beantwoorden:

Wat is er gebeurd met dit middel of deze instelling en wie heeft deze voor het laatst bijgewerkt?

Wat heeft gebruiker X bereikt?

Wie registreert zich op ons account?

## Wat wij controleren {#what-we-audit}

Marketo zal de [maken, bewerken en verwijderen](/help/marketo/product-docs/administration/audit-trail/change-details-in-audit-trail.md) acties voor:

* Ontwerpstudioactiva
* Alle Marketo-programma&#39;s
* Slimme campagnes
* Lijsten (slim/statisch)
* Gebruikers (beheerder)
* Rollen en machtigingen (admin)
* Werkruimte en partities (admin)
* Aanmeldingsgeschiedenis gebruiker

>[!NOTE]
>
>Marketo is _niet_ Het controleren van veranderingen die binnen Personalisatie van het Web, Voorspelende Inhoud, of Inzicht van de Verkoop op dit ogenblik worden aangebracht.

## Componenten van audittrail {#audit-trail-components}

Audittrail bestaat uit drie componenten.

**1) [Asset Audit Trail](/help/marketo/product-docs/administration/audit-trail/change-details-in-audit-trail.md#asset-audit-trail)**

Zie de activiteiten die zijn uitgevoerd voor specifieke elementen.

**2) [Beheerdersaudittrail](/help/marketo/product-docs/administration/audit-trail/change-details-in-audit-trail.md#admin-audit-trail)**

Op gebruikers gebaseerde gegevens controleren.

**3) [Aanmeldingsgeschiedenis gebruiker](/help/marketo/product-docs/administration/audit-trail/user-login-history.md)**

Zie wie zich heeft aangemeld bij uw abonnement en wanneer. Omvat ook ontbroken login pogingen.

>[!TIP]
>
>Er is zo veel u kunt controleren gebruikend het Spoor van de Controle, zeker om te gebruiken [Filteren](/help/marketo/product-docs/administration/audit-trail/filtering-in-audit-trail.md)!

## Gegevens exporteren {#exporting-data}

U kunt slechts gegevens van 30 dagen in uw exemplaar bekijken. Gebruik de exportoptie om een waarde van maximaal zes maanden te verkrijgen.

![](assets/two.png)

>[!NOTE]
>
>**Definitie**
>
>**Onbekend:** In [!DNL Webhook]kan de naam en het e-mailadres van een gebruiker worden weergegeven als Onbekend. Dit gebeurt wanneer u een verandering in uw picklist waarden in uw CRM aanbrengt. Deze waarden worden weergegeven in Marketo-formulieren en bestemmingspagina&#39;s. Als u deze update uitvoert aan de CRM-zijde, worden uw bestemmingspagina&#39;s die verwijzen naar het formulier automatisch geprogrammeerd. In [!DNL Webhook], zullen wij vangen dat de landingspagina werd opgesteld, maar de naam en de e-mail van de gebruiker zullen tonen als &quot;Onbekend,&quot;aangezien wij niet de gebruikersinformatie van de kant van CRM kunnen vangen.

>[!MORELIKETHIS]
>
>[Audittrail inschakelen](/help/marketo/product-docs/administration/audit-trail/enable-audit-trail.md)
