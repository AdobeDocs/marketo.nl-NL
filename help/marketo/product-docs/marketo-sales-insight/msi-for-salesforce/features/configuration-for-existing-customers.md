---
unique-page-id: 42762519
description: Configuratie voor bestaande klanten - Marketo Docs - Productdocumentatie
title: Configuratie voor bestaande klanten
translation-type: tm+mt
source-git-commit: 6ae882dddda220f7067babbe5a057eec82601abf
workflow-type: tm+mt
source-wordcount: '183'
ht-degree: 0%

---


# Configuratie voor bestaande klanten {#configuration-for-existing-customers}

Stel de volgende configuratie in om te beginnen met het gebruik van het nieuwe dashboard Inzichten.

>[!PREREQUISITES]
>
>Zorg ervoor dat u het Salesforce-pakket hebt bijgewerkt naar de nieuwste versie

## Het Inzicht van de Verkoop in Marketo {#configure-sales-insight-in-marketo} vormen

1. Open een nieuw tabblad in uw browser om de gegevens van Marketo Sales Insights van uw Marketo-account op te halen.

1. Ga naar **Admin** gebied.

   ![](assets/configure-1.png)

1. Klik **Sales Insight**.

   ![](assets/configure-2.png)

1. Klik **View** om de referenties van de rest-API te vullen.

   ![](assets/configure-3.png)

1. Er verschijnt een bevestigingspop-up. Klik **OK**.

## Het Inzicht van de Verkoop in Salesforce {#configure-sales-insight-in-salesforce} vormen

1. Klik in Salesforce op **Setup**.

   ![](assets/sfdc-1.png)

1. Zoek naar en selecteer **Verre Montages van de Plaats**.

   ![](assets/sfdc-2.png)

1. Klik **Nieuwe verre Plaats**.

   ![](assets/sfdc-3.png)

1. Voer de naam van de externe site in (dit kan bijvoorbeeld &quot;MarketoRestAPI&quot; zijn) en de URL van de externe site (uw API-URL vanuit het configuratievenster voor de rest van de API in Marketo).

   ![](assets/sfdc-4.png)

1. Klik **Opslaan**.

   ![](assets/sfdc-5.png)

   U hebt nu een externe site-instelling voor de rest-API gemaakt.

## Access Marketo Sales Insight {#access-marketo-sales-insight}

1. Kopieer de gegevens vanuit het venster Rest API in de pagina Sales Insight Admin van Marketo. Plak ze in de sectie Rest API in de pagina Configuration van het Inzicht van de Verkoop van Salesforce.

1. Voer de geheime API-sleutel in.

   ![](assets/config.png)
