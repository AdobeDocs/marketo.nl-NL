---
unique-page-id: 7513680
description: Automatiseer een waarschuwing voor mogelijke dubbele personen - Marketo Docs - Productdocumentatie
title: Een waarschuwing automatiseren voor mogelijke dubbele personen
exl-id: 596c03f4-7a84-4564-bbe1-e7bc0d22a616
source-git-commit: 50fc46312d2c7c25556994fad4e118c01cf92fc0
workflow-type: tm+mt
source-wordcount: '178'
ht-degree: 0%

---

# Een waarschuwing automatiseren voor mogelijke dubbele personen {#automate-an-alert-for-possible-duplicate-people}

Wilt u een waarschuwing telkens wanneer een mogelijk dubbele persoon wordt gemaakt? Hieronder wordt beschreven hoe u een slimme campagne kunt opzetten om dit te doen.

1. [Nieuwe slimme campagne maken](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/create-a-new-smart-campaign.md){target=&quot;_blank&quot;}. Definieer de volgende slimme lijst:

* Trigger: **Persoon is gemaakt**
* Filter: **Dubbele velden.** Veldnaam **is Volledige naam**

   ![](assets/automate-an-alert-1.png)

   >[!TIP]
   >
   >Wees creatief. Experimenteer met verschillende velden voor betere filterresultaten.

1. Kies in de stap Stroom de optie [Waarschuwing verzenden](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/send-alert.md){target=&quot;_blank&quot;} handeling flow.

   ![](assets/automate-an-alert-2.png)

   >[!TIP]
   >
   >Met de [Token voor waarschuwinginfo verzenden](/help/marketo/product-docs/email-marketing/general/using-tokens/use-the-send-alert-info-token.md){target=&quot;_blank&quot;} om een koppeling naar de persoon in uw CRM op te nemen.

   >[!CAUTION]
   >
   >Als je een grote lijst importeert, krijg je mogelijk een hoop van deze berichten tegelijk!
   >
   >Twee mensen met dezelfde naam betekenen niet automatisch dat ze dezelfde persoon zijn.

1. De campagne activeren in het dialoogvenster **Schema** tab.

   ![](assets/automate-an-alert-3.png)

Dat is het! Deze slimme campagne wordt elke keer gestart wanneer er in Marketo een nieuwe persoon met een bestaande volledige naam wordt gemaakt.

>[!MORELIKETHIS]
>
>[Dubbele personen zoeken en samenvoegen](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/find-and-merge-duplicate-people.md){target=&quot;_blank&quot;}
