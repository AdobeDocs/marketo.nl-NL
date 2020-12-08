---
unique-page-id: 4719291
description: Standaardnaam persoon en bedrijfsnaam instellen - Marketo Docs - Productdocumentatie
title: Achternaam en bedrijfsnaam voor standaardpersoon instellen
translation-type: tm+mt
source-git-commit: 00887ea53e395bea3a11fd28e0ac98b085ef6ed8
workflow-type: tm+mt
source-wordcount: '142'
ht-degree: 0%

---


# Achternaam en bedrijfsnaam voor standaardpersoon instellen {#set-default-person-last-name-and-company-name}

Salesforce vereist (minimale) achternaam en bedrijfsnaam voor de bijbehorende leads en contactpersonen. Onvolledige records worden niet gesynchroniseerd met Salesforce. Als u gedeeltelijke verslagen wilt synchroniseren, moet u standaardwaarden voor Marketo voor gebruik met Salesforce plaatsen.

1. Ga naar **Admin** en klik op **Salesforce**.

   ![](assets/image2014-12-9-13-3a41-3a58.png)

1. Klik op **Synchronisatieopties** bewerken.

   ![](assets/image2014-12-9-13-3a42-3a6.png)

1. Ga een achternaam **van de** Standaardpersoon en een **Standaard ****persoonbedrijf** in dan klik **sparen**.

   ![](assets/sync-options-hands.png)

   >[!NOTE]
   >
   >Marketo wijst alleen een standaardwaarde toe wanneer de record eerst wordt gesynchroniseerd met Salesforce en alleen als een van de vereiste velden leeg is.

En dat is dat! Telkens wanneer een persoon een achternaam en/of bedrijfsnaam mist, zal Marketo de standaardwaarde toevoegen aangezien het het verslag over synchroniseert.
