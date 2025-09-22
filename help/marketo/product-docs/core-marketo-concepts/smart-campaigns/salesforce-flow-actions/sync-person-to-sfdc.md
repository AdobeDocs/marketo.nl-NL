---
unique-page-id: 1147027
description: Persoon synchroniseren naar SFDC - Marketo Docs - Productdocumentatie
title: Persoon synchroniseren naar SFDC
exl-id: 4284ec35-6ac5-4084-beb7-976eb6fd7e3c
feature: Smart Campaigns, Salesforce Integration
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '125'
ht-degree: 0%

---

# Persoon synchroniseren naar SFDC {#sync-person-to-sfdc}

Met deze stroomstap worden door Marketo gemaakte mensen als leads ingevoegd in uw Salesforce CRM.

>[!NOTE]
>
>Alleen beschikbaar bij integratie met [!DNL Salesforce] .

1. Standaard wordt bij deze stap aan de eigenaars van leads toegewezen op basis van de Salesforce-regels voor automatische toewijzing.

   ![](assets/sync-person-to-sfdc-1.png)

   >[!TIP]
   >
   >[!DNL Salesforce] vereist dat de velden Bedrijf en Achternaam van de persoon zijn ingevuld. Anders wordt de lead record geweigerd.

1. U kunt een specifieke [!DNL Salesforce] gebruiker- of doorvoerwachtrij instellen als de eigenaar van de lead.

   ![](assets/sync-person-to-sfdc-2.png)

   Wanneer u deze flowstap gebruikt, wordt de persoon onmiddellijk gesynchroniseerd als een [!DNL Salesforce] lead en hoeft deze niet te wachten op de normale synchronisatie.

   >[!CAUTION]
   >
   >[!DNL Salesforce] staat niet toe dat &quot;Contacten&quot;worden toegewezen aan loodrijen. In dit geval maakt Marketo een duplicaat van &quot;Lead&quot; in [!DNL Salesforce] .
