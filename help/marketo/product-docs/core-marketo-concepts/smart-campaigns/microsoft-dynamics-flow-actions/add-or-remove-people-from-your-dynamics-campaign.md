---
description: Personen toevoegen aan of verwijderen uit uw campagne voor dynamiek - Marketo Docs - Productdocumentatie
title: Voeg of verwijder Mensen van uw Campagne van de Dynamiek toe
exl-id: 4fea2f7c-0655-4816-8640-76878f760b6e
feature: Smart Campaigns, Microsoft Dynamics
source-git-commit: 2eeb7ea7fd43ba75a3c802a91ce07c90dc8abd91
workflow-type: tm+mt
source-wordcount: '317'
ht-degree: 0%

---

# Voeg of verwijder Mensen van uw Campagne van de Dynamiek toe {#add-or-remove-people-from-your-dynamics-campaign}

## Toevoegen aan dynamicampagne {#add-to-dynamics-campaign}

Deze stroomstap kan in Marketo Engage Slimme Campagnes worden gebruikt om mensen als lood of contacten in een campagne van Microsoft toe te voegen. Als de lead nog niet bestaat in Dynamics, wordt deze automatisch gesynchroniseerd en toegevoegd aan de campagne.

>[!NOTE]
>
>Deze flowactie is alleen beschikbaar voor triggercampagnes.

Zoek en selecteer in uw slimme campagne de campagne Dynamiek waaraan u uw mensen wilt toevoegen.

![](assets/add-or-remove-people-from-your-dynamics-campaign-1.png)

>[!NOTE]
>
>Als u geen campagne van de Dynamiek in de campagnemijst kunt zien:
>
>* Zorg ervoor dat de campagnecSync functioneel is
>* De campagne is niet actief in [!DNL Microsoft Dynamics]

Het systeem leidt automatisch tot een campagne-specifieke statische marketing Lijst, elk voor lood en contacten, om de persoon aan toe te voegen. Het is een eenmalige actie en eens voor verdere syncs aan de campagne, wordt de zelfde Lijst van de Marketing gebruikt. De naamgevingsstandaard die wordt gebruikt voor de naam van de statische marketinglijst is `Mkto-leads-<uniqueID>` voor leads en `Mkto-contacts-<uniqueID>` voor contacten.

Het koppelen van deze door Marketo gegenereerde marketinglijsten aan andere campagnes kan leiden tot verwarrend gedrag. Bijvoorbeeld: het toevoegen aan één campagne zou er ook toe leiden dat de tweede campagne wordt uitgebreid. Ook het loskoppelen van de door Marketo gegenereerde Marketing List van de Campagne in Dynamics wordt niet aanbevolen.

## Verwijderen uit dynamicampagne {#remove-from-dynamics-campaign}

Deze flowstap kan worden gebruikt in Marketo Smart Campaigns om mensen uit een Microsoft-campagne te verwijderen. Hierdoor worden alleen die leads uit een campagne verwijderd die eerder aan de campagne zijn toegevoegd via de flowactie &quot;Toegevoegd aan Microsoft-campagne&quot;.

>[!NOTE]
>
>Deze flowactie is alleen beschikbaar voor triggercampagnes.

Zoek en selecteer in uw slimme campagne de campagne Dynamica waaruit u uw personen wilt verwijderen.

![](assets/add-or-remove-people-from-your-dynamics-campaign-2.png)

>[!NOTE]
>
>Als u geen campagne van de Dynamiek in de campagnemijst ziet:
>
>* Zorg ervoor dat de campagnecSync functioneel is
>* De campagne is niet actief in [!DNL Microsoft Dynamics]
