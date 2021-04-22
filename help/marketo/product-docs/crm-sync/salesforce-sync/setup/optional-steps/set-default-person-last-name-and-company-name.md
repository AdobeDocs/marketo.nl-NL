---
unique-page-id: 4719291
description: Standaardnaam persoon en bedrijfsnaam instellen - Marketo Docs - Productdocumentatie
title: Achternaam en bedrijfsnaam voor standaardpersoon instellen
exl-id: 0216fb41-adf0-4ccf-be22-c064e90be65a
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '142'
ht-degree: 0%

---

# Standaardnaam persoon en bedrijfsnaam {#set-default-person-last-name-and-company-name} instellen

Salesforce vereist (minimale) achternaam en bedrijfsnaam voor de bijbehorende leads en contactpersonen. Onvolledige records worden niet gesynchroniseerd met Salesforce. Als u deelrecords wilt synchroniseren, moet u standaardwaarden instellen voor Marketo die u met Salesforce wilt gebruiken.

1. Ga naar **Admin** en klik **Salesforce**.

   ![](assets/image2014-12-9-13-3a41-3a58.png)

1. Klik **Synchronisatieopties bewerken**.

   ![](assets/image2014-12-9-13-3a42-3a6.png)

1. Voer een **achternaam standaardpersoon** en een **Standaardpersonenbedrijf** in en klik vervolgens op **Opslaan**.

   ![](assets/sync-options-hands.png)

   >[!NOTE]
   >
   >Marketo wijst alleen een standaardwaarde toe als de record voor het eerst wordt gesynchroniseerd met Salesforce en alleen als een van de vereiste velden leeg is.

En dat is dat! Elke keer dat een persoon een achternaam en/of bedrijfsnaam mist, voegt Marketo de standaardwaarde toe bij het synchroniseren van de record.
