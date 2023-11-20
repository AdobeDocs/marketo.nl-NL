---
unique-page-id: 4719302
description: Niet-Engelse aangepaste objectsynchronisatie inschakelen - Marketo Docs - Productdocumentatie
title: Niet-Engelse aangepaste objectsynchronisatie inschakelen
exl-id: 5d1c5b52-5323-4f68-847b-7d24e6acd6c4
feature: Salesforce Integration
source-git-commit: 756a38ba87dd5af9ee783e9709056d444d4f415b
workflow-type: tm+mt
source-wordcount: '139'
ht-degree: 1%

---

# Niet-Engelse aangepaste objectsynchronisatie inschakelen {#enable-non-english-custom-object-sync}

Als uw Marketo-synchronisatiegebruiker is ingesteld op een andere taal dan Engels, treedt er mogelijk een fout op wanneer u probeert een aangepaste objectsynchronisatie in te schakelen.

## De fout {#the-error}

![](assets/image2014-12-10-13-3a17-3a51.png)

## Aan de slag {#getting-around-it}

1. Aanmelden bij [!DNL Salesforce] het gebruiken van Marketo synchroniseert gebruiker.

   ![](assets/image2014-12-10-13-3a18-3a1.png)

1. Ga onder de gebruikersnaam naar **[!UICONTROL Setup]**.

   ![](assets/image2014-12-10-13-3a18-3a11.png)

1. Onder **[!UICONTROL Personal Information]**, klikt u op **[!UICONTROL My Personal Information]**.

   ![](assets/image2014-12-10-13-3a18-3a22.png)

1. Klik op **[!UICONTROL Edit]**.

   ![](assets/image2014-12-10-13-3a18-3a32.png)

1. Wijzig de **[!UICONTROL Language]** tot **[!UICONTROL English]**.

   ![](assets/image2014-12-10-13-3a18-3a45.png)

1. Klik op **[!UICONTROL Save]**.

   ![](assets/image2014-12-10-13-3a18-3a55.png)

1. Terug in Marketo, onder **[!UICONTROL Admin]** > **[!UICONTROL Salesforce]** > **[!UICONTROL Objects]**, klikt u op **[!UICONTROL Refresh Schema]**.

   ![](assets/image2014-12-10-13-3a19-3a6.png)

1. Hierdoor wordt de lijst met objecten in het Engels weergegeven. Selecteer nu het gewenste object en klik op **[!UICONTROL Enable Sync]**.

   ![](assets/image2014-12-10-13-3a19-3a16.png)

1. Het aangepaste object is nu ingeschakeld en gesynchroniseerd.

   ![](assets/image2014-12-10-13-3a19-3a26.png)

1. Ga nu terug naar Salesforce en gebruik de bovenstaande stappen om de synchronisatiegebruiker terug te sturen naar de voorkeurstaal.

>[!NOTE]
>
>Vergeet niet het schema een laatste keer vernieuwen om de objecten weer in uw taal te plaatsen.
