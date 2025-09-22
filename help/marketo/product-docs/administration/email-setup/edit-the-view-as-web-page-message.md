---
unique-page-id: 2360253
description: Bewerk het bericht "Weergeven als webpagina" - Marketo Docs - Productdocumentatie
title: Het bericht "Weergeven als webpagina" bewerken
exl-id: 5541fe6c-7297-4277-8355-ba7b4ac73e2e
feature: Email Setup
source-git-commit: 65d607e279fb86b0816ccaec2f4bf3c69e309cb9
workflow-type: tm+mt
source-wordcount: '155'
ht-degree: 0%

---

# Het bericht &quot;Weergeven als webpagina&quot; bewerken {#edit-the-view-as-web-page-message}

Als u &quot;[ Mening als Web-pagina ](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md)&quot;tekst moet uitgeven, is hier hoe.

>[!NOTE]
>
>**Vereiste Bevoegdheden Admin**

## Het bericht &quot;Weergeven als webpagina&quot; bewerken {#edit-the-view-as-web-page-message-1}

1. Ga naar het **[!UICONTROL Admin]** -gebied.

   ![](assets/edit-the-view-as-web-page-message-1.png)

1. Klik op **[!UICONTROL Email]**.

   ![](assets/edit-the-view-as-web-page-message-2.png)

   >[!CAUTION]
   >
   >De volgende variabelen zijn van essentieel belang. Verwijder ze niet!
   >
   >`%mkt_webview_url%?mkt_tok=##MKT_TOK##`
   >
   >Het tweede deel `##MKT_TOK##` is het [!UICONTROL munchkin] cookie van die persoon. Het zorgt ervoor dat ze op de juiste wijze worden gekookt wanneer ze op de koppeling klikken.

1. Bewerk de versies **[!UICONTROL View as Web Page HTML]** en **[!UICONTROL View as Web Page Text]** naar wens en klik op **[!UICONTROL Save Changes]** .

   ![](assets/edit-the-view-as-web-page-message-3.png)

>[!CAUTION]
>
>Zorg ervoor dat u:
>
>* Extra URL&#39;s toevoegen aan een van de HTML-vakken
>* HTML in de tekstversie plaatsen

Daar heb je het. Test-e-mails verzenden om de opmaak te controleren.

## Standaardtekst &quot;Weergeven als webpagina&quot; {#default-view-as-web-page-text}

Als u ooit aan standaardsysteem &quot;[!UICONTROL View as Web Page]&quot;moet terugkeren, kopieer/kleef het volgende:

**[!UICONTROL View as Web Page HTML]**:

`<div style="text-align: center"><font face="Verdana" size="1">To view this email as a web page, <a href="%mkt_webview_url%?mkt_tok=##MKT_TOK##">click here</a></font></div>`

**[!UICONTROL View as Web Page Text]**:

Ga naar het volgende adres om deze e-mail als webpagina weer te geven:
`%mkt_webview_url%?mkt_tok=##MKT_TOK##`

Dat is het!
