---
unique-page-id: 12981145
description: Prestatieinzichten instellen - Marketo Docs - Productdocumentatie
title: Prestatie-inzichten instellen
translation-type: tm+mt
source-git-commit: cb7df3dd38275837f8ab05ce846c2c68ab78462f
workflow-type: tm+mt
source-wordcount: '307'
ht-degree: 0%

---


# Prestatieinzichten instellen {#setting-up-performance-insights}

Voer de onderstaande stappen uit om MPI in te stellen.

## Opportuniteit instellen {#opportunity-setup}

1. Klik **Admin**.

   ![](assets/admin.png)

1. Klik op **Analyse van omzetcyclus**.

   ![](assets/two-2.png)

   >[!NOTE]
   >
   >Als u geen RCA hebt, zult u **Analyse van het Programma** voor Stap 2 moeten selecteren.

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


## Programma-instelling {#program-setup}

Werk de programmakosten ten minste 12 maanden bij. U kunt dit handmatig doen of de programma-API gebruiken. In dit voorbeeld doen we het handmatig.

1. Klik **Marketingactiviteiten**.

   ![](assets/ma.png)

1. Zoek en selecteer uw programma.

   ![](assets/select-program.png)

1. Klik op het tabblad **Setup**.

   ![](assets/setup-tab.png)

1. Sleep **Periode Kosten** naar het canvas.

   ![](assets/period-cost.png)

1. Stel de programmamaand ten minste 12 maanden geleden in en klik op **OK**.

   ![](assets/set-period.png)

1. Stel de kosten voor de periode in en klik op **Opslaan**.

   ![](assets/set-cost.png)

Controleer vervolgens het analysegedrag om aan te geven of een bepaald kanaal moet worden opgenomen in de analyse. Stel het gedrag Analytics (Normaal, Inclusief, Operationeel) in.

1. Klik **Admin**.

   ![](assets/admin.png)

1. Klik **Codes**.

   ![](assets/tags.png)

1. Klik **+** om de lijst van het Kanaal uit te breiden.

   ![](assets/channel.png)

1. Dubbelklik op het gewenste kanaal.

   ![](assets/channel-click.png)

1. Klik op de vervolgkeuzelijst **Gedrag Analytics** en selecteer het gewenste gedrag.

   ![](assets/edit-channel.png)

1. Stel de succescriteria in.

   ![](assets/success.png)

1. Klik **Opslaan**.

   ![](assets/save.png)

## Plaats het programma aan de persoon {#tie-the-program-to-the-person}

1. Zorg ervoor dat het overnameprogramma en de overnamedatum zijn ingesteld voor elke persoon in de database, zodat First Touch Attribution werkt.
1. Zorg ervoor dat uw programma&#39;s de status van succes instellen voor uw volk.

>[!NOTE]
>
>Wijzigingen worden niet onmiddellijk doorgevoerd. Een overnight-periode is vereist voordat wijzigingen van kracht worden.
