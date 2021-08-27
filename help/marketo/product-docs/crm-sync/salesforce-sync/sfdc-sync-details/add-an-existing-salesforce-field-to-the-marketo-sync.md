---
unique-page-id: 4719308
description: Een bestaand Salesforce-veld toevoegen aan de Marketo Sync - Marketo Docs - Productdocumentatie
title: Een bestaand Salesforce-veld toevoegen aan Marketo Sync
exl-id: 6030aedd-9c4b-411f-89c7-f35fd39b0066
source-git-commit: 7376804bda915d7ff25cdc50cb78a6686bd36882
workflow-type: tm+mt
source-wordcount: '158'
ht-degree: 0%

---

# Een bestaand Salesforce-veld toevoegen aan Marketo Sync {#add-an-existing-salesforce-field-to-the-marketo-sync}

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

Gewoonlijk worden nieuwe aangepaste velden in Salesforce automatisch gesynchroniseerd met Marketo. Als dat niet het geval is, zijn de velden mogelijk niet zichtbaar voor de Marketo Sync gebruiker. Zo kunt u dit oplossen.

1. Klik uw naam en selecteer dan **Opstelling**.

   ![](assets/image2015-6-30-14-3a20-3a6.png)

1. Typ **profiel** in de linkerzoekbalk en klik op **Profielen** onder **Gebruikers beheren**.

   ![](assets/image2015-6-30-14-3a20-3a52.png)

1. Klik op het gebruikersprofiel synchroniseren.

   ![](assets/image2015-6-30-14-3a23-3a41.png)

1. Onder **Veld-Vlakke Veiligheid** sectie, klik **Mening** naast het voorwerp dat het gebied bevat.

   ![](assets/image2015-6-30-14-3a23-3a59.png)

1. Klik **Bewerken**.

   ![](assets/image2015-6-30-14-3a24-3a28.png)

1. Schakel het selectievakje **Visible** in voor het veld dat u aan de synchronisatie wilt toevoegen en klik op **Save**.

   ![](assets/image2015-6-30-14-3a24-3a49.png)

   Zoet! Bij de volgende synchronisatiecyclus zal Marketo het veld zien en de magie starten.

   >[!NOTE]
   >
   > Als het veld al waarden heeft in Salesforce, worden deze waarden pas gesynchroniseerd met Marketo als de volgende record wordt bijgewerkt.
