---
description: Het Inzicht van de Verkoop van de Opstelling voor uw Team - Marketo Docs - de Documentatie van het Product
title: Het Inzicht van de Verkoop van de Opstelling voor uw Team
translation-type: tm+mt
source-git-commit: ed9399396c82a3b2fb93c83ffdaa1dc7b0827306
workflow-type: tm+mt
source-wordcount: '439'
ht-degree: 0%

---


# Het Inzicht van de Verkoop van de Opstelling voor uw Team {#setting-up-sales-insight-for-your-team}

Hier is hoe te om een profiel met toegang tot het Inzicht van de Verkoop te creëren terwijl het verwijderen van toegang voor uw andere profielen. Dit is voor gebruikers die het [AppExchange-pakket van het Inzicht van de Verkoop](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md) reeds hebben geïnstalleerd.

## Nieuw profiel maken voor verkoopinzicht {#create-a-new-profile-for-sales-insight}

Als u een specifiek profiel voor uw gebruikers van het Inzicht van de Verkoop hebt, kunt u deze stap overslaan.

1. Ga in Salesforce naar de pagina Setup.

1. Zoek naar profielen in Snelle Vondst en selecteer **Profiel** optie.

1. Klik op de knop **Nieuw profiel** boven aan de pagina.

1. Kies een profiel om te klonen en geef het een naam (bijv. Gebruiker van het Inzicht van de Verkoop).

1. Klik **Opslaan** wanneer gereed.

## Machtigingen voor verkoopinzicht toevoegen {#add-sales-insight-permissions}

1. Ga terug naar uw profiellijst.

1. Klik op de koppeling **Bewerken** voor het nieuwe profiel dat u net hebt gemaakt (of een ander bestaand profiel dat u toegang tot het verkoopinzicht wilt geven).

1. Op de bewerkingspagina moet u een aantal instellingen wijzigen.

   **Voor profielen die toegang hebben tot Verkoopoverzicht**:

   * Schakel in Aangepaste toepassingsinstellingen de optie Marketo in om de toepassing Marketo zichtbaar te maken
   * Wijzig in Tabinstellingen de tabbladen Markeren in Standaard ingeschakeld
   * In de Toestemmingen van de Objecten van de Douane, controleer Gelezen, creeer, geef uit, en schrap op Config van het Inzicht van de Verkoop van de Verkoop van Marketo (als de gebruiker toegang tot config montages zou moeten hebben - typisch gebruikt voor Admins).

   **Voor profielen die geen toegang tot Verkoopinzicht** hebben:

   * Schakel in Aangepaste toepassingsinstellingen de optie Marketo uit om de app Marketo te verbergen
   * Wijzig in Tabinstellingen de tabbladen Markeren in Tabblad Verborgen
   * Schakel in Aangepaste objectmachtigingen de optie Lezen, Maken, Bewerken en Verwijderen uit bij Configuratie Marktinformatie


1. Klik **Opslaan** wanneer gereed.

## Layout maken voor verkoopinzicht {#create-layout-for-sales-insight}

1. Ga naar de pagina van de Opstelling, dan klik **App Opstelling** > **Customize** > **Leads** > **Paginalay-outs**. Klik vervolgens op de knop **Nieuw**.

1. Kloont uw lay-out en geeft de lay-out een geschikte naam (bijvoorbeeld: Inzichtsindeling van verkoop).

1. Klik **Opslaan** wanneer gereed.

1. Herhaal deze stappen voor de paginalay-outs Contacten, Opportunity en Accounts.

## Profiel toewijzen aan layout {#assign-profile-to-layout}

1. Ga terug naar de sectie van de Lay-outs van de Pagina en klik **de knoop van de Lay-out van de Pagina**.

1. Selecteer **Toewijzing bewerken**.

1. Selecteer uw profiel van het Inzicht van de Verkoop van de lijst, dan selecteer uw lay-out van het inzicht van de Verkoop van de &quot;Uitgezochte Indeling van de Pagina&quot;drop-down.

1. Klik **Opslaan** wanneer gereed.

1. Herhaal deze stappen voor de paginalay-outs Contacten, Opportunity en Accounts.

## Overige wijzigingen {#other-changes}

Hier zijn een paar andere plaatsen waar de voorwerpen van het Inzicht van de Verkoop zouden kunnen verschijnen. U moet ze rechtstreeks verwijderen omdat u geen profielen kunt gebruiken om de toegang te beperken tot:

* De knoppen Verkoopinzicht verwijderen uit de zoekindelingen voor contactpersonen, leads en accounts
* De kolommen van het Inzicht van de Verkoop van Contact en Leidingslijsten verwijderen
