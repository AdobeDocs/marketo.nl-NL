---
unique-page-id: 9438139
description: Persoon toevoegen aan Lijst van gewezen personen - Marketo Docs - Productdocumentatie
title: Persoon toevoegen aan Lijst van gewezen personen
exl-id: e4543bf9-11e9-42df-a31e-e2cebe24ad4a
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

1. [Een nieuw standaardprogramma maken](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/create-a-program.md) en noem deze **Toevoegen aan Lijst van gewezen personen**.

1. Klikken **Nieuw** en selecteert u **Nieuw lokaal element**.

   ![](assets/image2015-8-14-11-3a0-3a46.png)

1. Geef uw lijst een naam en klik op **Maken**.

   ![](assets/image2015-8-14-11-3a2-3a26.png)

1. Voeg alle mensen toe aan uw **Slimme lijst** u wilt toevoegen aan uw Lijst van gewezen personen.

   >[!NOTE]
   >
   >Personen op je Lijst van gewezen personen ontvangen geen e-mails met een normale werking.

   ![](assets/three-6.png)

1. Klikken **Nieuw** en selecteert u **Nieuwe slimme campagne**.

   ![](assets/image2015-8-14-11-3a12-3a35.png)

1. Geef de naam **Nieuwe slimme campagne**. Klikken **Maken**.

   ![](assets/image2015-8-14-11-3a13-3a36.png)

1. Slepen en neerzetten **Lid van slimme lijst**.

   ![](assets/image2015-8-14-11-3a16-3a34.png)

1. Selecteer de slimme lijst die u net hebt gemaakt.

   ![](assets/image2015-8-14-11-3a17-3a5.png)

1. Slepen en neerzetten **Gegevenswaarde wijzigen**.

   ![](assets/image2015-8-14-11-3a18-3a41.png)

1. Voor de **Stroom**, enter **Aangeboden blokkeren** voor de **Kenmerk** en instellen **Nieuwe waarde** tot **true**.

   ![](assets/image2015-8-14-11-3a21-3a1.png)

1. Op de **Schema** tab, selecteert u **Eenmaal uitvoeren**.

   ![](assets/ten.png)

1. Selecteren **Nu uitvoeren** en klik op **Uitvoeren**.

   ![](assets/image2015-8-14-11-3a24-3a50.png)

   JA! Deze mensen zullen geen e-mails meer ontvangen.

   >[!TIP]
   >
   >Een [slimme campagne activeren](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/create-a-new-smart-campaign.md) gebruiken **Gegevenswaarde wijzigen** with **Blok aangeboden is waar** voor alle mensen in de toekomst die kenmerken hebben die geschikt zijn voor lijst van gewezen personen.
