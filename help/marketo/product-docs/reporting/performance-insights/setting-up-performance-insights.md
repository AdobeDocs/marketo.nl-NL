---
unique-page-id: 12981145
description: Prestatie-inzichten instellen - Marketo Docs - Productdocumentatie
title: Prestatie-inzichten instellen
exl-id: f87bbaba-c2c1-4b83-9e07-f8a5d1f1738b
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '307'
ht-degree: 0%

---

# Prestatie-inzichten instellen {#setting-up-performance-insights}

Voer de onderstaande stappen uit om MPI in te stellen.

## Opportunity instellen {#opportunity-setup}

1. Klikken **Beheer**.

   ![](assets/admin.png)

1. Klikken **Analyse van inkomstencyclus**.

   ![](assets/two-2.png)

   >[!NOTE]
   >
   >Als u geen RCA hebt, zult u moeten selecteren **Programmaanalyse** voor Stap 2.

1. Klik onder Kenmerk op **Bewerken**.

   ![](assets/three-1.png)

1. Attributie-instellingen worden weergegeven.

   ![](assets/four-2.png)

   Als de Attributie uitdrukkelijk is, zorg ervoor de Rol van het Contact van de Kans is bevolkt (of via het eindpunt van de Rol van de Kans of via de integratie van CRM).

   Als Attribution impliciet is, zorg ervoor het bedrijfgebied op lood/contact het zelfde als de Naam van de Rekening van de kans is.

   >[!NOTE]
   >
   >Zorg ervoor dat alle mogelijkheden de juiste velden hebben:
   >
   >* Aantal kansen
   >* Is gesloten
   >* Is Won
   >* Aanmaakdatum (deze wordt mogelijk niet ingesteld in uw geval)
   >* Gesloten datum (dit wordt mogelijk niet ingesteld in je geval)
   >* Type opportunity


## Programma instellen {#program-setup}

Werk de programmakosten ten minste 12 maanden bij. U kunt dit handmatig doen of de programma-API gebruiken. In dit voorbeeld doen we het handmatig.

1. Klikken **Marketingactiviteiten**.

   ![](assets/ma.png)

1. Zoek en selecteer uw programma.

   ![](assets/select-program.png)

1. Klik op de knop **Instellen** tab.

   ![](assets/setup-tab.png)

1. Slepen **Kosten periode** op het canvas.

   ![](assets/period-cost.png)

1. Stel de programmamaand ten minste 12 maanden geleden in en klik op **OK**.

   ![](assets/set-period.png)

1. Stel de kosten voor de periode in en klik op **Opslaan**.

   ![](assets/set-cost.png)

Controleer vervolgens het analysegedrag om aan te geven of een bepaald kanaal moet worden opgenomen in de analyse. Stel het gedrag Analytics (Normaal, Inclusief, Operationeel) in.

1. Klikken **Beheer**.

   ![](assets/admin.png)

1. Klikken **Tags**.

   ![](assets/tags.png)

1. Klik op de knop **+** om de lijst Kanaal uit te vouwen.

   ![](assets/channel.png)

1. Dubbelklik op het gewenste kanaal.

   ![](assets/channel-click.png)

1. Klik op de knop **Analysegedrag** en selecteert u het gewenste gedrag.

   ![](assets/edit-channel.png)

1. Stel de succescriteria in.

   ![](assets/success.png)

1. Klikken **Opslaan**.

   ![](assets/save.png)

## Het programma aan de persoon overhandigen {#tie-the-program-to-the-person}

1. Zorg ervoor dat het overnameprogramma en de overnamedatum zijn ingesteld voor elke persoon in de database, zodat First Touch Attribution werkt.
1. Zorg ervoor dat uw programma&#39;s de status van succes instellen voor uw volk.

>[!NOTE]
>
>Wijzigingen worden niet onmiddellijk doorgevoerd. Een overnight-periode is vereist voordat wijzigingen van kracht worden.
