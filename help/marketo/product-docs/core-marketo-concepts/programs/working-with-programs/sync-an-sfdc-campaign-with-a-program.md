---
unique-page-id: 1147154
description: Een SFDC-campagne synchroniseren met een programma - Marketo Docs - Productdocumentatie
title: Een SFDC-campagne synchroniseren met een programma
exl-id: b95be580-c960-4a76-9d43-c7f624f43d03
source-git-commit: 8781c6cf2e64543809fe697e75ae6884969a4e40
workflow-type: tm+mt
source-wordcount: '176'
ht-degree: 0%

---

# Een SFDC-campagne synchroniseren met een programma {#sync-an-sfdc-campaign-with-a-program}

Met Marketo kunt u uw programma&#39;s synchroniseren met Salesforce-campagnes om dezelfde lijst met personen in beide systemen bij te houden, inclusief hun status. Laten we beginnen!

>[!PREREQUISITES]
>
>U moet [Salesforce-campagnecorrectie inschakelen](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync.md) eerst.

>[!CAUTION]
>
>Bij het synchroniseren van een SFDC-campagne met een Marketo-programma worden de geïmpliceerde SFDC-acties (bijv. toevoegen aan SFDC-campagne, synchroniseren met SFDC) uitgeschakeld voor onderliggende campagnes van het programma.

1. Ga naar **Marketingactiviteiten**.

   ![](assets/login-marketing-activities-1.png)

1. Selecteer uw programma.

   ![](assets/image2015-7-22-8-3a47-3a28.png)

1. Klikken **Programmaacties** selecteert u vervolgens **Salesforce Campaign Sync**.

   ![](assets/image2015-7-22-8-3a48-3a5.png)

1. Selecteren **Nieuw maken** of kies een bestaande Salesforce-campagne.

   >[!TIP]
   >
   >Als u een bestaande Salesforce-campagne selecteert, moet u [in overeenstemming zijn met de status van het programma van de Salesforce-campagne en het Marketo-programma](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/how-to-match-program-statuses-and-salesforce-campaign-statuses-prior-to-sync.md).

1. Voer een naam in voor de nieuwe campagne en klik op **Opslaan**.

   ![](assets/image2015-7-22-8-3a57-3a19.png)

1. Nu kunt u de gegevens voor het synchroniseren van de campagne verifiëren in de overzichtspagina van het programma.

   ![](assets/image2015-7-22-8-3a59-3a33.png)

   Uitstekend! Alle statuswijzigingen van programma&#39;s in Marketo worden nu gesynchroniseerd met de SFDC-campagne en andersom.
