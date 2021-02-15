---
unique-page-id: 2360366
description: Stap 3 van 3 -Connect Marketo en Salesforce (Enterprise/Unlimited) - Marketo Docs - Productdocumentatie
title: Stap 3 van 3 - de Marketo en Salesforce van Connect (Onderneming/Onbeperkt)
translation-type: tm+mt
source-git-commit: 6ae882dddda220f7067babbe5a057eec82601abf
workflow-type: tm+mt
source-wordcount: '405'
ht-degree: 0%

---


# Stap 3 van 3: Connect Marketo en Salesforce (Enterprise/Unlimited) {#step-of-connect-marketo-and-salesforce-enterprise-unlimited}

In dit artikel, zult u Marketo aan synchronisatie met uw gevormde instantie vormen Salesforce.

>[!PREREQUISITES]
>
>* [Stap 1 van 3: Marketo-velden toevoegen aan Salesforce (Enterprise/Onbeperkt)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-1-of-3-add-marketo-fields-to-salesforce-enterprise-unlimited.md)
>* [Stap 2 van 3: Een Salesforce-gebruiker voor markeren maken (Enterprise/Onbeperkt)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md)


## Symbool {#retrieve-sync-user-security-token} voor gebruikersbeveiliging synchroniseren ophalen

>[!TIP]
>
>Als u al een beveiligingstoken hebt, gaat u rechtstreeks door om Gebruikersreferenties synchroniseren en kudos in te stellen ter voorbereiding.

1. Meld u aan bij Salesforce met de functie Marketo Sync User en klik op de naam van de synchronisatiegebruiker en vervolgens op **Mijn instellingen**.

   ![](assets/image2015-6-12-9-3a12-3a47.png)

1. Typ &quot;reset&quot; in de snelle zoekactie en klik op **Mijn beveiligingstoken** herstellen.

   ![](assets/image2015-6-12-9-3a13-3a39.png)

1. Klik **Beveiligingstoken opnieuw instellen**.

   ![](assets/image2014-12-9-9-3a52-3a50.png)

   De beveiligingstoken wordt per e-mail naar u verzonden.

## Gebruikersreferenties synchroniseren instellen {#set-sync-user-credentials}

1. Ga in Marketo naar **Admin**, selecteer **CRM** en klik **Synchroniseren met [Salesforce.com](https://Salesforce.com)**

   ![](assets/image2014-12-9-9-3a52-3a58.png)

   >[!NOTE]
   >
   >Zorg dat u [alle velden die u niet nodig hebt ](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-field-sync/hide-a-salesforce-field-from-the-marketo-sync.md) in Marketo voor de synchronisatiegebruiker verbergt voordat u **Velden synchroniseren** klikt. Als u op Velden synchroniseren klikt, worden alle velden die de gebruiker kan zien, permanent gemaakt in Marketo en kunnen deze niet worden verwijderd.

1. Voer de Salesforce Sync gebruikersgegevens in die zijn gemaakt in deel 2 van de Salesforce-configuratie ([Professional](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/professional-edition/step-2-of-3-create-a-salesforce-user-for-marketo-professional.md), [Enterprise](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md)) en klik op **Velden synchroniseren**.

   ![](assets/image2014-12-9-9-3a53-3a8.png)

   >[!NOTE]
   >
   >Schakel **Sandbox** in als u een Marketo-sandbox synchroniseert met een Salesforce-sandbox.

1. Lees de waarschuwing en klik vervolgens op **Credentials bevestigen**.

   ![](assets/image2014-12-9-9-3a53-3a16.png)

   >[!CAUTION]
   >
   >Als u over [afbeeldingen wilt kijken en hen ](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/edit-initial-field-mappings.md) wilt aanpassen, is dit uw enige kans om dit te doen! Als u eenmaal op Salesforce Sync starten hebt geklikt, is het gelukt.

## Salesforce Sync starten {#start-salesforce-sync}

1. Klik **Begin Salesforce Sync** om met blijvende Marketo-Salesforce synchronisatie te beginnen.

   ![](assets/image2014-12-9-9-3a53-3a24.png)

   >[!CAUTION]
   >
   >Marketo wordt niet automatisch gededupliceerd bij een Salesforce-synchronisatie of wanneer u handmatig leads invoert.

1. Klik **Sync starten**.

   ![](assets/image2014-12-9-9-3a53-3a32.png)

   >[!NOTE]
   >
   >De tijd die nodig is om de eerste synchronisatie uit te voeren, is afhankelijk van de grootte en complexiteit van de database.

## Synchronisatie {#verify-sync} controleren

Marketo bevat statusberichten voor de Salesforce-synchronisatie in het beheergebied. U kunt controleren of de synchronisatie correct werkt door deze stappen uit te voeren.

1. Klik in Marketo op **Admin** en **Salesforce**.

   ![](assets/image2014-12-9-9-3a53-3a40.png)

1. De synchronisatiestatus wordt in de rechterbovenhoek weergegeven. Het zal één van drie berichten tonen: **Laatste gesynchroniseerd**, **Synchronisatie in uitvoering** of **Mislukt**.

   ![](assets/image2014-12-9-9-3a53-3a50.png)

   ![](assets/image2014-12-9-9-3a54-3a4.png)

   ![](assets/image2014-12-9-9-3a54-3a35.png)

Wow, je hebt net een van de krachtigste functies van Marketo geconfigureerd, ga je!

>[!MORELIKETHIS]
>
>* [Stap 1 van 3: Marketo-velden toevoegen aan Salesforce (Enterprise/Onbeperkt)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-1-of-3-add-marketo-fields-to-salesforce-enterprise-unlimited.md)
>* [Stap 2 van 3: Een Salesforce-gebruiker voor markeren maken (Enterprise/Onbeperkt)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md)
>* [Pakket met marketinggegevens in Salesforce AppExchange installeren](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md)
>* [Marktverkoopinzicht configureren in Salesforce Enterprise/Onbeperkt](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-enterprise-unlimited.md)

