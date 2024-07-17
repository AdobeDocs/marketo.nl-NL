---
unique-page-id: 1147031
description: Persoon verwijderen uit SFDC - Marketo Docs - Productdocumentatie
title: Persoon verwijderen uit SFDC
exl-id: 8245de35-f374-4241-946e-b4c4b87cc85e
feature: Smart Campaigns, Salesforce Integration
source-git-commit: 934bb5f197f801e48cf8e7554335eb2d07289037
workflow-type: tm+mt
source-wordcount: '119'
ht-degree: 0%

---

# Persoon verwijderen uit SFDC {#delete-person-from-sfdc}

Als u een specifieke reeks lood uit Salesforce moet verwijderen maar hen als mensen in Marketo Engage verlaat, kunt u de Persoon van de Schrapping van SFDC stroomactie gebruiken.

>[!NOTE]
>
>Alleen beschikbaar bij integratie met Salesforce.

1. Klik in de database op de persoon die u uit Salesforce wilt verwijderen. Klik vervolgens op **[!UICONTROL Person Actions]** en selecteer **[!DNL Salesforce]** .

   ![](assets/delete-person-from-sfdc-1.png)

1. Selecteer **[!UICONTROL Delete Person from SFDC]** .

   ![](assets/delete-person-from-sfdc-2.png)

1. Zorg dat de instelling **[!UICONTROL Delete in Marketo]** **[!UICONTROL false]** is en klik vervolgens op **[!UICONTROL Run Now]** .

   ![](assets/delete-person-from-sfdc-3.png)

   Na de looppas van de stroomstap, zal uw persoon niet meer een lood in Salesforce zijn maar zal in Marketo blijven.

   >[!CAUTION]
   >
   >Als u **[!UICONTROL Delete in Marketo]** instelt op **[!UICONTROL true]** en de mensen uit Marketo en de leads van Salesforce verwijdert, zijn ze voor altijd verdwenen. Dit kan niet ongedaan worden gemaakt.
