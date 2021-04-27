---
unique-page-id: 2360366
description: Stap 3 van 3 - Connect Marketo en Salesforce (Enterprise/Unlimited) - Marketo Docs - Productdocumentatie
title: Stap 3 van 3 - Connect Marketo en Salesforce (Enterprise/Onbeperkt)
exl-id: ef74bc53-9dc9-43c7-a9aa-565463fdd2e5
translation-type: tm+mt
source-git-commit: d81a4a3caa12c5ec642afadf9328b3825bde6fed
workflow-type: tm+mt
source-wordcount: '466'
ht-degree: 0%

---

# Stap 3 van 3: Connect Marketo en Salesforce (Enterprise/Unlimited) {#step-of-connect-marketo-and-salesforce-enterprise-unlimited}

In dit artikel configureert u Marketo voor synchronisatie met de geconfigureerde Salesforce-instantie.

>[!PREREQUISITES]
>
>* [Stap 1 van 3: Marketo-velden toevoegen aan Salesforce (Enterprise/Onbeperkt)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-1-of-3-add-marketo-fields-to-salesforce-enterprise-unlimited.md)
>* [Stap 2 van 3: Een Salesforce-gebruiker voor Marketo maken (Enterprise/Onbeperkt)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md)


## Symbool {#retrieve-sync-user-security-token} voor gebruikersbeveiliging synchroniseren ophalen

>[!TIP]
>
>Als u al een beveiligingstoken hebt, gaat u rechtstreeks door om Gebruikersreferenties synchroniseren en kudos in te stellen ter voorbereiding.

1. Meld u aan bij Salesforce met de Marketo Sync-gebruiker, klik op de naam van de synchronisatiegebruiker en **Mijn instellingen**.

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
   >Zorg dat u [alle velden die u niet nodig hebt ](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-field-sync/hide-a-salesforce-field-from-the-marketo-sync.md) in Marketo verbergt voor de synchronisatiegebruiker voordat u op **Velden synchroniseren** klikt. Nadat u op Velden synchroniseren hebt geklikt, worden alle velden weergegeven die de gebruiker kan zien, permanent gemaakt in Marketo en kunnen deze niet worden verwijderd.

1. Voer de Salesforce Sync gebruikersgegevens in die zijn gemaakt in deel 2 van de Salesforce-configuratie ([Professional](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/professional-edition/step-2-of-3-create-a-salesforce-user-for-marketo-professional.md) of [Enterprise](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md)) en klik op **Velden synchroniseren** (schakel **Sandbox** alleen in als u een Marketo-sandbox synchroniseert met een Salesforce-sandbox).

   ![](assets/image2014-12-9-9-3a53-3a8.png)

   >[!CAUTION]
   >
   >Als u een knop Aanmelden bij Salesforce ziet in plaats van de velden Gebruikersnaam/Wachtwoord/Token, is uw Marketo-abonnement ingeschakeld voor OAuth. [raadpleeg dit artikel](/help/marketo/product-docs/crm-sync/salesforce-sync/log-in-using-oauth-2-0.md). Zodra de synchronisatie begint gebruikend een reeks Referenties, **is er geen omschakeling van geloofsbrieven Salesforce of abonnement**. Als u Basisauthentificatie wilt gebruiken, contacteer uw Manager van het Succes van de Klant.

1. Lees de waarschuwing en klik vervolgens op **Credentials bevestigen**.

   ![](assets/image2014-12-9-9-3a53-3a16.png)

   >[!CAUTION]
   >
   >Als u over [afbeeldingen wilt kijken en hen ](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/edit-initial-field-mappings.md) wilt aanpassen, is dit uw enige kans om dit te doen! Als u eenmaal op Salesforce Sync starten hebt geklikt, is het gelukt.

## Salesforce Sync starten {#start-salesforce-sync}

1. Klik **Start Salesforce Sync** om de permanente Marketo-Salesforce synchronisatie te starten.

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

Marketo geeft statusberichten weer voor de Salesforce-synchronisatie in het beheergebied. U kunt controleren of de synchronisatie correct werkt door deze stappen uit te voeren.

1. Klik in Marketo op **Admin** en vervolgens **Salesforce**.

   ![](assets/image2014-12-9-9-3a53-3a40.png)

1. De synchronisatiestatus wordt in de rechterbovenhoek weergegeven. Het zal één van drie berichten tonen: **Laatste gesynchroniseerd**, **Synchronisatie in uitvoering** of **Mislukt**.

   ![](assets/image2014-12-9-9-3a53-3a50.png)

   ![](assets/image2014-12-9-9-3a54-3a4.png)

   ![](assets/image2014-12-9-9-3a54-3a35.png)

Wow, je hebt net een van de krachtigste functies van Marketo geconfigureerd, hè!

>[!MORELIKETHIS]
>
>* [Stap 1 van 3: Marketo-velden toevoegen aan Salesforce (Enterprise/Onbeperkt)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-1-of-3-add-marketo-fields-to-salesforce-enterprise-unlimited.md)
>* [Stap 2 van 3: Een Salesforce-gebruiker voor Marketo maken (Enterprise/Onbeperkt)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md)
>* [Marketo Sales Insight Package installeren in Salesforce AppExchange](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md)
>* [Marketo Sales Insight configureren in Salesforce Enterprise/Onbeperkt](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-enterprise-unlimited.md)

