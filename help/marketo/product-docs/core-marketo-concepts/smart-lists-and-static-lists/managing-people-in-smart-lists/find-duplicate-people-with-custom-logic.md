---
unique-page-id: 2952636
description: Zoek naar dubbele mensen met aangepaste logica - Marketo Docs - Productdocumentatie
title: Dubbele mensen zoeken met aangepaste logica
exl-id: e268ca34-03a3-403a-8869-4e2b60bba05c
feature: Smart Lists
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '124'
ht-degree: 0%

---

# Dubbele mensen zoeken met aangepaste logica {#find-duplicate-people-with-custom-logic}

Marketo Engage heeft een slimme lijst van het Systeem die dubbele mensen door hun e-mailadressen te passen vindt. Als u een ander veld wilt gebruiken om duplicaten te zoeken, gaat u als volgt te werk.

>[!PREREQUISITES]
>
>[ creeer een Slimme Lijst ](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md){target="_blank"}

1. Ga naar het **[!UICONTROL Marketing Activities]** -gebied.

![](assets/ma-2.png)

1. Selecteer de slimme lijst en klik op het tabblad **[!UICONTROL Smart List]** .

   ![](assets/two-4.png)

1. Zoek en sleep het filter **[!UICONTROL Duplicate Fields]** naar het canvas.

   ![](assets/three-4.png)

1. Kies een van de vier beschikbare opties:

   * [!UICONTROL Email Address]
   * [!UICONTROL Full Name]
   * [!UICONTROL Last Name]
   * [!UICONTROL Updated At]

   >[!NOTE]
   >
   >Alle velden, met uitzondering van E-mailadres, zijn hoofdlettergevoelig. Zo zou het gebruiken van &quot;john doe&quot;op het Volledige gebied van de Naam _niet_ resultaten voor Jan Smit terugkeren.

   ![](assets/four-2.png)

   Gereed! Voer de slimme lijst uit om mensen met dezelfde waarde te zoeken in het eerder geselecteerde veld.
