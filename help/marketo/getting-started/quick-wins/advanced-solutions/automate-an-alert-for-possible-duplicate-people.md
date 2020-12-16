---
unique-page-id: 7513680
description: Een waarschuwing automatiseren voor mogelijk dubbele personen - Marketo Docs - Productdocumentatie
title: Een waarschuwing automatiseren voor mogelijke dubbele personen
translation-type: tm+mt
source-git-commit: d7d6aee63144c472e02fe0221c4a164183d04dd4
workflow-type: tm+mt
source-wordcount: '170'
ht-degree: 0%

---


# Een waarschuwing automatiseren voor mogelijke dubbele personen {#automate-an-alert-for-possible-duplicate-people}

Wilt u een waarschuwing telkens wanneer een mogelijk dubbele persoon wordt gemaakt? Hieronder wordt beschreven hoe u een slimme campagne kunt opzetten om dit te doen.

1. [Maak een nieuwe slimme campagne](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/create-a-new-smart-campaign.md). Definieer de volgende slimme lijst:

* Trigger: **Persoon is gemaakt**
* Filter: **Dubbele velden.** Veldnaam **is Volledige naam**

   ![](assets/image2017-3-27-8-3a22-3a4.png)

   >[!TIP]
   >
   >Wees creatief. Experimenteer met verschillende velden voor betere filterresultaten.

1. Kies in de stap Stroom de optie [Waarschuwing](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/send-alert.md) verzenden.

   ![](assets/image2017-3-27-8-3a24-3a8.png)

   >[!TIP]
   >
   >Het gebruiken van het [Send teken](/help/marketo/product-docs/email-marketing/general/using-tokens/use-the-send-alert-info-token.md) van Info van het Bericht om een verbinding aan de persoon in uw CRM te omvatten.

   >[!CAUTION]
   >
   >Als je een grote lijst importeert, krijg je mogelijk een hoop van deze berichten tegelijk!
   >
   >Twee mensen met dezelfde naam betekenen niet automatisch dat ze dezelfde persoon zijn.

1. Activeer de campagne op het tabblad **Planning** .

   ![](assets/image2017-3-27-8-3a24-3a37.png)

Dat is het! Deze slimme campagne wordt elke keer geactiveerd wanneer een nieuwe persoon met een bestaande volledige naam in Marketo wordt gemaakt.

>[!MORELIKETHIS]
>
>[Dubbele personen zoeken en samenvoegen](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/find-and-merge-duplicate-people.md)
