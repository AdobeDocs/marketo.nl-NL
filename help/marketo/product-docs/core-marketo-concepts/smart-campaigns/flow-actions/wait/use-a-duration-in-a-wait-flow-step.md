---
unique-page-id: 1146978
description: Gebruik een Duur in een Stap van de Stroom van de Wacht - Marketo Docs - de Documentatie van het Product
title: Gebruik een Duur in een Stap van de Stroom van de Wacht
exl-id: 7b13d225-78ba-4ef1-9ff5-0f6acde6e5ff
feature: Smart Campaigns
source-git-commit: 2eeb7ea7fd43ba75a3c802a91ce07c90dc8abd91
workflow-type: tm+mt
source-wordcount: '200'
ht-degree: 0%

---

# Gebruik een Duur in een Stap van de Stroom van de Wacht {#use-a-duration-in-a-wait-flow-step}

U kunt de stap van de Wachtrij gebruiken om de reis van een persoon door een Slimme Campagne voor een bepaalde duur te pauzeren. U kunt ook criteria opgeven voor de dag van de week en het tijdstip waarop deze eindigt.

1. In uw slimme campagne **[!UICONTROL Flow]** tab, sleep over de **[!UICONTROL Wait]** stap Stroom.

   ![](assets/image2014-9-22-11-3a53-3a57.png)

1. Voer in hoelang u wilt pauzeren.

   ![](assets/image2014-9-22-11-3a54-3a0.png)

1. Dat is het! De flow wordt onderbroken voor de opgegeven duur. Voor geavanceerde opties klikt u op het tandwielpictogram rechts.

   ![](assets/image2014-9-22-11-3a54-3a7.png)

1. Geef de dag van de week op waarop de wachttijdstap moet worden beëindigd.

   ![](assets/image2014-9-22-11-3a54-3a10.png)

1. Geef eventueel de tijd op. Klik op **[!UICONTROL Save]**.

   ![](assets/image2014-9-22-11-3a54-3a35.png)

   >[!NOTE]
   >
   >**Voorbeeld**
   >
   >Een persoon activeert vrijdag om 17.00 uur een slimme campagne. De wachtstap is gevorderd: 48 uur en moet om 9.00 uur eindigen.
   >
   >Het resultaat zou zijn dat de persoon in de stroom zou blijven **Maandag, 9.00 uur**. Dit is de eerste M-F-datum na 48 uur.

   >[!NOTE]
   >
   >De duur, de data, de tijden, en de gebruikte dagen zijn allen gebaseerd op de tijdzone van uw abonnement.

   >[!MORELIKETHIS]
   >
   >* [Gebruik een specifieke Datum in een Stap van de Stroom van de Wacht](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/wait/use-a-specific-date-in-a-wait-flow-step.md){target="_blank"}
   >* [Een Date Token gebruiken in een Wachten Flow-stap](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/wait/use-a-date-token-in-a-wait-flow-step.md){target="_blank"}
