---
description: Personen toevoegen aan of verwijderen uit uw campagne voor dynamiek - Marketo Docs - Productdocumentatie
title: Voeg of verwijder Mensen van uw Campagne van de Dynamiek toe
exl-id: 4fea2f7c-0655-4816-8640-76878f760b6e
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '320'
ht-degree: 0%

---

# Personen toevoegen aan of verwijderen uit uw campagne voor dynamiek {#add-or-remove-people-from-your-dynamics-campaign}

## Toevoegen aan dynamicampagne {#add-to-dynamics-campaign}

Deze stroomstap kan in de Slimme Campagnes van Marketo worden gebruikt om mensen als lood of contacten in een campagne van Microsoft toe te voegen. Als de lead nog niet bestaat in Dynamics, wordt deze automatisch gesynchroniseerd en toegevoegd aan de campagne.

>[!NOTE]
>
>Deze flowactie is alleen beschikbaar voor triggercampagnes.

Zoek en selecteer in uw slimme campagne de campagne Dynamics waaraan u uw mensen wilt toevoegen.

![](assets/add-or-remove-people-from-your-dynamics-campaign-1.png)

>[!NOTE]
>
>Als u geen campagne van de Dynamiek in de campagnemijst kunt zien:
>
>* Zorg ervoor dat de campagnecSync functioneel is
>* De campagne is niet actief in Microsoft Dynamics


Het systeem leidt automatisch tot een campagne-specifieke statische marketing Lijst, elk voor lood en contacten, om de persoon aan toe te voegen. Het is een eenmalige actie en eens voor verdere syncs aan de campagne, wordt de zelfde Lijst van de Marketing gebruikt. De naamgevingsstandaard die wordt gebruikt voor de statische naam van de Marketing List is `Mkto-leads-<uniqueID>` voor leads en `Mkto-contacts-<uniqueID>` voor contactpersonen.

Het koppelen van deze door Marketo gegenereerde marketinglijsten aan andere campagnes kan leiden tot verwarrend gedrag. Bijvoorbeeld: het toevoegen aan één campagne zou ook leiden tot een uitbreiding van de tweede campagne . Ook het loskoppelen van de door Marketo gegenereerde Marketing List van de Campagne in Dynamics wordt niet aanbevolen.

## Verwijderen uit dynamicampagne {#remove-from-dynamics-campaign}

Deze stroomstap kan in de Slimme Campagnes van Marketo worden gebruikt om mensen uit een campagne van Microsoft te verwijderen. Dit verwijdert slechts die lood uit een Campagne die eerder aan de Campagne door de stroomactie &quot;aan de Campagne van Microsoft&quot;zijn toegevoegd.

>[!NOTE]
>
>Deze flowactie is alleen beschikbaar voor triggercampagnes.

Zoek en selecteer in uw slimme campagne de campagne Dynamica waaruit u uw mensen wilt verwijderen.

![](assets/add-or-remove-people-from-your-dynamics-campaign-2.png)

>[!NOTE]
>
>Als u geen campagne van de Dynamiek in de campagnemijst ziet:
>
>* Zorg ervoor dat de campagnecSync functioneel is
>* De campagne is niet actief in Microsoft Dynamics

