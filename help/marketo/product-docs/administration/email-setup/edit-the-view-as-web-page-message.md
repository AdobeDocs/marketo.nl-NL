---
unique-page-id: 2360253
description: Bewerk het bericht "Weergeven als webpagina" - Marketo Docs - Productdocumentatie
title: Het bericht "Weergeven als webpagina" bewerken
exl-id: 5541fe6c-7297-4277-8355-ba7b4ac73e2e
source-git-commit: 2776969be44ba1a3d795e99986d10cf0470fb9e9
workflow-type: tm+mt
source-wordcount: '184'
ht-degree: 0%

---

# Het bericht &quot;Weergeven als webpagina&quot; bewerken {#edit-the-view-as-web-page-message}

Als u &quot;[Weergeven als webpagina](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md)&quot; tekst , hier is hoe.

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

## Het bericht &quot;Weergeven als webpagina&quot; bewerken {#edit-the-view-as-web-page-message-1}

1. Ga naar de **Beheer** gebied.

   ![](assets/edit-the-view-as-web-page-message-1.png)

1. Klikken **E-mail**.

   ![](assets/edit-the-view-as-web-page-message-2.png)

   >[!CAUTION]
   >
   >De volgende variabelen zijn essentieel. Verwijder ze niet!
   >
   >`%mkt_webview_url%?mkt_tok=##MKT_TOK##`
   >
   >Het tweede deel `##MKT_TOK##` Het is de munchkin cookie van die persoon. Het zorgt ervoor dat ze op de juiste wijze worden gekookt wanneer ze op de koppeling klikken.

1. Bewerk de **HTML weergeven als webpagina** en **Weergeven als tekst op webpagina** gewenste versies en klik op **Wijzigingen opslaan**.

   ![](assets/edit-the-view-as-web-page-message-3.png)

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
`<pre data-theme="Confluence">%mkt_webview_url%?mkt_tok=##MKT_TOK##</pre>`

Dat is het!
