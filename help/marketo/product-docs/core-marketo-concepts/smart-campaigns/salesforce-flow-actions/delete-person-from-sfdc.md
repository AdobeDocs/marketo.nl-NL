---
unique-page-id: 1147031
description: Persoon verwijderen uit SFDC - Marketo Docs - Productdocumentatie
title: Persoon verwijderen uit SFDC
exl-id: 8245de35-f374-4241-946e-b4c4b87cc85e
feature: Smart Campaigns, Salesforce Integration
source-git-commit: 4bae0126d6b36720e170bea7b6b973508c855633
workflow-type: tm+mt
source-wordcount: '119'
ht-degree: 0%

---

# Persoon verwijderen uit SFDC {#delete-person-from-sfdc}

Als u een specifieke reeks lood uit Salesforce moet verwijderen maar hen als mensen in Marketo Engage verlaat, kunt u de Persoon van de Schrapping van SFDC stroomactie gebruiken.

>[!NOTE]
>
>Alleen beschikbaar bij integratie met Salesforce.

1. Klik in de database op de persoon die u uit Salesforce wilt verwijderen. Klik vervolgens op **[!UICONTROL Person Actions]** en selecteert u **[!DNL Salesforce]**.

   ![](assets/person-actions-salesforce.png)

1. Selecteren **[!UICONTROL Delete Person from SFDC]**.

   ![](assets/delete-person-from-sfdc.png)

1. Zorg ervoor dat de **[!UICONTROL Delete in Marketo]** instellen is **[!UICONTROL false]** en klik vervolgens op **[!UICONTROL Run Now]**.

   ![](assets/run-action-delete-lead-from-sfdc.png)

   Na de looppas van de stroomstap, zal uw persoon niet meer een lood in Salesforce zijn maar zal in Marketo blijven.

   >[!CAUTION]
   >
   >Als u **[!UICONTROL Delete in Marketo]** tot **[!UICONTROL true]** en de mensen uit Marketo en de leiders van Salesforce verwijderen, ze zijn voorgoed verdwenen. Dit kan niet ongedaan worden gemaakt.
