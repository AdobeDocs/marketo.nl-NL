---
unique-page-id: 1900577
description: E-mailscripttoken maken - Marketo Docs - Productdocumentatie
title: Een e-mailscripttoken maken
exl-id: c7f8c3e0-6d64-4115-b9b6-261576360ba1
feature: Tokens
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '203'
ht-degree: 0%

---

# Een e-mailscripttoken maken {#create-an-email-script-token}

Voor gevorderde ontwikkelaars, kunt u {de manuscripten van de Snelheid van 0} [ in uw e-mails gebruiken. ](https://velocity.apache.org/engine/1.7/user-guide.html) Zo doe je het.

1. Ga naar **[!UICONTROL Marketing Activities]** .

   ![](assets/ma.png)

1. Zoek en selecteer een programma (Event, Default, of Engagement, enz.).

   ![](assets/image2014-9-17-22-3a21-3a24.png)

1. Sleep onder het tabblad **[!UICONTROL My Tokens]** in een **[!UICONTROL Email Script]** -token.

   ![](assets/image2014-9-17-22-3a21-3a29.png)

1. Geef uw e-mailscripttoken een naam en **[!UICONTROL Click to Edit]** de bijbehorende inhoud.

   ![](assets/image2014-9-17-22-3a21-3a46.png)

1. Gebruik de boomstructuur aan de rechterkant om tokens **[!UICONTROL Person]** , **[!UICONTROL Opportunity]** of **[!UICONTROL Custom Object]** in te slepen.

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

   * [ de Documentatie van Scripting van de Ontwikkelaars E-mail van Marketo ](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/email-scripting)
   * [ Gids van de Gebruiker van 0&rbrace; Snelheid](https://velocity.apache.org/engine/devel/user-guide.html)
   * [ Gids van de Verwijzing van 0&rbrace; Snelheid](https://velocity.apache.org/engine/devel/vtl-reference-guide.html)
   * [ de Hulpmiddelen Javadoc van de Snelheid &lbrace;](https://velocity.apache.org/tools/releases/2.0/javadoc/index.html)

1. Klik op **[!UICONTROL Save]** wanneer het script is voltooid.

   ![](assets/image2014-9-17-22-3a23-3a1.png)

1. Klik nogmaals op **[!UICONTROL Save]** .

   ![](assets/image2014-9-17-22-3a23-3a13.png)

Nu kunt u deze token gebruiken in uw e-mails. Het script wordt uitgevoerd telkens wanneer een e-mail wordt verzonden.

>[!MORELIKETHIS]
>
>[ voeg een Token van het Manuscript E-mail aan Uw E-mail toe ](/help/marketo/product-docs/email-marketing/general/using-tokens/add-an-email-script-token-to-your-email.md)
