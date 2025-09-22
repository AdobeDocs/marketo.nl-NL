---
unique-page-id: 12981145
description: Prestatie-inzichten instellen - Marketo Docs - Productdocumentatie
title: Prestatie-inzichten instellen
exl-id: f87bbaba-c2c1-4b83-9e07-f8a5d1f1738b
feature: Reporting
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '277'
ht-degree: 2%

---

# Instellen [!UICONTROL Performance Insights] {#setting-up-performance-insights}

Voer de onderstaande stappen uit om MPI in te stellen.

## Opportunity instellen {#opportunity-setup}

1. Klik op **[!UICONTROL Admin]**.

   ![](assets/admin.png)

1. Klik op **[!UICONTROL Revenue Cycle Analytics]**.

   ![](assets/two-2.png)

   >[!NOTE]
   >
   >Als u geen RCA hebt, moet u **[!UICONTROL Program Analysis]** selecteren voor Stap 2.

1. Klik onder Kenmerk op **[!UICONTROL Edit]** .

   ![](assets/three-1.png)

1. Attributie-instellingen worden weergegeven.

   ![](assets/four-2.png)

   Als de Attributie uitdrukkelijk is, zorg ervoor de Rol van het Contact van de Kans is bevolkt (of via het eindpunt van de Rol van de Kans of via de integratie van CRM).

   Als Attribution impliciet is, zorg ervoor het bedrijfgebied op lood/contact het zelfde als de Naam van de Rekening van de kans is.

   >[!NOTE]
   >
   >Zorg ervoor dat alle mogelijkheden de juiste velden hebben:
   >
   >* [!UICONTROL Opportunity Amount]
   >* [!UICONTROL Is Closed]
   >* [!UICONTROL Is Won]
   >* [!UICONTROL Creation Date] (dit wordt mogelijk niet ingesteld in uw geval)
   >* [!UICONTROL Closed Date] (dit wordt mogelijk niet ingesteld in uw geval)
   >* [!UICONTROL Opportunity Type]

## Programma instellen {#program-setup}

Werk de programmakosten ten minste 12 maanden bij. U kunt dit handmatig doen of de programma-API gebruiken. In dit voorbeeld doen we het handmatig.

1. Klik op **[!UICONTROL Marketing Activities]**.

   ![](assets/ma.png)

1. Zoek en selecteer uw programma.

   ![](assets/select-program.png)

1. Klik op de tab **[!UICONTROL Setup]** .

   ![](assets/setup-tab.png)

1. Sleep **[!UICONTROL Period Cost]** naar het canvas.

   ![](assets/period-cost.png)

1. Stel de programmamaand minstens 12 maanden geleden in en klik op **[!UICONTROL Ok]** .

   ![](assets/set-period.png)

1. Stel de kosten voor de periode in en klik op **[!UICONTROL Save]** .

   ![](assets/set-cost.png)

Controleer vervolgens het analysegedrag om aan te geven of een bepaald kanaal moet worden opgenomen in de analyse. Stel het gedrag Analytics (Normaal, Inclusief, Operationeel) in.

1. Klik op **[!UICONTROL Admin]**.

   ![](assets/admin.png)

1. Klik op **[!UICONTROL Tags]**.

   ![](assets/tags.png)

1. Klik **+** om de lijst van het Kanaal uit te breiden.

   ![](assets/channel.png)

1. Klik het gewenste kanaal tweemaal.

   ![](assets/channel-click.png)

1. Klik op de vervolgkeuzelijst **[!UICONTROL Analytics Behavior]** en selecteer het gewenste gedrag.

   ![](assets/edit-channel.png)

1. Stel de succescriteria in.

   ![](assets/success.png)

1. Klik op **[!UICONTROL Save]**.

   ![](assets/save.png)

## Het programma aan de persoon overhandigen {#tie-the-program-to-the-person}

1. Zorg ervoor dat het overnameprogramma en de overnamedatum zijn ingesteld voor elke persoon in de database, zodat First Touch Attribution werkt.
1. Zorg ervoor dat uw programma&#39;s de status van succes instellen voor uw volk.

>[!NOTE]
>
>Wijzigingen worden niet onmiddellijk doorgevoerd. Een overnight-periode is vereist voordat wijzigingen van kracht worden.
