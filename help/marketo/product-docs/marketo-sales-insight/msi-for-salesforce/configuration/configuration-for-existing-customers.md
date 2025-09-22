---
unique-page-id: 42762519
description: Configuratie voor bestaande klanten - Marketo Docs - Productdocumentatie
title: Configuratie voor bestaande klanten
exl-id: e365f6b5-a3ec-492e-9348-2d3226e6c7eb
feature: Marketo Sales Insights
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '147'
ht-degree: 2%

---

# Configuratie voor bestaande klanten {#configuration-for-existing-customers}

Stel de volgende configuratie in om te beginnen met het gebruik van het nieuwe dashboard Inzichten.

>[!PREREQUISITES]
>
>Zorg ervoor dat u het [!DNL Salesforce] -pakket hebt bijgewerkt naar de nieuwste versie

## [!DNL Sales Insight] configureren in Marketo {#configure-sales-insight-in-marketo}

1. Open een nieuw tabblad in uw browser om de [!DNL Marketo Sales Insights] -gegevens van uw Marketo-account op te halen.

1. Ga naar het **[!UICONTROL Admin]** -gebied.

   ![](assets/configuration-for-existing-customers-1.png)

1. Klik op **[!UICONTROL Sales Insight]**.

   ![](assets/configuration-for-existing-customers-2.png)

1. Klik op **[!UICONTROL View]** om de referenties voor de rest-API in te vullen.

   ![](assets/configuration-for-existing-customers-3.png)

1. Er verschijnt een bevestigingspop-up. Klik op **[!UICONTROL OK]**.

## [!DNL Sales Insight] configureren in [!DNL Salesforce] {#configure-sales-insight-in-salesforce}

1. Klik in Salesforce op **[!UICONTROL Setup]** .

   ![](assets/configuration-for-existing-customers-4.png)

1. Zoek en selecteer **[!UICONTROL Remote Site Settings]** .

   ![](assets/configuration-for-existing-customers-5.png)

1. Klik op **[!UICONTROL New Remote Site]**.

   ![](assets/configuration-for-existing-customers-6.png)

1. Voer de [!UICONTROL Remote Site Name] (bijvoorbeeld MarketoRestAPI) en de [!UICONTROL Remote Site URL] (uw API-URL vanuit het configuratievenster voor de rest van de API in Marketo) in.

   ![](assets/configuration-for-existing-customers-7.png)

1. Klik op **[!UICONTROL Save]**.

   ![](assets/configuration-for-existing-customers-8.png)

   U hebt nu een externe site-instelling voor de rest-API gemaakt.

## Marketo Sales Insight openen {#access-marketo-sales-insight}

1. Kopieer de gegevens vanuit het venster Rest API in de pagina [!DNL Marketo’s Sales Insight] Admin. Plak ze in de sectie Rest API in de configuratiepagina van Salesforce [!DNL Sales Insight] .

1. Voer de [!UICONTROL API Secret Key] in.

   ![](assets/configuration-for-existing-customers-9.png)
