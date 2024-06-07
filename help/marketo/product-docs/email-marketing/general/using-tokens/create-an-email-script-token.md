---
unique-page-id: 1900577
description: E-mailscripttoken maken - Marketo Docs - Productdocumentatie
title: Een e-mailscripttoken maken
exl-id: c7f8c3e0-6d64-4115-b9b6-261576360ba1
feature: Tokens
source-git-commit: 2b610cc3486b745212b0b1f36018a83214d7ecd7
workflow-type: tm+mt
source-wordcount: '218'
ht-degree: 0%

---

# Een e-mailscripttoken maken {#create-an-email-script-token}

Voor gevorderde ontwikkelaars kunt u [Snelheidsscripts](https://velocity.apache.org/engine/1.7/user-guide.html) in uw e-mails. Zo doe je het.

1. Ga naar **Marketingactiviteiten**.

   ![](assets/ma.png)

1. Zoek en selecteer een programma (Event, Default, of Engagement, enz.).

   ![](assets/image2014-9-17-22-3a21-3a24.png)

1. Onder de **Mijn tokens** tabblad, slepen in een **E-mailscript** token.

   ![](assets/image2014-9-17-22-3a21-3a29.png)

1. Noem uw e-mailscripttoken en **klik om te bewerken** de inhoud ervan.

   ![](assets/image2014-9-17-22-3a21-3a46.png)

1. De boomstructuur aan de rechterkant gebruiken om in te slepen **Persoon, Opportunity**, of **Aangepast object** tokens.

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

   * [Marketo Developers Email Scripting Documentation](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/email-scripting)
   * [Gebruikershandleiding voor snelheid](https://velocity.apache.org/engine/devel/user-guide.html)
   * [Snelheidsnaslaggids](https://velocity.apache.org/engine/devel/vtl-reference-guide.html)
   * [Velocity Tools Javadoc](https://velocity.apache.org/tools/releases/2.0/javadoc/index.html)

1. Wanneer het script is voltooid, klikt u op **Opslaan**.

   ![](assets/image2014-9-17-22-3a23-3a1.png)

1. Klikken **Opslaan** nog een keer.

   ![](assets/image2014-9-17-22-3a23-3a13.png)

Nu kunt u deze token gebruiken in uw e-mails. Het script wordt uitgevoerd telkens wanneer een e-mail wordt verzonden.

>[!MORELIKETHIS]
>
>[Een e-mailscripttoken toevoegen aan uw e-mail](/help/marketo/product-docs/email-marketing/general/using-tokens/add-an-email-script-token-to-your-email.md)
