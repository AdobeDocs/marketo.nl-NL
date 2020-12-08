---
unique-page-id: 1147021
description: Eigenaar wijzigen - Marketo Docs - Productdocumentatie
title: Eigenaar wijzigen
translation-type: tm+mt
source-git-commit: f27e2bac90570f9f795dc6bdd5fcf208c446be14
workflow-type: tm+mt
source-wordcount: '154'
ht-degree: 0%

---


# Eigenaar wijzigen {#change-owner}

Als u bestaande mensen hebt die reeds aan een eigenaar worden toegewezen, kunt u deze stroomstap gebruiken om hen aan een andere eigenaar opnieuw toe te wijzen.

![](assets/image2014-9-22-15-3a1-3a3.png)

**Gebruik**

1. Kies gewoon de eigenaar of de hoofdwachtrij die u wilt wijzigen en ga naar!

   ![](assets/image2014-9-22-15-3a1-3a6.png)

   >[!CAUTION]
   >
   >Salesforce staat geen contacten toe om aan loodrijen worden toegewezen. Voor een record die een SFDC-contactpersoon is:
   >
   >1. Marketo maakt **alleen** een dubbele lead wanneer de contactpersoon wordt gesynchroniseerd met Salesforce. Met andere woorden, als u de de stroomstap van de Persoon van de **[Synchronisatie aan SFDC](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md)** met `AssignTo=<a lead queue>`, Marketo gebruikt zal tot een dubbele lood in Salesforce leiden en het toewijzen aan de lood rij.
      >
      >
   2. Als u probeert om de de stroomstap van de Eigenaar **van de** Verandering op een contact te gebruiken, zal geen duplicaat in Salesforce worden gecreeerd.


   >[!NOTE]
   >
   >Als de record nog niet bestaat in uw Salesforce-account, wordt deze gesynchroniseerd en toegewezen aan de geselecteerde gebruiker.
