---
unique-page-id: 1147021
description: Eigenaar wijzigen - Marketo Docs - Productdocumentatie
title: Eigenaar wijzigen
exl-id: b22c5cd8-1b53-4802-8b49-7f607c8a601b
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
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
   >1. Marketo maakt een gedupliceerde lead **only** wanneer de contactpersoon wordt gesynchroniseerd met Salesforce. Met andere woorden, als u **[Persoon synchroniseren met SFDC](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md)** stap laten doorlopen met `AssignTo=<a lead queue>`, maakt Marketo een dubbele lead in Salesforce en wijst het toe aan de hoofdwachtrij.
      >
      >
   1. Als u probeert om **de debietstap van de Eigenaar van de Verandering** op een contact te gebruiken, zal geen duplicaat in Salesforce worden gecreeerd.


   >[!NOTE]
   >
   >Als de record nog niet bestaat in uw Salesforce-account, wordt deze gesynchroniseerd en toegewezen aan de geselecteerde gebruiker.
