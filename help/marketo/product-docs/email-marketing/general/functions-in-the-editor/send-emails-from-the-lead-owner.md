---
unique-page-id: 1147340
description: E-mails verzenden van de eigenaar van de lead - Marketo Docs - Productdocumentatie
title: E-mails verzenden vanuit de eigenaar van de lead
translation-type: tm+mt
source-git-commit: 5c9683c6b00ccbf9e9d606fd4513432c9872ad00
workflow-type: tm+mt
source-wordcount: '193'
ht-degree: 0%

---


# E-mails verzenden vanuit de eigenaar van de lead {#send-emails-from-the-lead-owner}

Wat als u een e-mail naar een lead namens de Lead Owner wilt sturen?  Zo gaat het.

1. Zoek uw e-mail, selecteer het en klik **uitgeven Ontwerp**.

   ![](assets/one.png)

1. Klik in het veld **Van** (verwijder een bestaande naam) en klik op de knop Token **** invoegen.

   ![](assets/two.png)

1. Typ &quot;`{{lead.Lead Owner`&quot; en selecteer het **`{{lead.Lead Owner First Name}}`** token.

   ![](assets/image2014-9-11-13-3a7-3a43.png)

1. Voer een standaardwaarde in als de lead nog geen eigenaar van de lead heeft en klik op **Invoegen**.

   ![](assets/image2014-9-11-13-3a7-3a58.png)

1. Klik na het eerste token, voeg een spatie toe en klik op de knop **Token** invoegen.

   ![](assets/five.png)

1. Typ &quot;`{{lead.Lead Owner`&quot; en selecteer het **`{{lead.Lead Owner Last Name}}`** token.

   ![](assets/image2014-9-11-13-3a8-3a24.png)

1. Voer een standaardwaarde in als de lead nog geen eigenaar van de lead heeft en klik op **Invoegen**.

   ![](assets/image2014-9-11-13-3a8-3a39.png)

   >[!TIP]
   >
   >Zorg ervoor dat u ruimte hebt toegevoegd tussen de tokens voor de voornaam en achternaam.

   Klik in het veld Van e-mail (verwijder een bestaand e-mailadres) en klik op de knop Token invoegen.
   ![](assets/eight.png)

1. Typ &quot;`{{lead.Lead Owner`&quot; en selecteer het **`{{lead.Lead Owner Email Address}}`** token.

   ![](assets/image2014-9-11-13-3a9-3a33.png)

1. Voer een standaardwaarde in als de lead nog geen eigenaar van de lead heeft en klik op **Invoegen**.

   ![](assets/ten.png)

1. Zorg ervoor dat de velden **Reageren op** en **Onderwerp** zijn ingevuld en dat u klaar bent!

   ![](assets/eleven.png)

