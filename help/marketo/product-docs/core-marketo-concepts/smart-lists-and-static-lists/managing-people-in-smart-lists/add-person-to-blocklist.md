---
unique-page-id: 9438139
description: Persoon toevoegen aan Lijst van gewezen personen - Marketo Docs - Productdocumentatie
title: Persoon toevoegen aan Lijst van gewezen personen
exl-id: e4543bf9-11e9-42df-a31e-e2cebe24ad4a
feature: Smart Lists
source-git-commit: cc87ecb8d3245734ec0ce984eeccf742833a85d2
workflow-type: tm+mt
source-wordcount: '184'
ht-degree: 0%

---

# Persoon toevoegen aan Lijst van gewezen personen {#add-person-to-blocklist}

Als u mensen aan uw Lijst van gewezen personen toevoegt, kunnen ze uw correspondentie niet ontvangen.

1. [Een nieuw standaardprogramma maken](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/create-a-program.md) en noem deze **Toevoegen aan Lijst van gewezen personen**.

1. Klikken **Nieuw** en selecteert u **Nieuw lokaal element**.

   ![](assets/add-person-to-blocklist-1.png)

1. Selecteren **Slimme lijst**.

   ![](assets/add-person-to-blocklist-2.png)

1. Geef uw lijst een naam en klik op **Maken**.

   ![](assets/add-person-to-blocklist-3.png)

1. Voeg alle mensen toe aan uw **Slimme lijst** u wilt toevoegen aan uw Lijst van gewezen personen.

   ![](assets/add-person-to-blocklist-4.png)

   >[!NOTE]
   >
   >Personen op je Lijst van gewezen personen ontvangen geen e-mails met een normale werking.

1. Ga terug naar uw programma.

   ![](assets/add-person-to-blocklist-5.png)

1. Klikken **Nieuw** en selecteert u **Nieuwe slimme campagne**.

   ![](assets/add-person-to-blocklist-6.png)

1. Geef de naam **Nieuwe slimme campagne**. Klikken **Maken**.

   ![](assets/add-person-to-blocklist-7.png)

1. Slepen en slepen **Lid van slimme lijst**.

   ![](assets/add-person-to-blocklist-8.png)

1. Selecteer de slimme lijst die u net hebt gemaakt.

   ![](assets/add-person-to-blocklist-9.png)

1. Klik op de knop **Stroom** tab. Sleep de **Gegevenswaarde wijzigen** Flow-actie.

   ![](assets/add-person-to-blocklist-10.png)

1. In de **Kenmerk** vervolgkeuzelijst **Aangeboden blokkeren** en instellen **Nieuwe waarde** tot **true**.

   ![](assets/add-person-to-blocklist-11.png)

1. Klik op de knop **Schema** en selecteert u **Eenmaal uitvoeren**.

   ![](assets/add-person-to-blocklist-12.png)

1. Selecteren **Nu uitvoeren** en klik op **Uitvoeren**.

   ![](assets/add-person-to-blocklist-13.png)

1. Klikken **Uitvoeren** opnieuw.

   ![](assets/add-person-to-blocklist-14.png)

Deze mensen zullen geen e-mails meer ontvangen.

>[!TIP]
>
>Een [slimme campagne activeren](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/create-a-new-smart-campaign.md) gebruiken **Gegevenswaarde wijzigen** with **Blok aangeboden is waar** voor alle mensen in de toekomst die kenmerken hebben die geschikt zijn voor lijst van gewezen personen.
