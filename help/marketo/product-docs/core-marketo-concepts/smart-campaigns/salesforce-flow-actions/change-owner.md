---
unique-page-id: 1147021
description: Eigenaar wijzigen - Marketo Docs - Productdocumentatie
title: Eigenaar wijzigen
exl-id: b22c5cd8-1b53-4802-8b49-7f607c8a601b
feature: Smart Campaigns, Salesforce Integration
source-git-commit: 934bb5f197f801e48cf8e7554335eb2d07289037
workflow-type: tm+mt
source-wordcount: '167'
ht-degree: 0%

---

# Eigenaar wijzigen {#change-owner}

Als u bestaande mensen hebt die reeds aan een eigenaar worden toegewezen, kunt u deze stroomstap gebruiken om hen aan een andere eigenaar opnieuw toe te wijzen.

![](assets/change-owner-1.png)

1. Kies gewoon de eigenaar of de hoofdwachtrij waar u naartoe wilt gaan!

   ![](assets/change-owner-2.png)

   >[!CAUTION]
   >
   >Salesforce staat geen contacten toe om aan loodrijen worden toegewezen. Voor een record die een SFDC-contactpersoon is:
   >
   >* Marketo zal tot een dubbel lood **slechts** leiden wanneer het contact aan Salesforce wordt gesynchroniseerd. Met andere woorden, als u de **[Persoon van de Synchronisatie aan SFDC](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md)** stroomstap met `AssignTo=<a lead queue>` gebruikt, zal Marketo tot een dubbele lood in Salesforce leiden en het toewijzen aan de leidende rij.
   >
   >* Als u de **[!UICONTROL Change Owner]** flowstap op een contactpersoon gebruikt, maakt Marketo een dubbele lead in Salesforce. U kunt dit voorkomen door een filter in het veld SFDC-type te gebruiken dat de handeling beperkt tot alleen leads.

   >[!NOTE]
   >
   >Als de record nog niet bestaat in uw Salesforce-account, wordt deze gesynchroniseerd en toegewezen aan de geselecteerde gebruiker.
