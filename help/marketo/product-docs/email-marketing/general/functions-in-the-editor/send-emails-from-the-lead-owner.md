---
unique-page-id: 1147340
description: E-mails verzenden van de eigenaar van de lead - Marketo Docs - Productdocumentatie
title: E-mails verzenden vanuit de eigenaar van de lead
exl-id: b7ceb976-f52f-4134-8b7e-1c18d09af5de
feature: Email Editor
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '183'
ht-degree: 0%

---

# E-mails verzenden vanuit de eigenaar van de lead {#send-emails-from-the-lead-owner}

Wat als u een e-mail naar een lead namens de Lead Owner wilt sturen?  Zo gaat het.

1. Zoek de e-mail, selecteer deze en klik op **[!UICONTROL Edit Draft]** .

   ![](assets/one.png)

1. Klik op het **[!UICONTROL From]** gebied (schrap om het even welke bestaande naam), en klik **Symbolische** knoop van het Tussenvoegsel.

   ![](assets/two.png)

1. Typ &quot;`{{lead.Lead Owner`&quot; en selecteer het token **`{{lead.Lead Owner First Name}}`** .

   ![](assets/image2014-9-11-13-3a7-3a43.png)

1. Voer een standaardwaarde in voor het geval dat de lead nog geen eigenaar van de lead heeft en klik op **[!UICONTROL Insert]** .

   ![](assets/image2014-9-11-13-3a7-3a58.png)

1. Klik na het eerste teken, voeg een ruimte toe, dan klik het **Symbolische** knoop van het Tussenvoegsel.

   ![](assets/five.png)

1. Typ &quot;`{{lead.Lead Owner`&quot; en selecteer het token **`{{lead.Lead Owner Last Name}}`** .

   ![](assets/image2014-9-11-13-3a8-3a24.png)

1. Voer een standaardwaarde in voor het geval dat de lead nog geen eigenaar van de lead heeft en klik op **[!UICONTROL Insert]** .

   ![](assets/image2014-9-11-13-3a8-3a39.png)

   >[!TIP]
   >
   >Zorg ervoor dat u ruimte hebt toegevoegd tussen de tokens voor de voornaam en achternaam.

1. Klik op het **[!UICONTROL From Address]** gebied (schrap om het even welk bestaand e-mailadres), en klik de **Symbolische knoop van het Tussenvoegsel**.

   ![](assets/eight.png)

1. Typ &quot;`{{lead.Lead Owner`&quot; en selecteer het token **`{{lead.Lead Owner Email Address}}`** .

   ![](assets/image2014-9-11-13-3a9-3a33.png)

1. Voer een standaardwaarde in voor het geval dat de lead nog geen eigenaar van de lead heeft en klik op **[!UICONTROL Insert]** .

   ![](assets/ten.png)

1. Zorg ervoor dat de velden **[!UICONTROL Reply-to]** en **[!UICONTROL Subject]** zijn ingevuld en dat u klaar bent!

   ![](assets/eleven.png)
