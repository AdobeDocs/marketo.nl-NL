---
unique-page-id: 1146995
description: Tokens gebruiken in stroomstappen - Marketo Docs - Productdocumentatie
title: Tokens gebruiken in stappen
exl-id: 9b4c3d57-5906-4d7c-8215-4ba2271be3f8
feature: Smart Campaigns
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '194'
ht-degree: 0%

---

# Tokens gebruiken in stappen {#use-tokens-in-flow-steps}

>[!PREREQUISITES]
>
>[Een stroomstap toevoegen aan een slimme campagne](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md)

Een token is een variabele. Je gebruikt het in e-mails, landingspagina&#39;s en slimme campagnes om je leven makkelijker te maken. U kunt [Mijn tokens](/help/marketo/product-docs/core-marketo-concepts/programs/tokens/understanding-my-tokens-in-a-program.md) (aangepaste tokens) in stroomstappen, webhaken, e-mails en landingspagina&#39;s. U kunt tokens gebruiken om veranderlijke inhoud in deze stroomstappen te omvatten:

* Gegevenswaarde wijzigen
* Gegevens van programmalid wijzigen
* Interessant moment
* Stappen voor Salesforce-campagne (toevoegen, verwijderen, status wijzigen)
* Taak maken
* Waarschuwing verzenden (alleen in triggercampagnes)

1. Begin met typen in de flowstap `{{` om tokencategorieën op te halen.

   ![](assets/image2014-9-22-14-3a3-3a17.png)

   >[!NOTE]
   >
   >Uitchecken [Overzicht van tokens](/help/marketo/product-docs/demand-generation/landing-pages/personalizing-landing-pages/tokens-overview.md) voor een lijst met verschillende beschikbare tokens.

1. Blijf typen totdat u het gewenste token hebt gevonden en klik om dit te selecteren.

   ![](assets/image2014-9-22-14-3a3-3a48.png)

   >[!TIP]
   >
   >Meerdere tokens kunnen worden gebruikt in de stappen Interessant Moment, Taak maken en Waarschuwing verzenden.

   >[!NOTE]
   >
   >Aangepaste veldtokens van programmalid kunnen worden gebruikt in: Maak een taak, maak een taak in Microsoft, Interessant momenten, wijzig de gegevenswaardehandelingen en Webhooks.

   Koel! De gegevens worden uit het token gehaald wanneer de slimme campagne wordt uitgevoerd.

   >[!MORELIKETHIS]
   >
   >* [Mijn tokens beheren](/help/marketo/product-docs/core-marketo-concepts/programs/tokens/managing-my-tokens.md)
   >* [Mijn tokens in een programma begrijpen](/help/marketo/product-docs/core-marketo-concepts/programs/tokens/understanding-my-tokens-in-a-program.md)
