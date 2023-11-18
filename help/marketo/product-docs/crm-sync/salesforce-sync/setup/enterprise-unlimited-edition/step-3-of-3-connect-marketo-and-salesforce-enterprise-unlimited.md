---
unique-page-id: 2360366
description: Stap 3 van 3 - Connect Marketo en Salesforce (Enterprise/Unlimited) - Marketo Docs - Productdocumentatie
title: Stap 3 van 3 - Connect Marketo en Salesforce (Enterprise/Onbeperkt)
exl-id: ef74bc53-9dc9-43c7-a9aa-565463fdd2e5
feature: Salesforce Integration
source-git-commit: 4045f262889d06304111288d30da893529396e81
workflow-type: tm+mt
source-wordcount: '435'
ht-degree: 0%

---

# Stap 3 van 3: Connect Marketo en Salesforce (Enterprise/Onbeperkt) {#step-of-connect-marketo-and-salesforce-enterprise-unlimited}

In dit artikel, zult u Marketo Engage aan synchronisatie met uw gevormde instantie vormen Salesforce.

>[!PREREQUISITES]
>
>* [Stap 1 van 3: Voeg Marketo-velden toe aan Salesforce (Enterprise/Onbeperkt)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-1-of-3-add-marketo-fields-to-salesforce-enterprise-unlimited.md){target="_blank"}
>* [Stap 2 van 3: Een Salesforce-gebruiker voor Marketo maken (Enterprise/Onbeperkt)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md){target="_blank"}

## Synchronisatie van beveiligingstoken voor gebruiker ophalen {#retrieve-sync-user-security-token}

>[!TIP]
>
>Als u al een beveiligingstoken hebt, gaat u rechtstreeks door om Gebruikersreferenties synchroniseren en kudos in te stellen ter voorbereiding.

1. Meld u aan bij Salesforce met de Marketo Sync-gebruiker, klik op de naam van de synchronisatiegebruiker en klik vervolgens op **[!UICONTROL My Settings]**.

   ![](assets/image2015-6-12-9-3a12-3a47.png)

1. Typ &quot;reset&quot; en klik op **[!UICONTROL Reset My Security Token]**.

   ![](assets/image2015-6-12-9-3a13-3a39.png)

1. Klik op **[!UICONTROL Reset Security Token]**.

   ![](assets/image2014-12-9-9-3a52-3a50.png)

   De beveiligingstoken wordt per e-mail naar u verzonden.

## Gebruikersreferenties synchroniseren instellen {#set-sync-user-credentials}

1. Ga in Marketo naar **[!UICONTROL Admin]**, selecteert u **[!UICONTROL CRM]** en klik op **Sync met [Salesforce.com](https://Salesforce.com)**

   ![](assets/image2014-12-9-9-3a52-3a58.png)

   >[!NOTE]
   >
   >Zorg ervoor dat u [alle velden verbergen die u niet nodig hebt](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/hide-a-salesforce-field-from-the-marketo-sync.md){target="_blank"} in Marketo van de synchronisatiegebruiker voordat u op **[!UICONTROL Sync Fields]**. Als u op Velden synchroniseren klikt, worden alle velden die de gebruiker kan zien, permanent gemaakt in Marketo en kunnen deze niet worden verwijderd.

1. Ga de geloofsbrieven van de Gebruiker van de Synchronisatie Salesforce in die in deel 2 van de configuratie Salesforce worden gecreeerd ([Professional](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/professional-edition/step-2-of-3-create-a-salesforce-user-for-marketo-professional.md){target="_blank"} or [Enterprise](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md){target="_blank"}) en klik op **[!UICONTROL Sync Fields]** (controle **[!UICONTROL Sandbox]** alleen als u een Marketo-sandbox synchroniseert met een Salesforce-sandbox).

   ![](assets/image2014-12-9-9-3a53-3a8.png)

   >[!CAUTION]
   >
   >Als u een knop Aanmelden bij Salesforce ziet in plaats van de velden Gebruikersnaam/Wachtwoord/Token, is uw Marketo-abonnement ingeschakeld voor OAuth. Gelieve [verwijzen naar dit artikel](/help/marketo/product-docs/crm-sync/salesforce-sync/log-in-using-oauth-2-0.md){target="_blank"}. Zodra de synchronisatie begint met het gebruik van een set Referenties _er is geen omschakeling van de geloofsbrieven van Salesforce of abonnement_. Als u Basisverificatie wilt gebruiken, neemt u contact op met het accountteam van de Adobe (uw accountmanager).

1. Lees de waarschuwing en klik vervolgens op **[!UICONTROL Confirm Credentials]**.

   ![](assets/image2014-12-9-9-3a53-3a16.png)

   >[!CAUTION]
   >
   >Als u over wilt kijken [toewijzingen en aanpassen deze](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/edit-initial-field-mappings.md){target="_blank"}Dat is uw enige kans! Als u eenmaal op Salesforce Sync starten hebt geklikt, is het gelukt.

## Salesforce Sync starten {#start-salesforce-sync}

1. Klikken **[!UICONTROL Start Salesforce Sync]** om de permanente Marketo-Salesforce-synchronisatie te starten.

   ![](assets/image2014-12-9-9-3a53-3a24.png)

   >[!CAUTION]
   >
   >Marketo wordt niet automatisch gededupliceerd bij een Salesforce-synchronisatie of wanneer u handmatig leads invoert.

1. Klik op **[!UICONTROL Start Sync]**.

   ![](assets/image2014-12-9-9-3a53-3a32.png)

   >[!NOTE]
   >
   >De tijd die nodig is om de eerste synchronisatie uit te voeren, is afhankelijk van de grootte en complexiteit van uw database.

## Sync controleren {#verify-sync}

Marketo geeft statusberichten weer voor de Salesforce-synchronisatie in het beheergebied. U kunt controleren of de synchronisatie correct werkt door deze stappen uit te voeren.

1. Klik in Marketo op **[!UICONTROL Admin]** vervolgens **Salesforce**.

   ![](assets/image2014-12-9-9-3a53-3a40.png)

1. De synchronisatiestatus wordt in de rechterbovenhoek weergegeven. Het zal één van drie berichten tonen: **[!UICONTROL Last Synced]**, **[!UICONTROL Sync in Progress]**, of **[!UICONTROL Failed]**.

   ![](assets/image2014-12-9-9-3a53-3a50.png)

   ![](assets/image2014-12-9-9-3a54-3a4.png)

   ![](assets/image2014-12-9-9-3a54-3a35.png)

Je hebt net een van de krachtigste functies van Marketo geconfigureerd, ga je gang!

>[!MORELIKETHIS]
>
>* [Stap 1 van 3: Voeg Marketo-velden toe aan Salesforce (Enterprise/Onbeperkt)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-1-of-3-add-marketo-fields-to-salesforce-enterprise-unlimited.md){target="_blank"}
>* [Stap 2 van 3: Een Salesforce-gebruiker voor Marketo maken (Enterprise/Onbeperkt)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md){target="_blank"}
>* [Marketo Sales Insight Package installeren in Salesforce AppExchange](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md){target="_blank"}
>* [Marketo Sales Insight configureren in Salesforce Enterprise/Onbeperkt](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-enterprise-unlimited.md){target="_blank"}
