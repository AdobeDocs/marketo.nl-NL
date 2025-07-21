---
unique-page-id: 1147021
description: Eigenaar wijzigen - Marketo Docs - Productdocumentatie
title: Eigenaar wijzigen
exl-id: b22c5cd8-1b53-4802-8b49-7f607c8a601b
feature: Smart Campaigns, Salesforce Integration
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '165'
ht-degree: 0%

---

# Eigenaar wijzigen {#change-owner}

Als u bestaande mensen hebt die reeds aan een eigenaar worden toegewezen, kunt u deze stroomstap gebruiken om hen aan een andere eigenaar opnieuw toe te wijzen.

![](assets/change-owner-1.png)

1. Kies gewoon de eigenaar of de hoofdwachtrij waar u naartoe wilt gaan!

   ![](assets/change-owner-2.png)

   >[!CAUTION]
   >
   >[!DNL Salesforce] staat geen contacten toe om aan loodrijen worden toegewezen. Voor een record die een SFDC-contactpersoon is:
   >
   >* Marketo zal tot een dubbel lood **slechts** leiden wanneer het contact aan Salesforce wordt gesynchroniseerd. Met andere woorden, als u de **[Persoon van de Synchronisatie aan SFDC](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md)** stroomstap met `AssignTo=<a lead queue>` gebruikt, zal Marketo tot een dubbele lood in Salesforce leiden en het toewijzen aan de lood rij.
   >
   >* Als u de stap **[!UICONTROL Change Owner]** flow gebruikt voor een contactpersoon, maakt Marketo een dubbele lead in Salesforce. U kunt dit voorkomen door een filter in het veld SFDC Type te gebruiken dat de handeling beperkt tot alleen leads.

   >[!NOTE]
   >
   >Als de record nog niet bestaat in uw [!DNL Salesforce] -account, wordt deze gesynchroniseerd en toegewezen aan de geselecteerde gebruiker.
