---
unique-page-id: 9438139
description: Persoon toevoegen aan Lijst van gewezen personen - Marketo Docs - Productdocumentatie
title: Persoon toevoegen aan Lijst van gewezen personen
exl-id: e4543bf9-11e9-42df-a31e-e2cebe24ad4a
feature: Smart Lists
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '150'
ht-degree: 0%

---

# Persoon toevoegen aan Lijst van gewezen personen {#add-person-to-blocklist}

Als u mensen aan uw Lijst van gewezen personen toevoegt, kunnen ze uw correspondentie niet ontvangen.

1. Creeer een nieuw [ standaardprogramma ](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/create-a-program.md){target="_blank"} en noem het &quot;toevoegen aan Lijst van gewezen personen.&quot;

1. Klik op **[!UICONTROL New]** en selecteer **[!UICONTROL New Local Asset]** .

   ![](assets/add-person-to-blocklist-1.png)

1. Selecteer **[!UICONTROL Smart List]** .

   ![](assets/add-person-to-blocklist-2.png)

1. Geef een naam op voor de lijst en klik op **[!UICONTROL Create]** .

   ![](assets/add-person-to-blocklist-3.png)

1. Voeg alle mensen aan uw Slimme Lijst toe u aan uw Lijst van gewezen personen wilt toevoegen.

   ![](assets/add-person-to-blocklist-4.png)

   >[!NOTE]
   >
   >Personen op je Lijst van gewezen personen ontvangen geen e-mails met een normale werking.

1. Ga terug naar uw programma.

   ![](assets/add-person-to-blocklist-5.png)

1. Klik op **[!UICONTROL New]** en selecteer **[!UICONTROL New Smart Campaign]** .

   ![](assets/add-person-to-blocklist-6.png)

1. Geef de nieuwe slimme campagne een naam. Klik op **[!UICONTROL Create]**.

   ![](assets/add-person-to-blocklist-7.png)

1. Sleep **[!UICONTROL Member of Smart List]** .

   ![](assets/add-person-to-blocklist-8.png)

1. Selecteer de slimme lijst die u net hebt gemaakt.

   ![](assets/add-person-to-blocklist-9.png)

1. Klik op de tab **[!UICONTROL Flow]** . Sleep de **[!UICONTROL Change Data Value]** Flow-actie en zet deze neer.

   ![](assets/add-person-to-blocklist-10.png)

1. Selecteer **[!UICONTROL Attribute]** in de vervolgkeuzelijst **[!UICONTROL Block Listed]** en stel **[!UICONTROL New Value]** in op **[!UICONTROL true]** .

   ![](assets/add-person-to-blocklist-11.png)

1. Klik op de tab **[!UICONTROL Schedule]** en selecteer **[!UICONTROL Run Once]** .

   ![](assets/add-person-to-blocklist-12.png)

1. Selecteer **[!UICONTROL Run Now]** en klik op **[!UICONTROL Run]** .

   ![](assets/add-person-to-blocklist-13.png)

1. Klik nogmaals op **[!UICONTROL Run]** .

   ![](assets/add-person-to-blocklist-14.png)

Deze mensen zullen geen e-mails meer ontvangen.

>[!TIP]
>
>Creeer de Campagne van de a [ Trigger ](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/create-a-new-smart-campaign.md){target="_blank"} gebruikend **de Waarde van Gegevens van de Verandering** met **Voorgeschreven Blok is waar** voor alle mensen in de toekomst die lijst van gewezen personen-geschikte attributen hebben.
