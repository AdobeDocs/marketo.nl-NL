---
unique-page-id: 1147154
description: Een SFDC-campagne synchroniseren met een programma - Marketo Docs - Productdocumentatie
title: Een SFDC-campagne synchroniseren met een programma
exl-id: b95be580-c960-4a76-9d43-c7f624f43d03
feature: Programs
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '163'
ht-degree: 0%

---

# Een SFDC-campagne synchroniseren met een programma {#sync-an-sfdc-campaign-with-a-program}

Met Marketo Engage kunt u uw programma&#39;s synchroniseren met [!DNL Salesforce] -campagnes om dezelfde lijst met personen op beide systemen bij te houden, inclusief hun status. Laten we beginnen!

>[!PREREQUISITES]
>
>U zult [  [!DNL Salesforce]  campagnecsync ](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync.md){target="_blank"} eerst moeten toelaten.

>[!CAUTION]
>
>Wanneer u een SFDC-campagne synchroniseert met een Marketo Engage-programma, worden de impliciete SFDC-acties (bijv. toevoegen aan SFDC-campagne, synchroniseren met SFDC) uitgeschakeld voor onderliggende campagnes van het programma.

1. Ga naar **[!UICONTROL Marketing Activities]** .

   ![](assets/login-marketing-activities-1.png)

1. Selecteer uw programma.

   ![](assets/image2015-7-22-8-3a47-3a28.png)

1. Klik op **[!UICONTROL Program Actions]** en selecteer vervolgens **[!UICONTROL Salesforce Campaign Sync]** .

   ![](assets/image2015-7-22-8-3a48-3a5.png)

1. Selecteer **[!UICONTROL Create New]** of kies een bestaande [!DNL Salesforce] -campagne.

   >[!TIP]
   >
   >Als u een bestaande [!DNL Salesforce] campagne selecteert, zorg ervoor [ de programmastatussen van de  [!DNL Salesforce]  campagne en het programma van Marketo ](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/how-to-match-program-statuses-and-salesforce-campaign-statuses-prior-to-sync.md){target="_blank"} aanpast.

1. Voer een naam in voor de nieuwe campagne en klik op **[!UICONTROL Save]** .

   ![](assets/image2015-7-22-8-3a57-3a19.png)

1. Nu kunt u de gegevens voor het synchroniseren van de campagne verifiëren in de overzichtspagina van het programma.

   ![](assets/image2015-7-22-8-3a59-3a33.png)

   Uitstekend! Alle statuswijzigingen van programma&#39;s in Marketo worden nu gesynchroniseerd met de SFDC-campagne en andersom.
