---
unique-page-id: 1900554
description: HTML van e-mail bewerken - Marketo Docs - Productdocumentatie
title: HTML van een e-mail bewerken
translation-type: tm+mt
source-git-commit: 0f0217a88929661798015b51a26259a973f9f6ea
workflow-type: tm+mt
source-wordcount: '347'
ht-degree: 0%

---


# HTML {#edit-an-emails-html} van een e-mail bewerken

Soms moet u de onderliggende HTML van een e-mail wijzigen. Soms kunt u een extern systeem gebruiken om de code van uw e-mail te ontwerpen en te bouwen. In beide gevallen kunt u gemakkelijk code importeren en/of bewerken vanuit de e-maileditor.

## HTML {#edit-html} bewerken

1. Selecteer uw e-mail en klik **Concept** uitgeven.

   ![](assets/teamspidey.jpg)

1. Klik **Code bewerken**.

   ![](assets/two-4.png)

1. Breng de gewenste wijzigingen aan. Klik **Opslaan** wanneer gereed.

   ![](assets/three-3.png)

   >[!NOTE]
   >
   >Wijzig wat je wilt. U kunt de volledige HTML vervangen of kleine aanpassingen aanbrengen.

1. Klik op de vervolgkeuzelijst **Codehandelingen** om de code te downloaden als een HTML-bestand, uw CSS in te line of de HTML te valideren.

   ![](assets/four-2.png)

   >[!NOTE]
   >
   >De beste manier voor e-mails is om al uw stijlen inline te maken. Verschillende e-mailclients ondersteunen geen CSS in de sectie `<head>`.

## Een e-mail opsplitsen via de sjabloon {#breaking-an-email-from-its-template}

Met deze codewijzigingen **wordt een e-mailbericht niet** uit de sjabloon verbroken:

* De inhoud van een willekeurige module bewerken (inclusief het toevoegen van nieuwe elementen in de module)
* Een nieuwe module toevoegen aan de container
* Een module verwijderen uit de container

* Het veranderen van mkto-specifieke attributen (bijvoorbeeld, &quot;mktoName&quot;of &quot;mktoImgUrl&quot;) van om het even welk Element buiten een Module
* De inhoud van een willekeurig element bewerken (RTF-bestand, afbeelding, video, enz.) buiten een module

Deze dingen u in de code redacteur **zal** e-mail van zijn malplaatje breken:

* Alles wijzigen in de code buiten een Element of Module
* Niet-mkto-kenmerken (bijvoorbeeld &quot;id&quot; of &quot;style&quot;) van een element buiten een module toevoegen of wijzigen
* Een element verwijderen dat zich buiten een module bevindt

## Zoeken in code {#search-code}

Met de functie Code zoeken kunt u op efficiënte wijze inhoud in de HTML-code van uw e-mail zoeken en vervangen.

1. Klik in de code van uw e-mail op **Code zoeken**.

   ![](assets/five-2.png)

1. Voer in wat u wilt zoeken en klik op **Volgende zoeken** om naar voren te zoeken of **Vorige zoeken** om naar achteren te zoeken. U kunt ook **Vervangen** en **Alles vervangen** kiezen.

   ![](assets/six-1.png)

1. Klik **Sluiten** wanneer gereed.

   ![](assets/seven.png)

   >[!NOTE]
   >
   >Zoekcode is ook beschikbaar in de [E-mailsjablooneditor](/help/marketo/product-docs/email-marketing/general/email-editor-2/create-an-email-template.md).

We raden u aan uw e-mailberichten te blijven bewerken met de ingebouwde functionaliteit van Marketo, maar deze code-editor biedt wel flexibiliteit als dat nodig is.
