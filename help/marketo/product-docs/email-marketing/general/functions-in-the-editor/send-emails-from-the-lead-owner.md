---
unique-page-id: 1147340
description: E-mails verzenden van de eigenaar van de lead - Marketo Docs - Productdocumentatie
title: E-mails verzenden vanuit de eigenaar van de lead
exl-id: b7ceb976-f52f-4134-8b7e-1c18d09af5de
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '193'
ht-degree: 0%

---

# E-mails verzenden vanuit de eigenaar van de lead {#send-emails-from-the-lead-owner}

Wat als u een e-mail naar een lead namens de Lead Owner wilt sturen?  Zo gaat het.

1. Uw e-mail zoeken, deze selecteren en klikken **Concept bewerken**.

   ![](assets/one.png)

1. Klik in het dialoogvenster **Van** (verwijder een bestaande naam) en klik op de knop **Token invoegen** knop.

   ![](assets/two.png)

1. Begin met typen &quot;`{{lead.Lead Owner`&quot; en selecteert u de **`{{lead.Lead Owner First Name}}`** token.

   ![](assets/image2014-9-11-13-3a7-3a43.png)

1. Voer een standaardwaarde in als de lead nog geen eigenaar van de lead heeft en klik op **Invoegen**.

   ![](assets/image2014-9-11-13-3a7-3a58.png)

1. Klik na het eerste token, voeg een spatie toe en klik vervolgens op de knop **Token invoegen** knop.

   ![](assets/five.png)

1. Begin met typen &quot;`{{lead.Lead Owner`&quot; en selecteert u de **`{{lead.Lead Owner Last Name}}`** token.

   ![](assets/image2014-9-11-13-3a8-3a24.png)

1. Voer een standaardwaarde in als de lead nog geen eigenaar van de lead heeft en klik op **Invoegen**.

   ![](assets/image2014-9-11-13-3a8-3a39.png)

   >[!TIP]
   >
   >Zorg ervoor dat u ruimte hebt toegevoegd tussen de tokens voor de voornaam en achternaam.

1. Klik in het veld Van e-mail (verwijder een bestaand e-mailadres) en klik op de knop Token invoegen.

   ![](assets/eight.png)

1. Begin met typen &quot;`{{lead.Lead Owner`&quot; en selecteert u de **`{{lead.Lead Owner Email Address}}`** token.

   ![](assets/image2014-9-11-13-3a9-3a33.png)

1. Voer een standaardwaarde in als de lead nog geen eigenaar van de lead heeft en klik op **Invoegen**.

   ![](assets/ten.png)

1. Zorg ervoor dat de **Antwoord aan** en **Onderwerp** de velden zijn gevuld en u bent klaar!

   ![](assets/eleven.png)
