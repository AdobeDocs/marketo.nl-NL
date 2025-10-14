---
unique-page-id: 2360366
description: Stap 3 van 3 - Connect Marketo en Salesforce (Enterprise/Unlimited) - Marketo Docs - Productdocumentatie
title: Stap 3 van 3 - Connect Marketo en Salesforce (Enterprise/Onbeperkt)
exl-id: ef74bc53-9dc9-43c7-a9aa-565463fdd2e5
feature: Salesforce Integration
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '423'
ht-degree: 0%

---

# Stap 3 van 3: Connect Marketo en [!DNL Salesforce] (Enterprise/Unlimited) {#step-of-connect-marketo-and-salesforce-enterprise-unlimited}

In dit artikel configureert u Marketo voor synchronisatie met de geconfigureerde [!DNL Salesforce] -instantie.

>[!PREREQUISITES]
>
>* [&#x200B; Stap 1 van 3: Voeg de Gebieden van Marketo aan  [!DNL Salesforce]  toe (Onderneming/Onbeperkt) &#x200B;](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-1-of-3-add-marketo-fields-to-salesforce-enterprise-unlimited.md)
>* [&#x200B; Stap 2 van 3: Creeer a [!DNL Salesforce]  Gebruiker voor Marketo (Onderneming/Onbeperkt) &#x200B;](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md)

## Synchronisatie van beveiligingstoken voor gebruiker ophalen {#retrieve-sync-user-security-token}

>[!TIP]
>
>Als u al een beveiligingstoken hebt, gaat u rechtstreeks door om Gebruikersreferenties synchroniseren en kudos in te stellen ter voorbereiding.

1. Meld u aan bij [!DNL Salesforce] met de Marketo Sync-gebruiker, klik op de naam van de synchronisatiegebruiker en vervolgens op **[!UICONTROL My Settings]** .

   ![](assets/image2015-6-12-9-3a12-3a47.png)

1. Typ &quot;reset&quot; in de snelle zoekopdracht en klik op **[!UICONTROL Reset My Security Token]** .

   ![](assets/image2015-6-12-9-3a13-3a39.png)

1. Klik op **[!UICONTROL Reset Security Token]**.

   ![](assets/image2014-12-9-9-3a52-3a50.png)

   De beveiligingstoken wordt per e-mail naar u verzonden.

## Gebruikersreferenties synchroniseren instellen {#set-sync-user-credentials}

1. In Marketo, ga **[!UICONTROL Admin]**, uitgezochte **CRM**, en klik **[!UICONTROL Sync with Salesforce.com]**

   ![](assets/image2014-12-9-9-3a52-3a58.png)

   >[!NOTE]
   >
   >Ben zeker om [&#x200B; alle gebieden te verbergen u niet &#x200B;](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/hide-a-salesforce-field-from-the-marketo-sync.md) in Marketo van de synchronisatiegebruiker alvorens **[!UICONTROL Sync Fields]** vereist te klikken. Als u op [!UICONTROL Sync Fields] klikt, worden alle velden weergegeven die de gebruiker kan zien, permanent gemaakt in Marketo en kunnen deze niet meer worden verwijderd.

1. Ga de [!DNL Salesforce] geloofsbrieven van de Gebruiker van de Synchronisatie in deel 2 van de [!DNL Salesforce] configuratie ([&#x200B; Beroeps &#x200B;](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/professional-edition/step-2-of-3-create-a-salesforce-user-for-marketo-professional.md) of [&#x200B; Onderneming &#x200B;](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md)) en klik **[!UICONTROL Sync Fields]** (controle **[!UICONTROL Sandbox]** slechts als u een zandbak van Marketo aan a [!DNL Salesforce] Sandbox synchroniseert).

   ![](assets/image2014-12-9-9-3a53-3a8.png)

   >[!CAUTION]
   >
   >Als u de knop Aanmelden bij [!DNL Salesforce] ziet in plaats van de velden Gebruikersnaam/Wachtwoord/Token, is uw Marketo-abonnement ingeschakeld voor OAuth. Gelieve te verwijzen [&#x200B; naar dit artikel &#x200B;](/help/marketo/product-docs/crm-sync/salesforce-sync/log-in-using-oauth-2-0.md). Zodra de synchronisatie begint gebruikend een reeks Geloofsbrieven, **is er geen omschakeling van [!DNL Salesforce] geloofsbrieven of abonnement**. Als u Basisauthentificatie wilt gebruiken, contacteer uw Manager van het Succes van de Klant.

1. Lees de waarschuwing en klik op **[!UICONTROL Confirm Credentials]** .

   ![](assets/image2014-12-9-9-3a53-3a16.png)

   >[!CAUTION]
   >
   >Als u over de [&#x200B; afbeeldingen wilt kijken en hen &#x200B;](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/edit-initial-field-mappings.md) aanpassen, is dit uw enige kans om dit te doen! Zodra u klikt [!UICONTROL Start  Salesforce Sync], is het gedaan.

## [!DNL Salesforce] Sync starten {#start-salesforce-sync}

1. Klik op **[!UICONTROL Start  Salesforce Sync]** om de permanente Marketo- [!DNL Salesforce] -synchronisatie te starten.

   ![](assets/image2014-12-9-9-3a53-3a24.png)

   >[!CAUTION]
   >
   >Marketo wordt niet automatisch gededupliceerd via een [!DNL Salesforce] -sync of wanneer u handmatig leads invoert.

1. Klik op **[!UICONTROL Start Sync]**.

   ![](assets/image2014-12-9-9-3a53-3a32.png)

   >[!NOTE]
   >
   >De tijd die nodig is om de eerste synchronisatie uit te voeren, is afhankelijk van de grootte en complexiteit van uw database.

## Sync controleren {#verify-sync}

Marketo geeft statusberichten weer voor de synchronisatie van [!DNL Salesforce] in het beheergebied. U kunt controleren of de synchronisatie correct werkt door deze stappen uit te voeren.

1. Klik in Marketo op **[!UICONTROL Admin]** en vervolgens op **[!UICONTROL Salesforce]** .

   ![](assets/image2014-12-9-9-3a53-3a40.png)

1. De synchronisatiestatus wordt in de rechterbovenhoek weergegeven. Er worden drie berichten weergegeven: **[!UICONTROL Last Synced]**, **[!UICONTROL Sync in Progress]** of **[!UICONTROL Failed]** .

   ![](assets/image2014-12-9-9-3a53-3a50.png)

   ![](assets/image2014-12-9-9-3a54-3a4.png)

   ![](assets/image2014-12-9-9-3a54-3a35.png)

Je hebt net een van de krachtigste functies van Marketo geconfigureerd, ga je gang!

>[!MORELIKETHIS]
>
>* [&#x200B; Stap 1 van 3: Voeg de Gebieden van Marketo aan  [!DNL Salesforce]  toe (Onderneming/Onbeperkt) &#x200B;](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-1-of-3-add-marketo-fields-to-salesforce-enterprise-unlimited.md)
>* [&#x200B; Stap 2 van 3: Creeer a [!DNL Salesforce]  Gebruiker voor Marketo (Onderneming/Onbeperkt) &#x200B;](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md)
>* [&#x200B; installeer het Pakket van Insight van de Verkoop van Marketo in  [!DNL Salesforce]  AppExchange &#x200B;](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md)
>* [&#x200B; Vorm Insight van de Verkoop van Marketo in  [!DNL Salesforce]  Onderneming/Onbeperkt &#x200B;](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-enterprise-unlimited.md)
