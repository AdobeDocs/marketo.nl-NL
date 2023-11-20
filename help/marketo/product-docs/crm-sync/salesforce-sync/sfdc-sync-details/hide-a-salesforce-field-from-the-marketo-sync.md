---
unique-page-id: 4719306
description: Een Salesforce-veld verbergen in de Marketo Sync - Marketo Docs - Productdocumentatie
title: Een Salesforce-veld verbergen voor Marketo-synchronisatie
exl-id: 5d7229f0-43b0-4232-93ed-a9ca52ace401
feature: Salesforce Integration
source-git-commit: 0087a5e88b8bd9601875f68a2e7cadeebdb5d682
workflow-type: tm+mt
source-wordcount: '157'
ht-degree: 1%

---

# Een Salesforce-veld verbergen voor Marketo-synchronisatie {#hide-a-salesforce-field-from-the-marketo-sync}

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

Niet elk veld in Salesforce is nuttig voor marketing. U kunt de synchronisatieprestaties optimaliseren door alleen velden op te nemen die u nodig hebt. Zo kunt u een veld verbergen voor Marketo Engage.

1. Klik op het menu Naam en selecteer **[!UICONTROL Setup]**.

   ![](assets/image2015-6-30-15-3a11-3a23.png)

1. Voer &quot;profielen&quot; in op de zoekbalk en klik op **[!UICONTROL Profiles]** krachtens **[!UICONTROL Manage Users]**.

   ![](assets/image2015-6-30-15-3a12-3a46.png)

1. Klik op het gebruikersprofiel synchroniseren.

   ![](assets/image2015-6-30-15-3a17-3a38.png)

1. Onder de **[!UICONTROL Field-Level Security]** sectie, klikken **[!UICONTROL View]** naast het object dat het doelveld bevat.

   ![](assets/image2015-6-30-15-3a24-3a32.png)

1. Klik op **[!UICONTROL Edit]**.

   ![](assets/image2015-6-30-15-3a25-3a42.png)

1. Schakel het selectievakje **[!UICONTROL Visible]** selectievakje naast het veld dat u wilt verbergen. Klik op **[!UICONTROL Save]**.

   ![](assets/image2015-6-30-15-3a27-3a16.png)

   >[!NOTE]
   >
   >Als het veld dat u in Salesforce verbergt al met Marketo is gesynchroniseerd, moet u het ook in Marketo verbergen als u het niet wilt gebruiken.

   Dat is het! Dit veld wordt niet meer weergegeven in Marketo nadat de volgende synchronisatie is voltooid.

   >[!MORELIKETHIS]
   >
   >[Een veld verbergen en verbergen opheffen](/help/marketo/product-docs/administration/field-management/hide-and-unhide-a-field.md){target="_blank"}
