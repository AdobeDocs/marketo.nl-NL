---
unique-page-id: 37356429
description: Taak maken in Microsoft - Marketo Docs - Productdocumentatie
title: Taak maken in Microsoft
exl-id: b9ae425b-edf1-4aae-92f4-e7c6cf647cdc
feature: Smart Campaigns, Microsoft Dynamics
source-git-commit: d20a9bb584f69282eefae3704ce4be2179b29d0b
workflow-type: tm+mt
source-wordcount: '171'
ht-degree: 0%

---

# Taak maken in Microsoft {#create-task-in-microsoft}

Als markator, hebt u informatie die verkoop in het sluiten van overeenkomsten kan helpen. U kunt taken maken om ze te laten weten wat ze moeten doen en wanneer ze het moeten doen.

Met Taak maken in Microsoft wordt een taak gemaakt onder Activiteiten die betrekking hebben op de persoon (lead of contactpersoon) in Microsoft.

>[!NOTE]
>
>Deze stroomstap zal **werkt alleen bij gebruik met triggers**, niet filters, in uw slimme campagne.

Standaard ziet de flowstap er als volgt uit:

![](assets/msd1.png)

>[!NOTE]
>
>Wanneer de Marketo Sync-gebruiker taken maakt, **Eind** is een vereist veld voor de taak die in Microsoft moet worden gemaakt. Marketo voert standaard vijf dagen in als er geen waarde wordt opgegeven.

Pas alle velden aan om de taak op de gewenste manier te maken.

![](assets/msd2.png)

>[!NOTE]
>
>Het veld &quot;Status&quot; dat voor de taak is opgegeven in de Flow Action werkt het veld bij: &quot;Reden voor status&quot; in Microsoft.

>[!TIP]
>
>U kunt `{{lead.tokens}}`, `{{company.tokens}}`, `{{campaign.tokens}}` en `{{system.tokens}}` in de **Onderwerp** en **Beschrijving**. Zie [Tokens voor stroomstappen](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/use-tokens-in-flow-steps.md) voor meer informatie .
