---
unique-page-id: 37356429
description: Taak maken in Microsoft - Marketo Docs - Productdocumentatie
title: Taak maken in Microsoft
translation-type: tm+mt
source-git-commit: 5b9f48c98464c79bcdca2e335f6a4a2edce98ce4
workflow-type: tm+mt
source-wordcount: '171'
ht-degree: 0%

---


# Taak maken in Microsoft {#create-task-in-microsoft}

Als markator, hebt u informatie die verkoop in het sluiten van overeenkomsten kan helpen. U kunt taken maken om ze te laten weten wat ze moeten doen en wanneer ze het moeten doen.

Creeer Taak in Microsoft leidt tot een taak onder Activiteiten met betrekking tot de Persoon (Lood of Contact) in Microsoft.

>[!NOTE]
>
>Deze flowstap werkt alleen als u triggers **gebruikt, niet als filters in uw slimme campagne.**

Standaard ziet de flowstap er als volgt uit:

![](assets/msd1.png)

>[!NOTE]
>
>Wanneer de Gebruiker van de Synchronisatie van het Marketo taken creeert, **wegens In** is een vereist gebied voor de taak die in Microsoft moet worden gecreeerd. Marketo voert standaard vijf dagen in als er geen waarde wordt ingevoerd.

Pas alle velden aan om de taak op de gewenste manier te maken.

![](assets/msd2.png)

>[!NOTE]
>
>Het veld &quot;Status&quot; dat voor de taak is opgegeven in de Flow Action werkt het veld bij: &quot;Reden van de status&quot;in Microsoft.

>[!TIP]
>
>U kunt `{{lead.tokens}}`, `{{company.tokens}}`, `{{campaign.tokens}}` en `{{system.tokens}}` in **Onderwerp** en **Beschrijving** gebruiken. Zie [Tokens voor Flow Steps](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/use-tokens-in-flow-steps.md) voor meer informatie.
