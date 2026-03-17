---
unique-page-id: 1147017
description: Leer hoe u een Salesforce-taak maakt in een flowstap. Maak een taak voor de eigenaar van de lead wanneer iemand de flow ingaat.
title: Taak maken
exl-id: c484d913-1fd8-4716-8caa-0bf318218ca1
feature: Smart Campaigns, Salesforce Integration
source-git-commit: 3efcb529cd3e35027f35e51dfd91f95e94af9d61
workflow-type: tm+mt
source-wordcount: '126'
ht-degree: 0%

---

# Taak maken {#create-task}

Als markator, hebt u informatie die verkoop in het sluiten van overeenkomsten kan helpen. U kunt taken maken om ze te laten weten wat ze moeten doen en wanneer ze het moeten doen.

![](assets/create-task-1.png)

>[!NOTE]
>
>Wanneer de Marketo Sync-gebruiker taken maakt, is **[!UICONTROL Due In]** een vereist veld voor de taak die in Salesforce moet worden gemaakt. Marketo voert standaard vijf dagen in als er geen waarde is.

Standaard ziet de flowstap er als volgt uit:

![](assets/create-task-2.png)

Pas alle velden aan om de taak op de gewenste manier te maken.

![](assets/create-task-3.png)

>[!TIP]
>
>U kunt `{{lead.tokens}}` , `{{company.tokens}}` , `{{campaign.tokens}}` en `{{system.tokens}}` in de **[!UICONTROL Subject]** en **[!UICONTROL Description]** gebruiken. Zie [&#x200B; Tokens voor de Stappen van de Stroom &#x200B;](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/use-tokens-in-flow-steps.md){target="_blank"} voor meer details.
