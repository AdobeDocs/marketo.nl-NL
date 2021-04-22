---
unique-page-id: 1147027
description: Persoon synchroniseren naar SFDC - Marketo Docs - Productdocumentatie
title: Persoon synchroniseren naar SFDC
exl-id: 4284ec35-6ac5-4084-beb7-976eb6fd7e3c
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '133'
ht-degree: 0%

---

# Persoon synchroniseren naar SFDC {#sync-person-to-sfdc}

>[!NOTE]
>
>Alleen beschikbaar bij integratie met Salesforce.

## Overzicht {#overview}

Deze stroomstap zal Marketo-gecreeerde mensen als lood in uw Salesforce CRM opnemen.

![](assets/sync-person-to-sfdc.png)

## Gebruik {#usage}

1. Door gebrek, zal deze die stroomstap aan loodeigenaars toewijzen op de Salesforce auto-toewijzingsregels wordt gebaseerd.

   ![](assets/sync-person-to-sfdc.png)

   >[!TIP]
   >
   >Voor Salesforce moeten de velden Bedrijf en Achternaam van de persoon zijn ingevuld. Anders wordt de lead record geweigerd.

1. U kunt een specifieke gebruiker van Salesforce of een lood rij als lood eigenaar plaatsen.

   ![](assets/sync-person-to-sfdc-2.png)

   Wanneer u deze flowstap gebruikt, wordt de persoon onmiddellijk gesynchroniseerd als een Salesforce-lead en hoeft deze niet te wachten op de normale synchronisatie.

   >[!CAUTION]
   >
   >Salesforce staat niet toe dat &quot;Contacten&quot;worden toegewezen aan loodrijen. In dit geval maakt Marketo een duplicaat van &quot;Lead&quot; in Salesforce.
