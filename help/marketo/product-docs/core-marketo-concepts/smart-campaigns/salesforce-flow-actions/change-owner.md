---
unique-page-id: 1147021
description: Eigenaar wijzigen - Marketo Docs - Productdocumentatie
title: Eigenaar wijzigen
exl-id: b22c5cd8-1b53-4802-8b49-7f607c8a601b
feature: Smart Campaigns, Salesforce Integration
source-git-commit: d20a9bb584f69282eefae3704ce4be2179b29d0b
workflow-type: tm+mt
source-wordcount: '170'
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
   >1. Marketo maakt een dubbele lead **alleen** als de contactpersoon wordt gesynchroniseerd met Salesforce. Met andere woorden, als u de **[Persoon synchroniseren naar SFDC](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md)** stap doorlopen met `AssignTo=<a lead queue>`, Marketo maakt een dubbele lead in Salesforce en wijst deze toe aan de hoofdwachtrij.
   >
   >1. Als u het **Eigenaar wijzigen** In een stroomstap op een contactpersoon maakt Marketo een dubbele lead in Salesforce. U kunt dit voorkomen door een filter in het veld SFDC-type te gebruiken dat de handeling beperkt tot alleen leads.

   >[!NOTE]
   >
   >Als de record nog niet bestaat in uw Salesforce-account, wordt deze gesynchroniseerd en toegewezen aan de geselecteerde gebruiker.
