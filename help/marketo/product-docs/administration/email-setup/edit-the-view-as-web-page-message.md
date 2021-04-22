---
unique-page-id: 2360253
description: Bewerk het bericht "Weergeven als webpagina" - Marketo Docs - Productdocumentatie
title: Het bericht "Weergeven als webpagina" bewerken
exl-id: 5541fe6c-7297-4277-8355-ba7b4ac73e2e
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '182'
ht-degree: 0%

---

# Bewerk het bericht &quot;Weergeven als webpagina&quot; {#edit-the-view-as-web-page-message}

Als u &quot;[View als WebPage](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md)&quot;tekst moet uitgeven, is hier hoe.

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

## Bewerk het bericht &quot;Weergeven als webpagina&quot; {#edit-the-view-as-web-page-message-1}

1. Klik onder **Admin** op **E-mail**.

   ![](assets/image2014-9-18-17-3a13-3a2.png)

   >[!CAUTION]
   >
   >De volgende variabelen zijn essentieel. Verwijder ze niet!
   >
   >`%mkt_webview_url%?mkt_tok=##MKT_TOK##`
   >
   >Het tweede deel `##MKT_TOK##` is het ingewanden koekje van die persoon. Het zorgt ervoor dat ze op de juiste wijze worden gekookt wanneer ze op de koppeling klikken.

1. Bewerk de **Weergave als webpagina HTML** en **Weergeven als webpaginatekst** versies naar wens en klik op **Wijzigingen opslaan**.

   ![](assets/image2016-8-26-14-3a40-3a29.png)

>[!CAUTION]
>
>Zorg ervoor dat u:
>
>* Extra URL&#39;s toevoegen aan een van de HTML-vakken
>* HTML in de tekstversie plaatsen


Daar heb je het. Test-e-mails verzenden om de opmaak te controleren.

## Standaardtekst &quot;Weergeven als webpagina&quot; {#default-view-as-web-page-text}

Als u ooit aan standaardsysteem &quot;Mening als Web-pagina&quot;moet terugkeren, kopieer/kleef het volgende:

**Weergeven als HTML van webpagina:**

`<pre data-theme="Confluence"><div style="text-align: center"><font face="Verdana" size="1">To view this email as a web page, <a href="%mkt_webview_url%?mkt_tok=##MKT_TOK##">click here</a></font></div></pre>`

**Weergeven als tekst op webpagina:**

Ga naar het volgende adres om deze e-mail als webpagina weer te geven:
`<pre data-theme="Confluence">%mkt_webview_url%?mkt_tok=##MKT_TOK##</pre>` Zoomen! Je bent klaar.
