---
unique-page-id: 1146958
description: Waarschuwing verzenden - Marketo-documenten - productdocumentatie
title: Waarschuwing verzenden
exl-id: 2016e2e7-0361-4bb2-8740-819e21fbd15b
feature: Smart Campaigns
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '137'
ht-degree: 0%

---

# Waarschuwing verzenden {#send-alert}

Marketo Engage kan een e-mailbericht met persoonlijke gegevens naar iedereen sturen - de eigenaar van de verkoop, een partner of iemand anders. Gebruik de stap &quot;[!UICONTROL Send Alert]&quot;-stroom.

![](assets/send-alert-1.png)

1. Zoek en selecteer het e-mailbericht dat u wilt verzenden.

   ![](assets/send-alert-2.png)

   >[!NOTE]
   >
   >Uw e-mailwaarschuwing moet alle koptekstgegevens bevatten en de status **[!UICONTROL Approved]** hebben.

1. U kunt op het voorvertoningspictogram klikken om te controleren of u het juiste e-mailadres hebt geselecteerd.

   ![](assets/send-alert-3.png)

   >[!NOTE]
   >
   >Gebruik de token &quot;[!UICONTROL Send Alert Info]&quot; in uw e-mail.

1. Selecteer de ontvanger van de waarschuwing. U kunt [!UICONTROL Sales Owner] of [!UICONTROL Account Owner] kiezen.

   ![](assets/send-alert-4.png)

1. Voeg desgewenst andere e-mailadressen toe (gescheiden door een komma of een puntkomma).

   ![](assets/send-alert-5.png)

   >[!TIP]
   >
   >In triggercampagnes kunt u tokens gebruiken in **[!UICONTROL To Other Emails]** zoals `{{lead.Territory Owner}}` of `{{my.Alert Recipient}}` als de waarden geldige e-mailadressen zijn. Tokens in **[!UICONTROL To Other Emails]** werken niet in een batchcampagne.

>[!MORELIKETHIS]
>
>[ creeer een E-mail ](/help/marketo/product-docs/email-marketing/general/creating-an-email/create-an-email.md){target="_blank"}
