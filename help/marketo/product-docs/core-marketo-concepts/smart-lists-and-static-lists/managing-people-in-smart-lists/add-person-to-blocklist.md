---
unique-page-id: 9438139
description: Persoon toevoegen aan Lijst van gewezen personen - Marketo Docs - Productdocumentatie
title: Persoon toevoegen aan Lijst van gewezen personen
exl-id: e4543bf9-11e9-42df-a31e-e2cebe24ad4a
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '216'
ht-degree: 0%

---

# Persoon toevoegen aan Lijst van gewezen personen {#add-person-to-blocklist}

Als u mensen aan uw Lijst van gewezen personen toevoegt, kunnen ze uw correspondentie niet ontvangen.

>[!NOTE]
>
>Marketo is bezig met het wijzigen van termen als Blacklist en Whitelist in de Lijst van gewezen personen en de Lijst van gewenste personen in ons product. Tijdens deze update ziet u mogelijk de oude termen in onze gebruikersinterface en documentatiescherm en de nieuwe termen in onze documentatietekst. Onze excuses voor de verwarring.

1. [Creeer een nieuw standaardprogramma ](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/create-a-program.md) en noem het  **Toevoegen aan Lijst van gewezen personen**.

1. Klik **Nieuw** en selecteer **Nieuw Lokaal element**.

   ![](assets/image2015-8-14-11-3a0-3a46.png)

1. Geef uw lijst een naam en klik op **Maken**.

   ![](assets/image2015-8-14-11-3a2-3a26.png)

1. Voeg alle mensen aan uw **Slimme Lijst** toe u aan uw Lijst van gewezen personen wilt toevoegen.

   >[!NOTE]
   >
   >Personen op je Lijst van gewezen personen ontvangen geen e-mails met een normale werking.

   ![](assets/three-6.png)

1. Klik **Nieuw** en selecteer **Nieuwe slimme campagne**.

   ![](assets/image2015-8-14-11-3a12-3a35.png)

1. Geef de **Nieuwe slimme campagne** een naam. Klik **Maken**.

   ![](assets/image2015-8-14-11-3a13-3a36.png)

1. Sleep **Lid van Slimme Lijst**.

   ![](assets/image2015-8-14-11-3a16-3a34.png)

1. Selecteer de slimme lijst die u net hebt gemaakt.

   ![](assets/image2015-8-14-11-3a17-3a5.png)

1. Sleep **Gegevenswaarde wijzigen**.

   ![](assets/image2015-8-14-11-3a18-3a41.png)

1. Voor **Stroom**, ga **Blok op Lijst** voor **Kenmerk** in en reeks **Nieuwe Waarde** aan **true**.

   ![](assets/image2015-8-14-11-3a21-3a1.png)

1. Selecteer **Eenmaal uitvoeren** op het tabblad **Schema**.

   ![](assets/ten.png)

1. Selecteer **Nu uitvoeren** en klik **Run**.

   ![](assets/image2015-8-14-11-3a24-3a50.png)

   JA! Deze mensen zullen geen e-mails meer ontvangen.

   >[!TIP]
   >
   >Maak een [trigger smart campagne](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/create-a-new-smart-campaign.md) met **Gegevenswaarde wijzigen** met **Blok in de lijst is true** voor alle mensen in de toekomst die kenmerken hebben die geschikt zijn voor lijst van gewezen personen.
