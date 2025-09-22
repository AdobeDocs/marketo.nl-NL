---
unique-page-id: 1146995
description: Tokens gebruiken in stroomstappen - Marketo Docs - Productdocumentatie
title: Tokens gebruiken in stappen
exl-id: 9b4c3d57-5906-4d7c-8215-4ba2271be3f8
feature: Smart Campaigns
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '193'
ht-degree: 0%

---

# Tokens gebruiken in stappen {#use-tokens-in-flow-steps}

>[!PREREQUISITES]
>
>[ voeg een Stap van de Stroom aan een Slimme Campagne toe ](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md){target="_blank"}

Een token is een variabele. U gebruikt het in e-mails, Landing Pages, en Slimme Campagnes om uw leven gemakkelijker te maken. U kunt [ Mijn Tokens ](/help/marketo/product-docs/core-marketo-concepts/programs/tokens/understanding-my-tokens-in-a-program.md){target="_blank"} (douanetokens) in stroomstappen, webhooks, e-mail, en landende pagina&#39;s gebruiken. U kunt tokens gebruiken om veranderlijke inhoud in deze stroomstappen te omvatten:

* Gegevenswaarde wijzigen
* Gegevens van programmalid wijzigen
* Interessant moment
* [!DNL Salesforce] Campagnestappen (toevoegen, verwijderen, status wijzigen)
* Taak maken
* Waarschuwing verzenden (alleen in triggercampagnes)

1. In de flowstap typt u `{{` om tokencategorieën op te halen.

   ![](assets/use-tokens-in-flow-steps-1.png)

   >[!NOTE]
   >
   >Controle uit [ Tokens Overzicht ](/help/marketo/product-docs/demand-generation/landing-pages/personalizing-landing-pages/tokens-overview.md){target="_blank"} voor een lijst van verscheidene beschikbare tokens.

1. Blijf typen totdat u het gewenste token hebt gevonden en klik om dit te selecteren.

   ![](assets/use-tokens-in-flow-steps-2.png)

   >[!TIP]
   >
   >Meerdere tokens kunnen worden gebruikt in de stappen Interessant Moment, Taak maken en Waarschuwing verzenden.

   >[!NOTE]
   >
   >De Tokens van het Gebied van het Lid van het programma kunnen in worden gebruikt: Creeer Taak, creeer Taak in Microsoft, Interesserende Momenten, Verandering de Acties van de Stroom van de Waarde van Gegevens, en Webhooks.

   Koel! De gegevens worden uit het token gehaald wanneer de slimme campagne wordt uitgevoerd.

   >[!MORELIKETHIS]
   >
   >* [ het leiden Mijn Tokens ](/help/marketo/product-docs/core-marketo-concepts/programs/tokens/managing-my-tokens.md){target="_blank"}
   >* [ Begrijpend Mijn Tokens in een Programma ](/help/marketo/product-docs/core-marketo-concepts/programs/tokens/understanding-my-tokens-in-a-program.md){target="_blank"}
