---
unique-page-id: 4719308
description: Een bestaand Salesforce-veld toevoegen aan de Marketo Sync - Marketo Docs - Productdocumentatie
title: Een bestaand Salesforce-veld toevoegen aan Marketo Sync
exl-id: 6030aedd-9c4b-411f-89c7-f35fd39b0066
source-git-commit: 81bc90bcccc8073511c9f331471c0cda9f4147cb
workflow-type: tm+mt
source-wordcount: '158'
ht-degree: 0%

---

# Een bestaand Salesforce-veld toevoegen aan Marketo Sync {#add-an-existing-salesforce-field-to-the-marketo-sync}

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

Gewoonlijk worden nieuwe aangepaste velden in Salesforce automatisch gesynchroniseerd met Marketo. Als dat niet het geval is, zijn de velden mogelijk niet zichtbaar voor de Marketo Sync gebruiker. Zo kunt u dit oplossen.

1. Klik op uw naam en selecteer vervolgens **Instellen**.

   ![](assets/add-an-existing-salesforce-field-to-the-marketo-sync-1.png)

1. Enter **profiel** in de linkerzoekbalk en klik op **Profielen** krachtens **Gebruikers beheren**.

   ![](assets/add-an-existing-salesforce-field-to-the-marketo-sync-2.png)

1. Klik op het gebruikersprofiel synchroniseren.

   ![](assets/add-an-existing-salesforce-field-to-the-marketo-sync-3.png)

1. Onder de **Beveiliging op veldniveau** sectie, klikt u op **Weergave** naast het object dat het veld bevat.

   ![](assets/add-an-existing-salesforce-field-to-the-marketo-sync-4.png)

1. Klikken **Bewerken**.

   ![](assets/add-an-existing-salesforce-field-to-the-marketo-sync-5.png)

1. Controleer de **Zichtbaar** Schakel het selectievakje in voor het veld dat u aan de synchronisatie wilt toevoegen en klik op **Opslaan**.

   ![](assets/add-an-existing-salesforce-field-to-the-marketo-sync-6.png)

   Zoet! Bij de volgende synchronisatiecyclus zal Marketo het veld zien en de magie starten.

   >[!NOTE]
   >
   > Als het veld al waarden heeft in Salesforce, worden deze waarden pas gesynchroniseerd met Marketo als de volgende record wordt bijgewerkt.
