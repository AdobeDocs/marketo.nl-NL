---
unique-page-id: 1147034
description: Toevoegen aan SFDC-campagne - Marketo Docs - Productdocumentatie
title: Toevoegen aan SFDC-campagne
translation-type: tm+mt
source-git-commit: 00887ea53e395bea3a11fd28e0ac98b085ef6ed8
workflow-type: tm+mt
source-wordcount: '227'
ht-degree: 0%

---


# Toevoegen aan SFDC-campagne {#add-to-sfdc-campaign}

>[!NOTE]
>
>**FYI**
>
>Marketo is nu bezig met het standaardiseren van de taal voor alle abonnementen, dus u ziet mogelijk leads/leads in uw abonnement en personen/personen in docs.marketo.com. Deze termen betekenen hetzelfde. het heeft geen invloed op de instructies van het artikel . Er zijn nog enkele andere veranderingen. [Meer](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)informatie.

>[!NOTE]
>
>Alleen beschikbaar bij integratie met Salesforce.

## Overzicht {#overview}

Deze flowstap kan worden gebruikt in Marketo-campagnes of als een enkele flowstap om mensen als leider toe te voegen in een Salesforce-campagne. Als de lead nog niet bestaat in Salesforce, wordt deze automatisch gesynchroniseerd en met de opgegeven status toegevoegd aan de campagne.

![](assets/image2014-9-22-15-3a43-3a36.png)

## Gebruik {#usage}

1. Zoek en selecteer de Salesforce-campagne waaraan u uw leads wilt toevoegen.

   ![](assets/image2014-9-22-15-3a43-3a45.png)

   >[!TIP]
   >
   >Als u geen Salesforce-campagne kunt zien in de lijst Campagne:
   >
   >    
   >    
   >    1. Zorg ervoor dat de [campagnecsync is ingeschakeld](../../../../product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync.md).
   >    1. Bevestig dat uw gebruiker [](../../../../product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md) Marketo Sync een [marketinggebruiker](../../../../product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync/make-marketo-sync-user-a-marketing-user.md) in Salesforce is.


   >[!TIP]
   >
   >Met de Salesforce-campagne [My Tokens](../../../../product-docs/core-marketo-concepts/programs/tokens/managing-my-tokens.md) kunt u het klonen van programma&#39;s eenvoudiger maken.

1. Selecteer de status van het lid van de Salesforce-campagne dat u wilt toewijzen aan leads wanneer deze worden toegevoegd.

   ![](assets/image2014-9-22-15-3a45-3a2.png)

   >[!CAUTION]
   >
   >Als een persoon al een leidinggevend lid is van de Salesforce-campagne, worden ze overgeslagen en wordt hun status NIET bijgewerkt. In plaats daarvan kunt u hun status [wijzigen in een SFDC-campagne](change-status-in-sfdc-campaign.md) .

