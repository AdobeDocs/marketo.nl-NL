---
unique-page-id: 3571800
description: Stap 3 van 3 -Connect Marketo en Salesforce (Professional) - Marketo Docs - Productdocumentatie
title: Stap 3 van 3 - Connect Marketo en Salesforce (Professional)
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '406'
ht-degree: 0%

---


# Stap 3 van 3: Connect Marketo en Salesforce (Professional) {#step-of-connect-marketo-and-salesforce-professional}

In dit artikel, zult u Marketo aan synchronisatie met uw gevormde instantie vormen Salesforce.

>[!PREREQUISITES]
>
>* [Stap 1 van 3: Marketo-velden toevoegen aan Salesforce (Professional)](step-1-of-3-add-marketo-fields-to-salesforce-professional.md)
>* [Stap 2 van 3: Een Salesforce-gebruiker voor markeertekens maken (Professional)](step-2-of-3-create-a-salesforce-user-for-marketo-professional.md)

>



## Symbool {#retrieve-sync-user-security-token} voor gebruikersbeveiliging synchroniseren ophalen

>[!TIP]
>
>Als u al een beveiligingstoken hebt, gaat u rechtstreeks door om Gebruikersreferenties synchroniseren en kudos in te stellen ter voorbereiding.

1. Meld u aan bij Salesforce met de functie Marketo Sync User en klik op de naam van de synchronisatiegebruiker en vervolgens op **Mijn instellingen**.

   ![](assets/image2015-5-21-14-3a11-3a17.png)

1. Typ &quot;reset&quot; in de zoekbalk Nav en klik op **Mijn beveiligingstoken opnieuw instellen**.

   ![](assets/image2014-12-9-9-3a52-3a42.png)

1. Klik **Beveiligingstoken opnieuw instellen**.

   ![](assets/image2015-5-21-14-3a13-3a5.png)

   De beveiligingstoken wordt per e-mail naar u verzonden.

## Gebruikersreferenties synchroniseren instellen {#set-sync-user-credentials}

1. Ga in Marketo naar **Admin**, selecteer **CRM** en klik **Synchroniseren met [Salesforce.com](http://Salesforce.com)**

   ![](assets/image2014-12-9-9-3a52-3a58.png)

   >[!NOTE]
   >
   >**Herinnering**
   >
   >
   >Zorg dat u [alle velden die u niet nodig hebt ](../../../../../product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-field-sync/hide-a-salesforce-field-from-the-marketo-sync.md) in Marketo voor de synchronisatiegebruiker verbergt voordat u **Velden synchroniseren** klikt. Als u op Velden synchroniseren klikt, worden alle velden die de gebruiker kan zien, permanent gemaakt in Marketo en kunnen deze niet worden verwijderd.

1. Voer de Salesforce Sync gebruikersgegevens in die zijn gemaakt in deel 2 van de Salesforce-configuratie ([Professional](https://community.marketo.com/MarketoArticle?id=kA050000000LJ3QCAW), [Enterprise](https://community.marketo.com/MarketoArticle?id=kA050000000LIwKCAW)) en klik op **Velden synchroniseren**.

   ![](assets/image2014-12-9-9-3a53-3a8.png)

   >[!NOTE]
   >
   >Schakel **Sandbox** in als u een Marketo-sandbox synchroniseert met een Salesforce-sandbox.

1. Lees de waarschuwing en klik vervolgens op **Credentials bevestigen**.

   ![](assets/image2014-12-9-9-3a53-3a16.png)

   >[!CAUTION]
   >
   >Als u over [afbeeldingen wilt kijken en hen ](../../../../../product-docs/crm-sync/salesforce-sync/setup/optional-steps/edit-initial-field-mappings.md) wilt aanpassen, is dit uw enige kans om dit te doen! Als u eenmaal op Salesforce Sync starten hebt geklikt, is het gelukt.

## Salesforce Sync starten {#start-salesforce-sync}

1. Klik **Begin Salesforce Sync** om met blijvende Marketo-Salesforce synchronisatie te beginnen.

   ![](assets/image2014-12-9-9-3a53-3a24.png)

   >[!CAUTION]
   >
   >Marketo wordt niet automatisch gededupliceerd bij een Salesforce-synchronisatie of wanneer u handmatig leads invoert.

1. Klik **START SYNC**.

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

>[!NOTE]
>
>**Verwante artikelen**
>
>* [Pakket met marketinggegevens in Salesforce AppExchange installeren](../../../../../product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md)
>* [Marktverkoopinzicht configureren in Salesforce Professional Edition](../../../../../product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-professional-edition.md)
>* [Optionele stappen](http://docs.marketo.com/display/docs/optional+steps)

>



