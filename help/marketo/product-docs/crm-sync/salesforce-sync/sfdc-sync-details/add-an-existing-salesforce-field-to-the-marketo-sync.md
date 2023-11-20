---
unique-page-id: 4719308
description: Een bestaand Salesforce-veld toevoegen aan de Marketo Sync - Marketo Docs - Productdocumentatie
title: Een bestaand Salesforce-veld toevoegen aan Marketo Sync
exl-id: 6030aedd-9c4b-411f-89c7-f35fd39b0066
feature: Salesforce Integration
source-git-commit: 0087a5e88b8bd9601875f68a2e7cadeebdb5d682
workflow-type: tm+mt
source-wordcount: '148'
ht-degree: 0%

---

# Een bestaand Salesforce-veld toevoegen aan Marketo Sync {#add-an-existing-salesforce-field-to-the-marketo-sync}

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

Gewoonlijk worden nieuwe aangepaste velden in Salesforce automatisch gesynchroniseerd met Marketo Engage. Als dat niet het geval is, zijn de velden mogelijk niet zichtbaar voor de Marketo Sync gebruiker. Zo kunt u dit oplossen.

1. Klik op uw naam en selecteer vervolgens **[!UICONTROL Setup]**.

   ![](assets/add-an-existing-salesforce-field-to-the-marketo-sync-1.png)

1. Voer &quot;profiel&quot; in op de linkerzoekbalk en klik op **[!UICONTROL Profiles]** krachtens **[!UICONTROL Manage Users]**.

   ![](assets/add-an-existing-salesforce-field-to-the-marketo-sync-2.png)

1. Klik op het gebruikersprofiel synchroniseren.

   ![](assets/add-an-existing-salesforce-field-to-the-marketo-sync-3.png)

1. Onder de **[!UICONTROL Field-Level Security]** sectie, klikken **[!UICONTROL View]** naast het object dat het veld bevat.

   ![](assets/add-an-existing-salesforce-field-to-the-marketo-sync-4.png)

1. Klik op **[!UICONTROL Edit]**.

   ![](assets/add-an-existing-salesforce-field-to-the-marketo-sync-5.png)

1. Controleer de **[!UICONTROL Visible]** selectievakje voor het veld dat u aan de synchronisatie wilt toevoegen en klik op **[!UICONTROL Save]**.

   ![](assets/add-an-existing-salesforce-field-to-the-marketo-sync-6.png)

   Bij de volgende synchronisatiecyclus zal Marketo het veld zien en de magie starten.

   >[!NOTE]
   >
   > Als het veld al waarden heeft in Salesforce, worden deze waarden pas gesynchroniseerd met Marketo als de volgende record wordt bijgewerkt.
