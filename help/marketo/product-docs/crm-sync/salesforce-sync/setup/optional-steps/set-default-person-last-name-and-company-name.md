---
unique-page-id: 4719291
description: Leer hoe u de achternaam en bedrijfsnaam van de standaardpersoon instelt voor Salesforce-synchronisatie. Gebruik Beheer- en synchronisatieopties om gegevens zo gedeeltelijk te synchroniseren met standaardwaarden.
title: Achternaam en bedrijfsnaam voor standaardpersoon instellen
exl-id: 0216fb41-adf0-4ccf-be22-c064e90be65a
feature: Salesforce Integration
source-git-commit: 2b29f05a27f847184e0968442012d443e9e0597d
workflow-type: tm+mt
source-wordcount: '141'
ht-degree: 0%

---

# Achternaam en bedrijfsnaam voor standaardpersoon instellen {#set-default-person-last-name-and-company-name}

[!DNL Salesforce] vereist (minimale) achternaam en bedrijfsnaam voor de bijbehorende leads en contactpersonen. Onvolledige records worden niet gesynchroniseerd met [!DNL Salesforce] . Als u partiële records wilt synchroniseren, moet u standaardwaarden instellen voor Marketo om te gebruiken met [!DNL Salesforce] .

1. Ga naar **[!UICONTROL Admin]** en klik op **[!DNL Salesforce]** .

   ![](assets/image2014-12-9-13-3a41-3a58.png)

1. Klik op **[!UICONTROL Edit Sync Options]**.

   ![](assets/image2014-12-9-13-3a42-3a6.png)

1. Voer een **[!UICONTROL Default person last name]** en een **[!UICONTROL Default person company]** in en klik vervolgens op **[!UICONTROL Save]** .

   ![](assets/sync-options-hands.png)

   >[!NOTE]
   >
   >Marketo Engage wijst alleen een standaardwaarde toe wanneer de record voor het eerst wordt gesynchroniseerd met Salesforce en alleen als een van de vereiste velden leeg is.

En dat is dat! Elke keer dat een persoon een achternaam en/of bedrijfsnaam mist, voegt Marketo de standaardwaarde toe bij het synchroniseren van de record.
