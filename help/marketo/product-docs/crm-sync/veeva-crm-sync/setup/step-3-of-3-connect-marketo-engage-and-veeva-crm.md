---
description: Stap 3 van 3 - Connect Marketo Engage and Veeva CRM - Marketo Docs - Productdocumentatie
title: Stap 3 van 3 - Connect Marketo Engage en Veeva CRM
exl-id: aff91540-1d9d-448c-aae9-e6fa92a8ae01
feature: Veeva CRM
source-git-commit: 0087a5e88b8bd9601875f68a2e7cadeebdb5d682
workflow-type: tm+mt
source-wordcount: '314'
ht-degree: 1%

---

# Stap 3 van 3: Connect Marketo Engage en Veeva CRM {#step-3-of-3-connect-marketo-engage-and-veeva-crm}

In dit artikel, zult u Marketo Engage aan synchronisatie met uw gevormde instantie vormen van CRM. **Je ziet Salesforce in sommige pop-ups** Veeva CRM is gebouwd op het Salesforce-platform.

>[!PREREQUISITES]
>
>* [Stap 1 van 3: Marketo-velden toevoegen aan Veeva](/help/marketo/product-docs/crm-sync/veeva-crm-sync/setup/step-1-of-3-add-marketo-fields-to-veeva-crm.md){target="_blank"}
>* [Stap 2 van 3: Een Veeva-gebruiker voor Marketo maken](/help/marketo/product-docs/crm-sync/veeva-crm-sync/setup/step-2-of-3-create-a-veeva-crm-user-for-marketo-engage.md){target="_blank"}

>[!IMPORTANT]
>
>Er kan slechts één Marketo-instantie tegelijk worden verbonden met een Veeva CRM-instantie.

## Verbinden met Veeva CRM met OAuth {#connect-to-veeva-crm-using-oauth}

1. Klik in Marketo op **[!UICONTROL Admin]**. Selecteren **[!UICONTROL CRM]** en klik op **[!UICONTROL Sync with Veeva]**.

   ![](assets/step-3-of-3-connect-marketo-engage-1.png)

   >[!NOTE]
   >
   >Zorg ervoor dat u [alle velden verbergen die u niet nodig hebt](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/hide-a-salesforce-field-from-the-marketo-sync.md){target="_blank"} in Marketo door de synchronisatiegebruiker voordat u op Velden synchroniseren klikt. Als u op Velden synchroniseren klikt, worden alle velden die de gebruiker kan zien, permanent gemaakt in Marketo en kunnen deze niet worden verwijderd.

1. Klik op **[!UICONTROL Login with Veeva]**.

   ![](assets/step-3-of-3-connect-marketo-engage-2.png)

   >[!NOTE]
   >
   >Schakel Sandbox in als u een Marketo-sandbox synchroniseert met een Veeva CRM-sandbox.

1. Klik op **[!UICONTROL Confirm Credentials]**.

   ![](assets/step-3-of-3-connect-marketo-engage-3.png)

1. Er wordt een pop-up weergegeven met de aanmeldingspagina van Salesforce. Voer uw gebruikersgegevens voor &quot;Marketo Sync User&quot; in en klik op **[!UICONTROL Log In]**.

   ![](assets/step-3-of-3-connect-marketo-engage-4.png)

1. Voer de verificatiecode in die je via e-mail hebt ontvangen (verzonden door Salesforce) en klik op **[!UICONTROL Verify]**.

   ![](assets/step-3-of-3-connect-marketo-engage-5.png)

1. Na succesvolle verificatie wordt de toegangspagina weergegeven met het verzoek om toegang. Klik op **[!UICONTROL Allow]**.

   ![](assets/step-3-of-3-connect-marketo-engage-6.png)

1. Over een paar minuten wordt een pop-up weergegeven in Marketo Engae. Klik op **[!UICONTROL Confirm Credentials]**.

   ![](assets/step-3-of-3-connect-marketo-engage-7.png)

## Veeva-synchronisatie starten {#start-veeva-sync}

1. Klikken **[!UICONTROL Start Veeva Sync]** beginnen met de permanente Marketo-Veeva CRM-synchronisatie.

   ![](assets/step-3-of-3-connect-marketo-engage-8.png)

   >[!CAUTION]
   >
   >Marketo dedupliceert niet automatisch naar een Veeva CRM-synchronisatie of wanneer u handmatig leads invoert.

1. Klik op **[!UICONTROL Start Sync]**.

   ![](assets/step-3-of-3-connect-marketo-engage-9.png)

>[!NOTE]
>
>De tijd die nodig is om de eerste synchronisatie uit te voeren, is afhankelijk van de grootte en complexiteit van uw database.

## Sync controleren {#verify-sync}

Marketo geeft statusberichten weer voor de synchronisatie van Veeva CRM in het beheergebied. U kunt controleren of de synchronisatie correct werkt door deze stappen uit te voeren.

1. Klik in Marketo op **[!UICONTROL Admin]** vervolgens **[!UICONTROL Veeva]**.

   ![](assets/step-3-of-3-connect-marketo-engage-10.png)

1. De synchronisatiestatus wordt in de rechterbovenhoek weergegeven. Er wordt een van de volgende drie berichten weergegeven: Laatste synchronisatie, Synchronisatie bezig of Mislukt.

>[!MORELIKETHIS]
>
>[Aangepaste objecten configureren](/help/marketo/product-docs/crm-sync/veeva-crm-sync/sync-details/custom-object-sync.md){target="_blank"}
