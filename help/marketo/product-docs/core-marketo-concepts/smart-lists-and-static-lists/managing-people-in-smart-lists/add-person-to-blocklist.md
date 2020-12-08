---
unique-page-id: 9438139
description: Persoon toevoegen aan Lijst van afgewezen personen - Marketo Docs - Productdocumentatie
title: Persoon toevoegen aan Lijst van afgewezen personen
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '216'
ht-degree: 0%

---


# Persoon toevoegen aan Lijst van afgewezen personen {#add-person-to-blocklist}

Als u mensen aan uw Lijst van afgewezen personen toevoegt, kunnen ze uw correspondentie niet ontvangen.

>[!NOTE]
>
>Marketo is bezig met het wijzigen van termen als Blacklist en Whitelist in de Lijst van afgewezen personen en Lijst van gewenste personen in ons product. Tijdens deze update ziet u mogelijk de oude termen in onze gebruikersinterface en documentatiescherm en de nieuwe termen in onze documentatietekst. Onze excuses voor de verwarring.

1. [Creeer een nieuw standaardprogramma](../../../../product-docs/core-marketo-concepts/programs/creating-programs/create-a-program.md) en noem het **Toevoegen aan Lijst van afgewezen personen**.
1. Klik op **Nieuw** en selecteer **Nieuw lokaal element**.

   ![](assets/image2015-8-14-11-3a0-3a46.png)

1. Geef een naam op voor de lijst en klik op **Maken**.

   ![](assets/image2015-8-14-11-3a2-3a26.png)

1. Voeg alle mensen aan uw **Slimme Lijst** toe u aan uw Lijst van afgewezen personen wilt toevoegen.

   >[!NOTE]
   >
   >Personen op je Lijst van afgewezen personen ontvangen geen e-mails met een normale werking.

   ![](assets/three-6.png)

1. Klik op **Nieuw** en selecteer **Nieuwe slimme campagne**.

   ![](assets/image2015-8-14-11-3a12-3a35.png)

1. Geef een naam op voor de **nieuwe slimme campagne**. Klik op **Maken**.

   ![](assets/image2015-8-14-11-3a13-3a36.png)

1. Sleep **Lid van Slimme Lijst** en laat vallen.

   ![](assets/image2015-8-14-11-3a16-3a34.png)

1. Selecteer de slimme lijst die u net hebt gemaakt.

   ![](assets/image2015-8-14-11-3a17-3a5.png)

1. De belemmering en laat vallen **Verandering Gegevenswaarde**.

   ![](assets/image2015-8-14-11-3a18-3a41.png)

1. Voor de **Stroom**, ga **Blok dat voor het** Attribuut **wordt vermeld in en reeks** Nieuwe Waarde **aan** waar ****.

   ![](assets/image2015-8-14-11-3a21-3a1.png)

1. Selecteer Eenmaal **uitvoeren op het tabblad** Schema ****.

   ![](assets/ten.png)

1. Selecteer **Nu** uitvoeren en klik op **Uitvoeren**.

   ![](assets/image2015-8-14-11-3a24-3a50.png)

   JA! Deze mensen zullen geen e-mails meer ontvangen.

   >[!TIP]
   >
   >Creeer een [trekker slimme campagne](../../../../product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/create-a-new-smart-campaign.md) gebruikend de Waarde **van Gegevens van de** Verandering met **Blok dat voor alle mensen in de toekomst waar** is die lijst van afgewezen personen-able attributen hebben.

