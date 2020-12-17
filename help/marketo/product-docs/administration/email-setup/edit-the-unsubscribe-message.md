---
unique-page-id: 2360251
description: Het Abonnement opzeggen - Marketo Docs - Productdocumentatie bewerken
title: Bericht voor afmelden bewerken
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '145'
ht-degree: 0%

---


# Het opnamebericht {#edit-the-unsubscribe-message} bewerken

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

Wanneer u marketinge-mails verzendt (niet- [operationeel](../../../product-docs/email-marketing/general/functions-in-the-editor/make-an-email-operational.md)), worden de tekst en koppelingen voor het afmelden aan de onderkant toegevoegd. U kunt de standaardinstellingen wijzigen. Zo gaat het.

## Het opnamebericht {#edit-the-unsubscribe-message-1} bewerken

1. Klik onder **Admin** op **E-mail**.

   ![](assets/image2014-9-18-16-3a52-3a1.png)

   >[!CAUTION]
   >
   >
   >De volgende variabelen zijn essentieel. Verwijder ze niet!
   >
   >    
   >    
   >    * **%mkt_opt_out_prefix%**
   >    * **mkt_unsubscribe=1&amp;mkt_tok=##MKT_TOK#**


1. Bewerk de **Abonnement op HTML opzeggen** en **Tekstversie opzeggen** naar wens en klik op **Wijzigingen opslaan**.

   ![](assets/image2016-8-26-13-3a40-3a55.png)

   Daar heb je het. **Test zeker!** Je wilt niet dat je e-mails met marketingberichten verbroken zijn.

>[!TIP]
>
>U kunt de positie van het afmelden van HTML in uw e-mail aanpassen door [tokens](../../../product-docs/email-marketing/general/using-tokens/add-a-system-token-as-a-link-in-an-email.md) te gebruiken.

## Standaardtekst voor afmelden {#default-unsubscribe-text}

Kopieer/plak het volgende als u ooit moet terugkeren naar het standaardsysteemabonnement:

Abonnement op HTML opzeggen:
`<pre data-theme="Confluence"><p><font face="Verdana" size="1">If you no longer wish to receive these emails, click on the following link: <a href="%mkt_opt_out_prefix%UnsubscribePage.html?mkt_unsubscribe=1&mkt_tok=##MKT_TOK##">Unsubscribe</a><br/></font></p></pre>` Tekst opzeggen:
`<pre data-theme="Confluence">%mkt_opt_out_prefix%UnsubscribePage.html?mkt_unsubscribe=1&mkt_tok=##MKT_TOK##</pre>`

>[!MORELIKETHIS]
>
>* [Het bericht &quot;Weergeven als webpagina&quot; bewerken](edit-the-view-as-web-page-message.md)

>



