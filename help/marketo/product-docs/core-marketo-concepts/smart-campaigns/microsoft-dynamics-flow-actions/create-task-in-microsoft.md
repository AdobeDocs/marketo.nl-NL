---
unique-page-id: 37356429
description: Taak maken in Microsoft - Marketo Docs - Productdocumentatie
title: Taak maken in Microsoft
exl-id: b9ae425b-edf1-4aae-92f4-e7c6cf647cdc
feature: Smart Campaigns, Microsoft Dynamics
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '164'
ht-degree: 0%

---

# Taak maken in Microsoft {#create-task-in-microsoft}

Als markator, hebt u informatie die verkoop in het sluiten van overeenkomsten kan helpen. U kunt taken maken om ze te laten weten wat ze moeten doen en wanneer ze het moeten doen.

Met Taak maken in Microsoft wordt een taak gemaakt onder Activiteiten die betrekking hebben op de persoon (lead of contactpersoon) in [!DNL Microsoft] .

>[!NOTE]
>
>Deze stroomstap zal _slechts werken wanneer gebruikt met trekkers_, niet filters, in uw slimme campagne.

Standaard ziet de flowstap er als volgt uit:

![](assets/create-task-in-microsoft-1.png)

>[!NOTE]
>
>Wanneer de Marketo Sync-gebruiker taken maakt, is **[!UICONTROL Due In]** een vereist veld voor de taak die moet worden gemaakt in [!DNL Microsoft] . Marketo voert standaard vijf dagen in als er geen waarde wordt opgegeven.

Pas alle velden aan om de taak op de gewenste manier te maken.

![](assets/create-task-in-microsoft-2.png)

>[!NOTE]
>
>Het veld &quot;Status&quot; dat voor de taak is opgegeven in de Flow Action werkt het veld &quot;Reden van status&quot; bij in [!DNL Microsoft] .

>[!TIP]
>
>U kunt `{{lead.tokens}}` , `{{company.tokens}}` , `{{campaign.tokens}}` en `{{system.tokens}}` in de **[!UICONTROL Subject]** en **[!UICONTROL Description]** gebruiken. Zie [&#x200B; Tokens voor de Stappen van de Stroom &#x200B;](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/use-tokens-in-flow-steps.md){target="_blank"} voor meer details.
