---
unique-page-id: 2360251
description: Abonnement opzeggen - Marketo Docs - Productdocumentatie bewerken
title: Bericht voor afmelden bewerken
exl-id: 68a3ebc1-b2c9-4e6c-bb13-e5a94c9596d2
feature: Email Setup
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '127'
ht-degree: 0%

---

# Bericht voor afmelden bewerken {#edit-the-unsubscribe-message}

>[!NOTE]
>
>**Vereiste Bevoegdheden Admin**

Wanneer u marketing e-mails (niet - [&#x200B; operationeel &#x200B;](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/make-an-email-operational.md)) verzendt, unsubscribe tekst en de verbindingen worden toegevoegd aan de bodem. U kunt de standaardinstellingen wijzigen. Zo gaat het.

## Waar moet u de bewerking uitvoeren? {#where-to-make-the-edit}

1. Ga naar de sectie **[!UICONTROL Admin]** .

   ![](assets/edit-the-unsubscribe-message-1.png)

1. Klik op **[!UICONTROL Email]**.

   ![](assets/edit-the-unsubscribe-message-2.png)

   >[!CAUTION]
   >
   >De volgende variabelen zijn van essentieel belang. Verwijder ze niet!
   >
   >* `%mkt_opt_out_prefix%`
   >* `mkt_unsubscribe=1&mkt_tok=##MKT_TOK##`

1. Bewerk de versies **[!UICONTROL Unsubscribe HTML]** en **[!UICONTROL Unsubscribe Text]** naar wens en klik op **[!UICONTROL Save Changes]** .

   ![](assets/edit-the-unsubscribe-message-3.png)

   Daar heb je het. _zorg ervoor om te testen!_ Je wilt niet dat je e-mails met marketingberichten verbroken zijn.

>[!TIP]
>
>U kunt de positie van unsubscribe HTML in uw e-mail aanpassen door [&#x200B; tokens &#x200B;](/help/marketo/product-docs/email-marketing/general/using-tokens/add-a-system-token-as-a-link-in-an-email.md) te gebruiken.

## Standaardtekst voor abonnement opzeggen {#default-unsubscribe-text}

Kopieer/plak het volgende als u ooit moet terugkeren naar het standaardsysteemabonnement:

[!UICONTROL Unsubscribe HTML] :
`<p><font face="Verdana" size="1">If you no longer wish to receive these emails, click on the following link: <a href="%mkt_opt_out_prefix%UnsubscribePage.html?mkt_unsubscribe=1&mkt_tok=##MKT_TOK##">Unsubscribe</a><br/></font></p>` [!UICONTROL Unsubscribe Text] :
`%mkt_opt_out_prefix%UnsubscribePage.html?mkt_unsubscribe=1&mkt_tok=##MKT_TOK##`

>[!MORELIKETHIS]
>
>[&#x200B; geef het &quot;Mening uit als Web-pagina&quot;Bericht &#x200B;](/help/marketo/product-docs/administration/email-setup/edit-the-view-as-web-page-message.md)
