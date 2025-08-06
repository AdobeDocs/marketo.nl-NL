---
unique-page-id: 1147034
description: Toevoegen aan SFDC-campagne - Marketo Docs - Productdocumentatie
title: Toevoegen aan SFDC-campagne
exl-id: a5e14cc7-fd83-4a2c-aacb-e515669c9d21
feature: Smart Campaigns, Salesforce Integration
source-git-commit: 21bcdc10fe1f3517612efe0f8e2adaf2f4411a70
workflow-type: tm+mt
source-wordcount: '173'
ht-degree: 0%

---

# Toevoegen aan SFDC-campagne {#add-to-sfdc-campaign}

Deze flowstap kan worden gebruikt in Marketo Engage-campagnes of als een enkele flowstap om mensen als leads toe te voegen in een Salesforce-campagne. Als de lead nog niet in Salesforce bestaat, wordt deze automatisch gesynchroniseerd en met de opgegeven status toegevoegd aan de campagne.

>[!NOTE]
>
>Alleen beschikbaar bij integratie met [!DNL Salesforce] .

![](assets/add-to-sfdc-campaign-1.png)

## Gebruik {#usage}

1. Zoek en selecteer de [!DNL Salesforce] -campagne waaraan u uw leads wilt toevoegen.

   ![](assets/add-to-sfdc-campaign-2.png)

   >[!TIP]
   >
   >Als je geen Salesforce-campagne kunt zien in de campagnemelijst:
   >
   > 1. Zorg ervoor de [ campagnecsync ](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync.md){target="_blank"} wordt toegelaten.
   > 1. Bevestig dat uw [ Gebruiker van de Synchronisatie van Marketo ](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md){target="_blank"} a [ Marketing Gebruiker ](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync/make-marketo-sync-user-a-marketing-user.md){target="_blank"} in Salesforce is.

   >[!TIP]
   >
   >U kunt de campagne van Salesforce [ Mijn Tokens ](/help/marketo/product-docs/core-marketo-concepts/programs/tokens/managing-my-tokens.md){target="_blank"} gebruiken om programma het klonen gemakkelijker te maken.

1. Selecteer de status van het campagnerelid van [!DNL Salesforce] dat u wilt toewijzen aan leads wanneer deze worden toegevoegd.

   ![](assets/add-to-sfdc-campaign-3.png)

   >[!CAUTION]
   >
   >Als een persoon al een leidinggevend lid is van de Salesforce-campagne, worden deze overgeslagen en wordt hun status NIET bijgewerkt. U kunt [ gebruiken verandert hun status in een campagne van SFDC ](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/change-status-in-sfdc-campaign.md){target="_blank"} in plaats daarvan.
