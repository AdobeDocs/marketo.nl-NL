---
unique-page-id: 1147154
description: Een SFDC-campagne synchroniseren met een programma - Marketo Docs - Productdocumentatie
title: Een SFDC-campagne synchroniseren met een programma
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '176'
ht-degree: 0%

---


# Een SFDC-campagne synchroniseren met een programma {#sync-an-sfdc-campaign-with-a-program}

Met Marketo kunt u uw programma&#39;s synchroniseren met Salesforce-campagnes om dezelfde lijst met personen in beide systemen bij te houden, inclusief hun status. Laten we beginnen!

>[!PREREQUISITES]
>
>U moet eerst [de campagnecsync](../../../../product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync.md) van Salesforce inschakelen.

>[!CAUTION]
>
>Wanneer een SFDC-campagne wordt gesynchroniseerd met een Marketo-programma, worden de geïmpliceerde SFDC-acties (bijv. toevoegen aan SFDC-campagne, synchroniseren met SFDC) uitgeschakeld voor onderliggende campagnes van het programma.

1. Ga naar **Marketingactiviteiten**.

   ![](assets/login-marketing-activities-1.png)

1. Selecteer uw programma.

   ![](assets/image2015-7-22-8-3a47-3a28.png)

1. Klik **Program Actions**, dan selecteer **Salesforce Campagne Sync**.

   ![](assets/image2015-7-22-8-3a48-3a5.png)

1. Selecteer **Nieuw maken **of kies een bestaande Salesforce-campagne.

   >[!TIP]
   >
   >Als u een bestaande Salesforce-campagne selecteert, moet u [de status van het programma van de Salesforce-campagne en het Marketo-programma](../../../../product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-errors/how-to-match-program-statuses-and-salesforce-campaign-statuses-prior-to-sync.md) aanpassen.

1. Voer een naam in voor de nieuwe campagne en klik op **Opslaan**.

   ![](assets/image2015-7-22-8-3a57-3a19.png)

1. Nu kunt u de gegevens voor het synchroniseren van de campagne verifiëren in de overzichtspagina van het programma.

   ![](assets/image2015-7-22-8-3a59-3a33.png)

   Uitstekend! Alle statuswijzigingen van programma&#39;s in Marketo worden nu gesynchroniseerd met de SFDC-campagne en andersom.

