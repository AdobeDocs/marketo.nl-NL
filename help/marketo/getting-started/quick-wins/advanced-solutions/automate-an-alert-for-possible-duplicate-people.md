---
unique-page-id: 7513680
description: Automatiseer een waarschuwing voor mogelijke dubbele personen - Marketo Docs - Productdocumentatie
title: Een waarschuwing automatiseren voor mogelijke dubbele personen
exl-id: 596c03f4-7a84-4564-bbe1-e7bc0d22a616
feature: Getting Started
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '159'
ht-degree: 0%

---

# Een waarschuwing automatiseren voor mogelijke dubbele personen {#automate-an-alert-for-possible-duplicate-people}

Wilt u een waarschuwing telkens wanneer een mogelijk dubbele persoon wordt gemaakt? Hieronder wordt beschreven hoe u een slimme campagne kunt opzetten om dit te doen.

1. [ creeer een nieuwe slimme campagne ](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/create-a-new-smart-campaign.md){target="_blank"}. Definieer de volgende slimme lijst:

* Trigger: **[!UICONTROL Person is Created]**
* Filter: **[!UICONTROL Duplicate Fields]**. Veldnaam **[!UICONTROL is][!UICONTROL Full Name]**

  ![](assets/automate-an-alert-1.png)

  >[!TIP]
  >
  >Wees creatief. Experimenteer met verschillende velden voor betere filterresultaten.

1. Kies in de stap Stroom de optie [[!UICONTROL Send Alert]](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/send-alert.md){target="_blank"} Handeling Stroom.

   ![](assets/automate-an-alert-2.png)

   >[!TIP]
   >
   >Het gebruiken van [ verzendt het teken van Info van het Alarm ](/help/marketo/product-docs/email-marketing/general/using-tokens/use-the-send-alert-info-token.md){target="_blank"} om een verbinding aan de persoon in uw CRM te omvatten.

   >[!CAUTION]
   >
   >Als je een grote lijst importeert, krijg je mogelijk een hoop van deze berichten tegelijk!
   >
   >Twee mensen met dezelfde naam betekenen niet automatisch dat ze dezelfde persoon zijn.

1. Activeer de campagne op het tabblad **[!UICONTROL Schedule]** .

   ![](assets/automate-an-alert-3.png)

Dat is het! Deze slimme campagne wordt elke keer gestart wanneer er in Marketo een nieuwe persoon met een bestaande volledige naam wordt gemaakt.

>[!MORELIKETHIS]
>
>[ vind en voeg Dubbele Mensen ](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/find-and-merge-duplicate-people.md){target="_blank"} samen
