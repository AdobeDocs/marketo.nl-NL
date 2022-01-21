---
unique-page-id: 2360251
description: Abonnement opzeggen - Marketo Docs - Productdocumentatie bewerken
title: Bericht voor afmelden bewerken
exl-id: 68a3ebc1-b2c9-4e6c-bb13-e5a94c9596d2
source-git-commit: 931b42d7266b9c57308567527042dfcad9847993
workflow-type: tm+mt
source-wordcount: '135'
ht-degree: 0%

---

# Bericht voor afmelden bewerken {#edit-the-unsubscribe-message}

>[!NOTE]
>
>**Beheerdersmachtigingen vereist**

Wanneer u marketinge-mails verzendt (niet-[operationeel](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/make-an-email-operational.md)), wordt tekst afgebroken en worden koppelingen onderaan toegevoegd. U kunt de standaardinstellingen wijzigen. Zo gaat het.

## Bericht voor afmelden bewerken {#edit-the-unsubscribe-message-1}

1. Onder **Beheer**, klikt u op **E-mail**.

   ![](assets/image2014-9-18-16-3a52-3a1.png)

   >[!CAUTION]
   >
   >De volgende variabelen zijn essentieel. Verwijder ze niet!
   >
   >* `%mkt_opt_out_prefix%`
   >* `mkt_unsubscribe=1&mkt_tok=##MKT_TOK##`


1. Bewerk de **Abonnement op HTML opzeggen** en **Tekst afmelden** gewenste versies en klik op **Wijzigingen opslaan**.

   ![](assets/image2016-8-26-13-3a40-3a55.png)

   Daar heb je het. _Test zeker!_ Je wilt niet dat je e-mails met marketingberichten verbroken zijn.

>[!TIP]
>
>U kunt de positie van de HTML van het abonnement in uw e-mail aanpassen door te gebruiken [tokens](/help/marketo/product-docs/email-marketing/general/using-tokens/add-a-system-token-as-a-link-in-an-email.md).

## Standaardtekst voor abonnement opzeggen {#default-unsubscribe-text}

Kopieer/plak het volgende als u ooit moet terugkeren naar het standaardsysteemabonnement:

Abonnement op HTML opzeggen:
`<pre data-theme="Confluence"><p><font face="Verdana" size="1">If you no longer wish to receive these emails, click on the following link: <a href="%mkt_opt_out_prefix%UnsubscribePage.html?mkt_unsubscribe=1&mkt_tok=##MKT_TOK##">Unsubscribe</a><br/></font></p></pre>` Tekst afmelden:
`<pre data-theme="Confluence">%mkt_opt_out_prefix%UnsubscribePage.html?mkt_unsubscribe=1&mkt_tok=##MKT_TOK##</pre>`

>[!MORELIKETHIS]
>
>[Het bericht &quot;Weergeven als webpagina&quot; bewerken](/help/marketo/product-docs/administration/email-setup/edit-the-view-as-web-page-message.md)
