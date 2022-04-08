---
description: Toegang tot profielen van verkoopinzicht toevoegen - Marketo-documenten - Productdocumentatie
title: Toegang tot verkoopinzicht toevoegen aan profielen
exl-id: 269f9093-f530-4e3b-aac7-e317976cf0f0
source-git-commit: 5c4bce6ab6801b861f70722b6782df34f96fed10
workflow-type: tm+mt
source-wordcount: '438'
ht-degree: 0%

---

# Toegang tot verkoopinzicht toevoegen aan profielen {#add-sales-insight-access-to-profiles}

Hier is hoe te om een profiel met toegang tot het Inzicht van de Verkoop te creëren terwijl het verwijderen van toegang voor uw andere profielen. Dit is voor gebruikers die de [AppExchange-pakket voor verkoopinzicht](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md){target=&quot;_blank&quot;}.

>[!IMPORTANT]
>
>Als u al eerder toegang hebt verleend tot alle profielen via Verkoopcontrole, moet u [toegang tot profielniveau verwijderen](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/remove-sales-insight-access.md){target=&quot;_blank&quot;} om deze rechtenset te gebruiken.

## Een nieuw profiel voor Verkoopinzicht maken {#create-a-new-profile-for-sales-insight}

Als u een specifiek profiel voor uw gebruikers van het Inzicht van de Verkoop hebt, kunt u deze stap overslaan.

1. Ga in Salesforce naar de pagina Setup.

1. Zoek naar profielen in Snelle Vondst en selecteer **Profiel** optie.

1. Klik op de knop **Nieuw profiel** boven aan de pagina.

1. Kies een profiel om te klonen en geef het een naam (bijv. Gebruiker van het Inzicht van de Verkoop).

1. Klikken **Opslaan** wanneer gereed.

## Machtigingen voor verkoopinzicht toevoegen {#add-sales-insight-permissions}

1. Ga terug naar uw profiellijst.

1. Klik op de knop **Bewerken** een koppeling maken voor het nieuwe profiel dat u zojuist hebt gemaakt (of een ander bestaand profiel waaraan u toegang tot Sales Insight wilt geven).

1. Op de bewerkingspagina moet u een aantal instellingen wijzigen.

   **Voor profielen die toegang hebben tot Verkoopoverzicht**:

   * Wijzig in Tabinstellingen de Marketo-tabbladen in Standaard ingeschakeld
   * Schakel in Aangepaste objectmachtigingen de optie Lezen, Maken, Bewerken en Verwijderen in Marketo Sales Insight Config in (als de gebruiker toegang moet hebben tot de configuratie-instellingen - doorgaans wordt gebruikt voor Admins).

   **Voor profielen die geen toegang tot Verkoopinzicht hebben**:

   * Wijzig in Tabinstellingen de tabbladen van Marketo in Tabblad Verborgen
   * Schakel in Aangepaste objectmachtigingen de optie Lezen, Maken, Bewerken en Verwijderen uit in Marketo Sales Insight Config


1. Klikken **Opslaan** wanneer gereed.

## Lay-out maken voor Verkoopoverzicht {#create-layout-for-sales-insight}

1. Ga naar de pagina van de Opstelling, dan klik **App-instelling** > **Aanpassen** > **Leads** > **Pagina-indelingen**. Klik vervolgens op de knop **Nieuw** knop.

1. Kloont uw lay-out en geeft de lay-out een geschikte naam (bijvoorbeeld: Inzichtsindeling van verkoop).

1. Klikken **Opslaan** wanneer gereed.

1. Herhaal deze stappen voor de paginalay-outs Contacten, Opportunity en Accounts.

## Profiel toewijzen aan layout {#assign-profile-to-layout}

1. Ga terug naar de sectie Pagina-indelingen en klik op de knop **Toewijzing paginalayout** knop.

1. Selecteren **Toewijzing bewerken**.

1. Selecteer uw profiel van het Inzicht van de Verkoop van de lijst, dan selecteer uw lay-out van het inzicht van de Verkoop van de &quot;Uitgezochte Indeling van de Pagina&quot;drop-down.

1. Klikken **Opslaan** wanneer gereed.

1. Herhaal deze stappen voor de paginalay-outs Contacten, Opportunity en Accounts.

## Overige wijzigingen {#other-changes}

Hier zijn een paar andere plaatsen waar de voorwerpen van het Inzicht van de Verkoop zouden kunnen verschijnen. U moet ze rechtstreeks verwijderen omdat u geen profielen kunt gebruiken om de toegang te beperken tot:

* De knoppen Verkoopinzicht verwijderen uit de zoekindelingen voor contactpersonen, leads en accounts
* De kolommen van het Inzicht van de Verkoop van Contact en Leidingslijsten verwijderen
