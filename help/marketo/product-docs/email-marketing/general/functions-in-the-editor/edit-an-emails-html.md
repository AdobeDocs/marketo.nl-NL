---
unique-page-id: 1900554
description: HTML - Marketo-documenten - Productdocumentatie bewerken in een e-mail
title: HTML van e-mailberichten bewerken
exl-id: 9dc8e44d-d9da-4bc2-950f-3ffbb976f5d5
feature: Email Editor
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '330'
ht-degree: 0%

---

# HTML van e-mailberichten bewerken {#edit-an-emails-html}

Soms moet u de onderliggende HTML van een e-mailbericht wijzigen. Soms kunt u een extern systeem gebruiken om de code van uw e-mail te ontwerpen en te bouwen. In beide gevallen kunt u gemakkelijk code importeren en/of bewerken vanuit de e-maileditor.

## HTML bewerken {#edit-html}

1. Selecteer uw e-mail en klik op **[!UICONTROL Edit Draft]** .

   ![](assets/teamspidey.jpg)

1. Klik op **[!UICONTROL Edit Code]**.

   ![](assets/two-4.png)

1. Breng de gewenste wijzigingen aan. Klik op **[!UICONTROL Save]** als u klaar bent.

   ![](assets/three-3.png)

   >[!NOTE]
   >
   >Wijzig wat je wilt. U kunt de hele HTML vervangen of kleine aanpassingen aanbrengen.

1. Klik op de vervolgkeuzelijst **[!UICONTROL Code Actions]** om de code te downloaden als een HTML-bestand, uw CSS in te schakelen of de HTML te valideren.

   ![](assets/four-2.png)

   >[!NOTE]
   >
   >De beste manier voor e-mails is om al uw stijlen inline te maken. Verschillende e-mailclients ondersteunen CSS niet in de sectie `<head>` .

## Een e-mail verbreken via de sjabloon {#breaking-an-email-from-its-template}

Deze codeveranderingen **zullen** geen e-mail van zijn malplaatje breken:

* De inhoud van een willekeurige module bewerken (inclusief het toevoegen van nieuwe elementen in de module)
* Een nieuwe module toevoegen aan de container
* Een module verwijderen uit de container

* Het veranderen van mkto-specifieke attributen (bijvoorbeeld, &quot;mktoName&quot;of &quot;mktoImgUrl&quot;) van om het even welk Element buiten een Module
* De inhoud van een willekeurig element (opgemaakte tekst, afbeelding, video, enz.) buiten een module bewerken

Deze dingen u in de coderedacteur **kunt doen zullen** e-mail van zijn malplaatje breken:

* Alles wijzigen in de code buiten een Element of Module
* Niet-mkto-kenmerken (bijvoorbeeld &quot;id&quot; of &quot;style&quot;) van een element buiten een module toevoegen of wijzigen
* Een element verwijderen dat zich buiten een module bevindt

## Zoeken in code {#search-code}

Met de functie Code zoeken kunt u op efficiënte wijze inhoud zoeken en vervangen in de HTML-code van uw e-mail.

1. Klik in de e-mailcode op **[!UICONTROL Search Code]** .

   ![](assets/five-2.png)

1. Voer in wat u wilt zoeken en klik op **[!UICONTROL Find Next]** om naar voren te zoeken of op **[!UICONTROL Find Previous]** om naar achteren te zoeken. U kunt ook **[!UICONTROL Replace]** en **[!UICONTROL Replace All]** kiezen.

   ![](assets/six-1.png)

1. Klik op **[!UICONTROL Close]** als u klaar bent.

   ![](assets/seven.png)

   >[!NOTE]
   >
   >De Code van het onderzoek is ook beschikbaar in de [ redacteur van het Malplaatje E-mail ](/help/marketo/product-docs/email-marketing/general/email-editor-2/create-an-email-template.md).

We raden u aan uw e-mailberichten te blijven bewerken met de ingebouwde Marketo-functionaliteit, maar deze code-editor biedt wel flexibiliteit als dat nodig is.
