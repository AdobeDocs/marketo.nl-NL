---
unique-page-id: 4719302
description: Niet-Engelse aangepaste objectsynchronisatie inschakelen - Marketo Docs - Productdocumentatie
title: Niet-Engelse aangepaste objectsynchronisatie inschakelen
exl-id: 5d1c5b52-5323-4f68-847b-7d24e6acd6c4
feature: Salesforce Integration
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '138'
ht-degree: 1%

---

# Niet-Engelse aangepaste objectsynchronisatie inschakelen {#enable-non-english-custom-object-sync}

Als uw Marketo-synchronisatiegebruiker is ingesteld op een andere taal dan Engels, treedt er mogelijk een fout op wanneer u probeert een aangepaste objectsynchronisatie in te schakelen.

## De fout {#the-error}

![](assets/image2014-12-10-13-3a17-3a51.png)

## Aan de slag {#getting-around-it}

1. Meld u aan bij [!DNL Salesforce] met behulp van de markering om de gebruiker te synchroniseren.

   ![](assets/image2014-12-10-13-3a18-3a1.png)

1. Ga onder de gebruikersnaam naar **[!UICONTROL Setup]** .

   ![](assets/image2014-12-10-13-3a18-3a11.png)

1. Klik onder **[!UICONTROL Personal Information]** op **[!UICONTROL My Personal Information]** .

   ![](assets/image2014-12-10-13-3a18-3a22.png)

1. Klik op **[!UICONTROL Edit]**.

   ![](assets/image2014-12-10-13-3a18-3a32.png)

1. Wijzig **[!UICONTROL Language]** in **[!UICONTROL English]** .

   ![](assets/image2014-12-10-13-3a18-3a45.png)

1. Klik op **[!UICONTROL Save]**.

   ![](assets/image2014-12-10-13-3a18-3a55.png)

1. Klik nogmaals onder **[!UICONTROL Admin]** > **[!UICONTROL Salesforce]** > **[!UICONTROL Objects]** in Marketo op **[!UICONTROL Refresh Schema]** .

   ![](assets/image2014-12-10-13-3a19-3a6.png)

1. Hierdoor wordt de lijst met objecten in het Engels weergegeven. Selecteer nu het gewenste object en klik op **[!UICONTROL Enable Sync]** .

   ![](assets/image2014-12-10-13-3a19-3a16.png)

1. Het aangepaste object is nu ingeschakeld en gesynchroniseerd.

   ![](assets/image2014-12-10-13-3a19-3a26.png)

1. Ga nu terug naar [!DNL Salesforce] en gebruik de bovenstaande stappen om de synchronisatiegebruiker terug te sturen naar de voorkeurstaal.

>[!NOTE]
>
>Vergeet niet het schema een laatste keer vernieuwen om de objecten weer in uw taal te plaatsen.
