---
unique-page-id: 1147031
description: Persoon verwijderen uit SFDC - Marketo Docs - Productdocumentatie
title: Persoon verwijderen uit SFDC
exl-id: 8245de35-f374-4241-946e-b4c4b87cc85e
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '135'
ht-degree: 0%

---

# Persoon verwijderen uit SFDC {#delete-person-from-sfdc}

Als u een specifieke reeks leads uit Salesforce moet verwijderen maar deze als personen in Marketo wilt behouden, kunt u de actie Person verwijderen uit SFDC-flow gebruiken.

>[!NOTE]
>
>Alleen beschikbaar bij integratie met Salesforce.

1. Klik in de database op de persoon die u uit Salesforce wilt verwijderen. Klik vervolgens op **Handelingen personen** en selecteer **Salesforce**.

   ![](assets/person-actions-salesforce.png)

1. Selecteer **Persoon verwijderen uit SFDC**.

   ![](assets/delete-person-from-sfdc.png)

1. Zorg ervoor dat de **Delete-instelling in Marketo** **false** is en klik vervolgens op **Nu uitvoeren**.

   ![](assets/run-action-delete-lead-from-sfdc.png)

   Na de looppas van de stroomstap, zal uw persoon niet meer een lood in Salesforce zijn maar zal in Marketo blijven.

   >[!CAUTION]
   >
   >Als u **Delete in Marketo** aan **true** plaatst en de mensen uit Marketo en de lood van Salesforce schrapt, zijn zij voorgoed gegaan. Dit kan niet ongedaan worden gemaakt.
