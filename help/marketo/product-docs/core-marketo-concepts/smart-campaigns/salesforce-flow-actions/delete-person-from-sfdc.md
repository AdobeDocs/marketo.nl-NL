---
unique-page-id: 1147031
description: Persoon verwijderen uit SFDC - Marketo Docs - Productdocumentatie
title: Persoon verwijderen uit SFDC
exl-id: 8245de35-f374-4241-946e-b4c4b87cc85e
feature: Smart Campaigns, Salesforce Integration
source-git-commit: d20a9bb584f69282eefae3704ce4be2179b29d0b
workflow-type: tm+mt
source-wordcount: '135'
ht-degree: 0%

---

# Persoon verwijderen uit SFDC {#delete-person-from-sfdc}

Als u een specifieke reeks leads uit Salesforce moet verwijderen maar deze als personen in Marketo wilt behouden, kunt u de actie Person verwijderen uit SFDC-flow gebruiken.

>[!NOTE]
>
>Alleen beschikbaar bij integratie met Salesforce.

1. Klik in de database op de persoon die u uit Salesforce wilt verwijderen. Klik vervolgens op **Persoonlijke handelingen** en selecteert u **Salesforce**.

   ![](assets/person-actions-salesforce.png)

1. Selecteren **Persoon verwijderen uit SFDC**.

   ![](assets/delete-person-from-sfdc.png)

1. Zorg ervoor dat de **Verwijderen in Marketo** instellen is **false** en klik vervolgens op **Nu uitvoeren**.

   ![](assets/run-action-delete-lead-from-sfdc.png)

   Na de looppas van de stroomstap, zal uw persoon niet meer een lood in Salesforce zijn maar zal in Marketo blijven.

   >[!CAUTION]
   >
   >Als u **Verwijderen in Marketo** tot **true** en de mensen uit Marketo en de leiders van Salesforce verwijderen, ze zijn voorgoed verdwenen. Dit kan niet ongedaan worden gemaakt.
