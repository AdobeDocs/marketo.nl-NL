---
unique-page-id: 11377945
description: Overzicht audittrail - Marketo Docs - Productdocumentatie
title: Overzicht van audittrail
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '378'
ht-degree: 0%

---


# Overzicht van audittrail {#audit-trail-overview}

Met Audittrail beschikt u over de mogelijkheid om een complete geschiedenis (van zes maanden) met wijzigingen te verkrijgen die in uw Marketo-instantie zijn aangebracht.

>[!NOTE]
>
>De geschiedenis van audittrailgegevens begon op 14 september 2016.

![](assets/one.png)

## Wat is audittrail? {#what-is-audit-trail}

Met Audittrail wordt in real-time een uitgebreide lijst met acties en gebeurtenissen vastgelegd die plaatsvinden binnen een Marketo-abonnement. Het omvat een zelfredzame manier om tot een geschiedenis van zes maanden van gegevens toegang te hebben helpen vragen zoals beantwoorden:

Wat is er gebeurd met dit middel of deze instelling en wie heeft deze voor het laatst bijgewerkt?

Wat heeft gebruiker X bereikt?

Wie registreert zich op ons account?

## Wat wij controleren {#what-we-audit}

Marketo controleert de [acties voor het maken, bewerken en verwijderen](http://docs.marketo.com/display/DOCS/Change+Details+in+Audit+Trail) van:

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
>Marketo controleert **geen** veranderingen die binnen Personalisatie van het Web, Voorspelende Inhoud, of het Inzicht van de Verkoop op dit ogenblik worden aangebracht.

## Componenten van audittrail {#audit-trail-components}

Audittrail bestaat uit drie componenten.

**1) [Asset Audit Trail](http://docs.marketo.com/display/DOCS/Change+Details+in+Audit+Trail#ChangeDetailsinAuditTrail-AssetAuditTrail)**

Zie de activiteiten die zijn uitgevoerd voor specifieke elementen.

**2) [Beheerdersaudittrail](http://docs.marketo.com/display/DOCS/Change+Details+in+Audit+Trail#ChangeDetailsinAuditTrail-AdminAuditTrail)**

Op gebruikers gebaseerde gegevens controleren.

**3) [Aanmeldingsgeschiedenis gebruiker](http://docs.marketo.com/display/DOCS/User+Login+History)**

Zie wie zich heeft aangemeld bij uw abonnement en wanneer. Omvat ook ontbroken login pogingen.

>[!TIP]
>
>Er is zo veel u kunt controleren gebruikend het Trail van de Controle, zeker om het [Filtreren](http://docs.marketo.com/display/DOCS/Filtering+in+Audit+Trail)te gebruiken!

## Gegevens exporteren {#exporting-data}

U kunt slechts gegevens van 30 dagen in uw exemplaar bekijken. Gebruik de exportoptie om een waarde van maximaal zes maanden te verkrijgen.

![](assets/two.png)

>[!NOTE]
>
>**Definitie**
>
>**Onbekend:** In audittrail, kunt u de naam van een gebruiker en e-mail zien die als &quot;Onbekend&quot; worden vermeld. Dit gebeurt wanneer u een verandering in uw picklist waarden in uw CRM aanbrengt. Deze waarden worden weergegeven op Marketo-formulieren en landingspagina&#39;s. Als u deze update uitvoert aan de CRM-zijde, worden uw bestemmingspagina&#39;s die verwijzen naar het formulier automatisch geprogrammeerd. In audittrail, zullen wij vangen dat de het landen pagina werd opgesteld, maar de naam en e-mail van de gebruiker zullen tonen als &quot;Onbekend,&quot;aangezien wij niet de gebruikersinformatie van de kant van CRM kunnen vangen.

>[!NOTE]
>
>**Verwante artikelen**
>
>* [Audittrail inschakelen](enable-audit-trail.md)

>



