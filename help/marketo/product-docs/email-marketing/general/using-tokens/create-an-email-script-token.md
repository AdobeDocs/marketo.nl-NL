---
unique-page-id: 1900577
description: E-mailscripttoken maken - Marketo Docs - Productdocumentatie
title: Een e-mailscripttoken maken
translation-type: tm+mt
source-git-commit: 0f0217a88929661798015b51a26259a973f9f6ea
workflow-type: tm+mt
source-wordcount: '235'
ht-degree: 0%

---


# Een e-mailscripttoken maken {#create-an-email-script-token}

Voor gevorderde ontwikkelaars, kunt u [manuscripten ](https://velocity.apache.org/engine/1.7/user-guide.html) in uw e-mail gebruiken. Zo doe je het.

1. Ga naar **Marketingactiviteiten**.

   ![](assets/ma.png)

1. Zoek en selecteer een programma (Event, Default, of Engagement, enz.).

   ![](assets/image2014-9-17-22-3a21-3a24.png)

1. Onder **Mijn tokens** tabel, sleep in een **E-mailmanuscript** teken.

   ![](assets/image2014-9-17-22-3a21-3a29.png)

1. Noem uw e-mailmanuscriptteken en **klik om** zijn inhoud uit te geven.

   ![](assets/image2014-9-17-22-3a21-3a46.png)

1. Gebruik de boom op het recht om in **Person, Opportunity**, of **Aangepast Voorwerp** tokens te slepen.

   ![](assets/five-2.png)

   >[!NOTE]
   >
   >Wanneer u een array (opportunity of aangepast object) opent, beperkt u zich tot de meest recente 10 items die aan de persoon zijn gekoppeld.

1. Het token wordt ingeschakeld/actief nadat u het naar de scripteditor hebt gesleept.

   ![](assets/image2014-9-17-22-3a22-3a33.png)

   >[!NOTE]
   >
   >Als u tokens typt, moet u ervoor zorgen dat alle corresponderende tokens in de structuur worden gecontroleerd/geactiveerd. Als u dit niet doet, worden deze ook beschouwd als normale tekst en werken ze niet.

1. Schrijf uw script in Snelheid. Hier volgen enkele nuttige bronnen:

   * [Documenten met e-mailscripts voor Marketo Developers](https://developers.marketo.com/email-scripting/)
   * [Gebruikershandleiding voor snelheid](https://velocity.apache.org/engine/devel/user-guide.html)
   * [Snelheidsnaslaggids](https://velocity.apache.org/engine/devel/vtl-reference-guide.html)
   * [Velocity Tools Javadoc](https://velocity.apache.org/tools/releases/2.0/javadoc/index.html)

1. Zodra uw manuscript wordt voltooid, klik **sparen**.

   ![](assets/image2014-9-17-22-3a23-3a1.png)

1. Klik nog een keer op **Opslaan**.

   ![](assets/image2014-9-17-22-3a23-3a13.png)

Nu kunt u deze token gebruiken in uw e-mails. Het script wordt uitgevoerd telkens wanneer een e-mail wordt verzonden.

>[!MORELIKETHIS]
>
>[Een e-mailscripttoken toevoegen aan uw e-mail](/help/marketo/product-docs/email-marketing/general/using-tokens/add-an-email-script-token-to-your-email.md)
