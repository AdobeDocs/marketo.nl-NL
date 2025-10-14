---
unique-page-id: 1146978
description: Gebruik een Duur in een Stap van de Stroom van de Wacht - Marketo Docs - de Documentatie van het Product
title: Gebruik een Duur in een Stap van de Stroom van de Wacht
exl-id: 7b13d225-78ba-4ef1-9ff5-0f6acde6e5ff
feature: Smart Campaigns
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '202'
ht-degree: 0%

---

# Gebruik een Duur in een Stap van de Stroom van de Wacht {#use-a-duration-in-a-wait-flow-step}

U kunt de stap van de Wachtrij gebruiken om de reis van een persoon door een Slimme Campagne voor een bepaalde duur te pauzeren. U kunt ook criteria opgeven voor de dag van de week en het tijdstip waarop deze eindigt.

1. Sleep over de stap **[!UICONTROL Flow]** flow in de tab Slimme campagne **[!UICONTROL Wait]** .

   ![](assets/use-a-duration-in-a-wait-flow-step-1.png)

1. Voer in hoelang u wilt pauzeren.

   ![](assets/use-a-duration-in-a-wait-flow-step-2.png)

1. Dat is het! De flow wordt onderbroken voor de opgegeven duur. Voor geavanceerde opties klikt u op het tandwielpictogram rechts.

   ![](assets/use-a-duration-in-a-wait-flow-step-3.png)

1. Geef de dag van de week op waarop de wachttijdstap moet worden beëindigd.

   ![](assets/use-a-duration-in-a-wait-flow-step-4.png)

1. Geef eventueel de tijd op. Klik op **[!UICONTROL Save]**.

   ![](assets/use-a-duration-in-a-wait-flow-step-5.png)

   >[!NOTE]
   >
   >**Voorbeeld**
   >
   >Een persoon activeert vrijdag om 17.00 uur een slimme campagne. De wachtstap is gevorderd: 48 uur en moet om 9.00 uur eindigen.
   >
   >Het resultaat zou zijn dat de persoon in de stroom op **Maandag, 9am** zou voortzetten. Dit is de eerste M-F-datum na 48 uur.

   >[!NOTE]
   >
   >De duur, de data, de tijden, en de gebruikte dagen zijn allen gebaseerd op de tijdzone van uw abonnement.

   >[!MORELIKETHIS]
   >
   >* [&#x200B; gebruik een Specifieke Datum in een Wacht Stap van de Stroom &#x200B;](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/wait/use-a-specific-date-in-a-wait-flow-step.md){target="_blank"}
   >* [&#x200B; Gebruik een Symbolisch van de Datum in een Wacht Stap van de Stroom &#x200B;](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/wait/use-a-date-token-in-a-wait-flow-step.md){target="_blank"}
