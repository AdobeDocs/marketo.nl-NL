---
unique-page-id: 4719291
description: Standaardnaam persoon en bedrijfsnaam instellen - Marketo Docs - Productdocumentatie
title: Achternaam en bedrijfsnaam voor standaardpersoon instellen
translation-type: tm+mt
source-git-commit: 2b5ccd7220557a5e966d33436d0f0d2a65e4589d
workflow-type: tm+mt
source-wordcount: '142'
ht-degree: 0%

---


# Standaardnaam persoon en bedrijfsnaam {#set-default-person-last-name-and-company-name} instellen

Salesforce vereist (minimale) achternaam en bedrijfsnaam voor de bijbehorende leads en contactpersonen. Onvolledige records worden niet gesynchroniseerd met Salesforce. Als u gedeeltelijke verslagen wilt synchroniseren, moet u standaardwaarden voor Marketo voor gebruik met Salesforce plaatsen.

1. Ga naar **Admin** en klik **Salesforce**.

   ![](assets/image2014-12-9-13-3a41-3a58.png)

1. Klik **Synchronisatieopties bewerken**.

   ![](assets/image2014-12-9-13-3a42-3a6.png)

1. Voer een **achternaam standaardpersoon** en een **Standaardpersonenbedrijf** in en klik vervolgens op **Opslaan**.

   ![](assets/sync-options-hands.png)

   >[!NOTE]
   >
   >Marketo wijst alleen een standaardwaarde toe wanneer de record eerst wordt gesynchroniseerd met Salesforce en alleen als een van de vereiste velden leeg is.

En dat is dat! Telkens wanneer een persoon een achternaam en/of bedrijfsnaam mist, zal Marketo de standaardwaarde toevoegen aangezien het het verslag over synchroniseert.
