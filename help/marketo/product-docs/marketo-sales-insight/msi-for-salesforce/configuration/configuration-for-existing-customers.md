---
unique-page-id: 42762519
description: Configuratie voor bestaande klanten - Marketo Docs - Productdocumentatie
title: Configuratie voor bestaande klanten
exl-id: e365f6b5-a3ec-492e-9348-2d3226e6c7eb
feature: Marketo Sales Insights
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '183'
ht-degree: 0%

---

# Configuratie voor bestaande klanten {#configuration-for-existing-customers}

Stel de volgende configuratie in om te beginnen met het gebruik van het nieuwe dashboard Inzichten.

>[!PREREQUISITES]
>
>Zorg ervoor dat u het Salesforce-pakket hebt bijgewerkt naar de nieuwste versie

## Verkoopinzicht configureren in Marketo {#configure-sales-insight-in-marketo}

1. Open een nieuw tabblad in uw browser om de gegevens van Marketo Sales Insights van uw Marketo-account op te halen.

1. Ga naar de **Beheer** gebied.

   ![](assets/configuration-for-existing-customers-1.png)

1. Klikken **Verkoopoverzicht**.

   ![](assets/configuration-for-existing-customers-2.png)

1. Klikken **Weergave** om referenties voor de rest-API te vullen.

   ![](assets/configuration-for-existing-customers-3.png)

1. Er verschijnt een bevestigingspop-up. Klikken **OK**.

## Verkoopinzicht configureren in Salesforce {#configure-sales-insight-in-salesforce}

1. Klik in Salesforce op **Instellen**.

   ![](assets/configuration-for-existing-customers-4.png)

1. Zoeken naar en selecteren **Instellingen voor externe site**.

   ![](assets/configuration-for-existing-customers-5.png)

1. Klikken **Nieuwe externe site**.

   ![](assets/configuration-for-existing-customers-6.png)

1. Voer de naam van de externe site in (dit kan bijvoorbeeld &quot;MarketoRestAPI&quot; zijn) en de URL van de externe site (uw API-URL vanuit het configuratievenster voor de rest van de API in Marketo).

   ![](assets/configuration-for-existing-customers-7.png)

1. Klikken **Opslaan**.

   ![](assets/configuration-for-existing-customers-8.png)

   U hebt nu een externe site-instelling voor de rest-API gemaakt.

## Marketo Sales Insight openen {#access-marketo-sales-insight}

1. Kopieer de gegevens vanuit het venster Rest API in de pagina Sales Insight Admin van Marketo. Plak ze in de sectie Rest API in de pagina Configuration van het Inzicht van de Verkoop van Salesforce.

1. Voer de geheime API-sleutel in.

   ![](assets/configuration-for-existing-customers-9.png)
