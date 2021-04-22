---
unique-page-id: 1147034
description: Toevoegen aan SFDC-campagne - Marketo Docs - Productdocumentatie
title: Toevoegen aan SFDC-campagne
exl-id: a5e14cc7-fd83-4a2c-aacb-e515669c9d21
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '176'
ht-degree: 0%

---

# Toevoegen aan SFDC-campagne {#add-to-sfdc-campaign}

>[!NOTE]
>
>Alleen beschikbaar bij integratie met Salesforce.

## Overzicht {#overview}

Deze flowstap kan worden gebruikt in Marketo-campagnes of als een enkele flowstap om mensen toe te voegen als leider in een Salesforce-campagne. Als de lead nog niet bestaat in Salesforce, wordt deze automatisch gesynchroniseerd en met de opgegeven status toegevoegd aan de campagne.

![](assets/image2014-9-22-15-3a43-3a36.png)

## Gebruik {#usage}

1. Zoek en selecteer de Salesforce-campagne waaraan u uw leads wilt toevoegen.

   ![](assets/image2014-9-22-15-3a43-3a45.png)

   >[!TIP]
   >
   >Als u geen Salesforce-campagne kunt zien in de lijst Campagne:
   >
   >  1. Zorg ervoor [campagnecsync wordt toegelaten](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync.md).
   >  1. Bevestig dat uw [Marketo Sync User](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md) een [Marketing User](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync/make-marketo-sync-user-a-marketing-user.md) in Salesforce is.


   >[!TIP]
   >
   >U kunt de campagne van Salesforce [Mijn Tokens](/help/marketo/product-docs/core-marketo-concepts/programs/tokens/managing-my-tokens.md) gebruiken om programma het klonen gemakkelijker te maken.

1. Selecteer de status van het lid van de Salesforce-campagne dat u wilt toewijzen aan leads wanneer deze worden toegevoegd.

   ![](assets/image2014-9-22-15-3a45-3a2.png)

   >[!CAUTION]
   >
   >Als een persoon al een leidinggevend lid is van de Salesforce-campagne, worden ze overgeslagen en wordt hun status NIET bijgewerkt. U kunt [hun status in een campagne gebruiken SFDC](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/change-status-in-sfdc-campaign.md) in plaats daarvan veranderen.
